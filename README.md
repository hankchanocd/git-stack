# git-stack &nbsp;&nbsp; ![GitHub tag (latest SemVer)](https://img.shields.io/github/tag/hankchanocd/git-stack.svg) [![Build Status](https://travis-ci.org/hankchanocd/git-stack.svg?branch=master)](https://travis-ci.org/hankchanocd/git-stack) [![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/) [![Github issues](https://img.shields.io/github/issues/hankchanocd/git-stack.svg)](https://github.com/hankchanocd/git-stack/issues) [![CodeFactor](https://www.codefactor.io/repository/github/hankchanocd/git-stack/badge)](https://www.codefactor.io/repository/github/hankchanocd/git-stack)

> View differences between git branches with fzf

<p align="center">
<img alt="demo" width="850" src="https://github.com/hankchanocd/git-stack/blob/master/images/demo.png" />
</p>

Have a quick glance at the differences between `develop` and `master` branch with `git stack`.

## Install

Clone the repo, and run `npm run transfer` to transfer `./git-stack` to `~/bin`, or manually invoke `./script/transfer.sh` if you are not familiar with `npm`.

If you have a more desired `PATH` for storing scripts, configure `./script/transfer.sh` directly or ignore the transfer instructions.

## Before-Use

Make sure [`fzf`](https://github.com/junegunn/fzf) is installed globally. `git stack` won't work if `fzf` is not installed.

## Usage

```bash
$ git stack
```

`develop` is set as the default branch to compare against `master`. If no `develop` branch is detected, `git stack` will ask for input from a fuzzy list of all available branches.

## Changelog

**2018-Nov-11:** `v1` published. Automate commit and file transfer process with [`commitizen`](http://commitizen.github.io/cz-cli/) and [`ghooks`](https://github.com/ghooks-org/ghooks).

## Others

See [Dotfiles](https://gitlab.com/hankchanocd/dotfiles) for my other works on `git`.

## License

[MIT](./LICENSE)
