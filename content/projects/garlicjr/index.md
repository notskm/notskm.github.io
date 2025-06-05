+++
date = '2025-06-05T14:09:09-04:00'
draft = false
title = 'GarlicJr'
categories = ['projects']
tags = ['emulation', 'rust']

weight = 1

[cover]
image = "garlicjr.png"
alt = "Screenshot of the GarlicJr Game Boy emulator showing a view of the CPU, RAM, and the Game Boy screen"
caption = "GarlicJr, a Game Boy emulator"

[params]
+++

## About

GarlicJr is a Game Boy emulator written in Rust that runs in your browser.

I started this project as an excuse to learn Rust, and to learn more about hardware.
I thought this might be a fun way to accomplish both goals.

[Run GarlicJr](https://notskm.github.io/garlicjr)
[View on GitHub](https://github.com/notskm/garlicjr)

## Goals

- The final emulator should run on the web, Windows, and Linux.
- The core should require as few dependencies as possible for maximum portability.
- The emulator should have a number of debugging and introspection features.
- The end goal is to create a cycle-accurate Game Boy emulator.

## Technologies

This project is written in Rust and compiles both natively and to WebAssembly.
The front-end uses [egui](https://github.com/emilk/egui), an immediate-mode GUI framework that is compatible with the web.

