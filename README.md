# hpm [![Build Status](https://travis-ci.org/matheuss/hpm.svg?branch=master)](https://travis-ci.org/matheuss/hpm) [![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo) [![Coverage Status](https://coveralls.io/repos/github/matheuss/hpm/badge.svg?branch=master)](https://coveralls.io/github/matheuss/hpm?branch=master)


✨ A plugin manager for HyperTerm ✨

<img src="https://raw.githubusercontent.com/matheuss/hpm/master/screenshot.gif?v=2" width="629">

## Install

```
npm install -g hpm-cli
```

## Usage

```
❯ hpm --help

  Usage: hpm [options]

  Options:

    -h, --help             output usage information
    -V, --version          output the version number
    i, install <plugin>    Install a plugin
    u, uninstall <plugin>  Uninstall a plugin (aliases: rm, remove)
    ls, list               List installed plugins
    s, search <query>      Search for plugins on npm
    ls-remote              List plugins available on npm
    d, docs <plugin>       Open the npm page of the <plugin>
    f, fork <plugin>       Forks a plugin from npm into your ~/.hyperterm_plugins/local
```

## Upcoming
- [ ] `hpm view hyperpower` – something similar to `npm view`
- [ ] `hpm i hyperpower@beta` – same as `npm i package@tag`
- [ ] `hpm u --tmp` – comment the plugin in `.hyperterm.js` instead of deleting it
- [ ] Bulk commands (e.g. `hpm i hyperpower hyperyellow`)
- [ ] `hpm help` – same as `npm help`

## Done
- [x] `hpm i hyperpower#1.0.0`
- [x] `hpm fork hyperpower`
- [x] `hpm search <query>`
- [x] `hpm unistall <plugin>`
- [x] `hpm ls`

## Maybe
- [ ] `hpm init` (or something like that) that downloads HyperTerm for you
