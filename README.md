# Rust Template

> Template for Rust projects @okp4.

[![version](https://img.shields.io/github/v/release/okp4/template-rust?style=for-the-badge&logo=github)](https://github.com/okp4/template-rust/releases)
[![build](https://img.shields.io/github/actions/workflow/status/okp4/template-rust/build.yml?branch=main&label=build&style=for-the-badge&logo=github)](https://github.com/okp4/template-rust/actions/workflows/build.yml)
[![lint](https://img.shields.io/github/actions/workflow/status/okp4/template-rust/lint.yml?branch=main&label=lint&style=for-the-badge&logo=github)](https://github.com/okp4/template-rust/actions/workflows/lint.yml)
[![test](https://img.shields.io/github/actions/workflow/status/okp4/template-rust/test.yml?branch=main&label=test&style=for-the-badge&logo=github)](https://github.com/okp4/template-rust/actions/workflows/test.yml)
[![codecov](https://img.shields.io/codecov/c/github/okp4/template-rust?style=for-the-badge&token=K5CYM8TQQY&logo=codecov)](https://codecov.io/gh/okp4/template-rust)
[![conventional commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg?style=for-the-badge&logo=conventionalcommits)](https://conventionalcommits.org)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=for-the-badge)](https://github.com/semantic-release/semantic-release)
[![contributor covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg?style=for-the-badge)](https://github.com/okp4/.github/blob/main/CODE_OF_CONDUCT.md)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg?style=for-the-badge)](https://opensource.org/licenses/BSD-3-Clause)

## Purpose & Philosophy

This repository holds the template for building Rust projects with a consistent set of standards across all [OKP4](https://github.com/okp4) projects. We are convinced that the quality of the code depends on clear and consistent coding conventions, with an automated enforcement (CI).

This way, the template promotes:

- the use of [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/), [semantic versioning](https://semver.org/) and [semantic releasing](https://github.com/cycjimmy/semantic-release-action) which automates the whole package release workflow including: determining the next version number, generating the release notes, and publishing the artifacts (project tarball, docker images, etc.)
- unit testing
- linting via [rust-clippy](https://github.com/rust-lang/rust-clippy)
- formatting via [rustfmt](https://github.com/rust-lang/rustfmt)
- a uniform way of building via [cargo-make](https://github.com/sagiegurari/cargo-make)

## How to use

> 🚨 do not fork this repository as it is a [template repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)

1. Click on [Use this template](https://github.com/okp4/template-rust/generate)
2. Give a name to your project
3. Wait until the first run of CI finishes
4. Clone your new project and happy coding!

⚠ Do not forget to adapt your project to your needs by editing the `Cargo.toml` file.

## Prerequisites

Be sure you have [Rust](https://www.rust-lang.org/tools/install) properly installed with [cargo-make](https://github.com/sagiegurari/cargo-make).

## Build

```sh
cargo make
```
