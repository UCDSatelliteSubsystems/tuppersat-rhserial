# tuppersat-rhserial

Python implementation of the RadioHead LoRa API.

## Getting Started

### Using MicroPython & Raspberry Pi Pico

If you are using MicroPython and the Pi Pico, you will need to place the
`rhserial` package somewhere that your code's import statements can find
it. The recommended approach here is:

* clone this repository onto your working machine;

* create nested packages `tuppersat/` and `tuppersat/rhserial/` in your Pico's
  root directory,

* use the Thonny IDE to copy the source code files into these directories.

Note, MicroPython does not support namespace packages. You will likely need to
add an (empty) `__init__.py` to the `tuppersat/` directory, so that Python
treats this as a package for import purposes.

### Using CPython & Pip

A `pip install` option is to be completed

* * * * * * * * * * 