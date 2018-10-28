# elementary Icons

Classic [elementary](https://github.com/elementary/icons) blue folders.

This icon pack only contains icons for folders.

These icons are licensed openly under the terms of the [GNU General Public License](COPYING). Redistributing, forking, remixing, etc. are encouraged!

## Contributing Icons
It is recommended to use the free and open source [Inkscape](http://inkscape.org) vector editor to create elementary icons.

To contribute to the elementary icon set, open a pull request to this repository with your icon(s).

It is strongly encouraged to vacuum all vectors with [Inkscape](http://inkscape.org). This keeps the repository lean, clean, and fast for everyone. For convenience, a git pre-commit hook is included. To install, run these commands from your local repository folder:
```bash
$ cp pre-commit .git/hooks/
$ chmod +x .git/hooks/pre-commit
```

## Installation
You need the [Meson](http://mesonbuild.com) build system to install it.
Once you've installed it, run these commands in the root of the icon set.
```bash
$ meson build --prefix=/usr
$ cd build
$ sudo ninja install
```

## Not a Universal Icon Set
This icon set only covers icons for folders.

Use of icon names in line with the [FreeDesktop.Org Icon Naming Specification](http://standards.freedesktop.org/icon-naming-spec/icon-naming-spec-latest.html) is encouraged.
