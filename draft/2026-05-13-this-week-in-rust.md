Title: This Week in Rust 651
Number: 651
Date: 2026-05-13
Category: This Week in Rust

Hello and welcome to another issue of *This Week in Rust*!
[Rust](https://www.rust-lang.org/) is a programming language empowering everyone to build reliable and efficient software.
This is a weekly summary of its progress and community.
Want something mentioned? Tag us at
[@thisweekinrust.bsky.social](https://bsky.app/profile/thisweekinrust.bsky.social) on Bluesky or
[@ThisWeekinRust](https://mastodon.social/@thisweekinrust) on mastodon.social, or
[send us a pull request](https://github.com/rust-lang/this-week-in-rust).
Want to get involved? [We love contributions](https://github.com/rust-lang/rust/blob/main/CONTRIBUTING.md).

*This Week in Rust* is openly developed [on GitHub](https://github.com/rust-lang/this-week-in-rust) and archives can be viewed at [this-week-in-rust.org](https://this-week-in-rust.org/).
If you find any errors in this week's issue, [please submit a PR](https://github.com/rust-lang/this-week-in-rust/pulls).

Want TWIR in your inbox? [Subscribe here](https://this-week-in-rust.us11.list-manage.com/subscribe?u=fd84c1c757e02889a9b08d289&id=0ed8b72485).

## Updates from Rust Community

<!--

Dear community contributors:
Please read README.md for guidance on submissions.
Each submitted link should be of the form:

* [Title of the linked Page](https://example.com/my_article)

If you add a link to a non-text content please prefix it with `[video]` or `[audio]`:

* [video] [Title of the linked video](https://example.com/my_video_article)
* [audio] [Title of the linked audio file](https://example.com/my_podcast)

If you don't know which category to use, feel free to submit a PR anyway
and just ask the editors to select the category.

-->

### Official

### Foundation

### Newsletters
* [The Embedded Rustacean Issue #71](https://www.theembeddedrustacean.com/p/the-embedded-rustacean-issue-71)

### Project/Tooling Updates
* [Numax - A portable Rust runtime for distributed apps](https://github.com/GianIac/numax/releases/tag/v0.1.0-alpha.1)

* [Entroly 0.18.0: Rust-powered AI context engine with PRISM reinforcement learning, SimHash dedup, and EGSC caching](https://github.com/juyterman1000/entroly/discussions/43)

* [uFerris: A Versatile Learning Board for Rust Embedded](https://www.theembeddedrustacean.com/uferris)

* [Record Ownership: Which Side Is Right?](https://aimdb.dev/blog/record-ownership)

* [Burn 0.21.0 Release: Up to 8× Lower Framework Overhead, Differentiable Collectives and Improved Kernels](https://burn.dev/blog/release-0.21.0/)

- [Ratty: A terminal emulator with inline 3D graphics](https://blog.orhun.dev/introducing-ratty/)

* [Announcing diesel-async 0.9](https://blog.weiznich.de/blog/diesel-async-0-9/)

* [Fresh 0.3.4: Ansi-native 'terminal' theme matches the system's theme; UI for Live Grep + custom grep providers; persistent 'dock' split; Verilog/VHDL support; and much more](https://github.com/sinelaw/fresh/releases/tag/v0.3.4)

### Observations/Thoughts

* [Getting Started with Geospatial Rust](https://eors-workspace-a6ef35.gitlab.io/posts/001-introduction-geospatial-rust/) — What satellites measure, spectral bands, indices, cloud detection.
* [Lessons Learned Building High-Performance Rust Profiler](https://pawelurbanek.com/rust-performance-profiling)
* [The limits of Rust, or why you should probably not follow Amazon, Cloudflare and Discord](https://kerkour.com/the-limits-of-rust)
* ["Respectful" YAML patching in Rust](https://verrchu.github.io/blog/2-respectful-yaml-patching-in-rust/)


### Rust Walkthroughs
* [Learn Rust Generics and Traits By Building a Mini Blackjack Game](https://blog.sheerluck.dev/posts/learn-generics-traits-in-rust-by-building-blackjack-card-game-engine/)

* [Where the sun keeps shinin': the provider pattern](https://bitfieldconsulting.com/posts/sun-keeps-shinin)
* [End-to-End Geospatial Processing with EORST](https://eors-workspace-a6ef35.gitlab.io/posts/002-end-to-end-workflow/) — Build a satellite pipeline in Rust: STAC query to GeoTIFF.

### Research

### Miscellaneous
* [Announcing the 2026 Rust-Edu Refresh and CFP](https://rust-edu.org/news/call-for-participation/)
## Crate of the Week

This week's crate is [cloakrs](https://github.com/kadir/cloakrs), a library and CLI tool for detecting and masking personally identifiable information.

Despite having no suggestion to work with, llogiq is content with his choice.

[Please submit your suggestions and votes for next week][submit_crate]!

[submit_crate]: https://users.rust-lang.org/t/crate-of-the-week/2704

## Calls for Testing
An important step for RFC implementation is for people to experiment with the
implementation and give feedback, especially before stabilization.

If you are a feature implementer and would like your RFC to appear in this list, add a
`call-for-testing` label to your RFC along with a comment providing testing instructions and/or
guidance on which aspect(s) of the feature need testing.

*No calls for testing were issued this week by
[Rust](https://github.com/rust-lang/rust/issues?q=state%3Aopen%20label%3Acall-for-testing%20state%3Aopen),
[Cargo](https://github.com/rust-lang/cargo/issues?q=state%3Aopen%20label%3Acall-for-testing%20state%3Aopen),
[Rustup](https://github.com/rust-lang/rustup/issues?q=state%3Aopen%20label%3Acall-for-testing%20state%3Aopen) or
[Rust language RFCs](https://github.com/rust-lang/rfcs/issues?q=label%3Acall-for-testing%20state%3Aopen).*

[Let us know](https://github.com/rust-lang/this-week-in-rust/issues) if you would like your feature to be tracked as a part of this list.

## Call for Participation; projects and speakers

### CFP - Projects

Always wanted to contribute to open-source projects but did not know where to start?
Every week we highlight some tasks from the Rust community for you to pick and get started!

Some of these tasks may also have mentors available, visit the task page for more information.

<!-- CFPs go here, use this format: * [project name - title of issue](URL to issue) -->
<!-- * [ - ]() -->
*No Calls for participation were submitted this week.*

If you are a Rust project owner and are looking for contributors, please submit tasks [here][guidelines] or through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [Bluesky](https://bsky.app/profile/thisweekinrust.bsky.social) or [Mastodon](https://mastodon.social/@thisweekinrust)!

[guidelines]:https://github.com/rust-lang/this-week-in-rust?tab=readme-ov-file#call-for-participation-guidelines

### CFP - Events

Are you a new or experienced speaker looking for a place to share something cool? This section highlights events that are being planned and are accepting submissions to join their event as a speaker.

<!-- CFPs go here, use this format: * [**event name**](URL to CFP)| Date CFP closes in YYYY-MM-DD | city,state,country | Date of event in YYYY-MM-DD -->
<!-- or if none - *No Calls for papers or presentations were submitted this week.* -->

* [**Scientific Computing in Rust 2026**](https://scientificcomputing.rs/2026/submit-talk)| 2026-06-05 | Virtual | 2026-07-08 - 2026-07-10

If you are an event organizer hoping to expand the reach of your event, please submit a link to the website through a [PR to TWiR](https://github.com/rust-lang/this-week-in-rust) or by reaching out on [Bluesky](https://bsky.app/profile/thisweekinrust.bsky.social) or [Mastodon](https://mastodon.social/@thisweekinrust)!

## Updates from the Rust Project

502 pull requests were [merged in the last week][merged]

[merged]: https://github.com/search?q=is%3Apr+org%3Arust-lang+is%3Amerged+merged%3A2026-05-05..2026-05-12

#### Compiler
* [consider `Result<T, Uninhabited>` and `ControlFlow<Uninhabited, T>` to be equivalent to `T` for must use lint](https://github.com/rust-lang/rust/pull/148214)
* [fewer global `node_id_to_def_id` lookups](https://github.com/rust-lang/rust/pull/156173)
* [introduce move expressions (`move($expr)`)](https://github.com/rust-lang/rust/pull/155023)
* [resolve: evaluate private visibilities eagerly in eff vis computation](https://github.com/rust-lang/rust/pull/156185)

#### Library
* [add `Command::get_resolved_envs`](https://github.com/rust-lang/rust/pull/149362)
* [add `Drop::pin_drop` for pinned drops](https://github.com/rust-lang/rust/pull/144537)
* [add `keepalive`, `set_keepalive` to `TcpStream` implementations](https://github.com/rust-lang/rust/pull/154025)
* [drop unmapped ZSTs in array `map`](https://github.com/rust-lang/rust/pull/152487)
* [have arrays' `drop_glue` just unsize and call the slice version](https://github.com/rust-lang/rust/pull/155184)
* [implemented `PathBuf::into_string`](https://github.com/rust-lang/rust/pull/156204)

#### Cargo
* [`diag`: Track Cargo diagnostic warning/error count like is done for rustc](https://github.com/rust-lang/cargo/pull/16981)
* [suggest 'fmt' when user types 'cargo rustfmt'](https://github.com/rust-lang/cargo/pull/16985)
* [rebuild when -Zpublic-dependency changes](https://github.com/rust-lang/cargo/pull/16965)

#### Clippy
* [add new lint `inline_trait_bounds`](https://github.com/rust-lang/rust-clippy/pull/16486)
* [new lint: `manual_clear`](https://github.com/rust-lang/rust-clippy/pull/16617)
* [fix `manual_option_zip` false positive when the outer param is used in closure](https://github.com/rust-lang/rust-clippy/pull/16970)
* [incompatibility of `non_canonical_clone_impl` and `implicit_return`](https://github.com/rust-lang/rust-clippy/pull/16949)

#### Rust-Analyzer
* [add wrap in tree list with editor](https://github.com/rust-lang/rust-analyzer/pull/22256)
* [add diagnostic for E0436](https://github.com/rust-lang/rust-analyzer/pull/22309)
* [add diagnostic for E0529](https://github.com/rust-lang/rust-analyzer/pull/22334)
* [complete `:`: on module def](https://github.com/rust-lang/rust-analyzer/pull/22259)
* [support deref patterns](https://github.com/rust-lang/rust-analyzer/pull/22292)
* [add whitespaces on postfix completion in macro](https://github.com/rust-lang/rust-analyzer/pull/22315)
* [do not infer signatures, instead infer anon consts in them](https://github.com/rust-lang/rust-analyzer/pull/22198)
* [do not replace closure capture place types with errors if they fail to normalize](https://github.com/rust-lang/rust-analyzer/pull/22319)
* [fix handling of `self` in `lower_coroutine_body_with_moved_arguments()`](https://github.com/rust-lang/rust-analyzer/pull/22266)
* [fix offer on unrelated for `toggle_macro_delimiter`](https://github.com/rust-lang/rust-analyzer/pull/22304)
* [generally fix derive helper resolution in semantics](https://github.com/rust-lang/rust-analyzer/pull/22299)
* [in "Implement missing members", do not add assoc types with defaults](https://github.com/rust-lang/rust-analyzer/pull/22291)
* [no add spaces on `..=` on macro inside macro](https://github.com/rust-lang/rust-analyzer/pull/22302)
* [provide an InferCtxt to TyLoweringContext](https://github.com/rust-lang/rust-analyzer/pull/22237)
* [provide source map for the lowered `let self = self` binding in async fns](https://github.com/rust-lang/rust-analyzer/pull/22318)
* [ref match uses unified type](https://github.com/rust-lang/rust-analyzer/pull/22285)
* [renaming mut vars removed `mut` in patterns generated by macro](https://github.com/rust-lang/rust-analyzer/pull/22303)
* [respect lint attributes for diagnostics that don't set their main node](https://github.com/rust-lang/rust-analyzer/pull/22290)
* [remove make mut](https://github.com/rust-lang/rust-analyzer/pull/22310)

### Rust Compiler Performance Triage

This week saw a couple of PRs affecting the new trait solver, which is steadily moving forward,
in particular [#156139](https://github.com/rust-lang/rust/pull/156139) was a massive perf. win.
[#156185](https://github.com/rust-lang/rust/pull/156185) optimized visibility computation, resulting
in up to a 8% win on the `typenum` crate.

Triage done by **@Kobzol**.
Revision range: [1d72d7e8..aa31d6d8](https://perf.rust-lang.org/?start=1d72d7e8136faaebad3a85eeed432e6ea1b2ffab&end=aa31d6d8020dcb7c6e6635648d1ca2bc18caf059&absolute=false&stat=instructions%3Au)

**Summary**:

| (instructions:u)                   | mean   | range           | count |
|:----------------------------------:|:------:|:---------------:|:-----:|
| Regressions ❌ <br /> (primary)    | 0.3%   | [0.1%, 0.4%]    | 62    |
| Regressions ❌ <br /> (secondary)  | 0.5%   | [0.1%, 1.5%]    | 77    |
| Improvements ✅ <br /> (primary)   | -1.7%  | [-8.8%, -0.2%]  | 18    |
| Improvements ✅ <br /> (secondary) | -13.6% | [-85.6%, -0.0%] | 34    |
| All ❌✅ (primary)                 | -0.2%  | [-8.8%, 0.4%]   | 80    |

2 Regressions, 2 Improvements, 5 Mixed; 4 of them in rollups
31 artifact comparisons made in total

[Full report here](https://github.com/rust-lang/rustc-perf/blob/d4003fd3999eabaef2bca2c218d10f7547425a96/triage/2026/2026-05-12.md).

### [Approved RFCs](https://github.com/rust-lang/rfcs/commits/master)

Changes to Rust follow the Rust [RFC (request for comments) process](https://github.com/rust-lang/rfcs#rust-rfcs). These
are the RFCs that were approved for implementation this week:

* [Rust Foundation Maintainer Fund](https://github.com/rust-lang/rfcs/pull/3931)
* [RFC: Inheriting of default-features in Cargo](https://github.com/rust-lang/rfcs/pull/3945)

### Final Comment Period

Every week, [the team](https://www.rust-lang.org/team.html) announces the 'final comment period' for RFCs and key PRs
which are reaching a decision. Express your opinions now.

#### Tracking Issues & PRs

##### [Rust](https://github.com/rust-lang/rust/issues?q=is%3Aopen%20label%3Afinal-comment-period%20sort%3Aupdated-desc%20state%3Aopen)
* [lint on `core::ffi::c_void` as a return type](https://github.com/rust-lang/rust/pull/156379)
* [Tracking issue for release notes of #154647: change `c_double` to `f32` on `avr` targets](https://github.com/rust-lang/rust/issues/156477)
* [Stabilize `--remap-path-prefix` in rustdoc](https://github.com/rust-lang/rust/pull/155307)
* [Replace printables table with `unicode_data.rs` tables](https://github.com/rust-lang/rust/pull/155527)
* [Tracking issue for RFC 2137: Support defining C-compatible variadic functions in Rust (c_variadic](https://github.com/rust-lang/rust/issues/44930)
* [Tracking Issue for `Path::is_empty`](https://github.com/rust-lang/rust/issues/148494)
* [Tracking Issue for integer formatting into a fixed-size buffer](https://github.com/rust-lang/rust/issues/138215)
* [resolve: Partially convert `ambiguous_glob_imports` lint into a hard error](https://github.com/rust-lang/rust/pull/149195)

##### [Rust RFCs](https://github.com/rust-lang/rfcs/issues?q=state%3Aopen%20label%3Afinal-comment-period%20state%3Aopen)
* [Propose the concept of a crates.io username for identity](https://github.com/rust-lang/rfcs/pull/3946)
* [Cargo RFC for min publish age](https://github.com/rust-lang/rfcs/pull/3923)

##### [Language Reference](https://github.com/rust-lang/reference/issues?q=is%3Aopen%20label%3Afinal-comment-period%20sort%3Aupdated-desc%20state%3Aopen)
* [New rule `layout.repr.c.struct.align-empty`](https://github.com/rust-lang/reference/pull/2264)

##### [Leadership Council](https://github.com/rust-lang/leadership-council/issues?q=state%3Aopen%20label%3Afinal-comment-period%20state%3Aopen)
* [Establish the funding team](https://github.com/rust-lang/leadership-council/issues/294)

*No Items entered Final Comment Period this week for
[Cargo](https://github.com/rust-lang/cargo/issues?q=is%3Aopen%20label%3Afinal-comment-period%20sort%3Aupdated-desc%20state%3Aopen),
[Compiler Team](https://github.com/rust-lang/compiler-team/issues?q=label%3Amajor-change%20label%3Afinal-comment-period%20state%3Aopen) [(MCPs only)](https://forge.rust-lang.org/compiler/mcp.html),
[Language Team](https://github.com/rust-lang/lang-team/issues?q=is%3Aopen%20label%3Afinal-comment-period%20sort%3Aupdated-desc%20state%3Aopen) or
[Unsafe Code Guidelines](https://github.com/rust-lang/unsafe-code-guidelines/issues?q=is%3Aopen%20label%3Afinal-comment-period%20sort%3Aupdated-desc%20state%3Aopen).*
Let us know if you would like your PRs, Tracking Issues or RFCs to be tracked as a part of this list.

### [New and Updated RFCs](https://github.com/rust-lang/rfcs/pulls)
* *No New or Updated RFCs were created this week.*

## Upcoming Events

Rusty Events between 2026-05-13 - 2026-06-10 🦀

### Virtual
* 2026-05-17 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust)
    * [**Rust Deep Learning: Third Sunday**](https://www.meetup.com/dallasrust/events/314329043/)
* 2026-05-19 | Virtual (Washington, DC, US) | [Rust DC](https://www.meetup.com/rustdc)
    * [**Mid-month Rustful**](https://www.meetup.com/rustdc/events/rdhhptyjchbzb/)
* 2026-05-20 | Hybrid (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust)
    * [**Mouse Control with Rust**](https://www.meetup.com/vancouver-rust/events/313572925/)
* 2026-05-20 | Virtual (Girona, ES) | [Rust Girona](https://lu.ma/rust-girona)
    * [**Weekly coding session**](https://luma.com/548kbqhl)
* 2026-05-21 | Hybrid (Seattle, WA, US) | [Seattle Rust User Group](https://www.meetup.com/join-srug)
    * [**May, 2026 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/seattle-rust-user-group/events/313873203/)
* 2026-05-21 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/308455929/)
* 2026-05-21 | Virtual (Charlottesville, VA, US) | [Charlottesville Rust Meetup](https://www.meetup.com/charlottesville-rust-meetup)
    * [**Tock OS Part #4 - Capsule coding in QEMU!**](https://www.meetup.com/charlottesville-rust-meetup/events/314477948/)
* 2026-05-26 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust)
    * [**Fourth Tuesday**](https://www.meetup.com/dallasrust/events/310254781/)
* 2026-05-26 | Virtual (London, UK) | [Women in Rust](https://www.meetup.com/women-in-rust)
    * [**Lunch & Learn: Seeing Into Your Code - A Practical Guide to Tracing in Rust**](https://www.meetup.com/women-in-rust/events/313506048/)
* 2026-05-27 | Virtual (Girona, ES) | [Rust Girona](https://lu.ma/rust-girona)
    * [**Weekly coding session**](https://luma.com/9v7hv2g1)
* 2026-06-03 | Virtual (Indianapolis, IN, US) | [Indy Rust](https://www.meetup.com/indyrs)
    * [**Indy.rs - with Social Distancing**](https://www.meetup.com/indyrs/events/wqzhftyjcjbfb/)
* 2026-06-04 | Virtual (Berlin, DE) | [Rust Berlin](https://www.meetup.com/rust-berlin/events/)
    * [**Rust Hack and Learn**](https://www.meetup.com/rust-berlin/events/308455930/)
* 2026-06-04 | Virtual (Nürnberg, DE) | [Rust Nuremberg](https://www.meetup.com/rust-noris/events/)
    * [**Rust Nürnberg online**](https://www.meetup.com/rust-noris/events/313345241/)
* 2026-06-07 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Rust Deep Learning: First Sunday**](https://www.meetup.com/dallasrust/events/314095285/)
* 2026-06-09 | Virtual (Dallas, TX, US) | [Dallas Rust User Meetup](https://www.meetup.com/dallasrust/events/)
    * [**Second Tuesday**](https://www.meetup.com/dallasrust/events/310254780/)
* 2026-06-10 | Virtual (Girona, ES) | [Rust Girona](https://lu.ma/rust-girona)
    * [**Weekly coding session**](https://luma.com/3bcnx1jb)

### Asia
* 2026-05-13 | Malaysia, MY | [Rust Meetup Malaysia](https://docs.google.com/forms/d/e/1FAIpQLSfMh6PA05ujl3lS59tJU3DcLHGVZ1zjzJhl49hXEHU7e6vsQA/viewform)
    * [**Rust Meetup May 2026**](https://docs.google.com/forms/d/e/1FAIpQLSfMh6PA05ujl3lS59tJU3DcLHGVZ1zjzJhl49hXEHU7e6vsQA/viewform)
* 2026-05-14 | Seoul, KR | [Seoul Rust (Programming Language) Meetup](https://www.meetup.com/rust-seoul-meetup)
    * [**Seoul Rust Meetup**](https://www.meetup.com/rust-seoul-meetup/events/314649688/)
* 2026-05-16 | Bangalore, IN | [Rust Bangalore](https://hasgeek.com/rustbangalore)
    * [**May 2026 Rustacean meetup**](https://hasgeek.com/rustbangalore/may-2026-rustacean-meetup/)
* 2026-06-02 | Beijing, CN | [Voice AI and Rust Meetup (Rust for AI, lowcoderust.com)](https://www.meetup.com/wasm-rust-meetup/events/)
    * [**AI Agents and Open Source LLM (Call for Speakers)**](https://www.meetup.com/wasm-rust-meetup/events/314750465/)

### Europe
* 2026-05-13 | Girona, ES | [Rust Girona](https://luma.com/rust-girona)
    * [**Rust Girona Hack & Learn 05 2026**](https://luma.com/ooub1kt0)
* 2026-05-14 | Switzerland, CH | [PostTenebrasLab](https://www.posttenebraslab.ch/wiki/events/start)
    * [**Rust Meetup Geneva**](https://www.posttenebraslab.ch/wiki/events/monthly_meeting/rust_meetup)
* 2026-05-18 - 2026-05-23 | Utrecht, NL | [RustWeek 2026](https://2026.rustweek.org/)
    * [**RustWeek 2026**](https://2026.rustweek.org/)
* 2026-05-18 | Milano, MI, IT | [Rust Language Milan](https://www.meetup.com/rust-language-milano)
    * [**RustWeek 2026**](https://www.meetup.com/rust-language-milan/events/314329200/)
* 2026-05-19 | Aarhus, DK | [Rust Aarhus](https://www.meetup.com/rust-aarhus)
    * [**Hack Night**](https://www.meetup.com/rust-aarhus/events/314129975/)
* 2026-05-19 | Amsterdam, NL | [RustNL](https://www.meetup.com/rust-amsterdam)
    * [**RustWeek 2026 announcement**](https://www.meetup.com/rust-nederland/events/312861992/)
* 2026-05-19 | Leipzig, DE | [Rust - Modern Systems Programming in Leipzig](https://www.meetup.com/rust-modern-systems-programming-in-leipzig)
    * [**Cross-Building & Cross-Testing**](https://www.meetup.com/rust-modern-systems-programming-in-leipzig/events/313813902/)
* 2026-05-19 | London, UK | [Women in Rust](https://www.meetup.com/women-in-rust)
    * [**RustWeek lunch meetup**](https://www.meetup.com/women-in-rust/events/314313054/)
* 2026-05-21 | Amsterdam, NL | [RustNL](https://www.meetup.com/rust-amsterdam)
    * [**RustWeek Hackathon**](https://www.meetup.com/rust-nederland/events/314301699/)
* 2026-05-22 | Amsterdam, NL | [RustNL](https://www.meetup.com/rust-amsterdam)
    * [**Bike tour around Utrecht**](https://www.meetup.com/rust-nederland/events/314523659/)
* 2026-05-26 | Dortmund, DE | [Rust Dortmund](https://www.meetup.com/rust-dortmund)
    * [**Rust Dortmund Meetup - Agentic Programming - May**](https://www.meetup.com/rust-dortmund/events/314522781/)
* 2026-05-26 | Manchester, UK | [Rust Manchester](https://www.meetup.com/rust-manchester)
    * [**Rust Manchester May Code Night**](https://www.meetup.com/rust-manchester/events/314452972/)
* 2026-05-29 | Berlin, DE | [Rust Berlin](https://www.meetup.com/rust-berlin)
    * [**Rust Berlin Talks: The next generation**](https://www.meetup.com/rust-berlin/events/314396588/)
* 2026-06-03 | Dublin, IE | [Rust Dublin](https://www.meetup.com/rust-dublin/events/)
    * [**Join us live and INPERSON for Rust 261**](https://www.meetup.com/rust-dublin/events/314689875/)


### North America
* 2026-05-14 | Lehi, UT, US | [Utah Rust](https://www.meetup.com/utah-rust/events/)
    * [**Utah Rust May Meetup**](https://www.meetup.com/utah-rust/events/314696639/)
* 2026-05-14 | Mountain View, CA, US | [Hacker Dojo](https://www.meetup.com/hackerdojo/events/)
    * [**RUST MEETUP at HACKER DOJO**](https://www.meetup.com/hackerdojo/events/314469265/)
* 2026-05-14 | Portland, OR, US | [PDXRust](https://www.meetup.com/pdxrust)
    * [**From Radio Waves to Pixels - Real-Time Visualizations with Rust and WebAssembly**](https://www.meetup.com/pdxrust/events/314256732/)
* 2026-05-14 | San Diego, CA, US | [San Diego Rust](https://www.meetup.com/san-diego-rust)
    * [**San Diego Rust May Meetup - Back in person!**](https://www.meetup.com/san-diego-rust/events/313721886/)
* 2026-05-16 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust)
    * [**Lechmere Rust Lunch, May 16**](https://www.meetup.com/bostonrust/events/314480531/)
* 2026-05-19 | San Francisco, CA, US | [San Francisco Rust Study Group](https://www.meetup.com/san-francisco-rust-study-group)
    * [**Rust Hacking in Person**](https://www.meetup.com/san-francisco-rust-study-group/events/314154841/)
* 2026-05-20 | Hybrid (Vancouver, BC, CA) | [Vancouver Rust](https://www.meetup.com/vancouver-rust)
    * [**Mouse Control with Rust**](https://www.meetup.com/vancouver-rust/events/313572925/)
* 2026-05-20 | San Francisco, CA, US | [Bay Area Rust Meetup](https://luma.com/bayarearust)
    * [**Bay Area Rust Meetup**](https://luma.com/9j3q5ejl)
* 2026-05-21 | Hybrid (Seattle, WA, US) | [Seattle Rust User Group](https://www.meetup.com/join-srug)
    * [**May, 2026 SRUG (Seattle Rust User Group) Meetup**](https://www.meetup.com/seattle-rust-user-group/events/313873203/)
* 2026-05-21 | Nashville, TN, US | [Music City Rust Developers](https://www.meetup.com/music-city-rust-developers)
    * [**Community Meetup**](https://www.meetup.com/music-city-rust-developers/events/314359076/)
* 2026-05-23 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust)
    * [**Allston Rust Lunch, May 23**](https://www.meetup.com/bostonrust/events/314480534/)
* 2026-05-27 | Austin, TX, US | [Rust ATX](https://www.meetup.com/rust-atx)
    * [**Rust Lunch - Fareground**](https://www.meetup.com/rust-atx/events/314209662/)
* 2026-05-28 | Atlanta, GA, US | [Rust Atlanta](https://www.meetup.com/rust-atl)
    * [**Rust-Atl**](https://www.meetup.com/rust-atl/events/313539319/)
* 2026-05-28 | Los Angeles, CA, US | [Rust Los Angeles](https://www.meetup.com/rust-los-angeles)
    * [**Rust LA: Rust in Embedded & Autonomous Systems at Parallel Systems in DTLA**](https://www.meetup.com/rust-los-angeles/events/314218564/)
* 2026-05-30 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust)
    * [**Central Cambridge Rust Lunch, May 30**](https://www.meetup.com/bostonrust/events/314480537/)
* 2026-06-04 | Saint Louis, MO, US | [STL Rust](https://www.meetup.com/stl-rust/events/)
    * [**Testing, Coverage, Tracey & Mutations**](https://www.meetup.com/stl-rust/events/314106244/)
* 2026-06-06 | Boston, MA, US | [Boston Rust Meetup](https://www.meetup.com/bostonrust/events/)
    * [**Boston Common Rust Lunch, June 6**](https://www.meetup.com/bostonrust/events/314480539/)

### Oceania
* 2026-05-14 | Melbourne, AU | [Rust Melbourne](https://www.meetup.com/rust-melbourne)
    * [**Rust Melbourne - May 2026**](https://www.meetup.com/rust-melbourne/events/314260890/)
* 2026-05-26 | Barton, ACT, AU | [Canberra Rust User Group](https://www.meetup.com/rust-canberra)
    * [**May Meetup**](https://www.meetup.com/rust-canberra/events/314050576/)

### South America
* 2026-05-13 | Montevideo, UY | [Rust Meetup Uruguay](https://www.meetup.com/rust-uruguay)
    * [**Rust Uruguay meetup de Mayo**](https://www.meetup.com/rust-uruguay/events/314532884/)

If you are running a Rust event please add it to the [calendar] to get
it mentioned here. Please remember to add a link to the event too.
Email the [Rust Community Team][community] for access.

[calendar]: https://www.google.com/calendar/embed?src=apd9vmbc22egenmtu5l6c5jbfc%40group.calendar.google.com
[community]: mailto:community-team@rust-lang.org

## Jobs

Please see the latest [Who's Hiring thread on r/rust](INSERT_LINK_HERE)

# Quote of the Week

> Of the last 150 merged PRs to Bun, **108 are memory-safety-adjacent** — missed cleanup on an error path, use-after-free, uninitialized reads, out-of-bounds access, reentrancy. **75 of those would not compile** in a language with destructors, move semantics, and a borrow checker. One in three PRs we ship is "forgot to free something on an error path."
> 
> Of the 108, ~88 are in Zig. The ~14 in C++ are mostly ref-cycles and GC-concurrency races — the residual class that survives any language. So the Zig→Rust delta is real: the Zig bugs are exactly the destructor/ownership-fixable kind, and the C++ side is already near the floor.
> 
> Without stronger compile-time guarantees, this stays a cat-and-mouse game. The proposal is to remove the largest bug class structurally rather than fix instances of it indefinitely.

– [Jarred Sumner on the bun github](https://github.com/oven-sh/bun/blob/claude/phase-a-port/docs/rust-rewrite-plan.md#why)

Thanks to [Brian Kung](https://users.rust-lang.org/t/twir-quote-of-the-week/328/1765) for the suggestion!

[Please submit quotes and vote for next week!](https://users.rust-lang.org/t/twir-quote-of-the-week/328)

This Week in Rust is edited by:

* [nellshamrell](https://github.com/nellshamrell)
* [llogiq](https://github.com/llogiq)
* [ericseppanen](https://github.com/ericseppanen)
* [extrawurst](https://github.com/extrawurst)
* [U007D](https://github.com/U007D)
* [mariannegoldin](https://github.com/mariannegoldin)
* [bdillo](https://github.com/bdillo)
* [opeolluwa](https://github.com/opeolluwa)
* [bnchi](https://github.com/bnchi)
* [KannanPalani57](https://github.com/KannanPalani57)
* [tzilist](https://github.com/tzilist)

*Email list hosting is sponsored by [The Rust Foundation](https://foundation.rust-lang.org/)*

<small>[Discuss on r/rust](REDDIT_LINK_HERE)</small>
