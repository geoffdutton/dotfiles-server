# README

## Goal

Create general dotfiles that can be installed on production and staging servers.
These files will replace any personal dotfiles to prevent unexpected behavior.

## Requirements

- Can not override standard server commands
- Must have a help command
- Must show if we are on staging, test or production
- Must show the current branch we are on, in case of a git repo
- Aliases to show list of recursive folder -and dirsizes
- Git information with handy aliases and pretty= formats
- install/uninstall

## Installation

Run the following command:

	git clone git@github.ncube.be:wijs/dotfiles-server.git ~/.dotfiles-server && cd ~/.dotfiles-server && ./install.sh

Not that you'll be prompted for an environment. This is to easily spot the server we're on.
