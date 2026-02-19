# Awesome Microservices [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 438,407 | 🐛 71 | 📅 2026-01-28 with stars

A curated list of Microservice Architecture related principles and technologies.

**Table of Contents**

* [Platforms](#platforms)
* [Frameworks / Runtimes](#frameworks--runtimes)
* [Service Toolkits](#service-toolkits)
  * [Polyglot](#polyglot)
  * [C](#c)
  * [C++](#c-1)
  * [C#](#csharp)
  * [D](#d)
  * [Erlang VM](#erlang-vm)
  * [Go](#go)
  * [Haskell](#haskell)
  * [Java VM](#java-vm)
  * [Node.js](#nodejs)
  * [Perl](#perl)
  * [PHP](#php)
  * [Python](#python)
  * [Ruby](#ruby)
  * [Rust](#rust)
* [Frontend / UI](#frontend--ui)
* [Capabilities](#capabilities)
  * [API Gateways / Edge Services](#api-gateways--edge-services)
  * [Configuration & Discovery](#configuration--discovery)
  * [Workflow Orchestration](#workflow-orchestration)
  * [Elasticity](#elasticity)
  * [Job Schedulers / Workload Automation](#job-schedulers--workload-automation)
  * [Logging](#logging)
  * [Messaging](#messaging)
  * [Monitoring & Debugging](#monitoring--debugging)
  * [Reactivity](#reactivity)
  * [Resilience](#resilience)
  * [Security](#security)
  * [Serialization](#serialization)
  * [Storage](#storage)
  * [Testing](#testing)
* [Continuous Integration & Delivery](#continuous-integration--delivery)
* [Web API Modeling & Documentation](#web-api-modeling--documentation)
  * [Async](#async)
  * [GraphQL](#graphql)
  * [JSON](#json)
  * [REST](#rest)
* [Standards / Recommendations](#standards--recommendations)
  * [World Wide Web](#world-wide-web)
  * [Self-sovereignty & Decentralisation](#self-sovereignty--decentralisation)
  * [HTTP/1.1](#http11)
  * [HTTP/2](#http2)
  * [QUIC](#quic)
  * [RPC](#rpc)
  * [Messaging](#messaging-1)
  * [Security](#security-1)
  * [Service Discovery](#service-discovery)
  * [Data Formats](#data-formats)
  * [Vocabularies](#vocabularies)
  * [Unicode](#unicode)
* [Organization Design / Team Dynamics](#organization-design--team-dynamics)
* [Enterprise & Verticals](#enterprise--verticals)
* [Theory](#theory)
  * [Articles & Papers](#articles--papers)
  * [Sites & Organizations](#sites--organizations)
* [License](#license)
* [Contributing](#contributing)

## Platforms

* [OpenWhisk](https://github.com/apache/openwhisk) ⭐ 6,754 | 🐛 432 | 🌐 Scala | 📅 2026-01-24 - Serverless, open source cloud platform that executes functions in response to events at any scale.
* [1Backend](https://github.com/1backend/1backend) ⭐ 2,321 | 🐛 11 | 🌐 Go | 📅 2026-02-16 - AI-native microservices platform.
* [Triton](https://github.com/joyent/triton) ⭐ 1,362 | 🐛 42 | 🌐 Shell | 📅 2025-06-18 - Open-source cloud management platform that delivers next generation, container-based, service-oriented infrastructure across one or more data centers.
* [Jolie](https://jolie-lang.org) - Open source microservice-oriented programming language.
* [Pulumi](https://pulumi.io/) - SDK for cloud native infrastructure as code. Use your favorite language to preview and manage updates to your apps and infrastructure, and continuously deploy to any cloud (no YAML required).

## Frameworks / Runtimes

* [Erlang/OTP](https://github.com/erlang/otp) ⭐ 12,028 | 🐛 531 | 🌐 Erlang | 📅 2026-02-19 - Programming language used to build massively scalable soft real-time systems with requirements on high availability.
* [Spin](https://github.com/fermyon/spin) ⭐ 6,303 | 🐛 293 | 🌐 Rust | 📅 2026-02-17 - An open source framework for building and running fast, secure, and composable cloud microservices with WebAssembly.
* [Light-4j](https://github.com/networknt/light-4j) ⭐ 3,680 | 🐛 14 | 🌐 Java | 📅 2026-02-18 - A high throughput, low latency, small memory footprint and more productive microservices platform.
* [Wangle](https://github.com/facebook/wangle) ⭐ 3,095 | 🐛 47 | 🌐 C++ | 📅 2026-02-19 - A framework providing a set of common client/server abstractions for building services in a consistent, modular, and composable way.
* [Ice](https://github.com/zeroc-ice/ice) ⭐ 2,159 | 🐛 77 | 🌐 C++ | 📅 2026-02-18 - Comprehensive RPC framework with support for C++, C#, Java, JavaScript, Python, and more.
* [ScaleCube](https://github.com/scalecube/scalecube) ⭐ 638 | 🐛 16 | 🌐 Java | 📅 2026-02-18 - Toolkit for building reactive microservices for the JVM: low-latency, high-throughput, scalable and resilient.
* [Pears](https://github.com/holepunchto/pear) ⭐ 216 | 🐛 56 | 🌐 JavaScript | 📅 2026-02-18 - Peer-to-peer runtime, development and deployment.
* [Vert.X Toolbox](https://github.com/vert-x3/vertx-microservices-toolbox) ⭐ 119 | 🐛 13 | 🌐 Java | 📅 2026-02-16 - A set of Vert.x components to build reactive microservice applications.
* [Akka](http://akka.io/) - Toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM.
* [Axon (c)](https://axoniq.io/) - An end-to-end development and infrastructure platform for easy development and running of any DDD, CQRS and Event Sourcing applications on JVM.
* [Ballerina](https://ballerina.io) - Cloud native programming language.
* [Bun](https://bun.sh/) - Fast all-in-one JavaScript runtime.
* [Dapr](https://dapr.io) - Open source runtime for writing highly performant microservices using any programming language.
* [Deno](https://deno.land/) - JavaScript, TypeScript, and WebAssembly runtime with secure defaults and a great developer experience.
* [Eclipse Microprofile](https://microprofile.io/) - An open forum to optimize Enterprise Java for a microservices architecture by innovating across multiple implementations and collaborating on common areas of interest with a goal of standardization.
* [Finagle](http://twitter.github.io/finagle) - Extensible RPC system for the JVM, used to construct high-concurrency servers.
* [Gleam](https://gleam.run/) - A friendly language for building type-safe, scalable systems.
* [GraalVM](https://www.graalvm.org/) - High-performance runtime that provides significant improvements in application performance and efficiency which is ideal for microservices.
* [Helidon](https://helidon.io/) - Collection of Java libraries for writing microservices that run on a fast web core powered by Netty.
* [Micronaut](http://micronaut.io/) - A modern, JVM-based, full-stack framework for building modular, easily testable microservice applications.
* [Moleculer](http://moleculer.services/) - Fast & powerful microservices framework for Node.js, Java, Go and Ruby.
* [Open Liberty](https://openliberty.io/) - A lightweight open framework for building fast and efficient cloud-native Java microservices.
* [SmallRye](https://smallrye.io/) - APIs and implementations tailored for cloud development, including Eclipse MicroProfile.
* [Vert.X](http://vertx.io/) - Toolkit for building reactive applications on the JVM.

## Service Toolkits

### Polyglot

* [GRPC](http://www.grpc.io/) - A high performance, open source, general RPC framework that puts mobile and HTTP/2 first. Libraries in C, C++, Java, Go, Node.js, Python, Ruby, Objective-C, PHP and C#.

### C

* [Lwan](http://lwan.ws/) - High-performance and scalable web server.
* [uSockets](https://github.com/uNetworking/uSockets) ⭐ 1,431 | 🐛 44 | 🌐 C | 📅 2025-07-14 - Miniscule cross-platform eventing, networking & crypto for async applications.

### C++

<!-- #c-1 anchor -->

* [uWebSockets](https://github.com/uNetworking/uWebSockets) ⭐ 18,697 | 🐛 47 | 🌐 C++ | 📅 2026-02-11 - Simple, secure & standards compliant web server for the most demanding of applications.
* [Sogou Workflow](https://github.com/sogou/workflow) ⭐ 14,297 | 🐛 25 | 🌐 C++ | 📅 2026-02-13 - Enterprise-grade programming engine aimed to satisfy most of the backend development requirements.
* [Pistache](https://github.com/oktal/pistache) ⭐ 3,450 | 🐛 223 | 🌐 C++ | 📅 2025-12-15 - A high-performance REST toolkit written in C++.
* [C++ Micro Services](https://github.com/CppMicroServices/CppMicroServices) ⭐ 862 | 🐛 65 | 🌐 C++ | 📅 2026-02-09 - An OSGi-like C++ dynamic module system and service registry.
* [Enduro/X](https://github.com/endurox-dev/endurox/) ⭐ 137 | 🐛 0 | 🌐 C | 📅 2025-09-15 - XATMI based service framework for GNU/Linux.
* [Cap’n Proto RPC](https://capnproto.org/cxxrpc.html) - The Cap’n Proto C++ RPC implementation.
* [Poco](http://pocoproject.org/) - C++ class libraries for building network-based applications and servers.

### CSharp

* [Awesome Microservices .NET Core](https://github.com/mjebrahimi/Awesome-Microservices-NetCore) ⭐ 3,035 | 🐛 5 | 📅 2024-10-31 :star: - A collection of awesome training series, articles, videos, books, courses, sample projects, and tools for microservices in .NET Core.

### D

* [Vibe.d](http://vibed.org/) - Asynchronous I/O that doesn’t get in your way, written in D.

### Erlang VM

#### Elixir

* [Phoenix](http://www.phoenixframework.org/) - Framework for building HTML5 apps, API backends and distributed systems.
* [Plug](https://github.com/elixir-lang/plug) ⭐ 2,985 | 🐛 3 | 🌐 Elixir | 📅 2026-01-15 - A specification and conveniences for composable modules between web applications.

#### Erlang

* [Cowboy](https://github.com/ninenines/cowboy) ⭐ 7,475 | 🐛 53 | 🌐 Erlang | 📅 2026-02-13 - Small, fast, modular HTTP server written in Erlang.
* [Mochiweb](https://github.com/mochi/mochiweb) ⭐ 1,885 | 🐛 12 | 🌐 Erlang | 📅 2025-09-17 - Erlang library for building lightweight HTTP servers.

### Go

* [Gin](https://github.com/gin-gonic/gin) ⭐ 88,066 | 🐛 884 | 🌐 Go | 📅 2026-02-17 - Gin is a HTTP web framework written in Go (Golang). It features a Martini-like API with much better performance, up to 40 times faster.
* [Fiber](https://github.com/gofiber/fiber) ⭐ 39,228 | 🐛 42 | 🌐 Go | 📅 2026-02-18 - Express inspired web framework built on top of Fasthttp, the fastest HTTP engine for Go. Designed to ease things up for fast development with zero memory allocation and performance in mind.
* [Go-zero](https://github.com/tal-tech/go-zero) ⭐ 32,664 | 🐛 306 | 🌐 Go | 📅 2026-02-18 - A web and rpc distributed system development framework.
* [Iris](https://github.com/kataras/iris) ⭐ 25,623 | 🐛 143 | 🌐 Go | 📅 2026-01-15 - Fast, simple and efficient micro web framework for Go.
* [Go-micro](https://github.com/micro/go-micro) ⭐ 22,706 | 🐛 0 | 🌐 Go | 📅 2026-02-14 - A distributed systems development framework.
* [Chi](https://github.com/go-chi/chi) ⭐ 21,650 | 🐛 98 | 🌐 Go | 📅 2026-02-18 - Lightweight, idiomatic and composable router for building Go HTTP services.
* [GoFr](https://github.com/gofr-dev/gofr) ⭐ 16,091 | 🐛 90 | 🌐 Go | 📅 2026-02-18 - An opinionated microservice development framework emphasizing scalability and robustness. Designed to simplify the development of microservices.
* [RPCX](https://github.com/smallnest/rpcx) ⭐ 8,276 | 🐛 9 | 🌐 Go | 📅 2025-12-12 - A distributed RPC service framework based on NET/RPC like Alibaba Dubbo and Weibo Motan.
* [Lura](https://github.com/luraproject/lura) ⭐ 6,736 | 🐛 7 | 🌐 Go | 📅 2026-02-10 - Framework to build ultra performance API Gateways with middlewares.
* [Goa](https://github.com/goadesign/goa) ⭐ 6,055 | 🐛 37 | 🌐 Go | 📅 2026-02-19 - Design-based HTTP microservices in Go.
* [Go Chassis](https://github.com/go-chassis/go-chassis) ⭐ 2,735 | 🐛 44 | 🌐 Go | 📅 2025-12-31 - A framework for rapid development of microservices in Go that is easy to integrate with some cloud ecosystems.
* [Echo](https://echo.labstack.com/) - Fast and unfancy HTTP server framework for Go. Up to 10x faster than the rest.
* [Gorilla](http://www.gorillatoolkit.org/) - Web toolkit for the Go programming language.

### Haskell

* [Yesod](https://github.com/yesodweb/yesod) ⭐ 2,699 | 🐛 124 | 🌐 Haskell | 📅 2026-02-12 - The Haskell RESTful web framework.
* [Servant](https://github.com/haskell-servant/servant) ⭐ 1,939 | 🐛 288 | 🌐 Haskell | 📅 2025-12-23 - Type-level web DSL.
* [Scotty](https://github.com/scotty-web/scotty) ⭐ 1,767 | 🐛 29 | 🌐 Haskell | 📅 2026-01-15 - Micro web framework inspired by Ruby's Sinatra, using WAI and Warp.

### Java VM

#### Clojure

* [Compojure](https://github.com/weavejester/compojure) ⭐ 4,109 | 🐛 7 | 🌐 Clojure | 📅 2025-09-15 - A concise routing library for Ring/Clojure.
* [System](https://github.com/danielsz/system) ⭐ 605 | 🐛 13 | 🌐 Clojure | 📅 2025-08-16 - Built on top of Stuart Sierra's component library, offers a set of readymade components.
* [Tesla](https://github.com/otto-de/tesla-microservice) ⭐ 195 | 🐛 2 | 🌐 Clojure | 📅 2025-08-13 - Common basis for some of Otto.de's Clojure microservices.
* [Duct](https://duct-framework.org/) - A server-side framework for Clojure.

#### Java

* [Dubbo](https://github.com/apache/dubbo) ⭐ 41,734 | 🐛 923 | 🌐 Java | 📅 2026-02-16 - A high-performance, java based RPC framework open-sourced by Alibaba.
* [Disruptor](https://github.com/LMAX-Exchange/disruptor) ⭐ 18,236 | 🐛 14 | 🌐 Java | 📅 2025-04-02 - High-performance inter-thread messaging library.
* [Dropwizard](https://github.com/dropwizard/dropwizard) ⭐ 8,600 | 🐛 35 | 🌐 Java | 📅 2026-02-17 - Java framework for developing ops-friendly, high-performance, RESTful web services.
* [ActiveJ](https://github.com/activej/activej) ⭐ 983 | 🐛 47 | 🌐 Java | 📅 2026-01-09 - Lightweight and fast library for complex high-load distributed applications and Memcached-like solutions.
* [Jersey](https://github.com/eclipse-ee4j/jersey) ⭐ 726 | 🐛 828 | 🌐 Java | 📅 2026-01-30 - RESTful services in Java. JAX-RS reference implementation.
* [Airlift](https://github.com/airlift/airlift) ⭐ 629 | 🐛 112 | 🌐 Java | 📅 2026-02-18 - Framework for building REST services in Java.
* [Conjure](https://github.com/palantir/conjure-java-runtime) ⭐ 88 | 🐛 42 | 🌐 Java | 📅 2026-02-18 - Opinionated set of libraries for defining and creating RESTish/RPC servers and clients based on Feign or Retrofit as a client and Dropwizard/Jersey with JAX-RS service definitions as a server.
* [Armeria](https://line.github.io/armeria/) - Open-source asynchronous HTTP/2 RPC/REST client/server library built on top of Java 8, Netty, Thrift and gRPC.
* [Quarkus](https://quarkus.io/) - A Kubernetes Native Java stack tailored for OpenJDK HotSpot and GraalVM, crafted from the best of breed Java libraries and standards.
* [Ratpack](https://ratpack.io/) - Set of Java libraries that facilitate fast, efficient, evolvable and well tested HTTP applications. specific support for the Groovy language is provided.
* [Spring Boot](http://projects.spring.io/spring-boot/) - Makes it easy to create stand-alone, production-grade Spring based applications.

#### Kotlin

* [Http4k](https://www.http4k.org/) - Lightweight but fully-featured HTTP toolkit written in pure Kotlin that enables the serving and consuming of HTTP services in a functional and consistent way.
* [Ktor](https://ktor.io/) - Framework for building asynchronous servers and clients in connected systems using the Kotlin programming language.

#### Scala

* [Finatra](http://twitter.github.io/finatra/) - Fast, testable, Scala HTTP services built on Twitter-Server and Finagle.
* [Http4s](http://http4s.org/) - A minimal, idiomatic Scala interface for HTTP
* [Play](https://www.playframework.com/) - The high velocity web framework for Java and Scala.

### Node.js

* [Serverless](https://github.com/serverless/serverless) ⭐ 46,945 | 🐛 1,227 | 🌐 JavaScript | 📅 2026-02-18 - Build and maintain web, mobile and IoT applications running on AWS Lambda and API Gateway (formerly known as JAWS).
* [tRPC](https://github.com/trpc/trpc) ⭐ 39,562 | 🐛 183 | 🌐 TypeScript | 📅 2026-02-18 - End-to-end typesafe APIs.
* [Seneca](https://github.com/senecajs/seneca) ⭐ 3,950 | 🐛 212 | 🌐 JavaScript | 📅 2026-02-15 - A microservices toolkit for Node.js
* [Actionhero](http://www.actionherojs.com/) - Multi-transport Node.js API server with integrated cluster capabilities and delayed tasks.
* [Express](http://expressjs.com/) - Fast, unopinionated, minimalist web framework for Node.js
* [Fastify](https://www.fastify.io/) - Fastify, Fast and low overhead web framework, for Node.js.
* [FeathersJS](http://feathersjs.com/) - An open source REST and realtime API layer for modern applications.
* [Hono](https://hono.dev/) - Small, simple, and ultrafast web framework for the Edges. It works on any JavaScript runtime.
* [Koa](http://koajs.com/) - Next generation web framework for Node.js
* [Loopback](http://loopback.io/) - Node.js framework for creating APIs and easily connecting to backend data sources.
* [NestJS](https://docs.nestjs.com/) - A Node.js framework for building efficient and scalable server-side applications with a built-in microservices support.

### Perl

* [Cro](http://cro.services/) - Libraries for creating reactive distributed systems using Perl 6.
* [Mojolicious](https://mojolicious.org/) - Next generation web framework for Perl.

### PHP

* [Hyperf](https://github.com/hyperf/hyperf) ⭐ 6,773 | 🐛 455 | 🌐 PHP | 📅 2026-02-04 - Hyperf is an extremely performant and flexible PHP CLI framework based on Swoole 4.5+, powered by the state-of-the-art coroutine server and a large number of battle-tested components.
* [Swoft](https://github.com/swoft-cloud/swoft/) ⭐ 5,557 | 🐛 194 | 🌐 PHP | 📅 2023-02-28 - PHP microservices coroutine framework for building high-performance web systems, APIs, middleware, and basic services.
* [API Platform](https://api-platform.com/) - API-first web framework on top of Symfony with JSON-LD, Schema.org and Hydra support.
* [Ecotone](https://docs.ecotone.tech/) - Framework based on architectural principles of DDD, CQRS and Event Sourcing that provides building blocks to create scalable and extensible applications.
* [Lumen](https://lumen.laravel.com/) - Stunningly fast micro-framework.
* [Slim](http://www.slimframework.com/) - Micro-framework that helps you quickly write simple yet powerful web applications and APIs.
* [Spiral](https://spiral.dev/) - Framework designed for long-running applications using [RoadRunner](https://roadrunner.dev/). It offers advanced features like integration with the [Temporal](https://temporal.io/) workflow engine and [Centrifugo](https://centrifugal.dev/) websocket server. It is particularly effective for microservices architecture, providing robust support for REST APIs and gRPC services.
* [Symfony](https://symfony.com/) - Micro-framework based on the Symfony components.

### Python

* [Sanic](https://github.com/sanic-org/sanic) ⭐ 18,637 | 🐛 120 | 🌐 Python | 📅 2026-01-07 - Sanic is a Flask-like Python 3.5+ web server that's written to go fast.
* [Aiohttp](https://github.com/aio-libs/aiohttp) ⭐ 16,298 | 🐛 280 | 🌐 Python | 📅 2026-02-18 - HTTP client/server for asyncio.
* [Web.py](https://github.com/webpy/webpy/) ⭐ 5,933 | 🐛 55 | 🌐 Python | 📅 2025-12-28 - Minimalist web framework for Python.
* [Nameko](https://github.com/onefinestay/nameko) ⭐ 4,767 | 🐛 94 | 🌐 Python | 📅 2024-05-01 - Python framework for building microservices.
* [Connexion](https://github.com/zalando/connexion) ⭐ 4,577 | 🐛 172 | 🌐 Python | 📅 2026-02-02 - Swagger/OpenAPI framework for Python on top of Flask with automatic endpoint validation and OAuth2 support.
* [Bottle](https://bottlepy.org) - Fast, simple and lightweight WSGI micro web-framework for Python.
* [Falcon](https://falconframework.org/) - Bare-metal Python web API framework for building very fast app backends and microservices.
* [FastAPI](https://fastapi.tiangolo.com/) - Modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints.
* [Flask](http://flask.pocoo.org/) - Python framework for microservices based on Werkzeug and Jinja 2.
* [Tornado](http://www.tornadoweb.org/) - Web framework and asynchronous networking library.
* [Twisted](https://twisted.org/) - Event-driven network programming engine.

### Ruby

* [Grape](https://github.com/ruby-grape/grape) ⭐ 9,983 | 🐛 259 | 🌐 Ruby | 📅 2026-02-18 - An opinionated framework for creating REST-like APIs
* [Praxis](https://github.com/rightscale/praxis) ⭐ 301 | 🐛 12 | 🌐 Ruby | 📅 2025-04-09 - Framework for both designing and implementing APIs.
* [Scorched](https://github.com/wardrop/Scorched) ⭐ 275 | 🐛 0 | 🌐 Ruby | 📅 2025-02-21 - Light-weight web framework for Ruby.
* [Hanami](https://github.com/hanami) - A modern web framework for Ruby.
* [Sinatra](http://www.sinatrarb.com/) - Sinatra is a DSL for quickly creating web applications in Ruby with minimal effort.

### Rust

* [Tower](https://github.com/tower-rs/tower) ⭐ 4,088 | 🐛 80 | 🌐 Rust | 📅 2026-02-12 - Library of modular and reusable components for building robust networking clients and servers.
* [Tarpc](https://github.com/google/tarpc) ⭐ 3,672 | 🐛 55 | 🌐 Rust | 📅 2026-02-10 - RPC framework for Rust with a focus on ease of use.
* [Wtx](https://github.com/c410-f3r/wtx) ⭐ 342 | 🐛 12 | 🌐 Rust | 📅 2026-02-11 - HTTP/2 client/server framework.
* [Are we web yet?](https://www.arewewebyet.org/) :star: - A summary of the current state of web programming in Rust.
* [Actix](https://actix.rs/) - Powerful, pragmatic, and extremely fast web framework for Rust.
* [Tokio](https://tokio.rs) - Asynchronous runtime for writing network applications.

## Frontend / UI

* [Awesome Micro Frontends](https://github.com/ChristianUlbrich/awesome-microfrontends) ⭐ 592 | 🐛 4 | 📅 2021-11-08 :star: - A curated list of resources about Micro Frontends.
* [Electrode](https://github.com/electrode-io) - Universal React/Node.js application platform.
* [Micro Frontends](https://micro-frontends.org) - Extending the microservice idea to frontend development.
* [MiniApp White Paper](https://w3c.github.io/miniapp/white-paper/) - MiniApp standardization white paper.

## Capabilities

### API Gateways / Edge Services

> Note that [data and control plane](https://blog.envoyproxy.io/service-mesh-data-plane-vs-control-plane-2774e720f7fc) components are not categorized at this moment.

* [Kong](https://github.com/kong/kong) ⭐ 42,793 | 🐛 131 | 🌐 Lua | 📅 2026-01-19 - Open source management layer for APIs.
* [Envoy](https://github.com/lyft/envoy) ⭐ 27,570 | 🐛 1,710 | 🌐 C++ | 📅 2026-02-19 - Open source edge and service proxy, from the developers at Lyft.
* [Pingora](https://github.com/cloudflare/pingora) ⭐ 26,120 | 🐛 237 | 🌐 Rust | 📅 2026-02-10 - A library for building fast, reliable and evolvable network services.
* [Zuul](https://github.com/Netflix/zuul) ⭐ 13,987 | 🐛 11 | 🌐 Java | 📅 2026-02-19 - An edge service that provides dynamic routing, monitoring, resiliency, security, and more.
* [Bunker Web](https://github.com/bunkerity/bunkerweb) ⭐ 10,026 | 🐛 109 | 🌐 Python | 📅 2026-02-18 - Web app hosting and reverse proxy secure by default.
* [HAProxy](https://github.com/haproxy/haproxy) ⭐ 6,340 | 🐛 337 | 🌐 C | 📅 2026-02-18 - Reliable, high Performance TCP/HTTP load balancer.
* [Skipper](https://github.com/zalando/skipper) ⭐ 3,253 | 🐛 315 | 🌐 Go | 📅 2026-02-18 - HTTP router useful for decoupling routing from service logic.
* [Vulcand](https://github.com/vulcand/vulcand) ⭐ 3,098 | 🐛 70 | 🌐 Go | 📅 2024-07-27 - Programmatic load balancer backed by Etcd.
* [Traffic Server](https://github.com/apache/trafficserver) ⭐ 1,934 | 🐛 439 | 🌐 C++ | 📅 2026-02-18 - High-performance building block for cloud services.
* [APIcast](https://github.com/3scale/APIcast) ⭐ 323 | 🐛 59 | 🌐 Lua | 📅 2026-02-13 - APIcast is an API gateway built on top of NGINX. It is part of the Red Hat 3scale API Management Platform.
* [Neutrino](https://github.com/eBay/Neutrino) ⭐ 316 | 🐛 9 | 🌐 Scala | 📅 2018-02-09 - Extensible software load balancer.
* [Ambassador (c)](https://www.getambassador.io) - Kubernetes-native API gateway for microservices built on Envoy.
* [Caddy](https://caddyserver.com/) - Extensible HTTP/2 web server with automatic HTTPS.
* [Camel](http://camel.apache.org/) - Empowers you to define routing and mediation rules in a variety of domain-specific languages, including a Java-based fluent API, Spring or Blueprint XML configuration files, and a Scala DSL.
* [Istio](https://istio.io/) - An open platform to connect, manage, and secure microservices.
* [Keepalived](http://www.keepalived.org/) - Simple and robust facilities for loadbalancing and high-availability to Linux system and Linux based infrastructures.
* [KrakenD](http://krakend.io/) - Open source ultra performance API Gateway.
* [Kuma](https://kuma.io/) - Platform agnostic open source control plane for service mesh and microservices.
* [Linkerd](https://linkerd.io/) - Resilient service mesh for cloud native apps.
* [OpenResty](http://openresty.org/) - Fast web application server built on top of Nginx.
* [Open Service Mesh](https://openservicemesh.io/) - Lightweight and extensible cloud native service mesh.
* [Otoroshi](https://www.otoroshi.io/) - Modern HTTP reverse proxy with lightweight API management.
* [Spring Cloud Gateway](https://cloud.spring.io/spring-cloud-gateway/) - API Gateway on top of Spring MVC. Aims to provide a simple, yet effective way to route to APIs.
* [Tengine](http://tengine.taobao.org/) - A distribution of Nginx with some advanced features.
* [Træfɪk](http://traefik.io/) - A modern HTTP reverse proxy and load balancer made to deploy microservices with ease.
* [Tyk](https://tyk.io/) - Open source, fast and scalable API gateway, portal and API management platform.

### Configuration & Discovery

* [Etcd](https://github.com/coreos/etcd) ⭐ 51,559 | 🐛 221 | 🌐 Go | 📅 2026-02-18 - Highly-available key-value store for shared configuration and service discovery.
* [Nacos](https://github.com/alibaba/nacos) ⭐ 32,640 | 🐛 217 | 🌐 Java | 📅 2026-02-13 - Easy-to-use dynamic service discovery, configuration and service management platform.
* [Eureka](https://github.com/Netflix/eureka/wiki/Eureka-at-a-glance) ⭐ 12,697 | 🐛 137 | 🌐 Java | 📅 2026-01-23 - REST based service that is primarily used in the AWS cloud for locating services for the purpose of load balancing and failover of middle-tier servers.
* [SkyDNS](https://github.com/skynetservices/skydns) ⭐ 2,207 | 🐛 61 | 🌐 Go | 📅 2021-03-21 - Distributed service for announcement and discovery of services built on top of etcd. It utilizes DNS queries to discover available services.
* [Central Dogma](https://line.github.io/centraldogma/) - Open-source highly-available version-controlled service configuration repository based on Git, ZooKeeper and HTTP/2.
* [Consul](https://www.consul.io/) - Service discovery and configuration made easy. Distributed, highly available, and datacenter-aware.
* [Microconfig](https://microconfig.io) - Modern and simple way of microservice configuration management.
* [Spring Cloud Config](http://cloud.spring.io/spring-cloud-config/) - Provides server and client-side support for externalized configuration in a distributed system.
* [ZooKeeper](https://zookeeper.apache.org/) - Open source server which enables highly reliable distributed coordination.

### Workflow Orchestration

* [Kestra](https://github.com/kestra-io/kestra) ⭐ 26,413 | 🐛 533 | 🌐 Java | 📅 2026-02-18 - Open source microservices event-driven, language-agnostic orchestration and scheduling platform.
* [Temporal](https://github.com/temporalio/temporal) ⭐ 18,391 | 🐛 639 | 🌐 Go | 📅 2026-02-19 - Open source microservices orchestration platform for running mission critical code at any scale.
* [Conductor](https://github.com/Netflix/conductor) ⚠️ Archived - A microservices orchestration engine.
* [Inngest](https://github.com/inngest/inngest) ⭐ 4,857 | 🐛 180 | 🌐 Go | 📅 2026-02-18 - Durable functions for reliable background logic, from background jobs to complex workflows.
* [AWS Step Functions (c)](https://aws.amazon.com/step-functions/) - Coordinate the components of distributed applications and microservices using visual workflows.
* [Cadence](https://cadenceworkflow.io/) - Fault-oblivious stateful code platform.
* [Zeebe](https://camunda.com/platform/zeebe/) - Define, orchestrate, and monitor business processes across microservices.

### Elasticity

* [Valkey](https://github.com/valkey-io/valkey) ⭐ 24,860 | 🐛 606 | 🌐 C | 📅 2026-02-18 - A new project to resume development on the formerly open-source Redis project.
* [Redisson](https://github.com/mrniko/redisson) ⭐ 24,251 | 🐛 286 | 🌐 Java | 📅 2026-02-17 - Distributed and scalable Java data structures on top of Redis server.
* [Hazelcast](http://hazelcast.org/) - Open source in-memory data-grid. Allows you to distribute data and computation across servers, clusters and geographies, and to manage very large data sets or high data ingest rates. Mature technology.
* [Helix](http://helix.apache.org/) - Generic cluster management framework used for the automatic management of partitioned, replicated and distributed resources hosted on a cluster of nodes.
* [Ignite](http://ignite.apache.org/) - High-performance, integrated and distributed in-memory platform for computing and transacting on large-scale data sets in real-time, orders of magnitude faster than possible with traditional disk-based or flash technologies.
* [Libp2p](https://libp2p.io/) - A framework and suite of protocols for building peer-to-peer network applications.
* [Mesos](https://mesos.apache.org/) - Abstracts CPU, memory, storage, and other compute resources away from machines (physical or virtual), enabling fault-tolerant and elastic distributed systems to easily be built and run effectively.
* [Nomad](https://www.nomadproject.io/) - Distributed, highly available, datacenter-aware scheduler.
* [Serf](https://www.serf.io/) - Decentralized solution for cluster membership, failure detection and orchestration.
* [Zenoh](https://zenoh.io/) - Pub/sub/query protocol unifying data in motion, data at rest and computations. Efficiently blends traditional pub/sub with geo distributed storage, queries and computations.

### Job Schedulers / Workload Automation

* [Celery](https://github.com/celery/celery) ⭐ 28,069 | 🐛 776 | 🌐 Python | 📅 2026-02-18 - Asynchronous task queue/job queue based on distributed message passing. Focused on real-time operation and supports scheduling.
* [Faktory](https://github.com/contribsys/faktory) ⭐ 6,084 | 🐛 22 | 🌐 Go | 📅 2026-02-19 - Language-agnostic persistent background job server.
* [Schedulix](https://github.com/schedulix/schedulix) ⭐ 129 | 🐛 1 | 🌐 Java | 📅 2025-12-16 - Open source enterprise job scheduling system lays down ground-breaking standards for the professional automation of IT processes in advanced system environments.
* [Dkron](http://dkron.io/) - Distributed, fault tolerant job scheduling system.
* [Rundeck (c)](http://rundeck.org/) - Job scheduler and runbook automation. Enable self-service access to existing scripts and tools.

### Logging

* [Fluentd](http://www.fluentd.org/) - Open source data collector for unified logging layer.
* [Graylog](https://www.graylog.org/) - Fully integrated open source log management platform.
* [Kibana](https://www.elastic.co/products/kibana) - Flexible analytics and visualization platform.
* [LogDNA (c)](https://logdna.com/) - Centralized log management software. Instantly collect, centralize, and analyze logs in real-time from any platform, at any volume.
* [Logstash](https://www.elastic.co/logstash) - Tool for managing events and logs.
* [Loki](https://github.com/grafana/loki) ⭐ 27,631 | 🐛 2,232 | 🌐 Go | 📅 2026-02-19 - Like Prometheus, but for logs.

### Messaging

* [RocketMQ](https://github.com/apache/incubator-rocketmq) ⭐ 22,335 | 🐛 278 | 🌐 Java | 📅 2026-02-13 - A low latency, reliable, scalable, easy to use message oriented middleware born from alibaba massive messaging business.
* [Bull](https://github.com/OptimalBits/bull) ⭐ 16,234 | 🐛 146 | 🌐 JavaScript | 📅 2026-01-21 - Fast and reliable Redis-based queue for Node.
* [Redpanda](https://github.com/redpanda-data/redpanda/) ⭐ 11,739 | 🐛 675 | 🌐 C++ | 📅 2026-02-19 - Streaming data platform for developers: Kafka API compatible, 10x faster, no ZooKeeper and no JVM.
* [Aeron](https://github.com/real-logic/Aeron) ⭐ 8,449 | 🐛 17 | 🌐 Java | 📅 2026-02-19 - Efficient reliable UDP unicast, UDP multicast, and IPC message transport.
* [Crossbar](https://github.com/crossbario/crossbar) ⭐ 2,063 | 🐛 301 | 🌐 Python | 📅 2026-01-04 - Open source networking platform for distributed and microservice applications. It implements the open Web Application Messaging Protocol (WAMP).
* [Malamute](https://github.com/zeromq/malamute) ⭐ 334 | 🐛 28 | 🌐 C | 📅 2025-06-25 - ZeroMQ enterprise messaging broker.
* [ØMQ](http://zeromq.org/) - Brokerless intelligent transport layer.
* [ActiveMQ](http://activemq.apache.org/) - Powerful open source messaging and integration patterns server.
* [Beanstalk](https://beanstalkd.github.io/) - Simple, fast work queue.
* [Kafka](http://kafka.apache.org/) - Publish-subscribe messaging rethought as a distributed commit log.
* [Mosquitto](http://mosquitto.org/) - Open source message broker that implements the MQTT protocol.
* [NATS](https://nats.io/) - Open source, high-performance, lightweight cloud messaging system.
* [NSQ](http://nsq.io/) - A realtime distributed messaging platform.
* [Pulsar](https://pulsar.apache.org/) - Distributed pub-sub messaging system.
* [RabbitMQ](https://www.rabbitmq.com/) - Open source Erlang-based message broker that just works.

### Monitoring & Debugging

* [Beats](https://www.elastic.co/beats/) - Lightweight shippers for Elasticsearch & Logstash.
* [Elastalert](https://github.com/yelp/elastalert) ⭐ 8,009 | 🐛 1,400 | 🌐 Python | 📅 2024-08-07 - Easy & flexible alerting for Elasticsearch.
* [Ganglia](http://ganglia.info/) - A scalable distributed monitoring system for high-performance computing systems such as clusters and grids.
* [Grafana](http://grafana.org/) - An open source, feature rich metrics dashboard and graph editor for Graphite, InfluxDB & OpenTSDB.
* [Graphite](http://graphite.wikidot.com/) - Scalable realtime graphing.
* [IOpipe (c)](https://www.iopipe.com/) - Application performance monitoring for Amazon Lambda.
* [Jaeger](https://www.jaegertracing.io/) - An open source, end-to-end distributed tracing
* [OpenTelemetry](https://opentelemetry.io/) - High-quality, ubiquitous, and portable telemetry to enable effective observability.
* [Prometheus](http://prometheus.io/) - An open source service monitoring system and time series database.
* [Riemann](http://riemann.io/) - Monitors distributed systems.
* [Sensu](https://github.com/sensu) - Monitoring for today's infrastructure.
* [SkyWalking](https://skywalking.apache.org/) - Application performance monitor tool for distributed systems, especially designed for microservices, cloud native and container-based (Docker, K8s, Mesos) architectures.
* [Zabbix](http://www.zabbix.com/) - Open source enterprise-class monitoring solution.
* [Zipkin](http://zipkin.io) - Distributed tracing system.

### Reactivity

* [Reactor.io](https://github.com/reactor) - A second-generation Reactive library for building non-blocking applications on the JVM based on the Reactive Streams Specification.
* [Reactive Kafka](https://github.com/akka/alpakka-kafka) ⭐ 1,422 | 🐛 109 | 🌐 Scala | 📅 2025-11-21 - Reactive Streams API for Apache Kafka.
* [ReactiveX](http://reactivex.io/) - API for asynchronous programming with observable streams. Available for idiomatic Java, Scala, C#, C++, Clojure, JavaScript, Python, Groovy, JRuby, and others.
* [RSocket](https://rsocket.io/) - Application protocol providing Reactive Streams semantics.

### Resilience

* [Resilience4j](https://github.com/resilience4j/resilience4j) ⭐ 10,551 | 🐛 279 | 🌐 Java | 📅 2026-02-06 - Fault tolerance library designed for Java8 and functional programming.
* [Awesome Chaos Engineering](https://github.com/dastergon/awesome-chaos-engineering) ⭐ 6,497 | 🐛 55 | 📅 2023-12-28 :star: - A curated list of awesome chaos engineering resources.
* [Raft Consensus](https://raft.github.io/) - Consensus algorithm that is designed to be easy to understand. It's equivalent to Paxos in fault-tolerance and performance.
* [Svix](https://svix.com) - Webhooks service that sends webhooks to your users with full retry schedules, exponential backoff, signature verification, and event types.

### Security

* [Keycloak](https://github.com/keycloak/keycloak) ⭐ 32,904 | 🐛 2,553 | 🌐 Java | 📅 2026-02-19 - Full-featured and extensible auth service. OpenID Connect provider and third-party OAuth 2.0 delegation.
* [Dex](https://github.com/coreos/dex) ⭐ 10,591 | 🐛 496 | 🌐 Go | 📅 2026-02-18 - Opinionated auth/directory service with pluggable connectors. OpenID Connect provider and third-party OAuth 2.0 delegation.
* [Light OAuth2](https://github.com/networknt/light-oauth2) ⚠️ Archived - A fast, lightweight and cloud native OAuth 2.0 authorization microservices based on light-java.
* [Cerbos Hub](https://www.cerbos.dev/product-cerbos-hub) - Authorization management system for authoring, testing, and deploying access policies. Built scalable, fine-grained authorization in a microservice architecture.
* [JWT](http://jwt.io/) - JSON Web Tokens are an open, industry standard RFC 7519 method for representing claims securely between two parties.
* [OAuth](http://oauth.net/2/) - Provides specific authorization flows for web applications, desktop applications, mobile phones, and living room devices. Many implementations.
* [OpenID Connect](https://openid.net/certified-open-id-developer-tools/) - Libraries, products, and tools implementing current OpenID specifications and related specs.
* [Open Ziti](https://openziti.io/) - Zero trust security and overlay networking as pure open source software.
* [ORY](https://www.ory.sh/) - Open source identity infrastructure and services.
* [SCIM](https://simplecloud.info/) - System for Cross-domain Identity Management.
* [Vault](https://www.vaultproject.io/) - Secures, stores, and tightly controls access to tokens, passwords, certificates, API keys, and other secrets in modern computing.

### Serialization

* [Fastjson](https://github.com/alibaba/fastjson) ⚠️ Archived - Fast JSON Processor.
* [Jackson](https://github.com/FasterXML/jackson) ⭐ 9,669 | 🐛 1 | 📅 2026-02-13 -  A multi-purpose Java library for processing JSON data format.
* [Kryo](https://github.com/EsotericSoftware/kryo) ⭐ 6,488 | 🐛 35 | 🌐 HTML | 📅 2026-02-16 - Java serialization and cloning: fast, efficient, automatic.
* [Ffjson](https://github.com/pquerna/ffjson) ⭐ 2,994 | 🐛 59 | 🌐 Go | 📅 2023-09-21 - Faster JSON serialization for Go.
* [Bond](https://github.com/microsoft/bond/) ⚠️ Archived - Cross-platform framework for working with schematized data, broadly used at Microsoft in high scale services.
* [Protostuff](https://github.com/protostuff/protostuff) ⭐ 2,095 | 🐛 100 | 🌐 Java | 📅 2025-04-02 - A serialization library with built-in support for forward-backward compatibility (schema evolution) and validation.
* [FST](https://github.com/RuedigerMoeller/fast-serialization) ⭐ 1,594 | 🐛 126 | 🌐 Java | 📅 2023-06-30 - Fast java serialization drop in-replacement.
* [Cheshire](https://github.com/dakrone/cheshire) ⭐ 1,545 | 🐛 52 | 🌐 Clojure | 📅 2025-09-25 - Clojure JSON and JSON SMILE encoding/decoding.
* [BooPickle](https://github.com/ochrons/boopickle) ⭐ 368 | 🐛 27 | 🌐 Scala | 📅 2025-08-11 - Binary serialization library for efficient network communication. For Scala and Scala.js
* [Jackson Afterburner](https://github.com/FasterXML/jackson-module-afterburner) ⚠️ Archived - Jackson module that uses bytecode generation to further speed up data binding (+30-40% throughput for serialization, deserialization).
* [SBinary](https://github.com/harrah/sbinary) ⭐ 74 | 🐛 0 | 🌐 Scala | 📅 2015-12-06 - Library for describing binary formats for Scala types.
* [Avro](https://avro.apache.org/) - Apache data serialization system providing rich data structures in a compact, fast, binary data format.
* [Cap’n Proto](https://capnproto.org/) - Insanely fast data interchange format and capability-based RPC system.
* [CBOR](http://cbor.io/) - Implementations of the CBOR standard (RFC 7049) in many languages.
* [Cereal](http://uscilab.github.io/cereal/) - C++11 library for serialization.
* [Etch](http://etch.apache.org/) - Cross-platform, language and transport-independent framework for building and consuming network services.
* [MessagePack](http://msgpack.org/) - Efficient binary serialization format.
* [Thrift](http://thrift.apache.org/) - The Apache Thrift software framework, for scalable cross-language services development.

### Storage

* [InfluxDB](https://github.com/influxdata/influxdb) ⭐ 31,251 | 🐛 2,132 | 🌐 Rust | 📅 2026-02-19 - Scalable datastore for metrics, events, and real-time analytics.
* [Citus](https://github.com/citusdata/citus) ⭐ 12,294 | 🐛 1,050 | 🌐 C | 📅 2026-02-17 - Distributed PostgreSQL as an extension.
* [Alluxio](https://github.com/Alluxio/alluxio) ⭐ 7,157 | 🐛 1,039 | 🌐 Java | 📅 2025-04-29 - Virtual distributed storage system.
* [Pilosa](https://github.com/pilosa/pilosa) ⚠️ Archived - Open source, distributed bitmap index that dramatically accelerates queries across multiple, massive data sets.
* [AtlasDB](https://github.com/palantir/atlasdb) ⚠️ Archived - Transactional layer on top of a key value store.
* [Secure Scuttlebutt](https://github.com/ssbc/docs) ⭐ 61 | 🐛 0 | 🌐 Shell | 📅 2021-12-13 - P2P database of message-feeds.
* [Apache Cassandra](http://cassandra.apache.org) - Column-oriented and providing high availability with no single point of failure.
* [Aerospike (c)](http://www.aerospike.com/) - High performance NoSQL database delivering speed at scale.
* [ArangoDB](https://www.arangodb.com/) - A distributed free and open source database with a flexible data model for documents, graphs, and key-values.
* [CockroachDB (c)](https://www.cockroachlabs.com/) - A cloud-native SQL database modelled after Google Spanner.
* [Couchbase](https://github.com/couchbase) - A distributed database engineered for performance, scalability, and simplified administration.
* [Crate (c)](https://crate.io/) - Scalable SQL database with the NoSQL goodies.
* [Datomic](http://www.datomic.com/) - Fully transactional, cloud-ready, distributed database.
* [Druid](http://druid.io/) - Fast column-oriented distributed data store.
* [Elasticsearch](https://www.elastic.co/elasticsearch) - Open source distributed, scalable, and highly available search server.
* [Geode](http://geode.incubator.apache.org/) - Open source, distributed, in-memory database for scale-out applications.
* [Infinispan](http://infinispan.org/) - Highly concurrent key/value datastore used for caching.
* [OpenTSDB](http://opentsdb.net) - Scalable and distributed time series database written on top of Apache HBase.
* [RethinkDB](http://rethinkdb.com/) - Open source, scalable database that makes building realtime apps easier.
* [TiKV](https://github.com/tikv) - Distributed transactional key-value database.
* [Trino](https://trino.io/) - Fast distributed SQL query engine for big data analytics that helps you explore your data universe.

### Testing

* [Goreplay](https://github.com/buger/goreplay) ⭐ 19,247 | 🐛 341 | 🌐 Go | 📅 2026-01-27 - A tool for capturing and replaying live HTTP traffic into a test environment.
* [VCR](https://github.com/vcr/vcr) ⭐ 6,032 | 🐛 87 | 🌐 Ruby | 📅 2026-01-21 - Record your test suite's HTTP interactions and replay them during future test runs for fast, deterministic, accurate tests. See the list of ports for implementations in other languages.
* [Hoverfly](https://github.com/spectolabs/hoverfly) ⭐ 2,466 | 🐛 34 | 🌐 Go | 📅 2026-02-14 - Lightweight service virtualization/API simulation tool for developers and testers.
* [RestQA](https://github.com/restqa/restqa) ⭐ 93 | 🐛 18 | 🌐 JavaScript | 📅 2024-09-13 - A tool to manage microservices mocking, unit and performance testing locally with best in class developer experience.
* [Wilma](https://github.com/epam/Wilma) ⭐ 59 | 🐛 9 | 🌐 Java | 📅 2024-08-31 - Combined HTTP/HTTPS service stub and transparent proxy solution.
* [Mitmproxy](https://mitmproxy.org/) - An interactive console program that allows traffic flows to be intercepted, inspected, modified and replayed.
* [Mountebank](http://www.mbtest.org/) - Cross-platform, multi-protocol test doubles over the wire.
* [Pact](https://docs.pact.io) - Contract testing framework for HTTP APIs and non-HTTP asynchronous messaging systems.
* [Spring Cloud Contract](https://cloud.spring.io/spring-cloud-contract/) - TDD to the level of software architecture.
* [WireMock](http://wiremock.org/) - Flexible library for stubbing and mocking web services. Unlike general purpose mocking tools it works by creating an actual HTTP server that your code under test can connect to as it would a real web service.

## Continuous Integration & Delivery

* [Awesome CI/CD DevOps](https://github.com/ciandcd/awesome-ciandcd) ⭐ 1,982 | 🐛 19 | 📅 2024-04-01 :star: - A curated list of awesome tools for continuous integration, continuous delivery and DevOps.

## Web API Modeling & Documentation

### Async

* [AsyncAPI](https://github.com/asyncapi/spec) ⭐ 5,096 | 🐛 39 | 🌐 JavaScript | 📅 2026-02-14 - AsyncAPI specification, the industry standard for defining asynchronous APIs.

### GraphQL

* [GraphQL](http://graphql.org/) - Query language designed to build client applications by providing an intuitive and flexible syntax and system for describing their data requirements and interactions.

### JSON

* [JSON:API](https://jsonapi.org/) - A specification for how a client should request that resources be fetched or modified, and how a server should respond to those requests.

### REST

* [Slate](https://github.com/slatedocs/slate) ⚠️ Archived - Beautiful static documentation for your API.
* [ReDoc](https://github.com/Redocly/redoc) ⭐ 25,501 | 🐛 429 | 🌐 TypeScript | 📅 2026-02-07 - OpenAPI/Swagger-generated API Documentation.
* [Scalar](https://github.com/scalar/scalar) ⭐ 13,961 | 🐛 170 | 🌐 TypeScript | 📅 2026-02-19 - Open-source API platform: beautiful API references and 1st-class OpenAPI/Swagger support.
* [API Blueprint](https://apiblueprint.org/) - Tools for your whole API lifecycle. Use it to discuss your API with others. Generate documentation automatically. Or a test suite. Or even some code.
* [OpenAPI](https://www.openapis.org/) - The OpenAPI Specification (OAS) provides a consistent means to carry information through each stage of the API lifecycle.
* [RAML](http://raml.org/) - RESTful API Modeling Language, a simple and succinct way of describing practically-RESTful APIs.
* [Spring REST Docs](http://projects.spring.io/spring-restdocs/) - Document RESTful services by combining hand-written documentation with auto-generated snippets produced with Spring MVC Test.
* [Swagger](https://swagger.io/) - A simple yet powerful representation of your RESTful API.

## Standards / Recommendations

### World Wide Web

* [W3C.REC-Webarch](http://www.w3.org/TR/webarch/) - Architecture of the World Wide Web, Volume One.
* [RFC3986](https://tools.ietf.org/html/rfc3986) - Uniform Resource Identifier (URI): Generic Syntax.
* [RFC6570](https://tools.ietf.org/html/rfc6570) - URI Template.
* [RFC7320](https://tools.ietf.org/html/rfc7320) - URI Design and Ownership.

### Self-sovereignty & Decentralisation

* [DID](https://www.w3.org/TR/did-core/) - W3C specification of Decentralized identifiers (DIDs): a new type of identifier that enables verifiable, decentralized digital identity.
* [DIDComm](https://github.com/decentralized-identity/didcomm-messaging) ⭐ 183 | 🐛 42 | 🌐 JavaScript | 📅 2025-09-12 - Private communication methodology built atop the decentralized design of DIDs.
* [DIDComm Protocols](https://didcomm.org/) - Registry of protocols built on DIDComm, for high-trust, self-sovereign interactions over any transport.
* [IDSA](https://internationaldataspaces.org/) - The International Data Spaces Association (IDSA) is on a mission to create the future of the global, digital economy with International Data Spaces (IDS), a secure, sovereign system of data sharing in which all participants can realize the full value of their data.

### HTTP/1.1

* [RFC7230](https://tools.ietf.org/html/rfc7230) - Message Syntax and Routing.
* [RFC7231](https://tools.ietf.org/html/rfc7231) - Semantics and Content.
* [RFC7232](https://tools.ietf.org/html/rfc7232) - Conditional Requests.
* [RFC7233](https://tools.ietf.org/html/rfc7233) - Range Requests.
* [RFC7234](https://tools.ietf.org/html/rfc7234) - Caching.
* [RFC7235](https://tools.ietf.org/html/rfc7235) - Authentication.
* [RFC7807](https://tools.ietf.org/html/rfc7807) - Problem Details for HTTP APIs.

### HTTP/2

* [RFC7540](https://tools.ietf.org/html/rfc7540) - Hypertext Transfer Protocol Version 2.

### QUIC

* [QUIC-WG](https://quicwg.org/) - IETF Working Group that is chartered to deliver the next transport protocol for the Internet.
* [QUIC-Transport](https://tools.ietf.org/html/draft-ietf-quic-transport-27) - A UDP-based multiplexed and secure transport.

### RPC

* [JSON-RPC 2.0](http://www.jsonrpc.org/specification) - A stateless, light-weight remote procedure call (RPC) protocol.
* [Open RPC](https://open-rpc.org/) - The OpenRPC Specification defines a standard, programming language-agnostic interface description for JSON-RPC 2.0 APIs.

### Messaging

* [AMQP](https://www.amqp.org/) - Advanced Message Queuing Protocol.
* [MQTT](https://mqtt.org/) - MQ Telemetry Transport.
* [STOMP](https://stomp.github.io/) - Simple Text Oriented Messaging Protocol.

### Security

* [GNAP](https://datatracker.ietf.org/doc/html/draft-ietf-gnap-core-protocol) - Grant Negotiation and Authorization Protocol defines a mechanism for delegating authorization to a piece of software, and conveying that delegation to the software. This delegation can include access to a set of APIs as well as information passed directly to the software.<sup>DRAFT</sup>
* [OIDCONN](http://openid.net/connect/) - OpenID Connect 1.0 is a simple identity layer on top of the OAuth 2.0 protocol. It allows clients to verify the identity of the end-user based on the authentication performed by an Authorization Server, as well as to obtain basic profile information about the end-user in an interoperable and REST-like manner.
* [PASETO](https://paseto.io/) - Paseto is everything you love about JOSE (JWT, JWE, JWS) without any of the many design deficits that plague the JOSE standards. <sup>DRAFT</sup>
* [RFC5246](https://tools.ietf.org/html/rfc5246) - The Transport Layer Security (TLS) Protocol Version 1.2.
* [RFC6066](https://tools.ietf.org/html/rfc6066) - TLS Extensions.
* [RFC6347](https://tools.ietf.org/html/rfc6347) - Datagram Transport Layer Security Version 1.2.
* [RFC6749](https://tools.ietf.org/html/rfc6749) - The OAuth 2.0 authorization framework.
* [RFC6962](https://tools.ietf.org/html/rfc6962) - Certificate transparency.
* [RFC7515](https://tools.ietf.org/html/rfc7515) - JSON Web Signature (JWS) represents content secured with digital signatures or Message Authentication Codes (MACs) using JSON-based data structures.
* [RFC7519](https://tools.ietf.org/html/rfc7519) - JSON Web Token (JWT) is a compact, URL-safe means of representing claims to be transferred between two parties.
* [RFC7642](https://tools.ietf.org/html/rfc7642) - SCIM: Definitions, overview, concepts, and requirements.
* [RFC7643](https://tools.ietf.org/html/rfc7643) - SCIM: Core Schema, provides a platform-neutral schema and extension model for representing users and groups.
* [RFC7644](https://tools.ietf.org/html/rfc7644) - SCIM: Protocol, an application-level, REST protocol for provisioning and managing identity data on the web.

### Service Discovery

* [DNS-SD](https://datatracker.ietf.org/doc/html/rfc6763) - Mechanism for clients to discover a list of named instances of a service, using standard DNS queries.
* [RFC2782](https://datatracker.ietf.org/doc/html/rfc2782) - A DNS RR for specifying the location of services (DNS SRV).

### Data Formats

* [MSGPACK](https://github.com/msgpack/msgpack/blob/master/spec.md) ⭐ 7,412 | 🐛 94 | 📅 2024-08-10 - MessagePack Specification.
* [SBE](https://github.com/FIXTradingCommunity/fix-simple-binary-encoding) ⭐ 301 | 🐛 30 | 🌐 HTML | 📅 2025-06-22 - Simple Binary Encoding (SBE).
* [RFC4627](https://tools.ietf.org/html/rfc4627) - JavaScript Object Notation (JSON).
* [RFC7049](https://tools.ietf.org/html/rfc7049) - Concise Binary Object Representation (CBOR).
* [BSON](http://bsonspec.org/) - Binary JSON (BSON).
* [JSON-LD](http://json-ld.org/) - JSON for Linking Data.

### Vocabularies

* [JSON Schema](http://json-schema.org/) - Vocabulary that allows you to annotate and validate JSON documents.
* [Schema.org](http://schema.org/) - Collaborative, community activity with a mission to create, maintain, and promote schemas for structured data on the Internet, on web pages, in email messages, and beyond.

### Unicode

* [UNIV8](http://www.unicode.org/versions/Unicode8.0.0/) - The Unicode Consortium. The Unicode Standard, Version 8.0.0, (Mountain View, CA: The Unicode Consortium, 2015. ISBN 978-1-936213-10-8).
* [RFC3629](https://tools.ietf.org/html/rfc3629) - UTF-8, a transformation format of ISO 10646.

## Organization Design / Team Dynamics

* [How Do Committees Invent?](http://www.melconway.com/Home/pdf/committees.pdf) :small\_orange\_diamond:<sup>PDF</sup> - Melvin E. Conway, Datamation magazine 1968. The original article defining Conway's Law.
* [Service per Team](https://microservices.io/patterns/decomposition/service-per-team.html) - Each team is responsible for one or more business functions (e.g. business capabilities). A team owns a code base consisting of one or more modules. Its code base is sized so as to not exceed the cognitive capacity of team. The team deploys its code as one or more services. A team should have exactly one service unless there is a proven need to have multiple services.
* [Start with Team Cognitive Load - Team Topologies](https://www.youtube.com/watch?v=haejb5rzKsM) :small\_red\_triangle:<sup>YT</sup> - DOES19 London. The "monoliths vs microservices" debate often focuses on technological aspects, ignoring strategy and team dynamics. Instead of technology, smart-thinking organizations are beginning with team cognitive load as the guiding principle for modern software. In this talk, we explain how and why, illustrated by real case studies.

## Enterprise & Verticals

* [Commercetools](https://commercetools.com/) - Headless commerce platform.
* [Equinox](https://www.infosysequinox.com/) - Infosys Equinox is a human-centric commerce and marketing platform that supports rich, hyper-personalized experiences across any channel and touchpoint.
* [Flamingo](https://www.flamingo.me/) - Framework to build flexible and modern e-commerce applications.
* [Medusa](https://medusajs.com/) - Headless open source commerce platform.

## Theory

### Articles & Papers

* [Autonomy, Hyperconnectivity, and Residual Causality](https://www.mdpi.com/2409-9287/6/4/81) - Philosophical introduction to the design of adaptive hyperliminal systems through complexity science theories.
* [Awesome Scalability](https://github.com/binhnguyennus/awesome-scalability) ⭐ 68,693 | 🐛 20 | 📅 2026-01-04 :star: - An updated and organized reading list for illustrating the patterns of scalable, reliable, and performant large-scale systems. Concepts are explained in the articles of prominent engineers and credible references. Case studies are taken from battle-tested systems that serve millions to billions of users.
* [AKF Scale Cube](http://akfpartners.com/techblog/2008/05/08/splitting-applications-or-services-for-scale/) - Model depicting the dimensions to scale a service.
* [CALM](http://db.cs.berkeley.edu/papers/cidr11-bloom.pdf) :small\_orange\_diamond:<sup>PDF</sup> - Consistency as logical monotonicity.
* [Canary Release](http://martinfowler.com/bliki/CanaryRelease.html) - Technique to reduce the risk of introducing a new software version in production by slowly rolling out the change to a small subset of users before rolling it out to the entire infrastructure and making it available to everybody.
* [CAP Theorem](http://blog.thislongrun.com/2015/03/the-cap-theorem-series.html) -  States that it is impossible for a distributed computer system to simultaneously provide all three of the following guarantees: Consistency, Availability and Partition tolerance.
* [Formal Foundations of Serverless Computing](https://arxiv.org/pdf/1902.05870.pdf) :small\_orange\_diamond:<sup>PDF</sup> - The serverless computing abstraction exposes several low-level operational details that make it hard for programmers to write and reason about their code. This paper sheds light on this problem by presenting λ, an operational semantics of the essence of serverless computing.
* [Microservice Architecture](http://martinfowler.com/articles/microservices.html) - Particular way of designing software applications as suites of independently deployable services.
* [Microservices - From Design to Deployment](https://www.f5.com/content/dam/f5/corp/global/pdf/ebooks/Microservices_Designing_Deploying.pdf) :small\_orange\_diamond:<sup>PDF</sup> - F5's seven-part series on microservices.
* [Microservices – Please, don’t](https://riak.com/posts/technical/microservices-please-dont/) - Critical advice about some problems regarding a microservices approach.
* [Microservices Trade-Offs](http://martinfowler.com/articles/microservice-trade-offs.html) - Guide to ponder costs and benefits of the mircoservices architectural style.
* [Reactive Manifesto](http://www.reactivemanifesto.org/) - Reactive systems definition.
* [Reactive Streams](http://www.reactive-streams.org/) - Initiative to provide a standard for asynchronous stream processing with non-blocking back pressure.
* [ROCAS](http://resources.1060research.com/docs/2015/Resource-Oriented-Computing-Adaptive-Systems-ROCAS-1.2.pdf) :small\_orange\_diamond:<sup>PDF</sup> - Resource Oriented Computing for Adaptive Systems.
* [SECO](http://ceur-ws.org/Vol-746/IWSECO2011-6-DengYu.pdf) :small\_orange\_diamond:<sup>PDF</sup> - Understanding software ecosystems: a strategic modeling approach.
* [Testing Strategies in a Microservice Architecture](http://martinfowler.com/articles/microservice-testing/) - Approaches for managing the additional testing complexity of multiple independently deployable components.
* [Your Server as a Function](http://monkey.org/~marius/funsrv.pdf) :small\_orange\_diamond:<sup>PDF</sup> - Describes three abstractions which combine to present a powerful programming model for building safe, modular, and efficient server software: Composable futures, services and filters.

### Sites & Organizations

* [Cloud Native Computing Foundation](https://www.cncf.io/) - The Cloud Native Computing Foundation builds sustainable ecosystems and fosters a community around a constellation of high-quality projects that orchestrate containers as part of a microservices architecture.
* [CNCF Cloud Native Interactive Landscape](https://landscape.cncf.io/) - Interactive landscape of cloud native technologies.
* [Microservices Resource Guide](http://martinfowler.com/microservices/) - Martin Fowler's choice of articles, videos, books, and podcasts that can teach you more about the microservices architectural style.
* [Microservice Patterns](http://microservices.io/) - Microservice architecture patterns and best practices.
* [Microservice Antipatterns and Pitfalls](https://www.oreilly.com/ideas/microservices-antipatterns-and-pitfalls) - Microservice mostly known antipatterns and pitfalls.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

## Contributing

Please, read the [Contribution Guidelines](https://github.com/mfornos/awesome-microservices/blob/master/CONTRIBUTING.md) ⭐ 14,146 | 🐛 7 | 📅 2026-01-17 before submitting your suggestion.

Feel free to [open an issue](https://github.com/mfornos/awesome-microservices/issues) ⭐ 14,146 | 🐛 7 | 📅 2026-01-17 or [create a pull request](https://github.com/mfornos/awesome-microservices/pulls) ⭐ 14,146 | 🐛 7 | 📅 2026-01-17 with your additions.

:star2: Thank you!
