## Rust CLI tools I use a lot

- [basic-http-server](https://crates.io/crates/basic-http-server) - serve static HTML and rendered Markdown
- [cargo-clean-all](https://crates.io/crates/cargo-clean-all) - clean all projects, leaving recent files
- [cargo-edit](https://crates.io/crates/cargo-edit) - `cargo add` command especially
- [cargo-expand](https://github.com/dtolnay/cargo-expand) - expand macros
- [cargo-hack](https://crates.io/crates/cargo-hack) - build / test with all combinations of cargo features
- [cargo-tree](https://crates.io/crates/cargo-tree) - show the crate graph as a tree
- [du-dust](https://crates.io/crates/du-dust) - lik du, disk usage
- [fd-find](https://crates.io/crates/fd-find) - convenient `find` replacement
- [gist](https://crates.io/crates/gist) - post gists
- [lsd](https://crates.io/crates/lsd) - like ls
- [parol](https://crates.io/crates/parol) - LL(k) parser generator
- [ripgrep](https://crates.io/crates/ripgrep) - fast and convenient code grep
- [tokei](https://crates.io/crates/tokei) - count lines of code

## Rust CLI tools I use sometimes

- [bingrep](https://crates.io/crates/bingrep) - output info about binaries
- [cargo-audit](https://crates.io/crates/cargo-audit) - find known security vulnerabilities
- [cargo-benchcmp](https://crates.io/crates/cargo-benchcmp) - compare benchmarks using Rust's built-in benchmarker
- [cargo-bloat](https://crates.io/crates/cargo-bloat) - show what's bloating your bins
- [cargo-deps](https://crates.io/crates/cargo-deps) - generate dep graphs (deprecated - use carge-depgraph?)
- [cargo-fuzz](https://crates.io/crates/cargo-fuzz) - fuzz testing
- [cargo-generate](https://crates.io/crates/cargo-generate) - create a project from a project template
  - `cargo generate --git https://github.com/rustwasm/wasm-pack-template`
- [cargo-llvm-lines](https://github.com/dtolnay/cargo-llvm-lines/) - shows amount of LLVM IR generated per function
- [cargo-outdated](https://crates.io/crates/cargo-outdated) - find upgradable crates
- [cargo-udeps](https://crates.io/crates/cargo-udeps) - show unused crates
- [cargo-watch](https://crates.io/crates/cargo-watch) - rebuild on change
- [cargo-workspace](https://crates.io/crates/cargo-workspace) - operate on every crate in workspace
- [critcmp](https://crates.io/crates/critcmp) - compare criterion benchmarks
- [eza](https://crates.io/crates/eza) - like ls
- [hexyl](https://crates.io/crates/hexl) - hex viewer
- [jaq](https://crates.io/crates/jaq) - jq clone for querying JSON
- [jsonxf](https://crates.io/crates/jsonxf) - JSON pretty-printer and more
- [just](https://crates.io/crates/just) - custom command runner, like make but without the baggage
- [mdbook](https://crates.io/crates/mdbook) - Rust-standard markdown documentation generator
- [sd](https://crates.io/crates/sd) - sed replacement (find and replace)
- [stellar-xdr](https://crates.io/crates/stellar-xdr) - XDR encoding/decoding
- [twiggy](https://crates.io/crates/twiggy) - code size profiler
- [wagyu](https://crates.io/crates/wagyu) - generate blockchain wallets
- [wasm-cs](https://crates.io/crates/wasm-cs) - read and write custom wasm sections
- [wasm-opt](https://crates.io/crates/wasm-opt) - wasm optimizer
- [wasm-tools](https://crates.io/crates/wasm-tools) - various tools for wasm
- [xsv](https://crates.io/crates/xsv) - CSV tool

## Rust tools I have used in the past

- [cargo-feature-analyst](https://crates.io/crates/cargo-feature-analyst) - show feature usage

## Rust tools I don't use but might

- [bat](https://crates.io/crates/bat) - cat with syntax highlighting
- [bins](https://crates.io/crates/bins) - multi-pastebin tool
- [broot](https://crates.io/crates/broot) - novel large directory navigation
- [cargo-clean-recursive](https://crates.io/crates/cargo-clean-recursive) - clean all projects
- [cargo-count](https://crates.io/crates/cargo-count) - count lines in rust projects
- [cargo-deny](https://crates.io/crates/cargo-deny) - disallow specific crates, licenses, etc
- [cargo-geiger](https://crates.io/crates/cargo-geiger) - detect unsafe in dep tree
- [cargo-generate](https://crates.io/crates/cargo-generate) - create cargo projecs from temtplates
- [cargo-license](https://crates.io/crates/cargo-license) - show licenses of dependencies
- [chit](https://crates.io/crates/chit) - lookup crate info
- [dua-cli](https://crates.io/crates/dua-cli) - disk usage analyzer
- [eva](https://crates.io/crates/eva) - calculator, like bc
- [fastmod](https://crates.io/crates/fastmod) - code refactoring
- [hyperfine](https://crates.io/crates/hyperfine) - benchmarking tool
- [intentrace](https://crates.io/crates/intentrace) - better strace
- [measureme](https://github.com/rust-lang/measureme) - work with rustc's self-profile
- [memory-profiler](https://github.com/nokia/memory-profiler) - analyze memory leaks
- [miniserve](https://crates.io/crates/miniserve) - simple HTTP server
- [pomsky](https://crates.io/crates/pomsky) - easy regexes
- [procs](https://crates.io/crates/procs) - like htop / ps
- [rewrite](https://crates.io/crates/rewrite) - rewrite file contents
- [rust-semverver](https://github.com/rust-lang/rust-semverver) - check for semver API breakage
- [ripgrep_all](https://crates.io/crates/ripgrep_all) - search inside archives etc
- [svgbob](https://crates.io/crates/svgbob) - convert text to SVG
- [treeify](https://crates.io/crates/treeify) - display a list files as a tree
- [wasm-pack](https://crates.io/crates/wasm-pack) - package Rust as wasm

## Not Rust but useful for Rust

- [bloaty mcbloatface](https://github.com/google/bloaty) - find code bloat

## Don't use any more

- [cargo-lichking](https://crates.io/crates/cargo-lichking) - check dependency licenses

## Other's lists

- https://twitter.com/jesusprubio/status/1237752138069094400
- https://www.wezm.net/technical/2019/10/useful-command-line-tools
- https://elliehuxtable.com/my-tools-are-pretty-rusty/
- https://www.reddit.com/r/rust/comments/fvx7bm/i_wrote_a_blog_post_about_rust_cli_tools_i_find/
