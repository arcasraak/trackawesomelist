# Awesome Yew Overview

😎 A curated list of awesome things related to Yew / WebAssembly.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/jetli/awesome-yew/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 jetli/awesome-yew](https://github.com/jetli/awesome-yew) · ⭐ 945 · 🏷️ Front-End Development

[ [Daily](/content/jetli/awesome-yew/README.md) / [Weekly](/content/jetli/awesome-yew/week/README.md) / Overview ]

---

# Awesome Yew [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[<img src="https://github.com/jetli/awesome-yew/raw/master/logo.svg" align="right" width="100" title="Awesome Yew">](https://github.com/yewstack/yew)

> A curated list of awesome things related to Yew.

[Yew (⭐25k)](https://github.com/yewstack/yew) is a modern Rust framework inspired by Elm and React for creating multi-threaded frontend apps with WebAssembly.

Contributions welcome! Read the [contribution guidelines](https://github.com/jetli/awesome-yew/blob/master/README.md/CONTRIBUTING.md) first.

## Contents

*   [Official](#official)
*   [Projects](#projects)
*   [Templates](#templates)
*   [Crates](#crates)
    *   [Component Libraries](#component-libraries)
    *   [Components](#components)
    *   [Hooks](#hooks)
    *   [Utils](#utils)
    *   [Wasm](#wasm)
*   [Tooling](#tooling)
*   [Articles](#articles)
*   [Books](#books)
*   [Alternatives](#alternatives)
*   [Related lists](#related-lists)

## Official

*   [Yew (⭐25k)](https://github.com/yewstack/yew) - Rust / WebAssembly framework for building client web apps.
*   [Live demo](https://yew-todomvc.netlify.com) - A todomvc demo.
*   [Examples (⭐25k)](https://github.com/yewstack/yew/tree/master/examples) - Smaller examples included in official repo.
*   [API Docs](https://docs.rs/yew) - Docs on docs.rs.
*   [Website](https://yew.rs/) - Official website.
*   [Chatroom](https://discord.gg/VQck8X4) - It is pretty active and is a great place to ask questions.
*   [Reddit](https://www.reddit.com/r/yew_web/) - Dedicated Sub Reddit.
*   [Financial Contribute](https://opencollective.com/yew) - Become a financial contributor and help us sustain our community.
*   [Playground](https://play.yew.rs) - Online playground for Yew.

## Projects

*   [Realworld example (⭐592)](https://github.com/jetli/rust-yew-realworld-example-app) - Exemplary real world app built with Rust + Yew + WebAssembly. It utilizes Yew's latest `function components` and `hooks`. It also supports desktop application powered by [Tauri (⭐54k)](https://github.com/tauri-apps/tauri).
*   [webapp.rs (⭐2k)](https://github.com/saschagrunert/webapp.rs) - A web application completely written in Rust, frontend is built with Yew.
*   [Rust-Full-Stack (⭐1.2k)](https://github.com/steadylearner/Rust-Full-Stack) - Easily testable and working Rust codes with blog posts to explain them.
*   [Bucket Questions (⭐5)](https://github.com/hgzimmerman/BucketQuestions) - A webapp written entirely in Rust for a dumb party game.
*   [web-view todomvc desktop app (⭐98)](https://github.com/Extrawurst/rust-webview-todomvc-yew) - Demo how to use yew for a todomvc that compiles to WebAssembly and is bundled as a lightweight(\~2mb) desktop app by [web-view (⭐1.8k)](https://github.com/Boscop/web-view), as an alternative to Electron, [web-view (⭐1.8k)](https://github.com/Boscop/web-view) also has a [demo (⭐1.8k)](https://github.com/Boscop/web-view/tree/master/examples#todo-yew).
*   [yew-react-example (⭐50)](https://github.com/hobofan/yew-react-example) - This project shows how to create a web app using a React component inside a Yew component.
*   [Kirk (⭐35)](https://github.com/stkevintan/Kirk) - Just A Rust WebAssembly Blog.
*   [rust-async-wasm-demo (⭐35)](https://github.com/extraymond/rust-async-wasm-demo) - Toy project to learn Rust and async that can be deployed to the web.
*   [karaoke-rs (⭐136)](https://github.com/tarkah/karaoke-rs) - A simple, network enabled karaoke player in Rust.
*   [I Love Hue! (rs) (⭐12)](https://github.com/noc7c9/i-love-hue-rs) - A clone of the mobile game I Love Hue in Yew (Rust).
*   [yew-styles-page (⭐122)](https://github.com/spielrs/yew-styles-page) - This is an initial project of a framework style for yew.
*   [caniuse.rs (⭐145)](https://github.com/jplatte/caniuse.rs) - Rust feature search.
*   [Rust electron yew demo (⭐15)](https://github.com/Extrawurst/rust-electron-demo) - An example of building a Rust based web app (Yew) into a native app using electron.
*   [covplot (⭐17)](https://github.com/jbowens/covplot) - Live graphs of worldwide CoVID-19 data.
*   [Minesweeper (⭐23)](https://github.com/jgpaiva/minesweeper) - Minesweeper built with Rust, Yew and WebAssembly.
*   [Freecell (⭐4)](https://github.com/Stigjb/freecell) - A patience game written in Rust and Yew.
*   [Yew-WebRTC-Chat (⭐107)](https://github.com/codec-abc/Yew-WebRTC-Chat) - A simple WebRTC chat made with Yew.
*   [Yew Fullstack Boilerplate (⭐42)](https://github.com/lukidoescode/yew-fullstack-boilerplate) - Highly opinionated boilerplate for creating full stack applications with Rust.
*   [Chord Quiz (⭐11)](https://github.com/Stigjb/chord-quiz) - Practice recognizing chords in this Rust/Yew/WebAssembly app.
*   [RustMart (⭐247)](https://github.com/sheshbabu/rustmart-yew-example) - Single Page Application (SPA) written using Rust, Wasm and Yew.
*   [DevAndDev (⭐38)](https://github.com/alepez/devand) - A website where developers can find pair-programming partners. Written in Rust, Yew frontend.
*   [yew-octicons (⭐16)](https://github.com/io12/yew-octicons) - An easy interface for using Octicons in Yew projects.
*   [Pipe (⭐29)](https://github.com/pipe-fun/pipe) - This is a Rust / Wasm client web app which is a task control center.
*   [note-to-yew (⭐2)](https://github.com/oovm/note-to-yew) - Convert your markups into Yew macro online, which is also made by Yew.
*   [ASCII-Hangman (⭐6)](https://github.com/getreu/ascii-hangman) - Configurable Hangman game for children with ASCII-art rewarding.
*   [dotdotyew (⭐3)](https://github.com/shaunbennett/dotdotyew) - [Dot-voting](https://en.wikipedia.org/wiki/Dot-voting) using Yew, with Rust powering the backend API.
*   [wasm-2048 (⭐140)](https://github.com/dev-family/wasm-2048) - 2048 game implemented with Rust and Yew and compiled to Wasm.
*   [website-wasm (⭐45)](https://github.com/kamiyaa/website-wasm) - My personal website written in Rust via Yew/Wasm.
*   [KeyPress (⭐6)](https://github.com/rayylee/keypress) - A Rust WebAssembly Website example for practising english for chinese.
*   [yew-train-ticket (⭐4)](https://github.com/anthhub/yew-train-ticket) - A Rust WebAssembly [Webapp](http://118.190.37.169:8002) example basing Yew newest hooks and functional API, the code style is extremely like React Function Component.
*   [yew-d3-example (⭐17)](https://github.com/ivanschuetz/yew-d3-example) - Showing a d3 chart with Yew.
*   [Oxfeed (⭐7)](https://github.com/sanpii/oxfeed) - A feed reader written in Rust with a Yew frontend.
*   [Flow.er (⭐43)](https://github.com/LighghtEeloo/flow.er) - A notebook app integrated with todo lists utility. Developed with Rust, WebAssembly, Yew and Trunk.
*   [Fullstack-Rust (⭐57)](https://github.com/vascokk/fullstack-rust) - A Full Stack Rust application (Connect5 game) with Actix-web, Yew, Bulma CSS and Diesel.
*   [Sea\_battle (⭐0)](https://github.com/MAE664128/sea_battle) - A simple example of a sea battle game. Rust + Yew.
*   [tide-async-graphql-mongodb (⭐32)](https://github.com/zzy/tide-async-graphql-mongodb) - Clean boilerplate for graphql services, with wasm/yew frontend.
*   [surfer (⭐42)](https://github.com/zzy/surfer) - A blog built on yew + graphql, with [live demo site](https://niqin.com). Backend for graphql services, and frontend for web application.
*   [qubit](https://abhimanyu003.github.io/qubit) - A handy calculator, based on Rust and WebAssembly, [Live Demo](https://abhimanyu003.github.io/qubit/).
*   [Paudle (⭐40)](https://github.com/pmsanford/paudle) - A reimplementation of the excellent word game Wordle by Josh Wardle.
*   [Rust algorithms (⭐24)](https://github.com/Jondolf/rust-algorithms) - A website with interactive implementations of various algorithms (only sorting algorithms for now).
*   [Marc Portfolio](https://gitlab.com/marcempunkt/maeurerdev) - A software developer portfolio, [Live Demo](https://maeurer.dev/).
*   [zzhack (⭐180)](https://github.com/zzhack-stack/zzhack) - A personal blog, based on Rust & Yew, [Live Demo](https://www.zzhack.fun/).
*   [Rquote (⭐3)](https://github.com/Altair-Bueno/rquote) - Rquote is a web application built using Rust and WebAssembly. It fetches Anime quotes from the Animechan API. [Live Demo](https://rquote.vercel.app/).
*   [yew-ssr-tide (⭐1)](https://github.com/zzy/yew-ssr-tide) - The example demonstrates Yew server-side rendering with tide & surf, it needs the **development version** of Yew.
*   [yew-ssr-actix-web (⭐6)](https://github.com/zzy/yew-ssr-actix-web) - The example demonstrates Yew server-side rendering with actix-web & reqwest, it needs the **development version** of Yew.
*   [PixelGuesser (⭐4)](https://github.com/tdooms/pixelguesser) - PixelGuesser is a real life party gam where players try to guess the contents of an image as quickly as possible.
*   [Crabtyper (⭐182)](https://github.com/brancobruyneel/crabtyper) - A speedtyping web app written in Rust.
*   [We-Come Monorepo (⭐1)](https://github.com/kabinetkmitb/wecome) - This is a monorepo for wecome KM ITB, [Live Demo](https://wecome-itb.com/).
*   [blog-rs (⭐37)](https://github.com/songday/blog-rs) - A blog system in which frontend and backend are ALL written in Rust. Backend powered by Warp and frontend built on Yew (WASM).
*   [mb2](https://devctm.com) - A poker server with a Yew client. Click the `Demo` button and then `Start` to see the client.
*   [Puzzle Cube (⭐4)](https://github.com/wainwrightmark/puzzle_cube) - Rubix Cube solver using Rust and Yew, [Live Demo](https://wainwrightmark.github.io/puzzle_cube/).
*   [CubeShuffle (⭐15)](https://github.com/philipborg/CubeShuffle) - Card game shuffling utility built with Rust, Yew, Bulma and Tauri.
*   [Rust Audio (⭐25)](https://github.com/austintheriot/audio) - Realtime audio processing / synthesis using Rust/WASM in the browser, [Live Demo](https://austintheriot.github.io/audio/).
*   [Kiomet](https://kiomet.com) - An online real-time strategy game in which you expand your territory by capturing towers.
*   [Portfolio website (⭐7)](https://github.com/simbleau/website) - A portfolio SPA with accessibility built-in by Spencer Imbleau.
*   [tchatche.rs (⭐82)](https://github.com/nag763/tchatchers) - A Websocket chat based application built in Yew and Axum.
*   [viz.rs (⭐1)](https://github.com/viz-rs/viz-rs.github.io) - A website for viz web framework, [Live Demo](https://viz.rs/).
*   [theiskaa.com (⭐2)](https://github.com/theiskaa/theiskaa.com) - A real world implementation of Yew framework. [Live at theiskaa.com](https://theiskaa.com)

## Templates

*   [Create Yew App (⭐130)](https://github.com/jetli/create-yew-app) - Set up a modern Yew web app by running one command, `npx create-yew-app my-app`.
*   [yew-wasm-pack-template (⭐116)](https://github.com/yewstack/yew-wasm-pack-template) - A template for starting a Yew project to be used with wasm-pack.
*   [yew-wasm-pack-minimal (⭐108)](https://github.com/yewstack/yew-wasm-pack-minimal) - A minimal template for starting a Yew project using wasm-bindgen and wasm-pack.
*   [yew-parcel-template (⭐113)](https://github.com/spielrs/yew-parcel-template) - Awesome Yew with Yew-Router and Parcel application.
*   [yew-template-for-github-io (⭐16)](https://github.com/Ja-sonYun/yew-template-for-github-io) - Directly deployable Template of yew project for github.io, using tailwind and webpack for css, trunk for build and serve.
*   [tailwindcss-yew-template (⭐8)](https://github.com/vvcaw/tailwindcss-yew-template) - Simple layout for using Tailwindcss with Yew.
*   [axum-yew-setup (⭐80)](https://github.com/rksm/axum-yew-setup) - A starter project that sets up Axum and Yew for full stack Rust web apps.
*   [rust-yew-axum-tauri-desktop (⭐47)](https://github.com/jetli/rust-yew-axum-tauri-desktop) - Rust + Yew + Axum + Tauri, full-stack Rust development for Desktop apps.
*   [Yew PWA Minimal (⭐27)](https://github.com/fkohlgrueber/yew-pwa-minimal) - A minimal Progressive Web App using Yew.
*   [Yew HTTP Starter (⭐2)](https://github.com/LeTurt333/yew_http_starter) - Yew template with a simple HTTP message & useful helper comments.

## Crates

### Component Libraries

*   [yew-mdc (⭐56)](https://github.com/dungeonfog/yew-mdc) - Material Design Components for the Yew framework.
*   [muicss-yew (⭐25)](https://github.com/AlephAlpha/muicss-yew) - MUI-CSS Components for Yew framework.
*   [yew-bulma (⭐15)](https://github.com/kellpossible/yew-bulma) - A Rust library providing components based on the bulma css library for projects using Yew.
*   [material-yew (⭐155)](https://github.com/hamza1311/material-yew) - Yew wrapper for Material Web Components.
*   [Yewprint (⭐334)](https://github.com/yewprint/yewprint) - Port of blueprintjs.com to Yew.
*   [ybc (⭐192)](https://github.com/thedodd/ybc) - A Yew component library based on the Bulma CSS framework.
*   [patternfly-yew (⭐68)](https://github.com/ctron/patternfly-yew) - Patternfly components for Yew.
*   [yew-feather (⭐8)](https://github.com/pedrodesu/yew-feather) - Feather Icons components for Yew.
*   [tailwind-yew-builder (⭐55)](https://github.com/matiu2/tailwind-yew-builder) - Builds Tailwind CSS for Yew using docker-compose. Also supports Trunk.
*   [yew-components (⭐48)](https://github.com/angular-rust/yew-components) - Material Design Components for the Yew framework.
*   [yew-chart (⭐37)](https://github.com/titanclass/yew-chart) - A Yew-based charting library that provides SVG based components for rendering charts.
*   [tailyew (⭐9)](https://github.com/fuzzycloud/tailyew) - Yew wrapper around DaisyUI (tailwindcss based) components.

### Components

*   [Yew Form (⭐77)](https://github.com/jfbilodeau/yew_form) - Components to simplify handling forms with Yew.
*   [yew-component-size (⭐3)](https://github.com/AircastDev/yew-component-size) - A Yew component that emits events when the parent component changes width/height.
*   [yew-virtual-scroller (⭐4)](https://github.com/AircastDev/yew-virtual-scroller) - A Yew component for virtual scrolling / scroll windowing.
*   [yew-oauth2 (⭐10)](https://github.com/ctron/yew-oauth2/) - A plain Yew OAuth2/OpenIDConnect component, not tied to any CSS framework.
*   [yew-scroll-area (⭐0)](https://github.com/MatchaChoco010/yew-scroll-area) - Custom scroll area for Yew.

### Hooks

*   [yew-hooks (⭐96)](https://github.com/jetli/yew-hooks) - Custom Hooks library for Yew, inspired by [streamich/react-use (⭐34k)](https://github.com/streamich/react-use) and [alibaba/hooks (⭐11k)](https://github.com/alibaba/hooks).
*   [yew-side-effect (⭐3)](https://github.com/futursolo/yew-side-effect) - Reconcile Side Effects in Yew Applications, inspired by [react-side-effect (⭐1.2k)](https://github.com/gaearon/react-side-effect) and [react-helmet (⭐17k)](https://github.com/nfl/react-helmet).
*   [Bounce (⭐63)](https://github.com/bounce-rs/bounce) - The uncomplicated state management library for Yew, inspired by [Redux (⭐59k)](https://github.com/reduxjs/redux) and [Recoil (⭐18k)](https://github.com/facebookexperimental/Recoil).
*   [yewv (⭐5)](https://github.com/yewv/yewv) - A lightning fast state management module for Yew built with performance and simplicity as a first priority.

### Javascript Library Ports

*   [Plotly.rs (⭐626)](https://github.com/igiagkiozis/plotly) - Rust bindings for the popular [Plotly](https://plotly.com/javascript/) charting library.
*   [ag-grid-rs (⭐5)](https://github.com/mfreeborn/ag-grid-rs) - Rust bindings for the [AG Grid](https://www.ag-grid.com/javascript-data-grid/) datatable library.

### Utils

*   [Yewdux (⭐204)](https://github.com/intendednull/yewdux) - Redux-like state containers for Yew apps.
*   [reacty\_yew (⭐44)](https://github.com/hobofan/reacty_yew) - Generate Yew components from React components via Typescript type definitions.
*   [styled-yew (⭐26)](https://github.com/IcyDefiance/styled-yew) - CSS in Rust, similar to styled-components, but for Yew.
*   [stylist-rs (⭐168)](https://github.com/futursolo/stylist-rs) - A CSS-in-Rust styling solution for WebAssembly Applications.
*   [Yew Interop (⭐28)](https://github.com/Madoshakalaka/yew-interop) - Load JavaScript and CSS asynchronously in Yew.
*   [Tailwind RS (⭐54)](https://github.com/oovm/tailwind-rs) - Tailwind style tracer in rust, JIT + AOT interpreter.
*   [yew-style-in-rs (⭐18)](https://github.com/MatchaChoco010/yew-style-in-rs) - Scoped CSS in Rust for Yew.
*   [yew\_icons (⭐13)](https://github.com/finnbear/yew_icons) - Easily include a variety of svg icons(Feather/Font Awesome/Octicons) into your Yew app.
*   [Yew-Template (⭐16)](https://github.com/INSAgenda/yew-template) - A crate for separating HTML and Rust code when using Yew.

### Wasm

*   [wasm-bindgen (⭐5.8k)](https://github.com/rustwasm/wasm-bindgen) - Facilitating high-level interactions between WebAssembly modules and JavaScript.
*   [stdweb (⭐3.3k)](https://github.com/koute/stdweb) - Provides Rust bindings to the Web APIs and to allow a high degree of interoperability between Rust and JavaScript.

## Tooling

*   [wasm-pack (⭐4.7k)](https://github.com/rustwasm/wasm-pack) - Your favorite Rust -> WebAssembly workflow tool.
*   [wasm-pack-action (⭐33)](https://github.com/jetli/wasm-pack-action) - Github action to install `wasm-pack` by downloading the executable to speed up CI/CD.
*   [wasm-bindgen-action (⭐8)](https://github.com/jetli/wasm-bindgen-action) - Github action to install `wasm-bindgen` by downloading the executable to speed up CI/CD.
*   [cargo-web (⭐1.1k)](https://github.com/koute/cargo-web) - A Cargo subcommand for the client-side Web.
*   [Trunk (⭐2.1k)](https://github.com/thedodd/trunk) - Build, bundle & ship your Rust Wasm application to the web.
*   [trunk-action (⭐14)](https://github.com/jetli/trunk-action) - Github action to install `Trunk` by downloading the executable to speed up CI/CD.
*   [wabt (⭐4.9k)](https://github.com/WebAssembly/wabt) - The WebAssembly Binary Toolkit, for the `wasm-strip` and `wasm-objdump` tools to reduce .wasm file size.
*   [binaryen (⭐6k)](https://github.com/WebAssembly/binaryen) - Compiler infrastructure and toolchain library for WebAssembly, for the `wasm-opt` tool to reduce .wasm file size.

## Articles

*   [Let's Build a Rust Frontend with Yew](https://dev.to/deciduously/lets-build-a-rust-frontend-with-yew---part-1-3k2o)
*   [How to use Rust Yew (⭐0)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20Rust%20Yew.md)
*   [How to use a modal in Rust (⭐0)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20a%20modal%20in%20Rust.md)
*   [How to use routers in Rust Frontend (⭐0)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20routers%20in%20Rust%20Frontend.md)
*   [How to modulize your Rust Frontend (⭐0)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20modulize%20your%20Rust%20Frontend.md)
*   [How to use NPM packages with Rust Frontend (⭐0)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20use%20NPM%20packages%20with%20Rust%20Frontend.md)
*   [How to use markdown with Rust Frontend (⭐0)](https://github.com/steadylearner/blog/blob/master/posts/Rust/How%20to%20use%20markdown%20with%20code%20snippets%20in%20Rust%20Frontend.md)
*   [Fullstack Rust with Yew (⭐0)](https://github.com/steadylearner/blog/tree/master/posts/Rust/Fullstack%20Rust%20with%20Yew.md)
*   [How to write Full Stack Rust code (⭐0)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20write%20Full%20Stack%20Rust%20code.md)
*   [How to render a YouTube vlog with Rust Yew fetch API (⭐0)](https://github.com/steadylearner/blog/blob/master/posts/Rust/How%20to%20render%20a%20YouTube%20vlog%20with%20%20Rust%20Yew%20fetch%20API.md)
*   [How to render blog posts with Rust Yew mounted API (⭐0)](https://github.com/steadylearner/blog/tree/master/posts/Rust/How%20to%20render%20blog%20posts%20with%20Rust%20Yew%20mounted%20API.md)
*   [A Web Application completely in Rust](https://medium.com/@saschagrunert/a-web-application-completely-in-rust-6f6bdb6c4471)
*   [Yew - Rust & WebAsse-frontend framework](https://sudonull.com/post/11627-Yew-Rust-WebAsse-frontend-framework)
*   [Create a desktop app in Rust using Tauri and Yew](https://dev.to/stevepryde/create-a-desktop-app-in-rust-using-tauri-and-yew-2bhe)
*   [A code walkthrough video of Yew with a real-world app with Christopher Hunt and Kiki Carter](https://www.youtube.com/watch?v=ilrGIJGdqRo)

## Courses

*   [full-stack-todo-rust-course (⭐46)](https://github.com/brooks-builds/full-stack-todo-rust-course) - Full stack rust course including course for Yew.

## Books

*   [The WebAssembly Book](https://rustwasm.github.io/docs/book/) - Working with the web and producing .wasm files.
*   [The wasm-bindgen Guide](https://rustwasm.github.io/docs/wasm-bindgen/) - How to bind Rust and JavaScript APIs.
*   [The wasm-pack Guide](https://rustwasm.github.io/docs/wasm-pack/) - How to build and work with rust-generated WebAssembly.
*   [Programming WebAssembly with Rust](https://pragprog.com/book/khrust/programming-webassembly-with-rust) - Includes a chapter `Advanced JavaScript Integration with Yew` on creating an app with Yew.
*   [Creative Projects for Rust Programmers](https://www.oreilly.com/library/view/creative-projects-for/9781789346220/) - Chapter 5, `Creating a Client-Side WebAssembly App Using Yew`.

## Alternatives

Yew team love to share ideas with other projects and believe we can all help each other reach the full potential of this exciting new technology.

*   [Draco (⭐300)](https://github.com/utkarshkukreti/draco) - A Rust library for building client side web applications with WebAssembly.
*   [Percy (⭐2.1k)](https://github.com/chinedufn/percy) - A modular toolkit for building isomorphic web apps with Rust + WebAssembly.
*   [Sauron (⭐1.7k)](https://github.com/ivanceras/sauron) - Sauron is an HTML web framework for building web-apps.
*   [Seed (⭐3.5k)](https://github.com/seed-rs/seed) - A Rust framework for creating web apps.
*   [Smithy (⭐337)](https://github.com/rbalicki2/smithy) - A framework for building WebAssembly apps in Rust.
*   [Dioxus (⭐5.2k)](https://github.com/DioxusLabs/dioxus) - Elegant React-like library for building user interfaces for desktop, web, mobile, SSR, liveview, and more.
*   [Sycamore (⭐1.7k)](https://github.com/sycamore-rs/sycamore) - A reactive library for creating web apps in Rust and WebAssembly.

## Related lists

*   [Awesome Rust and WebAssembly (⭐515)](https://github.com/rustwasm/awesome-rust-and-webassembly) - A list of awesome Rust and WebAssembly projects, libraries, tools, and resources.
*   [Awesome WebAssembly (⭐7.3k)](https://github.com/mbasso/awesome-wasm) - Collection of awesome things regarding WebAssembly ecosystem.
*   [Awesome Rust (⭐30k)](https://github.com/rust-unofficial/awesome-rust) - A curated list of Rust code and resources.

