# Media Controller Hardware Build

# Requirements

The hardware media controller should provide configurable buttons/macro-keys to be used in conjunction with media programs such as Spotify and VLC, and online streaming services such as Youtube and Netflix. As such it must account for standard Play/Pause, Next, and Previous functions as well as a volume control knob. A good-to-have feature is 'click' functionality in the volume knob, which can replace the need for separate media playback controls, freeing them up for other uses such as programmable macro-keys. At this stage it should be wired using USB-B micro.

# Folder structure

**assets**: Images and other resources used in this README
**datasheets**: Datasheets for any components used in this project. Currently in progress.
**firmware**: Any C/C++ code written for the ATMEGA32U2 used in this PCB.
**pcb_design**: Altium project files.
**pcb_manufacturing**: Altium-generated files for manufacturing.

# Motivation

This project is purely for educational purposes. It serves as a way for myself to learn how to use Altium Designer by making a relatively simple electronics project. I expect to have a comfortable grasp of the following skills once this is completed:

- [x] Circuit Design (Basic)
- [x] Altium Designer
  - [x] Library Management
  - [x] Schematic Capture
  - [x] PCB Layout
  - [x] Gerber Generation
- [ ] Firmware
  - [ ] C/C++ for AVR processor
  - [ ] USB interface
  - [ ] Unit-testing
- [ ] Soldering
  - [ ] TQFP
  - [ ] SMD
  - [ ] THT
- [ ] Mechanical (optional)
  - [ ] Creating a case

## Progress

As I complete sections of this project, I will update this flowchart. This should give me a clear task-list, as well as introducing a sense of accountability.

![MediaControllerProjectFlow](/assets/MediaControllerProjectFlow.jpeg)
Improvement: Convert this to a mermaid diagram to reduce workload when updating progress.

## What I would do differently

I used this project in conjunction with learning Altium from scratch. For this reason, I chose not to delve too deep into additional details such as the assembly, mechanical, and manufacturing drawings/notes. This will be the focus of future PCBs.</br>

### Schematic and Footprint Libraries

Every component in this project has been added in individually. This was not a difficult task, however it took up a large portion of the design-time. In future, I will improve my skills in creating components by sharing common footprints between components, e.g. 0603 capacitors of different values. </br>
Community-sourced component libraries would also have sped up the process considerably. I connected the _celestial altium library_ database to experiment, and found it was useful for fast prototyping, INCLUDING supplier-linked parts. For future use, I will stick to generating the components myself so that I can improve my skills, however it is good to know that I can find most schematics/footprints a few clicks away. </br>
