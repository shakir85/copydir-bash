Simple tool to copy the current working directory to clipboard from the terminal, intended for Bash shell. 

### Requirement (MUST INSTALL)
- `xclip` : A command line interface for X11 clipboard to redirect the output of $PWD to the clipboard. This is a mandatory requirement and `copydir` will not work without it.
Debian / Ubuntu Linux: `apt-get install xclip`.
Red hat / CentOS / RHEL / Fedora Linux: `yum instal xclip`.
Arch / Manjaro: `pacman -S xclip`

---

*Inspired by `copydir` for ZSH. https://github.com/ohmyzsh/ohmyzsh/blob/master/plugins/copydir/copydir.plugin.zsh*
