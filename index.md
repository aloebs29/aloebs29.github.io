---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Hi, my name is Andrew. I write software for fun and for work, and some of it is [open source](https://github.com/aloebs29).

## Projects

### [Flash Management](https://github.com/aloebs29/flash_management)

Flash management stack consisting of a flash translation layer ([dhara](https://github.com/dlbeer/dhara)) and an SPI NAND driver. Uses an STM32L432KCUX MCU connected to a Micron MT29F1G01ABAFDWB SPI NAND SLC flash chip.

This project is intended to be the "minimum implementation" needed to tie a FAT filesystem, flash translation layer, and low-level flash driver together. Most areas of the source code are heavily commented (probably over commented) in an effort to make it easy as possible for people unfamiliar with ONFI & flash translation concepts to follow.

### [Halfling](https://github.com/aloebs29/halfling)

Build and task automation system written in python; intended to be simple to understand and easy to extend with a `halfling.py` file in your project root. Currently supports C and C++ builds out of the box (with incremental builds based on file modified times); supports custom/user-defined builds and generic tasks.

### [Z Quad Rotor](https://github.com/aloebs29/z_quad_rotor)

**WIP** A quad rotor flight controller written in C++ with the [Zephyr RTOS](https://github.com/zephyrproject-rtos/zephyr). Currently does multi-threaded sampling of an accelerometer/gyroscope, magnetometer, and pressure sensor, as well as filtering/fusion of these sensors for orientation and altitude.

### [C Data Structures](https://github.com/aloebs29/c-data-structures)

Implementations of common data structures in C (dynamic array, linked list, queue, hash table). I wrote this for fun, learning, and to try out a test framework I hadn't used (Unity). These aren't very useful, since they only work on integers.

### [AHRS Filter Fusion Viewer](https://github.com/aloebs29/AHRS-Filter-Fusion-Viewer)

Interactive python notebook for viewing fusion results on raw accelerometer, gyroscope, and magnetometer data. Useful for tweaking fusion parameters and viewing the results.
