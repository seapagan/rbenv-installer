# rbenv installer

**Really, do not use it! Please, use the installer provided by rbenv or use homebrew if you are using a Mac.**

This tool is used to install `rbenv` and some plugins. It also provides 
scripts to install required software to be able to compile **Ruby**.


## Requirements

- Git
- Curl


## Install

Install [rbenv] and friends by running:

    curl https://raw.githubusercontent.com/fesplugas/rbenv-installer/master/bin/rbenv-installer | bash


## Installing a Ruby

Install latest stable Ruby and make it global:

    rbenv install 2.1.3
    rbenv global 2.1.3


## Updating

Update `rbenv` and plugins provided by the installer running:

    rbenv update


## Bootstrap

If you are installing `rbenv` in Ubuntu you'll probably need to install
some required packages. You can use the provided `bootstrap` scripts.

    rbenv bootstrap-ubuntu-12-04


## About rbenv

**rbenv** source code is available at <https://github.com/sstephenson/rbenv>

[rbenv]: https://github.com/sstephenson/rbenv
