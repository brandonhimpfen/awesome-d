# Awesome D [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/brandonhimpfen/awesome-lists)

[![Support Open Work](https://img.shields.io/badge/Support-Open%20Work-0A0A0A?style=flat&logo=github)](https://github.com/brandonhimpfen/support) 
[![GitHub Sponsor](https://srv-cdn.himpfen.io/badges/github/github-flat.svg)](https://github.com/sponsors/brandonhimpfen) 
[![Buy Me a Coffee](https://srv-cdn.himpfen.io/badges/buymeacoffee/buymeacoffee-flat.svg)](https://buymeacoffee.com/brandonhimpfen) 
[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/brandonhimpfen) 
[![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) <br />
[![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) 
[![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of resources for the D programming language, web frameworks, async I/O engines, meta-programming toolkits, compilers, and game development libraries.

D is a high-level, statically typed systems programming language combining C-like performance and low-level control with powerful abstractions such as Compile-Time Function Execution (CTFE), design by contract, template metaprogramming, and memory safety guarantees (`@safe`). This list is intended for systems engineers, backend developers, game developers, and performance-critical software architects.

_Support ongoing maintenance and curation via [GitHub Sponsors](https://github.com/sponsors/brandonhimpfen)._

## Contents

- [Compilers & Build Systems](#compilers--build-systems)
- [Web Development & Async I/O](#web-development--async-io)
- [Metaprogramming & Serialization](#metaprogramming--serialization)
- [Database Toolkits & Data Access](#database-toolkits--data-access)
  - [SQL Drivers & ORMs](#sql-drivers--orms)
  - [Key-Value & NoSQL](#key-value--nosql)
- [Related Awesome Lists](#related-awesome-lists)

## Compilers & Build Systems

Official compilers, alternative backends, package managers, and build toolchains for the D language.

- [DMD (D Reference Compiler)](https://github.com/dlang/dmd) — Official reference compiler frontend and backend for the D programming language.
- [LDC (LLVM-based D Compiler)](https://github.com/ldc-developers/ldc) — D compiler utilizing the LLVM backend for high-performance code generation and optimization.
- [GDC (GNU D Compiler)](https://github.com/D-Programming-GDC/gdc) — D programming language frontend integrated into the GNU Compiler Collection (GCC).
- [DUB](https://github.com/dlang/dub) — Official package manager and build tool for D applications and libraries.

## Web Development & Async I/O

Asynchronous I/O frameworks, HTTP servers, microservices toolkits, and web frameworks.

- [Vibe.d](https://github.com/vibe-d/vibe.d) — Asynchronous I/O and web application framework built on fiber-based concurrency.
- [Handy-Httpd](https://github.com/andrewlalis/handy-httpd) — Lightweight, simple, and extensible HTTP server written in D.
- [Arsd Web Libraries](https://github.com/adamdruppe/arsd) — Versatile collection of single-file utility modules covering HTTP servers, DOM parsing, and terminal UI.
- [Serve-D](https://github.com/Pure-D/serve-d) — Language Server Protocol (LSP) implementation for D providing IDE auto-completion and diagnostics.

## Metaprogramming & Serialization

Compile-time reflection tools, code generation engines, and high-performance serialization libraries.

- [pegged](https://github.com/PhilippeSigaud/Pegged) — Parsing Expression Grammar (PEG) generator built entirely using D compile-time metaprogramming.
- [mir-algorithm](https://github.com/libmir/mir-algorithm) — Core package for high-performance numerical computing, multi-dimensional array operations, and data structures.
- [asdf](https://github.com/libmir/asdf) — High-performance cache-friendly JSON library designed for dynamic data inspection and serialization.
- [hibernated](https://github.com/vlad-kravchenko/hibernated) — Object-relational mapping (ORM) library using D compile-time introspection.

## Database Toolkits & Data Access

Database client drivers, query builders, and database abstractions for D projects.

### SQL Drivers & ORMs

- [dpq2](https://github.com/denizzzka/dpq2) — PostgreSQL driver for D wrapping the native `libpq` C library.
- [mysql-native](https://github.com/mysql-net/mysql-native) — Pure D implementation of the MySQL client protocol supporting fiber-based async I/O in Vibe.d.
- [d2sqlite3](https://github.com/bioexmachina/d2sqlite3) — Thin idiomatic D wrapper around the SQLite 3 C API.

### Key-Value & NoSQL

- [vibe-d-redis](https://github.com/vibe-d/vibe.d) — Asynchronous driver for Redis integrated directly into the Vibe.d framework ecosystem.

## Related Awesome Lists

- [Awesome Functional Programming](https://github.com/brandonhimpfen/awesome-functional-programming) — Purely functional languages, lambda calculus, type systems, and immutable data.
- [Awesome Java](https://github.com/brandonhimpfen/awesome-java) — High-performance JVM frameworks, concurrency libraries, and system tools.
- [Awesome Open Source](https://github.com/brandonhimpfen/awesome-open-source) — Best practices, licensing standards, and community management frameworks for open projects.

## Contribute

Contributions are welcome. Please ensure your submission fully follows the requirements outlined in [`CONTRIBUTING.md`](CONTRIBUTING.md), including formatting, scope alignment, and category placement.

Pull requests that do not adhere to the contribution guidelines may be closed.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
