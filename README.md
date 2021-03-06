# dotfiles

This my configuration files as managed by [dotbot](https://github.com/anishathalye/dotbot).

To run just type

```bash
$ ./install
```

Re-running should not do anything.

Things not covered:
-------------------

* [gnome-terminal-colors-solarized](https://github.com/Anthony25/gnome-terminal-colors-solarized) - run `./gnome-terminal-colors-solarized/set_dark.sh` and go through the process
* `./configure-gnome-terminal` is not automatically run
* Copying `sys/etc/ld.so.conf.d/usr-local.conf` into `/etc/ld.so.conf.d/` and running `ldconfig`. This adds `/usr/local/lib` to your `LD_LIBRARY_PATH`. If ldconfig gives a message about `/etc/ld.so.conf` missing, copy that file over as well.
* Things in `tools` are not run

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)
