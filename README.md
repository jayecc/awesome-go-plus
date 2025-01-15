# Awesome Go

<a href="https://awesome-go.com/"><img align="right" src="https://github.com/avelino/awesome-go/raw/main/tmpl/assets/logo.png" alt="awesome-go" title="awesome-go" /></a>

[![Build Status](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml/badge.svg?branch=main)](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml?query=branch%3Amain)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](https://gophers.slack.com/messages/awesome)
[![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/avelino/awesome-go/)
[![Last Commit](https://img.shields.io/github/last-commit/avelino/awesome-go)](https://img.shields.io/github/last-commit/avelino/awesome-go)

We use the _[Golang Bridge](https://github.com/gobridge/about-us/blob/master/README.md)_ community Slack for instant communication, follow the [form here to join](https://invite.slack.golangbridge.org/).

<a href="https://www.producthunt.com/posts/awesome-go?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-awesome-go" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=291535&theme=light" alt="awesome-go - Curated list awesome Go frameworks, libraries and software | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

**Sponsorships:**

_Special thanks to_

<div align="center">
<table cellpadding="5">
<tbody align="center">
<tr>
<td colspan="2">
<a href="https://bit.ly/awesome-go-workos">
<img src="https://avelino.run/sponsors/workos-logo-white-bg.svg" width="200" alt="WorkOS"><br/>
<b>Your app, enterprise-ready.</b><br/>
<sub>Start selling to enterprise customers with just a few lines of code.</sub><br/>
<sup>Add Single Sign-On (and more) in minutes instead of months.</sup>
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

**Awesome Go has no monthly fee**_, but we have employees who **work hard** to keep it running. With money raised, we can repay the effort of each person involved! You can see how we calculate our billing and distribution as it is open to the entire community. Want to be a supporter of the project click [here](mailto:avelinorun+oss@gmail.com?subject=awesome-go%3A%20project%20support)._

> A curated list of awesome Go frameworks, libraries, and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python).

**Contributing:**

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/main/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

> _If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!_

## Contents

- [Awesome Go](#awesome-go)
  - [Contents](#contents)
  - [Actor Model](#actor-model)
  - [Artificial Intelligence](#artificial-intelligence)
  - [Audio and Music](#audio-and-music)
  - [Authentication and OAuth](#authentication-and-oauth)
  - [Blockchain](#blockchain)
  - [Bot Building](#bot-building)
  - [Build Automation](#build-automation)
  - [Command Line](#command-line)
    - [Advanced Console UIs](#advanced-console-uis)
    - [Standard CLI](#standard-cli)
  - [Configuration](#configuration)
  - [Continuous Integration](#continuous-integration)
  - [CSS Preprocessors](#css-preprocessors)
  - [Data Integration Frameworks](#data-integration-frameworks)
  - [Data Structures and Algorithms](#data-structures-and-algorithms)
    - [Bit-packing and Compression](#bit-packing-and-compression)
    - [Bit Sets](#bit-sets)
    - [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
    - [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
    - [Iterators](#iterators)
    - [Maps](#maps)
    - [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
    - [Nullable Types](#nullable-types)
    - [Queues](#queues)
    - [Sets](#sets)
    - [Text Analysis](#text-analysis)
    - [Trees](#trees)
    - [Pipes](#pipes)
  - [Database](#database)
    - [Caches](#caches)
    - [Databases Implemented in Go](#databases-implemented-in-go)
    - [Database Schema Migration](#database-schema-migration)
    - [Database Tools](#database-tools)
    - [SQL Query Builders](#sql-query-builders)
  - [Database Drivers](#database-drivers)
    - [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
    - [Relational Database Drivers](#relational-database-drivers)
    - [NoSQL Database Drivers](#nosql-database-drivers)
    - [Search and Analytic Databases](#search-and-analytic-databases)
  - [Date and Time](#date-and-time)
  - [Distributed Systems](#distributed-systems)
  - [Dynamic DNS](#dynamic-dns)
  - [Email](#email)
  - [Embeddable Scripting Languages](#embeddable-scripting-languages)
  - [Error Handling](#error-handling)
  - [File Handling](#file-handling)
  - [Financial](#financial)
  - [Forms](#forms)
  - [Functional](#functional)
  - [Game Development](#game-development)
  - [Generators](#generators)
  - [Geographic](#geographic)
  - [Go Compilers](#go-compilers)
  - [Goroutines](#goroutines)
  - [GUI](#gui)
  - [Hardware](#hardware)
  - [Images](#images)
  - [IoT (Internet of Things)](#iot-internet-of-things)
  - [Job Scheduler](#job-scheduler)
  - [JSON](#json)
  - [Logging](#logging)
  - [Machine Learning](#machine-learning)
  - [Messaging](#messaging)
  - [Microsoft Office](#microsoft-office)
    - [Microsoft Excel](#microsoft-excel)
    - [Microsoft Word](#microsoft-word)
  - [Miscellaneous](#miscellaneous)
    - [Dependency Injection](#dependency-injection)
    - [Project Layout](#project-layout)
    - [Strings](#strings)
    - [Uncategorized](#uncategorized)
  - [Natural Language Processing](#natural-language-processing)
    - [Language Detection](#language-detection)
    - [Morphological Analyzers](#morphological-analyzers)
    - [Slugifiers](#slugifiers)
    - [Tokenizers](#tokenizers)
    - [Translation](#translation)
    - [Transliteration](#transliteration)
  - [Networking](#networking)
    - [HTTP Clients](#http-clients)
  - [OpenGL](#opengl)
  - [ORM](#orm)
  - [Package Management](#package-management)
  - [Performance](#performance)
  - [Query Language](#query-language)
  - [Reflection](#reflection)
  - [Resource Embedding](#resource-embedding)
  - [Science and Data Analysis](#science-and-data-analysis)
  - [Security](#security)
  - [Serialization](#serialization)
  - [Server Applications](#server-applications)
  - [Stream Processing](#stream-processing)
  - [Template Engines](#template-engines)
  - [Testing](#testing)
    - [Testing Frameworks](#testing-frameworks)
    - [Mock](#mock)
    - [Fuzzing and delta-debugging/reducing/shrinking](#fuzzing-and-delta-debuggingreducingshrinking)
    - [Selenium and browser control tools](#selenium-and-browser-control-tools)
    - [Fail injection](#fail-injection)
  - [Text Processing](#text-processing)
    - [Formatters](#formatters)
    - [Markup Languages](#markup-languages)
    - [Parsers/Encoders/Decoders](#parsersencodersdecoders)
    - [Regular Expressions](#regular-expressions)
    - [Sanitation](#sanitation)
    - [Scrapers](#scrapers)
    - [RSS](#rss)
    - [Utility/Miscellaneous](#utilitymiscellaneous)
  - [Third-party APIs](#third-party-apis)
  - [Utilities](#utilities)
  - [UUID](#uuid)
  - [Validation](#validation)
  - [Version Control](#version-control)
  - [Video](#video)
  - [Web Frameworks](#web-frameworks)
    - [Middlewares](#middlewares)
      - [Actual middlewares](#actual-middlewares)
      - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
    - [Routers](#routers)
  - [WebAssembly](#webassembly)
  - [Webhooks Server](#webhooks-server)
  - [Windows](#windows)
  - [Workflow Frameworks](#workflow-frameworks)
  - [XML](#xml)
  - [Zero Trust](#zero-trust)
  - [Code Analysis](#code-analysis)
  - [Editor Plugins](#editor-plugins)
  - [Go Generate Tools](#go-generate-tools)
  - [Go Tools](#go-tools)
  - [Software Packages](#software-packages)
    - [DevOps Tools](#devops-tools)
    - [Other Software](#other-software)
- [Resources](#resources)
  - [Benchmarks](#benchmarks)
  - [Conferences](#conferences)
  - [E-Books](#e-books)
    - [E-books for purchase](#e-books-for-purchase)
    - [Free e-books](#free-e-books)
  - [Gophers](#gophers)
  - [Meetups](#meetups)
  - [Style Guides](#style-guides)
  - [Social Media](#social-media)
    - [Twitter](#twitter)
    - [Reddit](#reddit)
  - [Websites](#websites)
    - [Tutorials](#tutorials)
    - [Guided Learning](#guided-learning)

**[⬆ back to top](#contents)**

## Actor Model

_Libraries for building actor-based programs._

- [Ergo](https://github.com/ergo-services/ergo) - An actor-based Framework with network transparency for creating event-driven architecture in Golang. Inspired by Erlang. ![stars](https://img.shields.io/badge/stars-3805-blue)
- [Goakt](https://github.com/Tochemey/goakt) - Fast and Distributed Actor framework using protocol buffers as message for Golang. ![stars](https://img.shields.io/badge/stars-209-blue)
- [Hollywood](https://github.com/anthdm/hollywood) - Blazingly fast and light-weight Actor engine written in Golang. ![stars](https://img.shields.io/badge/stars-1516-blue)
- [ProtoActor](https://github.com/asynkron/protoactor-go) - Proto Actor - Ultra fast distributed actors for Go, C# and Java/Kotlin. ![stars](https://img.shields.io/badge/stars-5121-blue)

## Artificial Intelligence

_Libraries for building programs that leverage AI._

- [chromem-go](https://github.com/philippgille/chromem-go) - Embeddable vector database for Go with Chroma-like interface and zero third-party dependencies. In-memory with optional persistence. ![stars](https://img.shields.io/badge/stars-378-blue)
- [fun](https://gitlab.com/tozd/go/fun) - The simplest but powerful way to use large language models (LLMs) in Go.
- [langchaingo](https://github.com/tmc/langchaingo) - LangChainGo is a framework for developing applications powered by language models. ![stars](https://img.shields.io/badge/stars-5354-blue)
- [LocalAI](https://github.com/mudler/LocalAI) - Open Source OpenAI alternative, self-host AI models. ![stars](https://img.shields.io/badge/stars-28353-blue)
- [Ollama](https://github.com/jmorganca/ollama) - Run large language models locally. ![stars](https://img.shields.io/badge/stars-107420-blue)
- [OllamaFarm](https://github.com/presbrey/ollamafarm) - Manage, load-balance, and failover packs of Ollamas ![stars](https://img.shields.io/badge/stars-49-blue)

**[⬆ back to top](#contents)**

## Audio and Music

_Libraries for manipulating audio._

- [flac](https://github.com/mewkiz/flac) - Native Go FLAC encoder/decoder with support for FLAC streams. ![stars](https://img.shields.io/badge/stars-322-blue)
- [gaad](https://github.com/Comcast/gaad) - Native Go AAC bitstream parser. ![stars](https://img.shields.io/badge/stars-127-blue)
- [GoAudio](https://github.com/DylanMeeus/GoAudio) - Native Go Audio Processing Library. ![stars](https://img.shields.io/badge/stars-357-blue)
- [gosamplerate](https://github.com/dh1tw/gosamplerate) - libsamplerate bindings for go. ![stars](https://img.shields.io/badge/stars-34-blue)
- [id3v2](https://github.com/bogem/id3v2) - ID3 decoding and encoding library for Go. ![stars](https://img.shields.io/badge/stars-344-blue)
- [malgo](https://github.com/gen2brain/malgo) - Mini audio library. ![stars](https://img.shields.io/badge/stars-315-blue)
- [minimp3](https://github.com/tosone/minimp3) - Lightweight MP3 decoder library. ![stars](https://img.shields.io/badge/stars-128-blue)
- [Oto](https://github.com/hajimehoshi/oto) - A low-level library to play sound on multiple platforms. ![stars](https://img.shields.io/badge/stars-1644-blue)
- [PortAudio](https://github.com/gordonklaus/portaudio) - Go bindings for the PortAudio audio I/O library. ![stars](https://img.shields.io/badge/stars-720-blue)

**[⬆ back to top](#contents)**

## Authentication and OAuth

_Libraries for implementing authentication schemes._

- [authboss](https://github.com/volatiletech/authboss) - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure it, and start building your app without having to build an authentication system each time. ![stars](https://img.shields.io/badge/stars-3895-blue)
- [branca](https://github.com/essentialkaos/branca) - branca token [specification implementation](https://github.com/tuupola/branca-spec) for Golang 1.15+. ![stars](https://img.shields.io/badge/stars-89-blue)
- [casbin](https://github.com/hsluoyz/casbin) - Authorization library that supports access control models like ACL, RBAC, and ABAC. ![stars](https://img.shields.io/badge/stars-18046-blue)
- [cookiestxt](https://github.com/mengzhuo/cookiestxt) - provides a parser of cookies.txt file format. ![stars](https://img.shields.io/badge/stars-17-blue)
- [go-guardian](https://github.com/shaj13/go-guardian) - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token, and Certificate based authentication. ![stars](https://img.shields.io/badge/stars-566-blue)
- [go-jose](https://github.com/go-jose/go-jose) - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs. ![stars](https://img.shields.io/badge/stars-344-blue)
- [goiabada](https://github.com/leodip/goiabada) - An open-source authentication and authorization server supporting OAuth2 and OpenID Connect. ![stars](https://img.shields.io/badge/stars-137-blue)
- [gologin](https://github.com/dghubble/gologin) - chainable handlers for login with OAuth1 and OAuth2 authentication providers. ![stars](https://img.shields.io/badge/stars-1862-blue)
- [gorbac](https://github.com/mikespook/gorbac) - provides a lightweight role-based access control (RBAC) implementation in Golang. ![stars](https://img.shields.io/badge/stars-1608-blue)
- [gosession](https://github.com/Kwynto/gosession) - This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, or at least it tries to become one. ![stars](https://img.shields.io/badge/stars-259-blue)
- [goth](https://github.com/markbates/goth) - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box. ![stars](https://img.shields.io/badge/stars-5734-blue)
- [jeff](https://github.com/abraithwaite/jeff) - Simple, flexible, secure, and idiomatic web session management with pluggable backends. ![stars](https://img.shields.io/badge/stars-267-blue)
- [jwt](https://github.com/pascaldekloe/jwt) - Lightweight JSON Web Token (JWT) library. ![stars](https://img.shields.io/badge/stars-357-blue)
- [jwt](https://github.com/cristalhq/jwt) - Safe, simple, and fast JSON Web Tokens for Go. ![stars](https://img.shields.io/badge/stars-673-blue)
- [jwt-auth](https://github.com/adam-hanna/jwt-auth) - JWT middleware for Golang http servers with many configuration options. ![stars](https://img.shields.io/badge/stars-233-blue)
- [jwt-go](https://github.com/golang-jwt/jwt) - A full featured implementation of JSON Web Tokens (JWT). This library supports the parsing and verification as well as the generation and signing of JWTs. ![stars](https://img.shields.io/badge/stars-7494-blue)
- [jwx](https://github.com/lestrrat-go/jwx) - Go module implementing various JWx (JWA/JWE/JWK/JWS/JWT, otherwise known as JOSE) technologies ![stars](https://img.shields.io/badge/stars-1982-blue)
- [keto](https://github.com/ory/keto) - Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models. ![stars](https://img.shields.io/badge/stars-4895-blue)
- [loginsrv](https://github.com/tarent/loginsrv) - JWT login microservice with pluggable backends such as OAuth2 (Github), htpasswd, osiam. ![stars](https://img.shields.io/badge/stars-1919-blue)
- [oauth2](https://github.com/golang/oauth2) - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine, and App Engine support. ![stars](https://img.shields.io/badge/stars-5454-blue)
- [oidc](https://github.com/zitadel/oidc) - Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation ![stars](https://img.shields.io/badge/stars-1463-blue)
- [openfga](https://github.com/openfga/openfga) - Implementation of fine-grained authorization based on the "Zanzibar: Google's Consistent, Global Authorization System" paper. Backed by [CNCF](https://www.cncf.io/). ![stars](https://img.shields.io/badge/stars-3127-blue)
- [osin](https://github.com/openshift/osin) - Golang OAuth2 server library. ![stars](https://img.shields.io/badge/stars-1913-blue)
- [otpgen](https://github.com/grijul/otpgen) - Library to generate TOTP/HOTP codes. ![stars](https://img.shields.io/badge/stars-138-blue)
- [otpgo](https://github.com/jltorresm/otpgo) - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go. ![stars](https://img.shields.io/badge/stars-73-blue)
- [paseto](https://github.com/o1egl/paseto) - Golang implementation of Platform-Agnostic Security Tokens (PASETO). ![stars](https://img.shields.io/badge/stars-868-blue)
- [permissions2](https://github.com/xyproto/permissions2) - Library for keeping track of users, login states, and permissions. Uses secure cookies and bcrypt. ![stars](https://img.shields.io/badge/stars-512-blue)
- [scope](https://github.com/SonicRoshan/scope) - Easily Manage OAuth2 Scopes In Go. ![stars](https://img.shields.io/badge/stars-41-blue)
- [scs](https://github.com/alexedwards/scs) - Session Manager for HTTP servers. ![stars](https://img.shields.io/badge/stars-2206-blue)
- [securecookie](https://github.com/chmike/securecookie) - Efficient secure cookie encoding/decoding. ![stars](https://img.shields.io/badge/stars-81-blue)
- [session](https://github.com/icza/session) - Go session management for web servers (including support for Google App Engine - GAE). ![stars](https://img.shields.io/badge/stars-118-blue)
- [sessions](https://github.com/adam-hanna/sessions) - Dead simple, highly performant, highly customizable sessions service for go http servers. ![stars](https://img.shields.io/badge/stars-78-blue)
- [sessionup](https://github.com/swithek/sessionup) - Simple, yet effective HTTP session management and identification package. ![stars](https://img.shields.io/badge/stars-125-blue)
- [sjwt](https://github.com/brianvoe/sjwt) - Simple jwt generator and parser. ![stars](https://img.shields.io/badge/stars-120-blue)

**[⬆ back to top](#contents)**

## Blockchain

_Tools for building blockchains._

- [cometbft](https://github.com/cometbft/cometbft) - A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. It is a fork of Tendermint Core and implements the Tendermint consensus algorithm. ![stars](https://img.shields.io/badge/stars-682-blue)
- [cosmos-sdk](https://github.com/cosmos/cosmos-sdk) - A Framework for Building Public Blockchains in the Cosmos Ecosystem. ![stars](https://img.shields.io/badge/stars-6404-blue)
- [gno](https://github.com/gnolang/gno) - A comprehensive smart contract suite built with Golang and Gnolang, a deterministic, purpose-built Go variant for blockchains. ![stars](https://img.shields.io/badge/stars-912-blue)
- [go-ethereum](https://github.com/ethereum/go-ethereum) - Official Go implementation of the Ethereum protocol. ![stars](https://img.shields.io/badge/stars-48104-blue)
- [gosemble](https://github.com/LimeChain/gosemble) - A Go-based framework for building Polkadot/Substrate-compatible runtimes. ![stars](https://img.shields.io/badge/stars-12-blue)
- [gossamer](https://github.com/ChainSafe/gossamer) - A Go implementation of the Polkadot Host. ![stars](https://img.shields.io/badge/stars-437-blue)
- [kubo](https://github.com/ipfs/kubo) - A blockchain framework implemented in Go. It provides content-addressable storage which can be used for decentralized storage in DApps. It is based on the IPFS protocol. ![stars](https://img.shields.io/badge/stars-16281-blue)
- [lnd](https://github.com/lightningnetwork/lnd) - A complete implementation of a Lightning Network node. ![stars](https://img.shields.io/badge/stars-7781-blue)
- [solana-go](https://github.com/gagliardetto/solana-go) - Go library to interface with Solana JSON RPC and WebSocket interfaces. ![stars](https://img.shields.io/badge/stars-1057-blue)
- [tendermint](https://github.com/tendermint/tendermint) - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols. ![stars](https://img.shields.io/badge/stars-5739-blue)

**[⬆ back to top](#contents)**

## Bot Building

_Libraries for building and working with bots._

- [arikawa](https://github.com/diamondburned/arikawa) - A library and framework for the Discord API.  ![stars](https://img.shields.io/badge/stars-493-blue)
- [bot](https://github.com/go-telegram/bot) - Zero-dependencies Telegram Bot library with additional UI components ![stars](https://img.shields.io/badge/stars-852-blue)
- [echotron](https://github.com/NicoNex/echotron) - An elegant and concurrent library for Telegram Bots in Go. ![stars](https://img.shields.io/badge/stars-382-blue)
- [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) - A Discord bot for managing ephemeral roles based upon voice channel member presence. ![stars](https://img.shields.io/badge/stars-90-blue)
- [go-chat-bot](https://github.com/go-chat-bot/bot) - IRC, Slack & Telegram bot written in Go. ![stars](https://img.shields.io/badge/stars-831-blue)
- [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.
- [go-sarah](https://github.com/oklahomer/go-sarah) - Framework to build a bot for desired chat services including LINE, Slack, Gitter, and more. ![stars](https://img.shields.io/badge/stars-261-blue)
- [go-tg](https://github.com/mr-linch/go-tg) - Generated from official docs Go client library for accessing Telegram Bot API, with batteries for building complex bots included. ![stars](https://img.shields.io/badge/stars-109-blue)
- [go-tgbot](https://github.com/olebedev/go-tgbot) - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router, and middleware. ![stars](https://img.shields.io/badge/stars-120-blue)
- [go-twitch-irc](https://github.com/gempir/go-twitch-irc) - Library to write bots for twitch.tv chat ![stars](https://img.shields.io/badge/stars-365-blue)
- [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) - A golang implementation of a console-based trading bot for cryptocurrency exchanges. ![stars](https://img.shields.io/badge/stars-1096-blue)
- [govkbot](https://github.com/nikepan/govkbot) - Simple Go [VK](https://vk.com) bot library. ![stars](https://img.shields.io/badge/stars-50-blue)
- [hanu](https://github.com/sbstjn/hanu) - Framework for writing Slack bots. ![stars](https://img.shields.io/badge/stars-155-blue)
- [Kelp](https://github.com/stellar/kelp) - official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies. ![stars](https://img.shields.io/badge/stars-1109-blue)
- [larry](https://github.com/ezeoleaf/larry) - Larry 🐦 is a really simple Twitter bot generator that tweets random repositories from Github built in Go. ![stars](https://img.shields.io/badge/stars-162-blue)
- [margelet](https://github.com/zhulik/margelet) - Framework for building Telegram bots. ![stars](https://img.shields.io/badge/stars-86-blue)
- [micha](https://github.com/onrik/micha) - Go Library for Telegram bot api. ![stars](https://img.shields.io/badge/stars-30-blue)
- [olivia](https://github.com/olivia-ai/olivia) - A chatbot built with an artificial neural network. ![stars](https://img.shields.io/badge/stars-3687-blue)
- [slack-bot](https://github.com/innogames/slack-bot) - Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github... ![stars](https://img.shields.io/badge/stars-188-blue)
- [slacker](https://github.com/slack-io/slacker) - Easy to use framework to create Slack bots. ![stars](https://img.shields.io/badge/stars-44-blue)
- [slackscot](https://github.com/alexandre-normand/slackscot) - Another framework for building Slack bots. ![stars](https://img.shields.io/badge/stars-55-blue)
- [tbot](https://github.com/yanzay/tbot) - Telegram bot server with API similar to net/http. ![stars](https://img.shields.io/badge/stars-356-blue)
- [telebot](https://github.com/tucnak/telebot) - Telegram bot framework is written in Go. ![stars](https://img.shields.io/badge/stars-4126-blue)
- [telego](https://github.com/mymmrac/telego) - Telegram Bot API library for Golang with full one-to-one API implementation. ![stars](https://img.shields.io/badge/stars-596-blue)
- [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) - Simple and clean Telegram bot client. ![stars](https://img.shields.io/badge/stars-5924-blue)
- [teleterm](https://github.com/alfiankan/teleterm) - Telegram Bot Exec Terminal Command. ![stars](https://img.shields.io/badge/stars-38-blue)
- [Tenyks](https://github.com/kyleterry/tenyks) - Service oriented IRC bot using Redis and JSON for messaging. ![stars](https://img.shields.io/badge/stars-176-blue)
- [wayback](https://github.com/wabarc/wayback) - A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages. ![stars](https://img.shields.io/badge/stars-1861-blue)

**[⬆ back to top](#contents)**

## Build Automation

_Libraries and tools help with build automation._

- [1build](https://github.com/gopinath-langote/1build) - Command line tool to frictionlessly manage project-specific commands. ![stars](https://img.shields.io/badge/stars-228-blue)
- [air](https://github.com/cosmtrek/air) - Air - Live reload for Go apps. ![stars](https://img.shields.io/badge/stars-18957-blue)
- [anko](https://github.com/GuilhermeCaruso/anko) - Simple application watcher for multiple programming languages. ![stars](https://img.shields.io/badge/stars-39-blue)
- [gaper](https://github.com/maxcnunes/gaper) - Builds and restarts a Go project when it crashes or some watched file changes. ![stars](https://img.shields.io/badge/stars-81-blue)
- [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
- [gob](https://github.com/kcmvp/gob) - [Gradle](https://docs.gradle.org/)/[Maven](https://maven.apache.org/) like build tool for Go projects. ![stars](https://img.shields.io/badge/stars-11-blue)
- [goyek](https://github.com/goyek/goyek) - Create build pipelines in Go. ![stars](https://img.shields.io/badge/stars-579-blue)
- [mage](https://github.com/magefile/mage) - Mage is a make/rake-like build tool using Go. ![stars](https://img.shields.io/badge/stars-4210-blue)
- [mmake](https://github.com/tj/mmake) - Modern Make. ![stars](https://img.shields.io/badge/stars-1722-blue)
- [realize](https://github.com/tockins/realize) - Go build a system with file watchers and live to reload. Run, build and watch file changes with custom paths. ![stars](https://img.shields.io/badge/stars-4460-blue)
- [Task](https://github.com/go-task/task) - simple "Make" alternative. ![stars](https://img.shields.io/badge/stars-11949-blue)
- [taskctl](https://github.com/taskctl/taskctl) - Concurrent task runner. ![stars](https://img.shields.io/badge/stars-302-blue)
- [xc](https://github.com/joerdav/xc) - Task runner with README.md defined tasks, executable markdown. ![stars](https://img.shields.io/badge/stars-1238-blue)

**[⬆ back to top](#contents)**

## Command Line

### Advanced Console UIs

_Libraries for building Console Applications and Console User Interfaces._

- [asciigraph](https://github.com/guptarohit/asciigraph) - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies. ![stars](https://img.shields.io/badge/stars-2715-blue)
- [aurora](https://github.com/logrusorgru/aurora) - ANSI terminal colors that support fmt.Printf/Sprintf. ![stars](https://img.shields.io/badge/stars-1437-blue)
- [box-cli-maker](https://github.com/Delta456/box-cli-maker) - Make Highly Customized Boxes for your CLI. ![stars](https://img.shields.io/badge/stars-545-blue)
- [bubble-table](https://github.com/Evertras/bubble-table) - An interactive table component for bubbletea. ![stars](https://img.shields.io/badge/stars-467-blue)
- [bubbles](https://github.com/charmbracelet/bubbles) - TUI components for bubbletea. ![stars](https://img.shields.io/badge/stars-5821-blue)
- [bubbletea](https://github.com/charmbracelet/bubbletea) - Go framework to build terminal apps, based on The Elm Architecture. ![stars](https://img.shields.io/badge/stars-29026-blue)
- [cfmt](https://github.com/mingrammer/cfmt) - Contextual fmt inspired by bootstrap color classes. ![stars](https://img.shields.io/badge/stars-104-blue)
- [cfmt](https://github.com/i582/cfmt) - Simple and convenient formatted stylized output fully compatible with fmt library. ![stars](https://img.shields.io/badge/stars-69-blue)
- [chalk](https://github.com/ttacon/chalk) - Intuitive package for prettifying terminal/console output. ![stars](https://img.shields.io/badge/stars-456-blue)
- [colourize](https://github.com/TreyBastian/colourize) - Go library for ANSI colour text in terminals. ![stars](https://img.shields.io/badge/stars-27-blue)
- [crab-config-files-templating](https://github.com/alfiankan/crab-config-files-templating) - Dynamic configuration file templating tool for kubernetes manifest or general configuration files. ![stars](https://img.shields.io/badge/stars-7-blue)
- [ctc](https://github.com/wzshiming/ctc) - The non-invasive cross-platform terminal color library does not need to modify the Print method. ![stars](https://img.shields.io/badge/stars-47-blue)
- [fx](https://github.com/antonmedv/fx) - Terminal JSON viewer & processor. ![stars](https://img.shields.io/badge/stars-19187-blue)
- [go-ataman](https://github.com/workanator/go-ataman) - Go library for rendering ANSI colored text templates in terminals. ![stars](https://img.shields.io/badge/stars-18-blue)
- [go-colorable](https://github.com/mattn/go-colorable) - Colorable writer for windows. ![stars](https://img.shields.io/badge/stars-779-blue)
- [go-colortext](https://github.com/daviddengcn/go-colortext) - Go library for color output in terminals. ![stars](https://img.shields.io/badge/stars-216-blue)
- [go-isatty](https://github.com/mattn/go-isatty) - isatty for golang. ![stars](https://img.shields.io/badge/stars-845-blue)
- [go-palette](https://github.com/abusomani/go-palette) - Go library that provides elegant and convenient style definitions using ANSI colors. Fully compatible & wraps the [fmt library](https://pkg.go.dev/fmt) for nice terminal layouts. ![stars](https://img.shields.io/badge/stars-18-blue)
- [go-prompt](https://github.com/c-bata/go-prompt) - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit). ![stars](https://img.shields.io/badge/stars-5327-blue)
- [gocui](https://github.com/jroimartin/gocui) - Minimalist Go library aimed at creating Console User Interfaces. ![stars](https://img.shields.io/badge/stars-10031-blue)
- [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text. ![stars](https://img.shields.io/badge/stars-547-blue)
- [gookit/color](https://github.com/gookit/color) - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows. ![stars](https://img.shields.io/badge/stars-1524-blue)
- [lipgloss](https://github.com/charmbracelet/lipgloss) - Declaratively define styles for color, format and layout in the terminal. ![stars](https://img.shields.io/badge/stars-8438-blue)
- [marker](https://github.com/cyucelen/marker) - Easiest way to match and mark strings for colorful terminal outputs. ![stars](https://img.shields.io/badge/stars-49-blue)
- [mpb](https://github.com/vbauerster/mpb) - Multi progress bar for terminal applications. ![stars](https://img.shields.io/badge/stars-2353-blue)
- [progressbar](https://github.com/schollz/progressbar) - Basic thread-safe progress bar that works in every OS. ![stars](https://img.shields.io/badge/stars-4223-blue)
- [pterm](https://github.com/pterm/pterm) - A library to beautify console output on every platform with many combinable components. ![stars](https://img.shields.io/badge/stars-4933-blue)
- [simpletable](https://github.com/alexeyco/simpletable) - Simple tables in a terminal with Go. ![stars](https://img.shields.io/badge/stars-533-blue)
- [spinner](https://github.com/briandowns/spinner) - Go package to easily provide a terminal spinner with options. ![stars](https://img.shields.io/badge/stars-2385-blue)
- [tabby](https://github.com/cheynewallace/tabby) - A tiny library for super simple Golang tables. ![stars](https://img.shields.io/badge/stars-357-blue)
- [table](https://github.com/tomlazar/table) - Small library for terminal color based tables. ![stars](https://img.shields.io/badge/stars-51-blue)
- [tabular](https://github.com/InVisionApp/tabular) - Print ASCII tables from command line utilities without the need to pass large sets of data to the API. ![stars](https://img.shields.io/badge/stars-78-blue)
- [termbox-go](https://github.com/nsf/termbox-go) - Termbox is a library for creating cross-platform text-based interfaces. ![stars](https://img.shields.io/badge/stars-4690-blue)
- [termdash](https://github.com/mum4k/termdash) - Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui). ![stars](https://img.shields.io/badge/stars-2753-blue)
- [termenv](https://github.com/muesli/termenv) - Advanced ANSI style & color support for your terminal applications. ![stars](https://img.shields.io/badge/stars-1778-blue)
- [termui](https://github.com/gizak/termui) - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib). ![stars](https://img.shields.io/badge/stars-13259-blue)
- [uilive](https://github.com/gosuri/uilive) - Library for updating terminal output in real time. ![stars](https://img.shields.io/badge/stars-1703-blue)
- [uiprogress](https://github.com/gosuri/uiprogress) - Flexible library to render progress bars in terminal applications. ![stars](https://img.shields.io/badge/stars-2119-blue)
- [uitable](https://github.com/gosuri/uitable) - Library to improve readability in terminal apps using tabular data. ![stars](https://img.shields.io/badge/stars-739-blue)
- [yacspin](https://github.com/theckman/yacspin) - Yet Another CLi Spinner package, for working with terminal spinners. ![stars](https://img.shields.io/badge/stars-440-blue)

**[⬆ back to top](#contents)**

### Standard CLI

_Libraries for building standard or basic Command Line applications._

- [acmd](https://github.com/cristalhq/acmd) - Simple, useful, and opinionated CLI package in Go. ![stars](https://img.shields.io/badge/stars-118-blue)
- [argparse](https://github.com/akamensky/argparse) - Command line argument parser inspired by Python's argparse module. ![stars](https://img.shields.io/badge/stars-620-blue)
- [argv](https://github.com/cosiner/argv) - Go library to split command line string as arguments array using the bash syntax. ![stars](https://img.shields.io/badge/stars-41-blue)
- [carapace](https://github.com/rsteube/carapace) - Command argument completion generator for spf13/cobra. ![stars](https://img.shields.io/badge/stars-482-blue)
- [carapace-bin](https://github.com/rsteube/carapace-bin) - Multi-shell multi-command argument completer. ![stars](https://img.shields.io/badge/stars-1042-blue)
- [carapace-spec](https://github.com/rsteube/carapace-spec) - Define simple completions using a spec file. ![stars](https://img.shields.io/badge/stars-20-blue)
- [climax](https://github.com/tucnak/climax) - Alternative CLI with "human face", in spirit of Go command. ![stars](https://img.shields.io/badge/stars-217-blue)
- [clîr](https://github.com/leaanthony/clir) - A Simple and Clear CLI library. Dependency free. ![stars](https://img.shields.io/badge/stars-184-blue)
- [cmd](https://github.com/posener/cmd) - Extends the standard `flag` package to support sub commands and more in idiomatic way. ![stars](https://img.shields.io/badge/stars-41-blue)
- [cmdr](https://github.com/hedzr/cmdr) - A POSIX/GNU style, getopt-like command-line UI Go library. ![stars](https://img.shields.io/badge/stars-136-blue)
- [cobra](https://github.com/spf13/cobra) - Commander for modern Go CLI interactions. ![stars](https://img.shields.io/badge/stars-38850-blue)
- [command-chain](https://github.com/rainu/go-command-chain) - A go library for configure and run command chains - such as pipelining in unix shells. ![stars](https://img.shields.io/badge/stars-64-blue)
- [commandeer](https://github.com/jaffee/commandeer) - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags. ![stars](https://img.shields.io/badge/stars-175-blue)
- [complete](https://github.com/posener/complete) - Write bash completions in Go + Go command bash completion. ![stars](https://img.shields.io/badge/stars-931-blue)
- [console](https://github.com/reeflective/console) Closed-loop application library for Cobra commands, with oh-my-posh prompts, and more. ![stars](https://img.shields.io/badge/stars-77-blue)
- [Dnote](https://github.com/dnote/dnote) - A simple command line notebook with multi-device sync. ![stars](https://img.shields.io/badge/stars-2815-blue)
- [elvish](https://github.com/elves/elvish) - An expressive programming language and a versatile interactive shell. ![stars](https://img.shields.io/badge/stars-5798-blue)
- [env](https://github.com/codingconcepts/env) - Tag-based environment configuration for structs. ![stars](https://img.shields.io/badge/stars-114-blue)
- [flaggy](https://github.com/integrii/flaggy) - A robust and idiomatic flags package with excellent subcommand support. ![stars](https://img.shields.io/badge/stars-860-blue)
- [flagvar](https://github.com/sgreben/flagvar) - A collection of flag argument types for Go's standard `flag` package. ![stars](https://img.shields.io/badge/stars-45-blue)
- [getopt](https://github.com/jon-codes/getopt) - An accurate Go `getopt`, validated against the GNU libc implementation. ![stars](https://img.shields.io/badge/stars-4-blue)
- [go-arg](https://github.com/alexflint/go-arg) - Struct-based argument parsing in Go. ![stars](https://img.shields.io/badge/stars-2062-blue)
- [go-flags](https://github.com/jessevdk/go-flags) - go command line option parser. ![stars](https://img.shields.io/badge/stars-2610-blue)
- [go-getoptions](https://github.com/DavidGamba/go-getoptions) - Go option parser inspired by the flexibility of Perl’s GetOpt::Long. ![stars](https://img.shields.io/badge/stars-57-blue)
- [gocmd](https://github.com/devfacet/gocmd) - Go library for building command line applications. ![stars](https://img.shields.io/badge/stars-66-blue)
- [hashicorp/cli](https://github.com/hashicorp/cli) - Go library for implementing command-line interfaces. ![stars](https://img.shields.io/badge/stars-17-blue)
- [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection. ![stars](https://img.shields.io/badge/stars-180-blue)
- [job](https://github.com/liujianping/job) - JOB, make your short-term command as a long-term job. ![stars](https://img.shields.io/badge/stars-147-blue)
- [kingpin](https://github.com/alecthomas/kingpin) - Command line and flag parser supporting sub commands (superseded by `kong`; see below). ![stars](https://img.shields.io/badge/stars-3520-blue)
- [liner](https://github.com/peterh/liner) - Go readline-like library for command-line interfaces. ![stars](https://img.shields.io/badge/stars-1056-blue)
- [mcli](https://github.com/jxskiss/mcli) - A minimal but very powerful cli library for Go. ![stars](https://img.shields.io/badge/stars-35-blue)
- [mkideal/cli](https://github.com/mkideal/cli) - Feature-rich and easy to use command-line package based on golang struct tags. ![stars](https://img.shields.io/badge/stars-732-blue)
- [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation. ![stars](https://img.shields.io/badge/stars-870-blue)
- [ops](https://github.com/nanovms/ops) - Unikernel Builder/Orchestrator. ![stars](https://img.shields.io/badge/stars-1314-blue)
- [pflag](https://github.com/spf13/pflag) - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags. ![stars](https://img.shields.io/badge/stars-2464-blue)
- [readline](https://github.com/reeflective/readline) Shell library with modern and easy to use UI features. ![stars](https://img.shields.io/badge/stars-94-blue)
- [sand](https://github.com/Zaba505/sand) - Simple API for creating interpreters and so much more. ![stars](https://img.shields.io/badge/stars-27-blue)
- [sflags](https://github.com/octago/sflags) - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin, and other libraries. ![stars](https://img.shields.io/badge/stars-157-blue)
- [strumt](https://github.com/antham/strumt) - Library to create prompt chain. ![stars](https://img.shields.io/badge/stars-62-blue)
- [subcmd](https://github.com/bobg/subcmd) - Another approach to parsing and running subcommands. Works alongside the standard `flag` package. ![stars](https://img.shields.io/badge/stars-8-blue)
- [survey](https://github.com/go-survey/survey) - Build interactive and accessible prompts with full support for windows and posix terminals. ![stars](https://img.shields.io/badge/stars-4102-blue)
- [teris-io/cli](https://github.com/teris-io/cli) - Simple and complete API for building command line interfaces in Go. ![stars](https://img.shields.io/badge/stars-130-blue)
- [ts](https://github.com/liujianping/ts) - Timestamp convert & compare tool. ![stars](https://img.shields.io/badge/stars-20-blue)
- [ukautz/clif](https://github.com/ukautz/clif) - Small command line interface framework. ![stars](https://img.shields.io/badge/stars-129-blue)
- [urfave/cli](https://github.com/urfave/cli) - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli). ![stars](https://img.shields.io/badge/stars-22614-blue)
- [version](https://github.com/mszostok/version) - Collects and displays CLI version information in multiple formats along with upgrade notice. ![stars](https://img.shields.io/badge/stars-103-blue)
- [wlog](https://github.com/dixonwille/wlog) - Simple logging interface that supports cross-platform color and concurrency. ![stars](https://img.shields.io/badge/stars-66-blue)
- [wmenu](https://github.com/dixonwille/wmenu) - Easy to use menu structure for cli applications that prompt users to make choices. ![stars](https://img.shields.io/badge/stars-220-blue)

**[⬆ back to top](#contents)**

## Configuration

_Libraries for configuration parsing._

- [aconfig](https://github.com/cristalhq/aconfig) - Simple, useful and opinionated config loader. ![stars](https://img.shields.io/badge/stars-557-blue)
- [bcl](https://github.com/wkhere/bcl) - BCL is a configuration language similar to HCL. ![stars](https://img.shields.io/badge/stars-20-blue)
- [cleanenv](https://github.com/ilyakaznacheev/cleanenv) - Minimalistic configuration reader (from files, ENV, and wherever you want). ![stars](https://img.shields.io/badge/stars-1708-blue)
- [config](https://github.com/JeremyLoy/config) - Cloud native application configuration. Bind ENV to structs in only two lines. ![stars](https://img.shields.io/badge/stars-336-blue)
- [config](https://github.com/num30/config) - configure your app using file, environment variables, or flags in two lines of code ![stars](https://img.shields.io/badge/stars-52-blue)
- [configuration](https://github.com/BoRuDar/configuration) - Library for initializing configuration structs from env variables, files, flags and 'default' tag. ![stars](https://img.shields.io/badge/stars-109-blue)
- [configure](https://github.com/paked/configure) - Provides configuration through multiple sources, including JSON, flags and environment variables. ![stars](https://img.shields.io/badge/stars-56-blue)
- [configuro](https://github.com/sherifabdlnaby/configuro) - opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications. ![stars](https://img.shields.io/badge/stars-95-blue)
- [confiq](https://github.com/greencoda/confiq) - Structured data format to config struct decoder library for Go - supporting multiple data formats ![stars](https://img.shields.io/badge/stars-35-blue)
- [confita](https://github.com/heetch/confita) - Load configuration in cascade from multiple backends into a struct. ![stars](https://img.shields.io/badge/stars-496-blue)
- [conflate](https://github.com/the4thamigo-uk/conflate) - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema. ![stars](https://img.shields.io/badge/stars-34-blue)
- [env](https://github.com/caarlos0/env) - Parse environment variables to Go structs (with defaults). ![stars](https://img.shields.io/badge/stars-5068-blue)
- [env](https://github.com/junk1tm/env) - A lightweight package for loading environment variables into structs. ![stars](https://img.shields.io/badge/stars-67-blue)
- [env](https://github.com/syntaqx/env) - An environment utility package with support for unmarshaling into structs ![stars](https://img.shields.io/badge/stars-6-blue)
- [envconfig](https://github.com/vrischmann/envconfig) - Read your configuration from environment variables. ![stars](https://img.shields.io/badge/stars-241-blue)
- [envh](https://github.com/antham/envh) - Helpers to manage environment variables. ![stars](https://img.shields.io/badge/stars-99-blue)
- [envyaml](https://github.com/yuseferi/envyaml) - Yaml with environment variables reader. it helps to have secrets as environment variable but load them configs as structured Yaml. ![stars](https://img.shields.io/badge/stars-11-blue)
- [fig](https://github.com/kkyr/fig) - Tiny library for reading configuration from a file and from environment variables (with validation & defaults). ![stars](https://img.shields.io/badge/stars-381-blue)
- [genv](https://github.com/sakirsensoy/genv) - Read environment variables easily with dotenv support. ![stars](https://img.shields.io/badge/stars-41-blue)
- [go-array](https://github.com/deatil/go-array) - A Go package that read or set data from map, slice or json. ![stars](https://img.shields.io/badge/stars-20-blue)
- [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) - Go package that fetches parameters from AWS System Manager - Parameter Store. ![stars](https://img.shields.io/badge/stars-60-blue)
- [go-cfg](https://github.com/dsbasko/go-cfg) - The library provides a unified way to read configuration data into a structure from various sources, such as env, flags, and configuration files (.json, .yaml, .toml, .env). ![stars](https://img.shields.io/badge/stars-43-blue)
- [go-conf](https://github.com/ThomasObenaus/go-conf) - Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters. ![stars](https://img.shields.io/badge/stars-11-blue)
- [go-ini](https://github.com/subpop/go-ini) - A Go package that marshals and unmarshals INI-files. ![stars](https://img.shields.io/badge/stars-14-blue)
- [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) - Go utility for loading configuration parameters from AWS SSM (Parameter Store). ![stars](https://img.shields.io/badge/stars-22-blue)
- [go-up](https://github.com/ufoscout/go-up) - A simple configuration library with recursive placeholders resolution and no magic. ![stars](https://img.shields.io/badge/stars-43-blue)
- [GoCfg](https://github.com/Jagerente/gocfg) - Config manager with Struct Tags based contracts, custom value providers, parsers, and documentation generation. Customizable yet simple. ![stars](https://img.shields.io/badge/stars-6-blue)
- [godotenv](https://github.com/joho/godotenv) - Go port of Ruby's dotenv library (Loads environment variables from `.env`). ![stars](https://img.shields.io/badge/stars-8655-blue)
- [gofigure](https://github.com/ian-kent/gofigure) - Go application configuration made easy. ![stars](https://img.shields.io/badge/stars-68-blue)
- [GoLobby/Config](https://github.com/golobby/config) - GoLobby Config is a lightweight yet powerful configuration manager for the Go programming language. ![stars](https://img.shields.io/badge/stars-364-blue)
- [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep your config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization. ![stars](https://img.shields.io/badge/stars-50-blue)
- [gonfig](https://github.com/milad-abbasi/gonfig) - Tag-based configuration parser which loads values from different providers into typesafe struct. ![stars](https://img.shields.io/badge/stars-9-blue)
- [gookit/config](https://github.com/gookit/config) - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge. ![stars](https://img.shields.io/badge/stars-544-blue)
- [harvester](https://github.com/beatlabs/harvester) - Harvester, a easy to use static and dynamic configuration package supporting seeding, env vars and Consul integration. ![stars](https://img.shields.io/badge/stars-132-blue)
- [hedzr/store](https://github.com/hedzr/store) - Extensible, high-performance configuration management library, optimized for hierarchical data. ![stars](https://img.shields.io/badge/stars-5-blue)
- [hjson](https://github.com/hjson/hjson-go) - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments. ![stars](https://img.shields.io/badge/stars-334-blue)
- [hocon](https://github.com/gurkankaymak/hocon) - Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files. ![stars](https://img.shields.io/badge/stars-79-blue)
- [ingo](https://github.com/schachmat/ingo) - Flags persisted in an ini-like config file. ![stars](https://img.shields.io/badge/stars-38-blue)
- [ini](https://github.com/go-ini/ini) - Go package to read and write INI files. ![stars](https://img.shields.io/badge/stars-3476-blue)
- [ini](https://github.com/wlevene/ini) - INI Parser & Write Library, Unmarshal to Struct, Marshal to Json, Write File, watch file. ![stars](https://img.shields.io/badge/stars-15-blue)
- [joshbetz/config](https://github.com/joshbetz/config) - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP. ![stars](https://img.shields.io/badge/stars-215-blue)
- [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) - Go library for managing configuration data from environment variables. ![stars](https://img.shields.io/badge/stars-5112-blue)
- [koanf](https://github.com/knadh/koanf) - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line. ![stars](https://img.shields.io/badge/stars-2936-blue)
- [konf](https://github.com/nil-go/konf) - The simplest API for reading/watching config from file, env, flag and clouds (e.g. AWS, Azure, GCP). ![stars](https://img.shields.io/badge/stars-268-blue)
- [konfig](https://github.com/lalamove/konfig) - Composable, observable and performant config handling for Go for the distributed processing era. ![stars](https://img.shields.io/badge/stars-646-blue)
- [kong](https://github.com/alecthomas/kong) - Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (successor to `kingpin`). ![stars](https://img.shields.io/badge/stars-2274-blue)
- [mini](https://github.com/sasbury/mini) - Golang package for parsing ini-style configuration files. ![stars](https://img.shields.io/badge/stars-35-blue)
- [nasermirzaei89/env](https://github.com/nasermirzaei89/env) - Simple useful package for read environment variables. ![stars](https://img.shields.io/badge/stars-18-blue)
- [nfigure](https://github.com/muir/nfigure) - Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML ![stars](https://img.shields.io/badge/stars-8-blue)
- [onion](https://github.com/goraz/onion) - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP. ![stars](https://img.shields.io/badge/stars-118-blue)
- [piper](https://github.com/Yiling-J/piper) - Viper wrapper with config inheritance and key generation. ![stars](https://img.shields.io/badge/stars-8-blue)
- [sonic](https://github.com/bytedance/sonic) - A blazingly fast JSON serializing & deserializing library. ![stars](https://img.shields.io/badge/stars-7218-blue)
- [store](https://github.com/tucnak/store) - Lightweight configuration manager for Go. ![stars](https://img.shields.io/badge/stars-274-blue)
- [swap](https://github.com/oblq/swap) - Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env). ![stars](https://img.shields.io/badge/stars-8-blue)
- [typenv](https://github.com/diegomarangoni/typenv) - Minimalistic, zero dependency, typed environment variables library. ![stars](https://img.shields.io/badge/stars-9-blue)
- [uConfig](https://github.com/omeid/uconfig) - Lightweight, zero-dependency, and extendable configuration management. ![stars](https://img.shields.io/badge/stars-69-blue)
- [viper](https://github.com/spf13/viper) - Go configuration with fangs. ![stars](https://img.shields.io/badge/stars-27619-blue)
- [xdg](https://github.com/adrg/xdg) - Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/latest/) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories). ![stars](https://img.shields.io/badge/stars-741-blue)
- [xdg](https://github.com/OpenPeeDeeP/xdg) - Cross platform package that follows the [XDG Standard](https://specifications.freedesktop.org/basedir-spec/latest/). ![stars](https://img.shields.io/badge/stars-80-blue)
- [yamagiconf](https://github.com/romshark/yamagiconf) - The "safe subset" of YAML for Go configs. ![stars](https://img.shields.io/badge/stars-18-blue)

**[⬆ back to top](#contents)**

## Continuous Integration

_Tools for help with continuous integration._

- [abstruse](https://github.com/bleenco/abstruse) - Abstruse is a distributed CI platform. ![stars](https://img.shields.io/badge/stars-943-blue)
- [Bencher](https://bencher.dev/) - A suite of continuous benchmarking tools designed to catch performance regressions in CI.
- [CDS](https://github.com/ovh/cds) - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform. ![stars](https://img.shields.io/badge/stars-4634-blue)
- [dot](https://github.com/opnlabs/dot) - A minimal, local first continuous integration system that uses Docker to run jobs concurrently in stages. ![stars](https://img.shields.io/badge/stars-24-blue)
- [drone](https://github.com/drone/drone) - Drone is a Continuous Integration platform built on Docker, written in Go. ![stars](https://img.shields.io/badge/stars-32369-blue)
- [go-beautiful-html-coverage](https://github.com/gha-common/go-beautiful-html-coverage) - A GitHub Action to track code coverage in your pull requests, with a beautiful HTML preview, for free. ![stars](https://img.shields.io/badge/stars-14-blue)
- [go-fuzz-action](https://github.com/jidicula/go-fuzz-action) - Use Go 1.18's built-in fuzz testing in GitHub Actions. ![stars](https://img.shields.io/badge/stars-15-blue)
- [go-semver-release](https://github.com/s0ders/go-semver-release) - Automate the semantic versioning of Git repositories. ![stars](https://img.shields.io/badge/stars-10-blue)
- [go-test-coverage](https://github.com/vladopajic/go-test-coverage) - Tool and GitHub action which reports issues when test coverage is below set threshold. ![stars](https://img.shields.io/badge/stars-116-blue)
- [gomason](https://github.com/nikogura/gomason) - Test, Build, Sign, and Publish your go binaries from a clean workspace. ![stars](https://img.shields.io/badge/stars-66-blue)
- [gotestfmt](https://github.com/GoTestTools/gotestfmt) - go test output for humans. ![stars](https://img.shields.io/badge/stars-524-blue)
- [goveralls](https://github.com/mattn/goveralls) - Go integration for Coveralls.io continuous code coverage tracking system. ![stars](https://img.shields.io/badge/stars-787-blue)
- [muffet](https://github.com/raviqqe/muffet) - Fast website link checker in Go, see [alternatives](https://github.com/lycheeverse/lychee#features). ![stars](https://img.shields.io/badge/stars-2527-blue)
- [overalls](https://github.com/go-playground/overalls) - Multi-Package go project coverprofile for tools like goveralls. ![stars](https://img.shields.io/badge/stars-115-blue)
- [roveralls](https://github.com/LawrenceWoodman/roveralls) - Recursive coverage testing tool. ![stars](https://img.shields.io/badge/stars-20-blue)
- [woodpecker](https://github.com/woodpecker-ci/woodpecker) - Woodpecker is a community fork of the Drone CI system. ![stars](https://img.shields.io/badge/stars-4492-blue)

**[⬆ back to top](#contents)**

## CSS Preprocessors

_Libraries for preprocessing CSS files._

- [gcss](https://github.com/yosssi/gcss) - Pure Go CSS Preprocessor. ![stars](https://img.shields.io/badge/stars-497-blue)
- [go-libsass](https://github.com/wellington/go-libsass) - Go wrapper to the 100% Sass compatible libsass project. ![stars](https://img.shields.io/badge/stars-206-blue)

**[⬆ back to top](#contents)**

## Data Integration Frameworks

_Frameworks for performing ELT / ETL_

- [Benthos](https://github.com/benthosdev/benthos) - A message streaming bridge between a range of protocols. ![stars](https://img.shields.io/badge/stars-8194-blue)
- [CloudQuery](http://github.com/cloudquery/cloudquery) - A high-performance ELT data integration framework with pluggable architecture.
- [omniparser](https://github.com/jf-tech/omniparser) - A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema. ![stars](https://img.shields.io/badge/stars-993-blue)

**[⬆ back to top](#contents)**

## Data Structures and Algorithms

### Bit-packing and Compression

- [bingo](https://github.com/iancmcc/bingo) - Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes. ![stars](https://img.shields.io/badge/stars-41-blue)
- [binpacker](https://github.com/zhuangsirui/binpacker) - Binary packer and unpacker helps user build custom binary stream. ![stars](https://img.shields.io/badge/stars-223-blue)
- [bit](https://github.com/yourbasic/bit) - Golang set data structure with bonus bit-twiddling functions. ![stars](https://img.shields.io/badge/stars-160-blue)
- [crunch](https://github.com/superwhiskers/crunch) - Go package implementing buffers for handling various datatypes easily. ![stars](https://img.shields.io/badge/stars-99-blue)
- [go-ef](https://github.com/amallia/go-ef) - A Go implementation of the Elias-Fano encoding. ![stars](https://img.shields.io/badge/stars-33-blue)
- [roaring](https://github.com/RoaringBitmap/roaring) - Go package implementing compressed bitsets. ![stars](https://img.shields.io/badge/stars-2588-blue)

### Bit Sets

- [bitmap](https://github.com/kelindar/bitmap) - Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go. ![stars](https://img.shields.io/badge/stars-318-blue)
- [bitset](https://github.com/bits-and-blooms/bitset) - Go package implementing bitsets. ![stars](https://img.shields.io/badge/stars-1376-blue)

### Bloom and Cuckoo Filters

- [bloom](https://github.com/bits-and-blooms/bloom) - Go package implementing Bloom filters. ![stars](https://img.shields.io/badge/stars-2487-blue)
- [bloom](https://github.com/zhenjl/bloom) - Bloom filters implemented in Go. ![stars](https://img.shields.io/badge/stars-146-blue)
- [bloom](https://github.com/yourbasic/bloom) - Golang Bloom filter implementation. ![stars](https://img.shields.io/badge/stars-86-blue)
- [bloomfilter](https://github.com/OldPanda/bloomfilter) - Yet another Bloomfilter implementation in Go, compatible with Java's Guava library. ![stars](https://img.shields.io/badge/stars-17-blue)
- [boomfilters](https://github.com/tylertreat/BoomFilters) - Probabilistic data structures for processing continuous, unbounded streams. ![stars](https://img.shields.io/badge/stars-1596-blue)
- [cuckoo-filter](https://github.com/linvon/cuckoo-filter) - Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper are available. ![stars](https://img.shields.io/badge/stars-297-blue)
- [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go. ![stars](https://img.shields.io/badge/stars-1152-blue)
- [ring](https://github.com/TheTannerRyan/ring) - Go implementation of a high performance, thread safe bloom filter. ![stars](https://img.shields.io/badge/stars-138-blue)

### Data Structure and Algorithm Collections

- [algorithms](https://github.com/shady831213/algorithms) - Algorithms and data structures.CLRS study. ![stars](https://img.shields.io/badge/stars-812-blue)
- [go-datastructures](https://github.com/Workiva/go-datastructures) - Collection of useful, performant, and thread-safe data structures. ![stars](https://img.shields.io/badge/stars-7722-blue)
- [gods](https://github.com/emirpasic/gods) - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc. ![stars](https://img.shields.io/badge/stars-16574-blue)
- [gostl](https://github.com/liyue201/gostl) - Data structure and algorithm library for go, designed to provide functions similar to C++ STL. ![stars](https://img.shields.io/badge/stars-1067-blue)

### Iterators

- [goterator](https://github.com/yaa110/goterator) - Iterator implementation to provide map and reduce functionalities. ![stars](https://img.shields.io/badge/stars-16-blue)
- [iter](https://github.com/disksing/iter) - Go implementation of C++ STL iterators and algorithms. ![stars](https://img.shields.io/badge/stars-187-blue)

### Maps

See also [Database](#database) for more complex key-value stores, and [Trees](#trees) for
additional ordered map implementations.

- [cmap](https://github.com/lrita/cmap) - a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards. ![stars](https://img.shields.io/badge/stars-92-blue)
- [dict](https://github.com/srfrog/dict) - Python-like dictionaries (dict) for Go. ![stars](https://img.shields.io/badge/stars-45-blue)
- [go-shelve](https://github.com/lucmq/go-shelve) - A persistent, map-like object for the Go programming language. Supports multiple embedded key-value stores. ![stars](https://img.shields.io/badge/stars-8-blue)
- [goradd/maps](https://github.com/goradd/maps) - Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc. ![stars](https://img.shields.io/badge/stars-47-blue)

### Miscellaneous Data Structures and Algorithms

- [concurrent-writer](https://github.com/free/concurrent-writer) - Highly concurrent drop-in replacement for `bufio.Writer`. ![stars](https://img.shields.io/badge/stars-55-blue)
- [conjungo](https://github.com/InVisionApp/conjungo) - A small, powerful and flexible merge library. ![stars](https://img.shields.io/badge/stars-127-blue)
- [count-min-log](https://github.com/seiflotfy/count-min-log) - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory). ![stars](https://img.shields.io/badge/stars-66-blue)
- [fsm](https://github.com/cocoonspace/fsm) - Finite-State Machine package. ![stars](https://img.shields.io/badge/stars-68-blue)
- [genfuncs](https://github.com/nwillc/genfuncs) - Go 1.18+ generics package inspired by Kotlin's Sequence and Map. ![stars](https://img.shields.io/badge/stars-51-blue)
- [go-generics](https://github.com/bobg/go-generics) - Generic slice, map, set, iterator, and goroutine utilities. ![stars](https://img.shields.io/badge/stars-76-blue)
- [go-geoindex](https://github.com/hailocab/go-geoindex) - In-memory geo index. ![stars](https://img.shields.io/badge/stars-357-blue)
- [go-rampart](https://github.com/francesconi/go-rampart) - Determine how intervals relate to each other. ![stars](https://img.shields.io/badge/stars-101-blue)
- [go-rquad](https://github.com/aurelien-rainone/go-rquad) - Region quadtrees with efficient point location and neighbour finding. ![stars](https://img.shields.io/badge/stars-134-blue)
- [go-tuple](https://github.com/barweiss/go-tuple) - Generic tuple implementation for Go 1.18+. ![stars](https://img.shields.io/badge/stars-82-blue)
- [go18ds](https://github.com/daichi-m/go18ds) - Go Data Structures using Go 1.18 generics. ![stars](https://img.shields.io/badge/stars-47-blue)
- [gofal](https://github.com/xxjwxc/gofal) - fractional api for Go. ![stars](https://img.shields.io/badge/stars-19-blue)
- [gogu](https://github.com/esimov/gogu) - A comprehensive, reusable and efficient concurrent-safe generics utility functions and data structures library. ![stars](https://img.shields.io/badge/stars-101-blue)
- [gota](https://github.com/kniren/gota) - Implementation of dataframes, series, and data wrangling methods for Go. ![stars](https://img.shields.io/badge/stars-3101-blue)
- [hide](https://github.com/emvi/hide) - ID type with marshalling to/from hash to prevent sending IDs to clients. ![stars](https://img.shields.io/badge/stars-69-blue)
- [hilbert](https://github.com/google/hilbert) - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves. ![stars](https://img.shields.io/badge/stars-279-blue)
- [hyperloglog](https://github.com/axiomhq/hyperloglog) - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction. ![stars](https://img.shields.io/badge/stars-950-blue)
- [quadtree](https://github.com/s0rg/quadtree) - Generic, zero-alloc, 100%-test covered quadtree. ![stars](https://img.shields.io/badge/stars-37-blue)
- [slices](https://github.com/srfrog/slices) - Functions that operate on slices; like `package strings` but adapted to work with slices. ![stars](https://img.shields.io/badge/stars-17-blue)
- [slices](https://github.com/twharmon/slices) - Pure, generic functions for slices. ![stars](https://img.shields.io/badge/stars-20-blue)

### Nullable Types

- [nan](https://github.com/kak-tus/nan) - Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers. ![stars](https://img.shields.io/badge/stars-85-blue)
- [null](https://github.com/emvi/null) - Nullable Go types that can be marshalled/unmarshalled to/from JSON. ![stars](https://img.shields.io/badge/stars-37-blue)
- [typ](https://github.com/gurukami/typ) - Null Types, Safe primitive type conversion and fetching value from complex structures. ![stars](https://img.shields.io/badge/stars-46-blue)

### Queues

- [deque](https://github.com/edwingeng/deque) - A highly optimized double-ended queue. ![stars](https://img.shields.io/badge/stars-188-blue)
- [deque](https://github.com/gammazero/deque) - Fast ring-buffer deque (double-ended queue). ![stars](https://img.shields.io/badge/stars-635-blue)
- [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) - Concurrent FIFO queue. ![stars](https://img.shields.io/badge/stars-412-blue)
- [hatchet](https://github.com/hatchet-dev/hatchet) - Distributed, Fault-tolerant task queue. ![stars](https://img.shields.io/badge/stars-4450-blue)
- [memlog](https://github.com/embano1/memlog) - An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka. ![stars](https://img.shields.io/badge/stars-129-blue)
- [queue](https://github.com/adrianbrad/queue) - Multiple thread-safe, generic queue implementations for Go. ![stars](https://img.shields.io/badge/stars-280-blue)

### Sets

- [dsu](https://github.com/ihebu/dsu) - Disjoint Set data structure implementation in Go. ![stars](https://img.shields.io/badge/stars-15-blue)
- [golang-set](https://github.com/deckarep/golang-set) - Thread-Safe and Non-Thread-Safe high-performance sets for Go. ![stars](https://img.shields.io/badge/stars-4326-blue)
- [goset](https://github.com/zoumo/goset) - A useful Set collection implementation for Go. ![stars](https://img.shields.io/badge/stars-52-blue)
- [set](https://github.com/StudioSol/set) - Simple set data structure implementation in Go using LinkedHashMap. ![stars](https://img.shields.io/badge/stars-27-blue)

### Text Analysis

- [bleve](https://github.com/blevesearch/bleve) - Modern text indexing library for go. ![stars](https://img.shields.io/badge/stars-10184-blue)
- [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) - Go implementation of Adaptive Radix Tree. ![stars](https://img.shields.io/badge/stars-380-blue)
- [go-edlib](https://github.com/hbollon/go-edlib) - Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode. ![stars](https://img.shields.io/badge/stars-494-blue)
- [levenshtein](https://github.com/agext/levenshtein) - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix. ![stars](https://img.shields.io/badge/stars-86-blue)
- [levenshtein](https://github.com/agnivade/levenshtein) - Implementation to calculate levenshtein distance in Go. ![stars](https://img.shields.io/badge/stars-370-blue)
- [mspm](https://github.com/BlackRabbitt/mspm) - Multi-String Pattern Matching Algorithm for information retrieval. ![stars](https://img.shields.io/badge/stars-25-blue)
- [parsefields](https://github.com/MonaxGT/parsefields) - Tools for parse JSON-like logs for collecting unique fields and events. ![stars](https://img.shields.io/badge/stars-7-blue)
- [ptrie](https://github.com/viant/ptrie) - An implementation of prefix tree. ![stars](https://img.shields.io/badge/stars-41-blue)
- [trie](https://github.com/derekparker/trie) - Trie implementation in Go. ![stars](https://img.shields.io/badge/stars-766-blue)

### Trees

- [hashsplit](http://github.com/bobg/hashsplit) - Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position.
- [merkle](https://github.com/bobg/merkle) - Space-efficient computation of Merkle root hashes and inclusion proofs. ![stars](https://img.shields.io/badge/stars-19-blue)
- [skiplist](https://github.com/MauriceGit/skiplist) - Very fast Go Skiplist implementation. ![stars](https://img.shields.io/badge/stars-282-blue)
- [skiplist](https://github.com/gansidui/skiplist) - Skiplist implementation in Go. ![stars](https://img.shields.io/badge/stars-84-blue)
- [treap](https://github.com/perdata/treap) - Persistent, fast ordered map using tree heaps. ![stars](https://img.shields.io/badge/stars-27-blue)
- [treemap](https://github.com/igrmk/treemap) - Generic key-sorted map using a red-black tree under the hood. ![stars](https://img.shields.io/badge/stars-62-blue)

### Pipes

- [ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) - Go module that processes work concurrently and returns output in a channel in the order of input. ![stars](https://img.shields.io/badge/stars-40-blue)
- [parapipe](https://github.com/nazar256/parapipe) - FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results. ![stars](https://img.shields.io/badge/stars-33-blue)
- [pipeline](https://github.com/hyfather/pipeline) - An implementation of pipelines with fan-in and fan-out. ![stars](https://img.shields.io/badge/stars-56-blue)

**[⬆ back to top](#contents)**

## Database

### Caches

_Data stores with expiring records, in-memory distributed data stores, or in-memory subsets of file-based databases._

- [2q](https://github.com/floatdrop/2q) - 2Q in-memory cache implementation. ![stars](https://img.shields.io/badge/stars-42-blue)
- [bcache](https://github.com/iwanbk/bcache) - Eventually consistent distributed in-memory cache Go library. ![stars](https://img.shields.io/badge/stars-157-blue)
- [BigCache](https://github.com/allegro/bigcache) - Efficient key/value cache for gigabytes of data. ![stars](https://img.shields.io/badge/stars-7652-blue)
- [cache](https://github.com/akyoto/cache) - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage. ![stars](https://img.shields.io/badge/stars-188-blue)
- [cache2go](https://github.com/muesli/cache2go) - In-memory key:value cache which supports automatic invalidation based on timeouts. ![stars](https://img.shields.io/badge/stars-2135-blue)
- [cachego](https://github.com/faabiosr/cachego) - Golang Cache component for multiple drivers. ![stars](https://img.shields.io/badge/stars-369-blue)
- [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) - BigCache with clustering support and individual item expiration. ![stars](https://img.shields.io/badge/stars-45-blue)
- [coherence-go-client](https://github.com/oracle/coherence-go-client) - Full implementation of Oracle Coherence cache API for Go applications using gRPC as network transport. ![stars](https://img.shields.io/badge/stars-10-blue)
- [couchcache](https://github.com/codingsince1985/couchcache) - RESTful caching micro-service backed by Couchbase server. ![stars](https://img.shields.io/badge/stars-64-blue)
- [EchoVault](https://github.com/EchoVault/EchoVault) - Embeddable Distributed in-memory data store compatible with Redis clients. ![stars](https://img.shields.io/badge/stars-436-blue)
- [fastcache](https://github.com/VictoriaMetrics/fastcache) - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead. ![stars](https://img.shields.io/badge/stars-2163-blue)
- [GCache](https://github.com/bluele/gcache) - Cache library with support for expirable Cache, LFU, LRU and ARC. ![stars](https://img.shields.io/badge/stars-2628-blue)
- [gdcache](https://github.com/ulovecode/gdcache) - A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache. ![stars](https://img.shields.io/badge/stars-13-blue)
- [go-cache](https://github.com/viney-shih/go-cache) - A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern. ![stars](https://img.shields.io/badge/stars-142-blue)
- [go-freelru](https://github.com/elastic/go-freelru) A GC-less, fast and generic LRU hashmap library with optional locking, sharding, eviction and expiration. ![stars](https://img.shields.io/badge/stars-219-blue)
- [go-mcache](https://github.com/OrlovEvgeny/go-mcache) - Fast in-memory key:value store/cache library. Pointer caches. ![stars](https://img.shields.io/badge/stars-97-blue)
- [gocache](https://github.com/eko/gocache) - A complete Go cache library with multiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more. ![stars](https://img.shields.io/badge/stars-2532-blue)
- [gocache](https://github.com/yuseferi/gocache) - A data race free Go ache library with high performance and auto pruge functionality ![stars](https://img.shields.io/badge/stars-9-blue)
- [groupcache](https://github.com/golang/groupcache) - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases. ![stars](https://img.shields.io/badge/stars-13031-blue)
- [icache](https://github.com/mdaliyan/icache) - A High Performance, Generic, thread-safe, zero-dependency cache package. ![stars](https://img.shields.io/badge/stars-19-blue)
- [imcache](https://github.com/erni27/imcache) - A generic in-memory cache Go library. It supports expiration, sliding expiration, max entries limit, eviction callbacks and sharding. ![stars](https://img.shields.io/badge/stars-123-blue)
- [nscache](https://github.com/no-src/nscache) - A Go caching framework that supports multiple data source drivers. ![stars](https://img.shields.io/badge/stars-11-blue)
- [otter](https://github.com/maypok86/otter) - A high performance lockless cache for Go. Many times faster than Ristretto and friends. ![stars](https://img.shields.io/badge/stars-1803-blue)
- [pocache](https://github.com/naughtygopher/pocache) - Pocache is a minimal cache package which focuses on a preemptive optimistic caching strategy. ![stars](https://img.shields.io/badge/stars-216-blue)
- [sturdyc](https://github.com/viccon/sturdyc) - A caching library with advanced concurrency features designed to make I/O heavy applications robust and highly performant. ![stars](https://img.shields.io/badge/stars-601-blue)
- [theine](https://github.com/Yiling-J/theine-go) - High performance, near optimal in-memory cache with proactive TTL expiration and generics. ![stars](https://img.shields.io/badge/stars-284-blue)
- [timedmap](https://github.com/zekroTJA/timedmap) - Map with expiring key-value pairs. ![stars](https://img.shields.io/badge/stars-72-blue)
- [ttlcache](https://github.com/jellydator/ttlcache) - An in-memory cache with item expiration and generics. ![stars](https://img.shields.io/badge/stars-983-blue)
- [ttlcache](https://github.com/cheshir/ttlcache) - In-memory key value storage with TTL for each record. ![stars](https://img.shields.io/badge/stars-10-blue)

### Databases Implemented in Go

- [badger](https://github.com/dgraph-io/badger) - Fast key-value store in Go. ![stars](https://img.shields.io/badge/stars-14171-blue)
- [bbolt](https://github.com/etcd-io/bbolt) - An embedded key/value database for Go. ![stars](https://img.shields.io/badge/stars-8433-blue)
- [Bitcask](https://git.mills.io/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).
- [buntdb](https://github.com/tidwall/buntdb) - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support. ![stars](https://img.shields.io/badge/stars-4623-blue)
- [clover](https://github.com/ostafen/clover) - A lightweight document-oriented NoSQL database written in pure Golang. ![stars](https://img.shields.io/badge/stars-714-blue)
- [cockroach](https://github.com/cockroachdb/cockroach) - Scalable, Geo-Replicated, Transactional Datastore. ![stars](https://img.shields.io/badge/stars-30393-blue)
- [Coffer](https://github.com/claygod/coffer) - Simple ACID key-value database that supports transactions. ![stars](https://img.shields.io/badge/stars-40-blue)
- [column](https://github.com/kelindar/column) - High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions. ![stars](https://img.shields.io/badge/stars-1450-blue)
- [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) - CovenantSQL is a SQL database on blockchain. ![stars](https://img.shields.io/badge/stars-1503-blue)
- [Databunker](https://github.com/paranoidguy/databunker) - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA. ![stars](https://img.shields.io/badge/stars-1269-blue)
- [dgraph](https://github.com/dgraph-io/dgraph) - Scalable, Distributed, Low Latency, High Throughput Graph Database. ![stars](https://img.shields.io/badge/stars-20580-blue)
- [diskv](https://github.com/peterbourgon/diskv) - Home-grown disk-backed key-value store. ![stars](https://img.shields.io/badge/stars-1411-blue)
- [dolt](https://github.com/dolthub/dolt) - Dolt – It's Git for Data. ![stars](https://img.shields.io/badge/stars-18148-blue)
- [eliasdb](https://github.com/krotik/eliasdb) - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language. ![stars](https://img.shields.io/badge/stars-1012-blue)
- [godis](https://github.com/hdt3213/godis) - A Golang implemented high-performance Redis server and cluster. ![stars](https://img.shields.io/badge/stars-3568-blue)
- [goleveldb](https://github.com/syndtr/goleveldb) - Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go. ![stars](https://img.shields.io/badge/stars-6197-blue)
- [hare](https://github.com/jameycribbs/hare) - A simple database management system that stores each table as a text file of line-delimited JSON. ![stars](https://img.shields.io/badge/stars-95-blue)
- [immudb](https://github.com/codenotary/immudb) - immudb is a lightweight, high-speed immutable database for systems and applications written in Go. ![stars](https://img.shields.io/badge/stars-8669-blue)
- [influxdb](https://github.com/influxdb/influxdb) - Scalable datastore for metrics, events, and real-time analytics. ![stars](https://img.shields.io/badge/stars-29309-blue)
- [ledisdb](https://github.com/siddontang/ledisdb) - Ledisdb is a high performance NoSQL like Redis based on LevelDB. ![stars](https://img.shields.io/badge/stars-4104-blue)
- [levigo](https://github.com/jmhodges/levigo) - Levigo is a Go wrapper for LevelDB. ![stars](https://img.shields.io/badge/stars-415-blue)
- [libradb](https://github.com/amit-davidson/LibraDB) - LibraDB is a simple database with less than 1000 lines of code for learning. ![stars](https://img.shields.io/badge/stars-172-blue)
- [LinDB](https://github.com/lindb/lindb) - LinDB is a scalable, high performance, high availability distributed time series database. ![stars](https://img.shields.io/badge/stars-3017-blue)
- [lotusdb](https://github.com/flower-corp/lotusdb) - Fast k/v database compatible with lsm and b+tree. ![stars](https://img.shields.io/badge/stars-2110-blue)
- [Milvus](https://github.com/milvus-io/milvus) - Milvus is a vector database for embedding management, analytics and search. ![stars](https://img.shields.io/badge/stars-31799-blue)
- [moss](https://github.com/couchbase/moss) - Moss is a simple LSM key-value storage engine written in 100% Go. ![stars](https://img.shields.io/badge/stars-994-blue)
- [nutsdb](https://github.com/xujiajun/nutsdb) - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set. ![stars](https://img.shields.io/badge/stars-3434-blue)
- [objectbox-go](https://github.com/objectbox/objectbox-go) - High-performance embedded Object Database (NoSQL) with Go API. ![stars](https://img.shields.io/badge/stars-1114-blue)
- [pebble](https://github.com/cockroachdb/pebble) - RocksDB/LevelDB inspired key-value database in Go. ![stars](https://img.shields.io/badge/stars-5083-blue)
- [piladb](https://github.com/fern4lvarez/piladb) - Lightweight RESTful database engine based on stack data structures. ![stars](https://img.shields.io/badge/stars-206-blue)
- [pogreb](https://github.com/akrylysov/pogreb) - Embedded key-value store for read-heavy workloads. ![stars](https://img.shields.io/badge/stars-1318-blue)
- [prometheus](https://github.com/prometheus/prometheus) - Monitoring system and time series database. ![stars](https://img.shields.io/badge/stars-56817-blue)
- [pudge](https://github.com/recoilme/pudge) - Fast and simple key/value store written using Go's standard library. ![stars](https://img.shields.io/badge/stars-370-blue)
- [redka](https://github.com/nalgeon/redka) - Redis re-implemented with SQLite. ![stars](https://img.shields.io/badge/stars-3577-blue)
- [rosedb](https://github.com/roseduan/rosedb) - An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset. ![stars](https://img.shields.io/badge/stars-4671-blue)
- [rotom](https://github.com/xgzlucario/rotom) - A tiny Redis server built with Golang, compatible with RESP protocols. ![stars](https://img.shields.io/badge/stars-41-blue)
- [rqlite](https://github.com/rqlite/rqlite) - The lightweight, distributed, relational database built on SQLite. ![stars](https://img.shields.io/badge/stars-16007-blue)
- [tempdb](https://github.com/rafaeljesus/tempdb) - Key-value store for temporary items. ![stars](https://img.shields.io/badge/stars-19-blue)
- [tidb](https://github.com/pingcap/tidb) - TiDB is a distributed SQL database. Inspired by the design of Google F1. ![stars](https://img.shields.io/badge/stars-37714-blue)
- [tiedot](https://github.com/HouzuoGuo/tiedot) - Your NoSQL database powered by Golang. ![stars](https://img.shields.io/badge/stars-2724-blue)
- [unitdb](https://github.com/unit-io/unitdb) - Fast timeseries database for IoT, realtime messaging applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application. ![stars](https://img.shields.io/badge/stars-120-blue)
- [Vasto](https://github.com/chrislusf/vasto) - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption. ![stars](https://img.shields.io/badge/stars-261-blue)
- [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL. ![stars](https://img.shields.io/badge/stars-12978-blue)

### Database Schema Migration

- [atlas](https://github.com/ariga/atlas) - A Database Toolkit. A CLI designed to help companies better work with their data. ![stars](https://img.shields.io/badge/stars-6271-blue)
- [avro](https://github.com/khezen/avro) - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes. ![stars](https://img.shields.io/badge/stars-46-blue)
- [bytebase](https://github.com/bytebase/bytebase) - Safe database schema change and version control for DevOps teams. ![stars](https://img.shields.io/badge/stars-11805-blue)
- [darwin](https://github.com/GuiaBolso/darwin) - Database schema evolution library for Go. ![stars](https://img.shields.io/badge/stars-144-blue)
- [dbmate](https://github.com/amacneil/dbmate) - A lightweight, framework-agnostic database migration tool. ![stars](https://img.shields.io/badge/stars-5601-blue)
- [go-fixtures](https://github.com/RichardKnop/go-fixtures) - Django style fixtures for Golang's excellent built-in database/sql library. ![stars](https://img.shields.io/badge/stars-29-blue)
- [go-pg-migrate](https://github.com/lawzava/go-pg-migrate) - CLI-friendly package for go-pg migrations management. ![stars](https://img.shields.io/badge/stars-10-blue)
- [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) - A Go package to help write migrations with go-pg/pg. ![stars](https://img.shields.io/badge/stars-84-blue)
- [goavro](https://github.com/linkedin/goavro) - A Go package that encodes and decodes Avro data. ![stars](https://img.shields.io/badge/stars-992-blue)
- [godfish](https://github.com/rafaelespinoza/godfish) - Database migration manager, works with native query language. Support for cassandra, mysql, postgres, sqlite3. ![stars](https://img.shields.io/badge/stars-8-blue)
- [goose](https://github.com/pressly/goose) - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts. ![stars](https://img.shields.io/badge/stars-7447-blue)
- [gorm-seeder](https://github.com/Kachit/gorm-seeder) - Simple database seeder for Gorm ORM. ![stars](https://img.shields.io/badge/stars-13-blue)
- [gormigrate](https://github.com/go-gormigrate/gormigrate) - Database schema migration helper for Gorm ORM. ![stars](https://img.shields.io/badge/stars-1059-blue)
- [libschema](https://github.com/muir/libschema) - Define your migrations separately in each library. Migrations for open source libraries. MySQL & PostgreSQL. ![stars](https://img.shields.io/badge/stars-15-blue)
- [migrate](https://github.com/golang-migrate/migrate) - Database migrations. CLI and Golang library. ![stars](https://img.shields.io/badge/stars-15872-blue)
- [migrator](https://github.com/lopezator/migrator) - Dead simple Go database migration library. ![stars](https://img.shields.io/badge/stars-172-blue)
- [migrator](https://github.com/larapulse/migrator) - MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code. ![stars](https://img.shields.io/badge/stars-25-blue)
- [schema](https://github.com/adlio/schema) - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries. ![stars](https://img.shields.io/badge/stars-36-blue)
- [skeema](https://github.com/skeema/skeema) - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools. ![stars](https://img.shields.io/badge/stars-1283-blue)
- [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. ![stars](https://img.shields.io/badge/stars-1459-blue)
- [sql-migrate](https://github.com/rubenv/sql-migrate) - Database migration tool. Allows embedding migrations into the application using go-bindata. ![stars](https://img.shields.io/badge/stars-3262-blue)
- [sqlize](https://github.com/sunary/sqlize) - Database migration generator. Allows generate sql migration from model and existing sql by differ them. ![stars](https://img.shields.io/badge/stars-113-blue)

### Database Tools

- [chproxy](https://github.com/Vertamedia/chproxy) - HTTP proxy for ClickHouse database. ![stars](https://img.shields.io/badge/stars-1306-blue)
- [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) - Collects small inserts and sends big requests to ClickHouse servers. ![stars](https://img.shields.io/badge/stars-478-blue)
- [dbbench](https://github.com/sj14/dbbench) - Database benchmarking tool with support for several databases and scripts. ![stars](https://img.shields.io/badge/stars-103-blue)
- [dg](https://github.com/codingconcepts/dg) - A fast data generator that produces CSV files from generated relational data. ![stars](https://img.shields.io/badge/stars-32-blue)
- [dynago](https://github.com/twharmon/dynago) - Simplify working with AWS DynamoDB. ![stars](https://img.shields.io/badge/stars-12-blue)
- [gatewayd](https://github.com/gatewayd-io/gatewayd) - Cloud-native database gateway and framework for building data-driven applications. Like API gateways, for databases. ![stars](https://img.shields.io/badge/stars-232-blue)
- [go-mysql](https://github.com/siddontang/go-mysql) - Go toolset to handle MySQL protocol and replication. ![stars](https://img.shields.io/badge/stars-4649-blue)
- [gorm-multitenancy](https://github.com/bartventer/gorm-multitenancy) - Multi-tenancy support for GORM managed databases. ![stars](https://img.shields.io/badge/stars-48-blue)
- [hasql](https://golang.yandex/hasql) - Library for accessing multi-host SQL database installations.
- [octillery](https://github.com/knocknote/octillery) - Go package for sharding databases ( Supports every ORM or raw SQL ). ![stars](https://img.shields.io/badge/stars-195-blue)
- [onedump](https://github.com/liweiyi88/onedump) - Database backup from different drivers to different destinations with one command and configuration. ![stars](https://img.shields.io/badge/stars-122-blue)
- [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) - Advanced scheduling for PostgreSQL. ![stars](https://img.shields.io/badge/stars-1116-blue)
- [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser. ![stars](https://img.shields.io/badge/stars-8709-blue)
- [prep](https://github.com/hexdigest/prep) - Use prepared SQL statements without changing your code. ![stars](https://img.shields.io/badge/stars-33-blue)
- [pREST](https://github.com/prest/prest) - Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new. ![stars](https://img.shields.io/badge/stars-4267-blue)
- [rdb](https://github.com/HDT3213/rdb) - Redis RDB file parser for secondary development and memory analysis. ![stars](https://img.shields.io/badge/stars-406-blue)
- [rwdb](https://github.com/andizzle/rwdb) - rwdb provides read replica capability for multiple database servers setup. ![stars](https://img.shields.io/badge/stars-19-blue)
- [vitess](https://github.com/youtube/vitess) - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services. ![stars](https://img.shields.io/badge/stars-18957-blue)
- [wescale](https://github.com/wesql/wescale) - WeScale is a database proxy designed to enhance the scalability, performance, security, and resilience of your applications. ![stars](https://img.shields.io/badge/stars-277-blue)

### SQL Query Builders

_Libraries for building and using SQL._

- [bqb](https://github.com/nullism/bqb) - Lightweight and easy to learn query builder. ![stars](https://img.shields.io/badge/stars-156-blue)
- [buildsqlx](https://github.com/arthurkushman/buildsqlx) - Go database query builder library for PostgreSQL. ![stars](https://img.shields.io/badge/stars-173-blue)
- [builq](https://github.com/cristalhq/builq) - Easily build SQL queries in Go. ![stars](https://img.shields.io/badge/stars-91-blue)
- [dbq](https://github.com/rocketlaunchr/dbq) - Zero boilerplate database operations for Go. ![stars](https://img.shields.io/badge/stars-405-blue)
- [Dotsql](https://github.com/gchaincl/dotsql) - Go library that helps you keep sql files in one place and use them with ease. ![stars](https://img.shields.io/badge/stars-743-blue)
- [gendry](https://github.com/didi/gendry) - Non-invasive SQL builder and powerful data binder. ![stars](https://img.shields.io/badge/stars-1624-blue)
- [godbal](https://github.com/xujiajun/godbal) - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily. ![stars](https://img.shields.io/badge/stars-59-blue)
- [goqu](https://github.com/doug-martin/goqu) - Idiomatic SQL builder and query library. ![stars](https://img.shields.io/badge/stars-2440-blue)
- [gosql](https://github.com/twharmon/gosql) - SQL Query builder with better null values support. ![stars](https://img.shields.io/badge/stars-34-blue)
- [Hotcoal](https://github.com/motrboat/hotcoal) - Secure your handcrafted SQL against injection. ![stars](https://img.shields.io/badge/stars-22-blue)
- [igor](https://github.com/galeone/igor) - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax. ![stars](https://img.shields.io/badge/stars-126-blue)
- [jet](https://github.com/go-jet/jet) - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure. ![stars](https://img.shields.io/badge/stars-2821-blue)
- [ormlite](https://github.com/pupizoid/ormlite) - Lightweight package containing some ORM-like features and helpers for sqlite databases. ![stars](https://img.shields.io/badge/stars-16-blue)
- [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) - Powerful data retrieval methods as well as DB-agnostic query building capabilities. ![stars](https://img.shields.io/badge/stars-640-blue)
- [qry](https://github.com/HnH/qry) - Tool that generates constants from files with raw SQL queries. ![stars](https://img.shields.io/badge/stars-35-blue)
- [sg](https://github.com/go-the-way/sg) - A SQL Gen for generating standard SQLs(supports: CRUD) written in Go. ![stars](https://img.shields.io/badge/stars-6-blue)
- [sq](https://github.com/bokwoon95/go-structured-query) - Type-safe SQL builder and struct mapper for Go. ![stars](https://img.shields.io/badge/stars-197-blue)
- [sqlc](https://github.com/kyleconroy/sqlc) - Generate type-safe code from SQL. ![stars](https://img.shields.io/badge/stars-13963-blue)
- [sqlf](https://github.com/leporo/sqlf) - Fast SQL query builder. ![stars](https://img.shields.io/badge/stars-149-blue)
- [sqlingo](https://github.com/lqs/sqlingo) - A lightweight DSL to build SQL in Go. ![stars](https://img.shields.io/badge/stars-420-blue)
- [sqrl](https://github.com/elgris/sqrl) - SQL query builder, fork of Squirrel with improved performance. ![stars](https://img.shields.io/badge/stars-279-blue)
- [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
- [Squirrel](https://github.com/Masterminds/squirrel) - Go library that helps you build SQL queries. ![stars](https://img.shields.io/badge/stars-7102-blue)
- [xo](https://github.com/knq/xo) - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server. ![stars](https://img.shields.io/badge/stars-3758-blue)

**[⬆ back to top](#contents)**

## Database Drivers

### Interfaces to Multiple Backends

- [cayley](https://github.com/google/cayley) - Graph database with support for multiple backends. ![stars](https://img.shields.io/badge/stars-14866-blue)
- [dsc](https://github.com/viant/dsc) - Datastore connectivity for SQL, NoSQL, structured files. ![stars](https://img.shields.io/badge/stars-32-blue)
- [dynamo](https://github.com/fogfish/dynamo) - A simple key-value abstraction to store algebraic and linked-data data types at AWS storage services: AWS DynamoDB and AWS S3. ![stars](https://img.shields.io/badge/stars-19-blue)
- [go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) - Transaction manager with multiple adapters (sql, sqlx, gorm, mongo, ...) controls transaction boundaries. ![stars](https://img.shields.io/badge/stars-251-blue)
- [gokv](https://github.com/philippgille/gokv) - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more). ![stars](https://img.shields.io/badge/stars-757-blue)

### Relational Database Drivers

- [avatica](https://github.com/apache/calcite-avatica-go) - Apache Avatica/Phoenix SQL driver for database/sql. ![stars](https://img.shields.io/badge/stars-121-blue)
- [bgc](https://github.com/viant/bgc) - Datastore Connectivity for BigQuery for go. ![stars](https://img.shields.io/badge/stars-21-blue)
- [firebirdsql](https://github.com/nakagami/firebirdsql) - Firebird RDBMS SQL driver for Go. ![stars](https://img.shields.io/badge/stars-229-blue)
- [go-adodb](https://github.com/mattn/go-adodb) - Microsoft ActiveX Object DataBase driver for go that uses database/sql. ![stars](https://img.shields.io/badge/stars-144-blue)
- [go-mssqldb](https://github.com/denisenkom/go-mssqldb) - Microsoft MSSQL driver for Go. ![stars](https://img.shields.io/badge/stars-1839-blue)
- [go-oci8](https://github.com/mattn/go-oci8) - Oracle driver for go that uses database/sql. ![stars](https://img.shields.io/badge/stars-634-blue)
- [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - MySQL driver for Go. ![stars](https://img.shields.io/badge/stars-14612-blue)
- [go-sqlite3](https://github.com/mattn/go-sqlite3) - SQLite3 driver for go that uses database/sql. ![stars](https://img.shields.io/badge/stars-8160-blue)
- [go-sqlite3](https://github.com/ncruces/go-sqlite3) - This Go module is compatible with the database/sql driver. It allows embedding SQLite into your application, provides direct access to its C API, supports SQLite VFS, and also includes a GORM driver. ![stars](https://img.shields.io/badge/stars-563-blue)
- [godror](https://github.com/godror/godror) - Oracle driver for Go, using the ODPI-C driver. ![stars](https://img.shields.io/badge/stars-539-blue)
- [gofreetds](https://github.com/minus5/gofreetds) - Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org). ![stars](https://img.shields.io/badge/stars-113-blue)
- [KSQL](https://github.com/VinGarcia/ksql) - A Simple and Powerful Golang SQL Library ![stars](https://img.shields.io/badge/stars-324-blue)
- [pgx](https://github.com/jackc/pgx) - PostgreSQL driver supporting features beyond those exposed by database/sql. ![stars](https://img.shields.io/badge/stars-11098-blue)
- [pig](https://github.com/alexeyco/pig) - Simple [pgx](https://github.com/jackc/pgx) wrapper to execute and [scan](https://github.com/georgysavva/scany) query results easily. ![stars](https://img.shields.io/badge/stars-17-blue)
- [pq](https://github.com/lib/pq) - Pure Go Postgres driver for database/sql. ![stars](https://img.shields.io/badge/stars-9250-blue)
- [Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) - SQLite with pure Go. ![stars](https://img.shields.io/badge/stars-438-blue)
- [sqlhooks](https://github.com/qustavo/sqlhooks) - Attach hooks to any database/sql driver. ![stars](https://img.shields.io/badge/stars-652-blue)
- [sqlite](https://pkg.go.dev/modernc.org/sqlite) - Package sqlite is a sql/database driver using a CGo-free port of the C SQLite3 library.
- [surrealdb.go](https://github.com/surrealdb/surrealdb.go) - SurrealDB Driver for Go. ![stars](https://img.shields.io/badge/stars-256-blue)
- [ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) - native and database/sql driver YDB (Yandex Database) ![stars](https://img.shields.io/badge/stars-148-blue)

### NoSQL Database Drivers

- [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) - Aerospike client in Go language. ![stars](https://img.shields.io/badge/stars-441-blue)
- [arangolite](https://github.com/solher/arangolite) - Lightweight golang driver for ArangoDB. ![stars](https://img.shields.io/badge/stars-72-blue)
- [asc](https://github.com/viant/asc) - Datastore Connectivity for Aerospike for go. ![stars](https://img.shields.io/badge/stars-11-blue)
- [forestdb](https://github.com/couchbase/goforestdb) - Go bindings for ForestDB. ![stars](https://img.shields.io/badge/stars-37-blue)
- [go-couchbase](https://github.com/couchbase/go-couchbase) - Couchbase client in Go. ![stars](https://img.shields.io/badge/stars-322-blue)
- [go-mongox](https://github.com/chenmingyong0423/go-mongox) - A Go Mongo library based on the official driver, featuring streamlined document operations, generic binding of structs to collections, built-in CRUD, aggregation, automated field updates, struct validation, hooks, and plugin-based programming. ![stars](https://img.shields.io/badge/stars-159-blue)
- [go-pilosa](https://github.com/pilosa/go-pilosa) - Go client library for Pilosa. ![stars](https://img.shields.io/badge/stars-57-blue)
- [go-rejson](https://github.com/nitishm/go-rejson) - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease. ![stars](https://img.shields.io/badge/stars-344-blue)
- [gocb](https://github.com/couchbase/gocb) - Official Couchbase Go SDK. ![stars](https://img.shields.io/badge/stars-370-blue)
- [gocosmos](https://github.com/btnguyen2k/gocosmos) - REST client and standard `database/sql` driver for Azure Cosmos DB. ![stars](https://img.shields.io/badge/stars-22-blue)
- [gocql](https://gocql.github.io) - Go language driver for Apache Cassandra.
- [godis](https://github.com/piaohao/godis) - redis client implement by golang, inspired by jedis. ![stars](https://img.shields.io/badge/stars-111-blue)
- [godscache](https://github.com/defcronyke/godscache) - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached. ![stars](https://img.shields.io/badge/stars-11-blue)
- [gomemcache](https://github.com/bradfitz/gomemcache/) - memcache client library for the Go programming language. ![stars](https://img.shields.io/badge/stars-1780-blue)
- [gomemcached](https://github.com/aliexpressru/gomemcached) - A binary Memcached client for Go with support for sharding using consistent hashing, along with SASL. ![stars](https://img.shields.io/badge/stars-19-blue)
- [gorethink](https://github.com/dancannon/gorethink) - Go language driver for RethinkDB. ![stars](https://img.shields.io/badge/stars-1655-blue)
- [goriak](https://github.com/zegl/goriak) - Go language driver for Riak KV. ![stars](https://img.shields.io/badge/stars-30-blue)
- [Kivik](https://github.com/go-kivik/kivik) - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases. ![stars](https://img.shields.io/badge/stars-316-blue)
- [mgm](https://github.com/kamva/mgm) - MongoDB model-based ODM for Go (based on official MongoDB driver). ![stars](https://img.shields.io/badge/stars-756-blue)
- [mgo](https://github.com/globalsign/mgo) - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms. ![stars](https://img.shields.io/badge/stars-1971-blue)
- [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) - Official MongoDB driver for the Go language. ![stars](https://img.shields.io/badge/stars-8224-blue)
- [neo4j](https://github.com/cihangir/neo4j) - Neo4j Rest API Bindings for Golang. ![stars](https://img.shields.io/badge/stars-28-blue)
- [neoism](https://github.com/jmcvetta/neoism) - Neo4j client for Golang. ![stars](https://img.shields.io/badge/stars-388-blue)
- [qmgo](https://github.com/qiniu/qmgo) - The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo. ![stars](https://img.shields.io/badge/stars-1331-blue)
- [redeo](https://github.com/bsm/redeo) - Redis-protocol compatible TCP servers/services. ![stars](https://img.shields.io/badge/stars-441-blue)
- [redigo](https://github.com/gomodule/redigo) - Redigo is a Go client for the Redis database. ![stars](https://img.shields.io/badge/stars-9767-blue)
- [redis](https://github.com/redis/go-redis) - Redis client for Golang. ![stars](https://img.shields.io/badge/stars-20352-blue)
- [rueidis](http://github.com/rueian/rueidis) - Fast Redis RESP3 client with auto pipelining and server-assisted client side caching.
- [xredis](https://github.com/shomali11/xredis) - Typesafe, customizable, clean & easy to use Redis client. ![stars](https://img.shields.io/badge/stars-19-blue)

### Search and Analytic Databases

- [clickhouse-go](https://github.com/ClickHouse/clickhouse-go/) - ClickHouse SQL client for Go with a `database/sql` compatibility. ![stars](https://img.shields.io/badge/stars-2951-blue)
- [effdsl](https://github.com/sdqri/effdsl) - Elasticsearch query builder for Go. ![stars](https://img.shields.io/badge/stars-27-blue)
- [elastic](https://github.com/olivere/elastic) - Elasticsearch client for Go. ![stars](https://img.shields.io/badge/stars-7442-blue)
- [elasticsql](https://github.com/cch123/elasticsql) - Convert sql to elasticsearch dsl in Go. ![stars](https://img.shields.io/badge/stars-1181-blue)
- [elastigo](https://github.com/mattbaird/elastigo) - Elasticsearch client library. ![stars](https://img.shields.io/badge/stars-943-blue)
- [go-elasticsearch](https://github.com/elastic/go-elasticsearch) - Official Elasticsearch client for Go. ![stars](https://img.shields.io/badge/stars-5734-blue)
- [goes](https://github.com/OwnLocal/goes) - Library to interact with Elasticsearch. ![stars](https://img.shields.io/badge/stars-31-blue)
- [skizze](https://github.com/seiflotfy/skizze) - probabilistic data-structures service and storage. ![stars](https://img.shields.io/badge/stars-90-blue)
- [zoekt](https://github.com/sourcegraph/zoekt) - Fast trigram based code search. ![stars](https://img.shields.io/badge/stars-794-blue)

**[⬆ back to top](#contents)**

## Date and Time

_Libraries for working with dates and times._

- [approx](https://github.com/goschtalt/approx) - A Duration extension supporting parsing/printing durations in days, weeks and years. ![stars](https://img.shields.io/badge/stars-13-blue)
- [carbon](https://github.com/golang-module/carbon) - A simple, semantic and developer-friendly golang package for datetime. ![stars](https://img.shields.io/badge/stars-4925-blue)
- [carbon](https://github.com/uniplaces/carbon) - Simple Time extension with a lot of util methods, ported from PHP Carbon library. ![stars](https://img.shields.io/badge/stars-776-blue)
- [cronrange](https://github.com/1set/cronrange) - Parses Cron-style time range expressions, checks if the given time is within any ranges. ![stars](https://img.shields.io/badge/stars-18-blue)
- [date](https://github.com/rickb777/date) - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day. ![stars](https://img.shields.io/badge/stars-136-blue)
- [dateparse](https://github.com/araddon/dateparse) - Parse date's without knowing format in advance. ![stars](https://img.shields.io/badge/stars-2062-blue)
- [durafmt](https://github.com/hako/durafmt) - Time duration formatting library for Go. ![stars](https://img.shields.io/badge/stars-497-blue)
- [feiertage](https://github.com/wlbr/feiertage) - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving... ![stars](https://img.shields.io/badge/stars-48-blue)
- [go-anytime](https://github.com/ijt/go-anytime) - Parse dates/times like "next dec 22nd at 3pm" and ranges like "from today until next thursday" without knowing the format in advance. ![stars](https://img.shields.io/badge/stars-24-blue)
- [go-datebin](https://github.com/deatil/go-datebin) - A simple datetime parse pkg. ![stars](https://img.shields.io/badge/stars-4-blue)
- [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) - The implementation of the Persian (Solar Hijri) Calendar in Go (golang). ![stars](https://img.shields.io/badge/stars-210-blue)
- [go-str2duration](https://github.com/xhit/go-str2duration) - Convert string to duration. Support time.Duration returned string and more. ![stars](https://img.shields.io/badge/stars-104-blue)
- [go-sunrise](https://github.com/nathan-osman/go-sunrise) - Calculate the sunrise and sunset times for a given location. ![stars](https://img.shields.io/badge/stars-153-blue)
- [go-week](https://github.com/stoewer/go-week) - An efficient package to work with ISO8601 week dates. ![stars](https://img.shields.io/badge/stars-9-blue)
- [gostradamus](https://github.com/bykof/gostradamus) - A Go package for working with dates. ![stars](https://img.shields.io/badge/stars-204-blue)
- [iso8601](https://github.com/relvacode/iso8601) - Efficiently parse ISO8601 date-times without regex. ![stars](https://img.shields.io/badge/stars-149-blue)
- [kair](https://github.com/GuilhermeCaruso/kair) - Date and Time - Golang Formatting Library. ![stars](https://img.shields.io/badge/stars-24-blue)
- [now](https://github.com/jinzhu/now) - Now is a time toolkit for golang. ![stars](https://img.shields.io/badge/stars-4472-blue)
- [strftime](https://github.com/awoodbeck/strftime) - C99-compatible strftime formatter. ![stars](https://img.shields.io/badge/stars-13-blue)
- [timespan](https://github.com/SaidinWoT/timespan) - For interacting with intervals of time, defined as a start time and a duration. ![stars](https://img.shields.io/badge/stars-83-blue)
- [timeutil](https://github.com/leekchan/timeutil) - Useful extensions (Timedelta, Strftime, ...) to the golang's time package. ![stars](https://img.shields.io/badge/stars-192-blue)
- [tuesday](https://github.com/osteele/tuesday) - Ruby-compatible Strftime function. ![stars](https://img.shields.io/badge/stars-12-blue)

**[⬆ back to top](#contents)**

## Distributed Systems

_Packages that help with building Distributed Systems._

- [arpc](https://github.com/lesismal/arpc) - More effective network communication, support two-way-calling, notify, broadcast. ![stars](https://img.shields.io/badge/stars-977-blue)
- [bedrock](https://github.com/z5labs/bedrock) - Provides a minimal, modular and composable foundation for quickly developing services and more use case specific frameworks in Go. ![stars](https://img.shields.io/badge/stars-7-blue)
- [capillaries](https://github.com/capillariesio/capillaries) - distributed batch data processing framework. ![stars](https://img.shields.io/badge/stars-63-blue)
- [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go. ![stars](https://img.shields.io/badge/stars-72-blue)
- [committer](https://github.com/vadiminshakov/committer) - A distributed transactions management system (2PC/3PC implementation). ![stars](https://img.shields.io/badge/stars-31-blue)
- [consistent](https://github.com/buraksezer/consistent) - Consistent hashing with bounded loads. ![stars](https://img.shields.io/badge/stars-710-blue)
- [consistenthash](https://github.com/mbrostami/consistenthash) - Consistent hashing with configurable replicas. ![stars](https://img.shields.io/badge/stars-28-blue)
- [dht](https://github.com/anacrolix/dht) - BitTorrent Kademlia DHT implementation. ![stars](https://img.shields.io/badge/stars-316-blue)
- [digota](https://github.com/digota/digota) - grpc ecommerce microservice. ![stars](https://img.shields.io/badge/stars-512-blue)
- [dot](https://github.com/dotchain/dot/) - distributed sync using operational transformation/OT. ![stars](https://img.shields.io/badge/stars-87-blue)
- [doublejump](https://github.com/edwingeng/doublejump) - A revamped Google's jump consistent hash. ![stars](https://img.shields.io/badge/stars-103-blue)
- [dragonboat](https://github.com/lni/dragonboat) - A feature complete and high performance multi-group Raft library in Go. ![stars](https://img.shields.io/badge/stars-5109-blue)
- [Dragonfly](https://github.com/dragonflyoss/Dragonfly2) - Provide efficient, stable and secure file distribution and image acceleration based on p2p technology to be the best practice and standard solution in cloud native architectures. ![stars](https://img.shields.io/badge/stars-2367-blue)
- [drmaa](https://github.com/dgruber/drmaa) - Job submission library for cluster schedulers based on the DRMAA standard. ![stars](https://img.shields.io/badge/stars-48-blue)
- [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
- [dynatomic](https://github.com/tylfin/dynatomic) - A library for using DynamoDB as an atomic counter. ![stars](https://img.shields.io/badge/stars-17-blue)
- [emitter-io](https://github.com/emitter-io/emitter) - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love. ![stars](https://img.shields.io/badge/stars-3882-blue)
- [evans](https://github.com/ktr0731/evans) - Evans: more expressive universal gRPC client. ![stars](https://img.shields.io/badge/stars-4320-blue)
- [failured](https://github.com/andy2046/failured) - adaptive accrual failure detector for distributed systems. ![stars](https://img.shields.io/badge/stars-13-blue)
- [flowgraph](https://github.com/vectaport/flowgraph) - flow-based programming package. ![stars](https://img.shields.io/badge/stars-60-blue)
- [gleam](https://github.com/chrislusf/gleam) - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed. ![stars](https://img.shields.io/badge/stars-3479-blue)
- [glow](https://github.com/chrislusf/glow) - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go. ![stars](https://img.shields.io/badge/stars-3207-blue)
- [gmsec](https://github.com/gmsec/micro) - A Go distributed systems development framework. ![stars](https://img.shields.io/badge/stars-25-blue)
- [go-doudou](https://github.com/unionj-cloud/go-doudou) - A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity. ![stars](https://img.shields.io/badge/stars-1430-blue)
- [go-eagle](https://github.com/go-eagle/eagle) - A Go framework for the API or Microservice with handy scaffolding tools. ![stars](https://img.shields.io/badge/stars-2222-blue)
- [go-health](https://github.com/InVisionApp/go-health) - Library for enabling asynchronous dependency health checks in your service. ![stars](https://img.shields.io/badge/stars-753-blue)
- [go-jump](https://github.com/dgryski/go-jump) - Port of Google's "Jump" Consistent Hash function. ![stars](https://img.shields.io/badge/stars-383-blue)
- [go-kit](https://github.com/go-kit/kit) - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc. ![stars](https://img.shields.io/badge/stars-26736-blue)
- [go-micro](https://github.com/micro/go-micro) - A distributed systems development framework. ![stars](https://img.shields.io/badge/stars-22062-blue)
- [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) - MySQL based distributed lock. ![stars](https://img.shields.io/badge/stars-62-blue)
- [go-pdu](https://github.com/pdupub/go-pdu) - A decentralized identity-based social network. ![stars](https://img.shields.io/badge/stars-47-blue)
- [go-sundheit](https://github.com/AppsFlyer/go-sundheit) - A library built to provide support for defining async service health checks for golang services. ![stars](https://img.shields.io/badge/stars-553-blue)
- [go-zero](https://github.com/tal-tech/go-zero) - A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity. ![stars](https://img.shields.io/badge/stars-29669-blue)
- [gorpc](https://github.com/valyala/gorpc) - Simple, fast and scalable RPC library for high load. ![stars](https://img.shields.io/badge/stars-707-blue)
- [grpc-go](https://github.com/grpc/grpc-go) - The Go language implementation of gRPC. HTTP/2 based RPC. ![stars](https://img.shields.io/badge/stars-21288-blue)
- [hprose](https://github.com/hprose/hprose-golang) - Very newbility RPC Library, support 25+ languages now. ![stars](https://img.shields.io/badge/stars-1259-blue)
- [jsonrpc](https://github.com/osamingo/jsonrpc) - The jsonrpc package helps implement of JSON-RPC 2.0. ![stars](https://img.shields.io/badge/stars-188-blue)
- [jsonrpc](https://github.com/ybbus/jsonrpc) - JSON-RPC 2.0 HTTP client implementation. ![stars](https://img.shields.io/badge/stars-338-blue)
- [K8gb](https://github.com/k8gb-io/k8gb) - A cloud native Kubernetes Global Balancer. ![stars](https://img.shields.io/badge/stars-914-blue)
- [Kitex](https://github.com/cloudwego/kitex) - A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices. If the performance and extensibility are the main concerns when you develop microservices, Kitex can be a good choice. ![stars](https://img.shields.io/badge/stars-7184-blue)
- [Kratos](https://github.com/go-kratos/kratos) - A modular-designed and easy-to-use microservices framework in Go. ![stars](https://img.shields.io/badge/stars-23590-blue)
- [liftbridge](https://github.com/liftbridge-io/liftbridge) - Lightweight, fault-tolerant message streams for NATS. ![stars](https://img.shields.io/badge/stars-2587-blue)
- [lura](https://github.com/luraproject/lura) - Ultra performant API Gateway framework with middlewares. ![stars](https://img.shields.io/badge/stars-6437-blue)
- [micro](https://github.com/micro/micro) - A distributed systems runtime for the cloud and beyond. ![stars](https://img.shields.io/badge/stars-12179-blue)
- [mochi mqtt](https://github.com/mochi-co/mqtt) - Fully spec compliant, embeddable high-performance MQTT v5/v3 broker for IoT, smarthome, and pubsub. ![stars](https://img.shields.io/badge/stars-1356-blue)
- [NATS](https://github.com/nats-io/nats-server) - NATS is a simple, secure, and ![stars](https://img.shields.io/badge/stars-16306-blue)
  performant communications system for digital systems, services, and devices.
- [outboxer](https://github.com/italolelis/outboxer) - Outboxer is a go library that implements the outbox pattern. ![stars](https://img.shields.io/badge/stars-160-blue)
- [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
- [pjrpc](https://gitlab.com/pjrpc/pjrpc) - Golang JSON-RPC Server-Client with Protobuf spec.
- [raft](https://github.com/hashicorp/raft) - Golang implementation of the Raft consensus protocol, by HashiCorp. ![stars](https://img.shields.io/badge/stars-8360-blue)
- [raft](https://github.com/etcd-io/raft) - Go implementation of the Raft consensus protocol, by CoreOS. ![stars](https://img.shields.io/badge/stars-711-blue)
- [rain](https://github.com/cenkalti/rain) - BitTorrent client and library. ![stars](https://img.shields.io/badge/stars-995-blue)
- [redis-lock](https://github.com/bsm/redislock) - Simplified distributed locking implementation using Redis. ![stars](https://img.shields.io/badge/stars-1511-blue)
- [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
- [ringpop-go](https://github.com/uber/ringpop-go) - Scalable, fault-tolerant application-layer sharding for Go applications. ![stars](https://img.shields.io/badge/stars-839-blue)
- [rpcx](https://github.com/smallnest/rpcx) - Distributed pluggable RPC service framework like alibaba Dubbo. ![stars](https://img.shields.io/badge/stars-8147-blue)
- [Semaphore](https://github.com/jexia/semaphore) - A straightforward (micro) service orchestrator. ![stars](https://img.shields.io/badge/stars-94-blue)
- [sleuth](https://github.com/ursiform/sleuth) - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)). ![stars](https://img.shields.io/badge/stars-378-blue)
- [sponge](https://github.com/zhufuyi/sponge) - A distributed development framework that integrates automatic code generation, gin and grpc frameworks, base development frameworks. ![stars](https://img.shields.io/badge/stars-1579-blue)
- [Tarmac](https://github.com/tarmac-project/tarmac) - Framework for writing functions, microservices, or monoliths with WebAssembly ![stars](https://img.shields.io/badge/stars-329-blue)
- [Temporal](https://github.com/temporalio/sdk-go) - Durable execution system for making code fault-tolerant and simple. ![stars](https://img.shields.io/badge/stars-558-blue)
- [torrent](https://github.com/anacrolix/torrent) - BitTorrent client package. ![stars](https://img.shields.io/badge/stars-5636-blue)
- [trpc-go](https://github.com/trpc-group/trpc-go) - The Go language implementation of tRPC, which is a pluggable, high-performance RPC framework. ![stars](https://img.shields.io/badge/stars-866-blue)

**[⬆ back to top](#contents)**

## Dynamic DNS

_Tools for updating dynamic DNS records._

- [DDNS](https://github.com/skibish/ddns) - Personal DDNS client with Digital Ocean Networking DNS as backend. ![stars](https://img.shields.io/badge/stars-258-blue)
- [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.
- [GoDNS](https://github.com/timothyye/godns) - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go. ![stars](https://img.shields.io/badge/stars-1533-blue)

**[⬆ back to top](#contents)**

## Email

_Libraries and tools that implement email creation and sending._

- [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
- [douceur](https://github.com/aymerick/douceur) - CSS inliner for your HTML emails. ![stars](https://img.shields.io/badge/stars-248-blue)
- [email](https://github.com/jordan-wright/email) - A robust and flexible email library for Go. ![stars](https://img.shields.io/badge/stars-2684-blue)
- [email-verifier](https://github.com/AfterShip/email-verifier) - A Go library for email verification without sending any emails. ![stars](https://img.shields.io/badge/stars-1280-blue)
- [go-dkim](https://github.com/toorop/go-dkim) - DKIM library, to sign & verify email. ![stars](https://img.shields.io/badge/stars-98-blue)
- [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) - Golang library for providing a canonical representation of email address. ![stars](https://img.shields.io/badge/stars-64-blue)
- [go-email-validator](https://github.com/go-email-validator/go-email-validator) - Modular email validator for syntax, disposable, smtp, etc... checking. ![stars](https://img.shields.io/badge/stars-51-blue)
- [go-imap](https://github.com/emersion/go-imap) - IMAP library for clients and servers. ![stars](https://img.shields.io/badge/stars-2125-blue)
- [go-mail](https://github.com/wneessen/go-mail) - A simple Go library for sending mails in Go. ![stars](https://img.shields.io/badge/stars-780-blue)
- [go-message](https://github.com/emersion/go-message) - Streaming library for the Internet Message Format and mail messages. ![stars](https://img.shields.io/badge/stars-392-blue)
- [go-premailer](https://github.com/vanng822/go-premailer) - Inline styling for HTML mail in Go. ![stars](https://img.shields.io/badge/stars-149-blue)
- [go-simple-mail](https://github.com/xhit/go-simple-mail) - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send. ![stars](https://img.shields.io/badge/stars-656-blue)
- [Hectane](https://github.com/hectane/hectane) - Lightweight SMTP client providing an HTTP API. ![stars](https://img.shields.io/badge/stars-222-blue)
- [hermes](https://github.com/matcornic/hermes) - Golang package that generates clean, responsive HTML e-mails. ![stars](https://img.shields.io/badge/stars-2845-blue)
- [Maddy](https://github.com/foxcpp/maddy) - All-in-one (SMTP, IMAP, DKIM, DMARC, MTA-STS, DANE) email server ![stars](https://img.shields.io/badge/stars-5249-blue)
- [mailchain](https://github.com/mailchain/mailchain) - Send encrypted emails to blockchain addresses written in Go. ![stars](https://img.shields.io/badge/stars-142-blue)
- [mailgun-go](https://github.com/mailgun/mailgun-go) - Go library for sending mail with the Mailgun API. ![stars](https://img.shields.io/badge/stars-705-blue)
- [MailHog](https://github.com/mailhog/MailHog) - Email and SMTP testing with web and API interface. ![stars](https://img.shields.io/badge/stars-14385-blue)
- [Mailpit](https://github.com/axllent/mailpit) - Email and SMTP testing tool for developers. ![stars](https://img.shields.io/badge/stars-6416-blue)
- [mailx](https://github.com/valord577/mailx) - Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`. ![stars](https://img.shields.io/badge/stars-19-blue)
- [mox](https://github.com/mjl-/mox) - Modern full-featured secure mail server for low-maintenance, self-hosted email. ![stars](https://img.shields.io/badge/stars-3787-blue)
- [SendGrid](https://github.com/sendgrid/sendgrid-go) - SendGrid's Go library for sending email. ![stars](https://img.shields.io/badge/stars-990-blue)
- [smtp](https://github.com/mailhog/smtp) - SMTP server protocol state machine. ![stars](https://img.shields.io/badge/stars-75-blue)
- [smtpmock](https://github.com/mocktools/go-smtp-mock) - Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment. ![stars](https://img.shields.io/badge/stars-139-blue)
- [truemail-go](https://github.com/truemail-rb/truemail-go) - Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more. ![stars](https://img.shields.io/badge/stars-108-blue)

**[⬆ back to top](#contents)**

## Embeddable Scripting Languages

_Embedding other languages inside your go code._

- [anko](https://github.com/mattn/anko) - Scriptable interpreter written in Go. ![stars](https://img.shields.io/badge/stars-1491-blue)
- [binder](https://github.com/alexeyco/binder) - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua). ![stars](https://img.shields.io/badge/stars-77-blue)
- [cel-go](https://github.com/google/cel-go) - Fast, portable, non-Turing complete expression evaluation with gradual typing. ![stars](https://img.shields.io/badge/stars-2352-blue)
- [ecal](https://github.com/krotik/ecal) - A simple embeddable scripting language which supports concurrent event processing. ![stars](https://img.shields.io/badge/stars-44-blue)
- [expr](https://github.com/antonmedv/expr) - Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing. ![stars](https://img.shields.io/badge/stars-6461-blue)
- [gentee](https://github.com/gentee/gentee) - Embeddable scripting programming language. ![stars](https://img.shields.io/badge/stars-137-blue)
- [gisp](https://github.com/jcla1/gisp) - Simple LISP in Go. ![stars](https://img.shields.io/badge/stars-513-blue)
- [go-duktape](https://github.com/olebedev/go-duktape) - Duktape JavaScript engine bindings for Go. ![stars](https://img.shields.io/badge/stars-778-blue)
- [go-lua](https://github.com/Shopify/go-lua) - Port of the Lua 5.2 VM to pure Go. ![stars](https://img.shields.io/badge/stars-3179-blue)
- [go-php](https://github.com/deuill/go-php) - PHP bindings for Go. ![stars](https://img.shields.io/badge/stars-936-blue)
- [go-python](https://github.com/sbinet/go-python) - naive go bindings to the CPython C-API. ![stars](https://img.shields.io/badge/stars-1529-blue)
- [goal](https://codeberg.org/anaseto/goal) - An embeddable scripting array language.
- [goja](https://github.com/dop251/goja) - ECMAScript 5.1(+) implementation in Go. ![stars](https://img.shields.io/badge/stars-5760-blue)
- [golua](https://github.com/aarzilli/golua) - Go bindings for Lua C API. ![stars](https://img.shields.io/badge/stars-655-blue)
- [gopher-lua](https://github.com/yuin/gopher-lua) - Lua 5.1 VM and compiler written in Go. ![stars](https://img.shields.io/badge/stars-6389-blue)
- [gval](https://github.com/PaesslerAG/gval) - A highly customizable expression language written in Go. ![stars](https://img.shields.io/badge/stars-766-blue)
- [metacall](https://github.com/metacall/core) - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more. ![stars](https://img.shields.io/badge/stars-1601-blue)
- [ngaro](https://github.com/db47h/ngaro) - Embeddable Ngaro VM implementation enabling scripting in Retro. ![stars](https://img.shields.io/badge/stars-29-blue)
- [prolog](https://github.com/ichiban/prolog) - Embeddable Prolog. ![stars](https://img.shields.io/badge/stars-641-blue)
- [purl](https://github.com/ian-kent/purl) - Perl 5.18.2 embedded in Go. ![stars](https://img.shields.io/badge/stars-41-blue)
- [starlark-go](https://github.com/google/starlark-go) - Go implementation of Starlark: Python-like language with deterministic evaluation and hermetic execution. ![stars](https://img.shields.io/badge/stars-2398-blue)
- [starlet](https://github.com/1set/starlet) - Go wrapper for [starlark-go](https://github.com/google/starlark-go) that simplifies script execution, offers data conversion, and useful Starlark libraries and extensions. ![stars](https://img.shields.io/badge/stars-28-blue)
- [tengo](https://github.com/d5/tengo) - Bytecode compiled script language for Go. ![stars](https://img.shields.io/badge/stars-3578-blue)
- [Wa/凹语言](https://github.com/wa-lang/wa) - The Wa Programming Language embedded in Go. ![stars](https://img.shields.io/badge/stars-1383-blue)

**[⬆ back to top](#contents)**

## Error Handling

_Libraries for handling errors._

- [emperror](https://github.com/emperror/emperror) - Error handling tools and best practices for Go libraries and applications. ![stars](https://img.shields.io/badge/stars-350-blue)
- [eris](https://github.com/rotisserie/eris) - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors. ![stars](https://img.shields.io/badge/stars-1512-blue)
- [errlog](https://github.com/snwfdhmp/errlog) - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place. ![stars](https://img.shields.io/badge/stars-461-blue)
- [errors](https://github.com/emperror/errors) - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives. ![stars](https://img.shields.io/badge/stars-199-blue)
- [errors](https://github.com/neuronlabs/errors) - Simple golang error handling with classification primitives. ![stars](https://img.shields.io/badge/stars-6-blue)
- [errors](https://github.com/PumpkinSeed/errors) - The most simple error wrapper with awesome performance and minimal memory overhead. ![stars](https://img.shields.io/badge/stars-7-blue)
- [errors](https://gitlab.com/tozd/go/errors) - Providing errors with a stack trace and optional structured details. Compatible with github.com/pkg/errors API but does not use it internally.
- [errors](https://github.com/naughtygopher/errors) - Drop-in replacement for builtin Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions. ![stars](https://img.shields.io/badge/stars-67-blue)
- [errors](https://github.com/cockroachdb/errors) - Go error library with error portability over the network. ![stars](https://img.shields.io/badge/stars-2143-blue)
- [errorx](https://github.com/joomcode/errorx) - A feature rich error package with stack traces, composition of errors and more. ![stars](https://img.shields.io/badge/stars-1229-blue)
- [exception](https://github.com/rbrahul/exception) - A simple utility package for exception handling with try-catch in Golang. ![stars](https://img.shields.io/badge/stars-34-blue)
- [Falcon](https://github.com/SonicRoshan/falcon) - A Simple Yet Highly Powerful Package For Error Handling. ![stars](https://img.shields.io/badge/stars-11-blue)
- [Fault](https://github.com/Southclaws/fault) - An ergonomic mechanism for wrapping errors in order to facilitate structured metadata and context for error values. ![stars](https://img.shields.io/badge/stars-171-blue)
- [go-multierror](https://github.com/hashicorp/go-multierror) - Go (golang) package for representing a list of errors as a single error. ![stars](https://img.shields.io/badge/stars-2390-blue)
- [multierr](https://github.com/uber-go/multierr) - Package for representing a list of errors as a single error. ![stars](https://img.shields.io/badge/stars-1071-blue)
- [oops](https://github.com/samber/oops) - Error handling with context, stack trace and source fragments. ![stars](https://img.shields.io/badge/stars-534-blue)
- [tracerr](https://github.com/ztrue/tracerr) - Golang errors with stack trace and source fragments. ![stars](https://img.shields.io/badge/stars-1053-blue)

**[⬆ back to top](#contents)**

## File Handling

_Libraries for handling files and file systems._

- [afero](https://github.com/spf13/afero) - FileSystem Abstraction System for Go. ![stars](https://img.shields.io/badge/stars-6039-blue)
- [afs](https://github.com/viant/afs) - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go. ![stars](https://img.shields.io/badge/stars-308-blue)
- [baraka](https://github.com/xis/baraka) - A library to process http file uploads easily. ![stars](https://img.shields.io/badge/stars-59-blue)
- [checksum](https://github.com/codingsince1985/checksum) - Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files. ![stars](https://img.shields.io/badge/stars-105-blue)
- [copy](https://github.com/otiai10/copy) - Copy directory recursively. ![stars](https://img.shields.io/badge/stars-732-blue)
- [flop](https://github.com/homedepot/flop) - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html). ![stars](https://img.shields.io/badge/stars-33-blue)
- [gdu](https://github.com/dundee/gdu) - Disk usage analyzer with console interface. ![stars](https://img.shields.io/badge/stars-4151-blue)
- [go-csv-tag](https://github.com/artonge/go-csv-tag) - Load csv file using tag. ![stars](https://img.shields.io/badge/stars-119-blue)
- [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) - Copy files for humans. ![stars](https://img.shields.io/badge/stars-22-blue)
- [go-exiftool](https://github.com/barasher/go-exiftool) - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...). ![stars](https://img.shields.io/badge/stars-258-blue)
- [go-gtfs](https://github.com/artonge/go-gtfs) - Load gtfs files in go. ![stars](https://img.shields.io/badge/stars-46-blue)
- [go-wkhtmltopdf](https://github.com/SebastiaanKlippert/go-wkhtmltopdf) - A package to convert an HTML template to a PDF file. ![stars](https://img.shields.io/badge/stars-1076-blue)
- [gofs](https://github.com/no-src/gofs) - A cross-platform real-time file synchronization tool out of the box. ![stars](https://img.shields.io/badge/stars-490-blue)
- [gulter](https://github.com/adelowo/gulter) - A simple HTTP middleware to automatically handle all your file upload needs ![stars](https://img.shields.io/badge/stars-61-blue)
- [gut/yos](https://github.com/1set/gut) - Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links. ![stars](https://img.shields.io/badge/stars-27-blue)
- [higgs](https://github.com/dastoori/higgs) - A tiny cross-platform Go library to hide/unhide files and directories. ![stars](https://img.shields.io/badge/stars-24-blue)
- [iso9660](https://github.com/kdomanski/iso9660) - A package for reading and creating ISO9660 disk images ![stars](https://img.shields.io/badge/stars-272-blue)
- [notify](https://github.com/rjeczalik/notify) - File system event notification library with simple API, similar to os/signal. ![stars](https://img.shields.io/badge/stars-914-blue)
- [opc](https://github.com/qmuntal/opc) - Load Open Packaging Conventions (OPC) files for Go. ![stars](https://img.shields.io/badge/stars-75-blue)
- [parquet](https://github.com/parsyl/parquet) - Read and write [parquet](https://parquet.apache.org) files. ![stars](https://img.shields.io/badge/stars-112-blue)
- [pathtype](https://github.com/jonchun/pathtype) - Treat paths as their own type instead of using strings. ![stars](https://img.shields.io/badge/stars-12-blue)
- [pdfcpu](https://github.com/pdfcpu/pdfcpu) - PDF processor. ![stars](https://img.shields.io/badge/stars-7228-blue)
- [skywalker](https://github.com/dixonwille/skywalker) - Package to allow one to concurrently go through a filesystem with ease. ![stars](https://img.shields.io/badge/stars-102-blue)
- [todotxt](https://github.com/1set/todotxt) - Go library for Gina Trapani's [_todo.txt_](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [_todo.txt_ format](https://github.com/todotxt/todo.txt). ![stars](https://img.shields.io/badge/stars-24-blue)
- [vfs](https://github.com/C2FO/vfs) - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS. ![stars](https://img.shields.io/badge/stars-317-blue)

**[⬆ back to top](#contents)**

## Financial

_Packages for accounting and finance._

- [accounting](https://github.com/leekchan/accounting) - money and currency formatting for golang. ![stars](https://img.shields.io/badge/stars-881-blue)
- [ach](https://github.com/moov-io/ach) - A reader, writer, and validator for Automated Clearing House (ACH) files. ![stars](https://img.shields.io/badge/stars-466-blue)
- [bbgo](https://github.com/c9s/bbgo) - A crypto trading bot framework written in Go. Including common crypto exchange API, standard indicators, back-testing and many built-in strategies. ![stars](https://img.shields.io/badge/stars-1278-blue)
- [currency](https://github.com/bojanz/currency) - Handles currency amounts, provides currency information and formatting. ![stars](https://img.shields.io/badge/stars-572-blue)
- [currency](https://github.com/naughtygopher/currency) - High performant & accurate currency computation package. ![stars](https://img.shields.io/badge/stars-61-blue)
- [decimal](https://github.com/shopspring/decimal) - Arbitrary-precision fixed-point decimal numbers. ![stars](https://img.shields.io/badge/stars-6509-blue)
- [decimal](https://github.com/govalues/decimal) - Immutable decimal numbers with panic-free arithmetic. ![stars](https://img.shields.io/badge/stars-119-blue)
- [fpdecimal](https://github.com/nikolaydubina/fpdecimal) - Fast and precise serialization and arithmetic for small fixed-point decimals ![stars](https://img.shields.io/badge/stars-31-blue)
- [fpmoney](https://github.com/nikolaydubina/fpmoney) - Fast and simple ISO4217 fixed-point decimal money. ![stars](https://img.shields.io/badge/stars-32-blue)
- [go-finance](https://github.com/alpeb/go-finance) - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations. ![stars](https://img.shields.io/badge/stars-177-blue)
- [go-finance](https://github.com/pieterclaerhout/go-finance) - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers. ![stars](https://img.shields.io/badge/stars-27-blue)
- [go-finnhub](https://github.com/m1/go-finnhub) - Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges. ![stars](https://img.shields.io/badge/stars-93-blue)
- [go-money](https://github.com/rhymond/go-money) - Implementation of Fowler's Money pattern. ![stars](https://img.shields.io/badge/stars-1710-blue)
- [go-nowpayments](https://github.com/matm/go-nowpayments) - Library for the crypto NOWPayments API. ![stars](https://img.shields.io/badge/stars-3-blue)
- [money](https://github.com/govalues/money) - Immutable monetary amounts and exchange rates with panic-free arithmetic. ![stars](https://img.shields.io/badge/stars-28-blue)
- [ofxgo](https://github.com/aclindsa/ofxgo) - Query OFX servers and/or parse the responses (with example command-line client). ![stars](https://img.shields.io/badge/stars-138-blue)
- [orderbook](https://github.com/i25959341/orderbook) - Matching Engine for Limit Order Book in Golang. ![stars](https://img.shields.io/badge/stars-453-blue)
- [payme](https://github.com/jovandeginste/payme) - QR code generator (ASCII & PNG) for SEPA payments. ![stars](https://img.shields.io/badge/stars-84-blue)
- [sleet](https://github.com/BoltApp/sleet) - One unified interface for multiple Payment Service Providers (PsP) to process online payment. ![stars](https://img.shields.io/badge/stars-140-blue)
- [swift](https://code.pfad.fr/swift/) - Offline validity check of IBAN (International Bank Account Number) and retrieval of BIC (for some countries).
- [techan](https://github.com/sdcoffey/techan) - Technical analysis library with advanced market analysis and trading strategies. ![stars](https://img.shields.io/badge/stars-844-blue)
- [ticker](https://github.com/achannarasappa/ticker) - Terminal stock watcher and stock position tracker. ![stars](https://img.shields.io/badge/stars-5055-blue)
- [transaction](https://github.com/claygod/transaction) - Embedded transactional database of accounts, running in multithreaded mode. ![stars](https://img.shields.io/badge/stars-132-blue)
- [udecimal](https://github.com/quagmt/udecimal) - High performance, high precision, zero allocation fixed-point decimal library for financial applications. ![stars](https://img.shields.io/badge/stars-122-blue)
- [vat](https://github.com/dannyvankooten/vat) - VAT number validation & EU VAT rates. ![stars](https://img.shields.io/badge/stars-111-blue)

**[⬆ back to top](#contents)**

## Forms

_Libraries for working with forms._

- [bind](https://github.com/robfig/bind) - Bind form data to any Go values. ![stars](https://img.shields.io/badge/stars-31-blue)
- [checker](https://github.com/cinar/checker) - Checker helps validating user input through rules defined in struct tags or directly through functions. ![stars](https://img.shields.io/badge/stars-34-blue)
- [conform](https://github.com/leebenson/conform) - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags. ![stars](https://img.shields.io/badge/stars-324-blue)
- [form](https://github.com/go-playground/form) - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support. ![stars](https://img.shields.io/badge/stars-786-blue)
- [formam](https://github.com/monoculum/formam) - decode form's values into a struct. ![stars](https://img.shields.io/badge/stars-192-blue)
- [forms](https://github.com/albrow/forms) - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files. ![stars](https://img.shields.io/badge/stars-138-blue)
- [gbind](https://github.com/bdjimmy/gbind) - Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation ![stars](https://img.shields.io/badge/stars-10-blue)
- [gorilla/csrf](https://github.com/gorilla/csrf) - CSRF protection for Go web applications & services. ![stars](https://img.shields.io/badge/stars-1072-blue)
- [httpin](https://github.com/ggicci/httpin) - Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc. ![stars](https://img.shields.io/badge/stars-327-blue)
- [nosurf](https://github.com/justinas/nosurf) - CSRF protection middleware for Go. ![stars](https://img.shields.io/badge/stars-1607-blue)
- [qs](https://github.com/sonh/qs) - Go module for encoding structs into URL query parameters. ![stars](https://img.shields.io/badge/stars-76-blue)
- [queryparam](https://github.com/tomwright/queryparam) - Decode `url.Values` into usable struct values of standard or custom types. ![stars](https://img.shields.io/badge/stars-19-blue)

**[⬆ back to top](#contents)**

## Functional

_Packages to support functional programming in Go._

- [fp-go](https://github.com/repeale/fp-go) - Collection of Functional Programming helpers powered by Golang 1.18+ generics. ![stars](https://img.shields.io/badge/stars-307-blue)
- [fpGo](https://github.com/TeaEntityLab/fpGo) - Monad, Functional Programming features for Golang. ![stars](https://img.shields.io/badge/stars-351-blue)
- [fuego](https://github.com/seborama/fuego) - Functional Experiment in Go. ![stars](https://img.shields.io/badge/stars-143-blue)
- [go-functional](https://github.com/BooleanCat/go-functional) - Functional programming in Go using generics ![stars](https://img.shields.io/badge/stars-470-blue)
- [go-underscore](https://github.com/tobyhede/go-underscore) - Useful collection of helpfully functional Go collection utilities. ![stars](https://img.shields.io/badge/stars-1300-blue)
- [gofp](https://github.com/rbrahul/gofp) - A lodash like powerful utility library for Golang. ![stars](https://img.shields.io/badge/stars-148-blue)
- [mo](https://github.com/samber/mo) - Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...). ![stars](https://img.shields.io/badge/stars-2751-blue)
- [underscore](https://github.com/rjNemo/underscore) - Functional programming helpers for Go 1.18 and beyond. ![stars](https://img.shields.io/badge/stars-110-blue)
- [valor](https://github.com/phelmkamp/valor) - Generic option and result types that optionally contain a value. ![stars](https://img.shields.io/badge/stars-17-blue)

**[⬆ back to top](#contents)**

## Game Development

_Awesome game development libraries._

- [Azul3D](https://github.com/azul3d/engine) - 3D game engine written in Go. ![stars](https://img.shields.io/badge/stars-621-blue)
- [Ebitengine](https://github.com/hajimehoshi/ebiten) - dead simple 2D game engine in Go. ![stars](https://img.shields.io/badge/stars-11351-blue)
- [ecs](https://github.com/andygeiss/ecs) - Build your own Game-Engine based on the Entity Component System concept in Golang. ![stars](https://img.shields.io/badge/stars-131-blue)
- [engo](https://github.com/EngoEngine/engo) - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm. ![stars](https://img.shields.io/badge/stars-1762-blue)
- [fantasyname](https://github.com/s0rg/fantasyname) - Fantasy names generator. ![stars](https://img.shields.io/badge/stars-34-blue)
- [g3n](https://github.com/g3n/engine) - Go 3D Game Engine. ![stars](https://img.shields.io/badge/stars-2838-blue)
- [go-astar](https://github.com/beefsack/go-astar) - Go implementation of the A\* path finding algorithm. ![stars](https://img.shields.io/badge/stars-602-blue)
- [go-sdl2](https://github.com/veandco/go-sdl2) - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/). ![stars](https://img.shields.io/badge/stars-2250-blue)
- [go3d](https://github.com/ungerik/go3d) - Performance oriented 2D/3D math package for Go. ![stars](https://img.shields.io/badge/stars-317-blue)
- [gonet](https://github.com/xtaci/gonet) - Game server skeleton implemented with golang. ![stars](https://img.shields.io/badge/stars-1273-blue)
- [goworld](https://github.com/xiaonanln/goworld) - Scalable game server engine, featuring space-entity framework and hot-swapping. ![stars](https://img.shields.io/badge/stars-2587-blue)
- [grid](https://github.com/s0rg/grid) - Generic 2D grid with ray-casting, shadow-casting and path finding. ![stars](https://img.shields.io/badge/stars-18-blue)
- [Harfang3D](https://github.com/harfang3d/harfang3d) - 3D engine for the Go language, works on Windows and Linux ([Harfang on Go.dev](https://github.com/harfang3d/harfang-go)). ![stars](https://img.shields.io/badge/stars-589-blue)
- [Leaf](https://github.com/name5566/leaf) - Lightweight game server framework. ![stars](https://img.shields.io/badge/stars-5335-blue)
- [nano](https://github.com/lonng/nano) - Lightweight, facility, high performance golang based game server framework. ![stars](https://img.shields.io/badge/stars-2922-blue)
- [Oak](https://github.com/oakmound/oak) - Pure Go game engine. ![stars](https://img.shields.io/badge/stars-1575-blue)
- [Pitaya](https://github.com/topfreegames/pitaya) - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK. ![stars](https://img.shields.io/badge/stars-2416-blue)
- [Pixel](https://github.com/gopxl/pixel) - Hand-crafted 2D game library in Go. ![stars](https://img.shields.io/badge/stars-270-blue)
- [prototype](https://github.com/gonutz/prototype) - Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API. ![stars](https://img.shields.io/badge/stars-88-blue)
- [raylib-go](https://github.com/gen2brain/raylib-go) - Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming. ![stars](https://img.shields.io/badge/stars-1790-blue)
- [termloop](https://github.com/JoelOtter/termloop) - Terminal-based game engine for Go, built on top of Termbox. ![stars](https://img.shields.io/badge/stars-1442-blue)
- [tile](https://github.com/kelindar/tile) - Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export. ![stars](https://img.shields.io/badge/stars-176-blue)

**[⬆ back to top](#contents)**

## Generators

_Tools that generate Go code._

- [convergen](https://github.com/reedom/convergen) - Feature rich type-to-type copy code generator. ![stars](https://img.shields.io/badge/stars-43-blue)
- [copygen](https://github.com/switchupcb/copygen) - Generate type-to-type and type-based code without reflection. ![stars](https://img.shields.io/badge/stars-359-blue)
- [generis](https://github.com/senselogic/GENERIS) - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating. ![stars](https://img.shields.io/badge/stars-43-blue)
- [go-enum](https://github.com/abice/go-enum) - Code generation for enums from code comments. ![stars](https://img.shields.io/badge/stars-777-blue)
- [go-enum-encoding](https://github.com/nikolaydubina/go-enum-encoding) - Code generation for enum encoding from code comments. ![stars](https://img.shields.io/badge/stars-14-blue)
- [go-linq](https://github.com/ahmetalpbalkan/go-linq) - .NET LINQ-like query methods for Go. ![stars](https://img.shields.io/badge/stars-3544-blue)
- [goderive](https://github.com/awalterschulze/goderive) - Derives functions from input types ![stars](https://img.shields.io/badge/stars-1249-blue)
- [goverter](https://github.com/jmattheis/goverter) - Generate converters by defining an interface. ![stars](https://img.shields.io/badge/stars-604-blue)
- [GoWrap](https://github.com/hexdigest/gowrap) - Generate decorators for Go interfaces using simple templates. ![stars](https://img.shields.io/badge/stars-1131-blue)
- [interfaces](https://github.com/rjeczalik/interfaces) - Command line tool for generating interface definitions. ![stars](https://img.shields.io/badge/stars-425-blue)
- [jennifer](https://github.com/dave/jennifer) - Generate arbitrary Go code without templates. ![stars](https://img.shields.io/badge/stars-3406-blue)
- [oapi-codegen](https://github.com/deepmap/oapi-codegen) - This package contains a set of utilities for generating Go boilerplate code for services based on OpenAPI 3.0 API definitions. ![stars](https://img.shields.io/badge/stars-6534-blue)
- [typeregistry](https://github.com/xiaoxin01/typeregistry) - A library to create type dynamically. ![stars](https://img.shields.io/badge/stars-25-blue)

**[⬆ back to top](#contents)**

## Geographic

_Geographic tools and servers_

- [geoos](https://github.com/spatial-go/geoos) - A library provides spatial data and geometric algorithms. ![stars](https://img.shields.io/badge/stars-622-blue)
- [geoserver](https://github.com/hishamkaram/geoserver) - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API. ![stars](https://img.shields.io/badge/stars-90-blue)
- [gismanager](https://github.com/hishamkaram/gismanager) - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver. ![stars](https://img.shields.io/badge/stars-54-blue)
- [godal](https://github.com/airbusgeo/godal) - Go wrapper for GDAL. ![stars](https://img.shields.io/badge/stars-145-blue)
- [H3](https://github.com/uber/h3-go) - Go bindings for H3, a hierarchical hexagonal geospatial indexing system. ![stars](https://img.shields.io/badge/stars-326-blue)
- [H3 GeoJSON](https://github.com/mmadfox/go-geojson2h3) - Conversion utilities between H3 indexes and GeoJSON. ![stars](https://img.shields.io/badge/stars-4-blue)
- [H3GeoDist](https://github.com/mmadfox/go-h3geo-dist) - Distribution of Uber H3geo cells by virtual nodes. ![stars](https://img.shields.io/badge/stars-2-blue)
- [mbtileserver](https://github.com/consbio/mbtileserver) - A simple Go-based server for map tiles stored in mbtiles format. ![stars](https://img.shields.io/badge/stars-677-blue)
- [osm](https://github.com/paulmach/osm) - Library for reading, writing and working with OpenStreetMap data and APIs. ![stars](https://img.shields.io/badge/stars-383-blue)
- [pbf](https://github.com/maguro/pbf) - OpenStreetMap PBF golang encoder/decoder. ![stars](https://img.shields.io/badge/stars-49-blue)
- [S2 geojson](https://github.com/pantrif/s2-geojson) - Convert geojson to s2 cells & demonstrating some S2 geometry features on map. ![stars](https://img.shields.io/badge/stars-33-blue)
- [S2 geometry](https://github.com/golang/geo) - S2 geometry library in Go. ![stars](https://img.shields.io/badge/stars-1716-blue)
- [simplefeatures](https://github.com/peterstace/simplefeatures) - simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them. ![stars](https://img.shields.io/badge/stars-135-blue)
- [Tile38](https://github.com/tidwall/tile38) - Geolocation DB with spatial index and realtime geofencing. ![stars](https://img.shields.io/badge/stars-9217-blue)
- [Web-Mercator-Projection](https://github.com/jorelosorio/web-mercator-projection) A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection. ![stars](https://img.shields.io/badge/stars-9-blue)
- [WGS84](https://github.com/wroge/wgs84) - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM). ![stars](https://img.shields.io/badge/stars-132-blue)

**[⬆ back to top](#contents)**

## Go Compilers

_Tools for compiling Go to other languages._

- [c2go](https://github.com/goplus/c2go) - Convert C code to Go code. ![stars](https://img.shields.io/badge/stars-303-blue)
- [c4go](https://github.com/Konstantin8105/c4go) - Transpile C code to Go code. ![stars](https://img.shields.io/badge/stars-366-blue)
- [esp32](https://github.com/andygeiss/esp32-transpiler) - Transpile Go into Arduino code. ![stars](https://img.shields.io/badge/stars-88-blue)
- [f4go](https://github.com/Konstantin8105/f4go) - Transpile FORTRAN 77 code to Go code. ![stars](https://img.shields.io/badge/stars-47-blue)
- [gopherjs](https://github.com/gopherjs/gopherjs) - Compiler from Go to JavaScript. ![stars](https://img.shields.io/badge/stars-12812-blue)
- [tardisgo](https://github.com/tardisgo/tardisgo) - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler. ![stars](https://img.shields.io/badge/stars-431-blue)

**[⬆ back to top](#contents)**

## Goroutines

_Tools for managing and working with Goroutines._

- [ants](https://github.com/panjf2000/ants) - A high-performance and low-cost goroutine pool in Go. ![stars](https://img.shields.io/badge/stars-13172-blue)
- [artifex](https://github.com/borderstech/artifex) - Simple in-memory job queue for Golang using worker-based dispatching. ![stars](https://img.shields.io/badge/stars-209-blue)
- [async](https://github.com/yaitoo/async) - An asynchronous task package with async/await style for Go. ![stars](https://img.shields.io/badge/stars-9-blue)
- [async](https://github.com/reugn/async) - An alternative sync library for Go (Future, Promise, Locks). ![stars](https://img.shields.io/badge/stars-231-blue)
- [async](https://github.com/studiosol/async) - A safe way to execute functions asynchronously, recovering them in case of panic. ![stars](https://img.shields.io/badge/stars-137-blue)
- [async-job](https://github.com/lab210-dev/async-job) - AsyncJob is an asynchronous queue job manager with light code, clear and speed. ![stars](https://img.shields.io/badge/stars-11-blue)
- [breaker](https://github.com/kamilsk/breaker) - Flexible mechanism to make execution flow interruptible. ![stars](https://img.shields.io/badge/stars-18-blue)
- [channelify](https://github.com/ddelizia/channelify) - Transform your function to return channels for easy and powerful parallel processing. ![stars](https://img.shields.io/badge/stars-32-blue)
- [conc](https://github.com/sourcegraph/conc) - `conc` is your toolbelt for structured concurrency in go, making common tasks easier and safer. ![stars](https://img.shields.io/badge/stars-9560-blue)
- [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) - Concurrency limiter with support for timeouts, dynamic priority and context cancellation of goroutines. ![stars](https://img.shields.io/badge/stars-17-blue)
- [conexec](https://github.com/ITcathyh/conexec) - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency. ![stars](https://img.shields.io/badge/stars-16-blue)
- [cyclicbarrier](https://github.com/marusama/cyclicbarrier) - CyclicBarrier for golang. ![stars](https://img.shields.io/badge/stars-149-blue)
- [execpool](https://github.com/hexdigest/execpool) - A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command. ![stars](https://img.shields.io/badge/stars-29-blue)
- [flowmatic](https://github.com/carlmjohnson/flowmatic) - Structured concurrency made easy. ![stars](https://img.shields.io/badge/stars-371-blue)
- [go-accumulator](https://github.com/nar10z/go-accumulator) - Solution for accumulation of events and their subsequent processing. ![stars](https://img.shields.io/badge/stars-7-blue)
- [go-actor](https://github.com/vladopajic/go-actor) - A tiny library for writing concurrent programs using actor model. ![stars](https://img.shields.io/badge/stars-172-blue)
- [go-floc](https://github.com/workanator/go-floc) - Orchestrate goroutines with ease. ![stars](https://img.shields.io/badge/stars-270-blue)
- [go-flow](https://github.com/kamildrazkiewicz/go-flow) - Control goroutines execution order. ![stars](https://img.shields.io/badge/stars-220-blue)
- [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) - Manage a pool of goroutines using this lightweight library with a simple API. ![stars](https://img.shields.io/badge/stars-15-blue)
- [go-trylock](https://github.com/subchen/go-trylock) - TryLock support on read-write lock for Golang. ![stars](https://img.shields.io/badge/stars-35-blue)
- [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) - Like `sync.WaitGroup` with error handling and concurrency control. ![stars](https://img.shields.io/badge/stars-48-blue)
- [go-workerpool](https://github.com/zenthangplus/go-workerpool) - Inspired from Java Thread Pool, Go WorkerPool aims to control heavy Go Routines. ![stars](https://img.shields.io/badge/stars-12-blue)
- [go-workers](https://github.com/catmullet/go-workers) - Easily and safely run workers for large data processing pipelines. ![stars](https://img.shields.io/badge/stars-165-blue)
- [goccm](https://github.com/zenthangplus/goccm) - Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently. ![stars](https://img.shields.io/badge/stars-73-blue)
- [gohive](https://github.com/loveleshsharma/gohive) - A highly performant and easy to use Goroutine pool for Go. ![stars](https://img.shields.io/badge/stars-52-blue)
- [gollback](https://github.com/vardius/gollback) - asynchronous simple function utilities, for managing execution of closures and callbacks. ![stars](https://img.shields.io/badge/stars-125-blue)
- [gowl](https://github.com/hamed-yousefi/gowl) - Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status. ![stars](https://img.shields.io/badge/stars-70-blue)
- [goworker](https://github.com/benmanns/goworker) - goworker is a Go-based background worker. ![stars](https://img.shields.io/badge/stars-2806-blue)
- [gowp](https://github.com/xxjwxc/gowp) - gowp is concurrency limiting goroutine pool. ![stars](https://img.shields.io/badge/stars-520-blue)
- [gpool](https://github.com/Sherifabdlnaby/gpool) - manages a resizeable pool of context-aware goroutines to bound concurrency. ![stars](https://img.shields.io/badge/stars-90-blue)
- [grpool](https://github.com/ivpusic/grpool) - Lightweight Goroutine pool. ![stars](https://img.shields.io/badge/stars-746-blue)
- [hands](https://github.com/duanckham/hands) - A process controller used to control the execution and return strategies of multiple goroutines. ![stars](https://img.shields.io/badge/stars-10-blue)
- [Hunch](https://github.com/AaronJan/Hunch) - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive. ![stars](https://img.shields.io/badge/stars-104-blue)
- [kyoo](https://github.com/dirkaholic/kyoo) - Provides an unlimited job queue and concurrent worker pools. ![stars](https://img.shields.io/badge/stars-50-blue)
- [neilotoole/errgroup](https://github.com/neilotoole/errgroup) - Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines. ![stars](https://img.shields.io/badge/stars-162-blue)
- [nursery](https://github.com/arunsworld/nursery) - Structured concurrency in Go. ![stars](https://img.shields.io/badge/stars-68-blue)
- [oversight](https://pkg.go.dev/cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
- [parallel-fn](https://github.com/rafaeljesus/parallel-fn) - Run functions in parallel. ![stars](https://img.shields.io/badge/stars-36-blue)
- [pond](https://github.com/alitto/pond) - Minimalistic and High-performance goroutine worker pool written in Go. ![stars](https://img.shields.io/badge/stars-1589-blue)
- [pool](https://github.com/go-playground/pool) - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation. ![stars](https://img.shields.io/badge/stars-729-blue)
- [rill](https://github.com/destel/rill) - Go toolkit for clean, composable, channel-based concurrency.  ![stars](https://img.shields.io/badge/stars-1489-blue)
- [routine](https://github.com/timandy/routine) - `routine` is a `ThreadLocal` for go library. It encapsulates and provides some easy-to-use, non-competitive, high-performance `goroutine` context access interfaces, which can help you access coroutine context information more gracefully. ![stars](https://img.shields.io/badge/stars-242-blue)
- [routine](https://github.com/x-mod/routine) - go routine control with context, support: Main, Go, Pool and some useful Executors. ![stars](https://img.shields.io/badge/stars-61-blue)
- [semaphore](https://github.com/kamilsk/semaphore) - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context. ![stars](https://img.shields.io/badge/stars-103-blue)
- [semaphore](https://github.com/marusama/semaphore) - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations). ![stars](https://img.shields.io/badge/stars-176-blue)
- [stl](https://github.com/ssgreg/stl) - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism. ![stars](https://img.shields.io/badge/stars-30-blue)
- [threadpool](https://github.com/shettyh/threadpool) - Golang threadpool implementation. ![stars](https://img.shields.io/badge/stars-102-blue)
- [tunny](https://github.com/Jeffail/tunny) - Goroutine pool for golang. ![stars](https://img.shields.io/badge/stars-3937-blue)
- [worker-pool](https://github.com/vardius/worker-pool) - goworker is a Go simple async worker pool. ![stars](https://img.shields.io/badge/stars-92-blue)
- [workerpool](https://github.com/gammazero/workerpool) - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued. ![stars](https://img.shields.io/badge/stars-1350-blue)

**[⬆ back to top](#contents)**

## GUI

_Libraries for building GUI Applications._

_Toolkits_

- [app](https://github.com/murlokswarm/app) - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress. ![stars](https://img.shields.io/badge/stars-8075-blue)
- [cimgui-go](https://github.com/AllenDang/cimgui-go) - Auto generated Go wrapper for [Dear ImGui](https://github.com/ocornut/imgui) via [cimgui](https://github.com/cimgui/cimgui). ![stars](https://img.shields.io/badge/stars-373-blue)
- [Cogent Core](https://github.com/cogentcore/core) - A framework for building 2D and 3D apps that run on macOS, Windows, Linux, iOS, Android, and the web. ![stars](https://img.shields.io/badge/stars-1827-blue)
- [DarwinKit](https://github.com/progrium/darwinkit) - Build native macOS applications using Go. ![stars](https://img.shields.io/badge/stars-5087-blue)
- [energy](https://github.com/energye/energy) - Cross-platform based on LCL(Native System UI Control Library) and CEF(Chromium Embedded Framework) (Windows/ macOS / Linux) ![stars](https://img.shields.io/badge/stars-407-blue)
- [fyne](https://github.com/fyne-io/fyne) - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android. ![stars](https://img.shields.io/badge/stars-25543-blue)
- [gio](https://gioui.org) - Gio is a library for writing cross-platform immediate mode GUI-s in Go. Gio supports all the major platforms: Linux, macOS, Windows, Android, iOS, FreeBSD, OpenBSD and WebAssembly.
- [go-gtk](https://mattn.github.io/go-gtk/) - Go bindings for GTK.
- [go-sciter](https://github.com/sciter-sdk/go-sciter) - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform. ![stars](https://img.shields.io/badge/stars-2588-blue)
- [Goey](https://bitbucket.org/rj/goey/src/master/) - Cross platform UI toolkit aggregator for Windows / Linux / Mac. GTK, Cocoa, Windows API
- [goradd/html5tag](https://github.com/goradd/html5tag) - Library for outputting HTML5 tags. ![stars](https://img.shields.io/badge/stars-10-blue)
- [gotk3](https://github.com/gotk3/gotk3) - Go bindings for GTK3. ![stars](https://img.shields.io/badge/stars-2123-blue)
- [gowd](https://github.com/dtylman/gowd) - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform. ![stars](https://img.shields.io/badge/stars-434-blue)
- [qt](https://github.com/therecipe/qt) - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi). ![stars](https://img.shields.io/badge/stars-10544-blue)
- [Spot](https://github.com/roblillack/spot) - Reactive, cross-platform desktop GUI toolkit. ![stars](https://img.shields.io/badge/stars-1154-blue)
- [ui](https://github.com/andlabs/ui) - Platform-native GUI library for Go. Cross platform. ![stars](https://img.shields.io/badge/stars-8342-blue)
- [unison](https://github.com/richardwilkes/unison) - A unified graphical user experience toolkit for Go desktop applications. macOS, Windows, and Linux are supported. ![stars](https://img.shields.io/badge/stars-220-blue)
- [Wails](https://wails.io) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
- [walk](https://github.com/lxn/walk) - Windows application library kit for Go. ![stars](https://img.shields.io/badge/stars-6898-blue)
- [webview](https://github.com/zserge/webview) - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux). ![stars](https://img.shields.io/badge/stars-12799-blue)

_Interaction_

- [AppIndicator Go](https://github.com/gopherlibs/appindicator) - Go bindings for libappindicator3 C library. ![stars](https://img.shields.io/badge/stars-6-blue)
- [gosx-notifier](https://github.com/deckarep/gosx-notifier) - OSX Desktop Notifications library for Go. ![stars](https://img.shields.io/badge/stars-588-blue)
- [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) - OSX library to notify about any (pluggable) activity on your machine. ![stars](https://img.shields.io/badge/stars-29-blue)
- [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) - OSX Sleep/Wake notifications in golang. ![stars](https://img.shields.io/badge/stars-36-blue)
- [robotgo](https://github.com/go-vgo/robotgo) - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other. ![stars](https://img.shields.io/badge/stars-9819-blue)
- [systray](https://github.com/getlantern/systray) - Cross platform Go library to place an icon and menu in the notification area. ![stars](https://img.shields.io/badge/stars-3376-blue)
- [trayhost](https://github.com/shurcooL/trayhost) - Cross-platform Go library to place an icon in the host operating system's taskbar. ![stars](https://img.shields.io/badge/stars-254-blue)
- [zenity](https://github.com/ncruces/zenity) - Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user. ![stars](https://img.shields.io/badge/stars-758-blue)

**[⬆ back to top](#contents)**

## Hardware

_Libraries, tools, and tutorials for interacting with hardware._

- [arduino-cli](https://github.com/arduino/arduino-cli) - Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects. ![stars](https://img.shields.io/badge/stars-4436-blue)
- [emgo](https://github.com/ziutek/emgo) - Go-like language for programming embedded systems (e.g. STM32 MCU). ![stars](https://img.shields.io/badge/stars-1077-blue)
- [ghw](https://github.com/jaypipes/ghw) - Golang hardware discovery/inspection library. ![stars](https://img.shields.io/badge/stars-1664-blue)
- [go-osc](https://github.com/hypebeast/go-osc) - Open Sound Control (OSC) bindings for Go. ![stars](https://img.shields.io/badge/stars-205-blue)
- [go-rpio](https://github.com/stianeikeland/go-rpio) - GPIO for Go, doesn't require cgo. ![stars](https://img.shields.io/badge/stars-2211-blue)
- [goroslib](https://github.com/aler9/goroslib) - Robot Operating System (ROS) library for Go. ![stars](https://img.shields.io/badge/stars-345-blue)
- [joystick](https://github.com/0xcafed00d/joystick) - a polled API to read the state of an attached joystick. ![stars](https://img.shields.io/badge/stars-65-blue)
- [sysinfo](https://github.com/zcalusic/sysinfo) - A pure Go library providing Linux OS / kernel / hardware system information. ![stars](https://img.shields.io/badge/stars-538-blue)

**[⬆ back to top](#contents)**

## Images

_Libraries for manipulating images._

- [bild](https://github.com/anthonynsimon/bild) - Collection of image processing algorithms in pure Go. ![stars](https://img.shields.io/badge/stars-4037-blue)
- [bimg](https://github.com/h2non/bimg) - Small package for fast and efficient image processing using libvips. ![stars](https://img.shields.io/badge/stars-2754-blue)
- [cameron](https://github.com/aofei/cameron) - An avatar generator for Go. ![stars](https://img.shields.io/badge/stars-124-blue)
- [canvas](https://github.com/tdewolff/canvas) - Vector graphics to PDF, SVG or rasterized image. ![stars](https://img.shields.io/badge/stars-1536-blue)
- [color-extractor](https://github.com/marekm4/color-extractor) - Dominant color extractor with no external dependencies. ![stars](https://img.shields.io/badge/stars-94-blue)
- [darkroom](https://github.com/gojek/darkroom) - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency. ![stars](https://img.shields.io/badge/stars-228-blue)
- [draft](https://github.com/lucasepe/draft) - Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax. ![stars](https://img.shields.io/badge/stars-582-blue)
- [geopattern](https://github.com/pravj/geopattern) - Create beautiful generative image patterns from a string. ![stars](https://img.shields.io/badge/stars-1271-blue)
- [gg](https://github.com/fogleman/gg) - 2D rendering in pure Go. ![stars](https://img.shields.io/badge/stars-4470-blue)
- [gift](https://github.com/disintegration/gift) - Package of image processing filters. ![stars](https://img.shields.io/badge/stars-1760-blue)
- [gltf](https://github.com/qmuntal/gltf) - Efficient and robust glTF 2.0 reader, writer and validator. ![stars](https://img.shields.io/badge/stars-247-blue)
- [go-cairo](https://github.com/ungerik/go-cairo) - Go binding for the cairo graphics library. ![stars](https://img.shields.io/badge/stars-146-blue)
- [go-gd](https://github.com/bolknote/go-gd) - Go binding for GD library. ![stars](https://img.shields.io/badge/stars-59-blue)
- [go-nude](https://github.com/koyachi/go-nude) - Nudity detection with Go. ![stars](https://img.shields.io/badge/stars-417-blue)
- [go-qrcode](https://github.com/yeqown/go-qrcode) - Generate QR codes with personalized styles, allowing adjustments to color, block size, shape, and icons. ![stars](https://img.shields.io/badge/stars-609-blue)
- [go-webcolors](https://github.com/jyotiska/go-webcolors) - Port of webcolors library from Python to Go. ![stars](https://img.shields.io/badge/stars-28-blue)
- [go-webp](https://github.com/kolesa-team/go-webp) - Library for encode and decode webp pictures, using libwebp. ![stars](https://img.shields.io/badge/stars-235-blue)
- [gocv](https://github.com/hybridgroup/gocv) - Go package for computer vision using OpenCV 3.3+. ![stars](https://img.shields.io/badge/stars-6823-blue)
- [goimagehash](https://github.com/corona10/goimagehash) - Go Perceptual image hashing package. ![stars](https://img.shields.io/badge/stars-761-blue)
- [goimghdr](https://github.com/corona10/goimghdr) - The imghdr module determines the type of image contained in a file for Go. ![stars](https://img.shields.io/badge/stars-40-blue)
- [govatar](https://github.com/o1egl/govatar) - Library and CMD tool for generating funny avatars. ![stars](https://img.shields.io/badge/stars-590-blue)
- [govips](https://github.com/davidbyttow/govips) - A lightning fast image processing and resizing library for Go. ![stars](https://img.shields.io/badge/stars-1348-blue)
- [gowitness](https://github.com/sensepost/gowitness) - Screenshoting webpages using go and headless chrome on command line. ![stars](https://img.shields.io/badge/stars-3451-blue)
- [gridder](https://github.com/shomali11/gridder) - A Grid based 2D Graphics library. ![stars](https://img.shields.io/badge/stars-77-blue)
- [image2ascii](https://github.com/qeesung/image2ascii) - Convert image to ASCII. ![stars](https://img.shields.io/badge/stars-900-blue)
- [imagick](https://github.com/gographics/imagick) - Go binding to ImageMagick's MagickWand C API. ![stars](https://img.shields.io/badge/stars-1791-blue)
- [imaginary](https://github.com/h2non/imaginary) - Fast and simple HTTP microservice for image resizing. ![stars](https://img.shields.io/badge/stars-5725-blue)
- [imaging](https://github.com/disintegration/imaging) - Simple Go image processing package. ![stars](https://img.shields.io/badge/stars-5332-blue)
- [imagor](https://github.com/cshum/imagor) - Fast, secure image processing server and Go library, using libvips. ![stars](https://img.shields.io/badge/stars-3510-blue)
- [img](https://github.com/hawx/img) - Selection of image manipulation tools. ![stars](https://img.shields.io/badge/stars-155-blue)
- [ln](https://github.com/fogleman/ln) - 3D line art rendering in Go. ![stars](https://img.shields.io/badge/stars-3295-blue)
- [mergi](https://github.com/noelyahan/mergi) - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate). ![stars](https://img.shields.io/badge/stars-237-blue)
- [mort](https://github.com/aldor007/mort) - Storage and image processing server written in Go. ![stars](https://img.shields.io/badge/stars-513-blue)
- [mpo](https://github.com/donatj/mpo) - Decoder and conversion tool for MPO 3D Photos. ![stars](https://img.shields.io/badge/stars-17-blue)
- [picfit](https://github.com/thoas/picfit) - An image resizing server written in Go. ![stars](https://img.shields.io/badge/stars-2160-blue)
- [pt](https://github.com/fogleman/pt) - Path tracing engine written in Go. ![stars](https://img.shields.io/badge/stars-2085-blue)
- [rez](https://github.com/bamiaux/rez) - Image resizing in pure Go and SIMD. ![stars](https://img.shields.io/badge/stars-213-blue)
- [scout](https://github.com/jonoton/scout) - Scout is a standalone open source software solution for DIY video security. ![stars](https://img.shields.io/badge/stars-16-blue)
- [smartcrop](https://github.com/muesli/smartcrop) - Finds good crops for arbitrary images and crop sizes. ![stars](https://img.shields.io/badge/stars-1827-blue)
- [steganography](https://github.com/auyer/steganography) - Pure Go Library for LSB steganography. ![stars](https://img.shields.io/badge/stars-323-blue)
- [stegify](https://github.com/DimitarPetrov/stegify) - Go tool for LSB steganography, capable of hiding any file within an image. ![stars](https://img.shields.io/badge/stars-1222-blue)
- [svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation. ![stars](https://img.shields.io/badge/stars-2168-blue)
- [transformimgs](https://github.com/Pixboost/transformimgs) - Transformimgs resizes and optimises images for Web using next-generation formats. ![stars](https://img.shields.io/badge/stars-243-blue)
- [webp-server](https://github.com/mehdipourfar/webp-server) - Simple and minimal image server capable of storing, resizing, converting and caching images. ![stars](https://img.shields.io/badge/stars-74-blue)

**[⬆ back to top](#contents)**

## IoT (Internet of Things)

_Libraries for programming devices of the IoT._

- [connectordb](https://github.com/connectordb/connectordb) - Open-Source Platform for Quantified Self & IoT. ![stars](https://img.shields.io/badge/stars-407-blue)
- [devices](https://github.com/goiot/devices) - Suite of libraries for IoT devices, experimental for x/exp/io. ![stars](https://img.shields.io/badge/stars-264-blue)
- [ekuiper](https://github.com/lf-edge/ekuiper) - Lightweight data stream processing engine for IoT edge. ![stars](https://img.shields.io/badge/stars-1517-blue)
- [eywa](https://github.com/xcodersun/eywa) - Project Eywa is essentially a connection manager that keeps track of connected devices. ![stars](https://img.shields.io/badge/stars-64-blue)
- [flogo](https://github.com/tibcosoftware/flogo) - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration. ![stars](https://img.shields.io/badge/stars-2438-blue)
- [gatt](https://github.com/paypal/gatt) - Gatt is a Go package for building Bluetooth Low Energy peripherals. ![stars](https://img.shields.io/badge/stars-1145-blue)
- [gobot](https://github.com/hybridgroup/gobot/) - Gobot is a framework for robotics, physical computing, and the Internet of Things. ![stars](https://img.shields.io/badge/stars-9037-blue)
- [huego](https://github.com/amimof/huego) - An extensive Philips Hue client library for Go. ![stars](https://img.shields.io/badge/stars-251-blue)
- [iot](https://github.com/vaelen/iot/) - IoT is a simple framework for implementing a Google IoT Core device. ![stars](https://img.shields.io/badge/stars-66-blue)
- [mainflux](https://github.com/Mainflux/mainflux) - Industrial IoT Messaging and Device Management Server. ![stars](https://img.shields.io/badge/stars-44-blue)
- [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
- [rulego](https://github.com/rulego/rulego) - RuleGo is a lightweight, high-performance, embedded, orchestrable component-based rule engine for IoT edge. ![stars](https://img.shields.io/badge/stars-946-blue)
- [sensorbee](https://github.com/sensorbee/sensorbee) - Lightweight stream processing engine for IoT. ![stars](https://img.shields.io/badge/stars-231-blue)
- [shifu](https://github.com/Edgenesis/shifu) - Kubernetes native IoT development framework. ![stars](https://img.shields.io/badge/stars-1299-blue)
- [smart-home](https://github.com/e154/smart-home) - Software package for IoT automation. ![stars](https://img.shields.io/badge/stars-87-blue)

**[⬆ back to top](#contents)**

## Job Scheduler

_Libraries for scheduling jobs._
- [cdule](https://github.com/deepaksinghvi/cdule) - Job scheduler library with database support ![stars](https://img.shields.io/badge/stars-55-blue)
- [cheek](https://github.com/datarootsio/cheek) - A simple crontab like scheduler that aims to offer a KISS approach to job scheduling. ![stars](https://img.shields.io/badge/stars-167-blue)
- [clockwerk](https://github.com/onatm/clockwerk) - Go package to schedule periodic jobs using a simple, fluent syntax. ![stars](https://img.shields.io/badge/stars-163-blue)
- [cronticker](https://github.com/krayzpipes/cronticker) - A ticker implementation to support cron schedules. ![stars](https://img.shields.io/badge/stars-16-blue)
- [go-cron](https://github.com/rk/go-cron) - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons. ![stars](https://img.shields.io/badge/stars-235-blue)
- [go-quartz](https://github.com/reugn/go-quartz) - Simple, zero-dependency scheduling library for Go. ![stars](https://img.shields.io/badge/stars-1816-blue)
- [gocron](https://github.com/go-co-op/gocron) - Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron). ![stars](https://img.shields.io/badge/stars-5848-blue)
- [goflow](https://github.com/fieldryand/goflow) - A simple but powerful DAG scheduler and dashboard. ![stars](https://img.shields.io/badge/stars-404-blue)
- [gron](https://github.com/roylee0704/gron) - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly. ![stars](https://img.shields.io/badge/stars-1034-blue)
- [gronx](https://github.com/adhocore/gronx) - Cron expression parser, task runner and daemon consuming crontab like task list. ![stars](https://img.shields.io/badge/stars-426-blue)
- [JobRunner](https://github.com/bamzi/jobrunner) - Smart and featureful cron job scheduler with job queuing and live monitoring built in. ![stars](https://img.shields.io/badge/stars-1060-blue)
- [leprechaun](https://github.com/kilgaloon/leprechaun) - Job scheduler that supports webhooks, crons and classic scheduling. ![stars](https://img.shields.io/badge/stars-104-blue)
- [sched](https://github.com/romshark/sched) - A job scheduler with the ability to fast-forward time. ![stars](https://img.shields.io/badge/stars-28-blue)
- [scheduler](https://github.com/carlescere/scheduler) - Cronjobs scheduling made easy. ![stars](https://img.shields.io/badge/stars-450-blue)
- [tasks](https://github.com/madflojo/tasks) - An easy to use in-process scheduler for recurring tasks in Go. ![stars](https://img.shields.io/badge/stars-306-blue)

**[⬆ back to top](#contents)**

## JSON

_Libraries for working with JSON._

- [ajson](https://github.com/spyzhov/ajson) - Abstract JSON for golang with JSONPath support. ![stars](https://img.shields.io/badge/stars-251-blue)
- [ask](https://github.com/simonnilsson/ask) - Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types. ![stars](https://img.shields.io/badge/stars-49-blue)
- [dynjson](https://github.com/cocoonspace/dynjson) - Client-customizable JSON formats for dynamic APIs. ![stars](https://img.shields.io/badge/stars-16-blue)
- [ej](https://github.com/lucassscaravelli/ej) - Write and read JSON from different sources succinctly. ![stars](https://img.shields.io/badge/stars-10-blue)
- [epoch](https://github.com/vtopc/epoch) - Contains primitives for marshaling/unmarshalling Unix timestamp/epoch to/from build-in time.Time type in JSON. ![stars](https://img.shields.io/badge/stars-14-blue)
- [fastjson](https://github.com/valyala/fastjson) - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection. ![stars](https://img.shields.io/badge/stars-2332-blue)
- [gabs](https://github.com/Jeffail/gabs) - For parsing, creating and editing unknown or dynamic JSON in Go. ![stars](https://img.shields.io/badge/stars-3491-blue)
- [gjo](https://github.com/skanehira/gjo) - Small utility to create JSON objects. ![stars](https://img.shields.io/badge/stars-128-blue)
- [GJSON](https://github.com/tidwall/gjson) - Get a JSON value with one line of code. ![stars](https://img.shields.io/badge/stars-14569-blue)
- [go-jsonerror](https://github.com/ddymko/go-jsonerror) - Go-JsonError is meant to allow us to easily create json response errors that follow the JsonApi spec. ![stars](https://img.shields.io/badge/stars-16-blue)
- [go-respond](https://github.com/nicklaw5/go-respond) - Go package for handling common HTTP JSON responses. ![stars](https://img.shields.io/badge/stars-55-blue)
- [gojmapr](https://github.com/limiu82214/gojmapr) - Get simple struct from complex json by json path. ![stars](https://img.shields.io/badge/stars-22-blue)
- [gojq](https://github.com/elgs/gojq) - JSON query in Golang. ![stars](https://img.shields.io/badge/stars-191-blue)
- [gojson](https://github.com/ChimeraCoder/gojson) - Automatically generate Go (golang) struct definitions from example JSON. ![stars](https://img.shields.io/badge/stars-2673-blue)
- [htmljson](https://github.com/nikolaydubina/htmljson) - Rich rendering of JSON as HTML in Go. ![stars](https://img.shields.io/badge/stars-7-blue)
- [JayDiff](https://github.com/yazgazan/jaydiff) - JSON diff utility written in Go. ![stars](https://img.shields.io/badge/stars-105-blue)
- [jettison](https://github.com/wI2L/jettison) - Fast and flexible JSON encoder for Go. ![stars](https://img.shields.io/badge/stars-177-blue)
- [jscan](https://github.com/romshark/jscan) - High performance zero-allocation JSON iterator. ![stars](https://img.shields.io/badge/stars-90-blue)
- [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
- [JSON-to-Proto](https://json-to-proto.github.io/) - Convert JSON to Protobuf online.
- [json2go](https://github.com/m-zajac/json2go) - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all. ![stars](https://img.shields.io/badge/stars-133-blue)
- [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) - Go bindings based on the JSON API errors reference. ![stars](https://img.shields.io/badge/stars-13-blue)
- [jsoncolor](https://github.com/neilotoole/jsoncolor) - Drop-in replacement for `encoding/json` that outputs colorized JSON. ![stars](https://img.shields.io/badge/stars-46-blue)
- [jsondiff](https://github.com/wI2L/jsondiff) - JSON diff library for Go based on RFC6902 (JSON Patch). ![stars](https://img.shields.io/badge/stars-536-blue)
- [jsonf](https://github.com/miolini/jsonf) - Console tool for highlighted formatting and struct query fetching JSON. ![stars](https://img.shields.io/badge/stars-65-blue)
- [jsongo](https://github.com/ricardolonga/jsongo) - Fluent API to make it easier to create Json objects. ![stars](https://img.shields.io/badge/stars-109-blue)
- [jsonhal](https://github.com/RichardKnop/jsonhal) - Simple Go package to make custom structs marshal into HAL compatible JSON responses. ![stars](https://img.shields.io/badge/stars-14-blue)
- [jsonhandlers](https://github.com/abusomani/jsonhandlers) - JSON library to expose simple handlers that lets you easily read and write json from various sources. ![stars](https://img.shields.io/badge/stars-2-blue)
- [jsonic](https://github.com/sinhashubham95/jsonic) - Utilities to handle and query JSON without defining structs in a type safe manner. ![stars](https://img.shields.io/badge/stars-11-blue)
- [jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) - A fast and convenient library for unstructured JSON data, replacing `encoding/json`. ![stars](https://img.shields.io/badge/stars-191-blue)
- [jzon](https://github.com/zerosnake0/jzon) - JSON library with standard compatible API/behavior. ![stars](https://img.shields.io/badge/stars-11-blue)
- [kazaam](https://github.com/Qntfy/kazaam) - API for arbitrary transformation of JSON documents. ![stars](https://img.shields.io/badge/stars-283-blue)
- [mapslice-json](https://github.com/mickep76/mapslice-json) - Go MapSlice for ordered marshal/ unmarshal of maps in JSON. ![stars](https://img.shields.io/badge/stars-20-blue)
- [marshmallow](https://github.com/PerimeterX/marshmallow) - Performant JSON unmarshalling for flexible use cases. ![stars](https://img.shields.io/badge/stars-377-blue)
- [mp](https://github.com/sanbornm/mp) - Simple cli email parser. It currently takes stdin and outputs JSON. ![stars](https://img.shields.io/badge/stars-47-blue)
- [OjG](https://github.com/ohler55/ojg) - Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath. ![stars](https://img.shields.io/badge/stars-870-blue)
- [omg.jsonparser](https://github.com/dedalqq/omg.jsonparser) - Simple JSON parser with validation by condition via golang struct fields tags. ![stars](https://img.shields.io/badge/stars-6-blue)
- [ujson](https://github.com/olvrng/ujson) - Fast and minimal JSON parser and transformer that works on unstructured JSON. ![stars](https://img.shields.io/badge/stars-82-blue)
- [vjson](https://github.com/miladibra10/vjson) - Go package for validating JSON objects with declaring a JSON schema with fluent API. ![stars](https://img.shields.io/badge/stars-41-blue)

**[⬆ back to top](#contents)**

## Logging

_Libraries for generating and working with log files._

- [distillog](https://github.com/amoghe/distillog) - distilled levelled logging (think of it as stdlib + log levels). ![stars](https://img.shields.io/badge/stars-31-blue)
- [glg](https://github.com/kpango/glg) - glg is simple and fast leveled logging library for Go. ![stars](https://img.shields.io/badge/stars-189-blue)
- [glo](https://github.com/lajosbencz/glo) - PHP Monolog inspired logging facility with identical severity levels. ![stars](https://img.shields.io/badge/stars-16-blue)
- [glog](https://github.com/golang/glog) - Leveled execution logs for Go. ![stars](https://img.shields.io/badge/stars-3559-blue)
- [go-cronowriter](https://github.com/utahta/go-cronowriter) - Simple writer that rotate log files automatically based on current date and time, like cronolog. ![stars](https://img.shields.io/badge/stars-56-blue)
- [go-log](https://github.com/pieterclaerhout/go-log) - A logging library with stack traces, object dumping and optional timestamps. ![stars](https://img.shields.io/badge/stars-10-blue)
- [go-log](https://github.com/subchen/go-log) - Simple and configurable Logging in Go, with level, formatters and writers. ![stars](https://img.shields.io/badge/stars-14-blue)
- [go-log](https://github.com/siddontang/go-log) - Log lib supports level and multi handlers. ![stars](https://img.shields.io/badge/stars-35-blue)
- [go-log](https://github.com/ian-kent/go-log) - Log4j implementation in Go. ![stars](https://img.shields.io/badge/stars-43-blue)
- [go-logger](https://github.com/apsdehal/go-logger) - Simple logger of Go Programs, with level handlers. ![stars](https://img.shields.io/badge/stars-289-blue)
- [gomol](https://github.com/aphistic/gomol) - Multiple-output, structured logging for Go with extensible logging outputs. ![stars](https://img.shields.io/badge/stars-19-blue)
- [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library. ![stars](https://img.shields.io/badge/stars-50-blue)
- [httpretty](https://github.com/henvic/httpretty) - Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest). ![stars](https://img.shields.io/badge/stars-402-blue)
- [journald](https://github.com/ssgreg/journald) - Go implementation of systemd Journal's native API for logging. ![stars](https://img.shields.io/badge/stars-41-blue)
- [kemba](https://github.com/clok/kemba) - A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug), great for CLI tools and applications. ![stars](https://img.shields.io/badge/stars-14-blue)
- [log](https://github.com/aerogo/log) - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection). ![stars](https://img.shields.io/badge/stars-10-blue)
- [log](https://github.com/apex/log) - Structured logging package for Go. ![stars](https://img.shields.io/badge/stars-1367-blue)
- [log](https://github.com/go-playground/log) - Simple, configurable and scalable Structured Logging for Go. ![stars](https://img.shields.io/badge/stars-293-blue)
- [log](https://github.com/teris-io/log) - Structured log interface for Go cleanly separates logging facade from its implementation. ![stars](https://img.shields.io/badge/stars-26-blue)
- [log](https://github.com/heartwilltell/log) - Simple leveled logging wrapper around standard log package. ![stars](https://img.shields.io/badge/stars-16-blue)
- [log](https://github.com/no-src/log) - A simple logging framework out of the box. ![stars](https://img.shields.io/badge/stars-3-blue)
- [log-voyage](https://github.com/firstrow/logvoyage) - Full-featured logging saas written in golang. ![stars](https://img.shields.io/badge/stars-94-blue)
- [log15](https://github.com/inconshreveable/log15) - Simple, powerful logging for Go. ![stars](https://img.shields.io/badge/stars-1100-blue)
- [logdump](https://github.com/ewwwwwqm/logdump) - Package for multi-level logging. ![stars](https://img.shields.io/badge/stars-11-blue)
- [logex](https://github.com/chzyer/logex) - Golang log lib, supports tracking and level, wrap by standard log lib. ![stars](https://img.shields.io/badge/stars-43-blue)
- [logger](https://github.com/azer/logger) - Minimalistic logging library for Go. ![stars](https://img.shields.io/badge/stars-157-blue)
- [logo](https://github.com/mbndr/logo) - Golang logger to different configurable writers. ![stars](https://img.shields.io/badge/stars-12-blue)
- [logrus](https://github.com/Sirupsen/logrus) - Structured logger for Go. ![stars](https://img.shields.io/badge/stars-24894-blue)
- [logrusiowriter](https://github.com/cabify/logrusiowriter) - `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger. ![stars](https://img.shields.io/badge/stars-16-blue)
- [logrusly](https://github.com/sebest/logrusly) - [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/). ![stars](https://img.shields.io/badge/stars-28-blue)
- [logur](https://github.com/logur/logur) - An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus), [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap), [zerolog](https://github.com/rs/zerolog), etc). ![stars](https://img.shields.io/badge/stars-204-blue)
- [logutils](https://github.com/hashicorp/logutils) - Utilities for slightly better logging in Go (Golang) extending the standard logger. ![stars](https://img.shields.io/badge/stars-367-blue)
- [logxi](https://github.com/mgutz/logxi) - 12-factor app logger that is fast and makes you happy. ![stars](https://img.shields.io/badge/stars-358-blue)
- [lumberjack](https://github.com/natefinch/lumberjack) - Simple rolling logger, implements io.WriteCloser. ![stars](https://img.shields.io/badge/stars-4947-blue)
- [mlog](https://github.com/jbrodriguez/mlog) - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output. ![stars](https://img.shields.io/badge/stars-33-blue)
- [noodlog](https://github.com/gyozatech/noodlog) - Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings. ![stars](https://img.shields.io/badge/stars-44-blue)
- [onelog](https://github.com/francoispqt/onelog) - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation. ![stars](https://img.shields.io/badge/stars-415-blue)
- [ozzo-log](https://github.com/go-ozzo/ozzo-log) - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail). ![stars](https://img.shields.io/badge/stars-122-blue)
- [phuslu/log](https://github.com/phuslu/log) - High performance structured logging. ![stars](https://img.shields.io/badge/stars-706-blue)
- [pp](https://github.com/k0kubun/pp) - Colored pretty printer for Go language. ![stars](https://img.shields.io/badge/stars-1886-blue)
- [rollingwriter](https://github.com/arthurkiller/rollingWriter) - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation. ![stars](https://img.shields.io/badge/stars-299-blue)
- [seelog](https://github.com/cihub/seelog) - Logging functionality with flexible dispatching, filtering, and formatting. ![stars](https://img.shields.io/badge/stars-1639-blue)
- [slf4g](https://github.com/echocat/slf4g) - Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks. ![stars](https://img.shields.io/badge/stars-3-blue)
- [slog](https://github.com/gookit/slog) - Lightweight, configurable, extensible logger for Go. ![stars](https://img.shields.io/badge/stars-413-blue)
- [slog-formatter](https://github.com/samber/slog-formatter) - Common formatters for slog and helpers to build your own. ![stars](https://img.shields.io/badge/stars-144-blue)
- [slog-multi](https://github.com/samber/slog-multi) - Chain of slog.Handler (pipeline, fanout...). ![stars](https://img.shields.io/badge/stars-419-blue)
- [slogor](https://gitlab.com/greyxor/slogor) - A colorful slog handler.
- [spew](https://github.com/davecgh/go-spew) - Implements a deep pretty printer for Go data structures to aid in debugging. ![stars](https://img.shields.io/badge/stars-6136-blue)
- [sqldb-logger](https://github.com/simukti/sqldb-logger) - A logger for Go SQL database driver without modify existing \*sql.DB stdlib usage. ![stars](https://img.shields.io/badge/stars-365-blue)
- [stdlog](https://github.com/alexcesaro/log) - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs. ![stars](https://img.shields.io/badge/stars-48-blue)
- [structy/log](https://github.com/structy/log) - A simple to use log system, minimalist but with features for debugging and differentiation of messages. ![stars](https://img.shields.io/badge/stars-5-blue)
- [tail](https://github.com/hpcloud/tail) - Go package striving to emulate the features of the BSD tail program. ![stars](https://img.shields.io/badge/stars-2730-blue)
- [tint](https://github.com/lmittmann/tint) - A slog.Handler that writes tinted logs. ![stars](https://img.shields.io/badge/stars-872-blue)
- [xlog](https://github.com/xfxdev/xlog) - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format. ![stars](https://img.shields.io/badge/stars-8-blue)
- [xlog](https://github.com/rs/xlog) - Structured logger for `net/context` aware HTTP handlers with flexible dispatching. ![stars](https://img.shields.io/badge/stars-137-blue)
- [xylog](https://github.com/xybor-x/xylog) - Leveled and structured logging, dynamic fields, high performance, zone management, simple configuration, and readable syntax. ![stars](https://img.shields.io/badge/stars-17-blue)
- [yell](https://github.com/jfcg/yell) - Yet another minimalistic logging library. ![stars](https://img.shields.io/badge/stars-1-blue)
- [zap](https://github.com/uber-go/zap) - Fast, structured, leveled logging in Go. ![stars](https://img.shields.io/badge/stars-22392-blue)
- [zax](https://github.com/yuseferi/zax) - Integrate Context with Zap logger, which leads to more flexibility in Go logging. ![stars](https://img.shields.io/badge/stars-26-blue)
- [zerolog](https://github.com/rs/zerolog) - Zero-allocation JSON logger. ![stars](https://img.shields.io/badge/stars-10845-blue)
- [zkits-logger](https://github.com/edoger/zkits-logger) - A powerful zero-dependency JSON logger. ![stars](https://img.shields.io/badge/stars-26-blue)
- [zl](https://github.com/nkmr-jp/zl) - High Developer Experience, zap based logger. It offers rich functionality but is easy to configure. ![stars](https://img.shields.io/badge/stars-6-blue)

**[⬆ back to top](#contents)**

## Machine Learning

_Libraries for Machine Learning._

- [bayesian](https://github.com/jbrukh/bayesian) - Naive Bayesian Classification for Golang. ![stars](https://img.shields.io/badge/stars-805-blue)
- [CloudForest](https://github.com/ryanbressler/CloudForest) - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go. ![stars](https://img.shields.io/badge/stars-741-blue)
- [ddt](https://github.com/sgrodriguez/ddt) - Dynamic decision tree, create trees defining customizable rules. ![stars](https://img.shields.io/badge/stars-37-blue)
- [eaopt](https://github.com/MaxHalford/eaopt) - An evolutionary optimization library. ![stars](https://img.shields.io/badge/stars-894-blue)
- [evoli](https://github.com/khezen/evoli) - Genetic Algorithm and Particle Swarm Optimization library. ![stars](https://img.shields.io/badge/stars-33-blue)
- [fonet](https://github.com/Fontinalis/fonet) - A Deep Neural Network library written in Go. ![stars](https://img.shields.io/badge/stars-84-blue)
- [go-cluster](https://github.com/e-XpertSolutions/go-cluster) - Go implementation of the k-modes and k-prototypes clustering algorithms. ![stars](https://img.shields.io/badge/stars-43-blue)
- [go-deep](https://github.com/patrikeh/go-deep) - A feature-rich neural network library in Go. ![stars](https://img.shields.io/badge/stars-537-blue)
- [go-fann](https://github.com/white-pony/go-fann) - Go bindings for Fast Artificial Neural Networks(FANN) library. ![stars](https://img.shields.io/badge/stars-116-blue)
- [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) - Fast and convenient feature processing for low latency machine learning in Go. ![stars](https://img.shields.io/badge/stars-121-blue)
- [go-galib](https://github.com/thoj/go-galib) - Genetic Algorithms library written in Go / golang. ![stars](https://img.shields.io/badge/stars-200-blue)
- [go-pr](https://github.com/daviddengcn/go-pr) - Pattern recognition package in Go lang. ![stars](https://img.shields.io/badge/stars-67-blue)
- [gobrain](https://github.com/goml/gobrain) - Neural Networks written in go. ![stars](https://img.shields.io/badge/stars-565-blue)
- [godist](https://github.com/e-dard/godist) - Various probability distributions, and associated methods. ![stars](https://img.shields.io/badge/stars-41-blue)
- [goga](https://github.com/tomcraven/goga) - Genetic algorithm library for Go. ![stars](https://img.shields.io/badge/stars-222-blue)
- [GoLearn](https://github.com/sjwhitworth/golearn) - General Machine Learning library for Go. ![stars](https://img.shields.io/badge/stars-9319-blue)
- [golinear](https://github.com/danieldk/golinear) - liblinear bindings for Go. ![stars](https://img.shields.io/badge/stars-45-blue)
- [GoMind](https://github.com/surenderthakran/gomind) - A simplistic Neural Network Library in Go. ![stars](https://img.shields.io/badge/stars-86-blue)
- [goml](https://github.com/cdipaolo/goml) - On-line Machine Learning in Go. ![stars](https://img.shields.io/badge/stars-1571-blue)
- [GoMLX](https://github.com/gomlx/gomlx) - An accelerated Machine Learning framework for Go. ![stars](https://img.shields.io/badge/stars-619-blue)
- [gonet](https://github.com/dathoangnd/gonet) - Neural Network for Go. ![stars](https://img.shields.io/badge/stars-82-blue)
- [Goptuna](https://github.com/c-bata/goptuna) - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized. ![stars](https://img.shields.io/badge/stars-264-blue)
- [goRecommend](https://github.com/timkaye11/goRecommend) - Recommendation Algorithms library written in Go. ![stars](https://img.shields.io/badge/stars-206-blue)
- [gorgonia](https://github.com/gorgonia/gorgonia) - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms. ![stars](https://img.shields.io/badge/stars-5611-blue)
- [gorse](https://github.com/zhenghaoz/gorse) - An offline recommender system backend based on collaborative filtering written in Go. ![stars](https://img.shields.io/badge/stars-8707-blue)
- [goscore](https://github.com/asafschers/goscore) - Go Scoring API for PMML. ![stars](https://img.shields.io/badge/stars-100-blue)
- [gosseract](https://github.com/otiai10/gosseract) - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library. ![stars](https://img.shields.io/badge/stars-2771-blue)
- [hugot](https://github.com/knights-analytics/hugot) - Huggingface transformer pipelines for golang with onnxruntime. ![stars](https://img.shields.io/badge/stars-324-blue)
- [libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14. ![stars](https://img.shields.io/badge/stars-73-blue)
- [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support. ![stars](https://img.shields.io/badge/stars-2838-blue)
- [neural-go](https://github.com/schuyler/neural-go) - Multilayer perceptron network implemented in Go, with training via backpropagation. ![stars](https://img.shields.io/badge/stars-70-blue)
- [ocrserver](https://github.com/otiai10/ocrserver) - A simple OCR API server, seriously easy to be deployed by Docker and Heroku. ![stars](https://img.shields.io/badge/stars-714-blue)
- [onnx-go](https://github.com/owulveryck/onnx-go) - Go Interface to Open Neural Network Exchange (ONNX). ![stars](https://img.shields.io/badge/stars-734-blue)
- [probab](https://github.com/ThePaw/probab) - Probability distribution functions. Bayesian inference. Written in pure Go. ![stars](https://img.shields.io/badge/stars-20-blue)
- [randomforest](https://github.com/malaschitz/randomForest) - Easy to use Random Forest library for Go. ![stars](https://img.shields.io/badge/stars-47-blue)
- [regommend](https://github.com/muesli/regommend) - Recommendation & collaborative filtering engine. ![stars](https://img.shields.io/badge/stars-314-blue)
- [shield](https://github.com/eaigner/shield) - Bayesian text classifier with flexible tokenizers and storage backends for Go. ![stars](https://img.shields.io/badge/stars-158-blue)
- [tfgo](https://github.com/galeone/tfgo) - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python. ![stars](https://img.shields.io/badge/stars-2431-blue)
- [Varis](https://github.com/Xamber/Varis) - Golang Neural Network. ![stars](https://img.shields.io/badge/stars-55-blue)

**[⬆ back to top](#contents)**

## Messaging

_Libraries that implement messaging systems._

- [ami](https://github.com/kak-tus/ami) - Go client to reliable queues based on Redis Cluster Streams. ![stars](https://img.shields.io/badge/stars-29-blue)
- [amqp](https://github.com/rabbitmq/amqp091-go) - Go RabbitMQ Client Library. ![stars](https://img.shields.io/badge/stars-1627-blue)
- [APNs2](https://github.com/sideshow/apns2) - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps. ![stars](https://img.shields.io/badge/stars-3028-blue)
- [Asynq](https://github.com/hibiken/asynq) - A simple, reliable, and efficient distributed task queue for Go built on top of Redis. ![stars](https://img.shields.io/badge/stars-10456-blue)
- [Beaver](https://github.com/Clivern/Beaver) - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps. ![stars](https://img.shields.io/badge/stars-1555-blue)
- [Bus](https://github.com/mustafaturan/bus) - Minimalist message bus implementation for internal communication. ![stars](https://img.shields.io/badge/stars-339-blue)
- [Centrifugo](https://github.com/centrifugal/centrifugo) - Real-time messaging (Websockets or SockJS) server in Go. ![stars](https://img.shields.io/badge/stars-8600-blue)
- [Chanify](https://github.com/chanify/chanify) - A push notification server send message to your iOS devices. ![stars](https://img.shields.io/badge/stars-1286-blue)
- [Commander](https://github.com/jeroenrinzema/commander) - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka. ![stars](https://img.shields.io/badge/stars-67-blue)
- [Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) - confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform. ![stars](https://img.shields.io/badge/stars-4702-blue)
- [dbus](https://github.com/godbus/dbus) - Native Go bindings for D-Bus. ![stars](https://img.shields.io/badge/stars-1011-blue)
- [drone-line](https://github.com/appleboy/drone-line) - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI. ![stars](https://img.shields.io/badge/stars-80-blue)
- [emitter](https://github.com/olebedev/emitter) - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins. ![stars](https://img.shields.io/badge/stars-512-blue)
- [event](https://github.com/agoalofalife/event) - Implementation of the pattern observer. ![stars](https://img.shields.io/badge/stars-58-blue)
- [EventBus](https://github.com/asaskevich/EventBus) - The lightweight event bus with async compatibility. ![stars](https://img.shields.io/badge/stars-1782-blue)
- [gaurun-client](https://github.com/osamingo/gaurun-client) - Gaurun Client written in Go. ![stars](https://img.shields.io/badge/stars-11-blue)
- [Glue](https://github.com/desertbit/glue) - Robust Go and Javascript Socket Library (Alternative to Socket.io). ![stars](https://img.shields.io/badge/stars-417-blue)
- [go-eventbus](https://github.com/stanipetrosyan/go-eventbus) - Simple Event Bus package for Go. ![stars](https://img.shields.io/badge/stars-6-blue)
- [Go-MediatR](https://github.com/mehdihadeli/Go-MediatR) - A library for handling mediator patterns and simplified CQRS patterns within an event-driven architecture, inspired by csharp MediatR library. ![stars](https://img.shields.io/badge/stars-216-blue)
- [go-mq](https://github.com/cheshir/go-mq) - RabbitMQ client with declarative configuration. ![stars](https://img.shields.io/badge/stars-90-blue)
- [go-notify](https://github.com/TheCreeper/go-notify) - Native implementation of the freedesktop notification spec. ![stars](https://img.shields.io/badge/stars-70-blue)
- [go-nsq](https://github.com/nsqio/go-nsq) - the official Go package for NSQ. ![stars](https://img.shields.io/badge/stars-2601-blue)
- [go-res](https://github.com/jirenius/go-res) - Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate. ![stars](https://img.shields.io/badge/stars-64-blue)
- [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework. ![stars](https://img.shields.io/badge/stars-5758-blue)
- [go-vitotrol](https://github.com/maxatome/go-vitotrol) - Client library to Viessmann Vitotrol web service. ![stars](https://img.shields.io/badge/stars-23-blue)
- [Gollum](https://github.com/trivago/gollum) - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations. ![stars](https://img.shields.io/badge/stars-940-blue)
- [golongpoll](https://github.com/jcuga/golongpoll) - HTTP longpoll server library that makes web pub-sub simple. ![stars](https://img.shields.io/badge/stars-661-blue)
- [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) - gopush-cluster is a go push server cluster. ![stars](https://img.shields.io/badge/stars-2081-blue)
- [gorush](https://github.com/appleboy/gorush) - Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm). ![stars](https://img.shields.io/badge/stars-8144-blue)
- [gosd](https://github.com/alexsniffin/gosd) - A library for scheduling when to dispatch a message to a channel. ![stars](https://img.shields.io/badge/stars-25-blue)
- [guble](https://github.com/smancke/guble) - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence. ![stars](https://img.shields.io/badge/stars-158-blue)
- [hare](https://github.com/leozz37/hare) - A user friendly library for sending messages and listening to TCP sockets. ![stars](https://img.shields.io/badge/stars-53-blue)
- [hub](https://github.com/leandro-lugaresi/hub) - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges. ![stars](https://img.shields.io/badge/stars-146-blue)
- [hypermatch](https://github.com/SchwarzIT/hypermatch) - A very fast and efficient Go library for matching events to a large set of rules ![stars](https://img.shields.io/badge/stars-22-blue)
- [jazz](https://github.com/socifi/jazz) - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages. ![stars](https://img.shields.io/badge/stars-18-blue)
- [machinery](https://github.com/RichardKnop/machinery) - Asynchronous task queue/job queue based on distributed message passing. ![stars](https://img.shields.io/badge/stars-7607-blue)
- [mangos](https://github.com/nanomsg/mangos) - Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability. ![stars](https://img.shields.io/badge/stars-691-blue)
- [melody](https://github.com/olahol/melody) - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling. ![stars](https://img.shields.io/badge/stars-3822-blue)
- [Mercure](https://github.com/dunglas/mercure) - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events). ![stars](https://img.shields.io/badge/stars-4692-blue)
- [messagebus](https://github.com/vardius/message-bus) - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD. ![stars](https://img.shields.io/badge/stars-274-blue)
- [NATS Go Client](https://github.com/nats-io/nats.go) - Go client for the NATS ![stars](https://img.shields.io/badge/stars-5659-blue)
  messaging system.
- [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) - A tiny wrapper around NSQ topic and channel. ![stars](https://img.shields.io/badge/stars-79-blue)
- [oplog](https://github.com/dailymotion/oplog) - Generic oplog/replication system for REST APIs. ![stars](https://img.shields.io/badge/stars-111-blue)
- [pubsub](https://github.com/tuxychandru/pubsub) - Simple pubsub package for go. ![stars](https://img.shields.io/badge/stars-431-blue)
- [Quamina](https://github.com/timbray/quamina) - Fast pattern-matching for filtering messages and events. ![stars](https://img.shields.io/badge/stars-420-blue)
- [rabbitroutine](https://github.com/furdarius/rabbitroutine) - Lightweight library that handles RabbitMQ auto-reconnect and publishing retries. The library takes into account the need to re-declare entities in RabbitMQ after reconnection.  ![stars](https://img.shields.io/badge/stars-110-blue)
- [rabbus](https://github.com/rafaeljesus/rabbus) - A tiny wrapper over amqp exchanges and queues. ![stars](https://img.shields.io/badge/stars-97-blue)
- [rabtap](https://github.com/jandelgado/rabtap) - RabbitMQ swiss army knife cli app. ![stars](https://img.shields.io/badge/stars-265-blue)
- [RapidMQ](https://github.com/sybrexsys/RapidMQ) - RapidMQ is a lightweight and reliable library for managing of the local messages queue. ![stars](https://img.shields.io/badge/stars-68-blue)
- [Ratus](https://github.com/hyperonym/ratus) - Ratus is a RESTful asynchronous task queue server. ![stars](https://img.shields.io/badge/stars-110-blue)
- [redisqueue](https://github.com/robinjoseph08/redisqueue) - redisqueue provides a producer and consumer of a queue that uses Redis streams. ![stars](https://img.shields.io/badge/stars-131-blue)
- [rmqconn](https://github.com/sbabiv/rmqconn) - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed. ![stars](https://img.shields.io/badge/stars-23-blue)
- [sarama](https://github.com/Shopify/sarama) - Go library for Apache Kafka. ![stars](https://img.shields.io/badge/stars-11693-blue)
- [Uniqush-Push](https://github.com/uniqush/uniqush-push) - Redis backed unified push service for server-side notifications to mobile devices. ![stars](https://img.shields.io/badge/stars-1541-blue)
- [Watermill](https://github.com/ThreeDotsLabs/watermill) - Working efficiently with message streams. Building event driven applications, enabling event sourcing, RPC over messages, sagas. Can use conventional pub/sub implementations like Kafka or RabbitMQ, but also HTTP or MySQL binlog. ![stars](https://img.shields.io/badge/stars-8006-blue)
- [zmq4](https://github.com/pebbe/zmq4) - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2). ![stars](https://img.shields.io/badge/stars-1186-blue)

**[⬆ back to top](#contents)**

## Microsoft Office

- [unioffice](https://github.com/unidoc/unioffice) - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents. ![stars](https://img.shields.io/badge/stars-4437-blue)

### Microsoft Excel

_Libraries for working with Microsoft Excel._

- [excelize](https://github.com/xuri/excelize) - Golang library for reading and writing Microsoft Excel&trade; (XLSX) files. ![stars](https://img.shields.io/badge/stars-18580-blue)
- [exl](https://github.com/go-the-way/exl) - Excel binding to struct written in Go.(Only supports Go1.18+) ![stars](https://img.shields.io/badge/stars-30-blue)
- [go-excel](https://github.com/szyhf/go-excel) - A simple and light reader to read a relate-db-like excel as a table. ![stars](https://img.shields.io/badge/stars-193-blue)
- [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files. ![stars](https://img.shields.io/badge/stars-21-blue)
- [xlsx](https://github.com/tealeg/xlsx) - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs. ![stars](https://img.shields.io/badge/stars-5902-blue)
- [xlsx](https://github.com/plandem/xlsx) - Fast and safe way to read/update your existing Microsoft Excel files in Go programs. ![stars](https://img.shields.io/badge/stars-174-blue)

### Microsoft Word

_Libraries for working with Microsoft Word._

- [godocx](https://github.com/gomutex/godocx) - Library for reading and writing Microsoft Word (Docx) files.  ![stars](https://img.shields.io/badge/stars-126-blue)

**[⬆ back to top](#contents)**

## Miscellaneous

### Dependency Injection

_Libraries for working with dependency injection._

- [alice](https://github.com/magic003/alice) - Additive dependency injection container for Golang. ![stars](https://img.shields.io/badge/stars-50-blue)
- [autowire](https://github.com/tiendc/autowire) - Dependency injection using Generics and reflection. ![stars](https://img.shields.io/badge/stars-10-blue)
- [boot-go](http://github.com/boot-go/boot) - Component-based development with dependency injection using reflections for Go developers.
- [componego](https://github.com/componego/componego) - A dependency injection framework based on components, allowing dynamic dependency replacement without duplicating code in tests. ![stars](https://img.shields.io/badge/stars-26-blue)
- [cosban/di](https://gitlab.com/cosban/di) - A code generation based dependency injection wiring tool.
- [di](https://github.com/goava/di) - A dependency injection container for go programming language. ![stars](https://img.shields.io/badge/stars-234-blue)
- [dig](https://github.com/uber-go/dig) - A reflection based dependency injection toolkit for Go. ![stars](https://img.shields.io/badge/stars-3989-blue)
- [dingo](https://github.com/i-love-flamingo/dingo) - A dependency injection toolkit for Go, based on Guice. ![stars](https://img.shields.io/badge/stars-181-blue)
- [do](https://github.com/samber/do) - A dependency injection framework based on Generics. ![stars](https://img.shields.io/badge/stars-1927-blue)
- [fx](https://github.com/uber-go/fx) - A dependency injection based application framework for Go (built on top of dig). ![stars](https://img.shields.io/badge/stars-6064-blue)
- [gocontainer](https://github.com/vardius/gocontainer) - Simple Dependency Injection Container. ![stars](https://img.shields.io/badge/stars-20-blue)
- [goioc/di](https://github.com/goioc/di) - Spring-inspired Dependency Injection Container. ![stars](https://img.shields.io/badge/stars-363-blue)
- [GoLobby/Container](https://github.com/golobby/container) - GoLobby Container is a lightweight yet powerful IoC dependency injection container for the Go programming language. ![stars](https://img.shields.io/badge/stars-568-blue)
- [gontainer](https://github.com/NVIDIA/gontainer) - A dependency injection service container for Go projects. ![stars](https://img.shields.io/badge/stars-40-blue)
- [gontainer/gontainer](https://github.com/gontainer/gontainer) - A YAML-based Dependency Injection container for GO. It supports dependencies' scopes, and auto-detection of circular dependencies. Gontainer is concurrent-safe. ![stars](https://img.shields.io/badge/stars-15-blue)
- [google/wire](https://github.com/google/wire) - Automated Initialization in Go. ![stars](https://img.shields.io/badge/stars-13276-blue)
- [HnH/di](https://github.com/HnH/di) - DI container library that is focused on clean API and flexibility. ![stars](https://img.shields.io/badge/stars-8-blue)
- [kinit](https://github.com/go-kata/kinit) - Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization. ![stars](https://img.shields.io/badge/stars-10-blue)
- [kod](https://github.com/go-kod/kod) - A generics based dependency injection framework for Go. ![stars](https://img.shields.io/badge/stars-177-blue)
- [linker](https://github.com/logrange/linker) - A reflection based dependency injection and inversion of control library with components lifecycle support. ![stars](https://img.shields.io/badge/stars-36-blue)
- [nject](https://github.com/muir/nject) - A type safe, reflective framework for libraries, tests, http endpoints, and service startup. ![stars](https://img.shields.io/badge/stars-30-blue)
- [ore](https://github.com/firasdarwish/ore) - Lightweight, generic & simple dependency injection (DI) container. ![stars](https://img.shields.io/badge/stars-13-blue)
- [wire](https://github.com/Fs02/wire) - Strict Runtime Dependency Injection for Golang. ![stars](https://img.shields.io/badge/stars-37-blue)

**[⬆ back to top](#contents)**

### Project Layout

_**Unofficial** set of patterns for structuring projects._

- [ardanlabs/service](https://github.com/ardanlabs/service) - A [starter kit](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications. ![stars](https://img.shields.io/badge/stars-3625-blue)
- [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) - A Go application boilerplate template for quick starting projects following production best practices. ![stars](https://img.shields.io/badge/stars-696-blue)
- [go-blueprint](https://github.com/Melkeydev/go-blueprint) - Allows users to spin up a quick Go project using a popular framework. ![stars](https://img.shields.io/badge/stars-6549-blue)
- [go-module](https://github.com/octomation/go-module) - Template for a typical module written on Go. ![stars](https://img.shields.io/badge/stars-31-blue)
- [go-sample](https://github.com/zitryss/go-sample) - A sample layout for Go application projects with the real code. ![stars](https://img.shields.io/badge/stars-131-blue)
- [go-starter](https://github.com/allaboutapps/go-starter) - An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers. ![stars](https://img.shields.io/badge/stars-513-blue)
- [go-todo-backend](https://github.com/Fs02/go-todo-backend) - Go Todo Backend example using modular project layout for product microservice. ![stars](https://img.shields.io/badge/stars-321-blue)
- [gobase](https://github.com/wajox/gobase) - A simple skeleton for golang application with basic setup for real golang application. ![stars](https://img.shields.io/badge/stars-61-blue)
- [golang-standards/project-layout](https://github.com/golang-standards/project-layout) - Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see [this issue](https://github.com/golang-standards/project-layout/issues/117) for more information. Nonetheless, some may find the layout useful. ![stars](https://img.shields.io/badge/stars-50384-blue)
- [golang-templates/seed](https://github.com/golang-templates/seed) - Go application GitHub repository template. ![stars](https://img.shields.io/badge/stars-487-blue)
- [goxygen](https://github.com/shpota/goxygen) - Generate a modern Web project with Go and Angular, React, or Vue in seconds. ![stars](https://img.shields.io/badge/stars-3551-blue)
- [insidieux/inizio](https://github.com/insidieux/inizio) - Golang project layout generator with plugins. ![stars](https://img.shields.io/badge/stars-18-blue)
- [kickstart.go](https://github.com/raeperd/kickstart.go) - Minimalistic single-file Go HTTP server template without third-party dependencies. ![stars](https://img.shields.io/badge/stars-79-blue)
- [modern-go-application](https://github.com/sagikazarmark/modern-go-application) - Go application boilerplate and example applying modern practices. ![stars](https://img.shields.io/badge/stars-1868-blue)
- [nunu](https://github.com/go-nunu/nunu) - Nunu is a scaffolding tool for building Go applications. ![stars](https://img.shields.io/badge/stars-2037-blue)
- [pagoda](https://github.com/mikestefanello/pagoda) - Rapid, easy full-stack web development starter kit built in Go. ![stars](https://img.shields.io/badge/stars-2267-blue)
- [scaffold](https://github.com/catchplay/scaffold) - Scaffold generates a starter Go project layout. Lets you focus on business logic implemented. ![stars](https://img.shields.io/badge/stars-149-blue)
- [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) - Set of practices and discussions on how to structure Go project layout. ![stars](https://img.shields.io/badge/stars-26-blue)

**[⬆ back to top](#contents)**

### Strings

_Libraries for working with strings._

- [bexp](https://github.com/happy-sdk/happy/tree/main/pkg/strings/bexp) - Go implementation of Brace Expansion mechanism to generate arbitrary strings. ![stars](https://img.shields.io/badge/stars-21-blue)
- [caps](https://github.com/chanced/caps) - A case conversion library. ![stars](https://img.shields.io/badge/stars-58-blue)
- [go-formatter](https://gitlab.com/tymonx/go-formatter) - Implements **replacement fields** surrounded by curly braces `{}` format strings.
- [gobeam/Stringy](https://github.com/gobeam/Stringy) - String manipulation library to convert string to camel case, snake case, kebab case / slugify etc. ![stars](https://img.shields.io/badge/stars-239-blue)
- [strcase](https://github.com/charlievieth/strcase) - Case-insensitive implementation of the standard library's strings/bytes packages. ![stars](https://img.shields.io/badge/stars-6-blue)
- [strutil](https://github.com/ozgio/strutil) - String utilities. ![stars](https://img.shields.io/badge/stars-207-blue)
- [sttr](https://github.com/abhimanyu003/sttr) - cross-platform, cli app to perform various operations on string. ![stars](https://img.shields.io/badge/stars-971-blue)
- [xstrings](https://github.com/huandu/xstrings) - Collection of useful string functions ported from other languages. ![stars](https://img.shields.io/badge/stars-1403-blue)

**[⬆ back to top](#contents)**

### Uncategorized

_These libraries were placed here because none of the other categories seemed to fit._

- [anagent](https://github.com/mudler/anagent) - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection. ![stars](https://img.shields.io/badge/stars-15-blue)
- [antch](https://github.com/antchfx/antch) - A fast, powerful and extensible web crawling & scraping framework. ![stars](https://img.shields.io/badge/stars-262-blue)
- [archiver](https://github.com/mholt/archiver) - Library and command for making and extracting .zip and .tar.gz archives. ![stars](https://img.shields.io/badge/stars-4434-blue)
- [autoflags](https://github.com/artyom/autoflags) - Go package to automatically define command line flags from struct fields. ![stars](https://img.shields.io/badge/stars-43-blue)
- [avgRating](https://github.com/kirillDanshin/avgRating) - Calculate average score and rating based on Wilson Score Equation. ![stars](https://img.shields.io/badge/stars-17-blue)
- [banner](https://github.com/dimiro1/banner) - Add beautiful banners into your Go applications. ![stars](https://img.shields.io/badge/stars-455-blue)
- [base64Captcha](https://github.com/mojocn/base64Captcha) - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha. ![stars](https://img.shields.io/badge/stars-2163-blue)
- [basexx](https://github.com/bobg/basexx) - Convert to, from, and between digit strings in various number bases. ![stars](https://img.shields.io/badge/stars-5-blue)
- [battery](https://github.com/distatus/battery) - Cross-platform, normalized battery information library. ![stars](https://img.shields.io/badge/stars-253-blue)
- [bitio](https://github.com/icza/bitio) - Highly optimized bit-level Reader and Writer for Go. ![stars](https://img.shields.io/badge/stars-245-blue)
- [browscap_go](https://github.com/digitalcrab/browscap_go) - GoLang Library for [Browser Capabilities Project](https://browscap.org/). ![stars](https://img.shields.io/badge/stars-49-blue)
- [captcha](https://github.com/steambap/captcha) - Package captcha provides an easy to use, unopinionated API for captcha generation. ![stars](https://img.shields.io/badge/stars-157-blue)
- [common](https://github.com/kubeservice-stack/common) - A library for server framework. ![stars](https://img.shields.io/badge/stars-4-blue)
- [conv](https://github.com/cstockton/go-conv) - Package conv provides fast and intuitive conversions across Go types. ![stars](https://img.shields.io/badge/stars-383-blue)
- [datacounter](https://github.com/miolini/datacounter) - Go counters for readers/writer/http.ResponseWriter. ![stars](https://img.shields.io/badge/stars-49-blue)
- [faker](https://github.com/pioz/faker) - Random fake data and struct generator for Go. ![stars](https://img.shields.io/badge/stars-97-blue)
- [ffmt](https://github.com/go-ffmt/ffmt) - Beautify data display for Humans. ![stars](https://img.shields.io/badge/stars-310-blue)
- [gatus](https://github.com/TwinProduction/gatus) - Automated service health dashboard. ![stars](https://img.shields.io/badge/stars-6871-blue)
- [go-commandbus](https://github.com/lana/go-commandbus) - A slight and pluggable command-bus for Go. ![stars](https://img.shields.io/badge/stars-13-blue)
- [go-commons-pool](https://github.com/jolestar/go-commons-pool) - Generic object pool for Golang. ![stars](https://img.shields.io/badge/stars-1234-blue)
- [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
- [go-resiliency](https://github.com/eapache/go-resiliency) - Resiliency patterns for golang. ![stars](https://img.shields.io/badge/stars-2245-blue)
- [go-unarr](https://github.com/gen2brain/go-unarr) - Decompression library for RAR, TAR, ZIP and 7z archives. ![stars](https://img.shields.io/badge/stars-286-blue)
- [gofakeit](https://github.com/brianvoe/gofakeit) - Random data generator written in go. ![stars](https://img.shields.io/badge/stars-4728-blue)
- [gommit](https://github.com/antham/gommit) - Analyze git commit messages to ensure they follow defined patterns. ![stars](https://img.shields.io/badge/stars-113-blue)
- [gopsutil](https://github.com/shirou/gopsutil) - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc). ![stars](https://img.shields.io/badge/stars-10787-blue)
- [gosh](https://github.com/osamingo/gosh) - Provide Go Statistics Handler, Struct, Measure Method. ![stars](https://img.shields.io/badge/stars-36-blue)
- [gosms](https://github.com/haxpax/gosms) - Your own local SMS gateway in Go that can be used to send SMS. ![stars](https://img.shields.io/badge/stars-1455-blue)
- [gotoprom](https://github.com/cabify/gotoprom) - Type-safe metrics builder wrapper library for the official Prometheus client. ![stars](https://img.shields.io/badge/stars-108-blue)
- [gountries](https://github.com/pariz/gountries) - Package that exposes country and subdivision data. ![stars](https://img.shields.io/badge/stars-408-blue)
- [gtree](https://github.com/ddddddO/gtree) - Provide CLI, Package and Web for tree output and directories creation from Markdown or programmatically. ![stars](https://img.shields.io/badge/stars-255-blue)
- [health](https://github.com/alexliesenfeld/health) - A simple and flexible health check library for Go. ![stars](https://img.shields.io/badge/stars-786-blue)
- [health](https://github.com/dimiro1/health) - Easy to use, extensible health check library. ![stars](https://img.shields.io/badge/stars-451-blue)
- [healthcheck](https://github.com/etherlabsio/healthcheck) - An opinionated and concurrent health-check HTTP handler for RESTful services. ![stars](https://img.shields.io/badge/stars-270-blue)
- [hostutils](https://github.com/Wing924/hostutils) - A golang library for packing and unpacking FQDNs list. ![stars](https://img.shields.io/badge/stars-13-blue)
- [indigo](https://github.com/osamingo/indigo) - Distributed unique ID generator of using Sonyflake and encoded by Base58. ![stars](https://img.shields.io/badge/stars-109-blue)
- [lk](https://github.com/hyperboloide/lk) - A simple licensing library for golang. ![stars](https://img.shields.io/badge/stars-375-blue)
- [llvm](https://github.com/llir/llvm) - Library for interacting with LLVM IR in pure Go. ![stars](https://img.shields.io/badge/stars-1212-blue)
- [metrics](https://github.com/pascaldekloe/metrics) - Library for metrics instrumentation and Prometheus exposition. ![stars](https://img.shields.io/badge/stars-28-blue)
- [morse](https://github.com/alwindoss/morse) - Library to convert to and from morse code. ![stars](https://img.shields.io/badge/stars-83-blue)
- [numa](https://github.com/lrita/numa) - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code. ![stars](https://img.shields.io/badge/stars-31-blue)
- [openapi](https://github.com/neotoolkit/openapi) - OpenAPI 3.x parser. ![stars](https://img.shields.io/badge/stars-11-blue)
- [pdfgen](https://github.com/hyperboloide/pdfgen) - HTTP service to generate PDF from Json requests. ![stars](https://img.shields.io/badge/stars-71-blue)
- [persian](https://github.com/mavihq/persian) - Some utilities for Persian language in go. ![stars](https://img.shields.io/badge/stars-87-blue)
- [sandid](https://github.com/aofei/sandid) - Every grain of sand on earth has its own ID. ![stars](https://img.shields.io/badge/stars-46-blue)
- [shellwords](https://github.com/Wing924/shellwords) - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell. ![stars](https://img.shields.io/badge/stars-25-blue)
- [shortid](https://github.com/teris-io/shortid) - Distributed generation of super short, unique, non-sequential, URL friendly IDs. ![stars](https://img.shields.io/badge/stars-943-blue)
- [shoutrrr](https://github.com/containrrr/shoutrrr) - Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others. ![stars](https://img.shields.io/badge/stars-1083-blue)
- [sitemap-format](https://github.com/mingard/sitemap-format) - A simple sitemap generator, with a little syntactic sugar. ![stars](https://img.shields.io/badge/stars-5-blue)
- [stateless](https://github.com/qmuntal/stateless) - A fluent library for creating state machines. ![stars](https://img.shields.io/badge/stars-994-blue)
- [stats](https://github.com/go-playground/stats) - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc... ![stars](https://img.shields.io/badge/stars-170-blue)
- [turtle](https://github.com/hackebrot/turtle) - Emojis for Go. ![stars](https://img.shields.io/badge/stars-161-blue)
- [url-shortener](https://github.com/pantrif/url-shortener) - A modern, powerful, and robust URL shortener microservice with mysql support. ![stars](https://img.shields.io/badge/stars-48-blue)
- [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling. ![stars](https://img.shields.io/badge/stars-6-blue)
- [varint](https://github.com/chmike/varint) - A faster varying length integer encoder/decoder than the one provided in the standard library. ![stars](https://img.shields.io/badge/stars-15-blue)
- [xdg](https://github.com/rkoesters/xdg) - FreeDesktop.org (xdg) Specs implemented in Go. ![stars](https://img.shields.io/badge/stars-45-blue)
- [xkg](https://github.com/go-xkg/xkg) - X Keyboard Grabber. ![stars](https://img.shields.io/badge/stars-59-blue)
- [xz](https://github.com/ulikunitz/xz) - Pure golang package for reading and writing xz-compressed files. ![stars](https://img.shields.io/badge/stars-489-blue)

**[⬆ back to top](#contents)**

## Natural Language Processing

_Libraries for working with human languages._

See also [Text Processing](#text-processing) and [Text Analysis](#text-analysis).

### Language Detection

- [detectlanguage](https://github.com/detectlanguage/detectlanguage-go) - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection. ![stars](https://img.shields.io/badge/stars-25-blue)
- [getlang](https://github.com/rylans/getlang) - Fast natural language detection package. ![stars](https://img.shields.io/badge/stars-172-blue)
- [guesslanguage](https://github.com/endeveit/guesslanguage) - Functions to determine the natural language of a unicode text. ![stars](https://img.shields.io/badge/stars-58-blue)
- [lingua-go](https://github.com/pemistahl/lingua-go) - An accurate natural language detection library, suitable for long and short text alike. Supports detecting multiple languages in mixed-language text. ![stars](https://img.shields.io/badge/stars-1196-blue)
- [whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc). ![stars](https://img.shields.io/badge/stars-644-blue)

### Morphological Analyzers

- [go-stem](https://github.com/agonopol/go-stem) - Implementation of the porter stemming algorithm. ![stars](https://img.shields.io/badge/stars-81-blue)
- [go2vec](https://github.com/danieldk/go2vec) - Reader and utility functions for word2vec embeddings. ![stars](https://img.shields.io/badge/stars-56-blue)
- [golibstemmer](https://github.com/rjohnsondev/golibstemmer) - Go bindings for the snowball libstemmer library including porter 2. ![stars](https://img.shields.io/badge/stars-20-blue)
- [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) - Sentiment analyzer using sentiwordnet lexicon in Go. ![stars](https://img.shields.io/badge/stars-10-blue)
- [govader](https://github.com/jonreiter/govader) - Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment). ![stars](https://img.shields.io/badge/stars-44-blue)
- [govader-backend](https://github.com/PIMPfiction/govader_backend) - Microservice implementation of [GoVader](https://github.com/jonreiter/govader). ![stars](https://img.shields.io/badge/stars-6-blue)
- [kagome](https://github.com/ikawaha/kagome) - JP morphological analyzer written in pure Go. ![stars](https://img.shields.io/badge/stars-840-blue)
- [libtextcat](https://github.com/goodsign/libtextcat) - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2. ![stars](https://img.shields.io/badge/stars-13-blue)
- [nlp](https://github.com/Shixzie/nlp) - Extract values from strings and fill your structs with nlp. ![stars](https://img.shields.io/badge/stars-388-blue)
- [nlp](https://github.com/james-bowman/nlp) - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis). ![stars](https://img.shields.io/badge/stars-451-blue)
- [paicehusk](https://github.com/rookii/paicehusk) - Golang implementation of the Paice/Husk Stemming Algorithm. ![stars](https://img.shields.io/badge/stars-29-blue)
- [porter](https://github.com/a2800276/porter) - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm. ![stars](https://img.shields.io/badge/stars-12-blue)
- [porter2](https://github.com/zhenjl/porter2) - Really fast Porter 2 stemmer. ![stars](https://img.shields.io/badge/stars-47-blue)
- [RAKE.go](https://github.com/afjoseph/RAKE.Go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE). ![stars](https://img.shields.io/badge/stars-118-blue)
- [snowball](https://github.com/goodsign/snowball) - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/). ![stars](https://img.shields.io/badge/stars-38-blue)
- [spaGO](https://github.com/nlpodyssey/spago) - Self-contained Machine Learning and Natural Language Processing library in Go. ![stars](https://img.shields.io/badge/stars-1765-blue)
- [spelling-corrector](https://github.com/jorelosorio/spellingcorrector) - A spelling corrector for the Spanish language or create your own. ![stars](https://img.shields.io/badge/stars-2-blue)

### Slugifiers

- [go-slugify](https://github.com/mozillazg/go-slugify) - Make pretty slug with multiple languages support. ![stars](https://img.shields.io/badge/stars-94-blue)
- [slug](https://github.com/gosimple/slug) - URL-friendly slugify with multiple languages support. ![stars](https://img.shields.io/badge/stars-1201-blue)
- [Slugify](https://github.com/avelino/slugify) - Go slugify application that handles string. ![stars](https://img.shields.io/badge/stars-33-blue)

### Tokenizers

- [gojieba](https://github.com/yanyiwu/gojieba) - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) which a Chinese word splitting algorithm. ![stars](https://img.shields.io/badge/stars-2467-blue)
- [gotokenizer](https://github.com/xujiajun/gotokenizer) - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation) ![stars](https://img.shields.io/badge/stars-21-blue)
- [gse](https://github.com/go-ego/gse) - Go efficient text segmentation; support english, chinese, japanese and other. ![stars](https://img.shields.io/badge/stars-2610-blue)
- [MMSEGO](https://github.com/awsong/MMSEGO) - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm. ![stars](https://img.shields.io/badge/stars-62-blue)
- [prose](https://github.com/jdkato/prose) - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only. ![stars](https://img.shields.io/badge/stars-3061-blue)
- [segment](https://github.com/blevesearch/segment) - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/) ![stars](https://img.shields.io/badge/stars-89-blue)
- [sentences](https://github.com/neurosnap/sentences) - Sentence tokenizer: converts text into a list of sentences. ![stars](https://img.shields.io/badge/stars-442-blue)
- [shamoji](https://github.com/osamingo/shamoji) - The shamoji is word filtering package written in Go. ![stars](https://img.shields.io/badge/stars-13-blue)
- [stemmer](https://github.com/dchest/stemmer) - Stemmer packages for Go programming language. Includes English and German stemmers. ![stars](https://img.shields.io/badge/stars-53-blue)
- [textcat](https://github.com/pebbe/textcat) - Go package for n-gram based text categorization, with support for utf-8 and raw text. ![stars](https://img.shields.io/badge/stars-73-blue)

### Translation

- [ctxi18n](https://github.com/invopop/ctxi18n/) - Context aware i18n with a short and consise API, pluralization, interpolation, and `fs.FS` support. YAML locale definitions are based on [Rails i18n](https://guides.rubyonrails.org/i18n.html). ![stars](https://img.shields.io/badge/stars-53-blue)
- [go-i18n](https://github.com/nicksnyder/go-i18n/) - Package and an accompanying tool to work with localized text. ![stars](https://img.shields.io/badge/stars-3069-blue)
- [go-mystem](https://github.com/dveselov/mystem) - CGo bindings to Yandex.Mystem - russian morphology analyzer. ![stars](https://img.shields.io/badge/stars-34-blue)
- [go-pinyin](https://github.com/mozillazg/go-pinyin) - CN Hanzi to Hanyu Pinyin converter. ![stars](https://img.shields.io/badge/stars-1649-blue)
- [go-words](https://github.com/saleh-rahimzadeh/go-words) - A words table and text resource library for Golang projects. ![stars](https://img.shields.io/badge/stars-6-blue)
- [gotext](https://github.com/leonelquinteros/gotext) - GNU gettext utilities for Go. ![stars](https://img.shields.io/badge/stars-442-blue)
- [iuliia-go](https://github.com/mehanizm/iuliia-go) - Transliterate Cyrillic → Latin in every possible way. ![stars](https://img.shields.io/badge/stars-49-blue)
- [spreak](https://github.com/vorlif/spreak) - Flexible translation and humanization library for Go, based on the concepts behind gettext. ![stars](https://img.shields.io/badge/stars-58-blue)
- [t](https://github.com/youthlin/t) - Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template. ![stars](https://img.shields.io/badge/stars-20-blue)

### Transliteration

- [enca](https://github.com/endeveit/enca) - Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings. ![stars](https://img.shields.io/badge/stars-16-blue)
- [go-unidecode](https://github.com/mozillazg/go-unidecode) - ASCII transliterations of Unicode text. ![stars](https://img.shields.io/badge/stars-133-blue)
- [gounidecode](https://github.com/fiam/gounidecode) - Unicode transliterator (also known as unidecode) for Go. ![stars](https://img.shields.io/badge/stars-80-blue)
- [transliterator](https://github.com/alexsergivan/transliterator) - Provides one-way string transliteration with supporting of language-specific transliteration rules. ![stars](https://img.shields.io/badge/stars-44-blue)

**[⬆ back to top](#contents)**

## Networking

_Libraries for working with various layers of the network._

- [arp](https://github.com/mdlayher/arp) - Package arp implements the ARP protocol, as described in RFC 826. ![stars](https://img.shields.io/badge/stars-367-blue)
- [bart](https://github.com/gaissmai/bart) - Package bart provides a fast routing table algorithm. ![stars](https://img.shields.io/badge/stars-39-blue)
- [buffstreams](https://github.com/stabbycutyou/buffstreams) - Streaming protocolbuffer data over TCP made easy. ![stars](https://img.shields.io/badge/stars-254-blue)
- [canopus](https://github.com/zubairhamed/canopus) - CoAP Client/Server implementation (RFC 7252). ![stars](https://img.shields.io/badge/stars-156-blue)
- [cidranger](https://github.com/yl2chen/cidranger) - Fast IP to CIDR lookup for Go. ![stars](https://img.shields.io/badge/stars-912-blue)
- [cloudflared](https://github.com/cloudflare/cloudflared) - Cloudflare Tunnel client (formerly Argo Tunnel).  ![stars](https://img.shields.io/badge/stars-9650-blue)
- [dhcp6](https://github.com/mdlayher/dhcp6) - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315. ![stars](https://img.shields.io/badge/stars-77-blue)
- [dns](https://github.com/miekg/dns) - Go library for working with DNS. ![stars](https://img.shields.io/badge/stars-8146-blue)
- [dnsmonster](https://github.com/mosajjal/dnsmonster) - Passive DNS Capture/Monitoring Framework. ![stars](https://img.shields.io/badge/stars-316-blue)
- [easytcp](https://github.com/DarthPestilane/easytcp) - A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful. ![stars](https://img.shields.io/badge/stars-820-blue)
- [ether](https://github.com/songgao/ether) - Cross-platform Go package for sending and receiving ethernet frames. ![stars](https://img.shields.io/badge/stars-80-blue)
- [ethernet](https://github.com/mdlayher/ethernet) - Package ethernet implements marshaling and unmarshalling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags. ![stars](https://img.shields.io/badge/stars-280-blue)
- [event](https://github.com/cheng-zhongliang/event) - Simple I/O event notification library written in Golang. ![stars](https://img.shields.io/badge/stars-153-blue)
- [fasthttp](https://github.com/valyala/fasthttp) - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http. ![stars](https://img.shields.io/badge/stars-22094-blue)
- [fortio](https://github.com/fortio/fortio) - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC. ![stars](https://img.shields.io/badge/stars-3402-blue)
- [ftp](https://github.com/jlaffaye/ftp) - Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959). ![stars](https://img.shields.io/badge/stars-1324-blue)
- [ftpserverlib](https://github.com/fclairamb/ftpserverlib) - Fully featured FTP server library. ![stars](https://img.shields.io/badge/stars-439-blue)
- [fullproxy](https://github.com/shoriwe/fullproxy) - A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols. ![stars](https://img.shields.io/badge/stars-81-blue)
- [fwdctl](https://github.com/alegrey91/fwdctl) - A simple and intuitive CLI to manage IPTables forwards in your Linux server. ![stars](https://img.shields.io/badge/stars-60-blue)
- [gaio](https://github.com/xtaci/gaio) - High performance async-io networking for Golang in proactor mode. ![stars](https://img.shields.io/badge/stars-834-blue)
- [gev](https://github.com/Allenxuxu/gev) - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode. ![stars](https://img.shields.io/badge/stars-1740-blue)
- [gldap](https://github.com/jimlambrt/gldap) - gldap provides an ldap server implementation and you provide handlers for its ldap operations. ![stars](https://img.shields.io/badge/stars-112-blue)
- [gmqtt](https://github.com/DrmagicE/gmqtt) - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1. ![stars](https://img.shields.io/badge/stars-987-blue)
- [gnet](https://github.com/panjf2000/gnet) - `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go. ![stars](https://img.shields.io/badge/stars-9912-blue)
- [gnet](https://github.com/fish-tennis/gnet) - `gnet` is a high-performance networking framework,especially for game servers. ![stars](https://img.shields.io/badge/stars-20-blue)
- [gNxI](https://github.com/google/gnxi) - A collection of tools for Network Management that use the gNMI and gNOI protocols. ![stars](https://img.shields.io/badge/stars-263-blue)
- [go-getter](https://github.com/hashicorp/go-getter) - Go library for downloading files or directories from various sources using a URL. ![stars](https://img.shields.io/badge/stars-1673-blue)
- [go-multiproxy](https://github.com/presbrey/go-multiproxy) - Library for making HTTP requests through a pool of proxies offering fault tolerance, load balancing, automatic retries, cookie management, and more, via http.Get/Post replacement or http.Client RoundTripper drop-in ![stars](https://img.shields.io/badge/stars-8-blue)
- [go-powerdns](https://github.com/joeig/go-powerdns) - PowerDNS API bindings for Golang. ![stars](https://img.shields.io/badge/stars-91-blue)
- [go-sse](https://github.com/lampctl/go-sse) - Go client and server implementation of HTML server-sent events. ![stars](https://img.shields.io/badge/stars-12-blue)
- [go-stun](https://github.com/ccding/go-stun) - Go implementation of the STUN client (RFC 3489 and RFC 5389). ![stars](https://img.shields.io/badge/stars-687-blue)
- [gobgp](https://github.com/osrg/gobgp) - BGP implemented in the Go Programming Language. ![stars](https://img.shields.io/badge/stars-3689-blue)
- [gopacket](https://github.com/google/gopacket) - Go library for packet processing with libpcap bindings. ![stars](https://img.shields.io/badge/stars-6404-blue)
- [gopcap](https://github.com/akrennmair/gopcap) - Go wrapper for libpcap. ![stars](https://img.shields.io/badge/stars-490-blue)
- [goshark](https://github.com/sunwxg/goshark) - Package goshark use tshark to decode IP packet and create data struct to analyse packet. ![stars](https://img.shields.io/badge/stars-19-blue)
- [gosnmp](https://github.com/soniah/gosnmp) - Native Go library for performing SNMP actions. ![stars](https://img.shields.io/badge/stars-1157-blue)
- [gotcp](https://github.com/gansidui/gotcp) - Go package for quickly writing tcp applications. ![stars](https://img.shields.io/badge/stars-512-blue)
- [grab](https://github.com/cavaliercoder/grab) - Go package for managing file downloads. ![stars](https://img.shields.io/badge/stars-1411-blue)
- [graval](https://github.com/koofr/graval) - Experimental FTP server framework. ![stars](https://img.shields.io/badge/stars-28-blue)
- [gws](https://github.com/lxzan/gws) - High-Performance WebSocket Server & Client With AsyncIO Supporting . ![stars](https://img.shields.io/badge/stars-1474-blue)
- [HTTPLab](https://github.com/gchaincl/httplab) - HTTPLabs let you inspect HTTP requests and forge responses. ![stars](https://img.shields.io/badge/stars-4062-blue)
- [httpproxy](https://github.com/wzshiming/httpproxy) - HTTP proxy handler and dialer. ![stars](https://img.shields.io/badge/stars-28-blue)
- [iplib](https://github.com/c-robinson/iplib) - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html) ![stars](https://img.shields.io/badge/stars-144-blue)
- [jazigo](https://github.com/udhos/jazigo) - Jazigo is a tool written in Go for retrieving configuration for multiple network devices. ![stars](https://img.shields.io/badge/stars-217-blue)
- [kcp-go](https://github.com/xtaci/kcp-go) - KCP - Fast and Reliable ARQ Protocol. ![stars](https://img.shields.io/badge/stars-4150-blue)
- [kcptun](https://github.com/xtaci/kcptun) - Extremely simple & fast udp tunnel based on KCP protocol. ![stars](https://img.shields.io/badge/stars-14016-blue)
- [lhttp](https://github.com/fanux/lhttp) - Powerful websocket framework, build your IM server more easily. ![stars](https://img.shields.io/badge/stars-690-blue)
- [linkio](https://github.com/ian-kent/linkio) - Network link speed simulation for Reader/Writer interfaces. ![stars](https://img.shields.io/badge/stars-53-blue)
- [llb](https://github.com/kirillDanshin/llb) - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response. ![stars](https://img.shields.io/badge/stars-16-blue)
- [mdns](https://github.com/hashicorp/mdns) - Simple mDNS (Multicast DNS) client/server library in Golang. ![stars](https://img.shields.io/badge/stars-1209-blue)
- [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
- [natiu-mqtt](https://github.com/soypat/natiu-mqtt) - A dead-simple, non-allocating, low level implementation of MQTT well suited for embedded systems. ![stars](https://img.shields.io/badge/stars-90-blue)
- [nbio](https://github.com/lesismal/nbio) - Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use. ![stars](https://img.shields.io/badge/stars-2288-blue)
- [net](https://golang.org/x/net) - This repository holds supplementary Go networking libraries.
- [netpoll](https://github.com/cloudwego/netpoll) - A high-performance non-blocking I/O networking framework, which focused on RPC scenarios, developed by ByteDance. ![stars](https://img.shields.io/badge/stars-4135-blue)
- [NFF-Go](https://github.com/intel-go/nff-go) - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF). ![stars](https://img.shields.io/badge/stars-1390-blue)
- [packet](https://github.com/aerogo/packet) - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed. ![stars](https://img.shields.io/badge/stars-80-blue)
- [peerdiscovery](https://github.com/schollz/peerdiscovery) - Pure Go library for cross-platform local peer discovery using UDP multicast. ![stars](https://img.shields.io/badge/stars-651-blue)
- [portproxy](https://github.com/aybabtme/portproxy) - Simple TCP proxy which adds CORS support to API's which don't support it. ![stars](https://img.shields.io/badge/stars-57-blue)
- [psql-wire](https://github.com/jeroenrinzema/psql-wire) - PostgreSQL server wire protocol. Build your own server and start serving connections.. ![stars](https://img.shields.io/badge/stars-114-blue)
- [publicip](https://github.com/polera/publicip) - Package publicip returns your public facing IPv4 address (internet egress). ![stars](https://img.shields.io/badge/stars-28-blue)
- [quic-go](https://github.com/lucas-clemente/quic-go) - An implementation of the QUIC protocol in pure Go. ![stars](https://img.shields.io/badge/stars-10327-blue)
- [raw](https://github.com/mdlayher/raw) - Package raw enables reading and writing data at the device driver level for a network interface. ![stars](https://img.shields.io/badge/stars-424-blue)
- [sdns](https://github.com/semihalev/sdns) - A high-performance, recursive DNS resolver server with DNSSEC support, focused on preserving privacy. ![stars](https://img.shields.io/badge/stars-970-blue)
- [sftp](https://github.com/pkg/sftp) - Package sftp implements the SSH File Transfer Protocol as described in <https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>. ![stars](https://img.shields.io/badge/stars-1536-blue)
- [ssh](https://github.com/gliderlabs/ssh) - Higher-level API for building SSH servers (wraps crypto/ssh). ![stars](https://img.shields.io/badge/stars-3776-blue)
- [sslb](https://github.com/eduardonunesp/sslb) - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance. ![stars](https://img.shields.io/badge/stars-149-blue)
- [stun](https://github.com/go-rtc/stun) - Go implementation of RFC 5389 STUN protocol. ![stars](https://img.shields.io/badge/stars-495-blue)
- [tcp_server](https://github.com/firstrow/tcp_server) - Go library for building tcp servers faster. ![stars](https://img.shields.io/badge/stars-425-blue)
- [tcpack](https://github.com/lim-yoona/tcpack) - tcpack is an application protocol based on TCP to Pack and Unpack bytes stream in go program. ![stars](https://img.shields.io/badge/stars-171-blue)
- [tspool](https://github.com/two/tspool) - A TCP Library use worker pool to improve performance and protect your server. ![stars](https://img.shields.io/badge/stars-14-blue)
- [tun2socks](https://github.com/xjasonlyu/tun2socks) - A pure go implementation of tun2socks powered by [gVisor](https://gvisor.dev/) TCP/IP stack. ![stars](https://img.shields.io/badge/stars-3552-blue)
- [utp](https://github.com/anacrolix/utp) - Go uTP micro transport protocol implementation. ![stars](https://img.shields.io/badge/stars-177-blue)
- [vssh](https://github.com/yahoo/vssh) - Go library for building network and server automation over SSH protocol. ![stars](https://img.shields.io/badge/stars-965-blue)
- [water](https://github.com/songgao/water) - Simple TUN/TAP library. ![stars](https://img.shields.io/badge/stars-1982-blue)
- [webrtc](https://github.com/pions/webrtc) - A pure Go implementation of the WebRTC API. ![stars](https://img.shields.io/badge/stars-14143-blue)
- [winrm](https://github.com/masterzen/winrm) - Go WinRM client to remotely execute commands on Windows machines. ![stars](https://img.shields.io/badge/stars-424-blue)
- [xtcp](https://github.com/xfxdev/xtcp) - TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol. ![stars](https://img.shields.io/badge/stars-155-blue)

**[⬆ back to top](#contents)**

### HTTP Clients

_Libraries for making HTTP requests._

- [azuretls-client](https://github.com/Noooste/azuretls-client) -  An easy-to-use HTTP client 100% in Go to spoof TLS/JA3 and HTTP2 fingerprint ![stars](https://img.shields.io/badge/stars-196-blue)
- [fast-shot](https://github.com/opus-domini/fast-shot) - Hit your API targets with rapid-fire precision using Go's fastest and simple HTTP Client. ![stars](https://img.shields.io/badge/stars-78-blue)
- [gentleman](https://github.com/h2non/gentleman) - Full-featured plugin-driven HTTP client library. ![stars](https://img.shields.io/badge/stars-1088-blue)
- [go-cleanhttp](https://github.com/hashicorp/go-cleanhttp) - Get easily stdlib HTTP client, which does not share any state with other clients. ![stars](https://img.shields.io/badge/stars-379-blue)
- [go-http-client](https://github.com/bozd4g/go-http-client) - Make http calls simply and easily. ![stars](https://img.shields.io/badge/stars-80-blue)
- [go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) - Go http.RoundTripper that emits open telemetry metrics for HTTP requests. ![stars](https://img.shields.io/badge/stars-83-blue)
- [go-req](https://github.com/wenerme/go-req) - Declarative golang HTTP client. ![stars](https://img.shields.io/badge/stars-22-blue)
- [go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) - Retryable HTTP client in Go. ![stars](https://img.shields.io/badge/stars-2038-blue)
- [go-zoox/fetch](https://github.com/go-zoox/fetch) - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API. ![stars](https://img.shields.io/badge/stars-73-blue)
- [grequests](https://github.com/levigross/grequests) - A Go "clone" of the great and famous Requests library. ![stars](https://img.shields.io/badge/stars-2144-blue)
- [heimdall](https://github.com/gojektech/heimdall) - An enhanced http client with retry and hystrix capabilities. ![stars](https://img.shields.io/badge/stars-2640-blue)
- [httpretry](https://github.com/ybbus/httpretry) - Enriches the default go HTTP client with retry functionality. ![stars](https://img.shields.io/badge/stars-49-blue)
- [pester](https://github.com/sethgrid/pester) - Go HTTP client calls with retries, backoff, and concurrency. ![stars](https://img.shields.io/badge/stars-652-blue)
- [req](https://github.com/imroc/req) - Simple Go HTTP client with Black Magic (Less code and More efficiency). ![stars](https://img.shields.io/badge/stars-4358-blue)
- [request](https://github.com/monaco-io/request) - HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency. ![stars](https://img.shields.io/badge/stars-292-blue)
- [requests](https://github.com/carlmjohnson/requests) - HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools. ![stars](https://img.shields.io/badge/stars-1548-blue)
- [resty](https://github.com/go-resty/resty) - Simple HTTP and REST client for Go inspired by Ruby rest-client. ![stars](https://img.shields.io/badge/stars-10370-blue)
- [rq](https://github.com/ddo/rq) - A nicer interface for golang stdlib HTTP client. ![stars](https://img.shields.io/badge/stars-52-blue)
- [sling](https://github.com/dghubble/sling) - Sling is a Go HTTP client library for creating and sending API requests. ![stars](https://img.shields.io/badge/stars-1690-blue)
- [tls-client](https://github.com/bogdanfinn/tls-client) - net/http.Client like HTTP Client with options to select specific client TLS Fingerprints to use for requests. ![stars](https://img.shields.io/badge/stars-929-blue)

**[⬆ back to top](#contents)**

## OpenGL

_Libraries for using OpenGL in Go._

- [gl](https://github.com/go-gl/gl) - Go bindings for OpenGL (generated via glow). ![stars](https://img.shields.io/badge/stars-1110-blue)
- [glfw](https://github.com/go-gl/glfw) - Go bindings for GLFW 3. ![stars](https://img.shields.io/badge/stars-1600-blue)
- [go-glmatrix](https://github.com/technohippy/go-glmatrix) - Go port of [glMatrix](https://glmatrix.net/) library. ![stars](https://img.shields.io/badge/stars-11-blue)
- [goxjs/gl](https://github.com/goxjs/gl) - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android). ![stars](https://img.shields.io/badge/stars-177-blue)
- [goxjs/glfw](https://github.com/goxjs/glfw) - Go cross-platform glfw library for creating an OpenGL context and receiving events. ![stars](https://img.shields.io/badge/stars-83-blue)
- [mathgl](https://github.com/go-gl/mathgl) - Pure Go math package specialized for 3D math, with inspiration from GLM. ![stars](https://img.shields.io/badge/stars-565-blue)

**[⬆ back to top](#contents)**

## ORM

_Libraries that implement Object-Relational Mapping or datamapping techniques._

- [bob](https://github.com/stephenafamo/bob) - SQL query builder and ORM/Factory generator for Go. Successor of SQLBoiler. ![stars](https://img.shields.io/badge/stars-859-blue)
- [bun](https://github.com/uptrace/bun) - SQL-first Golang ORM. Successor of go-pg. ![stars](https://img.shields.io/badge/stars-3943-blue)
- [cacheme](https://github.com/Yiling-J/cacheme-go) - Schema based, typed Redis caching/memoize framework for Go. ![stars](https://img.shields.io/badge/stars-23-blue)
- [CQL](https://github.com/FrancoLiberali/cql) - Built on top of GORM, adds compile-time verified queries based on auto-generated code. ![stars](https://img.shields.io/badge/stars-17-blue)
- [ent](https://github.com/facebook/ent) - An entity framework for Go. Simple, yet powerful ORM for modeling and querying data. ![stars](https://img.shields.io/badge/stars-15822-blue)
- [go-dbw](https://github.com/hashicorp/go-dbw) - A simple package that encapsulates database operations. ![stars](https://img.shields.io/badge/stars-15-blue)
- [go-firestorm](https://github.com/jschoedt/go-firestorm) - A simple ORM for Google/Firebase Cloud Firestore. ![stars](https://img.shields.io/badge/stars-52-blue)
- [go-sql](https://github.com/rushteam/gosql) - A easy ORM for mysql. ![stars](https://img.shields.io/badge/stars-179-blue)
- [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) - A flexible and powerful SQL string builder library plus a zero-config ORM. ![stars](https://img.shields.io/badge/stars-1489-blue)
- [go-store](https://github.com/gosuri/go-store) - Simple and fast Redis backed key-value store library for Go. ![stars](https://img.shields.io/badge/stars-112-blue)
- [golobby/orm](https://github.com/golobby/orm) - Simple, fast, type-safe, generic orm for developer happiness. ![stars](https://img.shields.io/badge/stars-160-blue)
- [GORM](https://github.com/go-gorm/gorm) - The fantastic ORM library for Golang, aims to be developer friendly. ![stars](https://img.shields.io/badge/stars-37297-blue)
- [gormt](https://github.com/xxjwxc/gormt) - Mysql database to golang gorm struct. ![stars](https://img.shields.io/badge/stars-2376-blue)
- [gorp](https://github.com/go-gorp/gorp) - Go Relational Persistence, ORM-ish library for Go. ![stars](https://img.shields.io/badge/stars-3734-blue)
- [grimoire](https://github.com/Fs02/grimoire) - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3). ![stars](https://img.shields.io/badge/stars-164-blue)
- [lore](https://github.com/abrahambotros/lore) - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go. ![stars](https://img.shields.io/badge/stars-14-blue)
- [marlow](https://github.com/marlow/marlow) - Generated ORM from project structs for compile time safety assurances. ![stars](https://img.shields.io/badge/stars-13-blue)
- [pop/soda](https://github.com/gobuffalo/pop) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite. ![stars](https://img.shields.io/badge/stars-1459-blue)
- [Prisma](https://github.com/prisma/prisma-client-go) - Prisma Client Go, Typesafe database access for Go. ![stars](https://img.shields.io/badge/stars-2211-blue)
- [reform](https://github.com/go-reform/reform) - Better ORM for Go, based on non-empty interfaces and code generation. ![stars](https://img.shields.io/badge/stars-1444-blue)
- [rel](https://github.com/go-rel/rel) - Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API. ![stars](https://img.shields.io/badge/stars-775-blue)
- [SQLBoiler](https://github.com/volatiletech/sqlboiler) - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema. ![stars](https://img.shields.io/badge/stars-6787-blue)
- [upper.io/db](https://github.com/upper/db) - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers. ![stars](https://img.shields.io/badge/stars-3552-blue)
- [XORM](https://gitea.com/xorm/xorm) - Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle).
- [Zoom](https://github.com/albrow/zoom) - Blazing-fast datastore and querying engine built on Redis. ![stars](https://img.shields.io/badge/stars-309-blue)

**[⬆ back to top](#contents)**

## Package Management

_Official tooling for dependency and package management_

- [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

_Unofficial libraries for package and dependency management._

- [glide](https://github.com/Masterminds/glide) - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip. ![stars](https://img.shields.io/badge/stars-8145-blue)
- [godep](https://github.com/tools/godep) - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies. ![stars](https://img.shields.io/badge/stars-5534-blue)
- [goop](https://github.com/nitrous-io/goop) - Simple dependency manager for Go (golang), inspired by Bundler. ![stars](https://img.shields.io/badge/stars-776-blue)
- [gop](https://github.com/lunny/gop) - Build and manage your Go applications out of GOPATH. ![stars](https://img.shields.io/badge/stars-49-blue)
- [gopm](https://github.com/gpmgo/gopm) - Go Package Manager. ![stars](https://img.shields.io/badge/stars-2465-blue)
- [govendor](https://github.com/kardianos/govendor) - Go Package Manager. Go vendor tool that works with the standard vendor file. ![stars](https://img.shields.io/badge/stars-4928-blue)
- [gpm](https://github.com/pote/gpm) - Barebones dependency manager for Go. ![stars](https://img.shields.io/badge/stars-1186-blue)
- [gup](https://github.com/nao1215/gup) - Update binaries installed by "go install". ![stars](https://img.shields.io/badge/stars-368-blue)
- [johnny-deps](https://github.com/VividCortex/johnny-deps) - Minimal dependency version using Git. ![stars](https://img.shields.io/badge/stars-213-blue)
- [modgv](https://github.com/lucasepe/modgv) - Converts 'go mod graph' output into Graphviz's DOT language. ![stars](https://img.shields.io/badge/stars-490-blue)
- [mvn-golang](https://github.com/raydac/mvn-golang) - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure. ![stars](https://img.shields.io/badge/stars-164-blue)
- [syft](https://github.com/anchore/syft) - A CLI tool and Go library for generating a Software Bill of Materials (SBOM) from container images and filesystems. ![stars](https://img.shields.io/badge/stars-6480-blue)
- [VenGO](https://github.com/DamnWidget/VenGO) - create and manage exportable isolated go virtual environments. ![stars](https://img.shields.io/badge/stars-124-blue)

**[⬆ back to top](#contents)**

## Performance

- [go-instrument](https://github.com/nikolaydubina/go-instrument) - Automatically add spans to all methods and functions. ![stars](https://img.shields.io/badge/stars-239-blue)
- [jaeger](https://github.com/jaegertracing/jaeger) - A distributed tracing system. ![stars](https://img.shields.io/badge/stars-20784-blue)
- [mm-go](https://github.com/joetifa2003/mm-go) - Generic manual memory management for golang. ![stars](https://img.shields.io/badge/stars-157-blue)
- [pixie](https://github.com/pixie-labs/pixie) - No instrumentation tracing for Golang applications via eBPF. ![stars](https://img.shields.io/badge/stars-5692-blue)
- [profile](https://github.com/pkg/profile) - Simple profiling support package for Go. ![stars](https://img.shields.io/badge/stars-2019-blue)
- [statsviz](https://github.com/arl/statsviz) - Live visualization of your Go application runtime statistics. ![stars](https://img.shields.io/badge/stars-3244-blue)
- [tracer](https://github.com/kamilsk/tracer) - Simple, lightweight tracing. ![stars](https://img.shields.io/badge/stars-87-blue)

**[⬆ back to top](#contents)**

## Query Language

- [api-fu](https://github.com/ccbrown/api-fu) - Comprehensive GraphQL implementation. ![stars](https://img.shields.io/badge/stars-56-blue)
- [dasel](https://github.com/tomwright/dasel) - Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies. ![stars](https://img.shields.io/badge/stars-7303-blue)
- [gojsonq](https://github.com/thedevsaddam/gojsonq) - A simple Go package to Query over JSON Data. ![stars](https://img.shields.io/badge/stars-2195-blue)
- [goven](https://github.com/SeldonIO/goven) - A drop-in query language for any database schema. ![stars](https://img.shields.io/badge/stars-60-blue)
- [gqlgen](https://github.com/99designs/gqlgen) - go generate based graphql server library. ![stars](https://img.shields.io/badge/stars-10063-blue)
- [grapher](https://github.com/reaganiwadha/grapher) - A GraphQL field builder utilizing Go generics with extra utilities and features. ![stars](https://img.shields.io/badge/stars-3-blue)
- [graphql](https://github.com/tmc/graphql) - graphql parser + utilities. ![stars](https://img.shields.io/badge/stars-57-blue)
- [graphql](https://github.com/neelance/graphql-go) - GraphQL server with a focus on ease of use. ![stars](https://img.shields.io/badge/stars-4668-blue)
- [graphql-go](https://github.com/graphql-go/graphql) - Implementation of GraphQL for Go. ![stars](https://img.shields.io/badge/stars-9957-blue)
- [gws](https://github.com/Zaba505/gws) - Apollos' "GraphQL over Websocket" client and server implementation. ![stars](https://img.shields.io/badge/stars-6-blue)
- [jsonpath](https://github.com/AsaiYusuke/jsonpath) - A query library for retrieving part of JSON based on JSONPath syntax. ![stars](https://img.shields.io/badge/stars-25-blue)
- [jsonql](https://github.com/elgs/jsonql) - JSON query expression library in Golang. ![stars](https://img.shields.io/badge/stars-276-blue)
- [jsonslice](https://github.com/bhmj/jsonslice) - Jsonpath queries with advanced filters. ![stars](https://img.shields.io/badge/stars-89-blue)
- [mql](https://github.com/hashicorp/mql) - Model Query Language (mql) is a query language for your database models. ![stars](https://img.shields.io/badge/stars-48-blue)
- [rql](https://github.com/a8m/rql) - Resource Query Language for REST API. ![stars](https://img.shields.io/badge/stars-346-blue)
- [rqp](https://github.com/timsolov/rest-query-parser) - Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query. ![stars](https://img.shields.io/badge/stars-80-blue)
- [straf](https://github.com/SonicRoshan/straf) - Easily Convert Golang structs to GraphQL objects. ![stars](https://img.shields.io/badge/stars-39-blue)

**[⬆ back to top](#contents)**

## Reflection

- [copy](https://github.com/gotidy/copy) - Package for fast copying structs of different types. ![stars](https://img.shields.io/badge/stars-49-blue)
- [Deepcopier](https://github.com/ulule/deepcopier) - Simple struct copying for Go. ![stars](https://img.shields.io/badge/stars-456-blue)
- [go-deepcopy](https://github.com/tiendc/go-deepcopy) - Fast deep copy library. ![stars](https://img.shields.io/badge/stars-38-blue)
- [goenum](https://github.com/lvyahui8/goenum) - A common enumeration struct based on generics and reflection that allows you to quickly define enumerations and use a set of useful default methods. ![stars](https://img.shields.io/badge/stars-12-blue)
- [gotype](https://github.com/wzshiming/gotype) - Golang source code parsing, usage like reflect package. ![stars](https://img.shields.io/badge/stars-62-blue)
- [gpath](https://github.com/tenntenn/gpath) - Library to simplify access struct fields with Go's expression in reflection. ![stars](https://img.shields.io/badge/stars-40-blue)
- [objwalker](https://github.com/rekby/objwalker) - Walk by go objects with reflection. ![stars](https://img.shields.io/badge/stars-3-blue)
- [reflectutils](https://github.com/muir/reflectutils) - Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string. ![stars](https://img.shields.io/badge/stars-8-blue)

**[⬆ back to top](#contents)**

## Resource Embedding

- [debme](https://github.com/leaanthony/debme) - Create an `embed.FS` from an existing `embed.FS` subdirectory. ![stars](https://img.shields.io/badge/stars-33-blue)
- [fileb0x](https://github.com/UnnoTed/fileb0x) - Simple tool to embed files in go with focus on "customization" and ease to use. ![stars](https://img.shields.io/badge/stars-635-blue)
- [go-resources](https://github.com/omeid/go-resources) - Unfancy resources embedding with Go. ![stars](https://img.shields.io/badge/stars-177-blue)
- [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy. ![stars](https://img.shields.io/badge/stars-2426-blue)
- [mule](https://github.com/wlbr/mule) - Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focused on simplicity. ![stars](https://img.shields.io/badge/stars-15-blue)
- [packr](https://github.com/gobuffalo/packr) - The simple and easy way to embed static files into Go binaries. ![stars](https://img.shields.io/badge/stars-3410-blue)
- [rebed](https://github.com/soypat/rebed) - Recreate folder structures and files from Go 1.16's `embed.FS` type ![stars](https://img.shields.io/badge/stars-29-blue)
- [statik](https://github.com/rakyll/statik) - Embeds static files into a Go executable. ![stars](https://img.shields.io/badge/stars-3772-blue)
- [templify](https://github.com/wlbr/templify) - Embed external template files into Go code to create single file binaries. ![stars](https://img.shields.io/badge/stars-30-blue)
- [vfsgen](https://github.com/shurcooL/vfsgen) - Generates a vfsdata.go file that statically implements the given virtual filesystem. ![stars](https://img.shields.io/badge/stars-984-blue)

**[⬆ back to top](#contents)**

## Science and Data Analysis

_Libraries for scientific computing and data analyzing._

- [assocentity](https://github.com/ndabAP/assocentity) - Package assocentity returns the average distance from words to a given entity. ![stars](https://img.shields.io/badge/stars-15-blue)
- [bradleyterry](https://github.com/seanhagen/bradleyterry) - Provides a Bradley-Terry Model for pairwise comparisons. ![stars](https://img.shields.io/badge/stars-11-blue)
- [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) - Calendar heatmap in plain Go inspired by Github contribution activity. ![stars](https://img.shields.io/badge/stars-403-blue)
- [chart](https://github.com/vdobler/chart) - Simple Chart Plotting library for Go. Supports many graphs types. ![stars](https://img.shields.io/badge/stars-772-blue)
- [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) - Dataframes for machine-learning and statistics (similar to pandas). ![stars](https://img.shields.io/badge/stars-1212-blue)
- [decimal](https://github.com/db47h/decimal) - Package decimal implements arbitrary-precision decimal floating-point arithmetic. ![stars](https://img.shields.io/badge/stars-42-blue)
- [evaler](https://github.com/soniah/evaler) - Simple floating point arithmetic expression evaluator. ![stars](https://img.shields.io/badge/stars-51-blue)
- [ewma](https://github.com/VividCortex/ewma) - Exponentially-weighted moving averages. ![stars](https://img.shields.io/badge/stars-441-blue)
- [geom](https://github.com/skelterjohn/geom) - 2D geometry for golang. ![stars](https://img.shields.io/badge/stars-55-blue)
- [go-dsp](https://github.com/mjibson/go-dsp) - Digital Signal Processing for Go. ![stars](https://img.shields.io/badge/stars-866-blue)
- [go-estimate](https://github.com/milosgajdos/go-estimate) - State estimation and filtering algorithms in Go. ![stars](https://img.shields.io/badge/stars-115-blue)
- [go-gt](https://github.com/ThePaw/go-gt) - Graph theory algorithms written in "Go" language. ![stars](https://img.shields.io/badge/stars-11-blue)
- [go-hep](https://github.com/go-hep/hep) - A set of libraries and tools for performing High Energy Physics analyses with ease. ![stars](https://img.shields.io/badge/stars-233-blue)
- [godesim](https://github.com/soypat/godesim) - Extended/multivariable ODE solver framework for event-based simulations with simple API. ![stars](https://img.shields.io/badge/stars-23-blue)
- [goent](https://github.com/kzahedi/goent) - GO Implementation of Entropy Measures. ![stars](https://img.shields.io/badge/stars-35-blue)
- [gograph](https://github.com/hmdsefi/gograph) - A golang generic graph library that provides mathematical graph-theory and algorithms. ![stars](https://img.shields.io/badge/stars-73-blue)
- [gohistogram](https://github.com/VividCortex/gohistogram) - Approximate histograms for data streams. ![stars](https://img.shields.io/badge/stars-175-blue)
- [gonum](https://github.com/gonum/gonum) - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more. ![stars](https://img.shields.io/badge/stars-7747-blue)
- [gonum/plot](https://github.com/gonum/plot) - gonum/plot provides an API for building and drawing plots in Go. ![stars](https://img.shields.io/badge/stars-2772-blue)
- [goraph](https://github.com/gyuho/goraph) - Pure Go graph theory library(data structure, algorithm visualization). ![stars](https://img.shields.io/badge/stars-740-blue)
- [gosl](https://github.com/cpmech/gosl) - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more. ![stars](https://img.shields.io/badge/stars-1838-blue)
- [GoStats](https://github.com/OGFris/GoStats) - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions. ![stars](https://img.shields.io/badge/stars-22-blue)
- [graph](https://github.com/yourbasic/graph) - Library of basic graph algorithms. ![stars](https://img.shields.io/badge/stars-714-blue)
- [jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) - Tool to manipulate JSONL graphs with graphviz support. ![stars](https://img.shields.io/badge/stars-74-blue)
- [ode](https://github.com/ChristopherRabotin/ode) - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions. ![stars](https://img.shields.io/badge/stars-22-blue)
- [orb](https://github.com/paulmach/orb) - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support. ![stars](https://img.shields.io/badge/stars-934-blue)
- [pagerank](https://github.com/alixaxel/pagerank) - Weighted PageRank algorithm implemented in Go. ![stars](https://img.shields.io/badge/stars-85-blue)
- [piecewiselinear](https://github.com/sgreben/piecewiselinear) - Tiny linear interpolation library. ![stars](https://img.shields.io/badge/stars-27-blue)
- [PiHex](https://github.com/claygod/PiHex) - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi. ![stars](https://img.shields.io/badge/stars-20-blue)
- [Poly](https://github.com/bebop/poly) - A Go package for engineering organisms. ![stars](https://img.shields.io/badge/stars-681-blue)
- [rootfinding](https://github.com/khezen/rootfinding) - root-finding algorithms library for finding roots of quadratic functions. ![stars](https://img.shields.io/badge/stars-11-blue)
- [sparse](https://github.com/james-bowman/sparse) - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries. ![stars](https://img.shields.io/badge/stars-162-blue)
- [stats](https://github.com/montanaflynn/stats) - Statistics package with common functions missing from the Golang standard library. ![stars](https://img.shields.io/badge/stars-2941-blue)
- [streamtools](https://github.com/nytlabs/streamtools) - general purpose, graphical tool for dealing with streams of data. ![stars](https://img.shields.io/badge/stars-1311-blue)
- [TextRank](https://github.com/DavidBelicza/TextRank) - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support. ![stars](https://img.shields.io/badge/stars-206-blue)
- [topk](https://github.com/keilerkonzept/topk) - Sliding-window and regular top-K sketches, based on the HeavyKeeper algorithm. ![stars](https://img.shields.io/badge/stars-5-blue)
- [triangolatte](https://github.com/tchayen/triangolatte) - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs. ![stars](https://img.shields.io/badge/stars-36-blue)

**[⬆ back to top](#contents)**

## Security

_Libraries that are used to help make your application more secure._

- [acmetool](https://github.com/hlandau/acme) - ACME (Let's Encrypt) client tool with automatic renewal. ![stars](https://img.shields.io/badge/stars-2059-blue)
- [acopw-go](https://sr.ht/~jamesponddotco/acopw-go/) - Small cryptographically secure password generator package for Go.
- [acra](https://github.com/cossacklabs/acra) - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system. ![stars](https://img.shields.io/badge/stars-1369-blue)
- [age](https://github.com/FiloSottile/age) - A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability. ![stars](https://img.shields.io/badge/stars-17885-blue)
- [argon2-hashing](https://github.com/andskur/argon2-hashing) - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package. ![stars](https://img.shields.io/badge/stars-20-blue)
- [argon2pw](https://github.com/raja/argon2pw) - Argon2 password hash generation with constant-time password comparison. ![stars](https://img.shields.io/badge/stars-91-blue)
- [autocert](https://pkg.go.dev/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
- [BadActor](https://github.com/jaredfolkins/badactor) - In-memory, application-driven jailer built in the spirit of fail2ban. ![stars](https://img.shields.io/badge/stars-320-blue)
- [beelzebub](https://github.com/mariocandela/beelzebub) - A secure low code honeypot framework, leveraging AI for System Virtualization. ![stars](https://img.shields.io/badge/stars-727-blue)
- [booster](https://github.com/anatol/booster) - Fast initramfs generator with full-disk encryption support. ![stars](https://img.shields.io/badge/stars-550-blue)
- [Cameradar](https://github.com/Ullaakut/cameradar) - Tool and library to remotely hack RTSP streams from surveillance cameras. ![stars](https://img.shields.io/badge/stars-4184-blue)
- [certificates](https://github.com/mvmaasakkers/certificates) - An opinionated tool for generating tls certificates. ![stars](https://img.shields.io/badge/stars-39-blue)
- [CertMagic](https://github.com/caddyserver/certmagic) - Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal. ![stars](https://img.shields.io/badge/stars-5100-blue)
- [Coraza](https://github.com/corazawaf/coraza) - Enterprise-ready, modsecurity and OWASP CRS compatible WAF library. ![stars](https://img.shields.io/badge/stars-2370-blue)
- [dongle](https://github.com/golang-module/dongle) - A simple, semantic and developer-friendly golang package for encoding&decoding and encryption&decryption. ![stars](https://img.shields.io/badge/stars-958-blue)
- [encid](https://github.com/bobg/encid) - Encode and decode encrypted integer IDs. ![stars](https://img.shields.io/badge/stars-3-blue)
- [entpassgen](https://github.com/andreimerlescu/entpassgen) - Entropy Password Generator with extensive command line arguments to generate random strings securely including digits, passwords, and passwords built using obscure dictionary words mixed with symbols and digits.  ![stars](https://img.shields.io/badge/stars-4-blue)
- [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) - A rest application to dynamically update firewalld rules on a linux server. ![stars](https://img.shields.io/badge/stars-338-blue)
- [go-generate-password](https://github.com/m1/go-generate-password) - Password generator that can be used on the cli or as a library. ![stars](https://img.shields.io/badge/stars-55-blue)
- [go-htpasswd](https://github.com/tg123/go-htpasswd) - Apache htpasswd Parser for Go. ![stars](https://img.shields.io/badge/stars-41-blue)
- [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) - Password validator based on raw cryptographic entropy values. ![stars](https://img.shields.io/badge/stars-510-blue)
- [go-peer](https://github.com/number571/go-peer) - A software library for creating secure and anonymous decentralized systems. ![stars](https://img.shields.io/badge/stars-279-blue)
- [go-yara](https://github.com/hillu/go-yara) - Go Bindings for [YARA](https://github.com/plusvic/yara), the "pattern matching swiss knife for malware researchers (and everyone else)". ![stars](https://img.shields.io/badge/stars-364-blue)
- [goArgonPass](https://github.com/dwin/goArgonPass) - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations. ![stars](https://img.shields.io/badge/stars-19-blue)
- [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) - A probably paranoid package for securely hashing and encrypting passwords. ![stars](https://img.shields.io/badge/stars-60-blue)
- [Interpol](https://github.com/avahidi/interpol) - Rule-based data generator for fuzzing and penetration testing. ![stars](https://img.shields.io/badge/stars-5-blue)
- [lego](https://github.com/go-acme/lego) - Pure Go ACME client library and CLI tool (for use with Let's Encrypt). ![stars](https://img.shields.io/badge/stars-8154-blue)
- [luks.go](https://github.com/anatol/luks.go) - Pure Golang library to manage LUKS partitions. ![stars](https://img.shields.io/badge/stars-89-blue)
- [memguard](https://github.com/awnumar/memguard) - A pure Go library for handling sensitive values in memory. ![stars](https://img.shields.io/badge/stars-2571-blue)
- [multikey](https://github.com/adrianosela/multikey) - An n-out-of-N keys encryption/decryption framework based on Shamir's Secret Sharing algorithm. ![stars](https://img.shields.io/badge/stars-6-blue)
- [nacl](https://github.com/kevinburke/nacl) - Go implementation of the NaCL set of API's. ![stars](https://img.shields.io/badge/stars-545-blue)
- [optimus-go](https://github.com/pjebs/optimus-go) - ID hashing and Obfuscation using Knuth's Algorithm. ![stars](https://img.shields.io/badge/stars-362-blue)
- [passlib](https://github.com/hlandau/passlib) - Futureproof password hashing library. ![stars](https://img.shields.io/badge/stars-288-blue)
- [passwap](https://github.com/zitadel/passwap) - Provides a unified implementation between different password hashing algorithms ![stars](https://img.shields.io/badge/stars-55-blue)
- [qrand](https://github.com/bitfield/qrand) - Client for the ANU Quantum Numbers (AQN) API, providing quantum-mechanically secure random data. ![stars](https://img.shields.io/badge/stars-16-blue)
- [secret](https://github.com/rsjethani/secret) - Prevent your secrets from leaking into logs, std\* etc. ![stars](https://img.shields.io/badge/stars-29-blue)
- [secure](https://github.com/unrolled/secure) - HTTP middleware for Go that facilitates some quick security wins. ![stars](https://img.shields.io/badge/stars-2289-blue)
- [secureio](https://github.com/xaionaro-go/secureio) - An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519. ![stars](https://img.shields.io/badge/stars-34-blue)
- [simple-scrypt](https://github.com/elithrar/simple-scrypt) - Scrypt package with a simple, obvious API and automatic cost calibration built-in. ![stars](https://img.shields.io/badge/stars-198-blue)
- [ssh-vault](https://github.com/ssh-vault/ssh-vault) - encrypt/decrypt using ssh keys. ![stars](https://img.shields.io/badge/stars-455-blue)
- [sslmgr](https://github.com/adrianosela/sslmgr) - SSL certificates made easy with a high level wrapper around acme/autocert. ![stars](https://img.shields.io/badge/stars-27-blue)
- [teler-waf](https://github.com/kitabisa/teler-waf) - teler-waf is a Go HTTP middleware that provide teler IDS functionality to protect against web-based attacks and improve the security of Go-based web applications. It is highly configurable and easy to integrate into existing Go applications. ![stars](https://img.shields.io/badge/stars-362-blue)
- [themis](https://github.com/cossacklabs/themis) - high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps. ![stars](https://img.shields.io/badge/stars-1887-blue)

**[⬆ back to top](#contents)**

## Serialization

_Libraries and tools for binary serialization._

- [asn1](https://github.com/PromonLogicalis/asn1) - Asn.1 BER and DER encoding library for golang. ![stars](https://img.shields.io/badge/stars-55-blue)
- [bambam](https://github.com/glycerine/bambam) - generator for Cap'n Proto schemas from go. ![stars](https://img.shields.io/badge/stars-65-blue)
- [bel](https://github.com/32leaves/bel) - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC. ![stars](https://img.shields.io/badge/stars-43-blue)
- [binstruct](https://github.com/ghostiam/binstruct) - Golang binary decoder for mapping data into the structure. ![stars](https://img.shields.io/badge/stars-100-blue)
- [cbor](https://github.com/fxamacker/cbor) - Small, safe, and easy CBOR encoding and decoding library. ![stars](https://img.shields.io/badge/stars-759-blue)
- [colfer](https://github.com/pascaldekloe/colfer) - Code generation for the Colfer binary format. ![stars](https://img.shields.io/badge/stars-746-blue)
- [csvutil](https://github.com/jszwec/csvutil) - High Performance, idiomatic CSV record encoding and decoding to native Go structures. ![stars](https://img.shields.io/badge/stars-947-blue)
- [elastic](https://github.com/epiclabs-io/elastic) - Convert slices, maps or any other unknown value across different types at run-time, no matter what. ![stars](https://img.shields.io/badge/stars-23-blue)
- [fixedwidth](https://github.com/huydang284/fixedwidth) - Fixed-width text formatting (UTF-8 supported). ![stars](https://img.shields.io/badge/stars-9-blue)
- [fwencoder](https://github.com/o1egl/fwencoder) - Fixed width file parser (encoding and decoding library) for Go. ![stars](https://img.shields.io/badge/stars-27-blue)
- [go-capnproto](https://github.com/glycerine/go-capnproto) - Cap'n Proto library and parser for go. ![stars](https://img.shields.io/badge/stars-288-blue)
- [go-codec](https://github.com/ugorji/go) - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support. ![stars](https://img.shields.io/badge/stars-1873-blue)
- [go-csvlib](https://github.com/tiendc/go-csvlib) - High level and rich functionalities CSV serialization/deserialization library. ![stars](https://img.shields.io/badge/stars-18-blue)
- [gogoprotobuf](https://github.com/gogo/protobuf) - Protocol Buffers for Go with Gadgets. ![stars](https://img.shields.io/badge/stars-5668-blue)
- [goprotobuf](https://github.com/golang/protobuf) - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers. ![stars](https://img.shields.io/badge/stars-9836-blue)
- [gotiny](https://github.com/raszia/gotiny) - Efficient Go serialization library, gotiny is almost as fast as serialization libraries that generate code. ![stars](https://img.shields.io/badge/stars-21-blue)
- [jsoniter](https://github.com/json-iterator/go) - High-performance 100% compatible drop-in replacement of "encoding/json". ![stars](https://img.shields.io/badge/stars-13530-blue)
- [mapstructure](https://github.com/mitchellh/mapstructure) - Go library for decoding generic map values into native Go structures. ![stars](https://img.shields.io/badge/stars-7950-blue)
- [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions. ![stars](https://img.shields.io/badge/stars-165-blue)
- [pletter](https://github.com/vimeda/pletter) - A standard way to wrap a proto message for message brokers. ![stars](https://img.shields.io/badge/stars-19-blue)
- [structomap](https://github.com/tuvistavie/structomap) - Library to easily and dynamically generate maps from static structures. ![stars](https://img.shields.io/badge/stars-144-blue)
- [unitpacking](https://github.com/recolude/unitpacking) - Library to pack unit vectors into as fewest bytes as possible. ![stars](https://img.shields.io/badge/stars-7-blue)

**[⬆ back to top](#contents)**

## Server Applications

- [algernon](https://github.com/xyproto/algernon) - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber. ![stars](https://img.shields.io/badge/stars-2861-blue)
- [Caddy](https://github.com/caddyserver/caddy) - Caddy is an alternative, HTTP/2 web server that's easy to configure and use. ![stars](https://img.shields.io/badge/stars-60450-blue)
- [Clace](https://github.com/claceio/clace) - Clace makes internal tool deployment and management easy by implementing an app server for containerized webapps. ![stars](https://img.shields.io/badge/stars-552-blue)
- [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
- [cortex-tenant](https://github.com/blind-oracle/cortex-tenant) - Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels. ![stars](https://img.shields.io/badge/stars-112-blue)
- [devd](https://github.com/cortesi/devd) - Local webserver for developers. ![stars](https://img.shields.io/badge/stars-3446-blue)
- [discovery](https://github.com/Bilibili/discovery) - A registry for resilient mid-tier load balancing and failover. ![stars](https://img.shields.io/badge/stars-1784-blue)
- [dudeldu](https://github.com/krotik/dudeldu) - A simple SHOUTcast server. ![stars](https://img.shields.io/badge/stars-143-blue)
- [dummy](https://github.com/neotoolkit/dummy) - Run mock server based off an API contract with one command. ![stars](https://img.shields.io/badge/stars-178-blue)
- [Easegress](https://github.com/megaease/easegress) - A cloud native high availability/performance traffic orchestration system with observability and extensibility. ![stars](https://img.shields.io/badge/stars-5796-blue)
- [Engity's Bifröst](https://bifroest.engity.org/) - Highly customizable SSH server with several ways to authorize a user how to execute its session (local or in containers).
- [etcd](https://github.com/etcd-io/etcd) - Highly-available key value store for shared configuration and service discovery. ![stars](https://img.shields.io/badge/stars-48196-blue)
- [Euterpe](https://github.com/ironsmile/euterpe) - Self-hosted music streaming server with built-in web UI and REST API. ![stars](https://img.shields.io/badge/stars-543-blue)
- [Fider](https://github.com/getfider/fider) - Fider is an open platform to collect and organize customer feedback. ![stars](https://img.shields.io/badge/stars-3133-blue)
- [Flagr](https://github.com/checkr/flagr) - Flagr is an open-source feature flagging and A/B testing service. ![stars](https://img.shields.io/badge/stars-2449-blue)
- [flipt](https://github.com/markphelps/flipt) - A self contained feature flag solution written in Go and Vue.js ![stars](https://img.shields.io/badge/stars-3990-blue)
- [go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) - A simple, complete and lightweight self-hosted feature flag solution 100% Open Source. ![stars](https://img.shields.io/badge/stars-1531-blue)
- [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) - Simple Reverse Proxy with Caching, written in Go, using Redis. ![stars](https://img.shields.io/badge/stars-133-blue)
- [gondola](https://github.com/bmf-san/gondola) - A YAML based golang reverse proxy. ![stars](https://img.shields.io/badge/stars-8-blue)
- [jackal](https://github.com/ortuman/jackal) - An XMPP server written in Go. ![stars](https://img.shields.io/badge/stars-1435-blue)
- [lets-proxy2](https://github.com/rekby/lets-proxy2) - Reverse proxy for handle https with issue certificates in fly from lets-encrypt. ![stars](https://img.shields.io/badge/stars-96-blue)
- [minio](https://github.com/minio/minio) - Minio is a distributed object storage server. ![stars](https://img.shields.io/badge/stars-49430-blue)
- [Moxy](https://github.com/sinhashubham95/moxy) - Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint. ![stars](https://img.shields.io/badge/stars-15-blue)
- [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) - Nginx log parser and exporter to Prometheus. ![stars](https://img.shields.io/badge/stars-40-blue)
- [nsq](https://nsq.io/) - A realtime distributed messaging platform.
- [pocketbase](https://github.com/pocketbase/pocketbase) - PocketBase is a realtime backend in 1 file consisting of embedded database (SQLite) with realtime subscriptions, built-in auth management and much more. ![stars](https://img.shields.io/badge/stars-42834-blue)
- [protoxy](https://github.com/camgraff/protoxy) - A proxy server that converts JSON request bodies to Protocol Buffers. ![stars](https://img.shields.io/badge/stars-35-blue)
- [psql-streamer](https://github.com/blind-oracle/psql-streamer) - Stream database events from PostgreSQL to Kafka. ![stars](https://img.shields.io/badge/stars-58-blue)
- [riemann-relay](https://github.com/blind-oracle/riemann-relay) - Relay to load-balance Riemann events and/or convert them to Carbon. ![stars](https://img.shields.io/badge/stars-2-blue)
- [RoadRunner](https://github.com/spiral/roadrunner) - High-performance PHP application server, load-balancer and process manager. ![stars](https://img.shields.io/badge/stars-7999-blue)
- [SFTPGo](https://github.com/drakkan/sftpgo) - Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage. ![stars](https://img.shields.io/badge/stars-9793-blue)
- [Trickster](https://github.com/tricksterproxy/trickster) - HTTP reverse proxy cache and time series accelerator. ![stars](https://img.shields.io/badge/stars-2004-blue)
- [wd-41](https://github.com/baalimago/wd-41) - A (w)eb (d)evelopment server with automatic live-reload on file changes. ![stars](https://img.shields.io/badge/stars-146-blue)
- [Wish](https://github.com/charmbracelet/wish) - Make SSH apps, just like that! ![stars](https://img.shields.io/badge/stars-3821-blue)

**[⬆ back to top](#contents)**

## Stream Processing

_Libraries and tools for stream processing and reactive programming._

- [go-streams](https://github.com/reugn/go-streams) - Go stream processing library. ![stars](https://img.shields.io/badge/stars-1960-blue)
- [goio](https://github.com/primetalk/goio) - An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2. ![stars](https://img.shields.io/badge/stars-83-blue)
- [machine](https://github.com/whitaker-io/machine) - Go library for writing and generating stream workers with built in metrics and traceability. ![stars](https://img.shields.io/badge/stars-158-blue)
- [stream](https://github.com/youthlin/stream) - Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce... ![stars](https://img.shields.io/badge/stars-91-blue)

**[⬆ back to top](#contents)**

## Template Engines

_Libraries and tools for templating and lexing._

- [ego](https://github.com/benbjohnson/ego) - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled. ![stars](https://img.shields.io/badge/stars-581-blue)
- [extemplate](https://github.com/dannyvankooten/extemplate) - Tiny wrapper around html/template to allow for easy file-based template inheritance. ![stars](https://img.shields.io/badge/stars-58-blue)
- [fasttemplate](https://github.com/valyala/fasttemplate) - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/). ![stars](https://img.shields.io/badge/stars-854-blue)
- [gomponents](https://www.gomponents.com) - HTML 5 components in pure Go, that look something like this: `func(name string) g.Node { return Div(Class("headline"), g.Textf("Hi %v!", name)) }`.
- [got](https://github.com/goradd/got) - A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more. ![stars](https://img.shields.io/badge/stars-32-blue)
- [goview](https://github.com/foolin/goview) - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application. ![stars](https://img.shields.io/badge/stars-429-blue)
- [htmgo](https://htmgo.dev) - build simple and scalable systems with go + htmx
- [jet](https://github.com/CloudyKit/jet) - Jet template engine. ![stars](https://img.shields.io/badge/stars-1281-blue)
- [liquid](https://github.com/osteele/liquid) - Go implementation of Shopify Liquid templates. ![stars](https://img.shields.io/badge/stars-294-blue)
- [maroto](https://github.com/johnfercher/maroto) - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple. ![stars](https://img.shields.io/badge/stars-2297-blue)
- [pongo2](https://github.com/flosch/pongo2) - Django-like template-engine for Go. ![stars](https://img.shields.io/badge/stars-2907-blue)
- [quicktemplate](https://github.com/valyala/quicktemplate) - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it. ![stars](https://img.shields.io/badge/stars-3157-blue)
- [raymond](https://github.com/aymerick/raymond) - Complete handlebars implementation in Go. ![stars](https://img.shields.io/badge/stars-613-blue)
- [Razor](https://github.com/sipin/gorazor) - Razor view engine for Golang. ![stars](https://img.shields.io/badge/stars-860-blue)
- [Soy](https://github.com/robfig/soy) - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/). ![stars](https://img.shields.io/badge/stars-172-blue)
- [sprout](https://github.com/go-sprout/sprout) - Useful template functions for Go templates. ![stars](https://img.shields.io/badge/stars-103-blue)
- [tbd](https://github.com/lucasepe/tbd) - A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata. ![stars](https://img.shields.io/badge/stars-25-blue)
- [templ](https://github.com/a-h/templ) - A HTML templating language that has great developer tooling. ![stars](https://img.shields.io/badge/stars-8698-blue)

**[⬆ back to top](#contents)**

## Testing

_Libraries for testing codebases and generating test data._

### Testing Frameworks

- [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
- [arch-go](https://github.com/fdaines/arch-go) - Architecture testing tool for Go projects. ![stars](https://img.shields.io/badge/stars-1-blue)
- [assert](https://github.com/go-playground/assert) - Basic Assertion Library used along side native go testing, with building blocks for custom assertions. ![stars](https://img.shields.io/badge/stars-63-blue)
- [baloo](https://github.com/h2non/baloo) - Expressive and versatile end-to-end HTTP API testing made easy. ![stars](https://img.shields.io/badge/stars-777-blue)
- [be](https://github.com/carlmjohnson/be) - The minimalist generic test assertion library. ![stars](https://img.shields.io/badge/stars-103-blue)
- [biff](https://github.com/fulldump/biff) - Bifurcation testing framework, BDD compatible. ![stars](https://img.shields.io/badge/stars-14-blue)
- [charlatan](https://github.com/percolate/charlatan) - Tool to generate fake interface implementations for tests. ![stars](https://img.shields.io/badge/stars-203-blue)
- [commander](https://github.com/SimonBaeumer/commander) - Tool for testing cli applications on windows, linux and osx. ![stars](https://img.shields.io/badge/stars-226-blue)
- [cupaloy](https://github.com/bradleyjkemp/cupaloy) - Simple snapshot testing addon for your test framework. ![stars](https://img.shields.io/badge/stars-313-blue)
- [dbcleaner](https://github.com/khaiql/dbcleaner) - Clean database for testing purpose, inspired by `database_cleaner` in Ruby. ![stars](https://img.shields.io/badge/stars-161-blue)
- [dft](https://github.com/abecodes/dft) - Lightweight, zero dependency docker containers for testing (or more). ![stars](https://img.shields.io/badge/stars-15-blue)
- [dsunit](https://github.com/viant/dsunit) - Datastore testing for SQL, NoSQL, structured files. ![stars](https://img.shields.io/badge/stars-45-blue)
- [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test. ![stars](https://img.shields.io/badge/stars-891-blue)
- [endly](https://github.com/viant/endly) - Declarative end to end functional testing. ![stars](https://img.shields.io/badge/stars-265-blue)
- [envite](https://github.com/PerimeterX/envite) - Dev and testing environment management framework. ![stars](https://img.shields.io/badge/stars-5-blue)
- [fixenv](https://github.com/rekby/fixenv) - Fixture manage engine, inspired by pytest fixtures. ![stars](https://img.shields.io/badge/stars-30-blue)
- [fluentassert](https://github.com/fluentassert/verify) - Extensible, type-safe, fluent assertion Go library. ![stars](https://img.shields.io/badge/stars-46-blue)
- [flute](https://github.com/suzuki-shunsuke/flute) - HTTP client testing framework. ![stars](https://img.shields.io/badge/stars-21-blue)
- [frisby](https://github.com/verdverm/frisby) - REST API testing framework. ![stars](https://img.shields.io/badge/stars-278-blue)
- [gherkingen](https://github.com/hedhyw/gherkingen) - BDD boilerplate generator and framework. ![stars](https://img.shields.io/badge/stars-80-blue)
- [ginkgo](https://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
- [gnomock](https://github.com/orlangure/gnomock) - integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks. ![stars](https://img.shields.io/badge/stars-1414-blue)
- [go-carpet](https://github.com/msoap/go-carpet) - Tool for viewing test coverage in terminal. ![stars](https://img.shields.io/badge/stars-246-blue)
- [go-cmp](https://github.com/google/go-cmp) - Package for comparing Go values in tests. ![stars](https://img.shields.io/badge/stars-4277-blue)
- [go-hit](https://github.com/Eun/go-hit) - Hit is an http integration test framework written in golang. ![stars](https://img.shields.io/badge/stars-256-blue)
- [go-mutesting](https://github.com/zimmski/go-mutesting) - Mutation testing for Go source code. ![stars](https://img.shields.io/badge/stars-652-blue)
- [go-mysql-test-container](https://github.com/arikama/go-mysql-test-container) - Golang MySQL testcontainer to help with MySQL integration testing. ![stars](https://img.shields.io/badge/stars-3-blue)
- [go-snaps](http://github.com/gkampitakis/go-snaps) - Jest-like snapshot testing in Golang.
- [go-testdeep](https://github.com/maxatome/go-testdeep) - Extremely flexible golang deep comparison, extends the go testing package. ![stars](https://img.shields.io/badge/stars-438-blue)
- [go-testpredicate](https://github.com/maargenton/go-testpredicate) - Test predicate style assertions library with extensive diagnostics output. ![stars](https://img.shields.io/badge/stars-5-blue)
- [go-vcr](https://github.com/dnaeon/go-vcr) - Record and replay your HTTP interactions for fast, deterministic and accurate tests. ![stars](https://img.shields.io/badge/stars-1264-blue)
- [goblin](https://github.com/franela/goblin) - Mocha like testing framework of Go. ![stars](https://img.shields.io/badge/stars-888-blue)
- [goc](https://github.com/qiniu/goc) - Goc is a comprehensive coverage testing system for The Go Programming Language. ![stars](https://img.shields.io/badge/stars-835-blue)
- [gocheck](https://labix.org/gocheck) - More advanced testing framework alternative to gotest.
- [GoConvey](https://github.com/smartystreets/goconvey/) - BDD-style framework with web UI and live reload. ![stars](https://img.shields.io/badge/stars-8294-blue)
- [gocrest](https://github.com/corbym/gocrest) - Composable hamcrest-like matchers for Go assertions. ![stars](https://img.shields.io/badge/stars-106-blue)
- [godog](https://github.com/cucumber/godog) - Cucumber BDD framework for Go. ![stars](https://img.shields.io/badge/stars-2354-blue)
- [gofight](https://github.com/appleboy/gofight) - API Handler Testing for Golang Router framework. ![stars](https://img.shields.io/badge/stars-442-blue)
- [gogiven](https://github.com/corbym/gogiven) - YATSPEC-like BDD testing framework for Go. ![stars](https://img.shields.io/badge/stars-15-blue)
- [gomatch](https://github.com/jfilipczyk/gomatch) - library created for testing JSON against patterns. ![stars](https://img.shields.io/badge/stars-47-blue)
- [gomega](https://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
- [Gont](https://github.com/stv0g/gont) - Go network testing toolkit for testing building complex network topologies using Linux namespaces. ![stars](https://img.shields.io/badge/stars-79-blue)
- [gospecify](https://github.com/stesla/gospecify) - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec. ![stars](https://img.shields.io/badge/stars-52-blue)
- [gosuite](https://github.com/pavlo/gosuite) - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests. ![stars](https://img.shields.io/badge/stars-12-blue)
- [got](https://github.com/ysmood/got) - An enjoyable golang test framework. ![stars](https://img.shields.io/badge/stars-265-blue)
- [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns. ![stars](https://img.shields.io/badge/stars-525-blue)
- [Hamcrest](https://github.com/rdrdr/hamcrest) - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results. ![stars](https://img.shields.io/badge/stars-30-blue)
- [httpexpect](https://github.com/gavv/httpexpect) - Concise, declarative, and easy to use end-to-end HTTP and REST API testing. ![stars](https://img.shields.io/badge/stars-2580-blue)
- [is](https://github.com/matryer/is) - Professional lightweight testing mini-framework for Go. ![stars](https://img.shields.io/badge/stars-1831-blue)
- [jsonassert](https://github.com/kinbiko/jsonassert) - Package for verifying that your JSON payloads are serialized correctly. ![stars](https://img.shields.io/badge/stars-128-blue)
- [keploy](https://github.com/keploy/keploy) - Generate Testcase and Data Mocks from API calls automatically. ![stars](https://img.shields.io/badge/stars-5244-blue)
- [omg.testingtools](https://github.com/dedalqq/omg.testingtools) - The simple library for change a values of private fields for testing. ![stars](https://img.shields.io/badge/stars-1-blue)
- [restit](https://github.com/yookoala/restit) - Go micro framework to help writing RESTful API integration test. ![stars](https://img.shields.io/badge/stars-55-blue)
- [schema](https://github.com/jgroeneveld/schema) - Quick and easy expression matching for JSON schemas used in requests and responses. ![stars](https://img.shields.io/badge/stars-20-blue)
- [stop-and-go](https://github.com/elgohr/stop-and-go) - Testing helper for concurrency. ![stars](https://img.shields.io/badge/stars-11-blue)
- [testcase](https://github.com/adamluzsi/testcase) - Idiomatic testing framework for Behavior Driven Development. ![stars](https://img.shields.io/badge/stars-122-blue)
- [testcerts](https://github.com/madflojo/testcerts) - Dynamically generate self-signed certificates and certificate authorities within your test functions. ![stars](https://img.shields.io/badge/stars-70-blue)
- [testcontainers-go](https://github.com/testcontainers/testcontainers-go) - A Go package that makes it simple to create and clean up container-based dependencies for automated integration/smoke tests. The clean, easy-to-use API enables developers to programmatically define containers that should be run as part of a test and clean up those resources when the test is done. ![stars](https://img.shields.io/badge/stars-3775-blue)
- [testfixtures](https://github.com/go-testfixtures/testfixtures) - A helper for Rails' like test fixtures to test database applications. ![stars](https://img.shields.io/badge/stars-1130-blue)
- [Testify](https://github.com/stretchr/testify) - Sacred extension to the standard go testing package. ![stars](https://img.shields.io/badge/stars-23821-blue)
- [testsql](https://github.com/zhulongcheng/testsql) - Generate test data from SQL files before testing and clear it after finished. ![stars](https://img.shields.io/badge/stars-17-blue)
- [testza](https://github.com/MarvinJWendt/testza) - Full-featured test framework with nice colorized output. ![stars](https://img.shields.io/badge/stars-419-blue)
- [trial](https://github.com/jgroeneveld/trial) - Quick and easy extendable assertions without introducing much boilerplate. ![stars](https://img.shields.io/badge/stars-6-blue)
- [Tt](https://github.com/vcaesar/tt) - Simple and colorful test tools. ![stars](https://img.shields.io/badge/stars-8-blue)
- [wstest](https://github.com/posener/wstest) - Websocket client for unit-testing a websocket http.Handler. ![stars](https://img.shields.io/badge/stars-102-blue)

### Mock

- [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) - Tool for generating self-contained mock objects. ![stars](https://img.shields.io/badge/stars-1018-blue)
- [genmock](https://gitlab.com/so_literate/genmock) - Go mocking system with code generator for building calls of the interface methods.
- [go-localstack](https://github.com/elgohr/go-localstack) - Tool for using localstack in AWS testing. ![stars](https://img.shields.io/badge/stars-80-blue)
- [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) - Mock SQL driver for testing database interactions. ![stars](https://img.shields.io/badge/stars-6215-blue)
- [go-txdb](https://github.com/DATA-DOG/go-txdb) - Single transaction based database driver mainly for testing purposes. ![stars](https://img.shields.io/badge/stars-682-blue)
- [gock](https://github.com/h2non/gock) - Versatile HTTP mocking made easy. ![stars](https://img.shields.io/badge/stars-2123-blue)
- [gomock](https://github.com/golang/mock) - Mocking framework for the Go programming language. ![stars](https://img.shields.io/badge/stars-9342-blue)
- [govcr](https://github.com/seborama/govcr) - HTTP mock for Golang: record and replay HTTP interactions for offline testing. ![stars](https://img.shields.io/badge/stars-179-blue)
- [hoverfly](https://github.com/SpectoLabs/hoverfly) - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI. ![stars](https://img.shields.io/badge/stars-2375-blue)
- [httpmock](https://github.com/jarcoal/httpmock) - Easy mocking of HTTP responses from external resources. ![stars](https://img.shields.io/badge/stars-1963-blue)
- [minimock](https://github.com/gojuno/minimock) - Mock generator for Go interfaces. ![stars](https://img.shields.io/badge/stars-656-blue)
- [mockery](https://github.com/vektra/mockery) - Tool to generate Go interfaces. ![stars](https://img.shields.io/badge/stars-6269-blue)
- [mockhttp](https://github.com/tv42/mockhttp) - Mock object for Go http.ResponseWriter. ![stars](https://img.shields.io/badge/stars-23-blue)
- [mooncake](https://github.com/GuilhermeCaruso/mooncake) - A simple way to generate mocks for multiple purposes. ![stars](https://img.shields.io/badge/stars-18-blue)
- [moq](https://github.com/matryer/moq) - Utility that generates a struct from any interface. The struct can be used in test code as a mock of the interface. ![stars](https://img.shields.io/badge/stars-2022-blue)
- [pgxmock](https://github.com/pashagolub/pgxmock) - A mock library implementing [pgx - PostgreSQL Driver and Toolkit](https://github.com/jackc/pgx/). ![stars](https://img.shields.io/badge/stars-404-blue)
- [timex](https://github.com/cabify/timex) - A test-friendly replacement for the native `time` package. ![stars](https://img.shields.io/badge/stars-71-blue)
- [xgo](https://github.com/xhd2015/xgo) - A general pureposed function mocking library. ![stars](https://img.shields.io/badge/stars-377-blue)

### Fuzzing and delta-debugging/reducing/shrinking

- [go-fuzz](https://github.com/dvyukov/go-fuzz) - Randomized testing system. ![stars](https://img.shields.io/badge/stars-4800-blue)
- [gofuzz](https://github.com/google/gofuzz) - Library for populating go objects with random values. ![stars](https://img.shields.io/badge/stars-1493-blue)
- [Tavor](https://github.com/zimmski/tavor) - Generic fuzzing and delta-debugging framework. ![stars](https://img.shields.io/badge/stars-245-blue)

### Selenium and browser control tools

- [cdp](https://github.com/mafredri/cdp) - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it. ![stars](https://img.shields.io/badge/stars-736-blue)
- [chromedp](https://github.com/knq/chromedp) - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol. ![stars](https://img.shields.io/badge/stars-11279-blue)
- [ggr](https://github.com/aerokube/ggr) - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs. ![stars](https://img.shields.io/badge/stars-314-blue)
- [playwright-go](https://github.com/mxschmitt/playwright-go) - browser automation library to control Chromium, Firefox and WebKit with a single API. ![stars](https://img.shields.io/badge/stars-2344-blue)
- [rod](https://github.com/go-rod/rod) - A Devtools driver to make web automation and scraping easy. ![stars](https://img.shields.io/badge/stars-5597-blue)
- [selenoid](https://github.com/aerokube/selenoid) - alternative Selenium hub server that launches browsers within containers. ![stars](https://img.shields.io/badge/stars-2617-blue)

### Fail injection
- [failpoint](https://github.com/pingcap/failpoint) - An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang. ![stars](https://img.shields.io/badge/stars-832-blue)

**[⬆ back to top](#contents)**

## Text Processing

_Libraries for parsing and manipulating texts._

See also [Natural Language Processing](#natural-language-processing) and [Text Analysis](#text-analysis).

### Formatters

- [address](https://github.com/bojanz/address) - Handles address representation, validation and formatting. ![stars](https://img.shields.io/badge/stars-74-blue)
- [align](https://github.com/Guitarbum722/align) - A general purpose application that aligns text. ![stars](https://img.shields.io/badge/stars-84-blue)
- [bytes](https://github.com/labstack/gommon/tree/master/bytes) - Formats and parses numeric byte values (10K, 2M, 3G, etc.). ![stars](https://img.shields.io/badge/stars-547-blue)
- [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) - Fixed-width text formatting (encoder/decoder with reflection). ![stars](https://img.shields.io/badge/stars-82-blue)
- [go-humanize](https://github.com/dustin/go-humanize) - Formatters for time, numbers, and memory size to human readable format. ![stars](https://img.shields.io/badge/stars-4414-blue)
- [gotabulate](https://github.com/bndr/gotabulate) - Easily pretty-print your tabular data with Go. ![stars](https://img.shields.io/badge/stars-334-blue)
- [sq](https://github.com/neilotoole/sq) - Convert data from SQL databases or document formats like CSV or Excel into formats such as JSON, Excel, CSV, HTML, Markdown, XML, and YAML. ![stars](https://img.shields.io/badge/stars-2196-blue)
- [textwrap](https://github.com/isbm/textwrap) - Wraps text at end of lines. Implementation of `textwrap` module from Python. ![stars](https://img.shields.io/badge/stars-5-blue)

### Markup Languages

- [bafi](https://github.com/mmalcek/bafi) - Universal JSON, BSON, YAML, XML translator to ANY format using templates. ![stars](https://img.shields.io/badge/stars-106-blue)
- [bbConvert](https://github.com/CalebQ42/bbConvert) - Converts bbCode to HTML that allows you to add support for custom bbCode tags. ![stars](https://img.shields.io/badge/stars-12-blue)
- [blackfriday](https://github.com/russross/blackfriday) - Markdown processor in Go. ![stars](https://img.shields.io/badge/stars-5489-blue)
- [go-output-format](https://github.com/drewstinnett/go-output-format) - Output go structures into multiple formats (YAML/JSON/etc) in your command line app. ![stars](https://img.shields.io/badge/stars-17-blue)
- [go-toml](https://github.com/pelletier/go-toml) - Go library for the TOML format with query support and handy cli tools. ![stars](https://img.shields.io/badge/stars-1759-blue)
- [goldmark](https://github.com/yuin/goldmark) - A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured. ![stars](https://img.shields.io/badge/stars-3812-blue)
- [goq](https://github.com/andrewstuart/goq) - Declarative unmarshalling of HTML using struct tags with jQuery syntax (uses GoQuery). ![stars](https://img.shields.io/badge/stars-262-blue)
- [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) - Convert HTML to Markdown. Even works with entire websites and can be extended through rules. ![stars](https://img.shields.io/badge/stars-2516-blue)
- [htmlquery](https://github.com/antchfx/htmlquery) - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression. ![stars](https://img.shields.io/badge/stars-753-blue)
- [htmlyaml](https://github.com/nikolaydubina/htmlyaml) -  Rich rendering of YAML as HTML in Go ![stars](https://img.shields.io/badge/stars-5-blue)
- [htree](https://github.com/bobg/htree) - Traverse, navigate, filter, and otherwise process trees of [html.Node](https://pkg.go.dev/golang.org/x/net/html#Node) objects. ![stars](https://img.shields.io/badge/stars-4-blue)
- [mxj](https://github.com/clbanning/mxj) - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages. ![stars](https://img.shields.io/badge/stars-624-blue)
- [toml](https://github.com/BurntSushi/toml) - TOML configuration format (encoder/decoder with reflection). ![stars](https://img.shields.io/badge/stars-4619-blue)

### Parsers/Encoders/Decoders

- [allot](https://github.com/sbstjn/allot) - Placeholder and wildcard text parsing for CLI tools and bots. ![stars](https://img.shields.io/badge/stars-59-blue)
- [codetree](https://github.com/aerogo/codetree) - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure. ![stars](https://img.shields.io/badge/stars-24-blue)
- [commonregex](https://github.com/mingrammer/commonregex) - A collection of common regular expressions for Go. ![stars](https://img.shields.io/badge/stars-896-blue)
- [did](https://github.com/ockam-network/did) - DID (Decentralized Identifiers) Parser and Stringer in Go. ![stars](https://img.shields.io/badge/stars-91-blue)
- [doi](https://github.com/hscells/doi) - Document object identifier (doi) parser in Go. ![stars](https://img.shields.io/badge/stars-10-blue)
- [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) - Editorconfig file parser and manipulator for Go. ![stars](https://img.shields.io/badge/stars-144-blue)
- [encdec](https://github.com/mickep76/encdec) - Package provides a generic interface to encoders and decoders. ![stars](https://img.shields.io/badge/stars-9-blue)
- [go-fasttld](https://github.com/elliotwutingfeng/go-fasttld) - High performance effective top level domains (eTLD) extraction module. ![stars](https://img.shields.io/badge/stars-33-blue)
- [go-nmea](https://github.com/adrianmo/go-nmea) - NMEA parser library for the Go language. ![stars](https://img.shields.io/badge/stars-229-blue)
- [go-querystring](https://github.com/google/go-querystring) - Go library for encoding structs into URL query parameters. ![stars](https://img.shields.io/badge/stars-2017-blue)
- [go-vcard](https://github.com/emersion/go-vcard) - Parse and format vCard. ![stars](https://img.shields.io/badge/stars-110-blue)
- [godump](https://github.com/yassinebenaid/godump) - Pretty print any GO variable with ease, an alternative to Go's `fmt.Printf("%#v")`. ![stars](https://img.shields.io/badge/stars-178-blue)
- [gofeed](https://github.com/mmcdole/gofeed) - Parse RSS and Atom feeds in Go. ![stars](https://img.shields.io/badge/stars-2623-blue)
- [gographviz](https://github.com/awalterschulze/gographviz) - Parses the Graphviz DOT language. ![stars](https://img.shields.io/badge/stars-555-blue)
- [gonameparts](https://github.com/polera/gonameparts) - Parses human names into individual name parts. ![stars](https://img.shields.io/badge/stars-42-blue)
- [ltsv](https://github.com/Wing924/ltsv) - High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go. ![stars](https://img.shields.io/badge/stars-9-blue)
- [normalize](https://github.com/avito-tech/normalize) - Sanitize, normalize and compare fuzzy text. ![stars](https://img.shields.io/badge/stars-46-blue)
- [parseargs-go](https://github.com/nproc/parseargs-go) - string argument parser that understands quotes and backslashes. ![stars](https://img.shields.io/badge/stars-10-blue)
- [parth](https://github.com/codemodus/parth) - URL path segmentation parsing.
- [prattle](https://github.com/askeladdk/prattle) - Scan and parse LL(1) grammars simply and efficiently. ![stars](https://img.shields.io/badge/stars-7-blue)
- [sdp](https://github.com/gortc/sdp) - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)]. ![stars](https://img.shields.io/badge/stars-113-blue)
- [sh](https://github.com/mvdan/sh) - Shell parser and formatter. ![stars](https://img.shields.io/badge/stars-7435-blue)
- [tokenizer](https://github.com/bzick/tokenizer) - Parse any string, slice or infinite buffer to any tokens. ![stars](https://img.shields.io/badge/stars-107-blue)
- [vdf](https://github.com/andygrunwald/vdf) - A Lexer and Parser for Valves Data Format (known as vdf) written in Go. ![stars](https://img.shields.io/badge/stars-45-blue)
- [when](https://github.com/olebedev/when) - Natural EN and RU language date/time parser with pluggable rules. ![stars](https://img.shields.io/badge/stars-1421-blue)
- [xj2go](https://github.com/stackerzzq/xj2go) - Convert xml or json to go struct. ![stars](https://img.shields.io/badge/stars-34-blue)

### Regular Expressions

- [genex](https://github.com/alixaxel/genex) - Count and expand Regular Expressions into all matching Strings. ![stars](https://img.shields.io/badge/stars-77-blue)
- [go-wildcard](https://github.com/IGLOU-EU/go-wildcard) - Simple and lightweight wildcard pattern matching. ![stars](https://img.shields.io/badge/stars-83-blue)
- [goregen](https://github.com/zach-klippenstein/goregen) - Library for generating random strings from regular expressions. ![stars](https://img.shields.io/badge/stars-91-blue)
- [regroup](https://github.com/oriser/regroup) - Match regex expression named groups into go struct using struct tags and automatic parsing. ![stars](https://img.shields.io/badge/stars-147-blue)
- [rex](https://github.com/hedhyw/rex) - Regular expressions builder. ![stars](https://img.shields.io/badge/stars-199-blue)

### Sanitation

- [bluemonday](https://github.com/microcosm-cc/bluemonday) - HTML Sanitizer. ![stars](https://img.shields.io/badge/stars-3262-blue)
- [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) - A sanitization-based swear filter for Go. ![stars](https://img.shields.io/badge/stars-67-blue)

### Scrapers

- [colly](https://github.com/asciimoo/colly) - Fast and Elegant Scraping Framework for Gophers. ![stars](https://img.shields.io/badge/stars-23576-blue)
- [dataflowkit](https://github.com/slotix/dataflowkit) - Web scraping Framework to turn websites into structured data. ![stars](https://img.shields.io/badge/stars-671-blue)
- [go-recipe](https://github.com/kkyr/go-recipe) - A package for scraping recipes from websites. ![stars](https://img.shields.io/badge/stars-28-blue)
- [GoQuery](https://github.com/PuerkitoBio/goquery) - GoQuery brings a syntax and a set of features similar to jQuery to the Go language. ![stars](https://img.shields.io/badge/stars-14193-blue)
- [pagser](https://github.com/foolin/pagser) - Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler. ![stars](https://img.shields.io/badge/stars-105-blue)
- [Tagify](https://github.com/zoomio/tagify) - Produces a set of tags from given source. ![stars](https://img.shields.io/badge/stars-38-blue)
- [walker](https://github.com/cyucelen/walker) - Seamlessly fetch paginated data from any source. Simple and high performance API scraping included. ![stars](https://img.shields.io/badge/stars-11-blue)
- [xurls](https://github.com/mvdan/xurls) - Extract urls from text. ![stars](https://img.shields.io/badge/stars-1201-blue)

### RSS

- [podcast](https://github.com/eduncan911/podcast) - iTunes Compliant and RSS 2.0 Podcast Generator in Golang ![stars](https://img.shields.io/badge/stars-134-blue)

### Utility/Miscellaneous

- [go-runewidth](https://github.com/mattn/go-runewidth) - Functions to get fixed width of the character or string. ![stars](https://img.shields.io/badge/stars-619-blue)
- [go-zero-width](https://github.com/trubitsyn/go-zero-width) - Zero-width character detection and removal for Go. ![stars](https://img.shields.io/badge/stars-110-blue)
- [kace](https://github.com/codemodus/kace) - Common case conversions covering common initialisms. ![stars](https://img.shields.io/badge/stars-20-blue)
- [petrovich](https://github.com/striker2000/petrovich) - Petrovich is the library which inflects Russian names to given grammatical case. ![stars](https://img.shields.io/badge/stars-48-blue)
- [radix](https://github.com/yourbasic/radix) - Fast string sorting algorithm. ![stars](https://img.shields.io/badge/stars-192-blue)
- [TySug](https://github.com/Dynom/TySug) - Alternative suggestions with respect to keyboard layouts. ![stars](https://img.shields.io/badge/stars-18-blue)
- [w2vgrep](https://github.com/arunsupe/semantic-grep) - A semantic grep tool using word embeddings to find semantically similar matches. For example, searching for "death" will find "dead", "killing", "murder". ![stars](https://img.shields.io/badge/stars-1129-blue)

**[⬆ back to top](#contents)**

## Third-party APIs

_Libraries for accessing third party APIs._

- [airtable](https://github.com/mehanizm/airtable) - Go client library for the [Airtable API](https://airtable.com/api). ![stars](https://img.shields.io/badge/stars-77-blue)
- [anaconda](https://github.com/ChimeraCoder/anaconda) - Go client library for the Twitter 1.1 API. ![stars](https://img.shields.io/badge/stars-1145-blue)
- [appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) - Unofficial Golang SDK for AppStore Connect API. ![stars](https://img.shields.io/badge/stars-5-blue)
- [aws-encryption-sdk-go](https://github.com/chainifynet/aws-encryption-sdk-go) - Unofficial Go SDK implementation of the [AWS Encryption SDK](https://docs.aws.amazon.com/encryption-sdk/latest/developer-guide/index.html). ![stars](https://img.shields.io/badge/stars-21-blue)
- [aws-sdk-go](https://github.com/aws/aws-sdk-go-v2) - The official AWS SDK for the Go programming language. ![stars](https://img.shields.io/badge/stars-2763-blue)
- [bqwriter](https://github.com/OTA-Insight/bqwriter) - High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout. ![stars](https://img.shields.io/badge/stars-16-blue)
- [brewerydb](https://github.com/naegelejd/brewerydb) - Go library for accessing the BreweryDB API. ![stars](https://img.shields.io/badge/stars-19-blue)
- [cachet](https://github.com/andygrunwald/cachet) - Go client library for [Cachet (open source status page system)](https://cachethq.io/). ![stars](https://img.shields.io/badge/stars-91-blue)
- [circleci](https://github.com/jszwedko/go-circleci) - Go client library for interacting with CircleCI's API. ![stars](https://img.shields.io/badge/stars-65-blue)
- [clarifai](https://github.com/samuelcouch/clarifai) - Go client library for interfacing with the Clarifai API. ![stars](https://img.shields.io/badge/stars-55-blue)
- [codeship-go](https://github.com/codeship/codeship-go) - Go client library for interacting with Codeship's API v2. ![stars](https://img.shields.io/badge/stars-18-blue)
- [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) - Go client library for interacting with Coinpaprika's API. ![stars](https://img.shields.io/badge/stars-25-blue)
- [device-check-go](https://github.com/rinchsan/device-check-go) - Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1. ![stars](https://img.shields.io/badge/stars-24-blue)
- [discordgo](https://github.com/bwmarrin/discordgo) - Go bindings for the Discord Chat API. ![stars](https://img.shields.io/badge/stars-5189-blue)
- [disgo](https://github.com/switchupcb/disgo) - Go API Wrapper for the Discord API. ![stars](https://img.shields.io/badge/stars-91-blue)
- [dusupay-sdk-go](https://github.com/Kachit/dusupay-sdk-go) - Unofficial Dusupay payment gateway API Client for Go ![stars](https://img.shields.io/badge/stars-3-blue)
- [ethrpc](https://github.com/onrik/ethrpc) - Go bindings for Ethereum JSON RPC API. ![stars](https://img.shields.io/badge/stars-269-blue)
- [facebook](https://github.com/huandu/facebook) - Go Library that supports the Facebook Graph API. ![stars](https://img.shields.io/badge/stars-1344-blue)
- [fasapay-sdk-go](https://github.com/Kachit/fasapay-sdk-go) - Unofficial Fasapay payment gateway XML API Client for Golang. ![stars](https://img.shields.io/badge/stars-2-blue)
- [fcm](https://github.com/maddevsio/fcm) - Go library for Firebase Cloud Messaging. ![stars](https://img.shields.io/badge/stars-51-blue)
- [gads](https://github.com/emiddleton/gads) - Google Adwords Unofficial API. ![stars](https://img.shields.io/badge/stars-51-blue)
- [gami](https://github.com/bit4bit/gami) - Go library for Asterisk Manager Interface. ![stars](https://img.shields.io/badge/stars-33-blue)
- [gcm](https://github.com/Aorioli/gcm) - Go library for Google Cloud Messaging. ![stars](https://img.shields.io/badge/stars-31-blue)
- [geo-golang](https://github.com/codingsince1985/geo-golang) - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://developer.mapquest.com/documentation/api/geocoding/), [Nominatim](https://nominatim.org/release-docs/latest/api/Overview/), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs. ![stars](https://img.shields.io/badge/stars-518-blue)
- [github](https://github.com/google/go-github) - Go library for accessing the GitHub REST API v3. ![stars](https://img.shields.io/badge/stars-10570-blue)
- [githubql](https://github.com/shurcooL/githubql) - Go library for accessing the GitHub GraphQL API v4. ![stars](https://img.shields.io/badge/stars-1134-blue)
- [go-atlassian](https://github.com/ctreminiom/go-atlassian) - Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud) ![stars](https://img.shields.io/badge/stars-135-blue)
- [go-aws-news](https://github.com/circa10a/go-aws-news) - Go application and library to fetch what's new from AWS. ![stars](https://img.shields.io/badge/stars-17-blue)
- [go-chronos](https://github.com/axelspringer/go-chronos) - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler ![stars](https://img.shields.io/badge/stars-8-blue)
- [go-gerrit](https://github.com/andygrunwald/go-gerrit) - Go cient library for [Gerrit Code Review](https://www.gerritcodereview.com/). ![stars](https://img.shields.io/badge/stars-97-blue)
- [go-hacknews](https://github.com/PaulRosset/go-hacknews) - Tiny Go client for HackerNews API. ![stars](https://img.shields.io/badge/stars-17-blue)
- [go-here](https://github.com/abdullahselek/go-here) - Go client library around the HERE location based APIs. ![stars](https://img.shields.io/badge/stars-13-blue)
- [go-hibp](https://github.com/wneessen/go-hibp) - Simple Go binding to the "Have I Been Pwned" APIs. ![stars](https://img.shields.io/badge/stars-6-blue)
- [go-imgur](https://github.com/koffeinsource/go-imgur) - Go client library for [imgur](https://imgur.com) ![stars](https://img.shields.io/badge/stars-24-blue)
- [go-jira](https://github.com/andygrunwald/go-jira) - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira) ![stars](https://img.shields.io/badge/stars-1495-blue)
- [go-lark](https://github.com/go-lark/lark) - An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform. ![stars](https://img.shields.io/badge/stars-210-blue)
- [go-marathon](https://github.com/gambol99/go-marathon) - Go library for interacting with Mesosphere's Marathon PAAS. ![stars](https://img.shields.io/badge/stars-199-blue)
- [go-myanimelist](https://github.com/nstratos/go-myanimelist) - Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2). ![stars](https://img.shields.io/badge/stars-39-blue)
- [go-openai](https://github.com/sashabaranov/go-openai) - OpenAI ChatGPT, DALL·E, Whisper API library for Go. ![stars](https://img.shields.io/badge/stars-9442-blue)
- [go-openproject](https://github.com/manuelbcd/go-openproject) - Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API. ![stars](https://img.shields.io/badge/stars-17-blue)
- [go-postman-collection](https://github.com/rbretecher/go-postman-collection) - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia). ![stars](https://img.shields.io/badge/stars-82-blue)
- [go-redoc](https://github.com/mvrilo/go-redoc) - Embedded OpenAPI/Swagger documentation ui for Go using [ReDoc](https://redocly.com/). ![stars](https://img.shields.io/badge/stars-79-blue)
- [go-restcountries](https://github.com/chriscross0/go-restcountries) - Go library for the [REST Countries API](https://countrylayer.com/). ![stars](https://img.shields.io/badge/stars-3-blue)
- [go-salesforce](https://github.com/k-capehart/go-salesforce) - Go client library for interacting with the [Salesforce REST API](https://developer.salesforce.com/docs/atlas.en-us.api_rest.meta/api_rest/resources_list.htm). ![stars](https://img.shields.io/badge/stars-33-blue)
- [go-sophos](https://github.com/esurdam/go-sophos) - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies. ![stars](https://img.shields.io/badge/stars-12-blue)
- [go-swagger-ui](https://github.com/esurdam/go-swagger-ui) - Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json. ![stars](https://img.shields.io/badge/stars-11-blue)
- [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
- [go-trending](https://github.com/andygrunwald/go-trending) - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) at Github. ![stars](https://img.shields.io/badge/stars-143-blue)
- [go-twitter](https://github.com/dghubble/go-twitter) - Go client library for the Twitter v1.1 APIs. ![stars](https://img.shields.io/badge/stars-1587-blue)
- [go-unsplash](https://github.com/hbagdi/go-unsplash) - Go client library for the [Unsplash.com](https://unsplash.com) API. ![stars](https://img.shields.io/badge/stars-75-blue)
- [go-xkcd](https://github.com/nishanths/go-xkcd) - Go client for the xkcd API. ![stars](https://img.shields.io/badge/stars-51-blue)
- [go-yapla](https://gitlab.com/adrienK/go-yapla) - Go client library for the Yapla v2.0 API.
- [goagi](https://github.com/staskobzar/goagi) - Go library to build Asterisk PBX agi/fastagi applications. ![stars](https://img.shields.io/badge/stars-10-blue)
- [goami2](https://github.com/staskobzar/goami2) - AMI v2 library for Asterisk PBX. ![stars](https://img.shields.io/badge/stars-15-blue)
- [GoFreeDB](https://github.com/FreeLeh/GoFreeDB) - Golang library providing common and simple database abstractions on top of Google Sheets. ![stars](https://img.shields.io/badge/stars-36-blue)
- [gogtrends](https://github.com/groovili/gogtrends) - Google Trends Unofficial API. ![stars](https://img.shields.io/badge/stars-82-blue)
- [golang-tmdb](https://github.com/cyruzin/golang-tmdb) - Golang wrapper for The Movie Database API v3. ![stars](https://img.shields.io/badge/stars-129-blue)
- [golyrics](https://github.com/mamal72/golyrics) - Golyrics is a Go library to fetch music lyrics data from the Wikia website. ![stars](https://img.shields.io/badge/stars-42-blue)
- [gomalshare](https://github.com/MonaxGT/gomalshare) - Go library MalShare API [malshare.com](https://www.malshare.com/) ![stars](https://img.shields.io/badge/stars-12-blue)
- [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) - Go MusicBrainz WS2 client library. ![stars](https://img.shields.io/badge/stars-59-blue)
- [google](https://github.com/google/google-api-go-client) - Auto-generated Google APIs for Go. ![stars](https://img.shields.io/badge/stars-4088-blue)
- [google-analytics](https://github.com/chonthu/go-google-analytics) - Simple wrapper for easy google analytics reporting. ![stars](https://img.shields.io/badge/stars-15-blue)
- [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) - Google Cloud APIs Go Client Library. ![stars](https://img.shields.io/badge/stars-3845-blue)
- [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/). ![stars](https://img.shields.io/badge/stars-8-blue)
- [google-play-scraper](https://github.com/n0madic/google-play-scraper) - Get data from Google Play Store. ![stars](https://img.shields.io/badge/stars-83-blue)
- [gopaapi5](https://github.com/utekaravinash/gopaapi5) - Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/). ![stars](https://img.shields.io/badge/stars-16-blue)
- [gopensky](https://github.com/navidys/gopensky) - Go client implementation for [OpenSKY Network](https://opensky-network.org/) live's API (airspace ADS-B and Mode S data). ![stars](https://img.shields.io/badge/stars-2-blue)
- [gosip](https://github.com/koltyakov/gosip) - Client library for SharePoint. ![stars](https://img.shields.io/badge/stars-150-blue)
- [gostorm](https://github.com/jsgilmore/gostorm) - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells. ![stars](https://img.shields.io/badge/stars-129-blue)
- [hipchat](https://github.com/andybons/hipchat) - This project implements a golang client library for the Hipchat API. ![stars](https://img.shields.io/badge/stars-105-blue)
- [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) - A golang package to communicate with HipChat over XMPP. ![stars](https://img.shields.io/badge/stars-111-blue)
- [igdb](https://github.com/Henry-Sarabia/igdb) - Go client for the [Internet Game Database API](https://api.igdb.com/). ![stars](https://img.shields.io/badge/stars-83-blue)
- [ip2location-io-go](https://github.com/ip2location/ip2location-io-go) - Go wrapper for the IP2Location.io API [IP2Location.io](https://www.ip2location.io/). ![stars](https://img.shields.io/badge/stars-10-blue)
- [jokeapi-go](https://github.com/icelain/jokeapi) - Go client for [JokeAPI](https://sv443.net/jokeapi/v2/). ![stars](https://img.shields.io/badge/stars-24-blue)
- [lark](https://github.com/chyroc/lark) - [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback. ![stars](https://img.shields.io/badge/stars-427-blue)
- [lastpass-go](https://github.com/ansd/lastpass-go) - Go client library for the [LastPass](https://www.lastpass.com/) API. ![stars](https://img.shields.io/badge/stars-35-blue)
- [libgoffi](https://github.com/clevabit/libgoffi) - Library adapter toolbox for native [libffi](https://sourceware.org/libffi/) integration ![stars](https://img.shields.io/badge/stars-9-blue)
- [Medium](https://github.com/Medium/medium-sdk-go) - Golang SDK for Medium's OAuth2 API. ![stars](https://img.shields.io/badge/stars-141-blue)
- [megos](https://github.com/andygrunwald/megos) - Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster. ![stars](https://img.shields.io/badge/stars-54-blue)
- [minio-go](https://github.com/minio/minio-go) - Minio Go Library for Amazon S3 compatible cloud storage. ![stars](https://img.shields.io/badge/stars-2544-blue)
- [mixpanel](https://github.com/dukex/mixpanel) - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications. ![stars](https://img.shields.io/badge/stars-61-blue)
- [newsapi-go](https://github.com/jellydator/newsapi-go) - Go client for [NewsAPI](https://newsapi.org/). ![stars](https://img.shields.io/badge/stars-7-blue)
- [openaigo](https://github.com/otiai10/openaigo) - OpenAI GPT3/GPT3.5 ChatGPT API client library for Go. ![stars](https://img.shields.io/badge/stars-290-blue)
- [patreon-go](https://github.com/mxpv/patreon-go) - Go library for Patreon API. ![stars](https://img.shields.io/badge/stars-42-blue)
- [paypal](https://github.com/logpacker/PayPal-Go-SDK) - Wrapper for PayPal payment API. ![stars](https://img.shields.io/badge/stars-700-blue)
- [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) - The Playlyfe Rest API Go SDK. ![stars](https://img.shields.io/badge/stars-2-blue)
- [pushover](https://github.com/gregdel/pushover) - Go wrapper for the Pushover API. ![stars](https://img.shields.io/badge/stars-145-blue)
- [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) - Go library for the [RAWG Video Games Database](https://rawg.io/) API ![stars](https://img.shields.io/badge/stars-13-blue)
- [rrdaclient](https://github.com/Omie/rrdaclient) - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP. ![stars](https://img.shields.io/badge/stars-10-blue)
- [shopify](https://github.com/rapito/go-shopify) - Go Library to make CRUD request to the Shopify API. ![stars](https://img.shields.io/badge/stars-24-blue)
- [simples3](https://github.com/rhnvrm/simples3) - Simple no frills AWS S3 Library using REST with V4 Signing written in Go. ![stars](https://img.shields.io/badge/stars-156-blue)
- [slack](https://github.com/slack-go/slack) - Slack API in Go. ![stars](https://img.shields.io/badge/stars-4711-blue)
- [smite](https://github.com/sergiotapia/smitego) - Go package to wraps access to the Smite game API. ![stars](https://img.shields.io/badge/stars-11-blue)
- [spotify](https://github.com/rapito/go-spotify) - Go Library to access Spotify WEB API. ![stars](https://img.shields.io/badge/stars-51-blue)
- [steam](https://github.com/sostronk/go-steam) - Go Library to interact with Steam game servers. ![stars](https://img.shields.io/badge/stars-32-blue)
- [stripe](https://github.com/stripe/stripe-go) - Go client for the Stripe API. ![stars](https://img.shields.io/badge/stars-2191-blue)
- [swag](https://github.com/zc2638/swag) - No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more. ![stars](https://img.shields.io/badge/stars-47-blue)
- [textbelt](https://github.com/dietsche/textbelt) - Go client for the textbelt.com txt messaging API. ![stars](https://img.shields.io/badge/stars-20-blue)
- [translate](https://github.com/poorny/translate) - Go online translation package. ![stars](https://img.shields.io/badge/stars-33-blue)
- [Trello](https://github.com/adlio/trello) - Go wrapper for the Trello API. ![stars](https://img.shields.io/badge/stars-221-blue)
- [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) - Go wrapper for the TripAdvisor API. ![stars](https://img.shields.io/badge/stars-2-blue)
- [tumblr](https://github.com/mattcunningham/gumblr) - Go wrapper for the Tumblr v2 API. ![stars](https://img.shields.io/badge/stars-8-blue)
- [twitter-scraper](https://github.com/n0madic/twitter-scraper) - Scrape the Twitter Frontend API without authentication and limits. ![stars](https://img.shields.io/badge/stars-943-blue)
- [uptimerobot](https://github.com/bitfield/uptimerobot) - Go wrapper and command-line client for the Uptime Robot v2 API. ![stars](https://img.shields.io/badge/stars-57-blue)
- [vl-go](https://github.com/verifid/vl-go) - Go client library around the VerifID identity verification layer API. ![stars](https://img.shields.io/badge/stars-2-blue)
- [webhooks](https://github.com/go-playground/webhooks) - Webhook receiver for GitHub and Bitbucket. ![stars](https://img.shields.io/badge/stars-968-blue)
- [wit-go](https://github.com/wit-ai/wit-go) - Go client for wit.ai HTTP API. ![stars](https://img.shields.io/badge/stars-161-blue)
- [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API. ![stars](https://img.shields.io/badge/stars-70-blue)
- [zooz](https://github.com/gojuno/go-zooz) - Go client for the Zooz API. ![stars](https://img.shields.io/badge/stars-7-blue)

**[⬆ back to top](#contents)**

## Utilities

_General utilities and tools to make your life easier._

- [apm](https://github.com/topfreegames/apm) - Process manager for Golang applications with an HTTP API. ![stars](https://img.shields.io/badge/stars-167-blue)
- [backscanner](https://github.com/icza/backscanner) - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward. ![stars](https://img.shields.io/badge/stars-64-blue)
- [bed](https://github.com/itchyny/bed) - A Vim-like binary editor written in Go. ![stars](https://img.shields.io/badge/stars-1280-blue)
- [blank](https://github.com/Henry-Sarabia/blank) - Verify or remove blanks and whitespace from strings. ![stars](https://img.shields.io/badge/stars-12-blue)
- [bleep](https://github.com/sinhashubham95/bleep) - Perform any number of actions on any set of OS signals in Go. ![stars](https://img.shields.io/badge/stars-11-blue)
- [boilr](https://github.com/tmrts/boilr) - Blazingly fast CLI tool for creating projects from boilerplate templates. ![stars](https://img.shields.io/badge/stars-1729-blue)
- [changie](https://github.com/miniscruff/changie) - Automated changelog tool for preparing releases with lots of customization options. ![stars](https://img.shields.io/badge/stars-712-blue)
- [chyle](https://github.com/antham/chyle) - Changelog generator using a git repository with multiple configuration possibilities. ![stars](https://img.shields.io/badge/stars-157-blue)
- [circuit](https://github.com/cep21/circuit) - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern. ![stars](https://img.shields.io/badge/stars-772-blue)
- [circuitbreaker](https://github.com/rubyist/circuitbreaker) - Circuit Breakers in Go. ![stars](https://img.shields.io/badge/stars-1130-blue)
- [clipboard](https://github.com/golang-design/clipboard) - 📋 cross-platform clipboard package in Go. ![stars](https://img.shields.io/badge/stars-640-blue)
- [clockwork](https://github.com/jonboulle/clockwork) - A simple fake clock for golang. ![stars](https://img.shields.io/badge/stars-678-blue)
- [cmd](https://github.com/SimonBaeumer/cmd) - Library for executing shell commands on osx, windows and linux. ![stars](https://img.shields.io/badge/stars-155-blue)
- [command](https://github.com/txgruppi/command) - Command pattern for Go with thread safe serial and parallel dispatcher. ![stars](https://img.shields.io/badge/stars-13-blue)
- [config-file-validator](https://github.com/Boeing/config-file-validator) - Cross Platform tool to validate configuration files. ![stars](https://img.shields.io/badge/stars-355-blue)
- [cookie](https://github.com/syntaqx/cookie) - Cookie struct parsing and helper package. ![stars](https://img.shields.io/badge/stars-111-blue)
- [copy-pasta](https://github.com/jutkko/copy-pasta) - Universal multi-workstation clipboard that uses S3 like backend for the storage. ![stars](https://img.shields.io/badge/stars-51-blue)
- [countries](https://github.com/biter777/countries) - Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standards. ![stars](https://img.shields.io/badge/stars-417-blue)
- [countries](https://github.com/pioz/countries) - All you need when you are working with countries in Go. ![stars](https://img.shields.io/badge/stars-87-blue)
- [create-go-app](https://github.com/create-go-app/cli) - A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command. ![stars](https://img.shields.io/badge/stars-2647-blue)
- [cryptgo](https://github.com/Gituser143/cryptgo) - Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time! ![stars](https://img.shields.io/badge/stars-155-blue)
- [ctop](https://github.com/bcicen/ctop) - [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics. ![stars](https://img.shields.io/badge/stars-15718-blue)
- [ctxutil](https://github.com/posener/ctxutil) - A collection of utility functions for contexts. ![stars](https://img.shields.io/badge/stars-25-blue)
- [cvt](https://github.com/shockerli/cvt) - Easy and safe convert any value to another type. ![stars](https://img.shields.io/badge/stars-49-blue)
- [dbt](https://github.com/nikogura/dbt) - A framework for running self-updating signed binaries from a central, trusted repository. ![stars](https://img.shields.io/badge/stars-64-blue)
- [Death](https://github.com/vrecan/death) - Managing go application shutdown with signals. ![stars](https://img.shields.io/badge/stars-196-blue)
- [delve](https://github.com/derekparker/delve) - Go debugger. ![stars](https://img.shields.io/badge/stars-642-blue)
- [dive](https://github.com/wagoodman/dive) - A tool for exploring each layer in a Docker image. ![stars](https://img.shields.io/badge/stars-48961-blue)
- [dlog](https://github.com/kirillDanshin/dlog) - Compile-time controlled logger to make your release smaller without removing debug calls. ![stars](https://img.shields.io/badge/stars-17-blue)
- [EaseProbe](https://github.com/megaease/easeprobe) - A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification. ![stars](https://img.shields.io/badge/stars-2190-blue)
- [equalizer](https://github.com/reugn/equalizer) - Quota manager and rate limiter collection for Go. ![stars](https://img.shields.io/badge/stars-89-blue)
- [ergo](https://github.com/cristianoliveira/ergo) - The management of multiple local services running over different ports made easy. ![stars](https://img.shields.io/badge/stars-631-blue)
- [evaluator](https://github.com/nullne/evaluator) - Evaluate an expression dynamically based on s-expression. It's simple and easy to extend. ![stars](https://img.shields.io/badge/stars-41-blue)
- [Failsafe-go](https://github.com/failsafe-go/failsafe-go) - Fault tolerance and resilience patterns for Go. ![stars](https://img.shields.io/badge/stars-1715-blue)
- [filetype](https://github.com/h2non/filetype) - Small package to infer the file type checking the magic numbers signature. ![stars](https://img.shields.io/badge/stars-2145-blue)
- [filler](https://github.com/yaronsumel/filler) - small utility to fill structs using "fill" tag. ![stars](https://img.shields.io/badge/stars-18-blue)
- [filter](https://github.com/gookit/filter) - provide filtering, sanitizing, and conversion of Go data. ![stars](https://img.shields.io/badge/stars-151-blue)
- [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder written in Go. ![stars](https://img.shields.io/badge/stars-67106-blue)
- [generate](https://github.com/go-playground/generate) - runs go generate recursively on a specified path or environment variable and can filter by regex. ![stars](https://img.shields.io/badge/stars-30-blue)
- [ghokin](https://github.com/antham/ghokin) - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...). ![stars](https://img.shields.io/badge/stars-45-blue)
- [git-time-metric](https://github.com/git-time-metric/gtm) - Simple, seamless, lightweight time tracking for Git. ![stars](https://img.shields.io/badge/stars-982-blue)
- [gitbatch](https://github.com/isacikgoz/gitbatch) - manage your git repositories in one place. ![stars](https://img.shields.io/badge/stars-1544-blue)
- [gitcs](https://github.com/knbr13/gitcs/) - Git Commits Visualizer, CLI tool to visualize your Git commits on your local machine. ![stars](https://img.shields.io/badge/stars-121-blue)
- [go-actuator](https://github.com/sinhashubham95/go-actuator) - Production ready features for Go based web frameworks. ![stars](https://img.shields.io/badge/stars-15-blue)
- [go-astitodo](https://github.com/asticode/go-astitodo) - Parse TODOs in your GO code. ![stars](https://img.shields.io/badge/stars-65-blue)
- [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) - go:generate tool for wrapping symbols exported by golang plugins (1.8 only). ![stars](https://img.shields.io/badge/stars-183-blue)
- [go-bsdiff](https://github.com/gabstv/go-bsdiff) - Pure Go bsdiff and bspatch libraries and CLI tools. ![stars](https://img.shields.io/badge/stars-161-blue)
- [go-clip](https://github.com/prashantgupta24/go-clip) - A minimalistic clipboard manager for Mac. ![stars](https://img.shields.io/badge/stars-13-blue)
- [go-convert](https://github.com/Eun/go-convert) - Package go-convert enables you to convert a value into another type. ![stars](https://img.shields.io/badge/stars-22-blue)
- [go-countries](https://github.com/mikekonan/go-countries) - Lightweight lookup over ISO-3166 codes. ![stars](https://img.shields.io/badge/stars-16-blue)
- [go-dry](https://github.com/ungerik/go-dry) - DRY (don't repeat yourself) package for Go. ![stars](https://img.shields.io/badge/stars-488-blue)
- [go-events](https://github.com/deatil/go-events) - A go event and event'subscribe package, like wordpress hook functions. ![stars](https://img.shields.io/badge/stars-2-blue)
- [go-funk](https://github.com/thoas/go-funk) - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...). ![stars](https://img.shields.io/badge/stars-4846-blue)
- [go-health](https://github.com/Talento90/go-health) - Health package simplifies the way you add health check to your services. ![stars](https://img.shields.io/badge/stars-96-blue)
- [go-httpheader](https://github.com/mozillazg/go-httpheader) - Go library for encoding structs into Header fields. ![stars](https://img.shields.io/badge/stars-47-blue)
- [go-lambda-cleanup](https://github.com/karl-cardenas-coding/go-lambda-cleanup) - A CLI for removing unused or previous versions of AWS Lambdas. ![stars](https://img.shields.io/badge/stars-91-blue)
- [go-lock](https://github.com/viney-shih/go-lock) - go-lock is a lock library implementing read-write mutex and read-write trylock without starvation. ![stars](https://img.shields.io/badge/stars-117-blue)
- [go-pattern-match](https://github.com/PhakornKiong/go-pattern-match) - A Pattern matching library inspired by ts-pattern. ![stars](https://img.shields.io/badge/stars-93-blue)
- [go-pkg](https://github.com/chenquan/go-pkg) - A go toolkit. ![stars](https://img.shields.io/badge/stars-7-blue)
- [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) - Go package for working with Problem Details. ![stars](https://img.shields.io/badge/stars-17-blue)
- [go-qr](https://github.com/piglig/go-qr) - A native, high-quality and minimalistic QR code generator. ![stars](https://img.shields.io/badge/stars-35-blue)
- [go-rate](https://github.com/beefsack/go-rate) - Timed rate limiter for Go. ![stars](https://img.shields.io/badge/stars-400-blue)
- [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) - XML Sitemap generator written in Go. ![stars](https://img.shields.io/badge/stars-222-blue)
- [go-trigger](https://github.com/sadlil/go-trigger) - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project. ![stars](https://img.shields.io/badge/stars-247-blue)
- [go-tripper](https://github.com/rajnandan1/go-tripper) - Tripper is a circuit breaker package for Go that allows you to circuit and control the status of circuits. ![stars](https://img.shields.io/badge/stars-12-blue)
- [go-type](https://github.com/mikekonan/go-types) - Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types. ![stars](https://img.shields.io/badge/stars-19-blue)
- [goback](https://github.com/carlescere/goback) - Go simple exponential backoff package. ![stars](https://img.shields.io/badge/stars-49-blue)
- [goctx](https://github.com/zerosnake0/goctx) - Get your context value with high performance. ![stars](https://img.shields.io/badge/stars-10-blue)
- [godaemon](https://github.com/VividCortex/godaemon) - Utility to write daemons. ![stars](https://img.shields.io/badge/stars-493-blue)
- [godropbox](https://github.com/dropbox/godropbox) - Common libraries for writing Go services/applications from Dropbox. ![stars](https://img.shields.io/badge/stars-4174-blue)
- [gofn](https://github.com/tiendc/gofn) - High performance utility functions written using Generics for Go 1.18+. ![stars](https://img.shields.io/badge/stars-52-blue)
- [golarm](https://github.com/msempere/golarm) - Fire alarms with system events. ![stars](https://img.shields.io/badge/stars-53-blue)
- [golog](https://github.com/mlimaloureiro/golog) - Easy and lightweight CLI tool to time track your tasks. ![stars](https://img.shields.io/badge/stars-62-blue)
- [gopencils](https://github.com/bndr/gopencils) - Small and simple package to easily consume REST APIs. ![stars](https://img.shields.io/badge/stars-452-blue)
- [goplaceholder](https://github.com/michiwend/goplaceholder) - a small golang lib to generate placeholder images. ![stars](https://img.shields.io/badge/stars-29-blue)
- [goreadability](https://github.com/philipjkim/goreadability) - Webpage summary extractor using Facebook Open Graph and arc90's readability. ![stars](https://img.shields.io/badge/stars-69-blue)
- [goreleaser](https://github.com/goreleaser/goreleaser) - Deliver Go binaries as fast and easily as possible. ![stars](https://img.shields.io/badge/stars-14105-blue)
- [goreporter](https://github.com/wgliang/goreporter) - Golang tool that does static analysis, unit testing, code review and generate code quality report. ![stars](https://img.shields.io/badge/stars-3131-blue)
- [goseaweedfs](https://github.com/linxGnu/goseaweedfs) - SeaweedFS client library with almost full features. ![stars](https://img.shields.io/badge/stars-113-blue)
- [gostrutils](https://github.com/ik5/gostrutils) - Collections of string manipulation and conversion functions. ![stars](https://img.shields.io/badge/stars-46-blue)
- [gotenv](https://github.com/subosito/gotenv) - Load environment variables from `.env` or any `io.Reader` in Go. ![stars](https://img.shields.io/badge/stars-300-blue)
- [goval](https://github.com/maja42/goval) - Evaluate arbitrary expressions in Go. ![stars](https://img.shields.io/badge/stars-160-blue)
- [graterm](https://github.com/skovtunenko/graterm) - Provides primitives to perform ordered (sequential/concurrent) GRAceful TERMination (aka shutdown) in Go application. ![stars](https://img.shields.io/badge/stars-26-blue)
- [grofer](https://github.com/pesos/grofer) - A system and resource monitoring tool written in Golang! ![stars](https://img.shields.io/badge/stars-360-blue)
- [gubrak](https://github.com/novalagung/gubrak) - Golang utility library with syntactic sugar. It's like lodash, but for golang. ![stars](https://img.shields.io/badge/stars-492-blue)
- [handy](https://github.com/miguelpragier/handy) - Many utilities and helpers like string handlers/formatters and validators. ![stars](https://img.shields.io/badge/stars-81-blue)
- [hostctl](https://github.com/guumaster/hostctl) - A CLI tool to manage /etc/hosts with easy commands. ![stars](https://img.shields.io/badge/stars-1115-blue)
- [htcat](https://github.com/htcat/htcat) - Parallel and Pipelined HTTP GET Utility. ![stars](https://img.shields.io/badge/stars-553-blue)
- [hub](https://github.com/github/hub) - wrap git commands with additional functionality to interact with github from the terminal. ![stars](https://img.shields.io/badge/stars-22860-blue)
- [immortal](https://github.com/immortal/immortal) - \*nix cross-platform (OS agnostic) supervisor. ![stars](https://img.shields.io/badge/stars-807-blue)
- [jet](https://github.com/NicoNex/jet) - Just Edit Text: a fast and powerful tool for finding and replacing file content and names using regular expressions. ![stars](https://img.shields.io/badge/stars-9-blue)
- [jsend](https://github.com/clevergo/jsend) - JSend's implementation written in Go. ![stars](https://img.shields.io/badge/stars-22-blue)
- [json-log-viewer](https://github.com/hedhyw/json-log-viewer) - Interactive viewer for JSON logs. ![stars](https://img.shields.io/badge/stars-131-blue)
- [jump](https://github.com/gsamokovarov/jump) - Jump helps you navigate faster by learning your habits. ![stars](https://img.shields.io/badge/stars-1807-blue)
- [just](https://github.com/kazhuravlev/just) - Just a collection of useful functions for working with generic data structures. ![stars](https://img.shields.io/badge/stars-32-blue)
- [koazee](https://github.com/wesovilabs/koazee) - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays. ![stars](https://img.shields.io/badge/stars-529-blue)
- [lancet](https://github.com/duke-git/lancet) - A comprehensive, efficient, and reusable util function library of go. ![stars](https://img.shields.io/badge/stars-4865-blue)
- [lets-go](https://github.com/aplescia-chwy/lets-go) - Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities. ![stars](https://img.shields.io/badge/stars-7-blue)
- [limiters](https://github.com/mennanov/limiters) - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks. ![stars](https://img.shields.io/badge/stars-495-blue)
- [lo](https://github.com/samber/lo) - A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...) ![stars](https://img.shields.io/badge/stars-18421-blue)
- [loncha](https://github.com/kazu/loncha) - A high-performance slice Utilities. ![stars](https://img.shields.io/badge/stars-11-blue)
- [lrserver](https://github.com/jaschaephraim/lrserver) - LiveReload server for Go. ![stars](https://img.shields.io/badge/stars-128-blue)
- [mani](https://github.com/alajmo/mani) - CLI tool to help you manage multiple repositories. ![stars](https://img.shields.io/badge/stars-456-blue)
- [mc](https://github.com/minio/mc) - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems. ![stars](https://img.shields.io/badge/stars-2925-blue)
- [mergo](https://github.com/imdario/mergo) - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements. ![stars](https://img.shields.io/badge/stars-2913-blue)
- [mimemagic](https://github.com/zRedShift/mimemagic) - Pure Go ultra performant MIME sniffing library/utility. ![stars](https://img.shields.io/badge/stars-99-blue)
- [mimesniffer](https://github.com/aofei/mimesniffer) - A MIME type sniffer for Go. ![stars](https://img.shields.io/badge/stars-33-blue)
- [mimetype](https://github.com/gabriel-vasile/mimetype) - Package for MIME type detection based on magic numbers. ![stars](https://img.shields.io/badge/stars-1716-blue)
- [minify](https://github.com/tdewolff/minify) - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats. ![stars](https://img.shields.io/badge/stars-3778-blue)
- [minquery](https://github.com/icza/minquery) - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off). ![stars](https://img.shields.io/badge/stars-62-blue)
- [moldova](https://github.com/StabbyCutyou/moldova) - Utility for generating random data based on an input template. ![stars](https://img.shields.io/badge/stars-169-blue)
- [mole](https://github.com/davrodpin/mole) - cli app to easily create ssh tunnels. ![stars](https://img.shields.io/badge/stars-1702-blue)
- [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) - Mongodb Pagination for official mongodb/mongo-go-driver package which supports both normal queries and Aggregation pipelines. ![stars](https://img.shields.io/badge/stars-130-blue)
- [mssqlx](https://github.com/linxGnu/mssqlx) - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind. ![stars](https://img.shields.io/badge/stars-103-blue)
- [multitick](https://github.com/VividCortex/multitick) - Multiplexor for aligned tickers. ![stars](https://img.shields.io/badge/stars-70-blue)
- [myhttp](https://github.com/inancgumus/myhttp) - Simple API to make HTTP GET requests with timeout support. ![stars](https://img.shields.io/badge/stars-34-blue)
- [netbug](https://github.com/e-dard/netbug) - Easy remote profiling of your services. ![stars](https://img.shields.io/badge/stars-72-blue)
- [nfdump](https://github.com/chrispassas/nfdump) - Read nfdump netflow files. ![stars](https://img.shields.io/badge/stars-11-blue)
- [nostromo](https://github.com/pokanop/nostromo) - CLI for building powerful aliases. ![stars](https://img.shields.io/badge/stars-144-blue)
- [okrun](https://github.com/xta/okrun) - go run error steamroller. ![stars](https://img.shields.io/badge/stars-16-blue)
- [olaf](https://github.com/btnguyen2k/olaf) - Twitter Snowflake implemented in Go. ![stars](https://img.shields.io/badge/stars-5-blue)
- [onecache](https://github.com/adelowo/onecache) - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc). ![stars](https://img.shields.io/badge/stars-136-blue)
- [panicparse](https://github.com/maruel/panicparse) - Groups similar goroutines and colorizes stack dump. ![stars](https://img.shields.io/badge/stars-3540-blue)
- [pattern-match](https://github.com/alexpantyukhin/go-pattern-match) - Pattern matching library. ![stars](https://img.shields.io/badge/stars-246-blue)
- [peco](https://github.com/peco/peco) - Simplistic interactive filtering tool. ![stars](https://img.shields.io/badge/stars-7707-blue)
- [pgo](https://github.com/arthurkushman/pgo) - Convenient functions for PHP community. ![stars](https://img.shields.io/badge/stars-86-blue)
- [pm](https://github.com/VividCortex/pm) - Process (i.e. goroutine) manager with an HTTP API. ![stars](https://img.shields.io/badge/stars-79-blue)
- [pointer](https://github.com/xorcare/pointer) - Package pointer contains helper routines for simplifying the creation of optional fields of basic type. ![stars](https://img.shields.io/badge/stars-42-blue)
- [ptr](https://github.com/gotidy/ptr) - Package that provide functions for simplified creation of pointers from constants of basic types. ![stars](https://img.shields.io/badge/stars-27-blue)
- [rclient](https://github.com/zpatrick/rclient) - Readable, flexible, simple-to-use client for REST APIs. ![stars](https://img.shields.io/badge/stars-35-blue)
- [remote-touchpad](https://github.com/Unrud/remote-touchpad) - Control mouse and keyboard from a smartphone. ![stars](https://img.shields.io/badge/stars-566-blue)
- [repeat](https://github.com/ssgreg/repeat) - Go implementation of different backoff strategies useful for retrying operations and heartbeating. ![stars](https://img.shields.io/badge/stars-85-blue)
- [request](https://github.com/mozillazg/request) - Go HTTP Requests for Humans™. ![stars](https://img.shields.io/badge/stars-426-blue)
- [rerun](https://github.com/ivpusic/rerun) - Recompiling and rerunning go apps when source changes. ![stars](https://img.shields.io/badge/stars-166-blue)
- [rest-go](https://github.com/edermanoel94/rest-go) - A package that provide many helpful methods for working with rest api. ![stars](https://img.shields.io/badge/stars-16-blue)
- [retry](https://github.com/kamilsk/retry) - The most advanced functional mechanism to perform actions repetitively until successful. ![stars](https://img.shields.io/badge/stars-342-blue)
- [retry](https://github.com/percolate/retry) - A simple but highly configurable retry package for Go. ![stars](https://img.shields.io/badge/stars-10-blue)
- [retry](https://github.com/thedevsaddam/retry) - Simple and easy retry mechanism package for Go. ![stars](https://img.shields.io/badge/stars-66-blue)
- [retry](https://github.com/shafreeck/retry) - A pretty simple library to ensure your work to be done. ![stars](https://img.shields.io/badge/stars-12-blue)
- [retry-go](https://github.com/avast/retry-go) - Simple library for retry mechanism. ![stars](https://img.shields.io/badge/stars-2500-blue)
- [retry-go](https://github.com/rafaeljesus/retry-go) - Retrying made simple and easy for golang. ![stars](https://img.shields.io/badge/stars-50-blue)
- [robustly](https://github.com/VividCortex/robustly) - Runs functions resiliently, catching and restarting panics. ![stars](https://img.shields.io/badge/stars-159-blue)
- [rospo](https://github.com/ferama/rospo) - Simple and reliable ssh tunnels with embedded ssh server in Golang. ![stars](https://img.shields.io/badge/stars-318-blue)
- [scan](https://github.com/blockloop/scan) - Scan golang `sql.Rows` directly to structs, slices, or primitive types. ![stars](https://img.shields.io/badge/stars-571-blue)
- [scan](https://github.com/wroge/scan) - Scan sql rows into any type powered by generics. ![stars](https://img.shields.io/badge/stars-63-blue)
- [scany](https://github.com/georgysavva/scany) - Library for scanning data from a database into Go structs and more. ![stars](https://img.shields.io/badge/stars-1335-blue)
- [serve](https://github.com/syntaqx/serve) - A static http server anywhere you need. ![stars](https://img.shields.io/badge/stars-336-blue)
- [sesh](https://github.com/joshmedeski/sesh) - Sesh is a CLI that helps you create and manage tmux sessions quickly and easily using zoxide. ![stars](https://img.shields.io/badge/stars-792-blue)
- [set](https://github.com/nofeaturesonlybugs/set) - Performant and flexible struct mapping and loose type conversion. ![stars](https://img.shields.io/badge/stars-47-blue)
- [shutdown](https://github.com/ztrue/shutdown) - App shutdown hooks for `os.Signal` handling. ![stars](https://img.shields.io/badge/stars-59-blue)
- [silk](https://github.com/chrispassas/silk) - Read silk netflow files. ![stars](https://img.shields.io/badge/stars-14-blue)
- [slice](https://github.com/psampaz/slice) - Type-safe functions for common Go slice operations. ![stars](https://img.shields.io/badge/stars-51-blue)
- [sliceconv](https://github.com/Henry-Sarabia/sliceconv) - Slice conversion between primitive types. ![stars](https://img.shields.io/badge/stars-10-blue)
- [slicer](https://github.com/leaanthony/slicer) - Makes working with slices easier. ![stars](https://img.shields.io/badge/stars-46-blue)
- [sorty](https://github.com/jfcg/sorty) - Fast Concurrent / Parallel Sorting. ![stars](https://img.shields.io/badge/stars-134-blue)
- [sqlx](https://github.com/jmoiron/sqlx) - provides a set of extensions on top of the excellent built-in database/sql package. ![stars](https://img.shields.io/badge/stars-16511-blue)
- [sshman](https://github.com/shoobyban/sshman) - SSH Manager for authorized_keys files on multiple remote servers. ![stars](https://img.shields.io/badge/stars-50-blue)
- [statiks](https://github.com/janiltonmaciel/statiks) - Fast, zero-configuration, static HTTP filer server. ![stars](https://img.shields.io/badge/stars-11-blue)
- [Storm](https://github.com/asdine/storm) - Simple and powerful toolkit for BoltDB. ![stars](https://img.shields.io/badge/stars-2066-blue)
- [structs](https://github.com/PumpkinSeed/structs) - Implement simple functions to manipulate structs. ![stars](https://img.shields.io/badge/stars-24-blue)
- [throttle](https://github.com/yudppp/throttle) - Throttle is an object that will perform exactly one action per duration. ![stars](https://img.shields.io/badge/stars-39-blue)
- [tik](https://github.com/andy2046/tik) - Simple and easy timing wheel package for Go. ![stars](https://img.shields.io/badge/stars-5-blue)
- [tome](https://github.com/cyruzin/tome) - Tome was designed to paginate simple RESTful APIs. ![stars](https://img.shields.io/badge/stars-35-blue)
- [toolbox](https://github.com/viant/toolbox) - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer. ![stars](https://img.shields.io/badge/stars-198-blue)
- [UNIS](https://github.com/esemplastic/unis) - Common Architecture™ for String Utilities in Go. ![stars](https://img.shields.io/badge/stars-70-blue)
- [upterm](https://github.com/owenthereal/upterm) - A tool for developers to share terminal/tmux sessions securely over the web. It’s perfect for remote pair programming, accessing computers behind NATs/firewalls, remote debugging, and more. ![stars](https://img.shields.io/badge/stars-884-blue)
- [usql](https://github.com/knq/usql) - usql is a universal command-line interface for SQL databases. ![stars](https://img.shields.io/badge/stars-9164-blue)
- [util](https://github.com/shomali11/util) - Collection of useful utility functions. (strings, concurrency, manipulations, ...). ![stars](https://img.shields.io/badge/stars-294-blue)
- [watchhttp](https://github.com/nikolaydubina/watchhttp) - Run command periodically and expose latest STDOUT or its rich delta as HTTP endpoint. ![stars](https://img.shields.io/badge/stars-33-blue)
- [wifiqr](https://github.com/reugn/wifiqr) - Wi-Fi QR Code Generator. ![stars](https://img.shields.io/badge/stars-265-blue)
- [wuzz](https://github.com/asciimoo/wuzz) - Interactive cli tool for HTTP inspection. ![stars](https://img.shields.io/badge/stars-10602-blue)
- [xferspdy](https://github.com/monmohan/xferspdy) - Xferspdy provides binary diff and patch library in golang. ![stars](https://img.shields.io/badge/stars-101-blue)
- [xpool](https://github.com/peczenyj/xpool) - Yet another golang type safe object pool using generics. ![stars](https://img.shields.io/badge/stars-3-blue)
- [yogo](https://github.com/antham/yogo) - Check yopmail mails from command line. ![stars](https://img.shields.io/badge/stars-43-blue)

**[⬆ back to top](#contents)**

## UUID

_Libraries for working with UUIDs._

- [fastuuid](https://github.com/rekby/fastuuid) - Fast generate UUIDv4 as string or bytes.
- [goid](https://github.com/jakehl/goid) - Generate and Parse RFC4122 compliant V4 UUIDs. ![stars](https://img.shields.io/badge/stars-41-blue)
- [gouid](https://github.com/twharmon/gouid) - Generate cryptographically secure random string IDs with just one allocation. ![stars](https://img.shields.io/badge/stars-24-blue)
- [nanoid](https://github.com/aidarkhanov/nanoid) - A tiny and efficient Go unique string ID generator. ![stars](https://img.shields.io/badge/stars-62-blue)
- [sno](https://github.com/muyo/sno) - Compact, sortable and fast unique IDs with embedded metadata. ![stars](https://img.shields.io/badge/stars-92-blue)
- [ulid](https://github.com/oklog/ulid) - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier). ![stars](https://img.shields.io/badge/stars-4586-blue)
- [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.
- [uuid](https://github.com/agext/uuid) - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier. ![stars](https://img.shields.io/badge/stars-18-blue)
- [uuid](https://github.com/gofrs/uuid) - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid. ![stars](https://img.shields.io/badge/stars-1603-blue)
- [uuid](https://github.com/google/uuid) - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services. ![stars](https://img.shields.io/badge/stars-5444-blue)
- [uuidcheck](https://github.com/ashwingopalsamy/uuidcheck) - A tiny, dependency-free Go library that validates UUIDs against standard RFC 4122 formatting, converts UUIDv7() into UTC timestamps. ![stars](https://img.shields.io/badge/stars-5-blue)
- [wuid](https://github.com/edwingeng/wuid) - An extremely fast globally unique number generator. ![stars](https://img.shields.io/badge/stars-535-blue)
- [xid](https://github.com/rs/xid) - Xid is a globally unique id generator library, ready to be safely used directly in your server code. ![stars](https://img.shields.io/badge/stars-4001-blue)

**[⬆ back to top](#contents)**

## Validation

_Libraries for validation._

- [checkdigit](https://github.com/osamingo/checkdigit) - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.). ![stars](https://img.shields.io/badge/stars-110-blue)
- [go-validator](https://github.com/tiendc/go-validator) - Validation library using Generics. ![stars](https://img.shields.io/badge/stars-22-blue)
- [gody](https://github.com/guiferpa/gody) - :balloon: A lightweight struct validator for Go. ![stars](https://img.shields.io/badge/stars-93-blue)
- [govalid](https://github.com/twharmon/govalid) - Fast, tag-based validation for structs. ![stars](https://img.shields.io/badge/stars-54-blue)
- [govalidator](https://github.com/asaskevich/govalidator) - Validators and sanitizers for strings, numerics, slices and structs. ![stars](https://img.shields.io/badge/stars-6077-blue)
- [govalidator](https://github.com/thedevsaddam/govalidator) - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation. ![stars](https://img.shields.io/badge/stars-1324-blue)
- [hvalid](https://github.com/lyonnee/hvalid) hvalid is a lightweight validation library written in Go language. It provides a custom validator interface and a series of common validation functions to help developers quickly implement data validation. ![stars](https://img.shields.io/badge/stars-11-blue)
- [jio](https://github.com/faceair/jio) - jio is a json schema validator similar to [joi](https://github.com/hapijs/joi). ![stars](https://img.shields.io/badge/stars-113-blue)
- [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags. ![stars](https://img.shields.io/badge/stars-3819-blue)
- [validate](https://github.com/gookit/validate) - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features. ![stars](https://img.shields.io/badge/stars-1084-blue)
- [validate](https://github.com/gobuffalo/validate) - This package provides a framework for writing validations for Go applications. ![stars](https://img.shields.io/badge/stars-95-blue)
- [validator](https://github.com/go-playground/validator) - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving. ![stars](https://img.shields.io/badge/stars-17286-blue)
- [Validator](https://github.com/go-the-way/validator) - A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex. ![stars](https://img.shields.io/badge/stars-7-blue)
- [valix](https://github.com/marrow16/valix) Go package for validating requests ![stars](https://img.shields.io/badge/stars-29-blue)
- [Zog](https://github.com/Oudwins/zog) - A [Zod](https://github.com/colinhacks/zod) inspired schema builder for runtime value parsing and validation. ![stars](https://img.shields.io/badge/stars-223-blue)
**[⬆ back to top](#contents)**

## Version Control

_Libraries for version control._

- [cli](https://gitlab.com/gitlab-org/cli) - An open-source GitLab command line tool bringing GitLab's cool features to your command line.
- [froggit-go](https://github.com/jfrog/froggit-go) - Froggit-Go is a Go library, allowing to perform actions on VCS providers. ![stars](https://img.shields.io/badge/stars-46-blue)
- [git2go](https://github.com/libgit2/git2go) - Go bindings for libgit2. ![stars](https://img.shields.io/badge/stars-1945-blue)
- [githooks](https://github.com/gabyx/githooks) - Per-repo and shared Git hooks with version control and auto update. ![stars](https://img.shields.io/badge/stars-106-blue)
- [go-git](https://github.com/go-git/go-git) - highly extensible Git implementation in pure Go. ![stars](https://img.shields.io/badge/stars-6150-blue)
- [go-vcs](https://github.com/sourcegraph/go-vcs) - manipulate and inspect VCS repositories in Go. ![stars](https://img.shields.io/badge/stars-80-blue)
- [hercules](https://github.com/src-d/hercules) - gaining advanced insights from Git repository history. ![stars](https://img.shields.io/badge/stars-2650-blue)
- [hgo](https://github.com/beyang/hgo) - Hgo is a collection of Go packages providing read-access to local Mercurial repositories. ![stars](https://img.shields.io/badge/stars-16-blue)

**[⬆ back to top](#contents)**

## Video

_Libraries for manipulating video._

- [gmf](https://github.com/3d0c/gmf) - Go bindings for FFmpeg av\* libraries. ![stars](https://img.shields.io/badge/stars-899-blue)
- [go-astiav](https://github.com/asticode/go-astiav) - Better C bindings for ffmpeg in GO. ![stars](https://img.shields.io/badge/stars-423-blue)
- [go-astisub](https://github.com/asticode/go-astisub) - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.). ![stars](https://img.shields.io/badge/stars-606-blue)
- [go-astits](https://github.com/asticode/go-astits) - Parse and demux MPEG Transport Streams (.ts) natively in GO. ![stars](https://img.shields.io/badge/stars-552-blue)
- [go-m3u8](https://github.com/etherlabsio/go-m3u8) - Parser and generator library for Apple m3u8 playlists. Actively maintained version of quangngotan95/go-m3u8 with improvements and latest HLS playlist parsing compatibility. ![stars](https://img.shields.io/badge/stars-30-blue)
- [go-mpd](https://github.com/unki2aut/go-mpd) - Parser and generator library for MPEG-DASH manifest files. ![stars](https://img.shields.io/badge/stars-24-blue)
- [goav](https://github.com/giorgisio/goav) - Comprehensive Go bindings for FFmpeg. ![stars](https://img.shields.io/badge/stars-2107-blue)
- [gortsplib](https://github.com/aler9/gortsplib) - Pure Go RTSP server and client library. ![stars](https://img.shields.io/badge/stars-720-blue)
- [libvlc-go](https://github.com/adrg/libvlc-go) - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player). ![stars](https://img.shields.io/badge/stars-445-blue)
- [m3u8](https://github.com/grafov/m3u8) - Parser and generator library of M3U8 playlists for Apple HLS. ![stars](https://img.shields.io/badge/stars-1245-blue)
- [mp4ff](https://github.com/Eyevinn/mp4ff) - Library and tools for working with MP4 files containing video, audio, subtitles, or metadata. ![stars](https://img.shields.io/badge/stars-488-blue)
- [v4l](https://github.com/korandiz/v4l) - Video capture library for Linux, written in Go. ![stars](https://img.shields.io/badge/stars-80-blue)

**[⬆ back to top](#contents)**

## Web Frameworks

_Full stack web frameworks._

- [Atreugo](https://github.com/savsgio/atreugo) - High performance and extensible micro web framework with zero memory allocations in hot paths. ![stars](https://img.shields.io/badge/stars-1252-blue)
- [Beego](https://github.com/beego/beego) - beego is an open-source, high-performance web framework for the Go programming language. ![stars](https://img.shields.io/badge/stars-31766-blue)
- [Confetti Framework](https://confetti-framework.github.io/docs/) - Confetti is a Go web application framework with an expressive, elegant syntax. Confetti combines the elegance of Laravel and the simplicity of Go.
- [Don](https://github.com/abemedia/go-don) - A highly performant and simple to use API framework. ![stars](https://img.shields.io/badge/stars-56-blue)
- [Echo](https://github.com/labstack/echo) - High performance, minimalist Go web framework. ![stars](https://img.shields.io/badge/stars-30274-blue)
- [Fastschema](https://github.com/fastschema/fastschema) - A flexible Go web framework and Headless CMS. ![stars](https://img.shields.io/badge/stars-380-blue)
- [Fiber](https://github.com/gofiber/fiber) - An Express.js inspired web framework build on Fasthttp. ![stars](https://img.shields.io/badge/stars-34633-blue)
- [Flamingo](https://github.com/i-love-flamingo/flamingo) - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc. ![stars](https://img.shields.io/badge/stars-496-blue)
- [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications. ![stars](https://img.shields.io/badge/stars-530-blue)
- [Fuego](https://github.com/go-fuego/fuego) - The framework for busy Go developers! Web framework generating OpenAPI 3 spec from source code. ![stars](https://img.shields.io/badge/stars-1103-blue)
- [Gin](https://github.com/gin-gonic/gin) - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity. ![stars](https://img.shields.io/badge/stars-79845-blue)
- [Ginrpc](https://github.com/xxjwxc/ginrpc) - Gin parameter automatic binding tool,gin rpc tools. ![stars](https://img.shields.io/badge/stars-291-blue)
- [Goa](https://github.com/goadesign/goa) - Goa provides a holistic approach for developing remote APIs and microservices in Go. ![stars](https://img.shields.io/badge/stars-5743-blue)
- [GoFr](https://github.com/gofr-dev/gofr) - Gofr is an opinionated microservice development framework. ![stars](https://img.shields.io/badge/stars-3916-blue)
- [GoFrame](https://github.com/gogf/gf) - GoFrame is a modular, powerful, high-performance and enterprise-class application development framework of Golang. ![stars](https://img.shields.io/badge/stars-11896-blue)
- [golamb](https://github.com/twharmon/golamb) - Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway. ![stars](https://img.shields.io/badge/stars-7-blue)
- [Gone](https://github.com/gone-io/gone) - A lightweight dependency injection and web framework inspired by Spring. ![stars](https://img.shields.io/badge/stars-134-blue)
- [goravel](https://github.com/goravel/goravel) - A Laravel-inspired web framework with ORM, authentication, queue, task scheduling, and more built-in features. ![stars](https://img.shields.io/badge/stars-3102-blue)
- [Goyave](https://github.com/go-goyave/goyave) - Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities. ![stars](https://img.shields.io/badge/stars-1650-blue)
- [Hertz](https://github.com/cloudwego/hertz) - A high-performance and strong-extensibility Go HTTP framework that helps developers build microservices. ![stars](https://img.shields.io/badge/stars-5752-blue)
- [hiboot](https://github.com/hidevopsio/hiboot) - hiboot is a high performance web application framework with auto configuration and dependency injection support. ![stars](https://img.shields.io/badge/stars-180-blue)
- [Huma](https://github.com/danielgtaylor/huma/) - Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI. ![stars](https://img.shields.io/badge/stars-2513-blue)
- [iWF](https://github.com/indeedeng/iwf) - iWF is an all-in-one platform for developing long-running business processes. It offers a convenient abstraction for utilizing databases, ElasticSearch, message queues, durable timers, and more, with a clean, simple, and user-friendly interface. ![stars](https://img.shields.io/badge/stars-546-blue)
- [Lit](https://github.com/jvcoutinho/lit) - Highly performant declarative web framework for Golang, aiming for simplicity and quality of life. ![stars](https://img.shields.io/badge/stars-25-blue)
- [Microservice](https://github.com/claygod/microservice) - The framework for the creation of microservices, written in Golang. ![stars](https://img.shields.io/badge/stars-116-blue)
- [patron](https://github.com/beatlabs/patron) - Patron is a microservice framework following best cloud practices with a focus on productivity. ![stars](https://img.shields.io/badge/stars-123-blue)
- [Pnutmux](https://gitlab.com/fruitygo/pnutmux) - Pnutmux is a powerful Go web framework that uses regex for matching and handling HTTP requests. It offers features such as CORS handling, structured logging, URL parameters extraction, middlewares, and concurrency limiting.
- [Revel](https://github.com/revel/revel) - High-productivity web framework for the Go language. ![stars](https://img.shields.io/badge/stars-13154-blue)
- [rk-boot](https://github.com/rookie-ninja/rk-boot) - A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily. ![stars](https://img.shields.io/badge/stars-524-blue)
- [rux](https://github.com/gookit/rux) - Simple and fast web framework for build golang HTTP applications. ![stars](https://img.shields.io/badge/stars-98-blue)
- [templui](https://github.com/axzilla/templui) - Modern UI Components for Go & Templ. ![stars](https://img.shields.io/badge/stars-265-blue)
- [uAdmin](https://github.com/uadmin/uadmin) - Fully featured web framework for Golang, inspired by Django. ![stars](https://img.shields.io/badge/stars-346-blue)
- [WebGo](https://github.com/naughtygopher/webgo) - A micro-framework to build web apps with handler chaining, middleware, and context injection. With standard library-compliant HTTP handlers (i.e., `http.HandlerFunc`).. ![stars](https://img.shields.io/badge/stars-304-blue)
- [Yokai](https://github.com/ankorstore/yokai) - Simple, modular, and observable Go framework for backend applications. ![stars](https://img.shields.io/badge/stars-538-blue)

**[⬆ back to top](#contents)**

### Middlewares

#### Actual middlewares

- [client-timing](https://github.com/posener/client-timing) - An HTTP client for Server-Timing header. ![stars](https://img.shields.io/badge/stars-24-blue)
- [CORS](https://github.com/rs/cors) - Easily add CORS capabilities to your API. ![stars](https://img.shields.io/badge/stars-2710-blue)
- [echo-middleware](https://github.com/faabiosr/echo-middleware) - Middleware for Echo framework with logging and metrics. ![stars](https://img.shields.io/badge/stars-15-blue)
- [formjson](https://github.com/rs/formjson) - Transparently handle JSON input as a standard form POST. ![stars](https://img.shields.io/badge/stars-39-blue)
- [go-fault](https://github.com/github/go-fault) - Fault injection middleware for Go. ![stars](https://img.shields.io/badge/stars-510-blue)
- [go-server-timing](https://github.com/mitchellh/go-server-timing) - Add/parse Server-Timing header. ![stars](https://img.shields.io/badge/stars-861-blue)
- [Limiter](https://github.com/ulule/limiter) - Dead simple rate limit middleware for Go. ![stars](https://img.shields.io/badge/stars-2147-blue)
- [ln-paywall](https://github.com/philippgille/ln-paywall) - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin). ![stars](https://img.shields.io/badge/stars-151-blue)
- [mid](https://github.com/bobg/mid) - Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more. ![stars](https://img.shields.io/badge/stars-9-blue)
- [rk-gin](https://github.com/rookie-ninja/rk-gin) - Middleware for Gin framework with logging, metrics, auth, tracing etc. ![stars](https://img.shields.io/badge/stars-47-blue)
- [rk-grpc](https://github.com/rookie-ninja/rk-grpc) - Middleware for gRPC with logging, metrics, auth, tracing etc. ![stars](https://img.shields.io/badge/stars-75-blue)
- [Tollbooth](https://github.com/didip/tollbooth) - Rate limit HTTP request handler. ![stars](https://img.shields.io/badge/stars-2735-blue)
- [XFF](https://github.com/sebest/xff) - Handle `X-Forwarded-For` header and friends. ![stars](https://img.shields.io/badge/stars-98-blue)

#### Libraries for creating HTTP middlewares

- [alice](https://github.com/justinas/alice) - Painless middleware chaining for Go. ![stars](https://img.shields.io/badge/stars-3151-blue)
- [catena](https://github.com/codemodus/catena) - http.Handler wrapper catenation (same API as "chain"). ![stars](https://img.shields.io/badge/stars-9-blue)
- [chain](https://github.com/codemodus/chain) - Handler wrapper chaining with scoped data (net/context-based "middleware"). ![stars](https://img.shields.io/badge/stars-63-blue)
- [gores](https://github.com/alioygur/gores) - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs. ![stars](https://img.shields.io/badge/stars-104-blue)
- [interpose](https://github.com/carbocation/interpose) - Minimalist net/http middleware for golang. ![stars](https://img.shields.io/badge/stars-294-blue)
- [mediary](https://github.com/HereMobilityDevelopers/mediary) - add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses. ![stars](https://img.shields.io/badge/stars-88-blue)
- [muxchain](https://github.com/stephens2424/muxchain) - Lightweight middleware for net/http. ![stars](https://img.shields.io/badge/stars-207-blue)
- [negroni](https://github.com/urfave/negroni) - Idiomatic HTTP middleware for Golang. ![stars](https://img.shields.io/badge/stars-7481-blue)
- [render](https://github.com/unrolled/render) - Go package for easily rendering JSON, XML, and HTML template responses. ![stars](https://img.shields.io/badge/stars-1954-blue)
- [renderer](https://github.com/thedevsaddam/renderer) - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go. ![stars](https://img.shields.io/badge/stars-263-blue)
- [rye](https://github.com/InVisionApp/rye) - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context. ![stars](https://img.shields.io/badge/stars-102-blue)
- [stats](https://github.com/thoas/stats) - Go middleware that stores various information about your web application. ![stars](https://img.shields.io/badge/stars-594-blue)

**[⬆ back to top](#contents)**

### Routers

- [alien](https://github.com/gernest/alien) - Lightweight and fast http router from outer space. ![stars](https://img.shields.io/badge/stars-133-blue)
- [bellt](https://github.com/GuilhermeCaruso/bellt) - A simple Go HTTP router. ![stars](https://img.shields.io/badge/stars-54-blue)
- [Bone](https://github.com/go-zoo/bone) - Lightning Fast HTTP Multiplexer. ![stars](https://img.shields.io/badge/stars-1289-blue)
- [Bxog](https://github.com/claygod/Bxog) - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters. ![stars](https://img.shields.io/badge/stars-101-blue)
- [chi](https://github.com/go-chi/chi) - Small, fast and expressive HTTP router built on net/context. ![stars](https://img.shields.io/badge/stars-18941-blue)
- [fasthttprouter](https://github.com/buaazp/fasthttprouter) - High performance router forked from `httprouter`. The first router fit for `fasthttp`. ![stars](https://img.shields.io/badge/stars-870-blue)
- [FastRouter](https://github.com/razonyang/fastrouter) - a fast, flexible HTTP router written in Go. ![stars](https://img.shields.io/badge/stars-23-blue)
- [goblin](https://github.com/bmf-san/goblin) - A golang http router based on trie tree. ![stars](https://img.shields.io/badge/stars-79-blue)
- [gocraft/web](https://github.com/gocraft/web) - Mux and middleware package in Go. ![stars](https://img.shields.io/badge/stars-1510-blue)
- [Goji](https://github.com/goji/goji) - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`. ![stars](https://img.shields.io/badge/stars-970-blue)
- [GoLobby/Router](https://github.com/golobby/router) - GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language. ![stars](https://img.shields.io/badge/stars-22-blue)
- [goroute](https://github.com/goroute/route) - Simple yet powerful HTTP request multiplexer. ![stars](https://img.shields.io/badge/stars-9-blue)
- [GoRouter](https://github.com/vardius/gorouter) - GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`. ![stars](https://img.shields.io/badge/stars-155-blue)
- [gowww/router](https://github.com/gowww/router) - Lightning fast HTTP router fully compatible with the net/http.Handler interface. ![stars](https://img.shields.io/badge/stars-185-blue)
- [httprouter](https://github.com/julienschmidt/httprouter) - High performance router. Use this and the standard http handlers to form a very high performance web framework. ![stars](https://img.shields.io/badge/stars-16707-blue)
- [httptreemux](https://github.com/dimfeld/httptreemux) - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter. ![stars](https://img.shields.io/badge/stars-617-blue)
- [lars](https://github.com/go-playground/lars) - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks. ![stars](https://img.shields.io/badge/stars-385-blue)
- [mux](https://github.com/gorilla/mux) - Powerful URL router and dispatcher for golang. ![stars](https://img.shields.io/badge/stars-21046-blue)
- [nchi](https://github.com/muir/nchi) - chi-like router built on httprouter with dependency injection based middleware wrappers ![stars](https://img.shields.io/badge/stars-16-blue)
- [ngamux](https://github.com/ngamux/ngamux) - Simple HTTP router for Go. ![stars](https://img.shields.io/badge/stars-68-blue)
- [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs. ![stars](https://img.shields.io/badge/stars-454-blue)
- [pure](https://github.com/go-playground/pure) - Is a lightweight HTTP router that sticks to the std "net/http" implementation. ![stars](https://img.shields.io/badge/stars-150-blue)
- [Siesta](https://github.com/VividCortex/siesta) - Composable framework to write middleware and handlers. ![stars](https://img.shields.io/badge/stars-349-blue)
- [vestigo](https://github.com/husobee/vestigo) - Performant, stand-alone, HTTP compliant URL Router for go web applications. ![stars](https://img.shields.io/badge/stars-267-blue)
- [violetear](https://github.com/nbari/violetear) - Go HTTP router. ![stars](https://img.shields.io/badge/stars-107-blue)
- [xmux](https://github.com/rs/xmux) - High performance muxer based on `httprouter` with `net/context` support. ![stars](https://img.shields.io/badge/stars-99-blue)
- [xujiajun/gorouter](https://github.com/xujiajun/gorouter) - A simple and fast HTTP router for Go. ![stars](https://img.shields.io/badge/stars-532-blue)

**[⬆ back to top](#contents)**

## WebAssembly

- [dom](https://github.com/dennwc/dom) - DOM library. ![stars](https://img.shields.io/badge/stars-490-blue)
- [Extism Go SDK](https://github.com/extism/go-sdk) - Universal, cross-language WebAssembly framework for building plug-in systems and polyglot apps. ![stars](https://img.shields.io/badge/stars-97-blue)
- [go-canvas](https://github.com/markfarnan/go-canvas) - Library to use HTML5 Canvas, with all drawing within go code. ![stars](https://img.shields.io/badge/stars-248-blue)
- [tinygo](https://github.com/tinygo-org/tinygo) - Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM. ![stars](https://img.shields.io/badge/stars-15687-blue)
- [vert](https://github.com/norunners/vert) - Interop between Go and JS values. ![stars](https://img.shields.io/badge/stars-102-blue)
- [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) - Run Go WASM tests in your browser. ![stars](https://img.shields.io/badge/stars-194-blue)
- [webapi](https://github.com/gowebapi/webapi) - Bindings for DOM and HTML generated from WebIDL. ![stars](https://img.shields.io/badge/stars-176-blue)

**[⬆ back to top](#contents)**

## Webhooks Server

- [webhook](https://github.com/adnanh/webhook) - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server. ![stars](https://img.shields.io/badge/stars-10576-blue)
- [webhooked](https://github.com/42Atomys/webhooked) - A webhook receiver on steroids: handle, secure, format and store a Webhook payload has never been easier. ![stars](https://img.shields.io/badge/stars-37-blue)
- [WebhookX](https://github.com/webhookx-io/webhookx) - A webhooks gateway for message receiving, processing, and reliable delivering. ![stars](https://img.shields.io/badge/stars-129-blue)

**[⬆ back to top](#contents)**

## Windows

- [d3d9](https://github.com/gonutz/d3d9) - Go bindings for Direct3D9. ![stars](https://img.shields.io/badge/stars-160-blue)
- [go-ole](https://github.com/go-ole/go-ole) - Win32 OLE implementation for golang. ![stars](https://img.shields.io/badge/stars-1189-blue)
- [gosddl](https://github.com/MonaxGT/gosddl) - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL. ![stars](https://img.shields.io/badge/stars-11-blue)

**[⬆ back to top](#contents)**

## Workflow Frameworks

_Libraries for creating Workflows._
- [Cadence-client](https://github.com/uber-go/cadence-client) - A framework for authoring workflows and activities running on top of the Cadence orchestration engine made by Uber. ![stars](https://img.shields.io/badge/stars-352-blue)
- [Dagu](https://github.com/dagu-go/dagu) - No-code workflow executor. it executes DAGs defined in a simple YAML format. ![stars](https://img.shields.io/badge/stars-1778-blue)
- [go-dag](https://github.com/rhosocial/go-dag) - A framework developed in Go that manages the execution of workflows described by directed acyclic graphs. ![stars](https://img.shields.io/badge/stars-24-blue)
- [go-taskflow](https://github.com/noneback/go-taskflow) - A taskflow-like General-purpose Task-parallel Programming Framework with integrated visualizer and profiler. ![stars](https://img.shields.io/badge/stars-359-blue)
- [workflow](https://github.com/luno/workflow) - A tech stack agnostic Event Driven Workflow framework. ![stars](https://img.shields.io/badge/stars-128-blue)

**[⬆ back to top](#contents)**

## XML

_Libraries and tools for manipulating XML._

- [XML-Comp](https://github.com/xml-comp/xml-comp) - Simple command line XML comparer that generates diffs of folders, files and tags. ![stars](https://img.shields.io/badge/stars-21-blue)
- [xml2map](https://github.com/sbabiv/xml2map) - XML to MAP converter written Golang. ![stars](https://img.shields.io/badge/stars-62-blue)
- [xmlwriter](https://github.com/shabbyrobe/xmlwriter) - Procedural XML generation API based on libxml2's xmlwriter module. ![stars](https://img.shields.io/badge/stars-28-blue)
- [xpath](https://github.com/antchfx/xpath) - XPath package for Go. ![stars](https://img.shields.io/badge/stars-697-blue)
- [xquery](https://github.com/antchfx/xquery) - XQuery lets you extract data from HTML/XML documents using XPath expression. ![stars](https://img.shields.io/badge/stars-158-blue)
- [zek](https://github.com/miku/zek) - Generate a Go struct from XML. ![stars](https://img.shields.io/badge/stars-760-blue)

## Zero Trust

_Libraries and tools to implement Zero Trust architectures._

- [Cosign](https://github.com/sigstore/cosign) - Container Signing, Verification and Storage in an OCI registry. ![stars](https://img.shields.io/badge/stars-4640-blue)
- [in-toto](https://github.com/in-toto/in-toto-golang) - Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation. ![stars](https://img.shields.io/badge/stars-133-blue)
- [OpenZiti](https://github.com/openziti/ziti) - A full, open source zero trust overlay network. Including numerous SDKs for numerous languages such as [golang](https://github.com/openziti/sdk-golang) allowing you to embed zero trust principles directly into your applications. The [OpenZiti Test Kitchen](https://github.com/openziti-test-kitchen) has numerous examples to draw inspiration from including a [zero trust ssh client - zssh](https://github.com/openziti-test-kitchen/zssh) ![stars](https://img.shields.io/badge/stars-2978-blue)
- [Spiffe-Vault](https://github.com/philips-labs/spiffe-vault) - Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication. ![stars](https://img.shields.io/badge/stars-85-blue)
- [Spire](https://github.com/spiffe/spire) - SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms. ![stars](https://img.shields.io/badge/stars-1841-blue)

## Code Analysis

_Source code analysis tools, also known as Static Application Security Testing (SAST) Tools._

- [apicompat](https://github.com/bradleyfalzon/apicompat) - Checks recent changes to a Go project for backwards incompatible changes. ![stars](https://img.shields.io/badge/stars-178-blue)
- [asty](https://github.com/asty-org/asty) - Converts golang AST to JSON and JSON to AST. ![stars](https://img.shields.io/badge/stars-82-blue)
- [blanket](https://gitlab.com/verygoodsoftwarenotvirus/blanket) - blanket is a tool that helps you catch functions which don't have direct unit tests in your Go packages.
- [ChainJacking](https://github.com/Checkmarx/chainjacking) - Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack. ![stars](https://img.shields.io/badge/stars-56-blue)
- [Chronos](https://github.com/amit-davidson/Chronos) - Detects race conditions statically ![stars](https://img.shields.io/badge/stars-429-blue)
- [dupl](https://github.com/mibk/dupl) - Tool for code clone detection. ![stars](https://img.shields.io/badge/stars-347-blue)
- [errcheck](https://github.com/kisielk/errcheck) - Errcheck is a program for checking for unchecked errors in Go programs. ![stars](https://img.shields.io/badge/stars-2369-blue)
- [fatcontext](https://github.com/Crocmagnon/fatcontext) - Fatcontext detects nested contexts in loops or function literals. ![stars](https://img.shields.io/badge/stars-15-blue)
- [gcvis](https://github.com/davecheney/gcvis) - Visualise Go program GC trace data in real time. ![stars](https://img.shields.io/badge/stars-1102-blue)
- [go-checkstyle](https://github.com/qiniu/checkstyle) - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments. ![stars](https://img.shields.io/badge/stars-130-blue)
- [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects. ![stars](https://img.shields.io/badge/stars-898-blue)
- [go-critic](https://github.com/go-critic/go-critic) - source code linter that brings checks that are currently not implemented in other linters. ![stars](https://img.shields.io/badge/stars-1888-blue)
- [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) - An easy way to find outdated dependencies of your Go projects. ![stars](https://img.shields.io/badge/stars-653-blue)
- [goast-viewer](https://github.com/yuroyoro/goast-viewer) - Web based Golang AST visualizer. ![stars](https://img.shields.io/badge/stars-773-blue)
- [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
- [golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) - iFood API SDK. ![stars](https://img.shields.io/badge/stars-12-blue)
- [golangci-lint](https://github.com/golangci/golangci-lint) – A fast Go linters runner. It runs linters in parallel, uses caching, supports `yaml` config, has integrations with all major IDE and has dozens of linters included. ![stars](https://img.shields.io/badge/stars-16020-blue)
- [golines](https://github.com/segmentio/golines) - Formatter that automatically shortens long lines in Go code. ![stars](https://img.shields.io/badge/stars-967-blue)
- [GoPlantUML](https://github.com/jfeliu007/goplantuml) - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them. ![stars](https://img.shields.io/badge/stars-1908-blue)
- [goreturns](https://github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types. ![stars](https://img.shields.io/badge/stars-531-blue)
- [gostatus](https://github.com/shurcooL/gostatus) - Command line tool, shows the status of repositories that contain Go packages. ![stars](https://img.shields.io/badge/stars-243-blue)
- [lint](https://github.com/surullabs/lint) - Run linters as part of go test. ![stars](https://img.shields.io/badge/stars-67-blue)
- [php-parser](https://github.com/z7zmey/php-parser) - A Parser for PHP written in Go. ![stars](https://img.shields.io/badge/stars-942-blue)
- [revive](https://github.com/mgechev/revive) – ~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for `golint`. ![stars](https://img.shields.io/badge/stars-4861-blue)
- [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#. ![stars](https://img.shields.io/badge/stars-6281-blue)
- [testifylint](https://github.com/Antonboom/testifylint) – A linter that checks usage of [github.com/stretchr/testify](https://github.com/stretchr/testify). ![stars](https://img.shields.io/badge/stars-114-blue)
- [tickgit](https://github.com/augmentable-dev/tickgit) - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author. ![stars](https://img.shields.io/badge/stars-324-blue)
- [todocheck](https://github.com/preslavmihaylov/todocheck) - Static code analyser which links TODO comments in code with issues in your issue tracker. ![stars](https://img.shields.io/badge/stars-429-blue)
- [unconvert](https://github.com/mdempsky/unconvert) - Remove unnecessary type conversions from Go source. ![stars](https://img.shields.io/badge/stars-382-blue)
- [usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) - A linter that detect the possibility to use variables/constants from the Go standard library. ![stars](https://img.shields.io/badge/stars-44-blue)
- [vacuum](https://github.com/daveshanley/vacuum) - An ultra-super-fast, lightweight OpenAPI linter and quality checking tool. ![stars](https://img.shields.io/badge/stars-670-blue)
- [validate](https://github.com/mccoyst/validate) - Automatically validates struct fields with tags. ![stars](https://img.shields.io/badge/stars-61-blue)
- [wrapcheck](https://github.com/tomarrell/wrapcheck) - A linter to check that errors from external packages are wrapped. ![stars](https://img.shields.io/badge/stars-312-blue)

**[⬆ back to top](#contents)**

## Editor Plugins

_Plugin for text editors and IDEs._

- [coc-go language server extension for Vim/Neovim](https://github.com/josa42/coc-go) - This plugin adds [gopls](https://github.com/golang/tools/blob/master/gopls/README.md) features to Vim/Neovim. ![stars](https://img.shields.io/badge/stars-567-blue)
- [Go Doc](https://github.com/msyrus/vscode-go-doc) - A Visual Studio Code extension for showing definition in output and generating go doc. ![stars](https://img.shields.io/badge/stars-8-blue)
- [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
- [go-language-server](https://github.com/theia-ide/go-language-server) - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol. ![stars](https://img.shields.io/badge/stars-32-blue)
- [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs. ![stars](https://img.shields.io/badge/stars-1395-blue)
- [go-plus](https://github.com/joefitzgerald/go-plus) - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting. ![stars](https://img.shields.io/badge/stars-1508-blue)
- [gocode](https://github.com/nsf/gocode) - Autocompletion daemon for the Go programming language. ![stars](https://img.shields.io/badge/stars-5012-blue)
- [goimports-reviser](https://github.com/incu6us/goimports-reviser) - Formatting tool for imports. ![stars](https://img.shields.io/badge/stars-621-blue)
- [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
- [GoSublime](https://github.com/DisposaBoy/GoSublime) - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features. ![stars](https://img.shields.io/badge/stars-3419-blue)
- [gounit-vim](https://github.com/hexdigest/gounit-vim) - Vim plugin for generating Go tests based on the function's or method's signature. ![stars](https://img.shields.io/badge/stars-24-blue)
- [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) - Vim plugin to highlight syntax errors on save. ![stars](https://img.shields.io/badge/stars-89-blue)
- [vim-go](https://github.com/fatih/vim-go) - Go development plugin for Vim. ![stars](https://img.shields.io/badge/stars-16058-blue)
- [vscode-go](https://github.com/golang/vscode-go) - Extension for Visual Studio Code (VS Code) which provides support for the Go language. ![stars](https://img.shields.io/badge/stars-3942-blue)
- [Watch](https://github.com/eaburns/Watch) - Runs a command in an acme win on file changes. ![stars](https://img.shields.io/badge/stars-202-blue)

**[⬆ back to top](#contents)**

## Go Generate Tools

- [envdoc](https://github.com/g4s8/envdoc) -  generate documentation for environment variables from Go source files. ![stars](https://img.shields.io/badge/stars-71-blue)
- [generic](https://github.com/usk81/generic) - flexible data type for Go. ![stars](https://img.shields.io/badge/stars-48-blue)
- [genny](https://github.com/cheekybits/genny) - Elegant generics for Go. ![stars](https://img.shields.io/badge/stars-1713-blue)
- [gocontracts](https://github.com/Parquery/gocontracts) - brings design-by-contract to Go by synchronizing the code with the documentation. ![stars](https://img.shields.io/badge/stars-113-blue)
- [godal](https://github.com/mafulong/godal) - Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm. ![stars](https://img.shields.io/badge/stars-18-blue)
- [gonerics](https://github.com/bouk/gonerics) - Idiomatic Generics in Go. ![stars](https://img.shields.io/badge/stars-114-blue)
- [gotests](https://github.com/cweill/gotests) - Generate Go tests from your source code. ![stars](https://img.shields.io/badge/stars-4992-blue)
- [gounit](https://github.com/hexdigest/gounit) - Generate Go tests using your own templates. ![stars](https://img.shields.io/badge/stars-81-blue)
- [hasgo](https://github.com/DylanMeeus/hasgo) - Generate Haskell inspired functions for your slices. ![stars](https://img.shields.io/badge/stars-141-blue)
- [options-gen](https://github.com/kazhuravlev/options-gen) - Functional options described by Dave Cheney's post "Functional options for friendly APIs". ![stars](https://img.shields.io/badge/stars-82-blue)
- [re2dfa](https://gitlab.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.
- [sqlgen](https://github.com/anqiansong/sqlgen) - Generate gorm, xorm, sqlx, bun, sql code from SQL file or DSN. ![stars](https://img.shields.io/badge/stars-84-blue)
- [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.
- [xgen](https://github.com/xuri/xgen) - XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator. ![stars](https://img.shields.io/badge/stars-346-blue)

**[⬆ back to top](#contents)**

## Go Tools

- [colorgo](https://github.com/songgao/colorgo) - Wrapper around `go` command for colorized `go build` output. ![stars](https://img.shields.io/badge/stars-113-blue)
- [decouple](https://github.com/bobg/decouple) - Find “overspecified” function parameters that could be generalized with interface types. ![stars](https://img.shields.io/badge/stars-24-blue)
- [depth](https://github.com/KyleBanks/depth) - Visualize dependency trees of any package by analyzing imports. ![stars](https://img.shields.io/badge/stars-956-blue)
- [docs](https://github.com/go-oas/docs) - Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard. ![stars](https://img.shields.io/badge/stars-43-blue)
- [go-callvis](https://github.com/TrueFurby/go-callvis) - Visualize call graph of your Go program using dot format. ![stars](https://img.shields.io/badge/stars-6042-blue)
- [go-size-analyzer](https://github.com/Zxilly/go-size-analyzer) - Analyze and visualize the size of dependencies in compiled Golang binaries, providing insight into their impact on the final build. ![stars](https://img.shields.io/badge/stars-1385-blue)
- [go-swagger](https://github.com/go-swagger/go-swagger) - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API. ![stars](https://img.shields.io/badge/stars-9611-blue)
- [godbg](https://github.com/tylerwince/godbg) - Implementation of Rusts `dbg!` macro for quick and easy debugging during development. ![stars](https://img.shields.io/badge/stars-204-blue)
- [gomodrun](https://github.com/dustinblackman/gomodrun/) - Go tool that executes and caches binaries included in go.mod files. ![stars](https://img.shields.io/badge/stars-36-blue)
- [gotemplate.io](https://gotemplate.io/) - Online tool to preview `text/template` templates live.
- [gotestdox](https://github.com/bitfield/gotestdox) - Show Go test results as readable sentences. ![stars](https://img.shields.io/badge/stars-126-blue)
- [gothanks](https://github.com/psampaz/gothanks) - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers. ![stars](https://img.shields.io/badge/stars-125-blue)
- [igo](https://github.com/rocketlaunchr/igo) - An igo to go transpiler (new language features for Go language!) ![stars](https://img.shields.io/badge/stars-66-blue)
- [modver](https://github.com/bobg/modver) - Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules. ![stars](https://img.shields.io/badge/stars-19-blue)
- [MoniGO](https://github.com/iyashjayesh/monigo) - A performance monitoring library for Go applications. It provides real-time insights into application performance! 🚀  ![stars](https://img.shields.io/badge/stars-248-blue)
- [OctoLinker](https://github.com/OctoLinker/browser-extension) - Navigate through go files efficiently with the OctoLinker browser extension for GitHub. ![stars](https://img.shields.io/badge/stars-5289-blue)
- [richgo](https://github.com/kyoh86/richgo) - Enrich `go test` outputs with text decorations. ![stars](https://img.shields.io/badge/stars-853-blue)
- [roumon](https://github.com/becheran/roumon) - Monitor current state of all active goroutines via a command line interface. ![stars](https://img.shields.io/badge/stars-189-blue)
- [rts](https://github.com/galeone/rts) - RTS: response to struct. Generates Go structs from server responses. ![stars](https://img.shields.io/badge/stars-248-blue)
- [textra](https://github.com/ravsii/textra) - Extract Go struct field names, types and tags for filtering and exporting. ![stars](https://img.shields.io/badge/stars-6-blue)
- [typex](https://github.com/dtgorski/typex) - Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration. ![stars](https://img.shields.io/badge/stars-205-blue)


**[⬆ back to top](#contents)**

## Software Packages

_Software written in Go._

**[⬆ back to top](#contents)**

### DevOps Tools

- [abbreviate](https://github.com/dnnrly/abbreviate) - abbreviate is a tool turning long strings in to shorter ones with configurable separators, for example to embed branch names in to deployment stack IDs. ![stars](https://img.shields.io/badge/stars-220-blue)
- [alaz](https://github.com/ddosify/alaz) - Effortless, Low-Overhead, eBPF-based Kubernetes Monitoring. ![stars](https://img.shields.io/badge/stars-666-blue)
- [aptly](https://github.com/smira/aptly) - aptly is a Debian repository management tool. ![stars](https://img.shields.io/badge/stars-13-blue)
- [aurora](https://github.com/xuri/aurora) - Cross-platform web-based Beanstalkd queue server console. ![stars](https://img.shields.io/badge/stars-600-blue)
- [awsenv](https://github.com/soniah/awsenv) - Small binary that loads Amazon (AWS) environment variables for a profile. ![stars](https://img.shields.io/badge/stars-35-blue)
- [Balerter](https://github.com/balerter/balerter) - A self-hosted script-based alerting manager. ![stars](https://img.shields.io/badge/stars-301-blue)
- [Blast](https://github.com/dave/blast) - A simple tool for API load testing and batch jobs. ![stars](https://img.shields.io/badge/stars-218-blue)
- [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool. ![stars](https://img.shields.io/badge/stars-6123-blue)
- [bosun](https://github.com/bosun-monitor/bosun) - Time Series Alerting Framework. ![stars](https://img.shields.io/badge/stars-3408-blue)
- [cassowary](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in Go. ![stars](https://img.shields.io/badge/stars-777-blue)
- [Ddosify](https://github.com/ddosify/ddosify) - High-performance load testing tool, written in Golang. ![stars](https://img.shields.io/badge/stars-8448-blue)
- [decompose](https://github.com/s0rg/decompose) - tool to generate and process Docker containers connections graphs. ![stars](https://img.shields.io/badge/stars-89-blue)
- [DepCharge](https://github.com/centerorbit/depcharge) - Helps orchestrating the execution of commands across the many dependencies in larger projects. ![stars](https://img.shields.io/badge/stars-23-blue)
- [Docker](https://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
- [docker-go-mingw](https://github.com/x1unix/docker-go-mingw) - Docker image for building Go binaries for Windows with MinGW toolchain. ![stars](https://img.shields.io/badge/stars-47-blue)
- [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) - A go library and an executable that produces valid Dockerfiles using various input channels. ![stars](https://img.shields.io/badge/stars-173-blue)
- [dogo](https://github.com/liudng/dogo) - Monitoring changes in the source file and automatically compile and run (restart). ![stars](https://img.shields.io/badge/stars-269-blue)
- [drone-jenkins](https://github.com/appleboy/drone-jenkins) - Trigger downstream Jenkins jobs using a binary, docker or Drone CI. ![stars](https://img.shields.io/badge/stars-39-blue)
- [drone-scp](https://github.com/appleboy/drone-scp) - Copy files and artifacts via SSH using a binary, docker or Drone CI. ![stars](https://img.shields.io/badge/stars-144-blue)
- [Dropship](https://github.com/chrismckenzie/dropship) - Tool for deploying code via cdn. ![stars](https://img.shields.io/badge/stars-65-blue)
- [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`. ![stars](https://img.shields.io/badge/stars-326-blue)
- [fac](https://github.com/mkchoi212/fac) - Command-line user interface to fix git merge conflicts. ![stars](https://img.shields.io/badge/stars-1847-blue)
- [Flannel](https://github.com/flannel-io/flannel) - Flannel is a network fabric for containers, designed for Kubernetes. ![stars](https://img.shields.io/badge/stars-8907-blue)
- [Fleet device management](https://github.com/fleetdm/fleet) - Lightweight, programmable telemetry for servers and workstations. ![stars](https://img.shields.io/badge/stars-3269-blue)
- [gaia](https://github.com/gaia-pipeline/gaia) - Build powerful pipelines in any programming language. ![stars](https://img.shields.io/badge/stars-5204-blue)
- [ghorg](https://github.com/gabrie30/ghorg) - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket. ![stars](https://img.shields.io/badge/stars-1616-blue)
- [Gitea](https://github.com/go-gitea/gitea) - Fork of Gogs, entirely community driven. ![stars](https://img.shields.io/badge/stars-46583-blue)
- [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
- [go-furnace](https://github.com/go-furnace/go-furnace) - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean. ![stars](https://img.shields.io/badge/stars-98-blue)
- [go-rocket-update](https://github.com/mouuff/go-rocket-update) - A simple way to make self updating Go applications - Supports Github and Gitlab. ![stars](https://img.shields.io/badge/stars-105-blue)
- [go-selfupdate](https://github.com/sanbornm/go-selfupdate) - Enable your Go applications to self update. ![stars](https://img.shields.io/badge/stars-1555-blue)
- [gobrew](https://github.com/cryptojuice/gobrew) - gobrew lets you easily switch between multiple versions of go. ![stars](https://img.shields.io/badge/stars-192-blue)
- [gobrew](https://github.com/kevincobain2000/gobrew) - Go version manager. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash. ![stars](https://img.shields.io/badge/stars-385-blue)
- [godbg](https://github.com/sirnewton01/godbg) - Web-based gdb front-end application. ![stars](https://img.shields.io/badge/stars-228-blue)
- [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
- [gonative](https://github.com/inconshreveable/gonative) - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages. ![stars](https://img.shields.io/badge/stars-338-blue)
- [govvv](https://github.com/ahmetalpbalkan/govvv) - “go build” wrapper to easily add version information into Go binaries. ![stars](https://img.shields.io/badge/stars-539-blue)
- [gox](https://github.com/mitchellh/gox) - Dead simple, no frills Go cross compile tool. ![stars](https://img.shields.io/badge/stars-4607-blue)
- [grapes](https://github.com/yaronsumel/grapes) - Lightweight tool designed to distribute commands over ssh with ease. ![stars](https://img.shields.io/badge/stars-170-blue)
- [GVM](https://github.com/moovweb/gvm) - GVM provides an interface to manage Go versions. ![stars](https://img.shields.io/badge/stars-10507-blue)
- [Hey](https://github.com/rakyll/hey) - Hey is a tiny program that sends some load to a web application. ![stars](https://img.shields.io/badge/stars-18404-blue)
- [httpref](https://github.com/dnnrly/httpref) - httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports. ![stars](https://img.shields.io/badge/stars-39-blue)
- [jcli](https://github.com/jenkins-zh/jenkins-cli) - Jenkins CLI allows you manage your Jenkins as an easy way. ![stars](https://img.shields.io/badge/stars-396-blue)
- [k3d](https://github.com/k3d-io/k3d) - Little helper to run CNCF's k3s in Docker. ![stars](https://img.shields.io/badge/stars-5563-blue)
- [k3s](https://github.com/k3s-io/k3s) - Lightweight Kubernetes. ![stars](https://img.shields.io/badge/stars-28552-blue)
- [k6](https://github.com/grafana/k6) - A modern load testing tool, using Go and JavaScript. ![stars](https://img.shields.io/badge/stars-26488-blue)
- [kala](https://github.com/ajvb/kala) - Simplistic, modern, and performant job scheduler. ![stars](https://img.shields.io/badge/stars-2144-blue)
- [kcli](https://github.com/cswank/kcli) - Command line tool for inspecting kafka topics/partitions/messages. ![stars](https://img.shields.io/badge/stars-216-blue)
- [kind](https://github.com/kubernetes-sigs/kind) - Kubernetes IN Docker - local clusters for testing Kubernetes. ![stars](https://img.shields.io/badge/stars-13711-blue)
- [ko](https://github.com/google/ko) - Command line tool for building and deploying Go applications on Kubernetes ![stars](https://img.shields.io/badge/stars-7759-blue)
- [kool](https://github.com/kool-dev/kool) - Command line tool for managing Docker environments as an easy way. ![stars](https://img.shields.io/badge/stars-670-blue)
- [kubeblocks](https://github.com/apecloud/kubeblocks) - KubeBlocks is an open-source control plane that runs and manages databases, message queues and other data infrastructure on K8s. ![stars](https://img.shields.io/badge/stars-2328-blue)
- [kubernetes](https://github.com/kubernetes/kubernetes) - Container Cluster Manager from Google. ![stars](https://img.shields.io/badge/stars-112354-blue)
- [kubeshark](https://github.com/kubeshark/kubeshark) - API traffic analyzer for Kubernetes, inspired by Wireshark, purposely built for Kubernetes. ![stars](https://img.shields.io/badge/stars-11152-blue)
- [KubeVela](https://github.com/kubevela/kubevela) - Cloud native application delivery. ![stars](https://img.shields.io/badge/stars-6516-blue)
- [KubeVPN](https://github.com/kubenetworks/kubevpn) - KubeVPN offers a Cloud-Native Dev Environment that seamlessly connects to your Kubernetes cluster network. ![stars](https://img.shields.io/badge/stars-593-blue)
- [KusionStack](https://github.com/KusionStack/kusion) - A unified programmable configuration techstack to deliver modern app in 'platform as code' and 'infra as code' approach. ![stars](https://img.shields.io/badge/stars-959-blue)
- [kwatch](https://github.com/abahmed/kwatch) - Monitor & detect crashes in your Kubernetes(K8s) cluster instantly. ![stars](https://img.shields.io/badge/stars-967-blue)
- [lstags](https://github.com/ivanilves/lstags) - Tool and API to sync Docker images across different registries. ![stars](https://img.shields.io/badge/stars-335-blue)
- [lwc](https://github.com/timdp/lwc) - A live-updating version of the UNIX wc command. ![stars](https://img.shields.io/badge/stars-32-blue)
- [manssh](https://github.com/xwjdsh/manssh) - manssh is a command line tool for managing your ssh alias config easily. ![stars](https://img.shields.io/badge/stars-299-blue)
- [Mantil](https://github.com/mantil-io/mantil) - Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure. ![stars](https://img.shields.io/badge/stars-110-blue)
- [minikube](https://github.com/kubernetes/minikube) - Run Kubernetes locally. ![stars](https://img.shields.io/badge/stars-29757-blue)
- [Moby](https://github.com/moby/moby) - Collaborative project for the container ecosystem to assemble container-based systems. ![stars](https://img.shields.io/badge/stars-68997-blue)
- [Mora](https://github.com/emicklei/mora) - REST server for accessing MongoDB documents and meta data. ![stars](https://img.shields.io/badge/stars-316-blue)
- [ostent](https://github.com/ostrost/ostent) - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB. ![stars](https://img.shields.io/badge/stars-180-blue)
- [Packer](https://github.com/mitchellh/packer) - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration. ![stars](https://img.shields.io/badge/stars-15185-blue)
- [Pewpew](https://github.com/bengadbois/pewpew) - Flexible HTTP command line stress tester. ![stars](https://img.shields.io/badge/stars-424-blue)
- [PipeCD](https://github.com/pipe-cd/pipecd) - A GitOps-style continuous delivery platform that provides consistent deployment and operations experience for any applications. ![stars](https://img.shields.io/badge/stars-1109-blue)
- [podinfo](https://github.com/stefanprodan/podinfo) - Podinfo is a tiny web application made with Go that showcases best practices of running microservices in Kubernetes. Podinfo is used by CNCF projects like Flux and Flagger for end-to-end testing and workshops. ![stars](https://img.shields.io/badge/stars-5481-blue)
- [Pomerium](https://github.com/pomerium/pomerium) - Pomerium is an identity-aware access proxy. ![stars](https://img.shields.io/badge/stars-4107-blue)
- [Rodent](https://github.com/alouche/rodent) - Rodent helps you manage Go versions, projects and track dependencies. ![stars](https://img.shields.io/badge/stars-34-blue)
- [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) - S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth). ![stars](https://img.shields.io/badge/stars-314-blue)
- [s3gof3r](https://github.com/rlmcpherson/s3gof3r) - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3. ![stars](https://img.shields.io/badge/stars-1143-blue)
- [s5cmd](https://github.com/peak/s5cmd) - Blazing fast S3 and local filesystem execution tool. ![stars](https://img.shields.io/badge/stars-2812-blue)
- [Scaleway-cli](https://github.com/scaleway/scaleway-cli) - Manage BareMetal Servers from Command Line (as easily as with Docker). ![stars](https://img.shields.io/badge/stars-891-blue)
- [script](https://github.com/bitfield/script) - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks. ![stars](https://img.shields.io/badge/stars-5783-blue)
- [sg](https://github.com/ChristopherRabotin/sg) - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response. ![stars](https://img.shields.io/badge/stars-8-blue)
- [skm](https://github.com/TimothyYe/skm) - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily! ![stars](https://img.shields.io/badge/stars-960-blue)
- [StatusOK](https://github.com/sanathp/statusok) - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected. ![stars](https://img.shields.io/badge/stars-1626-blue)
- [tau](https://github.com/taubyte/tau) - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, CI/CD, Object Storage, K/V Database, and Pub-Sub Messaging. ![stars](https://img.shields.io/badge/stars-3673-blue)
- [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed. ![stars](https://img.shields.io/badge/stars-275-blue)
- [tf-profile](https://github.com/datarootsio/tf-profile) - Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations. ![stars](https://img.shields.io/badge/stars-156-blue)
- [tlm](https://github.com/yusufcanb/tlm) - Local cli copilot, powered by CodeLLaMa ![stars](https://img.shields.io/badge/stars-1320-blue)
- [traefik](https://github.com/containous/traefik) - Reverse proxy and load balancer with support for multiple backends. ![stars](https://img.shields.io/badge/stars-52685-blue)
- [trubka](https://github.com/xitonix/trubka) - A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka. ![stars](https://img.shields.io/badge/stars-332-blue)
- [uTask](https://github.com/ovh/utask) - Automation engine that models and executes business processes declared in yaml. ![stars](https://img.shields.io/badge/stars-1227-blue)
- [Vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library. It's over 9000! ![stars](https://img.shields.io/badge/stars-23806-blue)
- [wait-for](https://github.com/dnnrly/wait-for) - Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things. ![stars](https://img.shields.io/badge/stars-17-blue)
- [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
- [winrm-cli](https://github.com/masterzen/winrm-cli) - Cli tool to remotely execute commands on Windows machines. ![stars](https://img.shields.io/badge/stars-163-blue)

**[⬆ back to top](#contents)**

### Other Software

- [Better Go Playground](https://goplay.tools) - Go playground with syntax highlight, code completion and other features.
- [blocky](https://github.com/0xERR0R/blocky) - Fast and lightweight DNS proxy as ad-blocker for local network with many features. ![stars](https://img.shields.io/badge/stars-4936-blue)
- [borg](https://github.com/crufter/borg) - Terminal based search engine for bash snippets. ![stars](https://img.shields.io/badge/stars-1606-blue)
- [boxed](https://github.com/tejo/boxed) - Dropbox based blog engine. ![stars](https://img.shields.io/badge/stars-79-blue)
- [Chapar](https://github.com/chapar-rest/chapar) - Chapar is a a cross-platform Postman alternative built with go, aims to help developers to test their api endpoints. it support http and grpc protocols. ![stars](https://img.shields.io/badge/stars-508-blue)
- [Cherry](https://github.com/rafael-santiago/cherry) - Tiny webchat server in Go. ![stars](https://img.shields.io/badge/stars-301-blue)
- [Circuit](https://github.com/gocircuit/circuit) - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications. ![stars](https://img.shields.io/badge/stars-1984-blue)
- [Comcast](https://github.com/tylertreat/Comcast) - Simulate bad network connections. ![stars](https://img.shields.io/badge/stars-10331-blue)
- [confd](https://github.com/kelseyhightower/confd) - Manage local application configuration files using templates and data from etcd or consul. ![stars](https://img.shields.io/badge/stars-8371-blue)
- [crawley](https://github.com/s0rg/crawley) - Web scraper/crawler for cli. ![stars](https://img.shields.io/badge/stars-273-blue)
- [croc](https://github.com/schollz/croc) - Easily and securely send files or folders from one computer to another. ![stars](https://img.shields.io/badge/stars-28537-blue)
- [Documize](https://github.com/documize/community) - Modern wiki software that integrates data from SaaS tools. ![stars](https://img.shields.io/badge/stars-2184-blue)
- [dp](https://github.com/scryinfo/dp) - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development. ![stars](https://img.shields.io/badge/stars-80-blue)
- [drive](https://github.com/odeke-em/drive) - Google Drive client for the commandline. ![stars](https://img.shields.io/badge/stars-6700-blue)
- [Duplicacy](https://github.com/gilbertchen/duplicacy) - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication. ![stars](https://img.shields.io/badge/stars-5310-blue)
- [fjira](https://github.com/mk-5/fjira) - A fuzzy-search based terminal UI application for Attlasian Jira ![stars](https://img.shields.io/badge/stars-155-blue)
- [Gebug](https://github.com/moshebe/gebug) - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly. ![stars](https://img.shields.io/badge/stars-635-blue)
- [gfile](https://github.com/Antonito/gfile) - Securely transfer files between two computers, without any third party, over WebRTC. ![stars](https://img.shields.io/badge/stars-745-blue)
- [Go Package Store](https://github.com/shurcooL/Go-Package-Store) - App that displays updates for the Go packages in your GOPATH. ![stars](https://img.shields.io/badge/stars-897-blue)
- [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) - Video streaming torrent client. ![stars](https://img.shields.io/badge/stars-473-blue)
- [goblin](https://goblin.reaper.im) - Golang binaries in a curl, built by goblins.
- [GoBoy](https://github.com/Humpheh/goboy) - Nintendo Game Boy Color emulator written in Go. ![stars](https://img.shields.io/badge/stars-2615-blue)
- [gocc](https://github.com/goccmack/gocc) - Gocc is a compiler kit for Go written in Go. ![stars](https://img.shields.io/badge/stars-622-blue)
- [GoDocTooltip](https://github.com/diankong/GoDocTooltip) - Chrome extension for Go Doc sites, which shows function description as tooltip at function list. ![stars](https://img.shields.io/badge/stars-13-blue)
- [Gokapi](https://github.com/Forceu/gokapi) - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to Firefox Send, but without public upload. ![stars](https://img.shields.io/badge/stars-1757-blue)
- [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
- [GoNB](https://github.com/janpfeifer/gonb) - Interactive Go programming with Jupyter Notebooks (also works in VSCode, Binder and Google's Colab). ![stars](https://img.shields.io/badge/stars-749-blue)
- [Gor](https://github.com/buger/gor) - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time. ![stars](https://img.shields.io/badge/stars-18741-blue)
- [Guora](https://github.com/meloalright/guora) - A self-hosted Quora like web application written in Go. ![stars](https://img.shields.io/badge/stars-676-blue)
- [hoofli](https://github.com/dnnrly/hoofli) - Generate PlantUML diagrams from Chrome or Firefox network inspections. ![stars](https://img.shields.io/badge/stars-9-blue)
- [hotswap](https://github.com/edwingeng/hotswap) - A complete solution to reload your go code without restarting your server, interrupting or blocking any ongoing procedure. ![stars](https://img.shields.io/badge/stars-371-blue)
- [hugo](https://gohugo.io/) - Fast and Modern Static Website Engine.
- [ide](https://github.com/thestrukture/ide) - Browser accessible IDE. Designed for Go with Go. ![stars](https://img.shields.io/badge/stars-360-blue)
- [ipe](https://github.com/dimiro1/ipe) - Open source Pusher server implementation compatible with Pusher client libraries written in GO. ![stars](https://img.shields.io/badge/stars-365-blue)
- [joincap](https://github.com/assafmo/joincap) - Command-line utility for merging multiple pcap files together. ![stars](https://img.shields.io/badge/stars-213-blue)
- [JuiceFS](https://github.com/juicedata/juicefs) - Distributed POSIX file system built on top of Redis and AWS S3. ![stars](https://img.shields.io/badge/stars-11152-blue)
- [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
- [Layli](https://layli.app) - Draw pretty layout diagrams as code.
- [Leaps](https://github.com/jeffail/leaps) - Pair programming service using Operational Transforms. ![stars](https://img.shields.io/badge/stars-752-blue)
- [lgo](https://github.com/yunabe/lgo) - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility. ![stars](https://img.shields.io/badge/stars-2441-blue)
- [limetext](https://limetext.github.io) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
- [LiteIDE](https://github.com/visualfc/liteide) - LiteIDE is a simple, open source, cross-platform Go IDE. ![stars](https://img.shields.io/badge/stars-7638-blue)
- [mockingjay](https://github.com/quii/mockingjay-server) - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests. ![stars](https://img.shields.io/badge/stars-562-blue)
- [myLG](https://github.com/mehrdadrad/mylg) - Command Line Network Diagnostic tool written in Go. ![stars](https://img.shields.io/badge/stars-2700-blue)
- [naclpipe](https://github.com/unix4fun/naclpipe) - Simple NaCL EC25519 based crypto pipe tool written in Go. ![stars](https://img.shields.io/badge/stars-23-blue)
- [Neo-cowsay](https://github.com/Code-Hex/Neo-cowsay) - 🐮 cowsay is reborn. for a New Era. ![stars](https://img.shields.io/badge/stars-319-blue)
- [nes](https://github.com/fogleman/nes) - Nintendo Entertainment System (NES) emulator written in Go. ![stars](https://img.shields.io/badge/stars-5485-blue)
- [Orbit](https://github.com/gulien/orbit) - A simple tool for running commands and generating files from templates. ![stars](https://img.shields.io/badge/stars-185-blue)
- [peg](https://github.com/pointlander/peg) - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator. ![stars](https://img.shields.io/badge/stars-1034-blue)
- [Plik](https://github.com/root-gg/plik) - Plik is a temporary file upload system (Wetransfer like) in Go. ![stars](https://img.shields.io/badge/stars-1506-blue)
- [portal](https://github.com/SpatiumPortae/portal) - Portal is a quick and easy command-line file transfer utility from any computer to another. ![stars](https://img.shields.io/badge/stars-1539-blue)
- [protoncheck](https://github.com/servusdei2018/protoncheck) - ProtonMail module for waybar/polybar/yabar/i3blocks. ![stars](https://img.shields.io/badge/stars-6-blue)
- [restic](https://github.com/restic/restic) - De-duplicating backup program. ![stars](https://img.shields.io/badge/stars-27236-blue)
- [sake](https://github.com/alajmo/sake) - sake is a command runner for local and remote hosts. ![stars](https://img.shields.io/badge/stars-659-blue)
- [scc](https://github.com/boyter/scc) - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates. ![stars](https://img.shields.io/badge/stars-6953-blue)
- [Seaweed File System](https://github.com/chrislusf/seaweedfs) - Fast, Simple and Scalable Distributed File System with O(1) disk seek. ![stars](https://img.shields.io/badge/stars-23455-blue)
- [shell2http](https://github.com/msoap/shell2http) - Executing shell commands via http server (for prototyping or remote control). ![stars](https://img.shields.io/badge/stars-1369-blue)
- [Snitch](https://github.com/lucasgomide/snitch) - Simple way to notify your team and many tools when someone has deployed any application via Tsuru. ![stars](https://img.shields.io/badge/stars-17-blue)
- [sonic](https://github.com/go-sonic/sonic) - Sonic is a Go Blogging Platform. Simple and Powerful. ![stars](https://img.shields.io/badge/stars-2045-blue)
- [Stack Up](https://github.com/pressly/sup) - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers. ![stars](https://img.shields.io/badge/stars-2488-blue)
- [stew](https://github.com/marwanhawari/stew) - An independent package manager for compiled binaries. ![stars](https://img.shields.io/badge/stars-207-blue)
- [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
- [tcpdog](https://github.com/mehrdadrad/tcpdog) - eBPF based TCP observability. ![stars](https://img.shields.io/badge/stars-255-blue)
- [tinycare-tui](https://github.com/DMcP89/tinycare-tui) - Small terminal app that shows git commits from the last 24 hours and week, current weather, some self care advice, a joke, and you current todo list tasks. ![stars](https://img.shields.io/badge/stars-12-blue)
- [toxiproxy](https://github.com/shopify/toxiproxy) - Proxy to simulate network and system conditions for automated tests. ![stars](https://img.shields.io/badge/stars-10967-blue)
- [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
- [vaku](https://github.com/lingrino/vaku) - CLI & API for folder-based functions in Vault like copy, move, and search. ![stars](https://img.shields.io/badge/stars-154-blue)
- [vFlow](https://github.com/VerizonDigital/vflow) - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector. ![stars](https://img.shields.io/badge/stars-1107-blue)
- [Wave Terminal](https://waveterm.dev) - Wave is an open-source, AI-native terminal built for seamless developer workflows with inline rendering, a modern UI, and persistent sessions.
- [wellington](https://github.com/wellington/wellington) - Sass project management tool, extends the language with sprite functions (like Compass). ![stars](https://img.shields.io/badge/stars-302-blue)
- [woke](https://github.com/get-woke/woke) - Detect non-inclusive language in your source code. ![stars](https://img.shields.io/badge/stars-462-blue)
- [yai](https://github.com/ekkinox/yai) - AI powered terminal assistant. ![stars](https://img.shields.io/badge/stars-715-blue)
- [zs](https://git.mills.io/prologic/zs) - an extremely minimal static site generator.

**[⬆ back to top](#contents)**

# Resources

_Where to discover new Go libraries._

**[⬆ back to top](#contents)**

## Benchmarks

- [autobench](https://github.com/davecheney/autobench) - Framework to compare the performance between different Go versions. ![stars](https://img.shields.io/badge/stars-99-blue)
- [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results. ![stars](https://img.shields.io/badge/stars-27-blue)
- [go-benchmarks](https://github.com/tylertreat/go-benchmarks) - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches. ![stars](https://img.shields.io/badge/stars-147-blue)
- [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) - Go HTTP request router benchmark and comparison. ![stars](https://img.shields.io/badge/stars-1655-blue)
- [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) - Go JSON benchmark. ![stars](https://img.shields.io/badge/stars-9-blue)
- [go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) - benchmarks for machine learning inference in Go. ![stars](https://img.shields.io/badge/stars-31-blue)
- [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) - Go web framework benchmark. ![stars](https://img.shields.io/badge/stars-2091-blue)
- [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) - Benchmarks of Go serialization methods. ![stars](https://img.shields.io/badge/stars-1580-blue)
- [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) - Benchmarks of common basic operations for the Go language. ![stars](https://img.shields.io/badge/stars-61-blue)
- [golang-benchmarks](https://github.com/SimonWaldherr/golang-benchmarks) - a collection of golang benchmarks.  ![stars](https://img.shields.io/badge/stars-133-blue)
- [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) - Collection of benchmarks for popular Go database/SQL utilities. ![stars](https://img.shields.io/badge/stars-65-blue)
- [gospeed](https://github.com/feyeleanor/GoSpeed) - Go micro-benchmarks for calculating the speed of language constructs. ![stars](https://img.shields.io/badge/stars-121-blue)
- [kvbench](https://github.com/jimrobinson/kvbench) - Key/Value database benchmark. ![stars](https://img.shields.io/badge/stars-26-blue)
- [skynet](https://github.com/atemerev/skynet) - Skynet 1M threads microbenchmark. ![stars](https://img.shields.io/badge/stars-1049-blue)
- [speedtest-resize](https://github.com/fawick/speedtest-resize) - Compare various Image resize algorithms for the Go language. ![stars](https://img.shields.io/badge/stars-240-blue)

**[⬆ back to top](#contents)**

## Conferences

- [GoCon](https://gocon.connpass.com/) - Tokyo, Japan.
- [GoDays](https://www.godays.io/) - Berlin, Germany.
- [GoLab](https://golab.io/) - Florence, Italy.
- [GopherChina](https://gopherchina.org) - Shanghai, China.
- [GopherCon](https://www.gophercon.com/) - Denver, USA.
- [GopherCon Australia](https://gophercon.com.au/) - Sydney, Australia.
- [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, Brazil.
- [GopherCon Europe](https://gophercon.eu/) - Berlin, Germany.
- [GopherCon India](https://gopherconindia.org/) - Pune, India.
- [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
- [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
- [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
- [GopherCon UK](https://www.gophercon.co.uk/) - London, UK.
- [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
- [GoWest Conference](https://www.gowestconf.com/) - Lehi, USA.

**[⬆ back to top](#contents)**

## E-Books

### E-books for purchase

- [100 Go Mistakes: How to Avoid Them](https://www.manning.com/books/100-go-mistakes-how-to-avoid-them)
- [Black Hat Go](https://nostarch.com/blackhatgo) - Go programming for hackers and pentesters.
- [Build an Orchestrator in Go](https://www.manning.com/books/build-an-orchestrator-in-go)
- [Continuous Delivery in Go](https://www.manning.com/books/continuous-delivery-in-go) - This practical guide to continuous delivery shows you how to rapidly establish an automated pipeline that will improve your testing, code quality, and final product.
- [Creative DIY Microcontroller Project With TinyGo and WebAssembly](https://www.packtpub.com/product/creative-diy-microcontroller-projects-with-tinygo-and-webassembly/9781800560208) - An introduction into the TinyGo compiler with projects involving Arduino and WebAssembly.
- [Effective Go: Elegant, efficient, and testable code](https://www.manning.com/books/effective-go) - Unlock Go’s unique perspective on program design, and start writing simple, maintainable, and testable Go code.
- [For the Love of Go](https://bitfieldconsulting.com/books/love) - An introductory book for Go beginners.
- [Go in Practice, Second Edition](https://www.manning.com/books/go-in-practice-second-edition)  - Your practical guide on the ins-and-outs of Go development, covering the standard library and the most important tools from Go’s powerful ecosystem.
- [Know Go: Generics](https://bitfieldconsulting.com/books/generics) - A guide to understanding and using generics in Go.
- [Lets-Go](https://lets-go.alexedwards.net) - A step-by-step guide to creating fast, secure and maintanable web applications with Go.
- [Lets-Go-Further](https://lets-go-further.alexedwards.net) - Advanced patterns for building APIs and web applications in Go.
- [The Power of Go: Tests](https://bitfieldconsulting.com/books/tests) - A guide to testing in Go.
- [The Power of Go: Tools](https://bitfieldconsulting.com/books/tools) - A guide to writing command-line tools in Go.
- [Writing A Compiler In Go](https://compilerbook.com)
- [Writing An Interpreter In Go](https://interpreterbook.com) - Book that introduces dozens of techniques for writing idiomatic, expressive, and efficient Go code that avoids common pitfalls.

### Free e-books

- [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
- [An Introduction to Programming in Go](http://www.golang-book.com/)
- [Build a blockchain from scratch in Go with gRPC](https://github.com/volodymyrprokopyuk/go-blockchain) - The foundational and practical guide for effectively learning and progressively building a blockchain from scratch in Go with gRPC. ![stars](https://img.shields.io/badge/stars-316-blue)
- [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/)
- [Building Web Apps With Go](https://codegangsta.gitbooks.io/building-web-apps-with-go/content/)
- [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
- [Go AST Book (Chinese)](https://github.com/chai2010/go-ast-book) - A book focusing on Go `go/*` packages. ![stars](https://img.shields.io/badge/stars-5400-blue)
- [Go Faster](https://leanpub.com/gofaster) - This book seeks to shorten your learning curve and help you become a proficient Go programmer, faster.
- [Go Succinctly](https://github.com/thedevsir/gosuccinctly) - in Persian. ![stars](https://img.shields.io/badge/stars-22-blue)
- [Go with the domain](https://threedots.tech/go-with-the-domain/) - A book showing how to apply DDD, Clean Architecture, and CQRS by practical refactoring.
- [GoBooks](https://github.com/dariubs/GoBooks) - A curated list of Go books. ![stars](https://img.shields.io/badge/stars-17400-blue)
- [How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) - A 600 page introduction to Go aimed at first time developers.
- [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
- [Network Programming With Go](https://jan.newmarch.name/golang/)
- [Practical Go Lessons](https://www.practical-go-lessons.com/)
- [Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/)
- [The Go Programming Language](https://www.gopl.io/)
- [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) ![stars](https://img.shields.io/badge/stars-9504-blue)
- [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/) ![stars](https://img.shields.io/badge/stars-3191-blue)

**[⬆ back to top](#contents)**

## Gophers

- [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster. ![stars](https://img.shields.io/badge/stars-3558-blue)
- [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) - Go gopher Vector Data [.ai, .svg]. ![stars](https://img.shields.io/badge/stars-69-blue)
- [gopher-logos](https://github.com/GolangUA/gopher-logos) - adorable gopher logos. ![stars](https://img.shields.io/badge/stars-125-blue)
- [gopher-stickers](https://github.com/tenntenn/gopher-stickers) ![stars](https://img.shields.io/badge/stars-591-blue)
- [gophericons](https://github.com/shalakhin/gophericons) ![stars](https://img.shields.io/badge/stars-618-blue)
- [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself. ![stars](https://img.shields.io/badge/stars-716-blue)
- [gophers](https://github.com/ashleymcnamara/gophers) - Gopher artworks by Ashley McNamara. ![stars](https://img.shields.io/badge/stars-2974-blue)
- [gophers](https://github.com/egonelbre/gophers) - Free gophers. ![stars](https://img.shields.io/badge/stars-3542-blue)
- [gophers](https://github.com/rogeralsing/gophers) - random gopher graphics. ![stars](https://img.shields.io/badge/stars-58-blue)
- [gophers](https://github.com/sillecelik/go-gopher) - Gopher amigurumi toy pattern. ![stars](https://img.shields.io/badge/stars-149-blue)
- [gophers](https://github.com/scraly/gophers) - Gophers by Aurélie Vache. ![stars](https://img.shields.io/badge/stars-34-blue)

**[⬆ back to top](#contents)**

## Meetups

- [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
- [Belfast Gophers](https://www.meetup.com/Belfast-Gophers/)
- [Belgrade Golang Meetup](https://www.meetup.com/golang-serbia/)
- [Berlin Golang](https://www.meetup.com/golang-users-berlin/)
- [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
- [Bärner Go Meetup - Berne, Switzerland](https://www.meetup.com/berner-go-meetup/)
- [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
- [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
- [Go Remote Meetup](https://www.meetup.com/Go-Remote-Meetup/)
- [Go Toronto](https://www.meetup.com/go-toronto/)
- [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
- [GoBandung](https://www.meetup.com/GoBandung/)
- [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
- [GoCracow - Krakow, Poland](https://www.meetup.com/GoCracow/)
- [GoJakarta](https://www.meetup.com/GoJakarta/)
- [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
- [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
- [Golang Athens](https://www.meetup.com/Athens-Gophers/)
- [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
- [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
- [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
- [Golang Boston](https://www.meetup.com/bostongo/)
- [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
- [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
- [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
- [Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/)
- [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
- [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
- [Golang Estonia](https://www.meetup.com/Golang-Estonia/)
- [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
- [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
- [Golang Israel](https://www.meetup.com/Go-Israel/)
- [Golang Kathmandu](https://www.meetup.com/Golang-Kathmandu/)
- [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
- [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
- [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
- [Golang Melbourne](https://www.meetup.com/golang-mel/)
- [Golang Milano](https://www.meetup.com/golang-milano/)
- [Golang North East](https://www.meetup.com/en-AU/Golang-North-East/)
- [Golang Paris](https://www.meetup.com/Golang-Paris/)
- [Golang Poland](https://www.meetup.com/Golang-Poland/)
- [Golang Pune](https://www.meetup.com/Golang-Pune/)
- [Golang Roma](https://www.meetup.com/golangroma/)
- [Golang Rotterdam](https://www.meetup.com/golang-rotterdam/)
- [Golang Singapore](https://www.meetup.com/golangsg/)
- [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
- [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
- [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
- [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
- [Golang Thessaloniki](https://www.meetup.com/thessaloniki-golang-meetup/)
- [Golang Torino](https://www.meetup.com/golang-torino/)
- [Golang Turkey](https://kommunity.com/goturkiye)
- [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
- [Golang Vienna, Austria](https://www.meetup.com/viennago/)
- [Golang Москва](https://www.meetup.com/Golang-Moscow/)
- [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
- [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
- [Lagos Gophers](https://www.meetup.com/GolangNigeria/)
- [Nairobi Gophers](https://www.meetup.com/nairobi-gophers/)
- [Seattle Go Programmers](https://www.meetup.com/golang/)
- [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
- [Utah Go User Group](https://www.meetup.com/utahgophers/)
- [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)
- [Zürich Gophers - Zurich, Switzerland](https://www.meetup.com/zurich-gophers/)

_Add the group of your city/country here (send **PR**)_

**[⬆ back to top](#contents)**

## Style Guides

- [bahlo/go-styleguide](https://github.com/bahlo/go-styleguide) ![stars](https://img.shields.io/badge/stars-1503-blue)
- [CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md) ![stars](https://img.shields.io/badge/stars-30393-blue)
- [GitLab](https://docs.gitlab.com/ee/development/go_guide/)
- [Google](https://google.github.io/styleguide/go/)
- [Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst) ![stars](https://img.shields.io/badge/stars-15876-blue)
- [Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification) ![stars](https://img.shields.io/badge/stars-3074-blue)
- [Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/)
- [Trybe](https://github.com/betrybe/playbook-go/blob/main/README_EN.md) ![stars](https://img.shields.io/badge/stars-310-blue)
- [Uber](https://github.com/uber-go/guide/blob/master/style.md) ![stars](https://img.shields.io/badge/stars-16068-blue)

**[⬆ back to top](#contents)**

## Social Media

### Twitter

- [@GoDiscussions](https://twitter.com/GoDiscussions)
- [@golang](https://twitter.com/golang)
- [@golang_news](https://twitter.com/golang_news)
- [@golangch](https://twitter.com/golangch)
- [@golangweekly](https://twitter.com/golangweekly)

**[⬆ back to top](#contents)**

### Reddit

- [r/golang](https://www.reddit.com/r/golang/)

**[⬆ back to top](#contents)**

## Websites

- [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
- [Awesome Golang Workshops](https://github.com/amit-davidson/awesome-golang-workshops) - A curated list of awesome golang workshops. ![stars](https://img.shields.io/badge/stars-515-blue)
- [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) - Curated list of awesome remote jobs. A lot of them are looking for Go hackers. ![stars](https://img.shields.io/badge/stars-36129-blue)
- [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) - List of other amazingly awesome lists. ![stars](https://img.shields.io/badge/stars-32265-blue)
- [awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) - Parse awesome-go README file and generate a new README file with repo info. ![stars](https://img.shields.io/badge/stars-23-blue)
- [Code with Mukesh](https://codewithmukesh.com/categories/golang) - Software Engineer and Blogs @ codewithmukesh.com.
- [Coding Mystery](https://codingmystery.com) - Solve exciting escape-room-inspired programming challenges using Go.
- [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
- [Go Blog](https://blog.golang.org) - The official Go blog.
- [Go Code Club](https://www.youtube.com/watch?v=nvoIPQYdx9g&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3) - A group of Gophers read and discuss a different Go project every week.
- [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
- [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
- [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki. ![stars](https://img.shields.io/badge/stars-125071-blue)
- [Go Proverbs](https://go-proverbs.github.io/) - Go Proverbs by Rob Pike.
- [Go Report Card](https://goreportcard.com) - A report card for your Go package.
- [go.dev](https://go.dev/) - A hub for Go developers.
- [gocryforhelp](https://github.com/ninedraft/gocryforhelp) - Collection of Go projects that needs help. Good place to start your open-source way in Go. ![stars](https://img.shields.io/badge/stars-41-blue)
- [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusively for Golang related Roles.
- [Golang News](https://golangnews.com) - Links and news about Go programming.
- [Golang Nugget](https://golangnugget.com) - A weekly roundup of the best Go content, delivered to your inbox every Monday.
- [Golang Resources](https://golangresources.com) - A curation of the best articles, exercises, talks and videos to learn Go.
- [Golang Weekly](https://discu.eu/weekly/golang/) - Each monday projects, tutorials and articles about Go.
- [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
- [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
- [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
- [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
- [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
- [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by Francesc Campoy [@francesc](https://twitter.com/francesc).
- [Learn Go Programming](https://blog.learngoprogramming.com) - Learn Go concepts with illustrations.
- [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
- [pkg.go.dev](https://pkg.go.dev/) - Documentation for open source Go packages.
- [r/Golang](https://www.reddit.com/r/golang) - News about Go.
- [studygolang](https://studygolang.com) - The community of studygolang in China.
- [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
- [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

**[⬆ back to top](#contents)**

### Tutorials

- [50 Shades of Go](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
- [A Comprehensive Guide to Structured Logging in Go](https://betterstack.com/community/guides/logging/logging-in-go/) - Delve deep into the world of structured logging in Go with a specific focus on recently accepted slog proposal which aims to bring high performance structured logging with levels to the standard library.
- [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
- [A Tour of Go](https://tour.golang.org/) - Interactive tour of Go.
- [Build a Database in 1000 lines of code]( https://link.medium.com/O9YQlx89Htb) - Build a NoSQL Database From Zero in 1000 Lines of Code.
- [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) - Golang ebook intro how to build a web app with golang. ![stars](https://img.shields.io/badge/stars-43390-blue)
- [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) - We’ll write an API with the help of the powerful Gorilla Mux.
- [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
- [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
- [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
- [CodeCrafters Golang Track](https://app.codecrafters.io/tracks/go) - Achieve mastery in advanced Go by building your own Redis, Docker, Git, and SQLite. Featuring goroutines, systems programming, file I/O, and more.
- [Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) - Collection of programming design patterns implemented in Go. ![stars](https://img.shields.io/badge/stars-121-blue)
- [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) - A little e-book on Ethereum Development with Go. ![stars](https://img.shields.io/badge/stars-1748-blue)
- [Games With Go](https://www.youtube.com/watch?v=9D4yH7e_ea8&list=PLDZujg-VgQlZUy1iCqBbe5faZLMkA3g2x) - A video series teaching programming and game development.
- [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
- [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) - Go's reference card. ![stars](https://img.shields.io/badge/stars-8506-blue)
- [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
- [Go in 7 days](https://github.com/harrytran103/7_days_of_go) - Learn everything about Go in 7 days (from a Nodejs developer). ![stars](https://img.shields.io/badge/stars-144-blue)
- [Go Language Tutorial](https://www.javatpoint.com/go-tutorial) - Learn Go language Tutorial.
- [Go Tutorial](https://www.tutorialspoint.com/go/index.htm) - Learn Go programming.
- [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
- [go-clean-template](https://github.com/evrone/go-clean-template) - Clean Architecture template for Golang services. ![stars](https://img.shields.io/badge/stars-6402-blue)
- [go-patterns](https://github.com/tmrts/go-patterns) - Curated list of Go design patterns, recipes and idioms. ![stars](https://img.shields.io/badge/stars-25737-blue)
- [goapp](https://github.com/naughtygopher/goapp) - An opinionated guideline to structure & develop a Go web application/service. ![stars](https://img.shields.io/badge/stars-934-blue)
- [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) - Examples of Golang compared to Node.js for learning. ![stars](https://img.shields.io/badge/stars-4671-blue)
- [Golang Tutorial Guide](https://www.freecodecamp.org/news/golang-tutorial-list-free-courses-learn-go-programming-language/) - A List of Free Courses to Learn the Go Programming Language.
- [golang-examples](https://github.com/SimonWaldherr/golang-examples) - Many examples to learn Golang. ![stars](https://img.shields.io/badge/stars-1588-blue)
- [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
- [GopherCoding](https://gophercoding.com/) - Collection of code snippets and tutorials to help tackle every day issues.
- [GopherSnippets](https://gophersnippets.com/) - Code snippets with tests and testable examples for the Go programming language.
- [Gosamples](https://gosamples.dev/) - Collection of code snippets that let you solve everyday code problems.
- [GraphQL with Go](https://hasura.io/learn/graphql/backend-stack/languages/go/) - Learn how to create a Go GraphQL server and client with code generation. Also includes creating REST endpoints.
- [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
- [Hex Monscape](https://github.com/Haraj-backend/hex-monscape) - Getting started guidelines in writing maintainable code using Hexagonal Architecture. ![stars](https://img.shields.io/badge/stars-74-blue)
- [How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) - Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM.
- [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) - Learn how to use Docker for Go development and how to build production Docker images.
- [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
- [Learn Go with 1000+ Exercises](https://github.com/inancgumus/learngo) - Learn Go with thousands of examples, exercises, and quizzes. ![stars](https://img.shields.io/badge/stars-19036-blue)
- [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) - Learn Go with test-driven development. ![stars](https://img.shields.io/badge/stars-22387-blue)
- [Learning Go by examples](https://dev.to/aurelievache/learning-go-by-examples-introduction-448n) - Series of articles in order to learn Golang language by concrete applications as example.
- [Microservices with Go](https://www.youtube.com/playlist?list=PLmD8u-IFdreyh6EUfevBcbiuCKzFk0EW_) - Dive deep into building microservices using Go, including gRPC.
- [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
- [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
- [Scaling Go Applications](https://betterstack.com/community/guides/scaling-go/) - Everything about building, deploying and scaling Go applications in production.
- [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
- [Understanding Go in a visual way](https://dev.to/aurelievache/series/26234) - Learn Go visually
- [W3basic Go Tutorials](https://www.w3basic.com/golang/) - W3Basic provides an in-depth tutorial and well-organized content to learn Golang programming.
- [Working with Go](https://github.com/mkaz/working-with-go) - Intro to go for experienced programmers. ![stars](https://img.shields.io/badge/stars-1150-blue)
- [Your basic Go](https://yourbasic.org/golang) - Huge collection of tutorials and how to's.

**[⬆ back to top](#contents)**

### Guided Learning

- [The Go Developer Roadmap](https://roadmap.sh/golang) - A visual roadmap that new Go developers can follow through to help them learn Go.
- [The Go Learning Path](https://tutorialedge.net/paths/golang/) - A guided learning path containing a mix of free and premium resources.
- [The Go Skill Tree](https://labex.io/skilltrees/go) - A structured learning path that combines both free and premium resources.

**[⬆ back to top](#contents)**