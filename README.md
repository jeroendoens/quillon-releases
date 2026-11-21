# Quillon releases

Signed images and release notes of **Quillon**, an operating system for the Raspberry Pi 5, written in Rust.

**This repository holds no source code.** It holds only the signed release files that Quillon devices download for updates.

## Source code

From the release **1.0.0** on, a source snapshot of each official release will be published in a separate repository: [`jeroendoens/quillon-src`](https://github.com/jeroendoens/quillon-src).

- One snapshot per official release, with a signed tag. It holds the kernel, the OS libraries, the apps and the SDK, plus the documents needed to build them.
- It does not hold the private development history, internal documents or measurements.
- Beta builds are not part of it.
- The snapshot is a read-only mirror at first: no issues and no pull requests.
- The licence of the source and the terms for the images will be published together with 1.0.0. Until then, please do not redistribute images from this repository.

## Releases and updates

- Every release file is signed. A Quillon device installs an update only when the signature matches the official Quillon key. A modified build cannot pass this check.
- There are two update channels, Stable and Beta. Only Stable releases are official.
- Versions use the form `MAJOR.MINOR.PATCH`. Versions below 1.0.0 are development milestones. The first public release is 1.0.0 (codename Pils).

## Status

Quillon is in development. This page will list the contact for security reports when 1.0.0 is released.
