# Hi, I'm Dhruv Rastogi 👋

**Backend and platform engineer.** I write production Java/Spring services, and in my own time I work on compilers and contribute upstream to open source.

## What I'd point at first

**Three merged patches in [uutils/coreutils](https://github.com/uutils/coreutils)** — the Rust reimplementation of GNU coreutils (24k★). Behaviour fixes in [`join`](https://github.com/uutils/coreutils/pull/13718), [`test`](https://github.com/uutils/coreutils/pull/13719) and [`chmod`](https://github.com/uutils/coreutils/pull/13731); the last closed an issue that had been open since 2022. All three were the same exercise: run GNU as the reference, find where the reimplementation quietly disagrees, work out the exact rule, and pin it with a test. The patch is the easy part — characterising the rule precisely enough to know the fix is right, and not merely right on the example in the bug report, is the work.

Also merged upstream: **[spring-projects/spring-boot#50779](https://github.com/spring-projects/spring-boot/pull/50779)** (a JUL bridge install/uninstall asymmetry) and an entry in **[akullpp/awesome-java#1173](https://github.com/akullpp/awesome-java/pull/1173)**.

## Projects

- **[DhrLang](https://github.com/dhruv-15-03/DhrLang)** — a statically-typed, object-oriented **JVM language built from scratch**: lexer → parser → type checker with generics → typed IR → JVM bytecode. Ships an **LSP server** and a **VS Code extension**, plus an experimental EVM target. It runs three ways — straight off the AST, through an IR interpreter, and compiled to bytecode — with a parity suite that diffs the backends against the AST interpreter as the reference, because two implementations that are supposed to agree will not stay in agreement on their own.
  *v4.0.2 · 38 releases · 1,491 tests · MIT · JaCoCo + PIT mutation testing in CI*

- **[boot-usage](https://github.com/dhruv-15-03/boot-usage)** — a Spring Boot starter **published to Maven Central** that adds an Actuator endpoint to detect used and unused starters at runtime, so you can trim dependency bloat with evidence rather than guesswork.

- **[Orchestrator](https://github.com/dhruv-15-03/Orchestrator)** — an event-driven microservices orchestrator implementing the **Saga pattern with rollback** on reactive Spring Boot.

## Day to day

Java · Spring Boot · Python · SQL · Azure · Terraform · Docker · Kubernetes · CI/CD

Currently building ETL pipelines on Azure Fabric and Databricks, and owning the CI/CD and Terraform behind 10+ Function Apps. The thing that job taught me is that a pipeline failing loudly is the good case — the expensive one is a run that completes and quietly produces the wrong output.

📫 **dhruvrastogi2004@gmail.com** · Open to backend and platform roles, remote or India.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/dhruv-rastogi-3b744032b) [![LeetCode](https://img.shields.io/badge/LeetCode-FFA116.svg?logo=leetcode&logoColor=white)](https://leetcode.com/u/dhruv_1503/) [![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:dhruvrastogi2004@gmail.com)
