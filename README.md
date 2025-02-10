# yq

![Build](https://github.com/mikefarah/yq/workflows/Build/badge.svg)
![Docker Pulls](https://img.shields.io/docker/pulls/mikefarah/yq.svg)
![Github Releases](https://img.shields.io/github/v/release/mikefarah/yq)

`yq` is a lightweight and portable command-line processor for YAML, JSON, XML, CSV, TOML, and properties. It uses [jq](https://github.com/stedolan/jq) like syntax but works with multiple file formats. Written in Go, `yq` provides a dependency-free binary for easy installation on various platforms.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
  - [Linux](#linux)
  - [macOS](#macos)
  - [Windows](#windows)
  - [Docker](#docker)
- [Quick Usage Guide](#quick-usage-guide)
- [Advanced Features](#advanced-features)
- [Documentation and Support](#documentation-and-support)
- [Contributing](#contributing)
- [License](#license)

## Introduction
`yq` is a versatile command-line tool for processing YAML, JSON, XML, CSV, TOML, and properties files. It supports various operations such as reading values, updating files, merging files, and converting formats.

## Installation

### Linux
#### wget (Binary)
```bash
VERSION=v4.2.0
BINARY=yq_linux_amd64
wget https://github.com/mikefarah/yq/releases/download/${VERSION}/${BINARY}.tar.gz -O - | tar xz && mv ${BINARY} /usr/bin/yq
