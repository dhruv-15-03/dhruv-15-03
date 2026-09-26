# Dhruv Rastogi

Backend engineer. Java and Spring Boot at work; compilers and open source (Java, Rust) outside it.

## Merged contributions to other people's projects

| Project | PR | What it fixed |
|---|---|---|
| [spring-projects/spring-boot](https://github.com/spring-projects/spring-boot) | [#50779](https://github.com/spring-projects/spring-boot/pull/50779) | The `java.util.logging` bridge handler was being removed even when the application had not installed it. Now it is only removed if it was installed. |
| [github/spec-kit](https://github.com/github/spec-kit) | [#3413](https://github.com/github/spec-kit/pull/3413) | Added configurable Conventional Commit support to the git extension. |
| [uutils/coreutils](https://github.com/uutils/coreutils) | [#13718](https://github.com/uutils/coreutils/pull/13718) | `join` was not applying the `-e` filler to empty output fields. |
| [uutils/coreutils](https://github.com/uutils/coreutils) | [#13719](https://github.com/uutils/coreutils/pull/13719) | `test` compared integers wider than `i128` incorrectly. |
| [uutils/coreutils](https://github.com/uutils/coreutils) | [#13731](https://github.com/uutils/coreutils/pull/13731) | `chmod` reported a umask-curtailed mode for operands that only looked like options. |

uutils/coreutils is an independent Rust reimplementation of the GNU Coreutils
command-line tools. It is not GNU Coreutils.

Currently open: [github/spec-kit#3748](https://github.com/github/spec-kit/pull/3748),
which makes agent CLI executable resolution happen in one place so the preflight
check and the actual dispatch cannot disagree.

## Projects

**[DhrLang](https://github.com/dhruv-15-03/DhrLang)** — a statically typed,
object-oriented JVM language written from scratch: lexer, parser, type checker with
generics, three execution backends (AST walker, IR, bytecode), an LSP server and a
VS Code extension, plus an experimental EVM target. Java, MIT.

**[boot-usage](https://github.com/dhruv-15-03/boot-usage)** — a Spring Boot starter
with an Actuator endpoint that reports which starters are actually used, unused or
indeterminate at runtime. Distributed via JitPack and GitHub Releases. Listed in
[awesome-java](https://github.com/akullpp/awesome-java) ([#1173](https://github.com/akullpp/awesome-java/pull/1173)).

**AI CourtRoom** — a legal case-management app in two repos:
[AI-CourtRoom](https://github.com/dhruv-15-03/AI-CourtRoom) (React frontend +
Spring Boot backend, with Resilience4j circuit breakers around the AI dependency)
and [AI-court-AI](https://github.com/dhruv-15-03/AI-court-AI) (the Python ML/LLM
service for retrieval-augmented answers and case prediction).
[Live demo](https://ai-court-room-iota.vercel.app).

**[spec-kit-ears](https://github.com/dhruv-15-03/spec-kit-ears)** — an EARS (Easy
Approach to Requirements Syntax) extension for GitHub's Spec Kit.

**[Orchestrator](https://github.com/dhruv-15-03/Orchestrator)** — a microservices
orchestrator demonstrating the Saga pattern with rollback, built on event-driven
reactive Spring Boot.

**[AlgoVisualizer](https://github.com/dhruv-15-03/AlgoVisualizer)** — edit real
Python ML code in the browser and watch the algorithm train step by step on real
datasets.

## Work

Associate Software Engineer at MAQ Software (since Nov 2025): Java/Spring Boot
features for an internal business application, and an internal RAG-based,
multi-agent slide-deck application in C#/.NET and React.

Java, Spring Boot, Rust, Python, TypeScript/React, MySQL, Redis, Docker, GitHub Actions.

dhruvrastogi2004@gmail.com. Open to backend and platform roles, remote or India.
