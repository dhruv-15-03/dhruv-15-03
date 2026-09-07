# Dhruv Rastogi

Backend engineer. Java and Spring at work, compilers and open source outside it.

## Open source

Three merged patches in [uutils/coreutils](https://github.com/uutils/coreutils), the Rust rewrite of GNU coreutils:

- [`join`](https://github.com/uutils/coreutils/pull/13718) - the `-e` filler was not being applied to output fields that exist but are empty
- [`test`](https://github.com/uutils/coreutils/pull/13719) - integer comparison was wrong for values wider than i128
- [`chmod`](https://github.com/uutils/coreutils/pull/13731) - umask diagnostics were reported for operands that only looked like options, open as a bug since 2022

Also [spring-boot#50779](https://github.com/spring-projects/spring-boot/pull/50779), where the JUL bridge handler was removed even when the application had never installed it, and [awesome-java#1173](https://github.com/akullpp/awesome-java/pull/1173).

## Projects

**[DhrLang](https://github.com/dhruv-15-03/DhrLang)** - a statically typed JVM language I wrote from scratch. Lexer, parser, type checker with generics, a typed IR, and a JVM bytecode emitter. It runs three ways: straight off the AST, through an IR interpreter, or compiled to bytecode, and a parity suite diffs the other two against the AST interpreter. Ships an LSP server and a VS Code extension. v4.0.2, 38 releases, 1,491 tests, MIT.

**[boot-usage](https://github.com/dhruv-15-03/boot-usage)** - a Spring Boot starter on Maven Central. Adds an Actuator endpoint that reports which of your starters are actually used at runtime, so you can drop the ones that are not.

**[Orchestrator](https://github.com/dhruv-15-03/Orchestrator)** - an event driven microservice orchestrator implementing the Saga pattern with rollback, on reactive Spring Boot.

## Work

Currently building ETL pipelines on Azure Fabric and Databricks, and running the CI/CD and Terraform behind 10+ Function Apps.

Java, Spring Boot, Python, SQL, Azure, Terraform, Docker, Kubernetes.

dhruvrastogi2004@gmail.com. Open to backend and platform roles, remote or India.
