# `blinky`

A Rust "Hello, World!" for the STM32F411CEUx.

Generated using [`cortex-m-quickstart`](https://github.com/rust-embedded/cortex-m-quickstart):

``` console
$ cargo generate --git https://github.com/rust-embedded/cortex-m-quickstart
```


## Dependencies

To build you'll need a cross-compilation toolchain supporting the `thumbv7em-none-eabihf` target. To install it using `rustup`, run:

``` console
$ rustup target add thumbv7em-none-eabihf
```


## Building and Flashing

To build:

``` console
$ cargo build --release
```

To flash:

``` console
$ cargo flash --chip stm32f411CEUx --release
```

In order to use the [`cargo-flash`](https://github.com/probe-rs/cargo-flash) command, it must have been previously installed. To install it, run:

``` console
$ cargo install cargo-flash
```


## Tested Hardware

This code has been successfully tested on the following board:

 - [WeAct Black-Pill V2.0](https://stm32-base.org/boards/STM32F411CEU6-WeAct-Black-Pill-V2.0.html)
