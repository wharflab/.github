# WharfLab 🐋

> Closing the gap in container development — one tool at a time.

WharfLab is an open source organization building developer tools and libraries for the container ecosystem. Our focus is on the parts of container development that deserve more love: better linting, smarter parsing, stricter policies, and deeper language support for the tooling that ships your software.

We write mostly in Go — the native language of container infrastructure — and we integrate directly with the lower layers: BuildKit, tree-sitter, ast-grep, and the OCI ecosystem.

## What we're working on

**Dockerfile tooling** — a modern linter/formatter built on top of the official BuildKit Dockerfile parser, with fast rule evaluation, auto-fixes, and AI-powered suggestions for the cases that require real reasoning.

**Container source policies** — ergonomic CLI tooling for generating Docker source policy files, making supply-chain controls easier to adopt.

**Language support** — first-class Dockerfile and Batch script grammars for the ast-grep and tree-sitter ecosystems, enabling structural code search and analysis across container-adjacent languages.

## Philosophy

Container tooling shouldn't stop at runtime. The gap between writing a `Dockerfile` and shipping a secure, well-structured image is full of rough edges. We build the tools that smooth them out.

All of our work is open source. Contributions, issues, and feedback are always welcome.
