# My Emacs Config

![Minimum Emacs version supported: 26.3 ](https://img.shields.io/badge/Supports-Emacs_26.3+-blueviolet.svg?style=flat-square&logo=GNU%20Emacs&logoColor=white)
[![GitHub issues](https://img.shields.io/github/issues/Aaron-Mann/.emacs.d)](https://github.com/Aaron-Mann/.emacs.d/issues)
[![GitHub forks](https://img.shields.io/github/forks/Aaron-Mann/.emacs.d)](https://github.com/Aaron-Mann/.emacs.d/network)
[![GitHub stars](https://img.shields.io/github/stars/Aaron-Mann/.emacs.d)](https://github.com/Aaron-Mann/.emacs.d/stargazers)
[![GitHub license](https://img.shields.io/github/license/Aaron-Mann/.emacs.d)](https://github.com/Aaron-Mann/.emacs.d/blob/main/LICENSE)

A Simple, Fully Featured, and Evil Emacs Config. Inspired by what Doom Emacs got right, what Spacemacs got wrong, and with some new ideas and features that strive to make your life easier.

# Design Goals and Features

- **Speed:** This emacs config unapologetically flies. With speeds comparable to doom emacs, you won't find a quicker config this much ease of use.
- **Selective Language Support:** This system allows a file to be created for each language you wish to use. Don't want to touch Javascript? Remove it's script. Disgusted by whitespace? `rm -rf .emacs.d/languages/python.el`. Interested in an unsupported language? Create `cobol.el`.
- **Boilerplate:** More than anything else, this repository acts as a jumping off point for one's own config. With easy to understand org-documented code, no other config provides such a simple starting point, with such useful defaults.

# Prerequisites

#### Git 2.23+
Ubuntu: `sudo apt install git`

Arch: `sudo pacman -S git`

#### Emacs 26.3 (although 27.2 is recommended)
Ubuntu: `sudo apt install emacs`

Arch: `sudo pacman -S emacs`

# Install

Navigate to your home directory, and issue the following command:
`git clone --depth 1 https://github.com/Aaron-Mann/.emacs.d ~/.emacs.d`

Now go ahead and run emacs! You should see a white screen with ELPA information across the bottom upon your first startup. No need to worry, this is just emacs configuring during its first startup. After processing for ~20 seconds, all packages should be installed and ready to operate. Just one last thing before emacs is ready...
`M-x all-the-icons-install-fonts`

Enjoy your emacs experience!

# Roadmap

As following is the current list of features to be implemented:
- **TreeSelect:** Implement a reasonable, fast, and useful treeselect module.

# Contribute

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com) 
[![Elisp styleguide](https://img.shields.io/badge/elisp-style%20guide-purple?style=flat-square)](https://github.com/bbatsov/emacs-lisp-style-guide)

All Functions, errors, and messages added by this config are seperated from vanilla emacs functions with the name "Toaster", ie: `toaster-log`. This naming convention should be used for any new functionality. 

ETH: `0x0F4A5595FC74a0279Dfe0aab8f5823B63400E15a`

BEAM: `3205ba4fa07fb2c332079a1d725f9d8f5a79d9b8042d560343a2e6981419253d966`
