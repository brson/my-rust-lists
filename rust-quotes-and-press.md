Collection of (mostly early) responses to Rust.

# 2021-06-12

A few thoughts on Fuchsia security

- https://blog.cr0.org/2021/06/a-few-thoughts-on-fuchsia-security.html

"For system-level folks, Rust is one of the most exciting security developments of the past few decades. It elegantly solves problems which smart people were saying could not be solved. Fuchsia has a lot of code, and we made sure that much of it (millions of LoC) was in Rust.

Our kernel, Zircon, is not in Rust. Not yet anyway. But it is in a nice, lean subset of C++ which I consider a vast improvement over C."


# 2021-06-01

Quote's from Guido

- https://www.tectalk.co/python-creator-guido-van-rossum-reviews-popular-programming-languages/

# 2019-07-23

PNA Rust on HN

- https://news.ycombinator.com/item?id=20511271
- https://twitter.com/lucio_d_franco/status/1153827158210560001

# 2019-07-20

Rust mentioned in congress re libra

https://www.c-span.org/video/?c4808083/rust-language-chosen
https://www.reddit.com/r/programming/comments/cf8j82/us_house_committee_on_financial_services_hearing/

# 2019-07-19

- https://www.zdnet.com/google-amp/article/microsoft-to-explore-using-rust/
  - 70% security bugs are memory bugs per microsoft

# 2017-07-16

https://techcrunch.com/2017/07/16/death-to-c/

TechCrunch says drop C/C++, use Rust.

# 2017-07-03

Rust used in the Win32/TeleBot.AB trojan.

https://www.welivesecurity.com/2017/06/30/telebots-back-supply-chain-attacks-against-ukraine/

# 2017-06-24

Chelsea Manning mentions Rust briefly:

https://twitter.com/xychelsea/status/878715383552856064?cn=bWVudGlvbg%3D%3D&refsrc=email

# 2017-06-20

"Hi, I think rust is just an amazing achievement because it is the
first time we all, just about the first time we've seen one of these
kind of linear or affine type systems actually make its way into
practical use. So its just incredible, well done! I'm, you know, I
mean I'm wild with envy. I want to steal all the best ideas I can and
put them in Haskell."

Simon Peyton Jones

https://youtu.be/wXoY91w4Agk?t=2022

# 2017-06-01

"The dev-environment-setup experience with Rust is amazing. The Rust
community has striven to make it super easy to get started with Rust
and it shows. Literally one shell command will set everything you need
up."

"Essentially Rust has a lot of the good things about Scala’s type
system. One thing currently missing from Rust is first class support
for higher-kinded types (HKT), which, to be honest, I don’t miss too
much"

https://beachape.com/blog/2017/05/24/rust-from-scala/

# 2017-05-09

https://michaelfairley.com/blog/i-made-a-game-in-rust/

> "TL;DR: I’m glad I picked Rust for A Snake’s Tale, and I will be
continuing to make my games in Rust for the foreseeable future1;
however, I can’t strongly recommend Rust for gamedev in the near-term,
especially if you’re hoping for a batteries included experience."

> "Beyond the “big ideas” contained in Rust (e.g. the ownership model),
the “small ideas” that most other systems-y language don’t contain
(Option, Result, Iterator, discriminated unions, pattern matching,
etc. etc. etc.) make minute-to-minute programming much nicer."

> "Holy cow are the compiler error messages generally fantastic. rustc
  seems like a friend who’s trying to help you write better code,
  rather than a gatekeeper working to slow you down."

> "Rather than being locked into one paradigm, I found myself being
  able to cleanly use different programming styles as warranted in
  different situations."

> Stable upgrades have been a breeze, and the release train has been
  very nice. 8 new versions of Rust were released during the
  development of A Snake’s Tale, and each upgrade took no more than a
  few minutes. The release train has also consistently delivered
  much-welcomed improvements.

> Rust code being platform independent by default is 😍😍😍. There are no
  source level differences between my Mac, Windows, and Linux builds3,
  and the differences between mobile and desktop are relatively small
  and focused mostly around the UI delta between touchscreen and
  mouse+keyboard and OpenGL vs OpenGL ES.

# 2017-05-07

Rust code in Prey video game

https://www.reddit.com/r/rust/comments/69s225/rust_makes_it_into_a_aaa_video_game_as_an_art/

# 2017-05-05

"I really love seeing articles like this come out about Rust.

It's language design the way it should be: incorporating the cutting
edge ideas from academia while still striving to cater to beginners;
drawing on the strengths of other languages communities to build out
good library and solutions to package management; designing everything
in the open, and constantly seeking feedback from their users.

It's a great blend of theoretical CS, HCI, computer systems, and
application development, and it's always fun to hear about what
they're up to."

https://news.ycombinator.com/reply?id=14276182&goto=item%3Fid%3D14275512%2314276182

# 2017-04-25

"In brief, Rust was a joy to work with. Its powerful pattern matching
made writing compiler optimization rules very easy, and we found that
code that compiled usually “just worked” because of the stringent
checks Rust’s own compiler performs on code the programmer
writes. Additionally, writing C APIs in Rust was also very easy; Rust
provides good support and documentation for doing this. While there
are a few features the Rust developers are working on which we hope
appear in the stable compiler soon (namely, incremental compilation
and the box keyword), we wholeheartedly reccomend Rust to those
looking for a fun, powerful programming language for their next
project."

http://dawn.cs.stanford.edu/blog/weld.html

# 2017-04-06

Rust mentioned in Batgirl comic

https://twitter.com/chasinglogic/status/850115493923086336
http://www.readcomics.tv/batgirl-2016/chapter-8/10

# 2017-03-27

"MIT-Stanford project uses LLVM to break big data bottlenecks"

"Written in Rust, Weld can provide orders-of-magnitude speedups to Spark and TensorFlow"

http://www.infoworld.com/article/3182205/big-data/mit-stanford-project-uses-llvm-to-break-big-data-bottlenecks.html

# 2017-03-26

https://omtcyfz.github.io/2017/03/26/Rust-from-a-C++-programmers-perspective.html

"I believe that Rust is, in fact, the future of low-level tools and systems, the actual future we deserve"

# 2017-03-25

"In modern gcc, std::variant doesn't look like a competent replacement
for old-fashioned tagged unions ..."

https://news.ycombinator.com/item?id=13956351

std::variant is not as efficient as rust enums

# 2017-03-23

"I use Rust (since ~9-10months) and C++ (since ~7 years) at work, both
in the same project (modern generic header-only C++ using almost all
of C++17 already...). My time is spent like this: ~40% Rust, and 60%
C++, implementing new features in both (the C++ part is not "legacy"
code or anything, it is just that new modules are written in Rust, but
the "old" ones are still being developed).

The jump from C++ to Rust is qualitatively larger and better in
benefits than the jump from C to C++. Still, trying to sell Rust to
C++ programmers is as hard as trying to sell C++ to C programmers.

...

What does Rust bring to the table? It eliminates all that cruft:

..."

massive pitch to C++ programmers

https://www.reddit.com/r/cpp/comments/611811/have_you_used_rust_do_you_prefer_it_over_modern_c/dfb3xhp/?st=j0mj6j2i&sh=d87c1791

"Everyone deserves access to C technology without restriction,
especially as rust makes inroads." -- Theo De Raadt

https://marc.info/?l=openbsd-tech&m=149032069130072&w=2

# 2017-03-22

Most loved language second year in a row.

http://stackoverflow.com/insights/survey/2017

"Developers using languages listed above the blue line in this chart
such as Go, Rust, and Clojure are being paid more even given how much
experience they have"

https://amosbbatto.wordpress.com/2017/03/19/the-growing-trend-toward-compiled-languages/

Lots of discussion about the popularity of Rust.

# 2017-03-21

OkCupid exploring Rust:

https://tech.okcupid.com/rust-and-rpc-okcupid-hackweek-2017

# 2017-03-17

"One of the biggest overall gainers of any of the measured languages,
Rust leaped from 47 on our board to 26 – one spot behind Visual
Basic. This comes two quarters after the language not only stalled,
but actually gave up ground in our last rankings. What a difference a
few months can make. By our metrics, Rust went from the 46th most
popular language on GitHub to the 18th. Some of that is potentially a
result of the new process, of course, but no other language grew
faster."

http://redmonk.com/sogrady/2017/03/17/language-rankings-1-17/

"C++ is where the money is currently at, but I've switched from C++ to
Rust. It took me a few weeks to get around the borrowing system, but
overall I feel that I write much more maintainable code than before.

Issues I had with C++:

- ... (littany)"

https://www.reddit.com/r/programming/comments/5zze8k/crosscompile_and_link_a_static_binary_on_macos/df2lidj/?st=j0eg3161&sh=b3e6c977

"The Rust #programming language has some traction outside @mozilla,
including use at @Dropbox. #rustlang" -- Stephen Shankland (CNET writer)

https://twitter.com/stshank/status/842872876042657792

# 2017-03-16

"Did a double-take upon seeing Windows used so nonchalantly. All of
the Rust tooling being so (apparently) effortlessly cross-platform is
really cool and I don't think the project sees enough love for it."

https://www.reddit.com/r/programming/comments/5zrzms/announcing_rust_116/df0qiut/

# 2017-03-10

"Until this point, all of the firmware I had written, personally and
professionally, was done in C and Assembly. Given the safety
guarantees and high performance provided by Rust, it was a very
enticing choice. I was curious to see how involved the process would
be and if I could ditch C for future projects (spoiler: yes)."

http://www.acrawford.com/2017/03/09/rust-on-the-cortex-m3.html

# 2017-03-09

"I recently wrote an MPEG-2 subtitle decoder in Rust, and spent my
weekend attacking it with cargo fuzz. The fuzzer ran over a billion
sample inputs through my code.

"I discovered:

  - No malloc/free-related errors, thanks to the borrow checker.
  - 3 errors where I constructed invalid Range objects. These might
    have been exploitable or resulted in infinite loops in C.
  - One arithmetic underflow error, which might have been exploitable
    if it weren't for Rust's bounds checking.

So while writing high risk code, Rust ruled out most errors at compile
time, and caught 4 more at run time. Up until now I had underrated
Rust's runtime checks as part of the overall security story, but I now
consider them as indispensable as the compile time checks."

https://www.reddit.com/r/rust/comments/5y3cxb/how_many_security_exploits_would_rust_prevent/den3vz7/

# 2017-03-06

Martin Odersky wants to remove implicits from Dotty, citing Rust.

https://github.com/lampepfl/dotty/pull/2060#issuecomment-284758952

# 2017-02-25

One Year with Rust: I wrote a full featured application in rust, and so can you

https://news.ycombinator.com/item?id=13732706

# 2017-02-23

http://blog.faraday.io/how-we-made-our-csv-processing-142x-faster/

# 2017-02-22

Toward a more approachable Rust

https://lwn.net/Articles/714712/

Fallout from ESR blog

# 2017-02-22

"I'm not sure if this is what you're after, since it's not really in
book form, but I've learned a lot about advanced language
implementation from reading the Rust RFCs [1], especially those
relating to MIR. Between the discussion on each PR and the resulting
implementation in the actual compiler, it makes some very complicated
subjects more relatable than they normally would be. I'm really
grateful that so much of Rust's development happens in such an open
fashion."

https://news.ycombinator.com/item?id=13710726

# 2017-02-22

https://medium.com/@rillian/deploying-rust-in-a-large-codebase-7e50328074e8#.9r5fixac2

rillian talks about integrating Firefox into Rust

# 2017-02-19

"Rust's poor support for pointer-based graphs improved my code"

https://www.reddit.com/r/rust/comments/5ux4uq/rusts_poor_support_for_pointerbased_graphs/

Ownership-obeying graph representations have a lot of advantages.

# 2017-02-15

"rust/prepare.mk: Don't remove the $(nop) command below!"

https://news.ycombinator.com/item?id=13655081

# 2017-02-13

What can the programming language Rust do for astrophysics?

https://arxiv.org/abs/1702.02951

https://news.ycombinator.com/item?id=13632894

Apparently the experiment is flawed https://news.ycombinator.com/reply?id=13635226&goto=item%3Fid%3D13632894%2313635226

https://www.reddit.com/r/rust/comments/5trref/what_can_rust_do_for_astrophysics/

A GNOME developers argument on Vala being a dead language

http://www.phoronix.com/scan.php?page=news_item&px=GNOME-Vala-Bassi

# 2017-02-08

boost regex badly needs fuzzing

https://news.ycombinator.com/item?id=13600284

This HN thread contrasts Rust with C++ quite starkly.

A fuzz report for [boost regex] is filled with horrific crashes.

Two fuzzing rounds on Rust regex yielded quality fixes, but no memory safety violations [rf1] [rf2].

Thread is mostly about Rust, and pcwalton picked a big fight!

[boost regex]: https://svn.boost.org/trac/boost/ticket/12818
[rf1]: https://github.com/rust-lang/regex/issues/84
[rf2]: https://github.com/rust-lang/regex/pull/262

# 2017-02-03

Mozilla binds Firefox's fate to the Rust language

http://www.infoworld.com/article/3165424/web-browsers/mozilla-binds-firefoxs-fate-to-the-rust-language.html

# 2017-02-02

"This is amazing. Is Rust the best developer team out there? They move quickly and release features with a cadence I have not seen in
other languages. I would love to hear more about other languages release this way."

https://news.ycombinator.com/item?id=13556486

# 2017-01-27

"Package managers all the way down" - discusses cargo and rustup

10:00 <&steveklabnik> Cargo is "at the apex of usability" for language package managers, he said, adding that developing code in Rust is "a painless and beautiful process".
10:00 <&steveklabnik> :metal:
10:02 <&steveklabnik>  It might be tempting to just dismiss the whole thing, saying that the older way was better, but that way is not going to remain viable for much longer. His
                      experience with Rust made that clear; developing in that environment is just too nice.

https://lwn.net/SubscriberLink/712318/0a8c0c18c21dc27d

"The trouble with FreeBSD"

https://lwn.net/SubscriberLink/712308/cea4a92801616685

# 2017-01-25

InfoWorld technology of the year award

http://www.infoworld.com/article/3160526/application-development/infoworlds-2017-technology-of-the-year-award-winners.html#slide12

# 2017-01-12

ESR has as an exceedingly bad impression of Rust :(
    
"Rust severely disappoints me"
http://esr.ibiblio.org/?p=7294

https://www.reddit.com/r/rust/comments/5nl3fk/rust_severely_disappoints_me/

# 2017-01-06

"I just want to say that this project is amazing. At the risk of
sounding hyperbolic, I think Rust is the most exciting thing that's
happening in computing today. This sort of project that plausibly
replaces projects traditionally written only in C/C++ with something
that has performance parity, but is in a language where contributions
are relatively accessible and safe, is the most exciting thing even
within the bounds of an intriguing ecosystem."

https://news.ycombinator.com/item?id=13339259

re alacritty terminal emulator

# 2017-01-04

librsvg requires Rust

https://mail.gnome.org/archives/desktop-devel-list/2017-January/msg00001.html

# 2017-01-03

ESR considers Rust for a rewrite from C

http://blog.ntpsec.org/2017/01/03/getting-past-c.html

# 2016-12-29

Various fallout from Steve's "Rust is more that safety" post

"Rust is it's community" - https://mgattozzi.com/rust-is

"Rust is mostly safety" http://graydon2.dreamwidth.org/247406.html

"Rust is software's salvation" https://redox-os.org/news/rust-is-softwares-salvation-17/

"Fire Mario, not Fire Flowers" http://words.steveklabnik.com/fire-mario-not-fire-flowers

"Safety is Rust's fireflower" https://thefeedbackloop.xyz/safety-is-rusts-fireflower/

"Fire Flowers and Mario" https://medium.com/@ag_dubs/fire-flowers-and-marios-marketing-rust-996b3fdbe8f3

"My thoughts on Rust in 2017" https://medium.com/@Hisako1337/rust-in-2017-8f2b57a67d9b#.3eegqri2g

# 2016-12-28

https://news.ycombinator.com/item?id=13272474

"Other than porting architectures and Rustifying the usual C headers from the manufacturer, Rust has been an absolute breath of fresh air
when working on reliable, memory constrained systems. I keep running to the disassembler to make sure that my high level code don't
force the compiler to do something stupid but have yet to find anything that required I scale back my abstractions back to C levels."

# 2016-12-24

zcache signing ceremony written in Rust due to security requirements 

https://m.reddit.com/r/rust/comments/5k55c0/zcash_ceremony_code_written_in_rust_due_to/

# 2016-12-14

http://www.welivesecurity.com/2016/12/13/rise-telebots-analyzing-disruptive-killdisk-attacks/

"This trojan downloader is written in the Rust programming language."

# 2016-12-13

https://www.reddit.com/r/golang/comments/5hx5ba/hello_gophers/db4vplp/?st=iwphpbjl&sh=7ae49d0d

"I just headed over to /r/rust and I am amazed. Respectful tone from anybody, absolutely no downvoted post (I tried hard to find one 
and failed), even no downvoted comments (I also tried hard to find one and failed). If we could take over some of this spirit to this
subreddit, it would benefit everyone."

# 2016-12-08

https://lwn.net/SubscriberLink/708196/f0f91b4c8b657b5b/

GStreamer security mentions Rust

# 2016-12-06

http://leftoversalad.com/c/015_programmingpeople/

comic about rust

# 2016-12-01

https://eev.ee/blog/2016/12/01/lets-stop-copying-c/

https://www.reddit.com/r/programming/comments/5fwce0/lets_stop_copying_c/

# 2016-11-30

http://joeduffyblog.com/2016/11/30/15-years-of-concurrency/

https://news.ycombinator.com/item?id=13076677

"Out of the bunch, Rust has impressed me the most. They have delivered on much of what we set out to deliver with Midori, but actually shipped it (whereas we did not). My hat goes off to that team, seriously, because I know first hand what hard, hard, hard work this level of type system hacking is."

https://ruudvanasseldonk.com/2016/11/30/zero-cost-abstractions

"All overhead is gone completely". Impressive example.

https://news.ycombinator.com/item?id=13074667



# 2016-11-22

http://accidentallyquadratic.tumblr.com/post/153545455987/rust-hash-iteration-reinsertion

# 2016-11-01

http://www.infoworld.com/article/3136934/open-source-tools/project-for-porting-c-to-rust-gains-mozillas-backing.html
http://lwn.net/Articles/705266/

# 2016-10-31

http://www.infoworld.com/article/3135382/development-tools/rust-language-puts-ease-ahead-of-features-for-2017.html

# 2016-10-20

http://blog.faraday.io/saved-by-the-compiler-parallelizing-a-loop-with-rust-and-rayon/

mention of rls:
http://sdtimes.com/microsofts-milestone-speech-recognition-node-js-v6-9-0-released-google-open-sources-nomulus-sd-times-news-digest-oct-19-2016

# 2016-10-19

Ask HN: What is the state of c++ vs. Rust?
https://news.ycombinator.com/item?id=12744317

"First of all, I agree that cargo blows the C/C++ tools out of the
water in terms of ease of use. But I think it's even easier than newer
stuff too. It's by far the best dependency manager I've used."

https://news.ycombinator.com/item?id=12746170

http://www.infoworld.com/article/3132449/application-development/mozillas-rust-goes-real-time-with-code-feedback.html#tk.rss_infoworldtechwatch?utm_source=twitterfeed&utm_medium=twitter

https://blog.sentry.io/2016/10/19/fixing-python-performance-with-rust.html

# 2016-10-18

http://www.theregister.co.uk/2016/10/18/facebook_mercurial_devs_forget_git/

# 2016-10-01

Mention of Rust in article about security

https://techcrunch.com/2016/10/01/learned-helplessness-and-the-languages-of-dao/?ncid=rss&utm_source=feedburner&utm_medium=feed&utm_campaign=Feed%3A+Techcrunch+%28TechCrunch%29

# 2016-09-14

re RustConf

"I was fortunate to be able to attend.  Sometimes I feel like I'm just not built for conferences: I prefer solitude, and people usually go to conferences to confer. That said, this was an exceptional group of people to be among: smart, friendly, helpful, passionate, and accepting. I know it's been said before: the rust community at this stage of its evolution gets this right."

- https://news.ycombinator.com/reply?id=12500858&goto=item%3Fid%3D12499292%2312500858

# 2016-08-31

http://www.infoworld.com/article/3114475/open-source-tools/the-next-version-of-fedora-picks-up-rust.html

# 2016-08-26

http://www.infoworld.com/article/3109150/linux/linux-at-25-linus-torvalds-on-the-evolution-and-future-of-linux.html

> That's not a new phenomenon at all. We've had the system people who used Modula-2 or Ada, and I have to say Rust looks a lot better than either of those two disasters. 

# 2016-08-22

http://stratumsecurity.ghost.io/2016/08/22/joining-hands-and-singing-merrily-part-2-2

> When our other major option for the XFIL Agent was C or C++, for code that we will have to deploy to our clients' own machines, Rust is
                      far and away a better option. Its powerful type system, safety guarantees, and high-level features have allowed us to solve problems
                      with more confidence than any of our other options would have. We're very happy with our results, as well as the efficiency and
                      reliability of the software we've built with it so far.


# 2016-08-03

http://arstechnica.com/information-technology/2016/08/firefox-48-ships-bringing-rust-mainstream-and-multiprocess-for-some/

# 2016-07-06

16:25 <&steveklabnik> We're expanding our use of Rust into even more bold endeavours, details soon.
16:25 <&steveklabnik> Based on our experience with it in the last 1.5 years, stick with it, it will return your effort many times over in the medium-long run.
16:25 <&steveklabnik> ^ jamie from dropbox on HN
16:25 <&steveklabnik> https://news.ycombinator.com/item?id=12044991

# 2016-06-29

08:44 <&steveklabnik> https://blogs.dropbox.com/tech/2016/06/lossless-compression-with-brotli/ <-
08:45 <&steveklabnik> The Rust programing language fits the bill perfectly: it’s a language that promises memory safety without garbage collection, concurrency without data races,
                      and abstractions without overhead. It also has sufficient performance for our needs. That means that code written in Rust has the same memory requirements as
                      the equivalent code written in C. At Dropbox, many of our services are actually memory bound, so this is a key advantage over a garbag
08:45 <&steveklabnik> etc
08:45 <&steveklabnik> :D
08:46 <&steveklabnik> Currently the decompressor runs at 72% of the speed of the vanilla -O3 optimized Brotli decompressor in gcc-4.9 for decompressing 4 megabyte blocks of data.

# 2016-06-28

> It's interesting, because this article - the whole theme of it - was inspired by the Rust and Servo community. They regularly have "This week in Rust" and "This week in Servo" posts to inform the community of the progress. And let me tell you, these are extremely valuable in keeping the community up to date and engaged. It's proven to be such a successful model that other libraries in the Rust community, and outside of it have started to make their own posts like this.

> Which brings us to this post. Someone took their time to write this up, gather and organize the relevant info, for the benefit of the community. And what do they get as a response? Negativity and memes.

[/u/ImSoCabbage](https://www.reddit.com/r/linux/comments/4q8d9n/this_week_in_gtk/d4r53l4)

# 2016-06-01

http://www.linuxjournal.com/content/new-version-rust-hits-streets-0

# 2016-05-16

> "Rust has done a truly phenomenal job at being a new language.  I can remember when it was first announced, the demo of rust looked like linefeed noise (anyone remember the @'s?)  It has become incredibly ergonomic.  I think rust took the right amount of time to stabilize, the long beta/alpha period was well worth it."

> "I also love just about every decision make about the language and
  ecosystem.  Small standard library.  Sanctioned build
  system/dependency management.  Unstable features for evolution.
  Continuous language feature deployment.  Using cargo to check for
  breaking language changes."

> "Really, just fantastic.  I can't think of any other way to start a language.  Here is to hoping that someday I can get rust at work."

[/u/cogman10](https://www.reddit.com/r/rust/comments/4jmb5z/one_year_of_rust/d381hh3)

# 2016-05-13

> "Rust's support for cross compilation, both in the compiler and the tooling (cargo, multirust/rustup) is amazing.  Last week I was working on a hardened system project.  It involved building a system consisting of just a kernel and a single process.  At first I was going to target a unikernel, so I pulled the "x86_64-rumprun-netbsd" target, read some docs on rumprun, and in about 30 minutes I had a Rust project running as a unikernel, all well supported by Rust and its tooling.Rust's support for cross compilation, both in the compiler and the tooling (cargo, multirust/rustup) is amazing.  Last week I was working on a hardened system project.  It involved building a system consisting of just a kernel and a single process.  At first I was going to target a unikernel, so I pulled the "x86_64-rumprun-netbsd" target, read some docs on rumprun, and in about 30 minutes I had a Rust project running as a unikernel, all well supported by Rust and its tooling."

[fpgaminer on HN](https://news.ycombinator.com/item?id=11693004)

# 2016-05-01

http://forum.dlang.org/post/mailman.1738.1462099059.26339.digitalmars-d@puremagic.com

# 2016-04-28

[Mozilla's Rust language doubles down on speed and simplicity (InfoWorld)](http://www.infoworld.com/article/3062936/application-development/mozillas-rust-language-doubles-down-on-speed-and-simplicity.html)

## 2016-04-15

[Rust 1.8 takes steps to replace the Make build system (InfoWorld)](http://www.infoworld.com/article/3056622/application-development/rust-18-takes-steps-to-replace-the-make-build-system.html)

## 2016-04-14 (1.8 release)

> "So in 1.7 one of the most important things was that it contained a breaking change, at it was a test of how Rust handled that sort of thing. I didn't see even one person express a negative outcome as a result of that change, so I would say that Rust passed the test, and Rust's strategy for small inevitable breaking changes so far is successful!"

-- [/u/deseringmachines](https://www.reddit.com/r/rust/comments/4es4av/announcing_rust_18/d22v8nd)

[Rust is the #4 website that feeds hackernews](https://github.com/antontarasenko/smq/blob/master/reports/hackernews-top-domains-by-median.md).

## 2016-04-10

> Q: "Do you see any programming language in the next 10/20 years taking over C++'s current place as most programming language used for systems?"

> A: "I would love to see Rust take that place. I have been following an OS written entirely in Rust, and it has great idioms."

-- [/u/migueldeicaza](https://www.reddit.com/r/programmerchat/comments/4dxpcp/i_am_miguel_de_icaza_i_started_xamarin_mono_gnome/d1vci1w)

## 2016-04-09

[Frog and Toad are Cofounders](https://medium.com/frog-and-toad-are-cofounders/the-pitch-655df5f5e6da#.m5qz5a64l).
A story using Rust as an example of trendy tech.

## 2016-04-06

[Redox: a Rust-based microkernel (LWN)](https://lwn.net/SubscriberLink/682591/b22d2633646dda29).

## 2016-03-22

[Rust's Redox could show Linux a few new tricks (InfoWorld)](http://www.infoworld.com/article/3046100/open-source-tools/rusts-redox-os-could-show-linux-a-few-new-tricks.html).

## 2016-03-14

[The Epic Story of Dropbox's Exodus from the Cloud Empire](http://www.wired.com/2016/03/epic-story-dropboxs-exodus-amazon-cloud-empire/).
Wired story on Dropbox. Mention's Rust.

[Magic Pocket Infrastructure](https://blogs.dropbox.com/tech/2016/03/magic-pocket-infrastructure/).
Dropbox's accompanying blog post.

> "I would be more interested in a proposal to move parts of QEMU
  to Rust, or just about anything else except C++..."

-- [PPM (QEMU maintainer)](http://lists.nongnu.org/archive/html/qemu-devel/2016-03/msg02276.html)

# 2016-03-10

[Rust most loved in StackOverflow developer's survey](http://stackoverflow.com/research/developer-survey-2016#technology-most-loved-dreaded-and-wanted)

# 2016-02-02

[4chan discusses rust](http://boards.4chan.org/g/thread/52767422).
Link dead.

# 2016-01-20

[InfoWorld technology of the year award](http://www.infoworld.com/article/3023050/open-source-tools/infoworlds-2016-technology-of-the-year-award-winners.html#slide21).

# 2016-01-22

> "The fact that Rust continues to mature is incredibly exciting."

> "One of the biggest reasons we're struggling with computer security today is that our tools are too primitive and fragile," said Ristic. "Most components of our infrastructure are written in low level languages such as C. Having been tortured by C during my years of wiring security-critical software, I don't think I exaggerate when I compare programming in it with walking through a minefield."
                
> "With Rust, many of the classes of problem simply go away, by design. At the same time, software written in it is compatible with existing software written in C. What this means is that we can start to slowly migrate to Rust and significantly improve our security as a result."

-- [Ivan Ristic, software engineer and founder of SSL Labs](http://www.theregister.co.uk/2016/01/22/rust_16)

# 2016-01-08

> "That leaves Rust as my default recommendation for new, non-critical
  projects in this space. Like Dropbox employee, what I've noticed is
  the two of you on Rust teams here are unusually helpful and
  respectful compared to many in PL communities defending their
  work. Even pcwalton when he's clearly less than happy with my
  comments. ;)"

-- [nickpsecurity on HN](https://news.ycombinator.com/item?id=10867076)

# 2015-12-10

> "Stability has been very good; in the last 6 months, we've had no issues with the stability of the rust compiler, the output binaries, or the rust stdlib."

-- [/u/jamwt (Dropbox)](https://www.reddit.com/r/programming/comments/3w8dgn/announcing_rust_15/cxucrse)

> "The Rust core team has been amazingly friendly and helpful.  We've had several meetings with them where they came to our office and basically said "how's it going?  what do you need? open up your laptop and show us your biggest problem."  The project is under very good management.

-- [/u/jamwt (Dropbox)](https://www.reddit.com/r/programming/comments/3w8dgn/announcing_rust_15/cxum0dm)

# 2015-11-23

> "Rust seems sensible"

-- [John Carmack](https://twitter.com/ID_AA_Carmack/status/668811183307145217)

# 2015-11-09

> "Friends don't let friends skip leg day"

-- [Andrei Alexandrescu on Rust](https://www.quora.com/Which-language-has-the-brightest-future-in-replacement-of-C-between-D-Go-and-Rust-And-Why/answer/Andrei-Alexandrescu)

See also his similar quote from 2015-08-28.

# 2015-10-28

[Ian Lance Taylor on Rust](https://www.quora.com/What-do-Go-programming-language-designers-think-of-Rust-programming-language)

# 2015-10-07

> "The OS community I always look to as an example of a welcoming and
  friendly one is Rust. Rust the compilar/cargo/infrastructure and
  also most of the bigger projects written in Rust have a very good
  vibe to them and are very explicit about the rules of engagement."

-- [What Makes a Good Community](http://sarah.thesharps.us/2015/10/06/what-makes-a-good-community/)

# 2015-10-05

[Positive report on RustCamp diversity](http://techwhirl.com/conference-report-friendly-diverse-rust-camp/)

# 2015-09-28

> "Rust's spectacular engineering makes memory management far less of a chore than it's predecessors"

[When Rust Makes Sense](http://m50d.github.io/2015/09/28/when-rust-makes-sense.html)

> "When I write Rust code, I feel like a great programmer, even though
  I've only recently graduated from being a complete newbie to someone
  who mostly knows his stuff."

-- [/u/llogiq](https://www.reddit.com/r/rust/comments/3mofy0/when_rust_makes_sense_or_the_state_of_typed/cvgpwke)

> "One of the major reasons for being interested in Rust is that it is something that is much easier to convince coworkers of."

-- [gmjosack on HN](https://news.ycombinator.com/item?id=10289174)

> "Essentially, Rust gives me new super powers and the borrow checker is my sidekick making sure I don't shoot myself in the foot."

-- [lambda on HN](https://news.ycombinator.com/reply?id=10290874&goto=item%3Fid%3D10289174)

"I would like to think it is because Rust put a breath of fresh air into Systems Programming, by adding features that make modern languages good, and makes what some of the hardest things to do in C easy."

-- unknown

[Rust most starred language on GitHub](https://github.com/showcases/programming-languages) (until Swift showed up).

# 2015-09-25

[Kenton Varda mentions Rust in `curl | bash` discussion](https://blog.sandstorm.io/news/2015-09-24-is-curl-bash-insecure-pgp-verified-install.html?hn=1)

# 2015-09-23

[CPP lifetime proposal references Rust. Authored by Herb Sutter.](https://github.com/isocpp/CppCoreGuidelines/blob/09aef9bd86d933bc1e1ffe344eb2e73d2de15685/docs/Lifetimes%20I%20and%20II%20-%20v0.9.1.pdf)

[Sutter on Rust](https://www.reddit.com/r/cpp/comments/3m0d41/writing_good_c14_by_default_herb_sutter/cvcnmn5).

# 2015-09-17 (1.3 release)

> "@rustlang might be one of the best documented, best engineered (and apparently, most honest) programming languages "

-- [@Jacob_Henner](https://twitter.com/Jacob_Henner/status/644364501391945729)

> " I guess I'll be able to compile all my code on stable 1.4 judging by https://github.com/rust-lang/rust/pull/28339"

-- [arthursilva on HN](https://news.ycombinator.com/item?id=10235011)

> "From what I can tell (passively reading about language decisions and seeing the responsiveness of all involved on various communication channels), it's a great lesson in building a community while simultaneously creating a fun programming language."

-- [noobymatze on HN makes their first internet comment](https://news.ycombinator.com/item?id=10235578)

# 2015-09-01

[Brief mention in Wired](http://www.wired.com/2015/09/facebooks-new-anti-spam-system-hints-future-coding/)

# 2015-08-28

> "Rust has great promise 'safe coding without a garbage collector' but herein
lies its challenge as well - the language had to dedicate so much real
estate to this (difficult) problem alone, it became a disharmonic creature
with one bulging muscle and little of anything else."

-- [Andrei Alexandrescu](https://www.reddit.com/r/programming/comments/3ioy9b/andrei_alexandrescu_c_guru_leaves_facebook_to/cuj0csn)

# 2015-08-17

[What's on tap for Mozilla's Rust in 2016 (InfoWorld)](http://www.infoworld.com/article/2971852/application-development/whats-on-tap-for-mozillas-rust-in-2016.html).

> "The Rust community seems to be populated entirely by human beings. I have no idea how this was done. I suspect Graydon Hoare deserves a large share of the credit for leading by example but everyone I have interacted with in the community has been friendly and patient."

-- [Three Months of Rust](http://scattered-thoughts.net/blog/2015/06/04/three-months-of-rust/)

# 2015-07-15

[Two reasons the Rust language will succeed (InfoWorld)](http://www.infoworld.com/article/2947214/open-source-tools/two-reasons-the-rust-language-will-succeed.html).

# 2015-07-14

[Rust doge](http://i.imgur.com/157mlnN.png)

# 2015-07-03

[Things Rust shipped without (Graydon)](http://graydon2.dreamwidth.org/218040.html).

[Comments on HN for the above](https://news.ycombinator.com/item?id=9827051).

# 2015-06-18

[Parallel page rendering with Mozilla Servo (LWN)](http://lwn.net/SubscriberLink/647969/48b505d485950a9e/)

# 2015-06-17

[Why I <3 Rust (Julia Evans)](https://drive.google.com/file/d/0B3oFPgN3B006Qjh0UWpLZlRXZzQ)

# 2015-06-15

[Rust mentioned in a comic strip](http://www.commitstrip.com/en/2015/06/15/when-you-have-no-room-for-error/).

# 2015-06-01

[Photos from 1.0 launch in bangalore](https://www.flickr.com/photos/galaxyk/sets/72157651031840283).

# 2015-05-15 (1.0 release)

> "This is a day I've been looking forward to for three-and-a-half years..."

-- [@saneyuki_s (with dramatic picture)](https://twitter.com/saneyuki_s/status/599259576517595137)

[HN](https://news.ycombinator.com/item?id=9551937).

[Ars Technica](http://arstechnica.com/information-technology/2015/05/mozilla-backed-rust-language-stabilizes-at-version-1-0/).

# 2015-05-13

[Rust makes me excited about the future](http://www.reddit.com/r/rust/comments/35w2nq/rust_makes_me_excited_about_the_future/).

# 2015-05-02

[Death to C (TechCrunch)](http://techcrunch.com/2015/05/02/and-c-plus-plus-too/)

# 2015-04-23

> "This ownership stuff is such a blessing and amazing. I'm currently working on a contract where we're trying to fixup some code that crashes under heavy load, as well as troubleshoot some perf issues. The root cause is that it's not clear who actually owns what until when, so in some cases an object is destructed while there's still some code thinking it can use it. Fun."

> "For perf, 30% of the CPU is burned in malloc/free, due to them copying strings around. The system has an arena allocator built in, and many of these strings might be able to go in there. Except no one is sure exactly how long the lifetime is on these things. So everyone copies everything just to be sure. Rust would force addressing this kinda thing up front. (And this project coulda added an refcounted structure or something, but it's a few hundred kloc of C and C++ so...)"

-- [MichaelGG on HN](https://news.ycombinator.com/item?id=9435792)

# 2015-04-04

[Mozilla's Rust-based Servo browser engine inches forward (InfoWorld)](http://www.infoworld.com/article/2905688/applications/mozillas-rust-based-servo-browser-engine-inches-forward.html)

# 2015-03-19

> "One reason Rust will be a great language for systems engineers - https://doc.rust-lang.org/std/process/struct.Command.html … is damn near perfect."

-- [@adamhjk](https://twitter.com/adamhjk/status/578627590996496384)

# 2015-03-13

[A Swift guide to Rust](http://faq.sealedabstract.com/rust/).

# 2015-03-12

[Rust CoC recommended by geekfeminism](http://geekfeminism.wikia.com/wiki/Code_of_conduct). (no longer apparently)

# 2015-02-24

> "In contrast, Rust's core devs have been forthcoming about
  practically every objection they've gotten. Their answers are clear,
  detailed, not demeaning, and constructive. When they don't know,
  they're honest about it, and when answers are hard, they take the
  time to explain. But I have never heard of anyone being belittled
  for not understanding lifetimes or the borrow checker."

-- [Daishiman on HN](https://news.ycombinator.com/item?id=9099299)

[What's your killer Rust feature love-fest](https://www.reddit.com/r/rust/comments/2x0h17/whats_your_killer_rust_feature/).

# 2015-02-20

```
11:22 -!- HappilyDoge [HappilyDoge@moz-hgo9t9.fios.verizon.net] has joined #rust-internals
11:23 < HappilyDoge> I just came in here to say that I'm with huon. I love this language too. That is all.
11:23 -!- HappilyDoge [HappilyDoge@moz-hgo9t9.fios.verizon.net] has left #rust-internals ["Leaving"]
```

# 2015-02-14

> "That was surprisingly civil. I came for drama and left pleasantly disappointed. Shoutout to /r/rust"

-- [/u/SosNapoleon](https://www.reddit.com/r/programming/comments/2vvcbm/author_of_unix_in_rust_abandons_rust_in_favour_of/col8o0k)

> "I am not a rust guy yet, but I plan on picking it up and have been in that sub for a long time. I don't think I've seen a more level headed sub on reddit."

-- [JavaDroid](https://www.reddit.com/r/programming/comments/2vvcbm/author_of_unix_in_rust_abandons_rust_in_favour_of/colbt25)

# 2015-01-24

> "The rust project is the best run open source project I've seen. The culture, automation and communication is awesome."

-- [ozten on HN](https://news.ycombinator.com/item?id=8940431)

```
10:47 < HKT> brson: As an outsider I really like how Rust feels like a community developed language rather than just being open source
```

# 2015-01-23

[How to Go and Rust languages compare (Quora)](https://www.quora.com/How-do-Go-and-Rust-languages-compare)

[Why Go is not Good](http://yager.io/programming/go.html)

[Rust vs. Go](http://jaredly.github.io/2014/03/22/rust-vs-go/)

# 2014-11-06

[Rust and I were meant for each other](https://www.reddit.com/r/rust/comments/2ljrp2/i_think_rust_and_i_were_meant_for_each_other/).

# 2014-10-27

[Some good floating point benchmarks](http://www.fourmilab.ch/fourmilog/archives/2014-10/001537.html).

# 2014-10-14

> "As someone interested in Rust and obsessive over Doom, this is about as cool as it gets"

-- [@Notch](https://twitter.com/notch/status/521988177519996928)

# 2014-09-24

> "The core team and it's open-ness and communication with everyone is really why i absolutely love Rust, they're very active in the community and very open to ideas and criticisms of the language"

-- [speewave](http://www.reddit.com/r/rust_gamedev/comments/2gyrkh/jonathan_blow_ideas_about_a_new_programming/ckoyc3h)

# 2014-07-30

[sebcrozet comment about rust perf](http://www.reddit.com/r/rust/comments/2c5ax6/how_does_rust_compare_to_c_performancewise/cjcalo1).

# 2014-07-01

[Discussion of 30-minute introduction (good rationalization of breakage)](https://news.ycombinator.com/item?id=7968556).

> "Mozilla is one of my favorite tech companies. Servo is a great example: Mozilla is willing to engage in fundamental CS research. Not only are they trying to put together a parallel, secure browser engine from the ground up, but they even created Rust to do so. This is truly long-term work, which seems rare in an increasingly short-term world."

> "And Rust isn't just another C clone with OOP or CSP bolted on: it's principled, relatively elegant and takes full advantage of the last few decades of PL research. All while being practical—it has to be, since it's evolved with a Servo as a concomitant project. A non-trivial companion project like that seems great for naturally guiding a language! Not many other languages can say any of this, much less ones actually poised to replace C++ or at least do actual systems programming."

> "And Mozilla is doing all this in a completely open and transparent way. I think this is incredibly important: anybody can get a glimpse into active development or even contribute. Just go to the relevant GitHub repo[1][2] and you're set. This is the way open source is supposed to work, rather than having companies develop behind close doors and dump source code occasionally (although that's also better than nothing)."

> "I really wish more companies would take this sort of approach with their open source or basic research work. This gives me more confidence in Servo, Rust and Mozilla as a whole, especially compared to many of Mozilla's competitors (both in the browser space and in programming languages)."

-- [tikhonj on HN](https://news.ycombinator.com/item?id=7238054)


> "Paul Graham talks about people who 'live in the future' -- in a specific area of their lives, they see clearly that some change is coming long before everyone else catches on. It seems the trend towards legalization of marijuana is one such area -- it probably is one of the next gold rushes. (In my opinion, 2 other such areas are virtual reality and the Rust programming language)."

-- [charlieflowers on HN](https://news.ycombinator.com/item?id=7611230)

> "If you are building a new language with serious ambitions for usage, you should really take a look at how well the Rust community has turned out to be. The "Buzz" you experience around the language is largely fueled by lots of enthusiasts - e.g. hop on the IRC channel at any time of day and get help. There are no dumb questions, especially about changes that happened in the mainline 2 days ago."

> "Barriers for committing to Rust itself are very low. Also, they aggressively moderate their spaces according to their CoC. A few days ago, I asked a rather picky question on their subreddit and was quite surprised how on-point and serious the answers were. Given that the topic had the potential for some trolling, it was surprisingly calm."

> "It's really a community I am happy in."

-- Argorak on HN (link?)

# 2014-07-03 (0.11 release)

[HN thread](https://news.ycombinator.com/item?id=7978599).

> > "I can't bring myself to care about a language that changes that much that quickly out in the open. I get that it's still early in development, but honestly, why even bother sharing it with the world at this point?"

> "Because it's an open source project. A real open source project, with open design and open contributions. This is exactly how it is supposed to work. You're supposed to care because you want to help develop a cutting-edge language to solve real world problems. If that is not your cup of tea, that's fine, just wait for 1.0, but open development is a good thing."

> "We've tend to expect projects to be released fully formed, but that's just because we're used to open source as corporate PR. This is how a community run project works."

-- [/u/jcdyer3](http://www.reddit.com/r/programming/comments/29o446/rust_0110_released/cinhddx)

# 2014-05-23

> "@Jonathan_Blow rust looks fun, but I don't think I'd want try to make a bigger project in it.."

-- [@Notch to @Jonathan_Blow](https://twitter.com/notch/status/469879785947402240)

# 2013-06-27

[Minor mention my John Carmack](https://twitter.com/seanmoon/status/350473918429143040).

# 2013-05-01

Go and Rust - objects without class

https://lwn.net/Articles/548560/

# 2013-04-17

[A taste of Rust](http://lwn.net/Articles/547145/). LWN article.

# 2013-04-03

Mozilla and Samsung building a new browser engine

https://lwn.net/Articles/545716/

# 2013-01-25

["When I checked out Rust" on This PLT Life](http://this-plt-life.tumblr.com/post/41441254767/when-i-checked-out-rust).

# 2010-07-08

[The Rust Language](http://lambda-the-ultimate.org/node/4009). Lambda the Ultimate. First significant mention of Rust in press.
