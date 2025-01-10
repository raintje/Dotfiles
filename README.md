# Dotfiles repository

Repository that contains portable dotfiles for use in any new GNU/Linux distribution.

## Requirements

Ensure you have `git` and `stow` installed on your system.

### Git
`sudo apt-get install -y git`

### Stow
`sudo apt-get install -y stow`

## Installation

Clone the dotfiles repository in your `$HOME` directory using git.

```sh
$ git clone git@github.com/raintje/dotfiles.git
$ cd dotfiles
```

Then use GNU stow to create symbolic links.

```sh
$ stow .
```