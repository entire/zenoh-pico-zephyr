# Zenoh-Pico example for Zephyr RTOS

## Requirements
- v3.3.0 Zephyr RTOS
- 0.7.2-rc zenoh-pico

## Purpose
This repository contains some proof-of-concept applications that show how to build and use [Zenoh-Pico](https://github.com/eclipse-zenoh/zenoh-pico) on [Zephyr RTOS](https://www.zephyrproject.org)

## Usage:
This repository can be cloned and used like any generic Zephyr application.
The `CMakeLists.txt` is currently set up to fetch and build Zenoh-Pico library and an example `z_pub` application. Nevertheless, it can be easily modified or extended for other application code.

For example, to build `z_pub` for the `nucleo_f746zg` target, inside `zenoh-pico-zephyr`, run:
```
$ west update
$ west build -b nucleo_f746zg .
```
