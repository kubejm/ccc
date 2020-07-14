# ccc (Conventional Commit Cheatsheet)

Quick reference for the [conventional commit](https://www.conventionalcommits.org/en/v1.0.0/) specification

## Install

```sh
sudo sh -c "curl https://raw.githubusercontent.com/kubejm/ccc/master/ccc \
       -o /usr/local/bin/ccc && \
       chmod +x /usr/local/bin/ccc"
```

## Usage

```
➜ ccc

Conventional Commit Cheatsheet

STRUCTURE
  <type>[optional scope]: <description>

  [optional body]

  [optional footer(s)]

TYPES
  build, chore, ci, docs, feat, fix, perf, refactor, style, test

EXAMPLES
  - Commit message with no body
    docs: add install instructions to README

  - Commit message with scope
    feat(search): add filter capability

  - Commit message with both '!' and breaking change footer
    refactor!: drop support for Node 11 and lower

    BREAKING CHANGE: using features introduced in Node 12
```
