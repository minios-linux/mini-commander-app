# mini-commander-app

Debian packaging repository for [mini-commander](https://github.com/Tomas-M/mini-commander).

## Description

This repository provides Debian packaging for mini-commander, a very simplified clone of Midnight Commander for Linux. It provides a dual-pane file manager interface with basic file operations in a terminal environment.

## Building

To build the package locally:

```bash
make
```

This will:
1. Clone the upstream repository
2. Create the original tarball
3. Add debian packaging files
4. Build the .deb package

The resulting .deb file will be in the `build/` directory.

## Installation

```bash
sudo dpkg -i build/mini-commander_*.deb
```

The binary is installed as `/usr/bin/mini-cmd`.

## Cleaning

```bash
make clean
```

## Upstream

- Repository: https://github.com/Tomas-M/mini-commander
- License: GNU GPL v3
