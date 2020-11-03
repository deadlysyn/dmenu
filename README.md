# Yet Another dmenu Fork

[Original art](https://tools.suckless.org/dmenu).

# Installation

In order to build dmenu you need the Xlib header files.

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install

# Included patches

- [case-insensitive](https://tools.suckless.org/dmenu/patches/case-insensitive)
- [fuzzyhighlight](https://tools.suckless.org/dmenu/patches/fuzzyhighlight)
- [fuzzymatch](https://tools.suckless.org/dmenu/patches/fuzzymatch)
- [line-height](https://tools.suckless.org/dmenu/patches/line-height)
- [xresources](https://tools.suckless.org/dmenu/patches/xresources)

