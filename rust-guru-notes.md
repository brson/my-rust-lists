- How to rebase around Cargo.lock conflicts
- Option::flatten
            let src_time = src_path.metadata()
                .ok().map(|m| m.modified().ok()).flatten();
- PhantomData
- using cfg_attr for conditional lines of docs

    //! You can serialize types in a similar fashion:
    //!
    #![cfg_attr(not(feature = "display"), doc = " ```ignore")]
    #![cfg_attr(feature = "display", doc = " ```")]
    //! use serde::Serialize;

* `use foo::*` to avoid name collision errors
* `const _` trick
  - https://github.com/rust-lang/rfcs/blob/master/text/2526-const-wildcard.md
  - also used to create temporary scopes in macros
    - as in soroban arbitrary macros
* use unnamed imports to avoid trait name collisions: 'import Bytes as _'
* `use std::format as s` to succinctly create strings from strs
* a crate can exclude itself from a workspace

    # Prevent this from interfering with workspaces
    [workspace]
    members = ["."]

* `[workspace.package]`
* workspace dependencies
  - https://doc.rust-lang.org/nightly/cargo/reference/specifying-dependencies.html#inheriting-a-dependency-from-a-workspace
* `#![no_main]` allows linking to a C library that provides `main`
* Use extra braces (scopes `{ }`) for organization.
* `use unused as _`
  - for linking to a crate containing only C code
  - cargo-contract uses it to satisfy the unused_crate lint
  - just use `extern crate`?
* tuple matching
- getting async blocks to typecheck `?`
  - `Ok::<_, anyhow::Error>(())`
  - for async test cases
* test runner has its own flags
  - --nocapture
- rustc won't attempt to link other crates if they are not referenced
  - this can cause huge confusion of those other crates only contain c symbols
    since rustc won't pass them to the linker and they'll just disappear
* Sealed trait pattern
- cargo aliases
* cargo xtask
* #[path = ""] trick
    ```
    #[path = ""]
    mod non_bpf_modules {
        mod sanitized;
        mod versions;
    }
    ```

* #[non_exhaustive]
* shebang?!
  - https://github.com/rust-lang/rust/issues/1772
  - https://neosmart.net/blog/2020/self-compiling-rust-code/
- Should I end a function with a passthrough call or with `?; Ok(())`
- Following crates.io / docs.rs to GitHUb etc.
- `-- --test-threads=1` will print names of test cases before they hard-crash
* Ok(panic!()) instead of panic!() in async fns
* compile dependencies with optimizations in dev mode
  - https://www.reddit.com/r/rust/comments/gvrgca/this_is_a_neat_trick_for_getting_good_runtime/
- out-of-bound pointer math not ok
  - https://github.com/tikv/tikv/pull/7751/files/69b602a4a50370cf8f327116ec345a13c7083ce8
  - https://blog.regehr.org/archives/1518
- https://www.reddit.com/r/rust/comments/518gcs/whats_your_favorite_piece_of_rust_code/d7a3gs0/
* don't use unchecked functions just because you "know" the invariant holds (i.e. from_utf8_unchecked)
* remove_dir_all crate
- Arc::make_mut for copy-on-write
- {String}.as_ref().map(Borrow::borrow) -> &str
* count complete source lines with cargo vendor + tokei
- https://github.com/Hexilee/async-io-demo
- https://github.com/dtolnay/semver-trick
- https://medium.com/@edwardpku/being-an-intermediate-rust-programmer-in-one-day-37283bb1b0b0?from=timeline&isappinstalled=0
- ECS
- https://blog.rust-lang.org/2018/12/21/Procedural-Macros-in-Rust-2018.html
- https://rust-lang-nursery.github.io/api-guidelines/documentation.html
- https://rust-random.github.io/book/
- https://www.breakdown-notes.com/make/load/rust_cs_canvas/true
* criterion
- create rust pro tips
- https://docs.rs/arc-swap/0.3.7/arc_swap/
- cargo test --all --no-run
- cargo check --all --no-run --profile=dev
- do code review series ala https://www.youtube.com/channel/UC_BzFbxG2za3bp5NRRRXJSw
- what is the default matching scheme for unadorned version numbers in cargo
- how does cargo's crate resolution work?
- do 'stacked' cfg attributes 'or' and 'and'?
- what do you about repeated big cfgs?
- why do Rc and Arc have static clone methods?
- DSTs
- IRC channels
  - #rust
  - #rust-internals
  - #rust-beginners
  - libs?
- https://github.com/nrc/talks - 'thinking in rust'
- overflow
* turbofish
* Collection<Result<T>> -> Result<Collection<T>>
  - https://doc.rust-lang.org/stable/std/iter/trait.FromIterator.html#impl-FromIterator%3CResult%3CA%2C%20E%3E%3E
- https://stjepang.github.io/2019/01/29/lock-free-rust-crossbeam-in-2019.html
- https://github.com/japaric/rust-san
- sccache
- default fns vs 'defaut fn'
- https://github.com/servo/string-cache
- StdError, StdResult
- https://limpet.net/mbrubeck/2019/02/07/rust-a-unique-perspective.html
- https://doc.rust-lang.org/nomicon/aliasing.html
- https://manishearth.github.io/blog/2015/05/17/the-problem-with-shared-mutability/
- security
  - https://github.com/ANSSI-FR/rust-guide - secure applications
  - https://research.kudelskisecurity.com/2019/02/07/auditing-rust-crypto-the-first-hours/
- production case studies
  - https://www.rust-lang.org/production
  - https://www.reddit.com/r/rust/comments/aohq6u/rust_velocity_and_defect_rates/eg189gu/
- cargo-outdated, cargo-audit
- [package.metadata.docs.rs] (ala jemalloc crate)
- profiling
  - https://github.com/andikleen/pmu-tools
  - https://github.com/andikleen/pmu-tools/wiki/toplev-manual
  - https://github.com/RazrFalcon/cargo-bloat
  - cargo profile
  - twiggy, bloaty, objdump, nm, readelf
  - cargo-tree
  - https://dendibakh.github.io/blog/2019/02/09/Top-Down-performance-analysis-methodology
  - https://github.com/svenstaro/cargo-profiler
  - https://github.com/dignifiedquire/rust-gperftools
- cargo-vendor, cargo-local-registry
- cargo -v and cargo -vv
- software validation projects
  - https://github.com/blt/bughunt-rust
  - miri
- embedded rust
  - https://github.com/rust-embedded
  - https://github.com/rust-embedded/awesome-embedded-rust
- symbolic crate for minidump reporting
* println!("{:#?}", ...);
- CI building with --locked when Cargo.toml is checked in
* dbg!
- getset crate
- cargo-local-registry
* Struct { no, name, stuttering }
- what's in `target/`
  - `target/$profile` vs `target/$triple/$profile`
- ashley's template project
- cargo-apply
- cargo-dot
- full CI regime
  - cargo -Vv
  - rustc -Vv
  - rustup -Vv
  - cargo generate-lockfile
  - cargo fetch
  - cargo build --locked
  - cargo run --locked -Zoffline?
  - cargo-clippy, cargo-fmt, cargo-outdated, cargo-audit
- impl Into<Option<_>> argument pattern
- cargo-src
- code comment guidelines - TiKV has some
- windows stack size https://github.com/rust-lang/rust/blob/master/src/tools/rustdoc/main.rs#L6
- trait aliasing pattern https://docs.rs/pest/2.1.0/pest/iterators/struct.Pairs.html
- failure, vs quick_error!, vs error_type! vs error_chain!
- https://rufflewind.com/2017-02-15/rust-move-copy-borrow
- https://blog.adamant-lang.org/2019/rust-lifetime-visualization-ideas/
- intl news
  - rust.cc - chinese
    - https://github.com/RustStudy/rust_daily_news
    - run by @Chaos, author of one of the Chinese Rust books
* cloned() tricks
- difference between executor and reactor
- parallel
  - antidote - standard rust types w/o poisoning
  - parking lot
- lto vs thinlto
- oxide paper - https://arxiv.org/pdf/1903.00982.pdf
  - Mezzo and Alms
  - two-phase borrows
- deny_bare_trait_objects
- rust-2018-idioms tidy group
- panicking drops
  - by-val close + dtor bomb w/ thread::panicking
  - https://github.com/servo/servo/blob/master/components/layout/context.rs#L93
  - https://gist.github.com/brson/4ab0526baab38972bccdfb60ef7a9bd9
- what's inside target/?
  - build script output:
    - build/$pkg/output, stderr, out
* turn default features off for deps if possible
  - otherwise they can't be turned off by other crates
  - default features considered harmful
- cargo search
- AsRef vs Borrow
* iterator cloned() vs borrowed()
* Path::display()
- tip: be curious about the crates scrolling by when you compile
- where to find the answers to common questions?
  - https://rust-lang-nursery.github.io/api-guidelines/documentation.html#documentation
  - cargo env vars
- qualify function calls, fs::read_dir_all
- fs_extra
- compile_error!
- http://pling.jondgoodwin.com/post/lifetimes/
- https://docs.rs/snafu/0.2.3/snafu/guide/index.html
- https://crates.io/crates/err-derive
- https://github.com/rust-lang-nursery/rust-cookbook/issues/502 re errors
- future combinators need to return the same error type as the previous future
  - need to call map_err(Error::from) _before_ changing the error type
- how can i list all defined cfgs?
- panic_hook runs even with panic=abort
- try test --all for new projects
- moves are not free
- str.parse() is magic
- https://github.com/dtolnay/case-studies (macros)
- rustc --print cfg / target-cpus / target-features
- rustc -C target-cpu / target-feature
- *.rlo
* don't jump to lifetimes
  - even graydon doesn't
- https://learning-rust.github.io/
- https://www.youtube.com/watch?v=N6b44kMS6OM
- first rust presentation http://venge.net/graydon/talks/intro-talk-2.pdf
* drop impacts API - re serde Value recursion
- impl Trait "leaks" Send/Sync https://twitter.com/Gankro/status/1141413230905966593?s=09
- concurrent map tests https://gitlab.nebulanet.cc/xacrimon/rs-hm-bench
- concurrent types https://gitlab.nebulanet.cc/xacrimon/ccl
- https://www.zdnet.com/google-amp/article/microsoft-to-explore-using-rust/
  - 70% security bugs are memory bugs per microsoft
- rust prevents data races, not general races
  - https://blog.regehr.org/archives/490
- PNA Rust comments
  - https://news.ycombinator.com/item?id=20511271
  - https://twitter.com/lucio_d_franco/status/1153827158210560001
- https://rust-lang-nursery.github.io/rust-toolstate/
- https://rust-lang.github.io/rustup-components-history/
- cheat sheet: https://cheats.rs/
- dev and test are intertwined https://github.com/tikv/tikv/issues/5049
- unexpected drop order
