Packaging
=========

This file contains quick reminders and notes on how to package Sonic.

We consider here the packaging flow of Sonic version `1.0.0` for Linux.

1. **How to bump Sonic version before a release:**
    1. Bump version in `Cargo.toml` to `1.0.0`
    2. Execute `cargo update` to bump `Cargo.lock`

2. **How to build Sonic, package it and release it on Crates, GitHub and Docker Hub (multiple architectures):**
    1. Tag the latest Git commit corresponding to the release with tag `v1.0.0`, and push the tag
    2. Wait for all release jobs to complete on the [actions](https://github.com/valeriansaliou/sonic/actions) page on GitHub
    3. Publish a changelog on the [releases](https://github.com/valeriansaliou/sonic/releases) page on GitHub
