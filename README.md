# Users scripts for many purpose

Scripts list:
* pac
* s_tmux

## Getting started

Simply copy scripts you want in your PATH.

Example:

```
sudo cp pac /usr/local/bin/
sudo chmod 755 /usr/local/bin/pac
```

## pac

This script is an Archlinux wrapper for package management

### Dependencies

* pacaur

### Features

* purge pacaur cache
* upgrade system (AUR included)
* remove orphan packages

### Example

```
pac -h      # print usage
pac -a      # do all actions
pac -o      # remove orphan
```

## s_tmux

This script is a simple tmux session manager

### Dependencies

* tmux

### Features

* list tmux sessions
* create new tmux session
* attach to already existing sessions
* manage session profile

### Example

```
s_tmux work
```
