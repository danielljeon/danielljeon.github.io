# danielljeon.github.io

---

## Info & Docs

About me: [danielljeon](danielljeon).

Personal notes: [docs](docs).

---

## Full Projects

### Nerve: 6-DOF Flight Controls

🚀 Nerve is a general-purpose controller designed for six degrees of freedom
(6-DOF) operation. Originally developed for jet vane rocket controls, it now
serves as a testbed for robotics and controls development.

Firmware:

- [nerve](https://github.com/danielljeon/nerve): Firmware for CAN-based control
  systems dev platform.

Hardware:

- [nerve_pcb](https://github.com/danielljeon/nerve_pcb): PCB for CAN-based
  control systems dev platform.
- [nerve_gps_pcb](https://github.com/danielljeon/nerve_gps_pcb): GPS module to
  `nerve_pcb`.
- [nerve_radio_pcb](https://github.com/danielljeon/nerve_radio_pcb): Radio and
  power supply module to `nerve_pcb`.


- [nerve_ada_board](https://github.com/danielljeon/nerve_ada_board): Nerve dev
  board using off-the-shelf modules.

Additional Software/Hardware:

- [gopher](https://github.com/danielljeon/gopher): Ground station for Nerve
  controller system.
    - Previously a Python desktop application for telemetry via XBee radios.

---

## Interesting Academic and Small Projects

### Soft Robotic Gripper: Software driven CAD

🎈 Pneumatic gripper project focusing on silicone mold design automated with
software for rapid design flexibility.

[soft_solution](https://github.com/danielljeon/soft_solution): soft robotic
gripper design project for university CAD course, completed in Fall 2023.

### Robotic Hand: 5 DOF Humanoid Hand Prototype

🤌 Robotic hand project for actuators/power electronics and
sensors/instrumentation university courses.

1. [robotic_hand](https://github.com/danielljeon/robotic_hand): firmware.
2. [robotic_hand_pcb](https://github.com/danielljeon/robotic_hand_pcb): PCB
   hardware.
3. [robotic_hand_wireless](https://github.com/danielljeon/robotic_hand_wireless):
   XBee wireless telemetry display desktop application.

### Maze Bot: Terrain and Maze Solving Robot

🐁 Terrain and maze solving robot for mechatronics design university course.

1. [maze_bot](https://github.com/danielljeon/maze_bot): firmware.
2. [maze_bot_pcb](https://github.com/danielljeon/maze_bot_pcb):
   electronic schematics (PCB not permitted by project rules).

### Drop Detect: FreeRTOS Soldering Iron Drop-Triggered Shield

🛡️ Soldering iron drop-triggered shield for real time embedded systems
university course.

1. [drop_detect](https://github.com/danielljeon/drop_detect): firmware.
2. [drop_detect_pcb](https://github.com/danielljeon/drop_detect_pcb): PCB
   hardware.

---

## Setup

This GitHub Pages repository uses submodules to pull in documentation and
references.

Quick command to pull changes from remote submodules:

```shell
git submodule update --remote --merge
```
