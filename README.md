# macos-goodies

[![License](https://img.shields.io/badge/license-MIT-007EC7)](/LICENSE)

> Zsh goodies for MacOS users

## Description

| Command     | Description                                          |
| ----------- | ---------------------------------------------------- |
| `afk`         | Lock the screen                                      |
| `emptytrash`  | Clean trash on primary HDD, clear quarantine logs    |
| `flushdns`    | Clear local DNS cache                                |
| `hidefiles`   | Hide hidden files in Finder                          |
| `rmdsstore` | Remove .DS_Store files recursively in a directory      |
| `showfiles` | Show hidden files in Finder                            |

## Installation

Either use your Zsh plugin mangager of choice or...

### Install manually, without a plugin manager

To install manually, first clone the repo:

```zsh
git clone https://github.com/mrolli/macos-goodies.git ${ZDOTDIR:-~}/.zplugins/macos-goodies
```

Then, in your .zshrc, add the following line:

```zsh
source ${ZDOTDIR:-~}/.zplugins/macos-goodies/macos-goodies.zsh
```
