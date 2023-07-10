# radxa-udev

[![Build & Release](https://github.com/radxa-pkg/radxa-udev/actions/workflows/release.yml/badge.svg)](https://github.com/radxa-pkg/radxa-udev/actions/workflows/release.yml)

This package provides Radxa custom udev rules to enhance RadxaOS.

## Development dependencies

<details>
<summary>Ubuntu</summary>

```bash
sudo apt-get update
sudo apt-get build-dep --no-install-recommends .
sudo apt-get install git-buildpackage
```
</details>

## Developer commands

`make dch`: generate changelog from git log

`make deb`: create Debian package
