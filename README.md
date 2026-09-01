# lab00
[![CMake](https://github.com/JoshMartinMaker/ECE-6785-lab00/actions/workflows/main.yml/badge.svg)](https://github.com/JoshMartinMaker/ECE-6785-lab00/actions/workflows/main.yml)
A repo to practice git submodules and GitHub actions, and to test building a project with CMake for a rp2040 microcontroller.

Most files are from [the template repo](https://github.com/uofu-embed/rtos.template).

## Renode setup
The Raspberry Pico needs configuration files for Renode to work properly.

* On MacOS, the installation location is `/Applications/Renode.app/Contents/MacOs`
* On Linux, the location for Debian, Fedora, and Arch is `/opt/renode`
* On Windows, the location is `C://Program Files/Renode`

To add the Pico configuration files:
1. Copy `rp2040_spinlock.py` and `rp2040_divider.py` to the `scripts/pydev` directory of your Renode installation.
1. Copy `rpi_pico_rp2040_w.repl` to the `platforms/cpus` directory.
