# Rust Template

> Template for Rust projects @okp4.

[![version](https://img.shields.io/github/v/release/okp4/template-rust)](https://github.com/okp4/template-rust/releases)
[![build](https://github.com/okp4/template-rust/actions/workflows/build.yml/badge.svg)](https://github.com/okp4/template-rust/actions/workflows/build.yml)
[![lint](https://github.com/okp4/template-rust/actions/workflows/lint.yml/badge.svg)](https://github.com/okp4/template-rust/actions/workflows/lint.yml)
[![test](https://github.com/okp4/template-rust/actions/workflows/test.yml/badge.svg)](https://github.com/okp4/template-rust/actions/workflows/test.yml)
[![conventional commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)
[![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

## Purpose & Philosophy

This repository holds the template for building Rust projects with a consistent set of standards accross all [OKP4](https://github.com/okp4) projects. We are convinced that the quality of the code depends on clear and consistent coding conventions, with an automated enforcement (CI).

This way, the template promotes:

- the use of [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/), [semantic versionning](https://semver.org/) and [semantic releasing](https://github.com/cycjimmy/semantic-release-action) which automates the whole package release workflow including: determining the next version number, generating the release notes, and publishing the artifacts (project tarball, docker images, etc.)
- unit testing
- linting via [rust-clippy](https://github.com/rust-lang/rust-clippy)
- formatting via [rustfmt](https://github.com/rust-lang/rustfmt)
- a uniform way of building via [cargo-make](https://github.com/sagiegurari/cargo-make)

## Prerequisites

Be sure you have [Rust](https://www.rust-lang.org/tools/install) properly installed with [cargo-make](https://github.com/sagiegurari/cargo-make).

## Build

```sh
cargo make
```
