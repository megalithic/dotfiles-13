This repo contains my dotfiles, with management provided by [Dotbot](https://github.com/anishathalye/dotbot).

#### Installation

```shell
cd ~/Developer # or another directory
git clone https://github.com/markneub/dotfiles.git
cd dotfiles
git submodule update --init --recursive
./install # adds dotfile symlinks from $HOME to repo
```

#### Maintenance

Upgrade submodules to latest versions:
```shell
git submodule update --init --remote
```
