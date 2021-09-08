## dmenu - dynamic menu

dmenu is an efficient dynamic menu for X.


### Requirements

In order to build dmenu you need the Xlib header files.

### Installation

Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):
```
    make clean install
```

### Running dmenu

See the man page for details.

### Patches

- Added Font Awesome icons and support for colored emojis (libxft-bgra)
- mouse support
    - `dmenu-mousesupport-5.0.diff`
- password
    - `dmenu-password-5.0.diff`
- xresources
    - `dmenu-xresources-4.9.diff`
