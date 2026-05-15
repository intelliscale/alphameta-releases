# AlphaMeta Releases

Public binary releases for [AlphaMeta](https://github.com/intelliscale/alphameta-core) — an agentic trading tool for Interactive Brokers.

> **Note:** This repository contains **only** compiled binary artifacts. Source code is in the private [intelliscale/alphameta-core](https://github.com/intelliscale/alphameta-core) repository.

## Download

Each [release](https://github.com/intelliscale/alphameta-releases/releases) includes:

- `alphameta-{version}-macos-arm64.tar.gz` — compiled binary for macOS ARM64
- `checksums.txt` — SHA-256 checksums

## Installation

```bash
# Direct download
curl -fsSL https://github.com/intelliscale/alphameta-releases/releases/latest/download/alphameta-{version}-macos-arm64.tar.gz | tar xz
sudo mv alphameta /usr/local/bin/
```

## Verification

```bash
shasum -a 256 -c checksums.txt
```
