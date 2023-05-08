# macos-goodies

[![License](https://img.shields.io/badge/license-MIT-007EC7)](/LICENSE)

> Zsh goodies for MacOS users

## Description

| Command                  | Description                                           |
| ------------------------ | ----------------------------------------------------- |
| `afk`                    | Lock the screen                                       |
| `brewup`                 | Update Homebrew and AppStore                          |
| `emptytrash`             | Clean trash on primary HDD, clear quarantine logs     |
| `flushdns`               | Clear local DNS cache                                 |
| `hidefiles`              | Hide hidden files in Finder                           |
| `rmdsstore`              | Remove .DS_Store files recursively in a directory     |
| `showfiles`              | Show hidden files in Finder                           |
| `create_macos_bootstick` | Create a bootable memory stick from a macOS Installer |
| `music`                  | CLI script to control Music application               |
| `tadd`                   | Add currently playing track to playlist               |
| `tpurge`                 | Delete currently playing track from playlist          |
| `usbcreator`             | Create a bootstick from an ISO file                   |

## Installation

Either use your Zsh plugin mangager of choice or...

### Install manually, without a plugin manager

To install manually, first clone the repo:

```zsh
git clone https://github.com/mrolli/macos-goodies.git ${ZDOTDIR:-~}/.zplugins/macos-goodies
```

Then, in your .zshrc, add the following line:

```zsh
source ${ZDOTDIR:-~}/.zplugins/macos-goodies/macos-goodies.plugin.zsh
```
