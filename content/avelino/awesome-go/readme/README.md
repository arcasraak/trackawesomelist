# Awesome Go Overview

A curated list of awesome Go frameworks, libraries and software

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/avelino/awesome-go/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 avelino/awesome-go](https://github.com/avelino/awesome-go) · ⭐ 91K · 🏷️ Programming Languages

[ [Daily](/content/avelino/awesome-go/README.md) / [Weekly](/content/avelino/awesome-go/week/README.md) / Overview ]

---

# Awesome Go

<a href="https://awesome-go.com/"><img align="right" src="https://github.com/avelino/awesome-go/raw/main/tmpl/assets/logo.png" alt="awesome-go" title="awesome-go" /></a>

[![Build Status](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml/badge.svg?branch=main)](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml?query=branch%3Amain)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true\&logo=slack\&colorB=red)](https://gophers.slack.com/messages/awesome)
[![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/avelino/awesome-go/)

We use the *[Golang Bridge (⭐345)](https://github.com/gobridge/about-us/blob/master/README.md)* community slack for instant communication, follow the [form here to join](https://invite.slack.golangbridge.org/).

<a href="https://www.producthunt.com/posts/awesome-go?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-awesome-go" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=291535&theme=light" alt="awesome-go - Curated list awesome Go frameworks, libraries and software | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

**Sponsorships:**

*Special thanks to*

<div align="center">
<table cellpadding="5">
<tbody align="center">
<tr>
<td colspan="2">
<a href="https://bit.ly/awesome-go-doppler">
<img src="https://avelino.run/sponsors/doppler-logo.png" width="200" alt="Doppler"><br/>
<b>Quit struggling with scattered API keys and access controls.</b><br/>
<sub>Keep your secrets in sync across environments, servers, and teams with Doppler.</sub>
</a>
</td>
</tr>
<tr>
<td>
<a href="https://bit.ly/awesome-go-workos">
<img src="https://avelino.run/sponsors/workos-logo-white-bg.svg" width="200" alt="WorkOS"><br/>
<b>Your app, enterprise-ready.</b><br/>
<sub>Start selling to enterprise customers with just a few lines of code.</sub><br/>
<sup>Add Single Sign-On (and more) in minutes instead of months.</sup>
</a>
</td>
<td>
<a href="https://bit.ly/awesome-go-keygen">
<img src="https://avelino.run/sponsors/keygen-logo.png" width="200" alt="keygen"><br/>
<b>A dead-simple software licensing and distribution API built for developers</b><br/>
<sub>Securely license and distribute Go applications with a single API.</sub><br>
<sup>Add auto updates with only a few lines of code.</sup>
</a>
</td>
</tr>
<tr>
<td colspan="2">
<a href="https://bit.ly/awesome-go-digitalocean">
<img src="https://avelino.run/sponsors/do_logo_horizontal_blue-210.png" width="200" alt="Digital Ocean">
</a>
</td>
</tr>
</tbody>
</table>
</div>

**Awesome Go has no monthly fee***, but we have employees who **work hard** to keep it running. With money raised, we can repay the effort of each person involved! You can see how we calculate our billing and distribution as it is open to the entire community. Want to be a supporter of the project click [here](https://github.com/avelino/awesome-go/blob/main/README.md/mailto:avelinorun+oss@gmail.com?subject=awesome-go%3A%20project%20support).*

> A curated list of awesome Go frameworks, libraries, and software. Inspired by [awesome-python (⭐146k)](https://github.com/vinta/awesome-python).

**Contributing:**

Please take a quick gander at the [contribution guidelines (⭐90k)](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors (⭐90k)](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

> *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

## Contents

*   [Awesome Go](#awesome-go)
    *   [Contents](#contents)
    *   [Audio and Music](#audio-and-music)
    *   [Authentication and OAuth](#authentication-and-oauth)
    *   [Blockchain](#blockchain)
    *   [Bot Building](#bot-building)
    *   [Build Automation](#build-automation)
    *   [Command Line](#command-line)
        *   [Advanced Console UIs](#advanced-console-uis)
        *   [Standard CLI](#standard-cli)
    *   [Configuration](#configuration)
    *   [Continuous Integration](#continuous-integration)
    *   [CSS Preprocessors](#css-preprocessors)
    *   [Data Structures and Algorithms](#data-structures-and-algorithms)
        *   [Bit-packing and Compression](#bit-packing-and-compression)
        *   [Bit Sets](#bit-sets)
        *   [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
        *   [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
        *   [Iterators](#iterators)
        *   [Maps](#maps)
        *   [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
        *   [Nullable Types](#nullable-types)
        *   [Queues](#queues)
        *   [Sets](#sets)
        *   [Text Analysis](#text-analysis)
        *   [Trees](#trees)
        *   [Pipes](#pipes)
    *   [Database](#database)
        *   [Caches](#caches)
        *   [Databases Implemented in Go](#databases-implemented-in-go)
        *   [Database Schema Migration](#database-schema-migration)
        *   [Database Tools](#database-tools)
        *   [SQL Query Builders](#sql-query-builders)
    *   [Database Drivers](#database-drivers)
        *   [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
        *   [Relational Database Drivers](#relational-database-drivers)
        *   [NoSQL Database Drivers](#nosql-database-drivers)
        *   [Search and Analytic Databases](#search-and-analytic-databases)
    *   [Date and Time](#date-and-time)
    *   [Distributed Systems](#distributed-systems)
    *   [Dynamic DNS](#dynamic-dns)
    *   [Email](#email)
    *   [Embeddable Scripting Languages](#embeddable-scripting-languages)
    *   [Error Handling](#error-handling)
    *   [File Handling](#file-handling)
    *   [Financial](#financial)
    *   [Forms](#forms)
    *   [Functional](#functional)
    *   [Game Development](#game-development)
    *   [Generators](#generators)
    *   [Geographic](#geographic)
    *   [Go Compilers](#go-compilers)
    *   [Goroutines](#goroutines)
    *   [GUI](#gui)
    *   [Hardware](#hardware)
    *   [Images](#images)
    *   [IoT (Internet of Things)](#iot-internet-of-things)
    *   [Job Scheduler](#job-scheduler)
    *   [JSON](#json)
    *   [Logging](#logging)
    *   [Machine Learning](#machine-learning)
    *   [Messaging](#messaging)
    *   [Microsoft Office](#microsoft-office)
        *   [Microsoft Excel](#microsoft-excel)
    *   [Miscellaneous](#miscellaneous)
        *   [Dependency Injection](#dependency-injection)
        *   [Project Layout](#project-layout)
        *   [Strings](#strings)
        *   [Uncategorized](#uncategorized)
    *   [Natural Language Processing](#natural-language-processing)
        *   [Language Detection](#language-detection)
        *   [Morphological Analyzers](#morphological-analyzers)
        *   [Slugifiers](#slugifiers)
        *   [Tokenizers](#tokenizers)
        *   [Translation](#translation)
        *   [Transliteration](#transliteration)
    *   [Networking](#networking)
        *   [HTTP Clients](#http-clients)
    *   [OpenGL](#opengl)
    *   [ORM](#orm)
    *   [Package Management](#package-management)
    *   [Performance](#performance)
    *   [Query Language](#query-language)
    *   [Resource Embedding](#resource-embedding)
    *   [Science and Data Analysis](#science-and-data-analysis)
    *   [Security](#security)
    *   [Serialization](#serialization)
    *   [Server Applications](#server-applications)
    *   [Stream Processing](#stream-processing)
    *   [Template Engines](#template-engines)
    *   [Testing](#testing)
    *   [Text Processing](#text-processing)
        *   [Formatters](#formatters)
        *   [Markup Languages](#markup-languages)
        *   [Parsers/Encoders/Decoders](#parsersencodersdecoders)
        *   [Regular Expressions](#regular-expressions)
        *   [Sanitation](#sanitation)
        *   [Scrapers](#scrapers)
        *   [RSS](#rss)
        *   [Utility/Miscellaneous](#utilitymiscellaneous)
    *   [Third-party APIs](#third-party-apis)
    *   [Utilities](#utilities)
    *   [UUID](#uuid)
    *   [Validation](#validation)
    *   [Version Control](#version-control)
    *   [Video](#video)
    *   [Web Frameworks](#web-frameworks)
        *   [Middlewares](#middlewares)
            *   [Actual middlewares](#actual-middlewares)
            *   [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        *   [Routers](#routers)
    *   [WebAssembly](#webassembly)
    *   [Windows](#windows)
    *   [XML](#xml)
    *   [Zero Trust](#zero-trust)
    *   [Code Analysis](#code-analysis)
    *   [Editor Plugins](#editor-plugins)
    *   [Go Generate Tools](#go-generate-tools)
    *   [Go Tools](#go-tools)
    *   [Software Packages](#software-packages)
        *   [DevOps Tools](#devops-tools)
        *   [Other Software](#other-software)
*   [Resources](#resources)
    *   [Benchmarks](#benchmarks)
    *   [Conferences](#conferences)
    *   [E-Books](#e-books)
        *   [E-books for purchase](#e-books-for-purchase)
        *   [Free e-books](#free-e-books)
    *   [Gophers](#gophers)
    *   [Meetups](#meetups)
    *   [Style Guides](#style-guides)
    *   [Social Media](#social-media)
        *   [Twitter](#twitter)
        *   [Reddit](#reddit)
    *   [Websites](#websites)
        *   [Tutorials](#tutorials)

**[⬆ back to top](#contents)**

## Audio and Music

*Libraries for manipulating audio.*

*   [flac (⭐225)](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams.
*   [gaad (⭐107)](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser.
*   [GoAudio (⭐264)](https://github.com/DylanMeeus/GoAudio) - Native Go Audio Processing Library.
*   [gosamplerate (⭐24)](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go.
*   [id3v2 (⭐269)](https://github.com/bogem/id3v2) - ID3 decoding and encoding library for Go.
*   [malgo (⭐205)](https://github.com/gen2brain/malgo) - Mini audio library.
*   [minimp3 (⭐91)](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library.
*   [Oto (⭐1.1k)](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms.
*   [PortAudio (⭐543)](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library.

**[⬆ back to top](#contents)**

## Authentication and OAuth

*Libraries for implementing authentication schemes.*

*   [authboss (⭐3.3k)](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure it, and start building your app without having to build an authentication system each time.
*   [branca (⭐47)](https://github.com/essentialkaos/branca) - branca token [specification implementation (⭐191)](https://github.com/tuupola/branca-spec) for Golang 1.15+.
*   [casbin (⭐13k)](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, and ABAC.
*   [cookiestxt (⭐14)](https://github.com/mengzhuo/cookiestxt) - provides a parser of cookies.txt file format.
*   [go-guardian (⭐415)](https://github.com/shaj13/go-guardian) - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token, and Certificate based authentication.
*   [go-jose (⭐2k)](https://github.com/square/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
*   [gologin (⭐1.6k)](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
*   [gorbac (⭐1.4k)](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang.
*   [gosession (⭐12)](http://github.com/Kwynto/gosession) - This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, or at least it tries to become one.
*   [goth (⭐3.9k)](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
*   [jeff (⭐243)](https://github.com/abraithwaite/jeff) - Simple, flexible, secure, and idiomatic web session management with pluggable backends.
*   [jwt (⭐300)](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library.
*   [jwt (⭐576)](https://github.com/cristalhq/jwt) - Safe, simple, and fast JSON Web Tokens for Go.
*   [jwt-auth (⭐223)](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options.
*   [keto (⭐3.7k)](https://github.com/ory/keto) - Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models.
*   [loginsrv (⭐1.9k)](https://github.com/tarent/loginsrv) - JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.
*   [oauth2 (⭐4.4k)](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine, and App Engine support.
*   [osin (⭐1.8k)](https://github.com/openshift/osin) - Golang OAuth2 server library.
*   [otpgen (⭐121)](https://github.com/grijul/otpgen) - Library to generate TOTP/HOTP codes.
*   [otpgo (⭐41)](https://github.com/jltorresm/otpgo) - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go.
*   [paseto (⭐645)](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO).
*   [permissions2 (⭐468)](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states, and permissions. Uses secure cookies and bcrypt.
*   [scope (⭐24)](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go.
*   [scs (⭐1.2k)](https://github.com/alexedwards/scs) - Session Manager for HTTP servers.
*   [securecookie (⭐63)](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding.
*   [session (⭐110)](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE).
*   [sessions (⭐67)](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers.
*   [sessionup (⭐120)](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package.
*   [sjwt (⭐105)](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser.

**[⬆ back to top](#contents)**

## Blockchain

*Tools for building blockchains.*

*   [cosmos-sdk (⭐4.7k)](https://github.com/cosmos/cosmos-sdk) - A Framework for Building Public Blockchains in the Cosmos Ecosystem.
*   [go-ethereum (⭐40k)](https://github.com/ethereum/go-ethereum) - Official Go implementation of the Ethereum protocol.
*   [gossamer (⭐361)](https://github.com/ChainSafe/gossamer) - A Go implementation of the Polkadot Host.
*   [solana-go (⭐380)](https://github.com/gagliardetto/solana-go) - Go library to interface with Solana JSON RPC and WebSocket interfaces.
*   [tendermint (⭐5.3k)](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.

**[⬆ back to top](#contents)**

## Bot Building

*Libraries for building and working with bots.*

*   [echotron (⭐200)](https://github.com/NicoNex/echotron) - An elegant and concurrent library for Telegram Bots in Go.
*   [ephemeral-roles (⭐69)](https://github.com/ewohltman/ephemeral-roles) - A Discord bot for managing ephemeral roles based upon voice channel member presence.
*   [go-chat-bot (⭐765)](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go.
*   [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.
*   [go-sarah (⭐251)](https://github.com/oklahomer/go-sarah) - Framework to build a bot for desired chat services including LINE, Slack, Gitter, and more.
*   [go-tgbot (⭐117)](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router, and middleware.
*   [go-twitch-irc (⭐262)](https://github.com/gempir/go-twitch-irc) - Library to write bots for twitch.tv chat
*   [Golang CryptoTrading Bot (⭐841)](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges.
*   [govkbot (⭐41)](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library.
*   [hanu (⭐142)](https://github.com/sbstjn/hanu) - Framework for writing Slack bots.
*   [Kelp (⭐944)](https://github.com/stellar/kelp) - official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies.
*   [larry (⭐92)](https://github.com/ezeoleaf/larry) - Larry 🐦 is a really simple Twitter bot generator that tweets random repositories from Github built in Go.
*   [margelet (⭐76)](https://github.com/zhulik/margelet) - Framework for building Telegram bots.
*   [micha (⭐24)](https://github.com/onrik/micha) - Go Library for Telegram bot api.
*   [olivia (⭐3.3k)](https://github.com/olivia-ai/olivia) - A chatbot built with an artificial neural network.
*   [slack-bot (⭐123)](https://github.com/innogames/slack-bot) - Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github...
*   [slacker (⭐703)](https://github.com/shomali11/slacker) - Easy to use framework to create Slack bots.
*   [slackscot (⭐54)](https://github.com/alexandre-normand/slackscot) - Another framework for building Slack bots.
*   [tbot (⭐333)](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http.
*   [telebot (⭐2.8k)](https://github.com/tucnak/telebot) - Telegram bot framework is written in Go.
*   [telego (⭐118)](https://github.com/mymmrac/telego) - Telegram Bot API library for Golang with full one-to-one API implementation.
*   [telegram-bot-api (⭐4.1k)](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client.
*   [teleterm (⭐14)](https://github.com/alfiankan/teleterm) - Telegram Bot Exec Terminal Command.
*   [Tenyks (⭐174)](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging.
*   [wayback (⭐360)](https://github.com/wabarc/wayback) - A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages.

**[⬆ back to top](#contents)**

## Build Automation

*Libraries and tools help with build automation.*

*   [1build (⭐189)](https://github.com/gopinath-langote/1build) - Command line tool to frictionlessly manage project-specific commands.
*   [anko (⭐28)](https://github.com/GuilhermeCaruso/anko) - Simple application watcher for multiple programming languages.
*   [gaper (⭐60)](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes.
*   [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
*   [goyek (⭐326)](https://github.com/goyek/goyek) - Create build pipelines in Go.
*   [mage (⭐3.3k)](https://github.com/magefile/mage) - Mage is a make/rake-like build tool using Go.
*   [mmake (⭐1.6k)](https://github.com/tj/mmake) - Modern Make.
*   [realize (⭐4.3k)](https://github.com/tockins/realize) - Go build a system with file watchers and live to reload. Run, build and watch file changes with custom paths.
*   [Task (⭐6k)](https://github.com/go-task/task) - simple "Make" alternative.
*   [taskctl (⭐228)](https://github.com/taskctl/taskctl) - Concurrent task runner.

**[⬆ back to top](#contents)**

## Command Line

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

*   [asciigraph (⭐2.1k)](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
*   [aurora (⭐1.3k)](https://github.com/logrusorgru/aurora) - ANSI terminal colors that support fmt.Printf/Sprintf.
*   [box-cli-maker (⭐296)](https://github.com/Delta456/box-cli-maker) - Make Highly Customized Boxes for your CLI.
*   [bubbletea (⭐16k)](https://github.com/charmbracelet/bubbletea) - Go framework to build terminal apps, based on The Elm Architecture.
*   [cfmt (⭐90)](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes.
*   [cfmt (⭐52)](https://github.com/i582/cfmt) - Simple and convenient formatted stylized output fully compatible with fmt library.
*   [chalk (⭐412)](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output.
*   [colourize (⭐26)](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals.
*   [crab-config-files-templating (⭐6)](https://github.com/alfiankan/crab-config-files-templating) - Dynamic configuration file templating tool for kubernetes manifest or general configuration files.
*   [ctc (⭐42)](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method.
*   [go-ataman (⭐13)](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals.
*   [go-colorable (⭐657)](https://github.com/mattn/go-colorable) - Colorable writer for windows.
*   [go-colortext (⭐215)](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals.
*   [go-isatty (⭐651)](https://github.com/mattn/go-isatty) - isatty for golang.
*   [go-prompt (⭐4.7k)](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit (⭐8k)](https://github.com/jonathanslenders/python-prompt-toolkit).
*   [gocui (⭐8.6k)](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces.
*   [gommon/color (⭐471)](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
*   [gookit/color (⭐1.2k)](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
*   [marker (⭐34)](https://github.com/cyucelen/marker) - Easiest way to match and mark strings for colorful terminal outputs.
*   [mpb (⭐1.9k)](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications.
*   [progressbar (⭐2.9k)](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS.
*   [pterm (⭐3.1k)](https://github.com/pterm/pterm) - A library to beautify console output on every platform with many combinable components.
*   [simpletable (⭐397)](https://github.com/alexeyco/simpletable) - Simple tables in a terminal with Go.
*   [spinner (⭐1.9k)](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options.
*   [tabby (⭐323)](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables.
*   [table (⭐40)](https://github.com/tomlazar/table) - Small library for terminal color based tables .
*   [tabular (⭐68)](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.
*   [termbox-go (⭐4.4k)](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces.
*   [termdash (⭐2.1k)](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by [termui (⭐12k)](https://github.com/gizak/termui).
*   [termenv (⭐1.2k)](https://github.com/muesli/termenv) - Advanced ANSI style & color support for your terminal applications.
*   [termui (⭐12k)](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib (⭐15k)](https://github.com/yaronn/blessed-contrib).
*   [uilive (⭐1.5k)](https://github.com/gosuri/uilive) - Library for updating terminal output in real time.
*   [uiprogress (⭐2k)](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications.
*   [uitable (⭐670)](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data.
*   [yacspin (⭐383)](https://github.com/theckman/yacspin) - Yet Another CLi Spinner package, for working with terminal spinners.

**[⬆ back to top](#contents)**

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

*   [acmd (⭐63)](https://github.com/cristalhq/acmd) - Simple, useful, and opinionated CLI package in Go.
*   [argparse (⭐469)](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module.
*   [argv (⭐36)](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax.
*   [carapace (⭐58)](https://github.com/rsteube/carapace) - Command argument completion generator for spf13/cobra.
*   [carapace-bin (⭐101)](https://github.com/rsteube/carapace-bin) - Multi-shell multi-command argument completer.
*   [carapace-spec (⭐3)](https://github.com/rsteube/carapace-spec) - Define simple completions using a spec file.
*   [cli (⭐673)](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags.
*   [cli (⭐116)](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go.
*   [climax (⭐201)](https://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command.
*   [clîr (⭐127)](https://github.com/leaanthony/clir) - A Simple and Clear CLI library. Dependency free.
*   [cmd (⭐35)](https://github.com/posener/cmd) - Extends the standard `flag` package to support sub commands and more in idiomatic way.
*   [cmdr (⭐116)](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library.
*   [cobra (⭐29k)](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions.
*   [command-chain (⭐34)](https://github.com/rainu/go-command-chain) - A go library for configure and run command chains - such as pipelining in unix shells.
*   [commandeer (⭐161)](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
*   [complete (⭐866)](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion.
*   [Dnote (⭐2.4k)](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync.
*   [elvish (⭐4.9k)](https://github.com/elves/elvish) - An expressive programming language and a versatile interactive shell.
*   [env (⭐99)](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs.
*   [flag (⭐123)](https://github.com/cosiner/flag) - Simple but powerful command line option parsing library for Go supporting subcommand.
*   [flaggy (⭐816)](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support.
*   [flagvar (⭐41)](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package.
*   [go-andotp (⭐18)](https://github.com/grijul/go-andotp) - A CLI program to encrypt/decrypt [andOTP (⭐3.6k)](https://github.com/andOTP/andOTP) files. Can be used as a library as well.
*   [go-arg (⭐1.5k)](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go.
*   [go-commander (⭐30)](https://github.com/yitsushi/go-commander) - Go library to simplify CLI workflow.
*   [go-flags (⭐2.3k)](https://github.com/jessevdk/go-flags) - go command line option parser.
*   [go-getoptions (⭐46)](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired by the flexibility of Perl’s GetOpt::Long.
*   [gocmd (⭐62)](https://github.com/devfacet/gocmd) - Go library for building command line applications.
*   [hiboot cli (⭐180)](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
*   [job (⭐122)](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job.
*   [kingpin (⭐3.3k)](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands (superseded by `kong`; see below).
*   [liner (⭐938)](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces.
*   [mcli (⭐8)](https://github.com/jxskiss/mcli) - A minimal but very powerful cli library for Go.
*   [mitchellh/cli (⭐1.6k)](https://github.com/mitchellh/cli) - Go library for implementing command-line interfaces.
*   [mow.cli (⭐834)](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
*   [ops (⭐1k)](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator.
*   [pflag (⭐2k)](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
*   [sand (⭐19)](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more.
*   [sflags (⭐142)](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin, and other libraries.
*   [strumt (⭐49)](https://github.com/antham/strumt) - Library to create prompt chain.
*   [subcmd (⭐3)](https://github.com/bobg/subcmd) - Another approach to parsing and running subcommands. Works alongside the standard `flag` package.
*   [ts (⭐16)](https://github.com/liujianping/ts) - Timestamp convert & compare tool.
*   [ukautz/clif (⭐118)](https://github.com/ukautz/clif) - Small command line interface framework.
*   [urfave/cli (⭐19k)](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
*   [version (⭐42)](https://github.com/mszostok/version) - Collects and displays CLI version information in multiple formats along with upgrade notice.
*   [wlog (⭐59)](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency.
*   [wmenu (⭐178)](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompt users to make choices.

**[⬆ back to top](#contents)**

## Configuration

*Libraries for configuration parsing.*

*   [aconfig (⭐408)](https://github.com/cristalhq/aconfig) - Simple, useful and opinionated config loader.
*   [cleanenv (⭐774)](https://github.com/ilyakaznacheev/cleanenv) - Minimalistic configuration reader (from files, ENV, and wherever you want).
*   [config (⭐317)](https://github.com/JeremyLoy/config) - Cloud native application configuration. Bind ENV to structs in only two lines.
*   [config (⭐26)](https://github.com/num30/config) - configure you app using file, environment variables, or flags in two lines of code
*   [config (⭐258)](https://github.com/olebedev/config) - JSON or YAML configuration wrapper with environment variables and flags parsing.
*   [configuration (⭐82)](https://github.com/BoRuDar/configuration) - Library for initializing configuration structs from env variables, files, flags and 'default' tag.
*   [configure (⭐57)](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables.
*   [configuro (⭐82)](https://github.com/sherifabdlnaby/configuro) - opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications.
*   [confita (⭐457)](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct.
*   [conflate (⭐26)](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
*   [env (⭐2.9k)](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults).
*   [env (⭐35)](https://github.com/junk1tm/env) - A lightweight package for loading environment variables into structs.
*   [envcfg (⭐99)](https://github.com/tomazk/envcfg) - Un-marshaling environment variables to Go structs.
*   [envconf (⭐11)](https://github.com/ian-kent/envconf) - Configuration from environment.
*   [envconfig (⭐229)](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables.
*   [envh (⭐96)](https://github.com/antham/envh) - Helpers to manage environment variables.
*   [fig (⭐244)](https://github.com/kkyr/fig) - Tiny library for reading configuration from a file and from environment variables (with validation & defaults).
*   [gcfg (⭐164)](https://github.com/go-gcfg/gcfg) - read INI-style configuration files into Go structs; supports user-defined types and subsections.
*   [genv (⭐29)](https://github.com/sakirsensoy/genv) - Read environment variables easily with dotenv support.
*   [go-aws-ssm (⭐51)](https://github.com/PaddleHQ/go-aws-ssm) - Go package that fetches parameters from AWS System Manager - Parameter Store.
*   [go-conf (⭐6)](https://github.com/ThomasObenaus/go-conf) - Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters.
*   [go-ini (⭐8)](https://github.com/subpop/go-ini) - A Go package that marshals and unmarshals INI-files.
*   [go-ssm-config (⭐17)](https://github.com/ianlopshire/go-ssm-config) - Go utility for loading configuration parameters from AWS SSM (Parameter Store).
*   [go-up (⭐38)](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic.
*   [goConfig (⭐1)](https://github.com/crgimenes/goConfig) - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.
*   [godotenv (⭐5.5k)](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
*   [gofigure (⭐65)](https://github.com/ian-kent/gofigure) - Go application configuration made easy.
*   [GoLobby/Config (⭐296)](https://github.com/golobby/config) - GoLobby Config is a lightweight yet powerful configuration manager for the Go programming language.
*   [gone/jconf (⭐43)](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
*   [gonfig (⭐5)](https://github.com/milad-abbasi/gonfig) - Tag-based configuration parser which loads values from different providers into typesafe struct.
*   [gookit/config (⭐409)](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.
*   [harvester (⭐119)](https://github.com/beatlabs/harvester) - Harvester, a easy to use static and dynamic configuration package supporting seeding, env vars and Consul integration.
*   [hjson (⭐282)](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
*   [hocon (⭐52)](https://github.com/gurkankaymak/hocon) - Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files.
*   [ingo (⭐36)](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file.
*   [ini (⭐3.1k)](https://github.com/go-ini/ini) - Go package to read and write INI files.
*   [ini (⭐10)](https://github.com/wlevene/ini) - INI Parser & Write Library, Unmarshal to Struct,Marshal to Json,Write File,watch file.
*   [joshbetz/config (⭐214)](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
*   [kelseyhightower/envconfig (⭐4.3k)](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables.
*   [koanf (⭐1.3k)](https://github.com/knadh/koanf) - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.
*   [konfig (⭐632)](https://github.com/lalamove/konfig) - Composable, observable and performant config handling for Go for the distributed processing era.
*   [kong (⭐1.2k)](https://github.com/alecthomas/kong) - Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (successor to `kingpin`).
*   [mini (⭐32)](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files.
*   [nasermirzaei89/env (⭐9)](https://github.com/nasermirzaei89/env) - Simple useful package for read environment variables.
*   [nfigure (⭐4)](https://github.com/muir/nfigure) - Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML
*   [onion (⭐109)](https://github.com/goraz/onion) - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.
*   [piper (⭐7)](https://github.com/Yiling-J/piper) - Viper wrapper with config inheritance and key generation.
*   [store (⭐263)](https://github.com/tucnak/store) - Lightweight configuration manager for Go.
*   [swap (⭐7)](https://github.com/oblq/swap) - Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env).
*   [typenv (⭐9)](https://github.com/diegomarangoni/typenv) - Minimalistic, zero dependency, typed environment variables library.
*   [uConfig (⭐53)](https://github.com/omeid/uconfig) - Lightweight, zero-dependency, and extendable configuration management.
*   [viper (⭐21k)](https://github.com/spf13/viper) - Go configuration with fangs.
*   [xdg (⭐291)](https://github.com/adrg/xdg) - Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories).
*   [xdg (⭐72)](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

**[⬆ back to top](#contents)**

## Continuous Integration

*Tools for help with continuous integration.*

*   [CDS (⭐4k)](https://github.com/ovh/cds) - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.
*   [drone (⭐26k)](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go.
*   [duci (⭐76)](https://github.com/duck8823/duci) - A simple ci server no needs domain specific languages.
*   [go-fuzz-action (⭐6)](https://github.com/jidicula/go-fuzz-action) - Use Go 1.18's built-in fuzz testing in GitHub Actions.
*   [gomason (⭐54)](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace.
*   [gotestfmt (⭐334)](https://github.com/GoTestTools/gotestfmt) - go test output for humans.
*   [goveralls (⭐743)](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system.
*   [overalls (⭐112)](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls.
*   [roveralls (⭐19)](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool.
*   [woodpecker (⭐1.7k)](https://github.com/woodpecker-ci/woodpecker) - Woodpecker is a community fork of the Drone CI system.

**[⬆ back to top](#contents)**

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

*   [gcss (⭐468)](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor.
*   [go-libsass (⭐190)](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project.

**[⬆ back to top](#contents)**

## Data Structures and Algorithms

### Bit-packing and Compression

*   [bingo (⭐16)](https://github.com/iancmcc/bingo) - Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes.
*   [binpacker (⭐196)](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream.
*   [bit (⭐136)](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions.
*   [crunch (⭐61)](https://github.com/superwhiskers/crunch) - Go package implementing buffers for handling various datatypes easily.
*   [go-ef (⭐25)](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding.
*   [roaring (⭐1.8k)](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets.

### Bit Sets

*   [bitmap (⭐183)](https://github.com/kelindar/bitmap) - Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go.
*   [bitset (⭐995)](https://github.com/bits-and-blooms/bitset) - Go package implementing bitsets.

### Bloom and Cuckoo Filters

*   [bloom (⭐1.7k)](https://github.com/bits-and-blooms/bloom) - Go package implementing Bloom filters.
*   [bloom (⭐147)](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go.
*   [bloom (⭐74)](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation.
*   [bloomfilter (⭐10)](https://github.com/OldPanda/bloomfilter) - Yet another Bloomfilter implementation in Go, compatible with Java's Guava library.
*   [boomfilters (⭐1.5k)](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams.
*   [cuckoo-filter (⭐233)](https://github.com/linvon/cuckoo-filter) - Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper is available.
*   [cuckoofilter (⭐940)](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
*   [ring (⭐128)](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter.

### Data Structure and Algorithm Collections

*   [algorithms (⭐682)](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study.
*   [go-datastructures (⭐6.7k)](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures.
*   [gods (⭐13k)](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
*   [gostl (⭐742)](https://github.com/liyue201/gostl) - Data structure and algorithm library for go, designed to provide functions similar to C++ STL.

### Iterators

*   [goterator (⭐11)](https://github.com/yaa110/goterator) - Iterator implementation to provide map and reduce functionalities.
*   [iter (⭐171)](https://github.com/disksing/iter) - Go implementation of C++ STL iterators and algorithms.

### Maps

See also [Database](#database) for more complex key-value stores, and [Trees](#trees) for
additional ordered map implementations.

*   [cmap (⭐38)](https://github.com/lrita/cmap) - a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards.
*   [dict (⭐34)](https://github.com/srfrog/dict) - Python-like dictionaries (dict) for Go.
*   [goradd/maps (⭐13)](https://github.com/goradd/maps) - Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc.

### Miscellaneous Data Structures and Algorithms

*   [concurrent-writer (⭐46)](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`.
*   [conjungo (⭐108)](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library.
*   [count-min-log (⭐58)](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
*   [fsm (⭐32)](https://github.com/cocoonspace/fsm) - Finite-State Machine package.
*   [genfuncs (⭐34)](https://github.com/nwillc/genfuncs) - Go 1.18+ generics package inspired by Kotlin's Sequence and Map.
*   [go-generics (⭐7)](https://github.com/bobg/go-generics) - Generic slice, map, set, iterator, and goroutine utilities.
*   [go-geoindex (⭐341)](https://github.com/hailocab/go-geoindex) - In-memory geo index.
*   [go-rampart (⭐85)](https://github.com/francesconi/go-rampart) - Determine how intervals relate to each other.
*   [go-rquad (⭐123)](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding.
*   [go-tuple (⭐39)](https://github.com/barweiss/go-tuple) - Generic tuple implementation for Go 1.18+.
*   [go18ds (⭐29)](https://github.com/daichi-m/go18ds) - Go Data Structures using Go 1.18 generics.
*   [gofal (⭐17)](https://github.com/xxjwxc/gofal) - fractional api for Go.
*   [gota (⭐2.4k)](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go.
*   [hide (⭐51)](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients.
*   [hilbert (⭐255)](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.
*   [hyperloglog (⭐805)](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
*   [quadtree (⭐18)](https://github.com/s0rg/quadtree) - Generic, zero-alloc, 100%-test covered quadtree.
*   [slices (⭐9)](https://github.com/srfrog/slices) - Functions that operate on slices; like `package strings` but adapted to work with slices.
*   [slices (⭐13)](https://github.com/twharmon/slices) - Pure, generic functions for slices.

### Nullable Types

*   [nan (⭐58)](https://github.com/kak-tus/nan) - Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers.
*   [null (⭐28)](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON.
*   [typ (⭐33)](https://github.com/gurukami/typ) - Null Types, Safe primitive type conversion and fetching value from complex structures.

### Queues

*   [deque (⭐83)](https://github.com/edwingeng/deque) - A highly optimized double-ended queue.
*   [deque (⭐397)](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue).
*   [goconcurrentqueue (⭐219)](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue.
*   [memlog (⭐66)](https://github.com/embano1/memlog) - An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka.

### Sets

*   [dsu (⭐8)](https://github.com/ihebu/dsu) - Disjoint Set data structure implementation in Go.
*   [golang-set (⭐2.8k)](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
*   [goset (⭐50)](https://github.com/zoumo/goset) - A useful Set collection implementation for Go.
*   [set (⭐22)](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap.

### Text Analysis

*   [bleve (⭐8.7k)](https://github.com/blevesearch/bleve) - Modern text indexing library for go.
*   [go-adaptive-radix-tree (⭐250)](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree.
*   [go-edlib (⭐362)](https://github.com/hbollon/go-edlib) - Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode.
*   [levenshtein (⭐70)](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
*   [levenshtein (⭐246)](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go.
*   [mspm (⭐18)](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval.
*   [parsefields (⭐7)](https://github.com/MonaxGT/parsefields) - Tools for parse JSON-like logs for collecting unique fields and events.
*   [ptrie (⭐31)](https://github.com/viant/ptrie) - An implementation of prefix tree.
*   [trie (⭐613)](https://github.com/derekparker/trie) - Trie implementation in Go.

### Trees

*   [hashsplit (⭐12)](http://github.com/bobg/hashsplit) - Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position.
*   [merkle (⭐8)](https://github.com/bobg/merkle) - Space-efficient computation of Merkle root hashes and inclusion proofs.
*   [skiplist (⭐236)](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation.
*   [skiplist (⭐79)](https://github.com/gansidui/skiplist) - Skiplist implementation in Go.
*   [treap (⭐20)](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps.
*   [treemap (⭐28)](https://github.com/igrmk/treemap) - Generic key-sorted map using a red-black tree under the hood.

### Pipes

*   [ordered-concurrently (⭐17)](https://github.com/tejzpr/ordered-concurrently) - Go module that processes work concurrently and returns output in a channel in the order of input.
*   [parapipe (⭐21)](https://github.com/nazar256/parapipe) - FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results.
*   [pipeline (⭐45)](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out.

**[⬆ back to top](#contents)**

## Database

### Caches

*Data stores with expiring records, in-memory distributed data stores, or in-memory subsets of file-based databases.*

*   [2q (⭐14)](https://github.com/floatdrop/2q) - 2Q in-memory cache implementation.
*   [bcache (⭐100)](https://github.com/iwanbk/bcache) - Eventually consistent distributed in-memory  cache Go library.
*   [BigCache (⭐6.1k)](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data.
*   [cache (⭐120)](https://github.com/akyoto/cache) - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage.
*   [cache2go (⭐1.9k)](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts.
*   [cachego (⭐193)](https://github.com/faabiosr/cachego) - Golang Cache component for multiple drivers.
*   [clusteredBigCache (⭐42)](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration.
*   [couchcache (⭐58)](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server.
*   [fastcache (⭐1.6k)](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
*   [GCache (⭐2.2k)](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC.
*   [gdcache (⭐10)](https://github.com/ulovecode/gdcache) - A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache.
*   [go-cache (⭐82)](https://github.com/viney-shih/go-cache) - A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern.
*   [go-mcache (⭐85)](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches.
*   [gocache (⭐1.5k)](https://github.com/eko/gocache) - A complete Go cache library with multiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more.
*   [groupcache (⭐12k)](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
*   [remember-go (⭐120)](https://github.com/rocketlaunchr/remember-go) - A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory).
*   [timedmap (⭐49)](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs.
*   [ttlcache (⭐521)](https://github.com/jellydator/ttlcache) - An in-memory cache with item expiration and generics.
*   [ttlcache (⭐7)](https://github.com/cheshir/ttlcache) - In-memory key value storage with TTL for each record.

### Databases Implemented in Go

*   [badger (⭐11k)](https://github.com/dgraph-io/badger) - Fast key-value store in Go.
*   [bbolt (⭐6k)](https://github.com/etcd-io/bbolt) - An embedded key/value database for Go.
*   [Bitcask](https://git.mills.io/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).
*   [buntdb (⭐3.9k)](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
*   [clover (⭐288)](https://github.com/ostafen/clover) - A lightweight document-oriented NoSQL database written in pure Golang.
*   [cockroach (⭐26k)](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore.
*   [Coffer (⭐31)](https://github.com/claygod/coffer) - Simple ACID key-value database that supports transactions.
*   [column (⭐1k)](https://github.com/kelindar/column) - High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions.
*   [CovenantSQL (⭐1.4k)](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain.
*   [Databunker (⭐1k)](https://github.com/paranoidguy/databunker) - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA.
*   [dgraph (⭐19k)](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database.
*   [diskv (⭐1.2k)](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store.
*   [dolt (⭐13k)](https://github.com/dolthub/dolt) - Dolt – It's Git for Data.
*   [dtf (⭐228)](https://github.com/dtm-labs/dtf) - A distributed transaction manager. Support XA, TCC, SAGA, Reliable Messages.
*   [eliasdb (⭐950)](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
*   [godis (⭐2.3k)](https://github.com/hdt3213/godis) - A Golang implemented high-performance Redis server and cluster.
*   [goleveldb (⭐5.4k)](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB (⭐31k)](https://github.com/google/leveldb) key/value database in Go.
*   [hare (⭐69)](https://github.com/jameycribbs/hare) - A simple database management system that stores each table as a text file of line-delimited JSON.
*   [immudb (⭐8k)](https://github.com/codenotary/immudb) - immudb is a lightweight, high-speed immutable database for systems and applications written in Go.
*   [influxdb (⭐24k)](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics.
*   [ledisdb (⭐3.9k)](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
*   [levigo (⭐407)](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB.
*   [lotusdb (⭐1k)](https://github.com/flower-corp/lotusdb) - Fast k/v database compatible with lsm and b+tree.
*   [Milvus (⭐14k)](https://github.com/milvus-io/milvus) - Milvus is a vector database for embedding management, analytics and search.
*   [moss (⭐893)](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go.
*   [nutsdb (⭐2.6k)](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set.
*   [objectbox-go (⭐800)](https://github.com/objectbox/objectbox-go) - High-performance embedded Object Database (NoSQL) with Go API.
*   [piladb (⭐199)](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures.
*   [pogreb (⭐961)](https://github.com/akrylysov/pogreb) - Embedded key-value store for read-heavy workloads.
*   [prometheus (⭐45k)](https://github.com/prometheus/prometheus) - Monitoring system and time series database.
*   [pudge (⭐332)](https://github.com/recoilme/pudge) - Fast and simple key/value store written using Go's standard library.
*   [rosedb (⭐3.4k)](https://github.com/roseduan/rosedb) - An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset.
*   [rqlite (⭐12k)](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite.
*   [tempdb (⭐17)](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items.
*   [tidb (⭐33k)](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1.
*   [tiedot (⭐2.7k)](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang.
*   [unitdb (⭐98)](https://github.com/unit-io/unitdb) - Fast timeseries database for IoT, realtime messaging  applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application.
*   [Vasto (⭐240)](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.
*   [VictoriaMetrics (⭐7.4k)](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.

### Database Schema Migration

*   [atlas (⭐2k)](https://github.com/ariga/atlas) - A Database Toolkit. A CLI designed to help companies better work with their data.
*   [avro (⭐42)](https://github.com/khezen/avro) - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.
*   [bytebase (⭐4.2k)](https://github.com/bytebase/bytebase) - Safe database schema change and version control for DevOps teams.
*   [darwin (⭐134)](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go.
*   [go-fixtures (⭐29)](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library.
*   [go-pg-migrate (⭐9)](https://github.com/lawzava/go-pg-migrate) - CLI-friendly package for go-pg migrations management.
*   [go-pg-migrations (⭐82)](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg.
*   [goavro (⭐847)](https://github.com/linkedin/goavro) - A Go package that encodes and decodes Avro data.
*   [godfish (⭐3)](https://github.com/rafaelespinoza/godfish) - Database migration manager, works with native query language. Support for cassandra, mysql, postgres, sqlite3.
*   [goose (⭐3.1k)](https://github.com/pressly/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
*   [gorm-seeder (⭐5)](https://github.com/Kachit/gorm-seeder) - Simple database seeder for Gorm ORM.
*   [gormigrate (⭐837)](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM.
*   [libschema (⭐11)](https://github.com/muir/libschema) - Define your migrations separately in each library.  Migrations for open source libraries.  MySQL & PostgreSQL.
*   [migrate (⭐10k)](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library.
*   [migrator (⭐134)](https://github.com/lopezator/migrator) - Dead simple Go database migration library.
*   [migrator (⭐21)](https://github.com/larapulse/migrator) - MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code.
*   [schema (⭐26)](https://github.com/adlio/schema) - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.
*   [skeema (⭐1.1k)](https://github.com/skeema/skeema) - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.
*   [soda (⭐1.3k)](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
*   [sql-migrate (⭐2.6k)](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata.
*   [sqlize (⭐45)](https://github.com/sunary/sqlize) - Database migration generator. Allows generate sql migration from model and existing sql by differ them.

### Database Tools

*   [chproxy (⭐1k)](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database.
*   [clickhouse-bulk (⭐394)](https://github.com/nikepan/clickhouse-bulk) - Collects small inserts and sends big requests to ClickHouse servers.
*   [datagen (⭐50)](https://github.com/codingconcepts/datagen) - A fast data generator that's multi-table aware and supports multi-row DML.
*   [dbbench (⭐76)](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts.
*   [dynago (⭐5)](https://github.com/twharmon/dynago) - Simplify working with AWS DynamoDB.
*   [go-mysql (⭐3.9k)](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication.
*   [go-mysql-elasticsearch (⭐3.9k)](https://github.com/siddontang/go-mysql-elasticsearch) - Sync your MySQL data into Elasticsearch automatically.
*   [hasql](https://golang.yandex/hasql) - Library for accessing multi-host SQL database installations.
*   [kingshard (⭐6.1k)](https://github.com/flike/kingshard) - kingshard is a high performance proxy for MySQL powered by Golang.
*   [octillery (⭐175)](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ).
*   [orchestrator (⭐4.7k)](https://github.com/github/orchestrator) - MySQL replication topology manager & visualizer.
*   [pg\_timetable (⭐806)](https://github.com/cybertec-postgresql/pg_timetable) - Advanced scheduling for PostgreSQL.
*   [pgweb (⭐7.5k)](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser.
*   [prep (⭐32)](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code.
*   [pREST (⭐3.4k)](https://github.com/prest/prest) - Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new.
*   [rdb (⭐197)](https://github.com/HDT3213/rdb) - Redis RDB file parser for secondary development and memory analysis.
*   [rwdb (⭐16)](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup.
*   [vitess (⭐15k)](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

### SQL Query Builders

*Libraries for building and using SQL.*

*   [bqb (⭐58)](https://github.com/nullism/bqb) - Lightweight and easy to learn query builder.
*   [buildsqlx (⭐81)](https://github.com/arthurkushman/buildsqlx) - Go database query builder library for PostgreSQL.
*   [builq (⭐29)](https://github.com/cristalhq/builq) - Easily build SQL queries in Go.
*   [dbq (⭐354)](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go.
*   [Dotsql (⭐651)](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease.
*   [gendry (⭐1.4k)](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder.
*   [godbal (⭐54)](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
*   [goqu (⭐1.7k)](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library.
*   [gosql (⭐26)](https://github.com/twharmon/gosql) - SQL Query builder with better null values support.
*   [igor (⭐88)](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
*   [jet (⭐873)](https://github.com/go-jet/jet) - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.
*   [ormlite (⭐4)](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases.
*   [ozzo-dbx (⭐583)](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
*   [qry (⭐25)](https://github.com/HnH/qry) - Tool that generates constants from files with raw SQL queries.
*   [sg (⭐2)](https://github.com/go-the-way/sg) - A SQL Gen for generating standard SQLs(supports: CRUD) written in Go.
*   [sq (⭐177)](https://github.com/bokwoon95/go-structured-query) - Type-safe SQL builder and struct mapper for Go.
*   [sqlc (⭐6.7k)](https://github.com/kyleconroy/sqlc) - Generate type-safe code from SQL.
*   [sqlf (⭐90)](https://github.com/leporo/sqlf) - Fast SQL query builder.
*   [sqlingo (⭐268)](https://github.com/lqs/sqlingo) - A lightweight DSL to build SQL in Go.
*   [sqrl (⭐246)](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance.
*   [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
*   [Squirrel (⭐5.3k)](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries.
*   [xo (⭐3.3k)](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

**[⬆ back to top](#contents)**

## Database Drivers

### Interfaces to Multiple Backends

*   [cayley (⭐14k)](https://github.com/google/cayley) - Graph database with support for multiple backends.
*   [dsc (⭐26)](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files.
*   [gokv (⭐488)](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).

### Relational Database Drivers

*   [avatica (⭐103)](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql.
*   [bgc (⭐18)](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go.
*   [firebirdsql (⭐181)](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go.
*   [go-adodb (⭐131)](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
*   [go-mssqldb (⭐1.7k)](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go.
*   [go-oci8 (⭐596)](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql.
*   [go-sql-driver/mysql (⭐13k)](https://github.com/go-sql-driver/mysql) - MySQL driver for Go.
*   [go-sqlite3 (⭐6.2k)](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql.
*   [godror (⭐397)](https://github.com/godror/godror) - Oracle driver for Go, using the ODPI-C driver.
*   [gofreetds (⭐106)](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org).
*   [Kivik (⭐244)](https://github.com/go-kivik/kivik) - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.
*   [KSQL (⭐190)](https://github.com/VinGarcia/ksql) - A Simple and Powerful Golang SQL Library
*   [pgx (⭐6.2k)](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql.
*   [pig (⭐10)](https://github.com/alexeyco/pig) - Simple [pgx (⭐6.2k)](https://github.com/jackc/pgx) wrapper to execute and [scan (⭐769)](https://github.com/georgysavva/scany) query results easily.
*   [pq (⭐7.7k)](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql.
*   [Sqinn-Go (⭐128)](https://github.com/cvilsmeier/sqinn-go) - SQLite with pure Go.
*   [sqlhooks (⭐594)](https://github.com/qustavo/sqlhooks) - Attach hooks to any database/sql driver.
*   [ydb-go-sdk (⭐67)](https://github.com/ydb-platform/ydb-go-sdk) - native and database/sql driver YDB (Yandex Database)

### NoSQL Database Drivers

*   [aerospike-client-go (⭐399)](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language.
*   [arangolite (⭐73)](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB.
*   [asc (⭐9)](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go.
*   [forestdb (⭐33)](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB.
*   [go-couchbase (⭐316)](https://github.com/couchbase/go-couchbase) - Couchbase client in Go.
*   [go-pilosa (⭐56)](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa.
*   [go-rejson (⭐291)](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.
*   [gocb (⭐339)](https://github.com/couchbase/gocb) - Official Couchbase Go SDK.
*   [gocosmos (⭐12)](https://github.com/btnguyen2k/gocosmos) - REST client and standard `database/sql` driver for Azure Cosmos DB.
*   [gocql](https://gocql.github.io) - Go language driver for Apache Cassandra.
*   [godis (⭐106)](https://github.com/piaohao/godis) - redis client implement by golang, inspired by jedis.
*   [godscache (⭐11)](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
*   [gomemcache (⭐1.5k)](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language.
*   [gorethink (⭐1.6k)](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB.
*   [goriak (⭐28)](https://github.com/zegl/goriak) - Go language driver for Riak KV.
*   [mgm (⭐581)](https://github.com/kamva/mgm) - MongoDB model-based ODM for Go (based on official MongoDB driver).
*   [mgo (⭐2k)](https://github.com/globalsign/mgo) - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
*   [mongo-go-driver (⭐7k)](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language.
*   [neo4j (⭐28)](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang.
*   [Neo4j-GO (⭐77)](https://github.com/davemeehan/Neo4j-GO) - Neo4j REST Client in golang.
*   [neoism (⭐388)](https://github.com/jmcvetta/neoism) - Neo4j client for Golang.
*   [qmgo (⭐1k)](https://github.com/qiniu/qmgo) - The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo.
*   [redeo (⭐420)](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services.
*   [redigo (⭐9.3k)](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database.
*   [redis (⭐16k)](https://github.com/go-redis/redis) - Redis client for Golang.
*   [rueidis (⭐764)](http://github.com/rueian/rueidis) - Fast Redis RESP3 client with auto pipelining and server-assisted client side caching.
*   [xredis (⭐19)](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client.

### Search and Analytic Databases

*   [elastic (⭐7k)](https://github.com/olivere/elastic) - Elasticsearch client for Go.
*   [elasticsql (⭐978)](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go.
*   [elastigo (⭐949)](https://github.com/mattbaird/elastigo) - Elasticsearch client library.
*   [go-elasticsearch (⭐4.5k)](https://github.com/elastic/go-elasticsearch) - Official Elasticsearch client for Go.
*   [goes (⭐29)](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch.
*   [skizze (⭐88)](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage.

**[⬆ back to top](#contents)**

## Date and Time

*Libraries for working with dates and times.*

*   [carbon (⭐2.5k)](https://github.com/golang-module/carbon) - A simple, semantic and developer-friendly golang package for datetime.
*   [carbon (⭐736)](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
*   [cronrange (⭐18)](https://github.com/1set/cronrange) - Parses Cron-style time range expressions, checks if the given time is within any ranges.
*   [date (⭐98)](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
*   [dateparse (⭐1.8k)](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance.
*   [durafmt (⭐450)](https://github.com/hako/durafmt) - Time duration formatting library for Go.
*   [feiertage (⭐43)](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
*   [go-anytime (⭐3)](https://github.com/ijt/go-anytime) - Parse dates/times like "next dec 22nd at 3pm" and ranges like "from today until next thursday" without knowing the format in advance.
*   [go-persian-calendar (⭐129)](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
*   [go-str2duration (⭐55)](https://github.com/xhit/go-str2duration) - Convert string to duration. Support time.Duration returned string and more.
*   [go-sunrise (⭐60)](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location.
*   [go-week (⭐8)](https://github.com/stoewer/go-week) - An efficient package to work with ISO8601 week dates.
*   [gostradamus (⭐171)](https://github.com/bykof/gostradamus) - A Go package for working with dates.
*   [iso8601 (⭐112)](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex.
*   [kair (⭐24)](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library.
*   [now (⭐3.9k)](https://github.com/jinzhu/now) - Now is a time toolkit for golang.
*   [NullTime (⭐13)](https://github.com/kirillDanshin/nulltime) - Nullable `time.Time`.
*   [strftime (⭐11)](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter.
*   [timespan (⭐82)](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration.
*   [timeutil (⭐191)](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
*   [tuesday (⭐12)](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function.

**[⬆ back to top](#contents)**

## Distributed Systems

*Packages that help with building Distributed Systems.*

*   [arpc (⭐629)](https://github.com/lesismal/arpc) - More effective network communication, support two-way-calling, notify, broadcast.
*   [celeriac (⭐73)](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
*   [consistent (⭐527)](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads.
*   [consistenthash (⭐14)](https://github.com/mbrostami/consistenthash) - Consistent hashing with configurable replicas.
*   [dht (⭐248)](https://github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation.
*   [digota (⭐467)](https://github.com/digota/digota) - grpc ecommerce microservice.
*   [dot (⭐73)](https://github.com/dotchain/dot/) - distributed sync using operational transformation/OT.
*   [doublejump (⭐80)](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash.
*   [dragonboat (⭐4.4k)](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go.
*   [drmaa (⭐42)](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard.
*   [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
*   [dynatomic (⭐15)](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter.
*   [emitter-io (⭐3.4k)](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
*   [failured (⭐7)](https://github.com/andy2046/failured) - adaptive accrual failure detector for distributed systems.
*   [flowgraph (⭐53)](https://github.com/vectaport/flowgraph) - flow-based programming package.
*   [gleam (⭐3.1k)](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
*   [glow (⭐3.1k)](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
*   [gmsec (⭐23)](https://github.com/gmsec/micro) - A Go distributed systems development framework.
*   [go-doudou (⭐868)](https://github.com/unionj-cloud/go-doudou) - A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity.
*   [go-health (⭐642)](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service.
*   [go-jump (⭐354)](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function.
*   [go-kit (⭐24k)](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
*   [go-micro (⭐20k)](https://github.com/micro/go-micro) - A distributed systems development framework.
*   [go-mysql-lock (⭐49)](https://github.com/sanketplus/go-mysql-lock) - MySQL based distributed lock.
*   [go-pdu (⭐43)](https://github.com/pdupub/go-pdu) - A decentralized identity-based social network.
*   [go-sundheit (⭐499)](https://github.com/AppsFlyer/go-sundheit) - A library built to provide support for defining async service health checks for golang services.
*   [go-zero (⭐21k)](https://github.com/tal-tech/go-zero) - A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
*   [gorpc (⭐662)](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load.
*   [grpc-go (⭐17k)](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC.
*   [hprose (⭐1.2k)](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now.
*   [jsonrpc (⭐170)](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0.
*   [jsonrpc (⭐252)](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation.
*   [Kitex (⭐5.3k)](https://github.com/cloudwego/kitex) - A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices. If the performance and extensibility are the main concerns when you develop microservices, Kitex can be a good choice.
*   [Kratos (⭐19k)](https://github.com/go-kratos/kratos) - A modular-designed and easy-to-use microservices framework in Go.
*   [liftbridge (⭐2.4k)](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams for NATS.
*   [lura (⭐5.3k)](https://github.com/luraproject/lura) - Ultra performant API Gateway framework with middlewares.
*   [micro (⭐11k)](https://github.com/micro/micro) - A distributed systems runtime for the cloud and beyond.
*   [NATS (⭐12k)](https://github.com/nats-io/gnatsd) - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
*   [outboxer (⭐94)](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern.
*   [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
*   [pjrpc](https://gitlab.com/pjrpc/pjrpc) - Golang JSON-RPC Server-Client with Protobuf spec.
*   [raft (⭐6.5k)](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp.
*   [raft (⭐42k)](https://github.com/coreos/etcd/tree/master/raft) - Go implementation of the Raft consensus protocol, by CoreOS.
*   [rain (⭐781)](https://github.com/cenkalti/rain) - BitTorrent client and library.
*   [redis-lock (⭐845)](https://github.com/bsm/redislock) - Simplified distributed locking implementation using Redis.
*   [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
*   [ringpop-go (⭐753)](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications.
*   [rpcx (⭐7.3k)](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo.
*   [Semaphore (⭐77)](https://github.com/jexia/semaphore) - A straightforward (micro) service orchestrator.
*   [sleuth (⭐359)](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ (⭐8.1k)](https://github.com/zeromq/libzmq)).
*   [torrent (⭐4.6k)](https://github.com/anacrolix/torrent) - BitTorrent client package.

**[⬆ back to top](#contents)**

## Dynamic DNS

*Tools for updating dynamic DNS records.*

*   [DDNS (⭐223)](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend.
*   [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.
*   [GoDNS (⭐1.2k)](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.

**[⬆ back to top](#contents)**

## Email

*Libraries and tools that implement email creation and sending.*

*   [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
*   [douceur (⭐222)](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails.
*   [email (⭐2.2k)](https://github.com/jordan-wright/email) - A robust and flexible email library for Go.
*   [email-verifier (⭐542)](https://github.com/AfterShip/email-verifier) - A Go library for email verification without sending any emails.
*   [go-dkim (⭐83)](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email.
*   [go-email-normalizer (⭐54)](https://github.com/dimuska139/go-email-normalizer) - Golang library for providing a canonical representation of email address.
*   [go-email-validator (⭐40)](https://github.com/go-email-validator/go-email-validator) - Modular email validator for syntax, disposable, smtp, etc... checking.
*   [go-imap (⭐1.7k)](https://github.com/emersion/go-imap) - IMAP library for clients and servers.
*   [go-mail (⭐96)](https://github.com/wneessen/go-mail) - A simple Go library for sending mails in Go.
*   [go-message (⭐279)](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages.
*   [go-premailer (⭐95)](https://github.com/vanng822/go-premailer) - Inline styling for HTML mail in Go.
*   [go-simple-mail (⭐398)](https://github.com/xhit/go-simple-mail) - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.
*   [Hectane (⭐222)](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API.
*   [hermes (⭐2.6k)](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails.
*   [mailchain (⭐133)](https://github.com/mailchain/mailchain) - Send encrypted emails to blockchain addresses written in Go.
*   [mailgun-go (⭐622)](https://github.com/mailgun/mailgun-go) - Go library for sending mail with the Mailgun API.
*   [MailHog (⭐11k)](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface.
*   [Mailpit (⭐72)](https://github.com/axllent/mailpit) - Email and SMTP testing tool for developers.
*   [mailx (⭐6)](https://github.com/valord577/mailx) - Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`.
*   [SendGrid (⭐864)](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email.
*   [smtp (⭐74)](https://github.com/mailhog/smtp) - SMTP server protocol state machine.
*   [smtpmock (⭐56)](https://github.com/mocktools/go-smtp-mock) - Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment.
*   [truemail-go (⭐25)](https://github.com/truemail-rb/truemail-go) - Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more.

**[⬆ back to top](#contents)**

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

*   [anko (⭐1.3k)](https://github.com/mattn/anko) - Scriptable interpreter written in Go.
*   [binder (⭐64)](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua (⭐5.1k)](https://github.com/yuin/gopher-lua).
*   [cel-go (⭐1.4k)](https://github.com/google/cel-go) - Fast, portable, non-Turing complete expression evaluation with gradual typing.
*   [ecal (⭐29)](https://github.com/krotik/ecal) - A simple embeddable scripting language which supports concurrent event processing.
*   [expr (⭐3.2k)](https://github.com/antonmedv/expr) - Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing.
*   [gentee (⭐100)](https://github.com/gentee/gentee) - Embeddable scripting programming language.
*   [gisp (⭐497)](https://github.com/jcla1/gisp) - Simple LISP in Go.
*   [go-duktape (⭐779)](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go.
*   [go-lua (⭐2.6k)](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go.
*   [go-php (⭐875)](https://github.com/deuill/go-php) - PHP bindings for Go.
*   [go-python (⭐1.4k)](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API.
*   [goja (⭐3.3k)](https://github.com/dop251/goja) - ECMAScript 5.1(+) implementation in Go.
*   [golua (⭐599)](https://github.com/aarzilli/golua) - Go bindings for Lua C API.
*   [gopher-lua (⭐5.1k)](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go.
*   [gval (⭐548)](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go.
*   [metacall (⭐1.1k)](https://github.com/metacall/core) - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more.
*   [ngaro (⭐23)](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro.
*   [prolog (⭐438)](https://github.com/ichiban/prolog) - Embeddable Prolog.
*   [purl (⭐35)](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go.
*   [starlark-go (⭐1.8k)](https://github.com/google/starlark-go) - Go implementation of Starlark: Python-like language with deterministic evaluation and hermetic execution.
*   [tengo (⭐2.9k)](https://github.com/d5/tengo) - Bytecode compiled script language for Go.

**[⬆ back to top](#contents)**

## Error Handling

*Libraries for handling errors.*

*   [emperror (⭐272)](https://github.com/emperror/emperror) - Error handling tools and best practices for Go libraries and applications.
*   [eris (⭐1.1k)](https://github.com/rotisserie/eris) - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors.
*   [errlog (⭐413)](https://github.com/snwfdhmp/errlog) - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.
*   [errors (⭐165)](https://github.com/emperror/errors) - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives.
*   [errors (⭐7.9k)](https://github.com/pkg/errors) - Package that provides simple error handling primitives.
*   [errors (⭐4)](https://github.com/neuronlabs/errors) - Simple golang error handling with classification primitives.
*   [errors (⭐7)](https://github.com/PumpkinSeed/errors) - The most simple error wrapper with awesome performance and minimal memory overhead.
*   [errors (⭐45)](https://github.com/bnkamalesh/errors) - Drop-in replacement for builtin Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions.
*   [errors (⭐1.5k)](https://github.com/cockroachdb/errors) - Go error library with error portability over the network.
*   [errorx (⭐903)](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more.
*   [exception (⭐20)](https://github.com/rbrahul/exception) - A simple utility package for exception handling with try-catch in Golang.
*   [Falcon (⭐8)](https://github.com/SonicRoshan/falcon) - A Simple Yet Highly Powerful Package For Error Handling.
*   [go-multierror (⭐1.7k)](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error.
*   [tracerr (⭐745)](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments.

**[⬆ back to top](#contents)**

## File Handling

*Libraries for handling files and file systems.*

*   [afero (⭐4.9k)](https://github.com/spf13/afero) - FileSystem Abstraction System for Go.
*   [afs (⭐211)](https://github.com/viant/afs) - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.
*   [baraka (⭐46)](https://github.com/xis/baraka) - A library to process http file uploads easily.
*   [bigfile (⭐233)](https://github.com/bigfile/bigfile) - A file transfer system, support to manage files with http api, rpc call and ftp client.
*   [checksum (⭐74)](https://github.com/codingsince1985/checksum) - Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files.
*   [copy (⭐481)](https://github.com/otiai10/copy) - Copy directory recursively.
*   [flop (⭐32)](https://github.com/homedepot/flop) - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
*   [gdu (⭐2.1k)](https://github.com/dundee/gdu) - Disk usage analyzer with console interface.
*   [go-csv-tag (⭐100)](https://github.com/artonge/go-csv-tag) - Load csv file using tag.
*   [go-decent-copy (⭐17)](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans.
*   [go-exiftool (⭐139)](https://github.com/barasher/go-exiftool) - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).
*   [go-gtfs (⭐33)](https://github.com/artonge/go-gtfs) - Load gtfs files in go.
*   [gofs (⭐105)](https://github.com/no-src/gofs) - A file synchronization tool out of the box.
*   [gut/yos (⭐25)](https://github.com/1set/gut) - Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links.
*   [higgs (⭐15)](https://github.com/dastoori/higgs) - A tiny cross-platform Go library to hide/unhide files and directories.
*   [notify (⭐768)](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal.
*   [opc (⭐74)](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go.
*   [parquet (⭐58)](https://github.com/parsyl/parquet) - Read and write [parquet](https://parquet.apache.org) files.
*   [pathtype (⭐12)](https://github.com/jonchun/pathtype) - Treat paths as their own type instead of using strings.
*   [pdfcpu (⭐3.5k)](https://github.com/pdfcpu/pdfcpu) - PDF processor.
*   [skywalker (⭐86)](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease.
*   [stl](https://gitlab.com/russoj88/stl) - Modules to read and write STL (stereolithography) files.  Concurrent algorithm for reading.
*   [tarfs (⭐51)](https://github.com/posener/tarfs) - Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.
*   [todotxt (⭐16)](https://github.com/1set/todotxt) - Go library for Gina Trapani's [*todo.txt*](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [*todo.txt* format](https://github.com/todotxt/todo.txt).
*   [vfs (⭐203)](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.

**[⬆ back to top](#contents)**

## Financial

*Packages for accounting and finance.*

*   [accounting (⭐778)](https://github.com/leekchan/accounting) - money and currency formatting for golang.
*   [ach (⭐342)](https://github.com/moov-io/ach) - A reader, writer, and validator for Automated Clearing House (ACH) files.
*   [bbgo (⭐728)](https://github.com/c9s/bbgo) - A crypto trading bot framework written in Go. Including common crypto exchange API, standard indicators, back-testing and many built-in strategies.
*   [currency (⭐338)](https://github.com/bojanz/currency) - Handles currency amounts, provides currency information and formatting.
*   [currency (⭐52)](https://github.com/bnkamalesh/currency) - High performant & accurate currency computation package.
*   [decimal (⭐4.5k)](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers.
*   [fastme](https://github.com/newity/fastme) - Fast extensible matching engine Go implementation.
*   [fpdecimal (⭐14)](https://github.com/nikolaydubina/fpdecimal) - Fast and precise serialization and arithmetic for small fixed-point decimals
*   [fpmoney (⭐10)](https://github.com/nikolaydubina/fpmoney) - Fast and simple ISO4217 fixed-point decimal money.
*   [go-finance (⭐537)](https://github.com/FlashBoys/go-finance) - Comprehensive financial markets data in Go.
*   [go-finance (⭐143)](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
*   [go-finance (⭐10)](https://github.com/pieterclaerhout/go-finance) - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers.
*   [go-finnhub (⭐77)](https://github.com/m1/go-finnhub) - Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges.
*   [go-money (⭐1.2k)](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern.
*   [ofxgo (⭐112)](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client).
*   [orderbook (⭐296)](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang.
*   [payme (⭐14)](https://github.com/jovandeginste/payme) - QR code generator (ASCII & PNG) for SEPA payments.
*   [sleet (⭐102)](https://github.com/BoltApp/sleet) - One unified interface for multiple Payment Service Providers (PsP) to process online payment.
*   [techan (⭐688)](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies.
*   [ticker (⭐4.4k)](https://github.com/achannarasappa/ticker) - Terminal stock watcher and stock position tracker.
*   [transaction (⭐116)](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode.
*   [vat (⭐99)](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates.

**[⬆ back to top](#contents)**

## Forms

*Libraries for working with forms.*

*   [bind (⭐28)](https://github.com/robfig/bind) - Bind form data to any Go values.
*   [binding (⭐793)](https://github.com/mholt/binding) - Binds form and JSON data from net/http Request to struct.
*   [conform (⭐272)](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
*   [form (⭐564)](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
*   [formam (⭐176)](https://github.com/monoculum/formam) - decode form's values into a struct.
*   [forms (⭐132)](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
*   [gbind (⭐8)](https://github.com/bdjimmy/gbind) - Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation
*   [gorilla/csrf (⭐848)](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services.
*   [httpin (⭐120)](https://github.com/ggicci/httpin) - Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc.
*   [nosurf (⭐1.3k)](https://github.com/justinas/nosurf) - CSRF protection middleware for Go.
*   [qs (⭐64)](https://github.com/sonh/qs) - Go module for encoding structs into URL query parameters.
*   [queryparam (⭐14)](https://github.com/tomwright/queryparam) - Decode `url.Values` into usable struct values of standard or custom types.

**[⬆ back to top](#contents)**

## Functional

*Packages to support functional programming in Go.*

*   [fp-go (⭐135)](https://github.com/repeale/fp-go) - Collection of Functional Programming helpers powered by Golang 1.18+ generics.
*   [fpGo (⭐299)](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang.
*   [fuego (⭐125)](https://github.com/seborama/fuego) - Functional Experiment in Go.
*   [go-underscore (⭐1.3k)](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities.
*   [gofp (⭐132)](https://github.com/rbrahul/gofp) - A lodash like powerful utility library for Golang.
*   [mo (⭐1.1k)](https://github.com/samber/mo) - Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...).
*   [underscore (⭐71)](https://github.com/rjNemo/underscore) - Functional programming helpers for Go 1.18 and beyond.
*   [valor (⭐10)](https://github.com/phelmkamp/valor) - Generic option and result types that optionally contain a value.

**[⬆ back to top](#contents)**

## Game Development

*Awesome game development libraries.*

*   [Azul3D (⭐559)](https://github.com/azul3d/engine) - 3D game engine written in Go.
*   [Ebitengine (⭐7.3k)](https://github.com/hajimehoshi/ebiten) - dead simple 2D game engine in Go.
*   [engo (⭐1.6k)](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
*   [fantasyname (⭐11)](https://github.com/s0rg/fantasyname) - Fantasy names generator.
*   [g3n (⭐2.2k)](https://github.com/g3n/engine) - Go 3D Game Engine.
*   [go-astar (⭐529)](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm.
*   [go-sdl2 (⭐1.9k)](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
*   [go3d (⭐276)](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go.
*   [gonet (⭐1.2k)](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang.
*   [goworld (⭐2.2k)](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping.
*   [Harfang3D (⭐219)](https://github.com/harfang3d/harfang3d) - 3D engine for the Go language, works on Windows and Linux ([Harfang on Go.dev (⭐7)](https://github.com/harfang3d/harfang-go)).
*   [Leaf (⭐4.6k)](https://github.com/name5566/leaf) - Lightweight game server framework.
*   [nano (⭐2.1k)](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework.
*   [Oak (⭐1.3k)](https://github.com/oakmound/oak) - Pure Go game engine.
*   [Pitaya (⭐1.6k)](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.
*   [Pixel (⭐4.1k)](https://github.com/faiface/pixel) - Hand-crafted 2D game library in Go.
*   [prototype (⭐76)](https://github.com/gonutz/prototype) - Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API.
*   [raylib-go (⭐895)](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
*   [termloop (⭐1.3k)](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox.
*   [tile (⭐73)](https://github.com/kelindar/tile) - Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export.

**[⬆ back to top](#contents)**

## Generators

*Tools that generate Go code.*

*   [copygen (⭐191)](https://github.com/switchupcb/copygen) - Generate type-to-type and type-based code without reflection.
*   [generis (⭐38)](https://github.com/senselogic/GENERIS) - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating.
*   [go-enum (⭐392)](https://github.com/abice/go-enum) - Code generation for enums from code comments.
*   [go-linq (⭐3.1k)](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go.
*   [goderive (⭐1k)](https://github.com/awalterschulze/goderive) - Derives functions from input types.
*   [gotype (⭐51)](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package.
*   [goverter (⭐171)](https://github.com/jmattheis/goverter) - Generate converters by defining an interface.
*   [GoWrap (⭐685)](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates.
*   [interfaces (⭐359)](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions.
*   [jennifer (⭐2.6k)](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates.
*   [typeregistry (⭐16)](https://github.com/xiaoxin01/typeregistry) - A library to create type dynamically.

**[⬆ back to top](#contents)**

## Geographic

*Geographic tools and servers*

*   [geoserver (⭐76)](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.
*   [gismanager (⭐48)](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.
*   [godal (⭐83)](https://github.com/airbusgeo/godal) - Go wrapper for GDAL.
*   \[h3-go] - Go bindings for H3, a hierarchical hexagonal geospatial indexing system.
*   [H3 GeoJSON (⭐3)](https://github.com/mmadfox/go-geojson2h3) - Conversion utilities between H3 indexes and GeoJSON.
*   [H3GeoDist (⭐1)](https://github.com/mmadfox/go-h3geo-dist) - Distribution of Uber H3geo cells by virtual nodes.
*   [mbtileserver (⭐420)](https://github.com/consbio/mbtileserver) - A simple Go-based server for map tiles stored in mbtiles format.
*   [osm (⭐237)](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs.
*   [pbf (⭐40)](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder.
*   [S2 geojson (⭐19)](https://github.com/pantrif/s2-geojson) - Convert geojson to s2 cells & demonstrating some S2 geometry features on map.
*   [S2 geometry (⭐1.4k)](https://github.com/golang/geo) - S2 geometry library in Go.
*   [simplefeatures (⭐69)](https://github.com/peterstace/simplefeatures) - simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them.
*   [Tile38 (⭐8.3k)](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing.
*   [Web-Mercator-Projection (⭐2)](https://github.com/jorelosorio/web-mercator-projection) A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection.
*   [WGS84 (⭐91)](https://github.com/wroge/wgs84) - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).

**[⬆ back to top](#contents)**

## Go Compilers

*Tools for compiling Go to other languages.*

*   [c2go (⭐216)](https://github.com/goplus/c2go) - Convert C code to Go code.
*   [c4go (⭐329)](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code.
*   [esp32 (⭐55)](https://github.com/andygeiss/esp32-transpiler) - Transpile Go into Arduino code.
*   [f4go (⭐34)](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code.
*   [gopherjs (⭐12k)](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript.
*   [tardisgo (⭐421)](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.

**[⬆ back to top](#contents)**

## Goroutines

*Tools for managing and working with Goroutines.*

*   [ants (⭐9.4k)](https://github.com/panjf2000/ants) - A high-performance and low-cost goroutine pool in Go.
*   [artifex (⭐140)](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching.
*   [async (⭐92)](https://github.com/reugn/async) - An alternative sync library for Go (Future, Promise, Locks).
*   [async (⭐114)](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic.
*   [async-job (⭐4)](https://github.com/lab210-dev/async-job) - AsyncJob is an asynchronous queue job manager with light code, clear and speed.
*   [breaker (⭐10)](https://github.com/kamilsk/breaker) - Flexible mechanism to make execution flow interruptible.
*   [channelify (⭐25)](https://github.com/ddelizia/channelify) - Transform your function to return channels for easy and powerful parallel processing.
*   [concurrency-limiter (⭐10)](https://github.com/vivek-ng/concurrency-limiter) - Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines.
*   [conexec (⭐13)](https://github.com/ITcathyh/conexec) - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency.
*   [cyclicbarrier (⭐113)](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang.
*   [execpool (⭐13)](https://github.com/hexdigest/execpool) - A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command.
*   [go-actor (⭐15)](https://github.com/vladopajic/go-actor) - A tiny library for writing concurrent programs using actor model.
*   [go-floc (⭐261)](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease.
*   [go-flow (⭐201)](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order.
*   [go-tools/multithreading (⭐8)](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API.
*   [go-trylock (⭐32)](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang.
*   [go-waitgroup (⭐35)](https://github.com/pieterclaerhout/go-waitgroup) - Like `sync.WaitGroup` with error handling and concurrency control.
*   [go-workerpool (⭐6)](https://github.com/zenthangplus/go-workerpool) - Inspired from Java Thread Pool, Go WorkerPool aims to control heavy Go Routines.
*   [go-workers (⭐146)](https://github.com/catmullet/go-workers) - Easily and safely run workers for large data processing pipelines.
*   [goccm (⭐62)](https://github.com/zenthangplus/goccm) - Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently.
*   [gohive (⭐43)](https://github.com/loveleshsharma/gohive) - A highly performant and easy to use Goroutine pool for Go.
*   [gollback (⭐100)](https://github.com/vardius/gollback) - asynchronous simple function utilities, for managing execution of closures and callbacks.
*   [gowl (⭐39)](https://github.com/hamed-yousefi/gowl) - Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status.
*   [goworker (⭐2.7k)](https://github.com/benmanns/goworker) - goworker is a Go-based background worker.
*   [gowp (⭐424)](https://github.com/xxjwxc/gowp) - gowp is concurrency limiting goroutine pool.
*   [gpool (⭐86)](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency.
*   [grpool (⭐715)](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool.
*   [hands (⭐10)](https://github.com/duanckham/hands) - A process controller used to control the execution and return strategies of multiple goroutines.
*   [Hunch (⭐92)](https://github.com/AaronJan/Hunch) - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive.
*   [kyoo (⭐39)](https://github.com/dirkaholic/kyoo) - Provides an unlimited job queue and concurrent worker pools.
*   [neilotoole/errgroup (⭐142)](https://github.com/neilotoole/errgroup) - Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines.
*   [nursery (⭐52)](https://github.com/arunsworld/nursery) - Structured concurrency in Go.
*   [oversight](https://cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
*   [parallel-fn (⭐34)](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel.
*   [pond (⭐662)](https://github.com/alitto/pond) - Minimalistic and High-performance goroutine worker pool written in Go.
*   [pool (⭐703)](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
*   [queue (⭐14)](https://github.com/AnikHasibul/queue) - Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more.
*   [routine (⭐74)](https://github.com/timandy/routine) - `routine` is a `ThreadLocal` for go library. It encapsulates and provides some easy-to-use, non-competitive, high-performance `goroutine` context access interfaces, which can help you access coroutine context information more gracefully.
*   [routine (⭐54)](https://github.com/x-mod/routine) - go routine control with context, support: Main, Go, Pool and some useful Executors.
*   [semaphore (⭐92)](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
*   [semaphore (⭐155)](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
*   [stl (⭐25)](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.
*   [threadpool (⭐82)](https://github.com/shettyh/threadpool) - Golang threadpool implementation.
*   [tunny (⭐3.4k)](https://github.com/Jeffail/tunny) - Goroutine pool for golang.
*   [worker-pool (⭐85)](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool.
*   [workerpool (⭐951)](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.

**[⬆ back to top](#contents)**

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

*   [app (⭐6.6k)](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
*   [fyne (⭐19k)](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android.
*   [gio](https://gioui.org) - Gio is a library for writing cross-platform immediate mode GUI-s in Go. Gio supports all the major platforms: Linux, macOS, Windows, Android, iOS, FreeBSD, OpenBSD and WebAssembly.
*   [go-astilectron (⭐4.6k)](https://github.com/asticode/go-astilectron) - Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).
*   [go-gtk](https://mattn.github.io/go-gtk/) - Go bindings for GTK.
*   [go-sciter (⭐2.5k)](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
*   [goradd/html5tag (⭐4)](https://github.com/goradd/html5tag) - Library for outputting HTML5 tags.
*   [gotk3 (⭐1.8k)](https://github.com/gotk3/gotk3) - Go bindings for GTK3.
*   [gowd (⭐384)](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW\.js. Cross platform.
*   [qt (⭐9.5k)](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
*   [ui (⭐8.2k)](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform.
*   [Wails](https://wails.io) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
*   [walk (⭐6.2k)](https://github.com/lxn/walk) - Windows application library kit for Go.
*   [webview (⭐11k)](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

*Interaction*

*   [AppIndicator Go (⭐3)](https://github.com/gopherlibs/appindicator) - Go bindings for libappindicator3 C library.
*   [gosx-notifier (⭐575)](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go.
*   [mac-activity-tracker (⭐22)](https://github.com/prashantgupta24/activity-tracker) - OSX library to notify about any (pluggable) activity on your machine.
*   [mac-sleep-notifier (⭐22)](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX Sleep/Wake notifications in golang.
*   [robotgo (⭐8k)](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
*   [systray (⭐2.6k)](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area.
*   [trayhost (⭐235)](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar.
*   [zenity (⭐362)](https://github.com/ncruces/zenity) - Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user.

**[⬆ back to top](#contents)**

## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

*   [arduino-cli (⭐3.6k)](https://github.com/arduino/arduino-cli) - Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects.
*   [emgo (⭐991)](https://github.com/ziutek/emgo) - Go-like language for programming embedded systems (e.g. STM32 MCU).
*   [ghw (⭐1.2k)](https://github.com/jaypipes/ghw) - Golang hardware discovery/inspection library.
*   [go-osc (⭐160)](https://github.com/hypebeast/go-osc) - Open Sound Control (OSC) bindings for Go.
*   [go-rpio (⭐1.9k)](https://github.com/stianeikeland/go-rpio) - GPIO for Go, doesn't require cgo.
*   [goroslib (⭐234)](https://github.com/aler9/goroslib) - Robot Operating System (ROS) library for Go.
*   [joystick (⭐39)](https://github.com/0xcafed00d/joystick) - a polled API to read the state of an attached joystick.
*   [sysinfo (⭐394)](https://github.com/zcalusic/sysinfo) - A pure Go library providing Linux OS / kernel / hardware system information.

**[⬆ back to top](#contents)**

## Images

*Libraries for manipulating images.*

*   [bild (⭐3.7k)](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go.
*   [bimg (⭐2.1k)](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips.
*   [cameron (⭐96)](https://github.com/aofei/cameron) - An avatar generator for Go.
*   [canvas (⭐1.1k)](https://github.com/tdewolff/canvas) - Vector graphics to PDF, SVG or rasterized image.
*   [darkroom (⭐202)](https://github.com/gojek/darkroom) - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.
*   [draft (⭐551)](https://github.com/lucasepe/draft) - Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax.
*   [geopattern (⭐1.2k)](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string.
*   [gg (⭐3.7k)](https://github.com/fogleman/gg) - 2D rendering in pure Go.
*   [gift (⭐1.6k)](https://github.com/disintegration/gift) - Package of image processing filters.
*   [gltf (⭐181)](https://github.com/qmuntal/gltf) - Efficient and robust glTF 2.0 reader, writer and validator.
*   [go-cairo (⭐125)](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library.
*   [go-gd (⭐56)](https://github.com/bolknote/go-gd) - Go binding for GD library.
*   [go-nude (⭐362)](https://github.com/koyachi/go-nude) - Nudity detection with Go.
*   [go-webcolors (⭐27)](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go.
*   [go-webp (⭐88)](https://github.com/kolesa-team/go-webp) - Library for encode and decode webp pictures, using libwebp.
*   [gocv (⭐5.1k)](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+.
*   [goimagehash (⭐548)](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package.
*   [goimghdr (⭐40)](https://github.com/corona10/goimghdr) - The imghdr module determines the type of image contained in a file for Go.
*   [govatar (⭐527)](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars.
*   [govips (⭐785)](https://github.com/davidbyttow/govips) - A lightning fast image processing and resizing library for Go.
*   [gowitness (⭐1.9k)](https://github.com/sensepost/gowitness) - Screenshoting webpages using go and headless chrome on command line.
*   [gridder (⭐55)](https://github.com/shomali11/gridder) - A Grid based 2D Graphics library.
*   [image2ascii (⭐705)](https://github.com/qeesung/image2ascii) - Convert image to ASCII.
*   [imagick (⭐1.5k)](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API.
*   [imaginary (⭐4.6k)](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing.
*   [imaging (⭐4.4k)](https://github.com/disintegration/imaging) - Simple Go image processing package.
*   [img (⭐144)](https://github.com/hawx/img) - Selection of image manipulation tools.
*   [ln (⭐3.1k)](https://github.com/fogleman/ln) - 3D line art rendering in Go.
*   [mergi (⭐189)](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
*   [mort (⭐465)](https://github.com/aldor007/mort) - Storage and image processing server written in Go.
*   [mpo (⭐10)](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos.
*   [picfit (⭐1.7k)](https://github.com/thoas/picfit) - An image resizing server written in Go.
*   [pt (⭐2k)](https://github.com/fogleman/pt) - Path tracing engine written in Go.
*   [resize (⭐2.9k)](https://github.com/nfnt/resize) - Image resizing for Go with common interpolation methods.
*   [rez (⭐209)](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD.
*   [scout (⭐8)](https://github.com/jonoton/scout) - Scout is a standalone open source software solution for DIY video security.
*   [smartcrop (⭐1.7k)](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes.
*   [steganography (⭐166)](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography.
*   [stegify (⭐1.1k)](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image.
*   [svgo (⭐1.9k)](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.
*   [tga (⭐32)](https://github.com/ftrvxmtrx/tga) - Package tga is a TARGA image format decoder/encoder.
*   [webp-server (⭐51)](https://github.com/mehdipourfar/webp-server) - Simple and minimal image server capable of storing, resizing, converting and caching images.

**[⬆ back to top](#contents)**

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

*   [connectordb (⭐353)](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT.
*   [devices (⭐256)](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io.
*   [eywa (⭐58)](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices.
*   [flogo (⭐2.1k)](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
*   [gatt (⭐1k)](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals.
*   [gobot (⭐8k)](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things.
*   [huego (⭐220)](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go.
*   [iot (⭐62)](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device.
*   [mainflux (⭐1.9k)](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server.
*   [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
*   [sensorbee (⭐214)](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT.

**[⬆ back to top](#contents)**

## Job Scheduler

*Libraries for scheduling jobs.*

*   [cdule (⭐13)](https://github.com/deepaksinghvi/cdule) - Job scheduler library with database support
*   [cheek (⭐61)](https://github.com/datarootsio/cheek) - A simple crontab like scheduler that aims to offer a KISS approach to job scheduling.
*   [clockwerk (⭐128)](https://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax.
*   [cronticker (⭐7)](https://github.com/krayzpipes/cronticker) - A ticker implementation to support cron schedules.
*   [Dagu (⭐479)](https://github.com/dagu-go/dagu) - No-code workflow executor. it executes DAGs defined in a simple YAML format.
*   [go-cron (⭐214)](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
*   [go-quartz (⭐994)](https://github.com/reugn/go-quartz) - Simple, zero-dependency scheduling library for Go.
*   [gocron (⭐2.5k)](https://github.com/go-co-op/gocron) - Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron (⭐3.1k)](https://github.com/jasonlvhit/gocron).
*   [goflow (⭐74)](https://github.com/fieldryand/goflow) - A workflow orchestrator and scheduler for rapid prototyping of ETL/ML/AI pipelines.
*   [gron (⭐930)](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
*   [gronx (⭐227)](https://github.com/adhocore/gronx) - Cron expression parser, task runner and daemon consuming crontab like task list.
*   [JobRunner (⭐944)](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
*   [jobs (⭐492)](https://github.com/albrow/jobs) - Persistent and flexible background jobs library.
*   [leprechaun (⭐93)](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling.
*   [sched (⭐26)](https://github.com/romshark/sched) - A job scheduler with the ability to fast-forward time.
*   [scheduler (⭐404)](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy.
*   [tasks (⭐119)](https://github.com/madflojo/tasks) - An easy to use in-process scheduler for recurring tasks in Go.

**[⬆ back to top](#contents)**

## JSON

*Libraries for working with JSON.*

*   [ajson (⭐134)](https://github.com/spyzhov/ajson) - Abstract JSON for golang with JSONPath support.
*   [ask (⭐22)](https://github.com/simonnilsson/ask) - Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types.
*   [dynjson (⭐13)](https://github.com/cocoonspace/dynjson) - Client-customizable JSON formats for dynamic APIs.
*   [ej (⭐10)](https://github.com/lucassscaravelli/ej) - Write and read JSON from different sources succinctly.
*   [epoch (⭐11)](https://github.com/vtopc/epoch) - Contains primitives for marshaling/unmarshaling Unix timestamp/epoch to/from build-in time.Time type in JSON.
*   [fastjson (⭐1.7k)](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection.
*   [gjo (⭐114)](https://github.com/skanehira/gjo) - Small utility to create JSON objects.
*   [GJSON (⭐11k)](https://github.com/tidwall/gjson) - Get a JSON value with one line of code.
*   [go-jsonerror (⭐13)](https://github.com/ddymko/go-jsonerror) - Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec.
*   [go-respond (⭐50)](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses.
*   [gojq (⭐184)](https://github.com/elgs/gojq) - JSON query in Golang.
*   [gojson (⭐2.6k)](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON.
*   [JayDiff (⭐93)](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go.
*   [jettison (⭐136)](https://github.com/wI2L/jettison) - Fast and flexible JSON encoder for Go.
*   [jscan (⭐15)](https://github.com/romshark/jscan) - High performance zero-allocation JSON iterator.
*   [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
*   [JSON-to-Proto](https://json-to-proto.github.io/) - Convert JSON to Protobuf online.
*   [json2go (⭐110)](https://github.com/m-zajac/json2go) - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.
*   [jsonapi-errors (⭐13)](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference.
*   [jsoncolor (⭐28)](https://github.com/neilotoole/jsoncolor) - Drop-in replacement for `encoding/json` that outputs colorized JSON.
*   [jsondiff (⭐210)](https://github.com/wI2L/jsondiff) - JSON diff library for Go based on RFC6902 (JSON Patch).
*   [jsonf (⭐64)](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON.
*   [jsongo (⭐107)](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects.
*   [jsonhal (⭐12)](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
*   [jsonic (⭐8)](https://github.com/sinhashubham95/jsonic) - Utilities to handle and query JSON without defining structs in a type safe manner.
*   [jzon (⭐11)](https://github.com/zerosnake0/jzon) - JSON library with standard compatible API/behavior.
*   [kazaam (⭐240)](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents.
*   [mapslice-json (⭐14)](https://github.com/mickep76/mapslice-json) - Go MapSlice for ordered marshal/ unmarshal of maps in JSON.
*   [marshmallow (⭐223)](https://github.com/PerimeterX/marshmallow) - Performant JSON unmarshaling for flexible use cases.
*   [mp (⭐46)](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON.
*   [OjG (⭐526)](https://github.com/ohler55/ojg) - Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath.
*   [omg.jsonparser (⭐4)](https://github.com/dedalqq/omg.jsonparser) - Simple JSON parser with validation by condition via golang struct fields tags.
*   [ujson (⭐60)](https://github.com/olvrng/ujson) - Fast and minimal JSON parser and transformer that works on unstructured JSON.
*   [vjson (⭐31)](https://github.com/miladibra10/vjson) - Go package for validating JSON objects with declaring a JSON schema with fluent API.

**[⬆ back to top](#contents)**

## Logging

*Libraries for generating and working with log files.*

*   [distillog (⭐30)](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels).
*   [glg (⭐172)](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go.
*   [glo (⭐15)](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels.
*   [glog (⭐3.2k)](https://github.com/golang/glog) - Leveled execution logs for Go.
*   [go-cronowriter (⭐50)](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog.
*   [go-log (⭐10)](https://github.com/pieterclaerhout/go-log) - A logging library with stack traces, object dumping and optional timestamps.
*   [go-log (⭐13)](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers.
*   [go-log (⭐32)](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers.
*   [go-log (⭐40)](https://github.com/ian-kent/go-log) - Log4j implementation in Go.
*   [go-logger (⭐281)](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers.
*   [gologger (⭐41)](https://github.com/sadlil/gologger) - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
*   [gomol (⭐19)](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs.
*   [gone/log (⭐43)](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
*   [httpretty (⭐278)](https://github.com/henvic/httpretty) - Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest).
*   [journald (⭐32)](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging.
*   [kemba (⭐9)](https://github.com/clok/kemba) - A tiny debug logging tool inspired by [debug (⭐10k)](https://github.com/visionmedia/debug), great for CLI tools and applications.
*   [log (⭐10)](https://github.com/aerogo/log) - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).
*   [log (⭐1.3k)](https://github.com/apex/log) - Structured logging package for Go.
*   [log (⭐283)](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go.
*   [log (⭐26)](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation.
*   [log (⭐13)](https://github.com/heartwilltell/log) - Simple leveled logging wrapper around standard log package.
*   [log-voyage (⭐93)](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang.
*   [log15 (⭐1.1k)](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go.
*   [logdump (⭐10)](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging.
*   [logex (⭐40)](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib.
*   [logger (⭐157)](https://github.com/azer/logger) - Minimalistic logging library for Go.
*   [logmatic (⭐15)](https://github.com/borderstech/logmatic) - Colorized logger for Golang with dynamic log level configuration.
*   [logo (⭐11)](https://github.com/mbndr/logo) - Golang logger to different configurable writers.
*   [logrus (⭐22k)](https://github.com/Sirupsen/logrus) - Structured logger for Go.
*   [logrusiowriter (⭐14)](https://github.com/cabify/logrusiowriter) - `io.Writer` implementation using [logrus (⭐22k)](https://github.com/sirupsen/logrus) logger.
*   [logrusly (⭐28)](https://github.com/sebest/logrusly) - [logrus (⭐22k)](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).
*   [logur (⭐179)](https://github.com/logur/logur) - An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus (⭐22k)](https://github.com/sirupsen/logrus), [go-kit log (⭐24k)](https://github.com/go-kit/kit/tree/master/log), [zap (⭐17k)](https://github.com/uber-go/zap), [zerolog (⭐7.2k)](https://github.com/rs/zerolog), etc).
*   [logutils (⭐335)](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger.
*   [logxi (⭐350)](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy.
*   [lumberjack (⭐3.6k)](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser.
*   [mlog (⭐28)](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
*   [noodlog (⭐42)](https://github.com/gyozatech/noodlog) - Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings.
*   [onelog (⭐402)](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation.
*   [ozzo-log (⭐121)](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
*   [phuslu/log (⭐457)](https://github.com/phuslu/log) - High performance structured logging.
*   [pp (⭐1.5k)](https://github.com/k0kubun/pp) - Colored pretty printer for Go language.
*   [rollingwriter (⭐250)](https://github.com/arthurkiller/rollingWriter) - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation.
*   [seelog (⭐1.6k)](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting.
*   [slf4g (⭐2)](https://github.com/echocat/slf4g) - Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks.
*   [slog (⭐143)](https://github.com/gookit/slog) - Lightweight, configurable, extensible logger for Go.
*   [spew (⭐5.4k)](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging.
*   [sqldb-logger (⭐274)](https://github.com/simukti/sqldb-logger) - A logger for Go SQL database driver without modify existing \*sql.DB stdlib usage.
*   [stdlog (⭐45)](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
*   [structy/log (⭐5)](https://github.com/structy/log) - A simple to use log system, minimalist but with features for debugging and differentiation of messages.
*   [tail (⭐2.5k)](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program.
*   [xlog (⭐8)](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
*   [xlog (⭐137)](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
*   [xylog (⭐11)](https://github.com/xybor-x/xylog) - Leveled and structured logging, dynamic fields, high performance, zone management, simple configuration, and readable syntax.
*   [yell (⭐1)](https://github.com/jfcg/yell) - Yet another minimalistic logging library.
*   [zap (⭐17k)](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go.
*   [zerolog (⭐7.2k)](https://github.com/rs/zerolog) - Zero-allocation JSON logger.
*   [zkits-logger (⭐23)](https://github.com/edoger/zkits-logger) - A powerful zero-dependency JSON logger.

**[⬆ back to top](#contents)**

## Machine Learning

*Libraries for Machine Learning.*

*   [bayesian (⭐742)](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang.
*   [CloudForest (⭐719)](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
*   [ddt (⭐21)](https://github.com/sgrodriguez/ddt) - Dynamic decision tree, create trees defining customizable rules.
*   [eaopt (⭐818)](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library.
*   [evoli (⭐25)](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library.
*   [fonet (⭐71)](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go.
*   [go-cluster (⭐36)](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms.
*   [go-deep (⭐393)](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go.
*   [go-fann (⭐111)](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library.
*   [go-featureprocessing (⭐88)](https://github.com/nikolaydubina/go-featureprocessing) - Fast and convenient feature processing for low latency machine learning in Go.
*   [go-galib (⭐193)](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang.
*   [go-pr (⭐62)](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang.
*   [gobrain (⭐527)](https://github.com/goml/gobrain) - Neural Networks written in go.
*   [godist (⭐35)](https://github.com/e-dard/godist) - Various probability distributions, and associated methods.
*   [goga (⭐171)](https://github.com/tomcraven/goga) - Genetic algorithm library for Go.
*   [GoLearn (⭐8.6k)](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go.
*   [golinear (⭐45)](https://github.com/danieldk/golinear) - liblinear bindings for Go.
*   [GoMind (⭐37)](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go.
*   [goml (⭐1.4k)](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go.
*   [gonet (⭐75)](https://github.com/dathoangnd/gonet) - Neural Network for Go.
*   [Goptuna (⭐224)](https://github.com/c-bata/goptuna) - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.
*   [goRecommend (⭐193)](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go.
*   [gorgonia (⭐4.7k)](https://github.com/gorgonia/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
*   [gorse (⭐6.3k)](https://github.com/zhenghaoz/gorse) - An offline recommender system backend based on collaborative filtering written in Go.
*   [goscore (⭐84)](https://github.com/asafschers/goscore) - Go Scoring API for PMML.
*   [gosseract (⭐1.9k)](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
*   [libsvm (⭐72)](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
*   [m2cgen (⭐2.3k)](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support.
*   [neat (⭐66)](https://github.com/jinyeom/neat) - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).
*   [neural-go (⭐64)](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation.
*   [ocrserver (⭐531)](https://github.com/otiai10/ocrserver) - A simple OCR API server, seriously easy to be deployed by Docker and Heroku.
*   [onnx-go (⭐443)](https://github.com/owulveryck/onnx-go) - Go Interface to Open Neural Network Exchange (ONNX).
*   [probab (⭐18)](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go.
*   [randomforest (⭐26)](https://github.com/malaschitz/randomForest) - Easy to use Random Forest library for Go.
*   [regommend (⭐301)](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine.
*   [shield (⭐152)](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go.
*   [tfgo (⭐2.1k)](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.
*   [Varis (⭐48)](https://github.com/Xamber/Varis) - Golang Neural Network.

**[⬆ back to top](#contents)**

## Messaging

*Libraries that implement messaging systems.*

*   [ami (⭐24)](https://github.com/kak-tus/ami) - Go client to reliable queues based on Redis Cluster Streams.
*   [amqp (⭐596)](https://github.com/rabbitmq/amqp091-go) - Go RabbitMQ Client Library.
*   [APNs2 (⭐2.7k)](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps.
*   [Asynq (⭐4.6k)](https://github.com/hibiken/asynq) - A simple, reliable, and efficient distributed task queue for Go built on top of Redis.
*   [Beaver (⭐1.4k)](https://github.com/Clivern/Beaver) - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.
*   [Benthos (⭐4.9k)](https://github.com/Jeffail/benthos) - A message streaming bridge between a range of protocols.
*   [Bus (⭐281)](https://github.com/mustafaturan/bus) - Minimalist message bus implementation for internal communication.
*   [Centrifugo (⭐6.5k)](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go.
*   [Chanify (⭐947)](https://github.com/chanify/chanify) - A push notification server send message to your iOS devices.
*   [Commander (⭐61)](https://github.com/jeroenrinzema/commander) - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka.
*   [Confluent Kafka Golang Client (⭐3.7k)](https://github.com/confluentinc/confluent-kafka-go) - confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform.
*   [dbus (⭐782)](https://github.com/godbus/dbus) - Native Go bindings for D-Bus.
*   [drone-line (⭐78)](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.
*   [emitter (⭐440)](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
*   [event (⭐49)](https://github.com/agoalofalife/event) - Implementation of the pattern observer.
*   [EventBus (⭐1.3k)](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility.
*   [gaurun-client (⭐11)](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go.
*   [Glue (⭐407)](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io).
*   [go-mq (⭐79)](https://github.com/cheshir/go-mq) - RabbitMQ client with declarative configuration.
*   [go-notify (⭐63)](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec.
*   [go-nsq (⭐2.3k)](https://github.com/nsqio/go-nsq) - the official Go package for NSQ.
*   [go-res (⭐60)](https://github.com/jirenius/go-res) - Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate.
*   [go-socket.io (⭐4.9k)](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
*   [go-vitotrol (⭐20)](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service.
*   [Gollum (⭐925)](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
*   [golongpoll (⭐614)](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple.
*   [gopush-cluster (⭐2.1k)](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster.
*   [gorush (⭐6.7k)](https://github.com/appleboy/gorush) - Push notification server using [APNs2 (⭐2.7k)](https://github.com/sideshow/apns2) and google [GCM (⭐104)](https://github.com/google/go-gcm).
*   [gosd (⭐21)](https://github.com/alexsniffin/gosd) - A library for scheduling when to dispatch a message to a channel.
*   [guble (⭐154)](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
*   [hare (⭐51)](https://github.com/leozz37/hare) - A user friendly library for sending messages and listening to TCP sockets.
*   [hub (⭐123)](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.
*   [jazz (⭐17)](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.
*   [machinery (⭐6.6k)](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing.
*   [mangos (⭐558)](https://github.com/nanomsg/mangos) - Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability.
*   [melody (⭐2.6k)](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
*   [Mercure (⭐3.1k)](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
*   [messagebus (⭐235)](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
*   [mob (⭐10)](https://github.com/erni27/mob) - mob is a generic-based, simple mediator / event aggregator library. It supports in-process requests / events processing.
*   [NATS Go Client (⭐4.2k)](https://github.com/nats-io/nats) - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
*   [nsq-event-bus (⭐75)](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel.
*   [oplog (⭐114)](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs.
*   [pubsub (⭐387)](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go.
*   [Quamina (⭐284)](https://github.com/timbray/quamina) - Fast pattern-matching for filtering messages and events.
*   [rabbus (⭐94)](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues.
*   [rabtap (⭐227)](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app.
*   [RapidMQ (⭐65)](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
*   [Ratus (⭐60)](https://github.com/hyperonym/ratus) - Ratus is a RESTful asynchronous task queue server.
*   [redisqueue (⭐95)](https://github.com/robinjoseph08/redisqueue) - redisqueue provides a producer and consumer of a queue that uses Redis streams.
*   [rmqconn (⭐20)](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
*   [sarama (⭐9.3k)](https://github.com/Shopify/sarama) - Go library for Apache Kafka.
*   [Uniqush-Push (⭐1.5k)](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices.
*   [zmq4 (⭐1k)](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3 (⭐133)](https://github.com/pebbe/zmq3) and [version 2 (⭐18)](https://github.com/pebbe/zmq2).

**[⬆ back to top](#contents)**

## Microsoft Office

*   [unioffice (⭐3.6k)](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.

### Microsoft Excel

*Libraries for working with Microsoft Excel.*

*   [excelize (⭐13k)](https://github.com/xuri/excelize) - Golang library for reading and writing Microsoft Excel™ (XLSX) files.
*   [exl (⭐13)](https://github.com/go-the-way/exl) - Excel binding to struct written in Go.(Only supports Go1.18+)
*   [go-excel (⭐162)](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table.
*   [goxlsxwriter (⭐19)](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
*   [xlsx (⭐5.4k)](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.
*   [xlsx (⭐155)](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.

**[⬆ back to top](#contents)**

## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

*   [alice (⭐51)](https://github.com/magic003/alice) - Additive dependency injection container for Golang.
*   [di (⭐166)](https://github.com/goava/di) - A dependency injection container for go programming language.
*   [dig (⭐2.8k)](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go.
*   [dingo (⭐150)](https://github.com/i-love-flamingo/dingo) - A dependency injection toolkit for Go, based on Guice.
*   [do (⭐651)](https://github.com/samber/do) - A dependency injection framework based on Generics.
*   [fx (⭐3.2k)](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig).
*   [gocontainer (⭐18)](https://github.com/vardius/gocontainer) - Simple Dependency Injection Container.
*   [goioc/di (⭐213)](https://github.com/goioc/di) - Spring-inspired Dependency Injection Container.
*   [GoLobby/Container (⭐391)](https://github.com/golobby/container) - GoLobby Container is a lightweight yet powerful IoC dependency injection container for the Go programming language.
*   [google/wire (⭐9.4k)](https://github.com/google/wire) - Automated Initialization in Go.
*   [HnH/di (⭐6)](https://github.com/HnH/di) - DI container library that is focused on clean API and flexibility.
*   [kinit (⭐9)](https://github.com/go-kata/kinit) - Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization.
*   [linker (⭐36)](https://github.com/logrange/linker) - A reflection based dependency injection and inversion of control library with components lifecycle support.
*   [nject (⭐21)](https://github.com/muir/nject) - A type safe, reflective framework for libraries, tests, http endpoints, and service startup.
*   [wire (⭐37)](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang.

**[⬆ back to top](#contents)**

### Project Layout

***Unofficial** set of patterns for structuring projects.*

*   [ardanlabs/service (⭐2.5k)](https://github.com/ardanlabs/service) - A [starter kit (⭐2.5k)](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications.
*   [cookiecutter-golang (⭐559)](https://github.com/lacion/cookiecutter-golang) - A Go application boilerplate template for quick starting projects following production best practices.
*   [go-sample (⭐112)](https://github.com/zitryss/go-sample) - A sample layout for Go application projects with the real code.
*   [go-starter (⭐263)](https://github.com/allaboutapps/go-starter) - An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers.
*   [go-todo-backend (⭐177)](https://github.com/Fs02/go-todo-backend) - Go Todo Backend example using modular project layout for product microservice.
*   [gobase (⭐37)](https://github.com/wajox/gobase) - A simple skeleton for golang application with basic setup for real golang application.
*   [golang-standards/project-layout (⭐36k)](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see [this issue (⭐36k)](https://github.com/golang-standards/project-layout/issues/117) for more information. Nonetheless, some may find the layout useful.
*   [golang-templates/seed (⭐343)](https://github.com/golang-templates/seed) - Go application GitHub repository template.
*   [insidieux/inizio (⭐13)](https://github.com/insidieux/inizio) - Golang project layout generator with plugins.
*   [modern-go-application (⭐1.3k)](https://github.com/sagikazarmark/modern-go-application) - Go application boilerplate and example applying modern practices.
*   [pagoda (⭐534)](https://github.com/mikestefanello/pagoda) - Rapid, easy full-stack web development starter kit built in Go.
*   [scaffold (⭐131)](https://github.com/catchplay/scaffold) - Scaffold generates a starter Go project layout. Lets you focus on business logic implemented.
*   [wangyoucao577/go-project-layout (⭐19)](https://github.com/wangyoucao577/go-project-layout) - Set of practices and discussions on how to structure Go project layout.

**[⬆ back to top](#contents)**

### Strings

*Libraries for working with strings.*

*   [bexp (⭐12)](https://github.com/mkungla/bexp) - Go implementation of Brace Expansion mechanism to generate arbitrary strings.
*   [caps (⭐31)](https://github.com/chanced/caps) - A case conversion library.
*   [go-formatter](https://gitlab.com/tymonx/go-formatter) - Implements **replacement fields** surrounded by curly braces `{}` format strings.
*   [gobeam/Stringy (⭐152)](https://github.com/gobeam/Stringy) - String manipulation library to convert string to camel case, snake case, kebab case / slugify etc.
*   [strutil (⭐189)](https://github.com/ozgio/strutil) - String utilities.
*   [sttr (⭐595)](https://github.com/abhimanyu003/sttr) - cross-platform, cli app to perform various operations on string.
*   [xstrings (⭐1.1k)](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages.

**[⬆ back to top](#contents)**

### Uncategorized

*These libraries were placed here because none of the other categories seemed to fit.*

*   [anagent (⭐15)](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
*   [antch (⭐241)](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework.
*   [archiver (⭐3.7k)](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives.
*   [autoflags (⭐38)](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields.
*   [avgRating (⭐13)](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation.
*   [banner (⭐409)](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications.
*   [base64Captcha (⭐1.6k)](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
*   [basexx (⭐4)](https://github.com/bobg/basexx) - Convert to, from, and between digit strings in various number bases.
*   [battery (⭐211)](https://github.com/distatus/battery) - Cross-platform, normalized battery information library.
*   [bitio (⭐205)](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go.
*   [browscap\_go (⭐43)](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](https://browscap.org/).
*   [captcha (⭐122)](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation.
*   [conv (⭐386)](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types.
*   [datacounter (⭐44)](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter.
*   [faker (⭐8)](https://github.com/neotoolkit/faker) - Fake data generator.
*   [faker (⭐67)](https://github.com/pioz/faker) - Random fake data and struct generator for Go.
*   [ffmt (⭐280)](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans.
*   [gatus (⭐3.1k)](https://github.com/TwinProduction/gatus) - Automated service health dashboard.
*   [go-commandbus (⭐6)](https://github.com/lana/go-commandbus) - A slight and pluggable command-bus for Go.
*   [go-commons-pool (⭐1.1k)](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang.
*   [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
*   [go-resiliency (⭐1.6k)](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang.
*   [go-unarr (⭐211)](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives.
*   [gofakeit (⭐2.7k)](https://github.com/brianvoe/gofakeit) - Random data generator written in go.
*   [gommit (⭐100)](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns.
*   [gopsutil (⭐8.4k)](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
*   [gosh (⭐31)](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method.
*   [gosms (⭐1.4k)](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS.
*   [gotoprom (⭐98)](https://github.com/cabify/gotoprom) - Type-safe metrics builder wrapper library for the official Prometheus client.
*   [gountries (⭐363)](https://github.com/pariz/gountries) - Package that exposes country and subdivision data.
*   [gtree (⭐77)](https://github.com/ddddddO/gtree) - Provide CLI and Package for tree output and directories creation from Markdown or programmatically.
*   [health (⭐626)](https://github.com/alexliesenfeld/health) - A simple and flexible health check library for Go.
*   [health (⭐436)](https://github.com/dimiro1/health) - Easy to use, extensible health check library.
*   [healthcheck (⭐240)](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services.
*   [hostutils (⭐12)](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list.
*   [indigo (⭐96)](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58.
*   [lk (⭐262)](https://github.com/hyperboloide/lk) - A simple licensing library for golang.
*   [llvm (⭐977)](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go.
*   [metrics (⭐24)](https://github.com/pascaldekloe/metrics) - Library for metrics instrumentation and Prometheus exposition.
*   [morse (⭐75)](https://github.com/alwindoss/morse) - Library to convert to and from morse code.
*   [numa (⭐11)](https://github.com/lrita/numa) - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code.
*   [openapi (⭐9)](https://github.com/neotoolkit/openapi) - OpenAPI 3.x parser.
*   [pdfgen (⭐60)](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests.
*   [persian (⭐68)](https://github.com/mavihq/persian) - Some utilities for Persian language in go.
*   [sandid (⭐38)](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID.
*   [shellwords (⭐18)](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
*   [shortid (⭐813)](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
*   [shoutrrr (⭐485)](https://github.com/containrrr/shoutrrr) - Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others.
*   [sitemap-format (⭐0)](https://github.com/mingard/sitemap-format) - A simple sitemap generator, with a little syntactic sugar.
*   [stateless (⭐500)](https://github.com/qmuntal/stateless) - A fluent library for creating state machines.
*   [stats (⭐164)](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
*   [turtle (⭐140)](https://github.com/hackebrot/turtle) - Emojis for Go.
*   [url-shortener (⭐39)](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support.
*   [VarHandler (⭐5)](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
*   [varint (⭐3)](https://github.com/chmike/varint) - A faster varying length integer encoder/decoder than the one provided in the standard library.
*   [xdg (⭐29)](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go.
*   [xkg (⭐54)](https://github.com/go-xkg/xkg) - X Keyboard Grabber.
*   [xz (⭐389)](https://github.com/ulikunitz/xz) - Pure golang package for reading and writing xz-compressed files.

**[⬆ back to top](#contents)**

## Natural Language Processing

*Libraries for working with human languages.*

See also [Text Processing](#text-processing) and [Text Analysis](#text-analysis).

### Language Detection

*   [detectlanguage (⭐16)](https://github.com/detectlanguage/detectlanguage-go) - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection.
*   [getlang (⭐143)](https://github.com/rylans/getlang) - Fast natural language detection package.
*   [guesslanguage (⭐56)](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text.
*   [whatlanggo (⭐568)](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).

### Morphological Analyzers

*   [go-stem (⭐69)](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm.
*   [go2vec (⭐49)](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings.
*   [golibstemmer (⭐20)](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2.
*   [gosentiwordnet (⭐9)](https://github.com/dinopuguh/gosentiwordnet) - Sentiment analyzer using sentiwordnet lexicon in Go.
*   [govader (⭐28)](https://github.com/jonreiter/govader) - Go implementation of [VADER Sentiment Analysis (⭐3.8k)](https://github.com/cjhutto/vaderSentiment).
*   [govader-backend (⭐3)](https://github.com/PIMPfiction/govader_backend) - Microservice implementation of [GoVader (⭐28)](https://github.com/jonreiter/govader).
*   [kagome (⭐689)](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go.
*   [libtextcat (⭐12)](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
*   [nlp (⭐380)](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp.
*   [nlp (⭐380)](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
*   [paicehusk (⭐29)](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm.
*   [porter (⭐11)](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
*   [porter2 (⭐46)](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer.
*   [RAKE.go (⭐98)](https://github.com/afjoseph/RAKE.Go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
*   [snowball (⭐34)](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
*   [spaGO (⭐1.3k)](https://github.com/nlpodyssey/spago) - Self-contained Machine Learning and Natural Language Processing library in Go.
*   [spelling-corrector (⭐1)](https://github.com/jorelosorio/spellingcorrector) - A spelling corrector for the Spanish language or create your own.

### Slugifiers

*   [go-slugify (⭐82)](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support.
*   [slug (⭐884)](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support.
*   [Slugify (⭐32)](https://github.com/avelino/slugify) - Go slugify application that handles string.

### Tokenizers

*   [gojieba (⭐2k)](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba (⭐30k)](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm.
*   [gotokenizer (⭐15)](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)
*   [gse (⭐2k)](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other.
*   [MMSEGO (⭐62)](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
*   [prose (⭐3k)](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only.
*   [segment (⭐73)](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/)
*   [sentences (⭐335)](https://github.com/neurosnap/sentences) - Sentence tokenizer:  converts text into a list of sentences.
*   [shamoji (⭐13)](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go.
*   [stemmer (⭐53)](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers.
*   [textcat (⭐68)](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text.

### Translation

*   [go-i18n (⭐2.2k)](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text.
*   [go-localize (⭐46)](https://github.com/m1/go-localize) - Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings.
*   [go-mystem (⭐29)](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer.
*   [go-pinyin (⭐1.3k)](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter.
*   [gotext (⭐360)](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go.
*   [icu (⭐21)](https://github.com/goodsign/icu) - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
*   [iuliia-go (⭐34)](https://github.com/mehanizm/iuliia-go) - Transliterate Cyrillic → Latin in every possible way.
*   [spreak (⭐15)](https://github.com/vorlif/spreak) - Flexible translation and humanization library for Go, based on the concepts behind gettext.
*   [t (⭐12)](https://github.com/youthlin/t) - Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate (⭐12)](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template.

### Transliteration

*   [enca (⭐13)](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings.
*   [go-unidecode (⭐98)](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text.
*   [gounidecode (⭐76)](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go.
*   [transliterator (⭐26)](https://github.com/alexsergivan/transliterator) - Provides one-way string transliteration with supporting of language-specific transliteration rules.

**[⬆ back to top](#contents)**

## Networking

*Libraries for working with various layers of the network.*

*   [arp (⭐300)](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826.
*   [buffstreams (⭐251)](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy.
*   [canopus (⭐149)](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252).
*   [cidranger (⭐755)](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go.
*   [dhcp6 (⭐76)](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
*   [dns (⭐6.6k)](https://github.com/miekg/dns) - Go library for working with DNS.
*   [dnsmonster (⭐215)](https://github.com/mosajjal/dnsmonster) - Passive DNS Capture/Monitoring Framework.
*   [easytcp (⭐510)](https://github.com/DarthPestilane/easytcp) - A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful.
*   [ether (⭐78)](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames.
*   [ethernet (⭐247)](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshaling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
*   [fasthttp (⭐19k)](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
*   [fortio (⭐2.7k)](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
*   [ftp (⭐1k)](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959).
*   [ftpserverlib (⭐336)](https://github.com/fclairamb/ftpserverlib) - Fully featured FTP server library.
*   [fullproxy (⭐40)](https://github.com/shoriwe/fullproxy) - A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols.
*   [gaio (⭐470)](https://github.com/xtaci/gaio) - High performance async-io networking for Golang in proactor mode.
*   [gev (⭐1.5k)](https://github.com/Allenxuxu/gev) - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode.
*   [gldap (⭐80)](https://github.com/jimlambrt/gldap) - gldap provides an ldap server implementation and you provide handlers for its ldap operations.
*   [gmqtt (⭐756)](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
*   [gnet (⭐7.1k)](https://github.com/panjf2000/gnet) - `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go.
*   [gNxI (⭐225)](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols.
*   [go-getter (⭐1.4k)](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL.
*   [go-powerdns (⭐65)](https://github.com/joeig/go-powerdns) - PowerDNS API bindings for Golang.
*   [go-stun (⭐535)](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389).
*   [gobgp (⭐3k)](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language.
*   [gohooks (⭐22)](https://github.com/averageflow/gohooks) - GoHooks make it easy to send and consume secured web-hooks from a Go application. Inspired by Spatie's Laravel Webhook Client and Server.
*   [golibwireshark (⭐26)](https://github.com/sunwxg/golibwireshark) - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
*   [gopacket (⭐5.2k)](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings.
*   [gopcap (⭐461)](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap.
*   [goshark (⭐15)](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
*   [gosnmp (⭐913)](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions.
*   [gotcp (⭐500)](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications.
*   [grab (⭐1.1k)](https://github.com/cavaliercoder/grab) - Go package for managing file downloads.
*   [graval (⭐28)](https://github.com/koofr/graval) - Experimental FTP server framework.
*   [HTTPLab (⭐3.8k)](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses.
*   [httpproxy (⭐18)](https://github.com/wzshiming/httpproxy) - HTTP proxy handler and dialer.
*   [iplib (⭐94)](https://github.com/c-robinson/iplib) - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
*   [jazigo (⭐185)](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
*   [kcp-go (⭐3.5k)](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol.
*   [kcptun (⭐13k)](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol.
*   [lhttp (⭐679)](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily.
*   [linkio (⭐53)](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces.
*   [llb (⭐13)](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
*   [mdns (⭐914)](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang.
*   [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
*   [nbio (⭐1k)](https://github.com/lesismal/nbio) - Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use.
*   [netpoll (⭐3.2k)](https://github.com/cloudwego/netpoll) - A high-performance non-blocking I/O networking framework, which focused on RPC scenarios, developed by ByteDance.
*   [NFF-Go (⭐1.3k)](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
*   [packet (⭐74)](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed.
*   [panoptes-stream (⭐37)](https://github.com/yahoo/panoptes-stream) - A cloud native distributed streaming network telemetry (gNMI, Juniper JTI and Cisco MDT).
*   [peerdiscovery (⭐564)](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast.
*   [portproxy (⭐51)](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it.
*   [publicip (⭐26)](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress).
*   [quic-go (⭐7.5k)](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go.
*   [raw (⭐423)](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface.
*   [sftp (⭐1.2k)](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in <https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>.
*   [ssh (⭐2.8k)](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh).
*   [sslb (⭐143)](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
*   [stun (⭐487)](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol.
*   [tcp\_server (⭐420)](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster.
*   [tspool (⭐14)](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server.
*   [utp (⭐164)](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation.
*   [vssh (⭐873)](https://github.com/yahoo/vssh) - Go library for building network and server automation over SSH protocol.
*   [water (⭐1.6k)](https://github.com/songgao/water) - Simple TUN/TAP library.
*   [webrtc (⭐10k)](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API.
*   [winrm (⭐386)](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines.
*   [xtcp (⭐136)](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol.

**[⬆ back to top](#contents)**

### HTTP Clients

*Libraries for making HTTP requests.*

*   [gentleman (⭐975)](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library.
*   [go-cleanhttp (⭐271)](https://github.com/hashicorp/go-cleanhttp) - Get easily stdlib HTTP client, which does not share any state with other clients.
*   [go-http-client (⭐47)](https://github.com/bozd4g/go-http-client) - Make http calls simply and easily.
*   [go-otelroundtripper (⭐68)](https://github.com/NdoleStudio/go-otelroundtripper) - Go http.RoundTripper that emits open telemetry metrics for HTTP requests.
*   [go-req (⭐16)](https://github.com/wenerme/go-req) - Declarative golang HTTP client.
*   [go-retryablehttp (⭐1.4k)](https://github.com/hashicorp/go-retryablehttp) - Retryable HTTP client in Go.
*   [go-zoox/fetch (⭐20)](https://github.com/go-zoox/fetch) - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API.
*   [grequests (⭐1.9k)](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library.
*   [heimdall (⭐2.3k)](https://github.com/gojektech/heimdall) - An enhanced http client with retry and hystrix capabilities.
*   [httpc (⭐5)](https://github.com/valord577/httpc) - A customizable and simple HTTP client library. Only depend on the stdlib HTTP client.
*   [httpretry (⭐26)](https://github.com/ybbus/httpretry) - Enriches the default go HTTP client with retry functionality.
*   [pester (⭐608)](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency.
*   [req (⭐2.8k)](https://github.com/imroc/req) - Simple Go HTTP client with Black Magic (Less code and More efficiency).
*   [request (⭐219)](https://github.com/monaco-io/request) - HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency.
*   [requests (⭐444)](https://github.com/carlmjohnson/requests) - HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools.
*   [resty (⭐6.9k)](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client.
*   [rq (⭐42)](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client.
*   [sling (⭐1.5k)](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests.

**[⬆ back to top](#contents)**

## OpenGL

*Libraries for using OpenGL in Go.*

*   [gl (⭐941)](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow).
*   [glfw (⭐1.3k)](https://github.com/go-gl/glfw) - Go bindings for GLFW 3.
*   [go-glmatrix (⭐5)](https://github.com/technohippy/go-glmatrix) - Go port of [glMatrix](https://glmatrix.net/) library.
*   [goxjs/gl (⭐161)](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
*   [goxjs/glfw (⭐77)](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events.
*   [mathgl (⭐465)](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM.

**[⬆ back to top](#contents)**

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques.*

*   [bun (⭐1.6k)](https://github.com/uptrace/bun) - SQL-first Golang ORM. Successor of go-pg.
*   [cacheme (⭐22)](https://github.com/Yiling-J/cacheme-go) - Schema based, typed Redis caching/memoize framework for Go.
*   [ent (⭐12k)](https://github.com/facebook/ent) - An entity framework for Go. Simple, yet powerful ORM for modeling and querying data.
*   [go-firestorm (⭐38)](https://github.com/jschoedt/go-firestorm) - A simple ORM for Google/Firebase Cloud Firestore.
*   [go-sql (⭐168)](https://github.com/rushteam/gosql) - A easy ORM for mysql.
*   [go-sqlbuilder (⭐864)](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM.
*   [go-store (⭐109)](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go.
*   [golobby/orm (⭐115)](https://github.com/golobby/orm) - Simple, fast, type-safe, generic orm for developer happiness.
*   [GORM (⭐30k)](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly.
*   [gormt (⭐2k)](https://github.com/xxjwxc/gormt) - Mysql database to golang gorm struct.
*   [gorp (⭐3.6k)](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go.
*   [grimoire (⭐158)](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
*   [lore (⭐11)](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
*   [marlow (⭐12)](https://github.com/marlow/marlow) - Generated ORM from project structs for compile time safety assurances.
*   [pop/soda (⭐1.3k)](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
*   [Prisma (⭐1.3k)](https://github.com/prisma/prisma-client-go) - Prisma Client Go, Typesafe database access for Go.
*   [reform (⭐1.4k)](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation.
*   [rel (⭐598)](https://github.com/go-rel/rel) - Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API.
*   [SQLBoiler (⭐5.3k)](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
*   [upper.io/db (⭐3.2k)](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
*   [XORM](https://gitea.com/xorm/xorm) - Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle).
*   [Zoom (⭐294)](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis.

**[⬆ back to top](#contents)**

## Package Management

*Official tooling for dependency and package management*

*   [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

*Official experimental tooling for package management*

*   [dep (⭐13k)](https://github.com/golang/dep) - Go dependency tool.
*   [vgo](https://go.googlesource.com/vgo/) - Versioned Go.

*Unofficial libraries for package and dependency management.*

*   [glide (⭐8.2k)](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
*   [godep (⭐5.6k)](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
*   [gom (⭐1.4k)](https://github.com/mattn/gom) - Go Manager - bundle for go.
*   [goop (⭐779)](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler.
*   [gop (⭐50)](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH.
*   [gopm (⭐2.5k)](https://github.com/gpmgo/gopm) - Go Package Manager.
*   [govendor (⭐5k)](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file.
*   [gpm (⭐1.2k)](https://github.com/pote/gpm) - Barebones dependency manager for Go.
*   [gup (⭐150)](https://github.com/nao1215/gup) - Update binaries installed by "go install".
*   [johnny-deps (⭐214)](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git.
*   [modgv (⭐443)](https://github.com/lucasepe/modgv) - Converts 'go mod graph' output into Graphviz's DOT language.
*   [mvn-golang (⭐146)](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.
*   [nut (⭐238)](https://github.com/jingweno/nut) - Vendor Go dependencies.
*   [VenGO (⭐124)](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments.

**[⬆ back to top](#contents)**

## Performance

*   [go-instrument (⭐7)](https://github.com/nikolaydubina/go-instrument) - Automatically add spans to all methods and functions.
*   [jaeger (⭐17k)](https://github.com/jaegertracing/jaeger) - A distributed tracing system.
*   [pixie (⭐4k)](https://github.com/pixie-labs/pixie) - No instrumentation tracing for Golang applications via eBPF.
*   [profile (⭐1.8k)](https://github.com/pkg/profile) - Simple profiling support package for Go.
*   [statsviz (⭐2.5k)](https://github.com/arl/statsviz) - Live visualization of your Go application runtime statistics.
*   [tracer (⭐68)](https://github.com/kamilsk/tracer) - Simple, lightweight tracing.

**[⬆ back to top](#contents)**

## Query Language

*   [api-fu (⭐45)](https://github.com/ccbrown/api-fu) - Comprehensive GraphQL implementation.
*   [dasel (⭐3.8k)](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies.
*   [gojsonq (⭐2k)](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data.
*   [goven (⭐39)](https://github.com/SeldonIO/goven) - A drop-in query language for any database schema.
*   [gqlgen (⭐8.3k)](https://github.com/99designs/gqlgen) - go generate based graphql server library.
*   [graphql (⭐57)](https://github.com/tmc/graphql) - graphql parser + utilities.
*   [graphql (⭐4.3k)](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use.
*   [graphql-go (⭐8.9k)](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go.
*   [gws (⭐5)](https://github.com/Zaba505/gws) - Apollos' "GraphQL over Websocket" client and server implementation.
*   [jsonpath (⭐12)](https://github.com/AsaiYusuke/jsonpath) - A query library for retrieving part of JSON based on JSONPath syntax.
*   [jsonql (⭐256)](https://github.com/elgs/jsonql) - JSON query expression library in Golang.
*   [jsonslice (⭐72)](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters.
*   [rql (⭐265)](https://github.com/a8m/rql) - Resource Query Language for REST API.
*   [rqp (⭐46)](https://github.com/timsolov/rest-query-parser) - Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query.
*   [straf (⭐34)](https://github.com/SonicRoshan/straf) - Easily Convert Golang structs to GraphQL objects.

**[⬆ back to top](#contents)**

## Resource Embedding

*   [debme (⭐22)](https://github.com/leaanthony/debme) - Create an `embed.FS` from an existing `embed.FS` subdirectory.
*   [esc (⭐629)](https://github.com/mjibson/esc) - Embeds files into Go programs and provides http.FileSystem interfaces to them.
*   [fileb0x (⭐619)](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use.
*   [go-resources (⭐176)](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go.
*   [go.rice (⭐2.3k)](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy.
*   [mule (⭐12)](https://github.com/wlbr/mule) - Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focussed on simplicity.
*   [packr (⭐3.4k)](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries.
*   [rebed (⭐23)](https://github.com/soypat/rebed) - Recreate folder structures and files from Go 1.16's `embed.FS` type
*   [statics (⭐65)](https://github.com/go-playground/statics) - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
*   [statik (⭐3.5k)](https://github.com/rakyll/statik) - Embeds static files into a Go executable.
*   [templify (⭐28)](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries.
*   [vfsgen (⭐949)](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem.

**[⬆ back to top](#contents)**

## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*

*   [assocentity (⭐11)](https://github.com/ndabAP/assocentity) - Package assocentity returns the average distance from words to a given entity.
*   [bradleyterry (⭐7)](https://github.com/seanhagen/bradleyterry) - Provides a Bradley-Terry Model for pairwise comparisons.
*   [calendarheatmap (⭐366)](https://github.com/nikolaydubina/calendarheatmap) - Calendar heatmap in plain Go inspired by Github contribution activity.
*   [chart (⭐746)](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types.
*   [dataframe-go (⭐900)](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for machine-learning and statistics (similar to pandas).
*   [decimal (⭐29)](https://github.com/db47h/decimal) - Package decimal implements arbitrary-precision decimal floating-point arithmetic.
*   [evaler (⭐50)](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator.
*   [ewma (⭐394)](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages.
*   [geom (⭐53)](https://github.com/skelterjohn/geom) - 2D geometry for golang.
*   [go-dsp (⭐799)](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go.
*   [go-estimate (⭐101)](https://github.com/milosgajdos/go-estimate) - State estimation and filtering algorithms in Go.
*   [go-gt (⭐8)](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language.
*   [godesim (⭐20)](https://github.com/soypat/godesim) - Extended/multivariable ODE solver framework for event-based simulations with simple API.
*   [goent (⭐28)](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures.
*   [gohistogram (⭐167)](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams.
*   [gonum (⭐6.2k)](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
*   [gonum/plot (⭐2.3k)](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go.
*   [goraph (⭐699)](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorithm visualization).
*   [gosl (⭐1.7k)](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
*   [GoStats (⭐20)](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.
*   [graph (⭐591)](https://github.com/yourbasic/graph) - Library of basic graph algorithms.
*   [jsonl-graph (⭐61)](https://github.com/nikolaydubina/jsonl-graph) - Tool to manipulate JSONL graphs with graphviz support.
*   [ode (⭐20)](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
*   [orb (⭐594)](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
*   [pagerank (⭐78)](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go.
*   [piecewiselinear (⭐23)](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library.
*   [PiHex (⭐18)](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
*   [rootfinding (⭐10)](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions.
*   [sparse (⭐136)](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
*   [stats (⭐2.6k)](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library.
*   [streamtools (⭐1.3k)](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data.
*   [TextRank (⭐166)](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
*   [triangolatte (⭐30)](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.

**[⬆ back to top](#contents)**

## Security

*Libraries that are used to help make your application more secure.*

*   [acmetool (⭐1.9k)](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal.
*   [acra (⭐1.1k)](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.
*   [age (⭐12k)](https://github.com/FiloSottile/age) - A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability.
*   [argon2-hashing (⭐19)](https://github.com/andskur/argon2-hashing) - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package.
*   [argon2pw (⭐89)](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison.
*   [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
*   [BadActor (⭐312)](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban.
*   [Cameradar (⭐3.1k)](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras.
*   [certificates (⭐24)](https://github.com/mvmaasakkers/certificates) - An opinionated tool for generating tls certificates.
*   [CertMagic (⭐4.3k)](https://github.com/caddyserver/certmagic) - Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal.
*   [Coraza (⭐769)](https://github.com/corazawaf/coraza) - Enterprise-ready, modsecurity and OWASP CRS compatible WAF library.
*   [dongle (⭐294)](https://github.com/golang-module/dongle) - A simple, semantic and developer-friendly golang package for encoding\&decoding and encryption\&decryption.
*   [firewalld-rest (⭐325)](https://github.com/prashantgupta24/firewalld-rest) - A rest application to dynamically update firewalld rules on a linux server.
*   [go-generate-password (⭐47)](https://github.com/m1/go-generate-password) - Password generator that can be used on the cli or as a library.
*   [go-htpasswd (⭐27)](https://github.com/tg123/go-htpasswd) - Apache htpasswd Parser for Go.
*   [go-password-validator (⭐364)](https://github.com/lane-c-wagner/go-password-validator) - Password validator based on raw cryptographic entropy values.
*   [go-yara (⭐277)](https://github.com/hillu/go-yara) - Go Bindings for [YARA (⭐130)](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)".
*   [goArgonPass (⭐16)](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.
*   [goSecretBoxPassword (⭐53)](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords.
*   [Interpol](https://bitbucket.org/vahidi/interpol) - Rule-based data generator for fuzzing and penetration testing.
*   [lego (⭐5.7k)](https://github.com/go-acme/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
*   [memguard (⭐2.2k)](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory.
*   [nacl (⭐529)](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's.
*   [optimus-go (⭐326)](https://github.com/pjebs/optimus-go) - ID hashing and Obfuscation using Knuth's Algorithm.
*   [passlib (⭐271)](https://github.com/hlandau/passlib) - Futureproof password hashing library.
*   [secret (⭐20)](https://github.com/rsjethani/secret) - Prevent your secrets from leaking into logs, std\* etc.
*   [secure (⭐2k)](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins.
*   [secureio (⭐26)](https://github.com/xaionaro-go/secureio) - An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519.
*   [simple-scrypt (⭐182)](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
*   [ssh-vault (⭐360)](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys.
*   [sslmgr (⭐16)](https://github.com/adrianosela/sslmgr) - SSL certificates made easy with a high level wrapper around acme/autocert.
*   [themis (⭐1.6k)](https://github.com/cossacklabs/themis) - high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps.

**[⬆ back to top](#contents)**

## Serialization

*Libraries and tools for binary serialization.*

*   [asn1 (⭐52)](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang.
*   [bambam (⭐65)](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go.
*   [bel (⭐31)](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
*   [binstruct (⭐62)](https://github.com/ghostiam/binstruct) - Golang binary decoder for mapping data into the structure.
*   [cbor (⭐501)](https://github.com/fxamacker/cbor) - Small, safe, and easy CBOR encoding and decoding library.
*   [colfer (⭐677)](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format.
*   [csvutil (⭐763)](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
*   [elastic (⭐19)](https://github.com/epiclabs-io/elastic) - Convert slices, maps or any other unknown value across different types at run-time, no matter what.
*   [fixedwidth (⭐8)](https://github.com/huydang284/fixedwidth) - Fixed-width text formatting (UTF-8 supported).
*   [fwencoder (⭐22)](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go.
*   [go-capnproto (⭐285)](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go.
*   [go-codec (⭐1.7k)](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
*   [go-lctree (⭐4)](https://github.com/sbourlon/go-lctree) - Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation).
*   [gogoprotobuf (⭐5.5k)](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets.
*   [goprotobuf (⭐8.8k)](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
*   [jsoniter (⭐11k)](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json".
*   [mapstructure (⭐6.3k)](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures.
*   [php\_session\_decoder (⭐155)](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
*   [pletter (⭐19)](https://github.com/vimeda/pletter) - A standard way to wrap a proto message for message brokers.
*   [structomap (⭐137)](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures.
*   [unitpacking (⭐5)](https://github.com/recolude/unitpacking) - Library to pack unit vectors into as fewest bytes as possible.

**[⬆ back to top](#contents)**

## Server Applications

*   [algernon (⭐2.1k)](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
*   [Caddy (⭐44k)](https://github.com/caddyserver/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
*   [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
*   [cortex-tenant (⭐57)](https://github.com/blind-oracle/cortex-tenant) - Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels.
*   [devd (⭐3.3k)](https://github.com/cortesi/devd) - Local webserver for developers.
*   [discovery (⭐1.7k)](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover.
*   [dudeldu (⭐138)](https://github.com/krotik/dudeldu) - A simple SHOUTcast server.
*   [dummy (⭐162)](https://github.com/neotoolkit/dummy) - Run mock server based off an API contract with one command.
*   [Easegress (⭐4.9k)](https://github.com/megaease/easegress) - A cloud native high availability/performance traffic orchestration system with observability and extensibility.
*   [etcd (⭐42k)](https://github.com/coreos/etcd) - Highly-available key value store for shared configuration and service discovery.
*   [Euterpe (⭐446)](https://github.com/ironsmile/euterpe) - Self-hosted music streaming server with built-in web UI and REST API.
*   [Fider (⭐2.1k)](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback.
*   [Flagr (⭐2k)](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service.
*   [flipt (⭐1.9k)](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js
*   [go-feature-flag (⭐546)](https://github.com/thomaspoignant/go-feature-flag) - A feature flag solution, with only a YAML file in the backend (S3, GitHub, HTTP, local file ...), no server to install, just add a file in a central system and refer to it.
*   [go-proxy-cache (⭐68)](https://github.com/fabiocicerchia/go-proxy-cache) - Simple Reverse Proxy with Caching, written in Go, using Redis.
*   [jackal (⭐1.4k)](https://github.com/ortuman/jackal) - An XMPP server written in Go.
*   [lets-proxy2 (⭐69)](https://github.com/rekby/lets-proxy2) - Reverse proxy for handle https with issue certificates in fly from lets-encrypt.
*   [minio (⭐36k)](https://github.com/minio/minio) - Minio is a distributed object storage server.
*   [Moxy (⭐8)](https://github.com/sinhashubham95/moxy) - Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint.
*   [nginx-prometheus (⭐34)](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus.
*   [nsq](https://nsq.io/) - A realtime distributed messaging platform.
*   [protoxy (⭐28)](https://github.com/camgraff/protoxy) - A proxy server that converts JSON request bodies to Protocol Buffers.
*   [psql-streamer (⭐46)](https://github.com/blind-oracle/psql-streamer) - Stream database events from PostgreSQL to Kafka.
*   [riemann-relay (⭐2)](https://github.com/blind-oracle/riemann-relay) - Relay to load-balance Riemann events and/or convert them to Carbon.
*   [RoadRunner (⭐6.9k)](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager.
*   [SFTPGo (⭐5.1k)](https://github.com/drakkan/sftpgo) - Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage.
*   [simple-jwt-provider (⭐30)](https://github.com/leberKleber/simple-jwt-provider) - Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management.
*   [Trickster (⭐1.8k)](https://github.com/tricksterproxy/trickster) - HTTP reverse proxy cache and time series accelerator.
*   [Wish (⭐1.7k)](https://github.com/charmbracelet/wish) - Make SSH apps, just like that!

**[⬆ back to top](#contents)**

## Stream Processing

*Libraries and tools for stream processing and reactive programming.*

*   [go-streams (⭐1.1k)](https://github.com/reugn/go-streams) - Go stream processing library.
*   [goio (⭐52)](https://github.com/primetalk/goio) - An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2.
*   [machine (⭐118)](https://github.com/whitaker-io/machine) - Go library for writing and generating stream workers with built in metrics and traceability.
*   [stream (⭐69)](https://github.com/youthlin/stream) - Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce...

**[⬆ back to top](#contents)**

## Template Engines

*Libraries and tools for templating and lexing.*

*   [ego (⭐538)](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
*   [extemplate (⭐50)](https://github.com/dannyvankooten/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance.
*   [fasttemplate (⭐652)](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/).
*   [gospin (⭐40)](https://github.com/m1/gospin) - Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations.
*   [got (⭐3)](https://github.com/goradd/got) - A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more.
*   [goview (⭐307)](https://github.com/foolin/goview) - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application.
*   [jet (⭐973)](https://github.com/CloudyKit/jet) - Jet template engine.
*   [liquid (⭐181)](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates.
*   [maroto (⭐832)](https://github.com/johnfercher/maroto) - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple.
*   [pongo2 (⭐2.4k)](https://github.com/flosch/pongo2) - Django-like template-engine for Go.
*   [quicktemplate (⭐2.6k)](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
*   [raymond (⭐499)](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go.
*   [Razor (⭐803)](https://github.com/sipin/gorazor) - Razor view engine for Golang.
*   [Soy (⭐167)](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
*   [sprig (⭐3.3k)](https://github.com/Masterminds/sprig) - Useful template functions for Go templates.
*   [tbd (⭐22)](https://github.com/lucasepe/tbd) - A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata.

**[⬆ back to top](#contents)**

## Testing

*Libraries for testing codebases and generating test data.*

*   Testing Frameworks
    *   [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
    *   [assert (⭐49)](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
    *   [badio (⭐10)](https://github.com/cavaliercoder/badio) - Extensions to Go's `testing/iotest` package.
    *   [baloo (⭐744)](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy.
    *   [be (⭐27)](https://github.com/carlmjohnson/be) - The minimalist generic test assertion library.
    *   [biff (⭐12)](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible.
    *   [charlatan (⭐199)](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests.
    *   [commander (⭐206)](https://github.com/SimonBaeumer/commander) - Tool for testing cli applications on windows, linux and osx.
    *   [covergates (⭐52)](https://github.com/covergates/covergates) - Self-hosted code coverage report review and management service.
    *   [cupaloy (⭐233)](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework.
    *   [dbcleaner (⭐144)](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
    *   [diff (⭐1)](https://github.com/terrastruct/diff) - Beautiful Git-style diffs to easily compare expected vs actual.
    *   [dsunit (⭐42)](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files.
    *   [embedded-postgres (⭐465)](https://github.com/fergusstrange/embedded-postgres) - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test.
    *   [endly (⭐225)](https://github.com/viant/endly) - Declarative end to end functional testing.
    *   [fixenv (⭐8)](https://github.com/rekby/fixenv) - Fixture manage engine, inspired by pytest fixtures.
    *   [flute (⭐17)](https://github.com/suzuki-shunsuke/flute) - HTTP client testing framework.
    *   [frisby (⭐274)](https://github.com/verdverm/frisby) - REST API testing framework.
    *   [gherkingen (⭐50)](https://github.com/hedhyw/gherkingen) - BDD boilerplate generator and framework.
    *   [ginkgo](https://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
    *   [gnomock (⭐970)](https://github.com/orlangure/gnomock) - integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks.
    *   [go-carpet (⭐231)](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal.
    *   [go-cmp (⭐3.2k)](https://github.com/google/go-cmp) - Package for comparing Go values in tests.
    *   [go-hit (⭐145)](https://github.com/Eun/go-hit) - Hit is an http integration test framework written in golang.
    *   [go-mutesting (⭐561)](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code.
    *   [go-mysql-test-container (⭐2)](https://github.com/arikama/go-mysql-test-container) - Golang MySQL testcontainer to help with MySQL integration testing.
    *   [go-snaps (⭐30)](http://github.com/gkampitakis/go-snaps) - Jest-like snapshot testing in Golang.
    *   [go-testdeep (⭐327)](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package.
    *   [go-testpredicate (⭐5)](https://github.com/maargenton/go-testpredicate) - Test predicate style assertions library with extensive diagnostics output.
    *   [go-vcr (⭐963)](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
    *   [goblin (⭐867)](https://github.com/franela/goblin) - Mocha like testing framework fo Go.
    *   [goc (⭐590)](https://github.com/qiniu/goc) - Goc is a comprehensive coverage testing system for The Go Programming Language.
    *   [gocheck](https://labix.org/gocheck) - More advanced testing framework alternative to gotest.
    *   [GoConvey (⭐7.5k)](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload.
    *   [gocrest (⭐85)](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions.
    *   [godog (⭐1.8k)](https://github.com/cucumber/godog) - Cucumber BDD framework for Go.
    *   [gofight (⭐428)](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework.
    *   [gogiven (⭐15)](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go.
    *   [gomatch (⭐44)](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns.
    *   [gomega](https://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
    *   [Gont (⭐15)](https://github.com/stv0g/gont) - Go network testing toolkit for testing building complex network topologies using Linux namespaces.
    *   [GoSpec (⭐114)](https://github.com/orfjackal/gospec) - BDD-style testing framework for the Go programming language.
    *   [gospecify (⭐53)](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
    *   [gosuite (⭐12)](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
    *   [got (⭐255)](https://github.com/ysmood/got) - An enjoyable golang test framework.
    *   [gotest.tools (⭐366)](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns.
    *   [Hamcrest (⭐28)](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
    *   [httpexpect (⭐2k)](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
    *   [is (⭐1.5k)](https://github.com/matryer/is) - Professional lightweight testing mini-framework for Go.
    *   [jsonassert (⭐95)](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly.
    *   [omg.testingtools (⭐1)](https://github.com/dedalqq/omg.testingtools) - The simple library for change a values of private fields for testing.
    *   [restit (⭐55)](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test.
    *   [schema (⭐19)](https://github.com/jgroeneveld/schema) - Quick and easy expression matching for JSON schemas used in requests and responses.
    *   [stop-and-go (⭐7)](https://github.com/elgohr/stop-and-go) - Testing helper for concurrency.
    *   [testcase (⭐103)](https://github.com/adamluzsi/testcase) - Idiomatic testing framework for Behavior Driven Development.
    *   [testfixtures (⭐871)](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications.
    *   [Testify (⭐18k)](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package.
    *   [testmd](https://godoc.org/github.com/tvastar/test/cmd/testmd) - Convert markdown snippets into testable go code.
    *   [testsql (⭐14)](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished.
    *   [testza (⭐408)](https://github.com/MarvinJWendt/testza) - Full-featured test framework with nice colorized output.
    *   [trial (⭐6)](https://github.com/jgroeneveld/trial) - Quick and easy extendable assertions without introducing much boilerplate.
    *   [Tt (⭐5)](https://github.com/vcaesar/tt) - Simple and colorful test tools.
    *   [wstest (⭐96)](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler.

*   Mock
    *   [counterfeiter (⭐739)](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects.
    *   [genmock](https://gitlab.com/so_literate/genmock) - Go mocking system with code generator for building calls of the interface methods.
    *   [go-localstack (⭐57)](https://github.com/elgohr/go-localstack) - Tool for using localstack in AWS testing.
    *   [go-sqlmock (⭐4.8k)](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions.
    *   [go-txdb (⭐491)](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes.
    *   [gock (⭐1.7k)](https://github.com/h2non/gock) - Versatile HTTP mocking made easy.
    *   [gomock (⭐8.2k)](https://github.com/golang/mock) - Mocking framework for the Go programming language.
    *   [govcr (⭐136)](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
    *   [hoverfly (⭐1.9k)](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
    *   [httpmock (⭐1.5k)](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources.
    *   [minimock (⭐467)](https://github.com/gojuno/minimock) - Mock generator for Go interfaces.
    *   [mockery (⭐4k)](https://github.com/vektra/mockery) - Tool to generate Go interfaces.
    *   [mockhttp (⭐22)](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter.
    *   [mockit (⭐10)](https://github.com/pasdam/mockit) - Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java.
    *   [mooncake (⭐15)](https://github.com/GuilhermeCaruso/mooncake) - A simple way to generate mocks for multiple purposes
    *   [timex (⭐65)](https://github.com/cabify/timex) - A test-friendly replacement for the native `time` package.

*   Fuzzing and delta-debugging/reducing/shrinking.
    *   [go-fuzz (⭐4.5k)](https://github.com/dvyukov/go-fuzz) - Randomized testing system.
    *   [gofuzz (⭐1.3k)](https://github.com/google/gofuzz) - Library for populating go objects with random values.
    *   [Tavor (⭐239)](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework.

*   Selenium and browser control tools.
    *   [cdp (⭐647)](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
    *   [chromedp (⭐8.3k)](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
    *   [ggr (⭐288)](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs.
    *   [playwright-go (⭐1k)](https://github.com/mxschmitt/playwright-go) - browser automation library to control Chromium, Firefox and WebKit with a single API.
    *   [rod (⭐3.1k)](https://github.com/go-rod/rod) - A Devtools driver to make web automation and scraping easy.
    *   [selenoid (⭐2.2k)](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers.

*   Fail injection
    *   [failpoint (⭐750)](https://github.com/pingcap/failpoint) - An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang.

**[⬆ back to top](#contents)**

## Text Processing

*Libraries for parsing and manipulating texts.*

See also [Natural Language Processing](#natural-language-processing) and [Text Analysis](#text-analysis).

### Formatters

*   [address (⭐56)](https://github.com/bojanz/address) - Handles address representation, validation and formatting.
*   [align (⭐78)](https://github.com/Guitarbum722/align) - A general purpose application that aligns text.
*   [bytes (⭐471)](https://github.com/labstack/gommon/tree/master/bytes) - Formats and parses numeric byte values (10K, 2M, 3G, etc.).
*   [go-fixedwidth (⭐67)](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection).
*   [go-humanize (⭐3.4k)](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format.
*   [gotabulate (⭐293)](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go.
*   [textwrap (⭐4)](https://github.com/isbm/textwrap) - Wraps text at end of lines. Implementation of `textwrap` module from Python.

### Markup Languages

*   [bafi (⭐67)](https://github.com/mmalcek/bafi) - Universal JSON, BSON, YAML, XML translator to ANY format using templates.
*   [bbConvert (⭐7)](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
*   [blackfriday (⭐5k)](https://github.com/russross/blackfriday) - Markdown processor in Go.
*   [github\_flavored\_markdown](https://godoc.org/github.com/shurcooL/github_flavored_markdown) - GitHub Flavored Markdown renderer (using blackfriday) with fenced code block highlighting, clickable header anchor links.
*   [go-output-format (⭐8)](https://github.com/drewstinnett/go-output-format) - Output go structures into multiple formats (YAML/JSON/etc) in your command line app.
*   [go-toml (⭐1.3k)](https://github.com/pelletier/go-toml) - Go library for the TOML format with query support and handy cli tools.
*   [goldmark (⭐2.4k)](https://github.com/yuin/goldmark) - A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured.
*   [goq (⭐220)](https://github.com/andrewstuart/goq) - Declarative unmarshaling of HTML using struct tags with jQuery syntax (uses GoQuery).
*   [html-to-markdown (⭐416)](https://github.com/JohannesKaufmann/html-to-markdown) - Convert HTML to Markdown. Even works with entire websites and can be extended through rules.
*   [htmlquery (⭐533)](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.
*   [mxj (⭐529)](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map\[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
*   [toml (⭐4k)](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection).

### Parsers/Encoders/Decoders

*   [allot (⭐56)](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots.
*   [codetree (⭐22)](https://github.com/aerogo/codetree) - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure.
*   [commonregex (⭐839)](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go.
*   [did (⭐70)](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go.
*   [doi (⭐7)](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go.
*   [editorconfig-core-go (⭐109)](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go.
*   [encdec (⭐8)](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decoders.
*   [go-fasttld (⭐10)](https://github.com/elliotwutingfeng/go-fasttld) - High performance top level domains (TLD) extraction module.
*   [go-nmea (⭐185)](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language.
*   [go-vcard (⭐82)](https://github.com/emersion/go-vcard) - Parse and format vCard.
*   [gofeed (⭐2k)](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go.
*   [gographviz (⭐501)](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language.
*   [gonameparts (⭐38)](https://github.com/polera/gonameparts) - Parses human names into individual name parts.
*   [ltsv (⭐8)](https://github.com/Wing924/ltsv) - High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go.
*   [normalize (⭐33)](https://github.com/avito-tech/normalize) - Sanitize, normalize and compare fuzzy text.
*   [omniparser (⭐516)](https://github.com/jf-tech/omniparser) - A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema.
*   [parseargs-go (⭐10)](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes.
*   [parth (⭐42)](https://github.com/codemodus/parth) - URL path segmentation parsing.
*   [sdp (⭐114)](https://github.com/gortc/sdp) - SDP: Session Description Protocol \[[RFC 4566](https://tools.ietf.org/html/rfc4566)].
*   [sh (⭐5.2k)](https://github.com/mvdan/sh) - Shell parser and formatter.
*   [tokenizer (⭐22)](https://github.com/bzick/tokenizer) - Parse any string, slice or infinite buffer to any tokens.
*   [when (⭐1.2k)](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules.
*   [xj2go (⭐29)](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct.

### Regular Expressions

*   [genex (⭐68)](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings.
*   [go-wildcard (⭐17)](https://github.com/IGLOU-EU/go-wildcard) - Simple and lightweight wildcard pattern matching.
*   [goregen (⭐79)](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions.
*   [regroup (⭐126)](https://github.com/oriser/regroup) - Match regex expression named groups into go struct using struct tags and automatic parsing.
*   [rex (⭐121)](https://github.com/hedhyw/rex) - Regular expressions builder.

### Sanitation

*   [bluemonday (⭐2.5k)](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer.
*   [gofuckyourself (⭐52)](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go.

### Scrapers

*   [colly (⭐18k)](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers.
*   [dataflowkit (⭐550)](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data.
*   [go-recipe (⭐11)](https://github.com/kkyr/go-recipe) - A package for scraping recipes from websites.
*   [GoQuery (⭐12k)](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
*   [gospider (⭐180)](https://github.com/zhshch2002/gospider) - A simple golang spider/scraping framework,build a spider in 3 lines. migrated from [goribot (⭐210)](https://github.com/zhshch2002/goribot)
*   [pagser (⭐70)](https://github.com/foolin/pagser) - Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler.
*   [Tagify (⭐24)](https://github.com/zoomio/tagify) - Produces a set of tags from given source.
*   [xurls (⭐972)](https://github.com/mvdan/xurls) - Extract urls from text.

### RSS

*   [podcast (⭐113)](https://github.com/eduncan911/podcast) - iTunes Compliant and RSS 2.0 Podcast Generator in Golang
*   [syndfeed (⭐9)](https://github.com/zhengchun/syndfeed) - A syndication feed for Atom 1.0 and RSS 2.0.

### Utility/Miscellaneous

*   [go-runewidth (⭐496)](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string.
*   [go-zero-width (⭐106)](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go.
*   [kace (⭐19)](https://github.com/codemodus/kace) - Common case conversions covering common initialisms.
*   [petrovich (⭐41)](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case.
*   [radix (⭐180)](https://github.com/yourbasic/radix) - Fast string sorting algorithm.
*   [TySug (⭐14)](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts.

**[⬆ back to top](#contents)**

## Third-party APIs

*Libraries for accessing third party APIs.*

*   [airtable (⭐45)](https://github.com/mehanizm/airtable) - Go client library for the [Airtable API](https://airtable.com/api).
*   [amazon-product-advertising-api (⭐54)](https://github.com/ngs/go-amazon-product-advertising-api) - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
*   [anaconda (⭐1.1k)](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API.
*   [appstore-sdk-go (⭐3)](https://github.com/Kachit/appstore-sdk-go) - Unofficial Golang SDK for AppStore Connect API.
*   [aws-sdk-go (⭐8k)](https://github.com/aws/aws-sdk-go) - The official AWS SDK for the Go programming language.
*   [bqwriter (⭐12)](https://github.com/OTA-Insight/bqwriter) - High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout.
*   [brewerydb (⭐19)](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API.
*   [cachet (⭐91)](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
*   [circleci (⭐65)](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API.
*   [clarifai (⭐57)](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API.
*   [codeship-go (⭐19)](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2.
*   [coinpaprika-go (⭐16)](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API.
*   [device-check-go (⭐16)](https://github.com/rinchsan/device-check-go) - Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1.
*   [discordgo (⭐3.5k)](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API.
*   [dusupay-sdk-go (⭐2)](https://github.com/Kachit/dusupay-sdk-go) - Unofficial Dusupay payment gateway API Client for Go
*   [ethrpc (⭐245)](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API.
*   [facebook (⭐1.1k)](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API.
*   [fasapay-sdk-go (⭐2)](https://github.com/Kachit/fasapay-sdk-go) - Unofficial Fasapay payment gateway XML API Client for Golang.
*   [fcm (⭐48)](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging.
*   [gads (⭐50)](https://github.com/emiddleton/gads) - Google Adwords Unofficial API.
*   [gami (⭐31)](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface.
*   [gcm (⭐31)](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging.
*   [geo-golang (⭐442)](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://open.mapquestapi.com/geocoding/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
*   [github (⭐8.9k)](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3.
*   [githubql (⭐938)](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4.
*   [go-atlassian (⭐56)](https://github.com/ctreminiom/go-atlassian) - Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud)
*   [go-aws-news (⭐15)](https://github.com/circa10a/go-aws-news) - Go application and library to fetch what's new from AWS.
*   [go-chronos (⭐7)](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
*   [go-hacknews (⭐16)](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API.
*   [go-here (⭐12)](https://github.com/abdullahselek/go-here) - Go client library around the HERE location based APIs.
*   [go-hibp (⭐5)](https://github.com/wneessen/go-hibp) - Simple Go binding to the "Have I Been Pwned" APIs.
*   [go-imgur (⭐24)](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com)
*   [go-jira (⭐1.2k)](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
*   [go-lark (⭐118)](https://github.com/go-lark/lark) - An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform.
*   [go-marathon (⭐197)](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS.
*   [go-myanimelist (⭐33)](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2).
*   [go-openproject (⭐12)](https://github.com/manuelbcd/go-openproject) - Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API.
*   [go-postman-collection (⭐58)](https://github.com/rbretecher/go-postman-collection) - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia).
*   [go-restcountries (⭐3)](https://github.com/chriscross0/go-restcountries) - Go library for the [REST Countries API](https://countrylayer.com/).
*   [go-sophos (⭐11)](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
*   [go-sptrans (⭐7)](https://github.com/sergioaugrod/go-sptrans) - Go client library for the SPTrans Olho Vivo API.
*   [go-swagger-ui (⭐7)](https://github.com/esurdam/go-swagger-ui) - Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json.
*   [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
*   [go-trending (⭐122)](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github.
*   [go-twitch](https://github.com/knspriggs/go-twitch) - Go client for interacting with the Twitch v3 API.
*   [go-twitter (⭐1.6k)](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs.
*   [go-unsplash (⭐68)](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API.
*   [go-xkcd (⭐48)](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API.
*   [go-yapla](https://git.iglou.eu/Production/go-yapla) - Go client library for the Yapla v2.0 API.
*   [goagi (⭐5)](https://github.com/staskobzar/goagi) - Go library to build Asterisk PBX agi/fastagi applications.
*   [goami2 (⭐8)](https://github.com/staskobzar/goami2) - AMI v2 library for Asterisk PBX.
*   [GoFreeDB (⭐17)](https://github.com/FreeLeh/GoFreeDB) - Golang library providing common and simple database abstractions on top of Google Sheets.
*   [gogtrends (⭐71)](https://github.com/groovili/gogtrends) - Google Trends Unofficial API.
*   [golang-tmdb (⭐61)](https://github.com/cyruzin/golang-tmdb) - Golang wrapper for The Movie Database API v3.
*   [golyrics (⭐39)](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
*   [gomalshare (⭐10)](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](https://www.malshare.com/)
*   [GoMusicBrainz (⭐47)](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library.
*   [google (⭐3.2k)](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go.
*   [google-analytics (⭐13)](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting.
*   [google-cloud (⭐3.1k)](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library.
*   [google-email-audit-api (⭐8)](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
*   [google-play-scraper (⭐41)](https://github.com/n0madic/google-play-scraper) - Get data from Google Play Store.
*   [gopaapi5 (⭐13)](https://github.com/utekaravinash/gopaapi5) - Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/).
*   [gosip (⭐85)](https://github.com/koltyakov/gosip) - Go client library SharePoint API.
*   [gostorm (⭐129)](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
*   [hipchat (⭐105)](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API.
*   [hipchat (xmpp) (⭐110)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP.
*   [igdb (⭐76)](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/).
*   [jokeapi-go (⭐19)](https://github.com/icelain/jokeapi) - Go client for [JokeAPI](https://sv443.net/jokeapi/v2/).
*   [lark (⭐250)](https://github.com/chyroc/lark) - [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback.
*   [lastpass-go (⭐31)](https://github.com/ansd/lastpass-go) - Go client library for the [LastPass](https://www.lastpass.com/) API.
*   [libgoffi (⭐9)](https://github.com/clevabit/libgoffi) - Library adapter toolbox for native [libffi](https://sourceware.org/libffi/) integration
*   [Medium (⭐133)](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API.
*   [megos (⭐55)](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster.
*   [minio-go (⭐1.8k)](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage.
*   [mixpanel (⭐49)](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
*   [newsapi-go (⭐6)](https://github.com/jellydator/newsapi-go) - Go client for [NewsAPI](https://newsapi.org/).
*   [patreon-go (⭐33)](https://github.com/mxpv/patreon-go) - Go library for Patreon API.
*   [paypal (⭐539)](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API.
*   [playlyfe (⭐2)](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK.
*   [pushover (⭐128)](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API.
*   [rawg-sdk-go (⭐8)](https://github.com/dimuska139/rawg-sdk-go) - Go library for the [RAWG Video Games Database](https://rawg.io/) API
*   [rrdaclient (⭐9)](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
*   [shopify (⭐24)](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API.
*   [simples3 (⭐95)](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
*   [slack (⭐4.1k)](https://github.com/slack-go/slack) - Slack API in Go.
*   [smite (⭐11)](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API.
*   [spotify (⭐45)](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API.
*   [steam (⭐29)](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers.
*   [stripe (⭐1.7k)](https://github.com/stripe/stripe-go) - Go client for the Stripe API.
*   [swag (⭐21)](https://github.com/zc2638/swag) - No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more.
*   [textbelt (⭐18)](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API.
*   [translate (⭐32)](https://github.com/poorny/translate) - Go online translation package.
*   [Trello (⭐205)](https://github.com/adlio/trello) - Go wrapper for the Trello API.
*   [TripAdvisor (⭐2)](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API.
*   [tumblr (⭐8)](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API.
*   [twitter-scraper (⭐272)](https://github.com/n0madic/twitter-scraper) - Scrape the Twitter Frontend API without authentication and limits.
*   [uptimerobot (⭐53)](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API.
*   [vl-go (⭐2)](https://github.com/verifid/vl-go) - Go client library around the VerifID identity verification layer API.
*   [webhooks (⭐787)](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket.
*   [wit-go (⭐132)](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API.
*   [ynab (⭐55)](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API.
*   [zooz (⭐7)](https://github.com/gojuno/go-zooz) - Go client for the Zooz API.

**[⬆ back to top](#contents)**

## Utilities

*General utilities and tools to make your life easier.*

*   [apm (⭐161)](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API.
*   [backscanner (⭐40)](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
*   [beyond (⭐49)](https://github.com/wesovilabs/beyond) - The Go tool that will drive you to the AOP world!
*   [blank (⭐9)](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings.
*   [bleep (⭐9)](https://github.com/sinhashubham95/bleep) - Perform any number of actions on any set of OS signals in Go.
*   [boilr (⭐1.5k)](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates.
*   [changie (⭐396)](https://github.com/miniscruff/changie) - Automated changelog tool for preparing releases with lots of customization options.
*   [chyle (⭐146)](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities.
*   [circuit (⭐672)](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
*   [circuitbreaker (⭐1k)](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go.
*   [clipboard (⭐294)](https://github.com/golang-design/clipboard) - 📋 cross-platform clipboard package in Go.
*   [clockwork (⭐421)](https://github.com/jonboulle/clockwork) - A simple fake clock for golang.
*   [cmd (⭐115)](https://github.com/SimonBaeumer/cmd) - Library for executing shell commands on osx, windows and linux.
*   [command (⭐14)](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher.
*   [copy (⭐28)](https://github.com/gotidy/copy) - Package for fast copying structs of different types.
*   [copy-pasta (⭐50)](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage.
*   [countries (⭐194)](https://github.com/biter777/countries) - Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standards.
*   [countries (⭐68)](https://github.com/pioz/countries) - All you need when you are working with countries in Go.
*   [create-go-app (⭐1.5k)](https://github.com/create-go-app/cli) - A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command.
*   [cryptgo (⭐123)](https://github.com/Gituser143/cryptgo) - Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time!
*   [ctop (⭐14k)](https://github.com/bcicen/ctop) - [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics.
*   [ctxutil (⭐20)](https://github.com/posener/ctxutil) - A collection of utility functions for contexts.
*   [cvt (⭐29)](https://github.com/shockerli/cvt) - Easy and safe convert any value to another type.
*   [dbt (⭐50)](https://github.com/nikogura/dbt) - A framework for running self-updating signed binaries from a central, trusted repository.
*   [Death (⭐186)](https://github.com/vrecan/death) - Managing go application shutdown with signals.
*   [Deepcopier (⭐396)](https://github.com/ulule/deepcopier) - Simple struct copying for Go.
*   [delve (⭐535)](https://github.com/derekparker/delve) - Go debugger.
*   [dlog (⭐17)](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls.
*   [EaseProbe (⭐1.3k)](https://github.com/megaease/easeprobe) - A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification.
*   [equalizer (⭐39)](https://github.com/reugn/equalizer) - Quota manager and rate limiter collection for Go.
*   [ergo (⭐539)](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy.
*   [evaluator (⭐35)](https://github.com/nullne/evaluator) - Evaluate an expression dynamically based on s-expression. It's simple and easy to extend.
*   [filetype (⭐1.6k)](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature.
*   [filler (⭐17)](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag.
*   [filter (⭐110)](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data.
*   [fzf (⭐48k)](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go.
*   [generate (⭐28)](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex.
*   [ghokin (⭐28)](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
*   [git-time-metric (⭐915)](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git.
*   [gitbatch (⭐1.5k)](https://github.com/isacikgoz/gitbatch) - manage your git repositories in one place.
*   [go-actuator (⭐10)](https://github.com/sinhashubham95/go-actuator) - Production ready features for Go based web frameworks.
*   [go-astitodo (⭐60)](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code.
*   [go-bind-plugin (⭐182)](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
*   [go-bsdiff (⭐136)](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools.
*   [go-clip (⭐9)](https://github.com/prashantgupta24/go-clip) - A minimalistic clipboard manager for Mac.
*   [go-convert (⭐18)](https://github.com/Eun/go-convert) - Package go-convert enables you to convert a value into another type.
*   [go-countries (⭐10)](https://github.com/mikekonan/go-countries) - Lightweight lookup over ISO-3166 codes.
*   [go-dry (⭐479)](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go.
*   [go-funk (⭐4k)](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
*   [go-health (⭐92)](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services.
*   [go-httpheader (⭐43)](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields.
*   [go-lock (⭐82)](https://github.com/viney-shih/go-lock) - go-lock is a lock library implementing read-write mutex and read-write trylock without starvation.
*   [go-pkg (⭐7)](https://github.com/chenquan/go-pkg) - A go toolkit.
*   [go-problemdetails (⭐15)](https://github.com/mvmaasakkers/go-problemdetails) - Go package for working with Problem Details.
*   [go-rate (⭐372)](https://github.com/beefsack/go-rate) - Timed rate limiter for Go.
*   [go-safe](https://github.com/kenkyu392/go-safe) - Panic-safe sandbox.
*   [go-sitemap-generator (⭐187)](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go.
*   [go-trigger (⭐230)](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
*   [go-type (⭐15)](https://github.com/mikekonan/go-types) - Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types.
*   [goback (⭐47)](https://github.com/carlescere/goback) - Go simple exponential backoff package.
*   [goctx (⭐3)](https://github.com/zerosnake0/goctx) - Get your context value with high performance.
*   [godaemon (⭐490)](https://github.com/VividCortex/godaemon) - Utility to write daemons.
*   [godropbox (⭐4.1k)](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox.
*   [gohper (⭐255)](https://github.com/cosiner/gohper) - Various tools/modules help for development.
*   [golarm (⭐49)](https://github.com/msempere/golarm) - Fire alarms with system events.
*   [golog (⭐57)](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks.
*   [gopencils (⭐440)](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs.
*   [goplaceholder (⭐25)](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images.
*   [goreadability (⭐68)](https://github.com/philipjkim/goreadability) - Webpage summary extractor using Facebook Open Graph and arc90's readability.
*   [goreleaser (⭐11k)](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible.
*   [goreporter (⭐3k)](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report.
*   [goseaweedfs (⭐99)](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features.
*   [gostrutils (⭐38)](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions.
*   [gotenv (⭐240)](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go.
*   [goval (⭐93)](https://github.com/maja42/goval) - Evaluate arbitrary expressions in Go.
*   [gpath (⭐39)](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection.
*   [graterm (⭐21)](https://github.com/skovtunenko/graterm) - Provides primitives to perform ordered (sequential/concurrent) GRAceful TERMination (aka shutdown) in Go application.
*   [grofer (⭐227)](https://github.com/pesos/grofer) - A system and resource monitoring tool written in Golang!
*   [gubrak (⭐417)](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang.
*   [handy (⭐70)](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators.
*   [hostctl (⭐815)](https://github.com/guumaster/hostctl) - A CLI tool to manage /etc/hosts with easy commands.
*   [htcat (⭐549)](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility.
*   [hub (⭐22k)](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal.
*   [hystrix-go (⭐3.8k)](https://github.com/afex/hystrix-go) - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
*   [immortal (⭐755)](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor.
*   [intrinsic (⭐45)](https://github.com/mengzhuo/intrinsic) - Use x86 SIMD without writing any assembly code.
*   [jsend (⭐17)](https://github.com/clevergo/jsend) - JSend's implementation written in Go.
*   [jump (⭐1.5k)](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits.
*   [koazee (⭐508)](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
*   [lancet (⭐1.8k)](https://github.com/duke-git/lancet) - A comprehensive, efficient, and reusable util function library of go.
*   [lets-go (⭐5)](https://github.com/aplescia-chwy/lets-go) - Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities.
*   [limiters (⭐107)](https://github.com/mennanov/limiters) - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks.
*   [lo (⭐8.5k)](https://github.com/samber/lo) - A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...)
*   [loncha (⭐6)](https://github.com/kazu/loncha) - A high-performance slice Utilities.
*   [lrserver (⭐122)](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go.
*   [mani (⭐323)](https://github.com/alajmo/mani) - CLI tool to help you manage multiple repositories.
*   [mc (⭐2.3k)](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
*   [mergo (⭐2.2k)](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
*   [mimemagic (⭐83)](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility.
*   [mimesniffer (⭐25)](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go.
*   [mimetype (⭐871)](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers.
*   [minify (⭐3.1k)](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
*   [minquery (⭐60)](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
*   [moldova (⭐162)](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template.
*   [mole (⭐1.6k)](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels.
*   [mongo-go-pagination (⭐110)](https://github.com/gobeam/mongo-go-pagination) - Mongodb Pagination for official mongodb/mongo-go-driver package which supports  both normal queries and Aggregation pipelines.
*   [mssqlx (⭐102)](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
*   [multitick (⭐64)](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers.
*   [myhttp (⭐35)](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support.
*   [netbug (⭐71)](https://github.com/e-dard/netbug) - Easy remote profiling of your services.
*   [nfdump (⭐7)](https://github.com/chrispassas/nfdump) - Read nfdump netflow files.
*   [nostromo (⭐123)](https://github.com/pokanop/nostromo) - CLI for building powerful aliases.
*   [objwalker (⭐2)](https://github.com/rekby/objwalker) - Walk by go objects with reflection.
*   [okrun (⭐16)](https://github.com/xta/okrun) - go run error steamroller.
*   [olaf (⭐5)](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go.
*   [onecache (⭐130)](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
*   [panicparse (⭐3.3k)](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump.
*   [pattern-match (⭐192)](https://github.com/alexpantyukhin/go-pattern-match) - Pattern matching libray.
*   [peco (⭐7.2k)](https://github.com/peco/peco) - Simplistic interactive filtering tool.
*   [pgo (⭐73)](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community.
*   [pm (⭐78)](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API.
*   [pointer (⭐32)](https://github.com/xorcare/pointer) - Package pointer contains helper routines for simplifying the creation of optional fields of basic type.
*   [ptr (⭐19)](https://github.com/gotidy/ptr) - Package that provide functions for simplified creation of pointers from constants of basic types.
*   [rclient (⭐33)](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs.
*   [reflectutils (⭐4)](https://github.com/muir/reflectutils) - Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string.
*   [remote-touchpad (⭐341)](https://github.com/Unrud/remote-touchpad) - Control mouse and keyboard from a smartphone.
*   [repeat (⭐81)](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
*   [request (⭐420)](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™.
*   [rerun (⭐165)](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes.
*   [rest-go (⭐16)](https://github.com/edermanoel94/rest-go) - A package that provide many helpful methods for working with rest api.
*   [retry (⭐330)](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful.
*   [retry (⭐8)](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go.
*   [retry (⭐59)](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go.
*   [retry (⭐11)](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done.
*   [retry-go (⭐1.3k)](https://github.com/avast/retry-go) - Simple library for retry mechanism.
*   [retry-go (⭐45)](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang.
*   [robustly (⭐154)](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics.
*   [rospo (⭐185)](https://github.com/ferama/rospo) - Simple and reliable ssh tunnels with embedded ssh server in Golang.
*   [scan (⭐311)](https://github.com/blockloop/scan) - Scan golang `sql.Rows` directly to structs, slices, or primitive types.
*   [scan (⭐41)](https://github.com/wroge/scan) - Scan sql rows into any type powered by generics.
*   [scany (⭐769)](https://github.com/georgysavva/scany) - Library for scanning data from a database into Go structs and more.
*   [serve (⭐282)](https://github.com/syntaqx/serve) - A static http server anywhere you need.
*   [set (⭐42)](https://github.com/nofeaturesonlybugs/set) - Performant and flexible struct mapping and loose type conversion.
*   [shutdown (⭐42)](https://github.com/ztrue/shutdown) - App shutdown hooks for `os.Signal` handling.
*   [silk (⭐12)](https://github.com/chrispassas/silk) - Read silk netflow files.
*   [slice (⭐49)](https://github.com/psampaz/slice) - Type-safe functions for common Go slice operations.
*   [sliceconv (⭐8)](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types.
*   [slicer (⭐40)](https://github.com/leaanthony/slicer) - Makes working with slices easier.
*   [sorty (⭐110)](https://github.com/jfcg/sorty) - Fast Concurrent / Parallel Sorting.
*   [sqlx (⭐13k)](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package.
*   [sshman (⭐39)](https://github.com/shoobyban/sshman) - SSH Manager for authorized\_keys files on multiple remote servers.
*   [statiks (⭐10)](https://github.com/janiltonmaciel/statiks) - Fast, zero-configuration, static HTTP filer server.
*   [Storm (⭐1.9k)](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB.
*   [structs (⭐21)](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs.
*   [throttle (⭐30)](https://github.com/yudppp/throttle) - Throttle is an object that will perform exactly one action per duration.
*   [tik (⭐4)](https://github.com/andy2046/tik) - Simple and easy timing wheel package for Go.
*   [tome (⭐31)](https://github.com/cyruzin/tome) - Tome was designed to paginate simple RESTful APIs.
*   [toolbox (⭐184)](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
*   [ugo (⭐27)](https://github.com/alxrm/ugo) - ugo is slice toolbox with concise syntax for Go.
*   [UNIS (⭐70)](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go.
*   [usql (⭐7.6k)](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases.
*   [util (⭐262)](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
*   [wifiqr (⭐219)](https://github.com/reugn/wifiqr) - Wi-Fi QR Code Generator.
*   [wuzz (⭐10k)](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection.
*   [xferspdy (⭐94)](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang.

**[⬆ back to top](#contents)**

## UUID

*Libraries for working with UUIDs.*

*   [goid (⭐35)](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs.
*   [gouid (⭐18)](https://github.com/twharmon/gouid) - Generate cryptographically secure random string IDs with just one allocation.
*   [nanoid (⭐55)](https://github.com/aidarkhanov/nanoid) - A tiny and efficient Go unique string ID generator.
*   [sno (⭐72)](https://github.com/muyo/sno) - Compact, sortable and fast unique IDs with embedded metadata.
*   [ulid (⭐2.9k)](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).
*   [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.
*   [uuid (⭐15)](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
*   [uuid (⭐1.2k)](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.
*   [uuid (⭐4k)](https://github.com/google/uuid) - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
*   [wuid (⭐477)](https://github.com/edwingeng/wuid) - An extremely fast unique number generator, 10-135 times faster than UUID.
*   [xid (⭐3.1k)](https://github.com/rs/xid) - Xid is a globally unique id generator library, ready to be safely used directly in your server code.

**[⬆ back to top](#contents)**

## Validation

*Libraries for validation.*

*   [checkdigit (⭐95)](https://github.com/osamingo/checkdigit) - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.).
*   [gody (⭐63)](https://github.com/guiferpa/gody) - :balloon: A lightweight struct validator for Go.
*   [govalid (⭐31)](https://github.com/twharmon/govalid) - Fast, tag-based validation for structs.
*   [govalidator (⭐5.5k)](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs.
*   [govalidator (⭐1.2k)](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
*   [jio (⭐71)](https://github.com/faceair/jio) - jio is a json schema validator similar to [joi (⭐19k)](https://github.com/hapijs/joi).
*   [ozzo-validation (⭐3k)](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
*   [terraform-validator (⭐79)](https://github.com/thazelart/terraform-validator) - A norms and conventions validator for Terraform.
*   [validate (⭐799)](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.
*   [validate (⭐78)](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications.
*   [validator (⭐12k)](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.
*   [Validator (⭐4)](https://github.com/go-the-way/validator) - A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex.
*   [valix (⭐4)](https://github.com/marrow16/valix) Go package for validating requests

**[⬆ back to top](#contents)**

## Version Control

*Libraries for version control.*

*   [cli](https://gitlab.com/gitlab-org/cli) - An open-source GitLab command line tool bringing GitLab's cool features to your command line.
*   [froggit-go (⭐21)](https://github.com/jfrog/froggit-go) - Froggit-Go is a Go library, allowing to perform actions on VCS providers.
*   [gh (⭐79)](https://github.com/rjeczalik/gh) - Scriptable server and net/http middleware for GitHub Webhooks.
*   [git2go (⭐1.8k)](https://github.com/libgit2/git2go) - Go bindings for libgit2.
*   [githooks (⭐52)](https://github.com/gabyx/githooks) - Per-repo and shared Git hooks with version control and auto update.
*   [go-git (⭐4k)](https://github.com/go-git/go-git) - highly extensible Git implementation in pure Go.
*   [go-vcs (⭐74)](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go.
*   [hercules (⭐1.8k)](https://github.com/src-d/hercules) - gaining advanced insights from Git repository history.
*   [hgo (⭐14)](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

**[⬆ back to top](#contents)**

## Video

*Libraries for manipulating video.*

*   [gmf (⭐808)](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries.
*   [go-astisub (⭐417)](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
*   [go-astits (⭐444)](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO.
*   [go-m3u8 (⭐8)](https://github.com/etherlabsio/go-m3u8) - Parser and generator library for Apple m3u8 playlists. Actively maintained version of quangngotan95/go-m3u8 with improvements and latest HLS playlist parsing compatibility.
*   [go-mpd (⭐14)](https://github.com/unki2aut/go-mpd) - Parser and generator library for MPEG-DASH manifest files.
*   [goav (⭐1.9k)](https://github.com/giorgisio/goav) - Comprehensive Go bindings for FFmpeg.
*   [gortsplib (⭐319)](https://github.com/aler9/gortsplib) - Pure Go RTSP server and client library.
*   [gst (⭐166)](https://github.com/ziutek/gst) - Go bindings for GStreamer.
*   [libgosubs (⭐20)](https://github.com/wargarblgarbl/libgosubs) - Subtitle format support for go. Supports .srt, .ttml, and .ass.
*   [libvlc-go (⭐322)](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).
*   [m3u8 (⭐975)](https://github.com/grafov/m3u8) - Parser and generator library of M3U8 playlists for Apple HLS.
*   [v4l (⭐70)](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go.

**[⬆ back to top](#contents)**

## Web Frameworks

*Full stack web frameworks.*

*   [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
*   [Aero (⭐503)](https://github.com/aerogo/aero) - High-performance web framework for Go, reaches top scores in Lighthouse.
*   [Air (⭐419)](https://github.com/aofei/air) - An ideally refined web framework for Go.
*   [anoweb (⭐5)](https://github.com/go-the-way/anoweb) - The lightweight and powerful web framework using the new way for Go.Another go the way.
*   [appy (⭐128)](https://github.com/appist/appy) - An opinionated productive web framework that helps scaling business easier.
*   [Atreugo (⭐956)](https://github.com/savsgio/atreugo) - High performance and extensible micro web framework with zero memory allocations in hot paths.
*   [Banjo (⭐20)](https://github.com/nsheremet/banjo) - Very simple and fast web framework for Go.
*   [Beego (⭐29k)](https://github.com/beego/beego) - beego is an open-source, high-performance web framework for the Go programming language.
*   [Buffalo](https://gobuffalo.io) - Bringing the productivity of Rails to Go!
*   [Confetti Framework](https://confetti-framework.github.io/docs/) - Confetti is a Go web application framework with an expressive, elegant syntax. Confetti combines the elegance of Laravel and the simplicity of Go.
*   [Echo (⭐24k)](https://github.com/labstack/echo) - High performance, minimalist Go web framework.
*   [Fiber (⭐23k)](https://github.com/gofiber/fiber) - An Express.js inspired web framework build on Fasthttp.
*   [Fireball (⭐59)](https://github.com/zpatrick/fireball) - More "natural" feeling web framework.
*   [Flamingo (⭐326)](https://github.com/i-love-flamingo/flamingo) - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc.
*   [Flamingo Commerce (⭐372)](https://github.com/i-love-flamingo/flamingo-commerce) - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications.
*   [Gearbox (⭐687)](https://github.com/abahmed/gearbox) - A web framework written in Go with a focus on high performance and memory optimization.
*   [Gin (⭐64k)](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
*   [Ginrpc (⭐239)](https://github.com/xxjwxc/ginrpc) - Gin parameter automatic binding tool,gin rpc tools.
*   [Gizmo (⭐3.7k)](https://github.com/NYTimes/gizmo) - Microservice toolkit used by the New York Times.
*   [go-json-rest (⭐3.5k)](https://github.com/ant0ine/go-json-rest) - Quick and easy way to setup a RESTful JSON API.
*   [go-rest (⭐125)](https://github.com/ungerik/go-rest) - Small and evil REST framework for Go.
*   [Goa (⭐4.9k)](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go.
*   [goa (⭐47)](https://github.com/goa-go/goa) - goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware.
*   [golamb (⭐3)](https://github.com/twharmon/golamb) - Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway.
*   [Golax (⭐76)](https://github.com/fulldump/golax) - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more.
*   [Golf (⭐259)](https://github.com/dinever/golf) - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
*   [Gondola (⭐311)](https://github.com/rainycape/gondola) - The web framework for writing faster sites, faster.
*   [gongular (⭐451)](https://github.com/mustafaakin/gongular) - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
*   [GoTuna (⭐42)](https://github.com/gotuna/gotuna) - Minimalistic web framework for Go with mux router, middlewares, sessions, templates, embedded views and static files.
*   [goweb (⭐33)](https://github.com/twharmon/goweb) - Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS.
*   [Goyave (⭐1.2k)](https://github.com/go-goyave/goyave) - Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities.
*   [Hertz (⭐2.5k)](https://github.com/cloudwego/hertz) - A high-performance and strong-extensibility Go HTTP framework that helps developers build microservices.
*   [hiboot (⭐180)](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support.
*   [Huma (⭐144)](https://github.com/danielgtaylor/huma/) - Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI.
*   [Macaron (⭐3.3k)](https://github.com/go-macaron/macaron) - Macaron is a high productive and modular design web framework in Go.
*   [mango (⭐370)](https://github.com/paulbellamy/mango) - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
*   [Microservice (⭐106)](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang.
*   [neo (⭐418)](https://github.com/ivpusic/neo) - Neo is minimal and fast Go Web Framework with extremely simple API.
*   [patron (⭐99)](https://github.com/beatlabs/patron) - Patron is a microservice framework following best cloud practices with a focus on productivity.
*   [Resoursea (⭐33)](https://github.com/resoursea/api) - REST framework for quickly writing resource based services.
*   [REST Layer](https://rest-layer.io) - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
*   [Revel (⭐13k)](https://github.com/revel/revel) - High-productivity web framework for the Go language.
*   [rex (⭐33)](https://github.com/goanywhere/rex) - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
*   [rk-boot (⭐324)](https://github.com/rookie-ninja/rk-boot) - A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily.
*   [rux (⭐83)](https://github.com/gookit/rux) - Simple and fast web framework for build golang HTTP applications.
*   [tango (⭐834)](https://github.com/lunny/tango) - Micro & pluggable web framework for Go.
*   [tigertonic (⭐1k)](https://github.com/rcrowley/go-tigertonic) - Go framework for building JSON web services inspired by Dropwizard.
*   [uAdmin (⭐211)](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django.
*   [utron (⭐2.2k)](https://github.com/gernest/utron) - Lightweight MVC framework for Go(Golang).
*   [vox (⭐79)](https://github.com/aisk/vox) - A golang web framework for humans, inspired by Koa heavily.
*   [WebGo (⭐259)](https://github.com/bnkamalesh/webgo) - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc).
*   [YARF (⭐66)](https://github.com/yarf-framework/yarf) - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.

**[⬆ back to top](#contents)**

### Middlewares

#### Actual middlewares

*   [client-timing (⭐21)](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header.
*   [CORS (⭐2.2k)](https://github.com/rs/cors) - Easily add CORS capabilities to your API.
*   [echo-middleware (⭐12)](https://github.com/faabiosr/echo-middleware) - Middleware for Echo framework with logging and metrics.
*   [formjson (⭐38)](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST.
*   [go-fault (⭐470)](https://github.com/github/go-fault) - Fault injection middleware for Go.
*   [go-server-timing (⭐842)](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header.
*   [Limiter (⭐1.7k)](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go.
*   [ln-paywall (⭐131)](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin).
*   [mid (⭐5)](https://github.com/bobg/mid) - Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more.
*   [rk-gin (⭐38)](https://github.com/rookie-ninja/rk-gin) - Middleware for Gin framework with logging, metrics, auth, tracing etc.
*   [rk-grpc (⭐54)](https://github.com/rookie-ninja/rk-grpc) - Middleware for gRPC with logging, metrics, auth, tracing etc.
*   [Tollbooth (⭐2.3k)](https://github.com/didip/tollbooth) - Rate limit HTTP request handler.
*   [XFF (⭐94)](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

*   [alice (⭐2.7k)](https://github.com/justinas/alice) - Painless middleware chaining for Go.
*   [catena (⭐9)](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain").
*   [chain (⭐65)](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware").
*   [go-wrap](https://github.com/go-on/wrap) - Small middlewares package for net/http.
*   [gores (⭐101)](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
*   [interpose (⭐296)](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang.
*   [mediary (⭐81)](https://github.com/HereMobilityDevelopers/mediary) - add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses.
*   [muxchain (⭐209)](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http.
*   [negroni (⭐7.3k)](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang.
*   [render (⭐1.7k)](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses.
*   [renderer (⭐247)](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
*   [rye (⭐98)](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
*   [stats (⭐586)](https://github.com/thoas/stats) - Go middleware that stores various information about your web application.

**[⬆ back to top](#contents)**

### Routers

*   [alien (⭐123)](https://github.com/gernest/alien) - Lightweight and fast http router from outer space.
*   [bellt (⭐55)](https://github.com/GuilhermeCaruso/bellt) - A simple Go HTTP router.
*   [Bone (⭐1.3k)](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer.
*   [Bxog (⭐105)](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
*   [chi (⭐13k)](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context.
*   [fasthttprouter (⭐871)](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
*   [FastRouter (⭐22)](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go.
*   [goblin (⭐43)](https://github.com/bmf-san/goblin) - A golang http router based on trie tree.
*   [gocraft/web (⭐1.5k)](https://github.com/gocraft/web) - Mux and middleware package in Go.
*   [Goji (⭐913)](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
*   [GoLobby/Router (⭐20)](https://github.com/golobby/router) - GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language.
*   [goroute (⭐8)](https://github.com/goroute/route) - Simple yet powerful HTTP request multiplexer.
*   [GoRouter (⭐137)](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
*   [gowww/router (⭐165)](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
*   [httprouter (⭐15k)](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework.
*   [httptreemux (⭐563)](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
*   [lars (⭐390)](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
*   [mux (⭐18k)](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang.
*   [nchi (⭐8)](https://github.com/muir/nchi) - chi-like router built on httprouter with dependency injection based middleware wrappers
*   [ngamux (⭐53)](https://github.com/ngamux/ngamux) - Simple HTTP router for Go.
*   [ozzo-routing (⭐442)](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
*   [pure (⭐131)](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
*   [Siesta (⭐353)](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers.
*   [vestigo (⭐267)](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications.
*   [violetear (⭐105)](https://github.com/nbari/violetear) - Go HTTP router.
*   [xmux (⭐95)](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support.
*   [xujiajun/gorouter (⭐532)](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go.

**[⬆ back to top](#contents)**

## WebAssembly

*   [dom (⭐466)](https://github.com/dennwc/dom) - DOM library.
*   [go-canvas (⭐179)](https://github.com/markfarnan/go-canvas) - Library to use HTML5 Canvas, with all drawing within go code.
*   [tinygo (⭐12k)](https://github.com/tinygo-org/tinygo) - Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM.
*   [vert (⭐78)](https://github.com/norunners/vert) - Interop between Go and JS values.
*   [wasmbrowsertest (⭐131)](https://github.com/agnivade/wasmbrowsertest) - Run Go WASM tests in your browser.
*   [webapi (⭐127)](https://github.com/gowebapi/webapi) - Bindings for DOM and HTML generated from WebIDL.

**[⬆ back to top](#contents)**

## Windows

*   [d3d9 (⭐134)](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9.
*   [go-ole (⭐919)](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang.
*   [gosddl (⭐9)](https://github.com/MonaxGT/gosddl) - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL.

**[⬆ back to top](#contents)**

## XML

*Libraries and tools for manipulating XML.*

*   [XML-Comp (⭐19)](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags.
*   [xml2map (⭐43)](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang.
*   [xmlwriter (⭐22)](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module.
*   [xpath (⭐522)](https://github.com/antchfx/xpath) - XPath package for Go.
*   [xquery (⭐156)](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression.
*   [zek (⭐607)](https://github.com/miku/zek) - Generate a Go struct from XML.

## Zero Trust

*Libraries and tools to implement Zero Trust architectures.*

*   [Cosign (⭐2.7k)](https://github.com/sigstore/cosign) - Container Signing, Verification and Storage in an OCI registry.
*   [in-toto (⭐67)](https://github.com/in-toto/in-toto-golang) - Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation.
*   [Spiffe-Vault (⭐46)](https://github.com/philips-labs/spiffe-vault) - Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication.
*   [Spire (⭐1.3k)](https://github.com/spiffe/spire) - SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms.

## Code Analysis

*Source code analysis tools, also known as Static Application Security Testing (SAST) Tools.*

*   [apicompat (⭐176)](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes.
*   [asty (⭐32)](https://github.com/asty-org/asty) - Converts golang AST to JSON and JSON to AST.
*   [ChainJacking (⭐36)](https://github.com/Checkmarx/chainjacking) - Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack.
*   [dupl (⭐299)](https://github.com/mibk/dupl) - Tool for code clone detection.
*   [errcheck (⭐1.9k)](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs.
*   [gcvis (⭐1.1k)](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time.
*   [go-checkstyle (⭐122)](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments.
*   [go-cleanarch (⭐630)](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
*   [go-critic (⭐1.4k)](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters.
*   [go-mod-outdated (⭐601)](https://github.com/psampaz/go-mod-outdated) - An easy way to find outdated dependencies of your Go projects.
*   [go-outdated (⭐44)](https://github.com/firstrow/go-outdated) - Console application that displays outdated packages.
*   [goast-viewer (⭐662)](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer.
*   [GoCover.io](https://gocover.io/) - GoCover.io offers the code coverage of any golang package as a service.
*   [goimports](https://godoc.org/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
*   [golang-ifood-sdk (⭐10)](https://github.com/arxdsilva/golang-ifood-sdk) - iFood API SDK.
*   [golines (⭐491)](https://github.com/segmentio/golines) - Formatter that automatically shortens long lines in Go code.
*   [GoLint (⭐4k)](https://github.com/golang/lint) - Golint is a linter for Go source code.
*   [GoPlantUML (⭐1.2k)](https://github.com/jfeliu007/goplantuml) - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them.
*   [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
*   [gosimple (⭐5k)](https://github.com/dominikh/go-tools/tree/master/cmd/gosimple) - gosimple is a linter for Go source code that specialises on simplifying code.
*   [gostatus (⭐243)](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages.
*   [lint (⭐67)](https://github.com/surullabs/lint) - Run linters as part of go test.
*   [php-parser (⭐895)](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go.
*   [staticcheck (⭐5k)](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
*   [tarp (⭐15)](https://github.com/verygoodsoftwarenotvirus/tarp) - tarp finds functions and methods without direct unit tests in Go source code.
*   [tickgit (⭐288)](https://github.com/augmentable-dev/tickgit) - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author.
*   [todocheck (⭐392)](https://github.com/preslavmihaylov/todocheck) - Static code analyser which links TODO comments in code with issues in your issue tracker.
*   [unconvert (⭐342)](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source.
*   [unused (⭐5k)](https://github.com/dominikh/go-tools/tree/master/cmd/unused) - unused checks Go code for unused constants, variables, functions and types.
*   [usestdlibvars (⭐30)](https://github.com/sashamelentyev/usestdlibvars) - A linter that detect the possibility to use variables/constants from the Go standard library.
*   [validate (⭐60)](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags.

**[⬆ back to top](#contents)**

## Editor Plugins

*Plugin for text editors and IDEs.*

*   [coc-go language server extension for Vim/Neovim (⭐502)](https://github.com/josa42/coc-go) - This plugin adds [gopls (⭐6.5k)](https://github.com/golang/tools/blob/master/gopls/README.md) features to Vim/Neovim.
*   [Go Doc (⭐5)](https://github.com/msyrus/vscode-go-doc) - A Visual Studio Code extension for showing definition in output and generating go doc.
*   [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
*   [go-language-server (⭐32)](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
*   [go-mode (⭐1.3k)](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
*   [go-plus (⭐1.5k)](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
*   [gocode (⭐5k)](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language.
*   [goimports-reviser (⭐221)](https://github.com/incu6us/goimports-reviser) - Formatting tool for imports.
*   [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
*   [GoSublime (⭐3.4k)](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
*   [gounit-vim (⭐24)](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature.
*   [theia-go-extension (⭐16)](https://github.com/theia-ide/theia-go-extension) - Go language support for the Theia IDE.
*   [vim-compiler-go (⭐88)](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save.
*   [vim-go (⭐15k)](https://github.com/fatih/vim-go) - Go development plugin for Vim.
*   [vscode-go (⭐3k)](https://github.com/golang/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
*   [Watch (⭐196)](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes.

**[⬆ back to top](#contents)**

## Go Generate Tools

*   [generic (⭐45)](https://github.com/usk81/generic) - flexible data type for Go.
*   [genny (⭐1.7k)](https://github.com/cheekybits/genny) - Elegant generics for Go.
*   [gocontracts (⭐87)](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation.
*   [godal (⭐14)](https://github.com/mafulong/godal) - Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm.
*   [gonerics (⭐116)](https://github.com/bouk/gonerics) - Idiomatic Generics in Go.
*   [gotests (⭐4.3k)](https://github.com/cweill/gotests) - Generate Go tests from your source code.
*   [gounit (⭐64)](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates.
*   [hasgo (⭐121)](https://github.com/DylanMeeus/hasgo) - Generate Haskell inspired functions for your slices.
*   [re2dfa (⭐195)](https://github.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.
*   [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.
*   [xgen (⭐194)](https://github.com/xuri/xgen) - XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator.

**[⬆ back to top](#contents)**

## Go Tools

*   [colorgo (⭐111)](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output.
*   [depth (⭐797)](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports.
*   [docs (⭐14)](https://github.com/go-oas/docs) - Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard.
*   [generator-go-lang (⭐25)](https://github.com/axelspringer/generator-go-lang) - A [Yeoman](https://yeoman.io) generator to get new Go projects started.
*   [go-callvis (⭐4.5k)](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format.
*   [go-james (⭐56)](https://github.com/pieterclaerhout/go-james) - Go project skeleton creator, builds and tests your projects without the manual setup.
*   [go-pkg-complete (⭐41)](https://github.com/skelterjohn/go-pkg-complete) - Bash completion for go and wgo.
*   [go-swagger (⭐8.1k)](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
*   [godbg (⭐187)](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development.
*   [gomodrun (⭐24)](https://github.com/dustinblackman/gomodrun/) - Go tool that executes and caches binaries included in go.mod files.
*   [gotemplate.io](https://gotemplate.io/) - Online tool to preview `text/template` templates live.
*   [gotestdox (⭐22)](https://github.com/bitfield/gotestdox) - Show Go test results as readable sentences.
*   [gothanks (⭐115)](https://github.com/psampaz/gothanks) - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers.
*   [igo (⭐55)](https://github.com/rocketlaunchr/igo) - An igo to go transpiler (new language features for Go language!)
*   [modver (⭐3)](https://github.com/bobg/modver) - Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules.
*   [OctoLinker (⭐5.1k)](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
*   [richgo (⭐738)](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations.
*   [roumon (⭐123)](https://github.com/becheran/roumon) - Monitor current state of all active goroutines via a command line interface.
*   [rts (⭐235)](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses.
*   [typex (⭐154)](https://github.com/dtgorski/typex) - Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration.

**[⬆ back to top](#contents)**

## Software Packages

*Software written in Go.*

**[⬆ back to top](#contents)**

### DevOps Tools

*   [abbreviate (⭐191)](https://github.com/dnnrly/abbreviate) - abbreviate is a tool turning long strings in to shorter ones with configurable separators, for example to embed branch names in to deployment stack IDs.
*   [aptly (⭐9)](https://github.com/smira/aptly) - aptly is a Debian repository management tool.
*   [aurora (⭐569)](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console.
*   [awsenv (⭐31)](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile.
*   [Balerter (⭐278)](https://github.com/balerter/balerter) - A self-hosted script-based alerting manager.
*   [Blast (⭐210)](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs.
*   [bombardier (⭐3.8k)](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool.
*   [bosun (⭐3.3k)](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework.
*   [cassowary (⭐627)](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in Go.
*   [Ddosify (⭐5.1k)](https://github.com/ddosify/ddosify) - High-performance load testing tool, written in Golang.
*   [DepCharge (⭐23)](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects.
*   [docker-go-mingw (⭐34)](https://github.com/x1unix/docker-go-mingw) - Docker image for building Go binaries for Windows with MinGW toolchain.
*   [Dockerfile-Generator (⭐140)](https://github.com/ozankasikci/dockerfile-generator) - A go library and an executable that produces valid Dockerfiles using various input channels.
*   [dogo (⭐253)](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart).
*   [drone-jenkins (⭐35)](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
*   [drone-scp (⭐113)](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI.
*   [Dropship (⭐62)](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn.
*   [easyssh-proxy (⭐264)](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
*   [fac (⭐1.8k)](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts.
*   [Fleet device management (⭐968)](https://github.com/fleetdm/fleet) - Lightweight, programmable telemetry for servers and workstations.
*   [gaia (⭐4.8k)](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language.
*   [ghorg (⭐1.1k)](https://github.com/gabrie30/ghorg) - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket.
*   [Gitea (⭐33k)](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven.
*   [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
*   [go-furnace (⭐94)](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.
*   [go-rocket-update (⭐73)](https://github.com/mouuff/go-rocket-update) - A simple way to make self updating Go applications - Supports Github and Gitlab.
*   [go-selfupdate (⭐1.1k)](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update.
*   [gobrew (⭐193)](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go.
*   [godbg (⭐227)](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application.
*   [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
*   [gonative (⭐333)](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
*   [govvv (⭐531)](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries.
*   [gox (⭐4.4k)](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool.
*   [goxc (⭐1.7k)](https://github.com/laher/goxc) - build tool for Go, with a focus on cross-compiling and packaging.
*   [grapes (⭐158)](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease.
*   [GVM (⭐7.9k)](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions.
*   [Hey (⭐15k)](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application.
*   [httpref (⭐26)](https://github.com/dnnrly/httpref) - httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports.
*   [jcli (⭐339)](https://github.com/jenkins-zh/jenkins-cli) - Jenkins CLI allows you manage your Jenkins as an easy way.
*   [kala (⭐1.9k)](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler.
*   [kcli (⭐187)](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages.
*   [ko (⭐5.3k)](https://github.com/google/ko) - Command line tool for building and deploying Go applications on Kubernetes
*   [kool (⭐617)](https://github.com/kool-dev/kool) - Command line tool for managing Docker environments as an easy way.
*   [kubernetes (⭐94k)](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google.
*   [kwatch (⭐690)](https://github.com/abahmed/kwatch) - Monitor & detect crashes in your Kubernetes(K8s) cluster instantly.
*   [lstags (⭐296)](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries.
*   [lwc (⭐27)](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command.
*   [manssh (⭐275)](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily.
*   [Mantil (⭐96)](https://github.com/mantil-io/mantil) - Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure.
*   [Mizu (⭐4.2k)](https://github.com/up9inc/mizu) - API traffic viewer for Kubernetes enabling you to view all API communication between microservices, multiprotocol support: HTTP1.1, HTTP/2, AMQP, Kafka, Redis.
*   [Moby (⭐64k)](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems.
*   [Mora (⭐307)](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data.
*   [ostent (⭐175)](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
*   [Packer (⭐14k)](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
*   [Pewpew (⭐361)](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester.
*   [Pomerium (⭐3.3k)](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy.
*   [Rodent (⭐33)](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies.
*   [s3-proxy (⭐139)](https://github.com/oxyno-zeta/s3-proxy) - S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).
*   [s3gof3r (⭐1.1k)](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
*   [s5cmd (⭐1.4k)](https://github.com/peak/s5cmd) - Blazing fast S3 and local filesystem execution tool.
*   [Scaleway-cli (⭐785)](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker).
*   [script (⭐3.1k)](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.
*   [sg (⭐8)](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.
*   [skm (⭐833)](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
*   [StatusOK (⭐1.6k)](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
*   [terraform-provider-openapi (⭐221)](https://github.com/dikhan/terraform-provider-openapi) - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed.
*   [traefik (⭐40k)](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends.
*   [trubka (⭐326)](https://github.com/xitonix/trubka) - A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka.
*   [uTask (⭐783)](https://github.com/ovh/utask) - Automation engine that models and executes business processes declared in yaml.
*   [Vegeta (⭐20k)](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000!
*   [wait-for (⭐5)](https://github.com/dnnrly/wait-for) - Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things.
*   [webhook (⭐8.4k)](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
*   [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
*   [winrm-cli (⭐144)](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines.

**[⬆ back to top](#contents)**

### Other Software

*   [Better Go Playground](https://goplay.tools) - Go playground with syntax highlight, code completion and other features.
*   [blocky (⭐2k)](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy as ad-blocker for local network with many features.
*   [borg (⭐1.6k)](https://github.com/crufter/borg) - Terminal based search engine for bash snippets.
*   [boxed (⭐78)](https://github.com/tejo/boxed) - Dropbox based blog engine.
*   [Cherry (⭐286)](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go.
*   [Circuit (⭐2k)](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
*   [Comcast (⭐9.8k)](https://github.com/tylertreat/Comcast) - Simulate bad network connections.
*   [confd (⭐7.9k)](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul.
*   [crawley (⭐106)](https://github.com/s0rg/crawley) - Web scraper/crawler for cli.
*   [croc (⭐21k)](https://github.com/schollz/croc) - Easily and securely send files or folders from one computer to another.
*   [Docker](https://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
*   [Documize (⭐1.7k)](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools.
*   [dp (⭐86)](https://github.com/scryinfo/dp) - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development.
*   [drive (⭐6.5k)](https://github.com/odeke-em/drive) - Google Drive client for the commandline.
*   [Duplicacy (⭐4.3k)](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
*   [Gebug (⭐612)](https://github.com/moshebe/gebug) - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
*   [gfile (⭐686)](https://github.com/Antonito/gfile) - Securely transfer files between two computers, without any third party, over WebRTC.
*   [Go Package Store (⭐889)](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH.
*   [go-peerflix (⭐454)](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client.
*   [goblin](https://goblin.reaper.im) - Golang binaries in a curl, built by goblins.
*   [GoBoy (⭐2.5k)](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go.
*   [gocc (⭐543)](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go.
*   [GoDocTooltip (⭐13)](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.
*   [Gokapi (⭐453)](https://github.com/Forceu/gokapi) - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to Firefox Send, but without public upload.
*   [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
*   [Gor (⭐16k)](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
*   [Guora (⭐613)](https://github.com/meloalright/guora) - A self-hosted Quora like web application written in Go.
*   [hoofli (⭐5)](https://github.com/dnnrly/hoofli) - Generate PlantUML diagrams from Chrome or Firefox network inspections.
*   [hugo](https://gohugo.io/) - Fast and Modern Static Website Engine.
*   [ide (⭐353)](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go.
*   [ipe (⭐359)](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
*   [joincap (⭐178)](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together.
*   [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
*   [Leaps (⭐730)](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms.
*   [lgo (⭐2.3k)](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
*   [limetext](https://limetext.github.io) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
*   [LiteIDE (⭐7k)](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE.
*   [mockingjay (⭐524)](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
*   [myLG (⭐2.6k)](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go.
*   [naclpipe (⭐23)](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go.
*   [Neo-cowsay (⭐232)](https://github.com/Code-Hex/Neo-cowsay) - 🐮 cowsay is reborn. for a New Era.
*   [nes (⭐5.1k)](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go.
*   [Orbit (⭐174)](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates.
*   [peg (⭐879)](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
*   [Plik (⭐1.1k)](https://github.com/root-gg/plik) - Plik is a temporary file upload system (Wetransfer like) in Go.
*   [protoncheck (⭐4)](https://github.com/servusdei2018/protoncheck) - ProtonMail module for waybar/polybar/yabar/i3blocks.
*   [restic (⭐18k)](https://github.com/restic/restic) - De-duplicating backup program.
*   [sake (⭐570)](https://github.com/alajmo/sake) - sake is a command runner for local and remote hosts.
*   [scc (⭐3.9k)](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.
*   [Seaweed File System (⭐16k)](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
*   [shell2http (⭐1k)](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control).
*   [snap (⭐1.8k)](https://github.com/intelsdi-x/snap) - Powerful telemetry framework.
*   [Snitch (⭐16)](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
*   [Stack Up (⭐2.4k)](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
*   [stew (⭐108)](https://github.com/marwanhawari/stew) - An independent package manager for compiled binaries.
*   [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
*   [tcpdog (⭐212)](https://github.com/mehrdadrad/tcpdog) - eBPF based TCP observability.
*   [tcpprobe (⭐330)](https://github.com/mehrdadrad/tcpprobe) - TCP tool for network performance and path monitoring, including socket statistics.
*   [term-quiz (⭐23)](https://github.com/crazcalm/term-quiz) - Quizzes for your terminal.
*   [toxiproxy (⭐8.7k)](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests.
*   [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
*   [vaku (⭐140)](https://github.com/lingrino/vaku) - CLI & API for folder-based functions in Vault like copy, move, and search.
*   [vFlow (⭐932)](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
*   [wellington (⭐300)](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass).
*   [woke (⭐352)](https://github.com/get-woke/woke) - Detect non-inclusive language in your source code.

**[⬆ back to top](#contents)**

# Resources

*Where to discover new Go libraries.*

**[⬆ back to top](#contents)**

## Benchmarks

*   [autobench (⭐95)](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions.
*   [go-benchmark-app (⭐24)](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
*   [go-benchmarks (⭐146)](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
*   [go-http-routing-benchmark (⭐1.6k)](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison.
*   [go-json-benchmark (⭐8)](https://github.com/zerosnake0/go-json-benchmark) - Go JSON benchmark.
*   [go-ml-benchmarks (⭐24)](https://github.com/nikolaydubina/go-ml-benchmarks) - benchmarks for machine learning inference in Go.
*   [go-web-framework-benchmark (⭐1.8k)](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark.
*   [go\_serialization\_benchmarks (⭐1.4k)](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods.
*   [gocostmodel (⭐58)](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language.
*   [golang-sql-benchmark (⭐62)](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities.
*   [gospeed (⭐110)](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs.
*   [kvbench (⭐25)](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark.
*   [skynet (⭐1k)](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark.
*   [speedtest-resize (⭐225)](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language.

**[⬆ back to top](#contents)**

## Conferences

*   [Capital Go](http://www.capitalgolang.com) - Washington, D.C., USA.
*   [dotGo](https://www.dotgo.eu) - Paris, France.
*   [GoCon](https://gocon.connpass.com/) - Tokyo, Japan.
*   [GoDays](https://www.godays.io/) - Berlin, Germany.
*   [GoLab](https://golab.io/) - Florence, Italy.
*   [GopherChina](https://gopherchina.org) - Shanghai, China.
*   [GopherCon](https://www.gophercon.com/) - Denver, USA.
*   [GopherCon Australia](https://gophercon.com.au/) - Sydney, Australia.
*   [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, Brazil.
*   [GopherCon Europe](https://gophercon.eu/) - Berlin, Germany.
*   [GopherCon India](https://www.gophercon.in/) - Pune, India.
*   [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
*   [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
*   [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
*   [GopherCon UK](https://www.gophercon.co.uk/) - London, UK.
*   [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
*   [GoWest Conference](https://www.gowestconf.com/) - Lehi, USA.

**[⬆ back to top](#contents)**

## E-Books

### E-books for purchase

*   [100 Go Mistakes: How to Avoid Them](https://www.manning.com/books/100-go-mistakes-how-to-avoid-them)
*   [Black Hat Go](https://nostarch.com/blackhatgo) - Go programming for hackers and pentesters.
*   [Build an Orchestrator in Go](https://www.manning.com/books/build-an-orchestrator-in-go)
*   [Continuous Delivery in Go](https://www.manning.com/books/continuous-delivery-in-go) - This practical guide to continuous delivery shows you how to rapidly establish an automated pipeline that will improve your testing, code quality, and final product.
*   [Creative DIY Microcontroller Project With TinyGo and WebAssembly](https://www.packtpub.com/product/creative-diy-microcontroller-projects-with-tinygo-and-webassembly/9781800560208) - An introduction into the TinyGo compiler with projects involving Arduino and WebAssembly.
*   [Effective Go: Elegant, efficient, and testable code](https://www.manning.com/books/effective-go) - Unlock Go’s unique perspective on program design, and start writing simple, maintainable, and testable Go code.
*   [For the Love of Go](https://bitfieldconsulting.com/books/love) - An introductory book for Go beginners.
*   [Know Go: Generics](https://bitfieldconsulting.com/books/generics) - A guide to understanding and using generics in Go.
*   [The Power of Go: Tests](https://bitfieldconsulting.com/books/tests) - A guide to testing in Go.
*   [The Power of Go: Tools](https://bitfieldconsulting.com/books/tools) - A guide to writing command-line tools in Go.
*   [Writing A Compiler In Go](https://compilerbook.com)
*   [Writing An Interpreter In Go](https://interpreterbook.com) - Book that introduces dozens of techniques for writing idiomatic, expressive, and efficient Go code that avoids common pitfalls.

### Free e-books

*   [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
*   [An Introduction to Programming in Go](http://www.golang-book.com/)
*   [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/)
*   [Building Web Apps With Go](https://codegangsta.gitbooks.io/building-web-apps-with-go/content/)
*   [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
*   [Go AST Book (Chinese) (⭐4.7k)](https://github.com/chai2010/go-ast-book) - A book focusing on Go `go/*` packages.
*   [Go Bootcamp](http://golangbootcamp.com)
*   [Go Succinctly (⭐22)](https://github.com/thedevsir/gosuccinctly) - in Persian.
*   [GoBooks (⭐13k)](https://github.com/dariubs/GoBooks) - A curated list of Go books.
*   [How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) - A 600 page introduction to Go aimed at first time developers.
*   [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
*   [Network Programming With Go](https://jan.newmarch.name/golang/)
*   [Practical Go Lessons](https://www.practical-go-lessons.com/)
*   [Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/)
*   [The Go Programming Language](https://www.gopl.io/)
*   [The Golang Standard Library by Example (Chinese) (⭐8.9k)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example)
*   [Web Application with Go the Anti-Textbook (⭐3.1k)](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/)

**[⬆ back to top](#contents)**

## Gophers

*   [Free Gophers Pack (⭐2.6k)](https://github.com/MariaLetta/free-gophers-pack) - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster.
*   [Go-gopher-Vector (⭐57)](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data \[.ai, .svg].
*   [gopher-logos (⭐106)](https://github.com/GolangUA/gopher-logos) - adorable gopher logos.
*   [gopher-stickers (⭐544)](https://github.com/tenntenn/gopher-stickers)
*   [gophericons (⭐606)](https://github.com/shalakhin/gophericons)
*   [gopherize.me (⭐604)](https://github.com/matryer/gopherize.me) - Gopherize yourself.
*   [gophers (⭐2.7k)](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara.
*   [gophers (⭐3k)](https://github.com/egonelbre/gophers) - Free gophers.
*   [gophers (⭐57)](https://github.com/rogeralsing/gophers) - random gopher graphics.
*   [gophers (⭐107)](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern.
*   [gophers (⭐19)](https://github.com/scraly/gophers) - Gophers by Aurélie Vache.

**[⬆ back to top](#contents)**

## Meetups

*   [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
*   [Belfast Gophers](https://www.meetup.com/Belfast-Gophers/)
*   [Belgrade Golang Meetup](https://www.meetup.com/golang-serbia/)
*   [Berlin Golang](https://www.meetup.com/golang-users-berlin/)
*   [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
*   [Canberra Gophers](https://www.meetup.com/Canberra-Gophers/)
*   [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
*   [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
*   [Go Remote Meetup](https://www.meetup.com/Go-Remote-Meetup/)
*   [Go Toronto](https://www.meetup.com/go-toronto/)
*   [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
*   [GoBandung](https://www.meetup.com/GoBandung/)
*   [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
*   [GoCracow - Krakow, Poland](https://www.meetup.com/GoCracow/)
*   [GoJakarta](https://www.meetup.com/GoJakarta/)
*   [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
*   [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
*   [Golang Athens](https://www.meetup.com/Athens-Gophers/)
*   [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
*   [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
*   [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
*   [Golang Boston](https://www.meetup.com/bostongo/)
*   [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
*   [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
*   [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
*   [Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/)
*   [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
*   [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
*   [Golang Estonia](https://www.meetup.com/Golang-Estonia/)
*   [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
*   [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
*   [Golang Israel](https://www.meetup.com/Go-Israel/)
*   [Golang Kathmandu](https://www.meetup.com/Golang-Kathmandu/)
*   [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
*   [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
*   [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
*   [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
*   [Golang Melbourne](https://www.meetup.com/golang-mel/)
*   [Golang Mountain View](https://www.meetup.com/Golang-Mountain-View/)
*   [Golang North East](https://www.meetup.com/en-AU/Golang-North-East/)
*   [Golang Paris](https://www.meetup.com/Golang-Paris/)
*   [Golang Poland](https://www.meetup.com/Golang-Poland/)
*   [Golang Pune](https://www.meetup.com/Golang-Pune/)
*   [Golang Singapore](https://www.meetup.com/golangsg/)
*   [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
*   [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
*   [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
*   [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
*   [Golang Thessaloniki](https://www.meetup.com/thessaloniki-golang-meetup/)
*   [Golang Turkey](https://kommunity.com/goturkiye)
*   [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
*   [Golang Vienna, Austria](https://www.meetup.com/viennago/)
*   [Golang Казань](https://www.meetup.com/GolangKazan/)
*   [Golang Москва](https://www.meetup.com/Golang-Moscow/)
*   [Golang Питер](https://www.meetup.com/Golang-Peter/)
*   [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
*   [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
*   [Seattle Go Programmers](https://www.meetup.com/golang/)
*   [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
*   [Utah Go User Group](https://www.meetup.com/utahgophers/)
*   [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)

*Add the group of your city/country here (send **PR**)*

**[⬆ back to top](#contents)**

## Style Guides

*   [bahlo/go-styleguide (⭐1.4k)](https://github.com/bahlo/go-styleguide)
*   [CockroachDB (⭐26k)](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md)
*   [GitLab](https://docs.gitlab.com/ee/development/go_guide/)
*   [Hyperledger (⭐14k)](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst)
*   [Magnetico (⭐2.9k)](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification)
*   [Sourcegraph](https://about.sourcegraph.com/handbook/engineering/go_style_guide)
*   [Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/)
*   [Trybe (⭐313)](https://github.com/betrybe/playbook-go/blob/main/README_EN.md)
*   [Uber (⭐13k)](https://github.com/uber-go/guide/blob/master/style.md)

**[⬆ back to top](#contents)**

## Social Media

### Twitter

*   [@golang](https://twitter.com/golang)
*   [@golang\_news](https://twitter.com/golang_news)
*   [@golangch](https://twitter.com/golangch)
*   [@golangflow](https://twitter.com/golangflow)
*   [@golangweekly](https://twitter.com/golangweekly)

**[⬆ back to top](#contents)**

### Reddit

*   [r/golang](https://www.reddit.com/r/golang/)

**[⬆ back to top](#contents)**

## Websites

*   [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
*   [Awesome Golang Workshops (⭐477)](https://github.com/amit-davidson/awesome-golang-workshops) - A curated list of awesome golang workshops.
*   [Awesome Remote Job (⭐23k)](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
*   [awesome-awesomeness (⭐30k)](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists.
*   [awesome-go-extra (⭐19)](https://github.com/xwjdsh/awesome-go-extra) - Parse awesome-go README file and generate a new README file with repo info.
*   [Code with Mukesh](https://codewithmukesh.com/blog/category/golang) - Software Engineer and Blogs @ codewithmukesh.com.
*   [Coding Mystery](https://codingmystery.com) - Solve exciting escape-room-inspired programming challenges using Go.
*   [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
*   [Explore Go Libraries & Projects](https://kandi.openweaver.com/explore/go) - Discover & find a curated list of popular & new Go libraries, top authors, trending project kits, discussions, tutorials & learning resources on kandi.
*   [Go Blog](https://blog.golang.org) - The official Go blog.
*   [Go Code Club](https://www.youtube.com/watch?v=nvoIPQYdx9g\&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3) - A group of Gophers read and discuss a different Go project every week.
*   [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
*   [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
*   [Go Projects (⭐106k)](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
*   [Go Proverbs](https://go-proverbs.github.io/) - Go Proverbs by Rob Pike.
*   [Go Report Card](https://goreportcard.com) - A report card for your Go package.
*   [go.dev](https://go.dev/) - A hub for Go developers.
*   [gocryforhelp (⭐40)](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go.
*   [godoc.org](https://godoc.org/) - Documentation for open source Go packages.
*   [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusively for Golang related Roles.
*   [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
*   [Golang News](https://golangnews.com) - Links and news about Go programming.
*   [Golang Resources](https://golangresources.com) - A curation of the best articles, exercises, talks and videos to learn Go.
*   [golang-graphics (⭐138)](https://github.com/mholt/golang-graphics) - Collection of Go images, graphics, and art.
*   [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
*   [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
*   [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
*   [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
*   [gowalker.org](https://gowalker.org) - Go Project API documentation.
*   [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
*   [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by  Francesc Campoy [@francesc](https://twitter.com/francesc).
*   [Learn Go Programming](https://blog.learngoprogramming.com) - Learn Go concepts with illustrations.
*   [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
*   [r/Golang](https://www.reddit.com/r/golang) - News about Go.
*   [studygolang](https://studygolang.com) - The community of studygolang in China.
*   [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
*   [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

**[⬆ back to top](#contents)**

### Tutorials

*   [50 Shades of Go](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
*   [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
*   [A Tour of Go](https://tour.golang.org/) - Interactive tour of Go.
*   [Build web application with Golang (⭐41k)](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang.
*   [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) - We’ll write an API with the help of the powerful Gorilla Mux.
*   [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
*   [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
*   [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
*   [CodeCrafters Golang Track](https://app.codecrafters.io/tracks/go) - Achieve mastery in advanced Go by building your own Redis, Docker, Git, and SQLite. Featuring goroutines, systems programming, file I/O, and more.
*   [Debugged.it Go patterns (⭐5)](https://github.com/haveyoudebuggedit/go-patterns) - Advanced Go patterns with ready-to-run examples.
*   [Design Patterns in Go (⭐85)](https://github.com/shubhamzanwar/design-patterns) - Collection of programming design patterns implemented in Go.
*   [Ethereum Development with Go (⭐1.5k)](https://github.com/miguelmota/ethereum-development-with-go-book) - A little e-book on Ethereum Development with Go.
*   [Games With Go](https://www.youtube.com/watch?v=9D4yH7e_ea8\&list=PLDZujg-VgQlZUy1iCqBbe5faZLMkA3g2x) - A video series teaching programming and game development.
*   [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
*   [Go Cheat Sheet (⭐7.1k)](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card.
*   [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
*   [Go in 7 days (⭐106)](https://github.com/harrytran103/7_days_of_go) - Learn everything about Go in 7 days (from a Nodejs developer).
*   [Go Language Tutorial](https://www.javatpoint.com/go-tutorial) - Learn Go language Tutorial.
*   [Go Tutorial](https://www.tutorialspoint.com/go/index.htm) - Learn Go programming.
*   [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
*   [go-clean-template (⭐3.8k)](https://github.com/evrone/go-clean-template) - Clean Architecture template for Golang services.
*   [go-patterns (⭐20k)](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms.
*   [goapp (⭐538)](https://github.com/bnkamalesh/goapp) - An opinionated guideline to structure & develop a Go web application/service.
*   [Golang for Node.js Developers (⭐3.2k)](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning.
*   [Golang Tutorial Guide](https://www.freecodecamp.org/news/golang-tutorial-list-free-courses-learn-go-programming-language/) - A List of Free Courses to Learn the Go Programming Language.
*   [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
*   [GopherCoding](https://gophercoding.com/) - Collection of code snippets and tutorials to help tackle every day issues.
*   [GopherSnippets](https://gophersnippets.com/) - Code snippets with tests and testable examples for the Go programming language.
*   [Gosamples](https://gosamples.dev/) - Collection of code snippets that let you solve everyday code problems.
*   [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
*   [How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) - Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM.
*   [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) - Learn how to use Docker for Go development and how to build production Docker images.
*   [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
*   [Learn Go with 1000+ Exercises (⭐16k)](https://github.com/inancgumus/learngo) - Learn Go with thousands of examples, exercises, and quizzes.
*   [Learn Go with TDD (⭐19k)](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development.
*   [Learning Go by examples](https://dev.to/aurelievache/learning-go-by-examples-introduction-448n) - Serie of article in order to learn Golang language by concrete applications as example.
*   [Microservices with Go](https://www.youtube.com/playlist?list=PLmD8u-IFdreyh6EUfevBcbiuCKzFk0EW_) - Dive deep into building microservices using Go, including gRPC.
*   [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
*   [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
*   [Saving a Third of Our Memory by Re-ordering Go Struct Fields](https://qvault.io/golang/struct-field-ordering-memory/) - How inefficient field ordering in Go structs.
*   [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
*   [W3basic Go Tutorials](https://www.w3basic.com/golang/) - W3Basic provides an in-depth tutorial and well-organized content to learn Golang programming.
*   [Working with Go (⭐1.2k)](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers.
*   [Your basic Go](https://yourbasic.org/golang) - Huge collection of tutorials and how to's.

**[⬆ back to top](#contents)**

