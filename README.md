# Template

Starting point for a new DualSlide game.

A DualSlide game, built as a `.dsg` game file.

## Building

Needs the [DualSlide](../DualSlide) repository beside this one (it holds the
game SDK), the Arm GNU toolchain (`arm-none-eabi-gcc`), CMake, Ninja and
Python 3.

    cmake --preset default
    cmake --build --preset default

This writes `build/template_game.dsg`.

## Installing

Connect the DualSlide to a computer, copy `template_game.dsg` onto the DUALSLIDE
drive, and eject the drive.

## Details

| | |
| --- | --- |
| Identifier | `dualslide.template` |
| Version | 1.0.0 |
