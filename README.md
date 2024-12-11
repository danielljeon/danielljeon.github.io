# danielljeon.github.io

## Info & Docs

About me: [danielljeon](danielljeon).

Personal notes: [docs](docs).

## Projects

### Embedded Systems & Firmware Projects

[nerve](https://github.com/danielljeon/nerve): STM32F446RE based general purpose
controller with telemetry ICs.

- [nerve_pcb](https://github.com/danielljeon/nerve_pcb): Production optimized
  PCB for the STM32 based nerve controller firmware.
- [nerve_gps_pcb](https://github.com/danielljeon/nerve_gps_pcb): GPS
  board-to-board module for `nerve_pcb`.
- [nerve_radio_pcb](https://github.com/danielljeon/nerve_radio_pcb): XBee radio
  board-to-board module for `nerve_pcb`.
    - [nerve_ada_board](https://github.com/danielljeon/nerve_ada_board): Nerve
      controller dev board using off-the-shelf modules, made in KiCad with KiBot
      workflows.
- [gopher](https://github.com/danielljeon/gopher): Python based radio and
  telemetry desktop app for XBee radios.

## Setup

This GitHub Pages repository uses submodules to pull in documentation and
references.

Quick command to pull changes from remote submodules:

```shell
git submodule update --remote --merge
```
