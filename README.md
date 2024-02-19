# dotfiles
My Linux config dotfiles for Termux on android

### Termux (Android)

Termux is an terminal emulator for Android but has modern feature like Debian and Ubuntu (Termux has Bash shell and Busybox GNU-like programs). For the package manager, Termux using an Debian/Ubuntu package manager, APT.
To install the package, run this command:

```sh
pkg install zsh
```

The command looks like FreeBSD package manager (`pkg`). Or you can run this command:

```sh
apt update && apt upgrade
apt install zsh
```

To set zsh as your default shell, run this command:

```sh
chsh -s zsh
```

download and install termux-nerd-installer
font used "hack"
# TODO:
- [ ] add install script to install requirements
- [ ] update zsh-fzf-history to correct command automatically

