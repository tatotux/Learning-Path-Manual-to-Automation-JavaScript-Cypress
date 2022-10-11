# Learning Path Manual to Automation JavaScript Cypress

## Setting Up local environment

### Welcome

This guide walks through setup of a Macbook for QA Automation. By completing this guide you will be able to work with almost all Web Applications and APIs.

This guide assumes that you are using zsh as your shell (the latest Mac default). If you are using a different shell, be sure to replace instances of .zprofile with the corresponding file for your specific shell (e.g. .bash_profile).

### Recommended Software

I recommend using Visual Studio Code <https://code.visualstudio.com/download> and have generally coalesced around its usage as a team.

I maintain a useful list of VSCode plugins that I use for my own development. You can find that list here.

#### Required

- EditorConfig for VSCode
- npm Intellisense
- Eslint
- Jest
- Prettier - Code Formatter. Note: it's also recommended to set prettier as your default formatter and to enable the "Editor: Format on Save" setting
- Gitlens

#### Recommended

- SCSS Intellisense
- Babel JavaScript
- HTML CSS Support
- NodeJS Modules Intellisense
- Paste and Indent
- Guides
- Project Manager
- Restore Editors
- Settings Sync

### Environment Setup

#### Install Homebrew

Install homebrew: <https://brew.sh> . As a by-product, this will also automatically install Command Line Tools for Xcode.

#### Install Node

Install nvm and node version 16.13.1. nvm is a tool that lets you manage multiple node versions on your machine at the same time.  Do not install node directly from the node website.

```bash

brew install nvm
brew info nvm
nvm install 16.13.1

```

### Step Verification

Open a new terminal instance, and run the following commands:

- brew help: returns a list of brew commands
- make: returns make: *** No targets specified and no makefile found. Stop.
- git help: returns a list of git commands
- nvm --version: returns version
- node --version: returns version v16.13.1
- npm --version: returns version 8.1.0

### Setup your git profile

git config --global user.name "Eduardo Uribe"
git config --global user.email euribe@gmail.com

#### GIT Verification

Open a new terminal instance, and run the following commands:

- git config user.name: returns your full name
- git config user.email: returns your work email
