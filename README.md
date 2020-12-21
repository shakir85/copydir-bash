Note: This tool will only work for X Window managers. So, yeah!. I'll fix that later on and look for `xclip` alternatives.

Simple tool to copy the current working directory to clipboard from the terminal. 

### Requirement
`xclip` : A command line interface for X11 clipboard to redirect the output of `$PWD` to the clipboard. This plugin will not work without installing `xclip`. You can get if from:
- Debian / Ubuntu Linux: `apt-get install xclip`.
- Fedora / CentOS / RHEL Linux: `yum instal xclip`.
- Arch / Manjaro: `pacman -S xclip`
- MacOS: `brew install xclip`

### Usage
Add `copydir` to plugins array in `.bashrc`
```
plugins=(... copydir)
```

*Inspired by `copydir` of [oh my zsh](https://github.com/ohmyzsh/ohmyzsh/tree/master/plugins/copydir) project.*
