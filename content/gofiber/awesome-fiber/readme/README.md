# Awesome Fiber Overview

✨ A curated list of awesome Fiber middlewares, boilerplates, recipes, articles and tools.

[🏠 Home](/README.md) · [🔥 Feed](https://www.trackawesomelist.com/gofiber/awesome-fiber/rss.xml) · [📮 Subscribe](https://trackawesomelist.us17.list-manage.com/subscribe?u=d2f0117aa829c83a63ec63c2f&id=36a103854c) · [😺 gofiber/awesome-fiber](https://github.com/gofiber/awesome-fiber) · ⭐ 99 · 🏷️ Back-End Development

[ [Daily](/content/gofiber/awesome-fiber/README.md) / [Weekly](/content/gofiber/awesome-fiber/week/README.md) / Overview ]

---

# Awesome Fiber [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<a href="https://gofiber.io">
  <img src="https://raw.githubusercontent.com/gofiber/docs/master/static/fiber_v2_logo.svg" alt="Fiber Logo" align="right" style="margin-right: 25px" height=75>
</a>

> **Fiber** is an [Express (⭐59k)](https://github.com/expressjs/express) inspired **web framework** built on top of [Fasthttp (⭐19k)](https://github.com/valyala/fasthttp), the **fastest** HTTP engine for [Go](https://golang.org/doc/). Designed to **ease** things up for **fast** development with **zero memory allocation** and **performance** in mind.

A curated list of awesome Fiber middlewares, boilerplates, recipes, articles and tools. <br>

## Contents

<!--lint disable awesome-toc-->

<!--lint disable awesome-git-repo-age-->

*   [⚙️ Middlewares](#%EF%B8%8F-middlewares)
    *   [🧬 Core](#-core)
    *   [🔗 External](#-external)
    *   [💻 Contrib](#-contrib)
    *   [🌱 Third Party](#-third-party)
*   [🚧 Boilerplates](#-boilerplates)
*   [📁 Recipes](#-recipes)
*   [🛠️ Tools](#%EF%B8%8F-tools)
*   [📖 Articles](#-articles)
*   [📺 Videos](#-videos)
*   [🤖 Benchmarks](#-benchmarks)

## ⚙️ Middlewares

Where to discover Fiber middlewares.

### 🧬 Core

List of middlewares that are included within the Fiber framework.

*   [BasicAuth (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/basicauth) - Basic auth middleware provides an HTTP basic authentication. It calls the next handler for valid credentials and 401 Unauthorized for missing or invalid credentials.
*   [Cache (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/cache) - Intercept and cache responses.
*   [Compress (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/compress) - 	Compression middleware for Fiber, it supports `deflate`, `gzip` and `brotli` by default.
*   [CORS (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/cors) - Enable cross-origin resource sharing (CORS) with various options.
*   [CSRF (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/csrf) - Protect from CSRF exploits.
*   [Encrypt Cookie (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/encryptcookie) - Encrypt middleware which encrypts cookie values.
*   [EnvVar (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/envvar) - Expose environment variables with providing an optional config.
*   [ETag (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/etag) - ETag middleware that lets caches be more efficient and save bandwidth, as a web server does not need to resend a full response if the content has not changed.
*   [Expvar (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/expvar) - Expvar middleware that serves via its HTTP server runtime exposed variants in the JSON format.
*   [Favicon (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/favicon) - Ignore favicon from logs or serve from memory if a file path is provided.
*   [FileSystem (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/filesystem) - FileSystem middleware for Fiber, special thanks and credits to Alireza Salary.
*   [Limiter (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/limiter) - Rate-limiting middleware. Use to limit repeated requests to public APIs and/or endpoints such as password reset.
*   [Logger (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/logger) - HTTP request/response logger.
*   [Monitor (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/monitor) - Monitor middleware that reports server metrics, inspired by express-status-monitor.
*   [Pprof (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/pprof) - Pprof middleware that serves via its HTTP server runtime profiling data in the format expected by the pprof visualization tool.
*   [Proxy (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/proxy) - Allows you to proxy requests to a multiple servers.
*   [Recover (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/recover) - Recover middleware recovers from panics anywhere in the stack chain and handles the control to the centralized ErrorHandler.
*   [RequestID (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/requestid) - Adds a requestid to every request.
*   [Session (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/session) - Session middleware. NOTE: This middleware uses our Storage package.
*   [Skip (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/skip) - Skip middleware that skips a wrapped handler is a predicate is true.
*   [Timeout (⭐23k)](https://github.com/gofiber/fiber/tree/master/middleware/timeout) - Adds a max time for a request and forwards to ErrorHandler if it is exceeded.

### 🔗 External

List of externally hosted middleware modules and maintained by the [Fiber team](https://github.com/orgs/gofiber/people).

*   [adaptor (⭐136)](https://github.com/gofiber/adaptor) - Converter for net/http handlers to/from Fiber request handlers.
*   [helmet (⭐68)](https://github.com/gofiber/helmet) - Helps secure your apps by setting various HTTP headers.
*   [jwt (⭐338)](https://github.com/gofiber/jwt) - JWT returns a JSON Web Token (JWT) auth middleware.
*   [keyauth (⭐57)](https://github.com/gofiber/keyauth) - Key auth middleware provides a key based authentication.
*   [redirect (⭐14)](https://github.com/gofiber/redirect) - Redirect middleware for Fiber.
*   [rewrite (⭐13)](https://github.com/gofiber/rewrite) - Rewrite middleware rewrites the URL path based on provided rules. It can be helpful for backward compatibility or just creating cleaner and more descriptive links.
*   [storage (⭐143)](https://github.com/gofiber/storage) - Premade storage drivers that implement the Storage interface, designed to be used with various Fiber middlewares.
*   [template (⭐167)](https://github.com/gofiber/template) - This package contains 8 template engines that can be used with Fiber v1.10.x Go version 1.13 or higher is required.
*   [websocket (⭐229)](https://github.com/gofiber/websocket) - Based on Fasthttp WebSocket for Fiber with Locals support!

### ‍💻 Contrib

List of third party middlewares and maintained by the Fiber team and community.

*   [casbin (⭐55)](https://github.com/gofiber/contrib/tree/main/casbin) - Casbin middleware for Fiber.
*   [fibernewrelic (⭐55)](https://github.com/gofiber/contrib/tree/main/fibernewrelic) - NewRelic middleware for Fiber. The middleware handles NewRelic insturmentation.
*   [fibersentry (⭐55)](https://github.com/gofiber/contrib/tree/main/fibersentry) - Sentry support for Fiber.
*   [fiberzap (⭐55)](https://github.com/gofiber/contrib/tree/main/fiberzap) - Zap logging support for Fiber.
*   [opafiber (⭐55)](https://github.com/gofiber/contrib/tree/main/opafiber) - Open Policy Agent middleware for Fiber. The middleware handles running Rego policies.
*   [otelfiber (⭐55)](https://github.com/gofiber/contrib/tree/main/otelfiber) - OpenTelemetry support for Fiber.
*   [paseto (⭐55)](https://github.com/gofiber/contrib/tree/main/paseto) - PASETO returns a Web Token (PASETO) auth middleware.
*   [swagger (⭐55)](https://github.com/gofiber/contrib/tree/main/swagger) - Swagger middleware for Fiber. The middleware handles Swagger UI.

### 🌱 Third Party

List of middlewares that are created by the Fiber community.

*   [arsmn/fiber-swagger (⭐242)](https://github.com/arsmn/fiber-swagger) - Fiber middleware to automatically generate RESTful API documentation with Swagger 2.0.
*   [arsmn/fiber-casbin (⭐56)](https://github.com/arsmn/fiber-casbin) - Casbin middleware for Fiber.
*   [shareed2k/fiber\_tracing (⭐8)](https://github.com/shareed2k/fiber_tracing) - Middleware trace requests on Fiber framework with OpenTracing API.
*   [shareed2k/fiber\_limiter (⭐13)](https://github.com/shareed2k/fiber_limiter) - Limiter using redis as store for rate limit with two algorithms for choosing sliding window, gcra leaky bucket.
*   [arsmn/fastgql (⭐78)](https://github.com/arsmn/fastgql) - Go library for building GraphQL servers without any fuss, but with fasthttp support.
*   [kiyonlin/fiber\_limiter (⭐3)](https://github.com/kiyonlin/fiber_limiter) - Limiter is based on rate which forks of golang.org/x/time/rate.
*   [juandiii/go-jwk-security (⭐7)](https://github.com/juandiii/go-jwk-security) - JWT middleware for fiber.
*   [ansrivas/fiberprometheus (⭐83)](https://github.com/ansrivas/fiberprometheus) - Prometheus middleware for gofiber.
*   [LdDl/fiber-long-poll (⭐12)](https://github.com/LdDl/fiber-long-poll) - Golang long polling library for fasthttp-based web framework called Fiber.
*   [K0enM/fiber\_vhost (⭐5)](https://github.com/K0enM/fiber_vhost) - Vhost (Virtual host) middleware for Fiber that enables the use of virtual hosts based on the Host Header.
*   [sacsand/gofiber-firebaseauth (⭐18)](https://github.com/sacsand/gofiber-firebaseauth) - Fiber Firebase Auth Middleware.
*   [theArtechnology/fiber-inertia (⭐10)](https://github.com/theArtechnology/fiber-inertia) - This is a Inertia.js server-side adapter based on inertia-laravel, but for Fiber Framework.
*   [aschenmaker/fiber-health-check (⭐7)](https://github.com/aschenmaker/fiber-health-check) - Health-check middleware support health-check for Fiber️ framework.
*   [elastic/apmfiber (⭐361)](https://github.com/elastic/apm-agent-go/tree/master/module/apmfiber) - APM Agent for Go Fiber.
*   [eozer/fiber\_ldapauth (⭐1)](https://github.com/eozer/fiber_ldapauth) - LDAP Authentication Middleware for Fiber.
*   [darkweak/souin (⭐360)](https://github.com/darkweak/souin) - HTTP cache, RFC compliant, alternative to Varnish available as a middleware.
*   [witer33/fiberpow (⭐2)](https://github.com/witer33/fiberpow) - Anti DDoS/Bot Middleware with a customizable Proof Of Work challenge.
*   [joffref/opa-middleware (⭐5)](https://github.com/Joffref/opa-middleware) - Provides an OPA middleware integration for fiber.
*   [vladfr/fiber-servertiming (⭐0)](https://github.com/vladfr/fiber-servertiming) - A middleware to add Server-Timing headers based on the W3C Server-Timing Spec.

## 🚧 Boilerplates

Premade boilerplates for Fiber.

*   [gofiber/boilerplate (⭐230)](https://github.com/gofiber/boilerplate) - Official fiber boilerplate.
*   [fiber-boilerplate (⭐182)](https://github.com/thomasvvugt/fiber-boilerplate) - A boilerplate for the Fiber web framework.
*   [sujit-baniya/fiber-boilerplate (⭐254)](https://github.com/sujit-baniya/fiber-boilerplate) - Boilerplate on the top of fiber web framework with many middlewares and features.
*   [sujit-baniya/goravel (⭐3)](https://github.com/sujit-baniya/goravel) - Laravel similar boilerplate go Go with support for Gofiber or Gin.
*   [create-go-app/fiber-go-template (⭐461)](https://github.com/create-go-app/fiber-go-template) - Fiber backend template for Create Go App CLI.
*   [efectn/fiber-boilerplate (⭐37)](https://github.com/efectn/fiber-boilerplate) - Simple and scalable boilerplate to build powerful and organized REST projects with Fiber.
*   [embedmode/fiberseed (⭐23)](https://github.com/embedmode/fiberseed) - Fiber boilerplate api with many middlewares.
*   [GalvinGao/gofiber-template (⭐3)](https://github.com/GalvinGao/gofiber-template) - A production-ready, container-first opinionated gofiber project template. Config by envvars, DI by go.uber.org/fx, Database by uptrace/bun, with out-of-the-box MVC folder structure and CI/CD support.

## 📁 Recipes

Recipes for Fiber.

*   [gofiber/recipes (⭐1.9k)](https://github.com/gofiber/recipes) - Official Fiber cookbook.
*   [kiyonlin/fiblar-demo (⭐1)](https://github.com/kiyonlin/fiblar-demo) - Fiber v1 + angular demo.
*   [koddr/tutorial-go-fiber-rest-api (⭐214)](https://github.com/koddr/tutorial-go-fiber-rest-api) - Tutorial for building a restful api with fiber.
*   [firebase007/go-rest-api-with-fiber (⭐34)](https://github.com/firebase007/go-rest-api-with-fiber) - Demo project with fiber, logging, basicAuth and postgresql.
*   [chawk/go\_fiber\_quickstart (⭐18)](https://github.com/chawk/go_fiber_quickstart) - Fiber quick start example project.
*   [EricLau1/go-fiber-auth-api (⭐34)](https://github.com/EricLau1/go-fiber-auth-api) - Golang Authentication API with Fiber MongoDB and JWT.

## 🛠️ Tools

Several tools to make Fiber usage easier.

*   [gofiber/cli (⭐77)](https://github.com/gofiber/cli) - Fiber Command Line Interface.
*   [go-dawn/dawn (⭐7)](https://github.com/go-dawn/dawn) - Dawn is an opinionated web framework that provides rapid development capabilities which on top of Fiber.
*   [tompston/gomakeme (⭐4)](https://github.com/tompston/gomakeme) - Generate boilerplate + endpoints for Fiber or Gin REST APIs.

## 📖 Articles

Articles about Fiber written by the community.

*   [Working with middlewares and boilerplates](https://dev.to/koddr/go-fiber-by-examples-working-with-middlewares-and-boilerplates-3p0m)
*   [Testing the application](https://dev.to/koddr/go-fiber-by-examples-testing-the-application-1ldf)
*   [Delving into built-in functions](https://dev.to/koddr/go-fiber-by-examples-delving-into-built-in-functions-1p3k)
*   [Go Fiber by Examples: How can the Fiber Web Framework be useful?](https://dev.to/koddr/go-fiber-by-examples-how-can-the-fiber-web-framework-be-useful-487a)
*   [Build a RESTful API on Go: Fiber, PostgreSQL, JWT and Swagger docs in isolated Docker containers](https://dev.to/koddr/build-a-restful-api-on-go-fiber-postgresql-jwt-and-swagger-docs-in-isolated-docker-containers-475j)
*   [Getting started with Fiber](https://dev.to/fenny/getting-started-with-fiber-36b6)
*   [Building an Express-style API in Go with Fiber](https://blog.logrocket.com/express-style-api-go-fiber/)
*   [Fiber v1.9.6 How to improve performance by 817% and stay fast, flexible and friendly?](https://dev.to/koddr/fiber-v1-9-5-how-to-improve-performance-by-817-and-stay-fast-flexible-and-friendly-2dp6)
*   [Create a travel list app with Go, Fiber, Angular, MongoDB and Google Cloud Secret Manager](https://blog.yongweilun.me/create-a-travel-list-app-with-go-fiber-angular-mongodb-and-google-cloud-secret-manager-ck9fgxy0p061pcss1xt1ubu8t)
*   [Building a Basic REST API in Go using Fiber](https://tutorialedge.net/golang/basic-rest-api-go-fiber/)
*   [Creating Fast APIs In Go Using Fiber](https://dev.to/jozsefsallai/creating-fast-apis-in-go-using-fiber-59m9)
*   [Is switching from Express to Fiber worth it?](https://dev.to/koddr/are-sure-what-your-lovely-web-framework-running-so-fast-2jl1)
*   [Fiber v1.8. What's new, updated and re-thinked?](https://dev.to/koddr/fiber-v1-8-what-s-new-updated-and-re-thinked-339h)
*   [Fiber released v1.7! What's new and is it still fast, flexible and friendly?](https://dev.to/koddr/fiber-v2-is-out-now-what-s-new-and-is-he-still-fast-flexible-and-friendly-3ipf)
*   [Welcome to Fiber — an Express.js styled web framework written in Go with ❤️](https://dev.to/koddr/welcome-to-fiber-an-express-js-styled-fastest-web-framework-written-with-on-golang-497)
*   [Blazing Fast Unit Tests - Fiber/fasthttp/http Internals](https://medium.com/trendyol-tech/golang-blazing-fast-unit-tests-fiber-fasthttp-http-internals-and-optimizing-http-server-tests-bbd1fe7b944b)
*   [Building Microservices in Go : Part 1 - Project Setup, Dockerization](https://saadfarhan124.medium.com/building-microservices-in-go-part-1-e7e58893bc5e)
*   [Building Microservices in Go : Part 2 - Live Reload](https://saadfarhan124.medium.com/building-microservices-in-go-part-2-f9c6c535805c)
*   [Building Microservices in Go : Part 3 - Database, Models, Migrations](https://saadfarhan124.medium.com/building-microservices-in-go-part-3-database-models-migrations-a4455121bb11)

## 📺 Videos

Video tutorials created by the community about Fiber.

*   [Is Fiber the best Go web framework? Better than Gin?](https://youtu.be/10miByMOGfY)

## 🤖 Benchmarks

Several benchmarks to compare Fiber with other frameworks.

*   [TechEmpower](https://www.techempower.com/benchmarks/#section=data-r20\&hw=ph\&test=json) - Project provides performance measures across a wide field of web application frameworks.
*   [web-frameworks-benchmark](https://web-frameworks-benchmark.netlify.app/result) - Project aims to measure the differences between the various programming language frameworks.
*   [go-web-framework-benchmark (⭐1.8k)](https://github.com/smallnest/go-web-framework-benchmark) - This benchmark suite aims to compare the performance of Go web frameworks.

### 👍 Contributing

Contribution guidelines can be found on [CONTRIBUTING.md (⭐99)](https://github.com/gofiber/awesome-fiber/blob/master/CONTRIBUTING.md)

