---
---

# 2015-02-17

* [Responded to DroidLogician about office visits](https://www.reddit.com/r/rust/comments/2w6rrk/im_going_to_be_in_sf_in_april_for_a_convention_is/cooewtk)
* [Filed issue about security policy](https://github.com/rust-lang/rust/issues/22464)
* Responded to a person looking to contribute to Rust
* Working on problem with CentOS linux builders checking out deep submodules
* Recompiled git from master on the CentOS linux-snap builders
* Reimaged linux-snap builders
* Updated slave-list.txt on prod and dev build masters
* acrichto volunteered to restart buildmaster
* Started build of nightlies with new installer
* Started build of nightly combined package with new installer
* [Commented on recycling slaves](https://github.com/rust-lang/rust/issues/22448)
* [Posted meeting minutes](http://internals.rust-lang.org/t/weekly-meetings-2015-02-17-fott-security-bugs-code-completion-open-ended-proposals-struct-syntax-alpha2-integer-suffixes-overflow/1608/1)

# 2015-02-16

* Gave michaelwoerister r+ for debuginfo
* [Reviewed string matching RFC](https://github.com/rust-lang/rfcs/pull/528)
* [Reviewed comment conventions RFC](https://github.com/rust-lang/rfcs/pull/505)
* [Reviewed hash RFC](https://github.com/rust-lang/rfcs/pull/823)
* [Reviewed rustup locale fix](https://github.com/rust-lang/rust/pull/22420)
* Working on TWiR
* [Responded to thread about 2nd tier builders](http://internals.rust-lang.org/t/community-supported-build-slaves-for-2nd-tier-platforms/1528/7)
* [Postponed unsafe enum RFC](https://github.com/rust-lang/rfcs/pull/724)
* [Enthused about acrichto's fixes of stability lints](https://github.com/rust-lang/rust/pull/22127)

# 2015-02-15

* [Made encouraging comments about Iron perf](https://www.reddit.com/r/rust/comments/2vzxjr/poor_http_performance_iron_framework/comjwyx)
* Looked for TWiR stories
* [Responded to concerns about bootstrapping Rust with Cargo](http://internals.rust-lang.org/t/should-cargo-be-written-in-rust/1595/4)
* Thanked Lars for making faster builds of Rust for Servo
* [Made some cleanups to the source README](https://github.com/rust-lang/rust/pull/22395)
* [Reviewed kmc's macro docs](https://github.com/rust-lang/rust/pull/22393/files)
* [Wrote encouraging things about dotdosh's miscompile fix](https://github.com/rust-lang/rust/pull/22385)
* [Reviewed fhahn's solution to compiletest capturing output incorrectly](https://github.com/rust-lang/rust/pull/22371)
* [Reviewed rustc_attrs feature](https://github.com/rust-lang/rust/pull/22336)
* [Approved Cargo rust-installer upgrade](https://github.com/rust-lang/cargo/pull/1301)
* [Merged rust-packaging upgrade](https://github.com/rust-lang/rust-packaging/pull/11)
* [Reviewed comment patch about Vec::from_iter](https://github.com/rust-lang/rust/pull/22394)
* [Reviewed stevek's CONTRIBUTING patches](https://github.com/rust-lang/rust/pull/22282)
* [Responded to GSoC thread](http://www.reddit.com/r/rust/comments/2vy5n3/rust_in_gsoc_2015/com8cq3)
* [Added rustfmt to list of gsoc projects](https://wiki.mozilla.org/Community:SummerOfCode15:Brainstorming)
* [Expressed mild support for publishing std via cargo](http://internals.rust-lang.org/t/std-on-crates-io/1585/5?u=brson)

# 2015-02-14

* [Praised Trace Quest Season 5](https://www.reddit.com/r/rust/comments/2vva9y/trace_quest_5_season_1_results/colj77q)
* [Responded to a Q about linking std to musl](https://news.ycombinator.com/item?id=9050828)
* [Commented on Huon's expansion of `must_use` to `ok`](https://github.com/rust-lang/rust/pull/22348)
* [Spent time working on int audit](https://github.com/rust-lang/rust/issues/22240)
* [Reviewed rename of std::failure](https://github.com/rust-lang/rust/pull/22347)
* [Filed uint -> usize PR](https://github.com/rust-lang/rust/pull/22350)
* [Revised usize PR](https://github.com/rust-lang/rust/pull/22350)
* [Stared a node.js lib for interacting with Rust infra](https://github.com/brson/rustworld)

# 2015-02-13

* Interviewed an intern candidate
* [Replied to coroutine thread](http://users.rust-lang.org/t/goroutine-coroutine-or-the-similar-in-rust/327/2)
* [Replied to most coveted features thread](http://users.rust-lang.org/t/most-coveted-rust-features/324/4)
* [Begged people for quotes of the week for TWiR](http://users.rust-lang.org/t/twir-quote-of-the-week/328)
* [Responded to publishing std on crates.io](http://internals.rust-lang.org/t/std-on-crates-io/1585/2)
* [Pushed temporary disable of msi packaging](https://github.com/rust-lang/rust-packaging/commit/c183da100c025d80f685970ac0e6ee21e5852a8d)
* Triggered rebuild of last night's failed nightlies
* [Updated version number for alpha.2](https://github.com/rust-lang/rust/pull/22292)
* Registered event, room, and airmo for 3/17 meetup
* [Reviewed doc PR](https://github.com/rust-lang/rust/pull/22293)
* [Re-reviewed bitrig PR](https://github.com/rust-lang/rust/pull/21959)
* [Investigated dist desync issue](https://github.com/rust-lang/rust-buildbot/issues/7)
* [Revised Rust --version PR](https://github.com/rust-lang/rust/pull/22201)
* [Revised Cargo --version PR](https://github.com/rust-lang/cargo/pull/1292)
* Attempting to debug wix failures on windows bots
* [Reviewed fhahn's fixes for early termination errors](https://github.com/rust-lang/rust/pull/22117)
* [Reviewed fhahn's parse-fail tests](https://github.com/rust-lang/rust/pull/22118)
* [Requested retry of PR](https://github.com/rust-lang/rust/pull/21376)
* [Reviewed test](https://github.com/rust-lang/rust/pull/22302)
* [Reviewed int audit of std::failure](https://github.com/rust-lang/rust/pull/22303)
* [Filed issue about incorrect naming in std::failure](https://github.com/rust-lang/rust/issues/22306)
* [Expressed my disapproval of another stealth attribute addition](https://github.com/rust-lang/rust/pull/22278#issuecomment-74342434)
* [Reviewed grammar docs](https://github.com/rust-lang/rust/pull/22308)
* Responded to jhford about global CI design
* [Submitted rustup PR for suruga](https://github.com/klutzy/suruga/pull/7)

# 2015-02-12

* [Complimented RustAudio](https://www.reddit.com/r/rust/comments/2vn0xx/rustaudio_a_collection_of_crates_for_audio_and/)
* [Emailed the person from Codius with words of encouragement](https://codius.org/blog/codius-rust/)
* [Responded to Process not Send on Windows thread](https://www.reddit.com/r/rust/comments/2vmzmh/coremarkersend_difference_mac_vs_windows/)
* [Promised to look into HTTPS on discourse](http://users.rust-lang.org/t/secure-access-via-https/296)
* Asked Neil from Discourse about HTTPS
* [Responded to OS X 10.5 q](http://users.rust-lang.org/t/rust-on-mac-os-10-5-8/304/3)
* [Responded to thread about platform-specific APIs in std](http://internals.rust-lang.org/t/what-rate-of-importability-do-we-allow-in-libstd/1556)
* Attended Rust triage
* Triaged a few I-compiletime issues
* [Reviewed ammendments to object safety RFC](https://github.com/rust-lang/rfcs/pull/817)
* Got OS X .pkg working with component selection and uninstallation
* Got .exe and .msi working with new installer
* Created new EC2 AMI for windows with WIX
* Added new windows AMI's to buildbot config. Waiting to restart buildbot.
* [Updated multirust for rust-installer](https://github.com/brson/multirust/commit/095e540026824e0e047f7325b9fcd5959fb9aeec)
* [Closed old build system issue](https://github.com/rust-lang/rust/issues/12363)
* [Added a --without flag to rust-installer](https://github.com/rust-lang/rust-installer/commit/60fd8abfcae50629a3fc664bd809238fed039617)
* [Filed multirust issue about slow blastoff script](https://github.com/brson/multirust/issues/29)
* [Filed PR for Rust rust-installer upgrade](https://github.com/rust-lang/rust/pull/22256)
* [Filed PR for Cargo rust-installer upgrade](https://github.com/rust-lang/cargo/pull/1301)
* [Filed PR for rust-packaging rust-installer upgrade](https://github.com/rust-lang/rust-packaging/pull/11)
* [Updated rust-buildbot to enable .msi](https://github.com/rust-lang/rust-buildbot/commit/ff9022c9c8be047152d5cf01a22a6b5408738a4e)
* Restarted buildbot for .msi
* [Updated .msi issue](https://github.com/rust-lang/rust/issues/21118#issuecomment-74205873)
* [Tightened up description of 1.0.0-alpha on rust-www](https://github.com/rust-lang/rust-www/pull/95)
* [Filed issue about unsafety of Repr](https://github.com/rust-lang/rust/issues/22260)

# 2015-02-11

* [Responded to questions about no_std gating](https://www.reddit.com/r/rust/comments/2vc05d/this_week_in_rust_69/coibg28)
* Obsoleted --disable-verify flag to rust-installer
* Improved error handling in rust-installer
* Upgraded rust-installer for rust, cargo, rust-packaging, multirust
* [Posted rust-installer upgrades](https://github.com/rust-lang/rust-installer/pull/20)
* [Updated rust-installer readme](https://github.com/rust-lang/rust-installer/commit/5bd23c2845a11856f6bc14b61c9ea963656731d9)
* Pointed out the Samsung OSG position to some people
* Responded to dhuseby about bitrig PR
* Responded to Packt telling them I'll review their book
* [Voiced approval for from_elem RFC](https://github.com/rust-lang/rfcs/pull/832#issuecomment-73989469)
* Submitted expense report for users.rust-lang.org
* Pinged jhford about global CI
* [Posted PR to solve --version date confusion](https://github.com/rust-lang/rust/pull/22201)
* [Likewise a Cargo PR for --version](https://github.com/rust-lang/cargo/pull/1292)

# 2015-02-10

* Wrote today's fott
* Weekly meeting
* [Expressed my opinion about array pattern simplification](https://github.com/rust-lang/rfcs/pull/495)
* [Posted meeting minutes](https://github.com/rust-lang/meeting-minutes/blob/master/weekly-meetings/2015-02-10.md)
* [Posted meeting minute thread](http://internals.rust-lang.org/t/weekly-meetings-2015-02-10-fott-unsafe-no-drop-flag-box-rfc-fallout-unused-attribute-feature-gate-sizeof-alignof-array-patterns/1578)
* [Re-reviewed bitrig PR](https://github.com/rust-lang/rust/pull/21959)
* [Reviewed fix for ffi ICEs](https://github.com/rust-lang/rust/pull/22160)
* Cleaned up rust-installer and made its backups work consistently

# 2015-02-09

* [Posted twir](https://www.reddit.com/r/rust/comments/2vc05d/this_week_in_rust_69/)
* [Filled out status report](http://benjamin.smedbergs.us/weekly-updates.fcgi/user/banderson%40mozilla.com)
* [Replied to thread about coding standards](https://www.reddit.com/r/rust/comments/2vc63z/with_10_around_the_corner_is_there_a_place_to/)
* [Responded to some multirust issue](https://github.com/brson/multirust/issues/27)
* [Responded to pnkfelix about RFC features](https://github.com/rust-lang/rfcs/pull/815)
* More work on rust-installer

# 2015-02-08

* twir
* [Asked for rebase of bitrig patch](https://github.com/rust-lang/rust/pull/21959)
* [Reviewed test tweaks](https://github.com/rust-lang/rust/pull/21862)

# 2015-02-07

* [Filed a bug about debugging extern fns](https://github.com/rust-lang/rust/issues/22071)
* Working on OpenSSL impl

# 2015-02-06

* [Responded to 1.0 bugs issue on internals](http://internals.rust-lang.org/t/a-list-of-high-priority-but-borderline-1-0-bugs-that-need-attention/1550/5?u=brson)
* [Commented on rustc --version confusion](https://github.com/rust-lang/rust/issues/21957#issuecomment-73290701)
* [Cheerlead parse-fail test PR](https://github.com/rust-lang/rust/pull/22011#issuecomment-73291027)
* [Reviewed featureck bugfix PR](https://github.com/rust-lang/rust/pull/21994)
* [Reviewed debuginfo fixes](https://github.com/rust-lang/rust/pull/21970)
* [Gisted some things that surprised me about assoc types](https://gist.github.com/brson/32a56693fa554b5a9dda)
* [Reviewed Cargo style PR](https://github.com/rust-lang/cargo/pull/1278)
* [Reviewed Cargo bugfix](https://github.com/rust-lang/cargo/pull/1271)
* [Reviewed another Cargo PR](https://github.com/rust-lang/cargo/pull/1270)
* [Reviewed another Cargo PR](https://github.com/rust-lang/cargo/pull/1269)
* Working on more rust-installer features
* [Responded to weird installation error](https://github.com/rust-lang/rust-buildbot/issues/7#issuecomment-73328834)
* [Reviewed kmc's plugin change](https://github.com/rust-lang/rust/pull/22026)

# 2015-02-05

* Attended triage
* [Reviewed bitrig patch](https://github.com/rust-lang/rust/pull/21959)
* [Added feature header to RFC template](https://github.com/rust-lang/rfcs/pull/815)
* [Revised my tidy PR](https://github.com/rust-lang/rust/pull/21619)
* [Filed issue about package desync](https://github.com/rust-lang/rust-buildbot/issues/7)
* [Added version file to combined package](https://github.com/rust-lang/rust-packaging/commit/d3ef82109a2894d5472a5a7b7b093b9bf9d9f3bc)
* [Posted list of high-pri bugs](http://internals.rust-lang.org/t/a-list-of-high-priority-but-borderline-1-0-bugs-that-need-attention/1550)
* [Reviewed binop optimization](https://github.com/rust-lang/rust/pull/21985)
* [Opened thread about porting maintenance](http://internals.rust-lang.org/t/rust-platform-portability-and-maintenance/1551)
* [Responded to RandomAccessIterator pre-RFC](http://internals.rust-lang.org/t/pre-rfc-remove-randomaccessiterator/1548)
* [Responded to Aatch's type system refactoring post](http://internals.rust-lang.org/t/type-system-refactoring/1487/7)
* [Re-reviewed RangeFull PR](https://github.com/rust-lang/rust/pull/21947)
* Upgraded rust-installer metadata version
* [Cheerleadered a windows fix in libpnet](https://github.com/libpnet/libpnet/pull/41)

# 2015-02-04

* [Reviewed bitflags PR](https://github.com/rust-lang/bitflags/pull/3)
* Cleaned up test harness in rust-installer and multirust
* Continued working on stable feature lint
* [Reviewed `..` syntax PR](https://github.com/rust-lang/rust/pull/21947)
* [Fixed printing errors to stderr in rust-installer](https://github.com/rust-lang/rust-installer/issues/5)
* [Fixed allcaps style issues in rust-installer](https://github.com/rust-lang/rust-installer/issues/1)
* [Responded to cross-compile thread](https://www.reddit.com/r/rust/comments/2ut7qi/rust_how_good_is_the_support_of_cross_compilation/)
* [Expressed reservation about timing of type ascription RFC](https://github.com/rust-lang/rfcs/pull/803#issuecomment-72975225)
* Reviewed various RFCs
* [rust-installer cleanup](https://github.com/rust-lang/rust-installer/pull/17)
* [Responded to SimonSapin's q about cargo isolation](https://github.com/brson/multirust/issues/25)
* [Filed issue about confusing date in rustc --version](https://github.com/rust-lang/rust/issues/21957)
* [Responded to confusing inference error](http://internals.rust-lang.org/t/compile-time-error-unable-to-infer-enough-type-information-about--/1396/7)
* [Filed issue about upgrading multirust independently](https://github.com/brson/multirust/issues/27)
* [Filed issue re Cargo testing vs. old rustc](https://github.com/rust-lang/cargo/issues/1276)
* [Filed issue re multirust show-toolchain](https://github.com/brson/multirust/issues/28)
* [Opend PR for stable_features lint](https://github.com/rust-lang/rust/pull/21958)
* [Building miniservo-gtk](https://github.com/glennw/miniservo-gtk)
