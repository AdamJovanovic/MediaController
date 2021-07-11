# Media Controller Hardware Build

# Requirements

I require a hardware media controller which I can use to

# Folder structure

**assets**: Images and other resources used in this README
**datasheets**: Datasheets for any components used in this project. Currently in progress.
**firmware**: Any C/C++ code written for the ATMEGA32U2 used in this PCB.
**pcb_design**: Altium project files.

# Motivation

This project is purely for educational purposes. It serves as a way for myself to learn how to use Altium Designer by making a relatively simple electronics project. I expect to have a comfortable grasp of the following skills once this is completed:

- [x] Circuit Design (Basic)
- [ ] Altium Designer
  - [x] Library Management
  - [x] Schematic Capture
  - [ ] PCB Layout
  - [ ] Gerber Generation
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

As I complete sections of this project, I will update this flowchart. This should give myself a clear task-list, as well as introducing a sense of accountability.

![MediaControllerProjectFlow](/assets/MediaControllerProjectFlow.jpeg)
Improvement: Convert this to a mermaid diagram to reduce workload when updating progress.

## What I would do differently

### Schematic and Footprint Libraries

Every component in this project has been added in individually. This was not a difficult task, however it took up a large portion of the schematic capture time. </br>
In hindsight, I did not need to create separate footprints for passive components with identical package-sizes. </br>
Community-sourced component libraries would also have sped up the process considerably. </br>
Using UltraLibrarian and SnapEda provided me with footprints, as well as a large chunk of un-necessary dimensioning text.
