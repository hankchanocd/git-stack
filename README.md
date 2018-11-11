# git-stack &nbsp;&nbsp; ![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/hankchanocd/git-stack.svg) [![Build Status](https://travis-ci.org/hankchanocd/git-stack.svg?branch=master)](https://travis-ci.org/hankchanocd/git-stack) [![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/) [![Github issues](https://img.shields.io/github/issues/hankchanocd/git-stack.svg)](https://github.com/hankchanocd/git-stack/issues) [![CodeFactor](https://www.codefactor.io/repository/github/hankchanocd/git-stack/badge)](https://www.codefactor.io/repository/github/hankchanocd/git-stack)

> View difference between git branches

<p align="center">
<img alt="demo" width="850" src="https://github.com/hankchanocd/git-stack/blob/master/images/demo.png" />
</p>

`git stack`.

## Install

Clone the repo, and run `npm run transfer` to transfer `./git-stack` to `~/bin`, or manually invoke `./script/transfer.sh`. If you have a more desired `PATH` for storing scripts, configure `./script/transfer.sh` directly.

## Before-Use

Make sure [`fzf`](https://github.com/junegunn/fzf) is installed globally. `git stack` won't work if `fzf` is not installed.

## Usage

```bash
$ git stack
```

## Changelog

**2018-Nov-11:** `v1` published. Automate commit and file transfer process with [`commitizen`](http://commitizen.github.io/cz-cli/) and [`ghooks`](https://github.com/ghooks-org/ghooks).

## License

[MIT](./LICENSE)
