---
layout: default
title: IMMERSE Log
---

### Week 12: July 12, 2021 - July 19, 2021

**Goals**:

- Resolve misunderstandings/questions about the process of associating bit addresses to tile config bit addresses
- Finish design (and implementation?) of rt_mux model format
- Complete Preliminary Analysis of ethics case study
- Create 1st draft of Reasearch Presentation

**Monday**:

- Finished setup of arty_dma_000 and dvi_002 designs for testing
- Tested fasm2firm.py and bits2firm.py for same read in of information
- Time duration of bits2firm.py reduced by approximatly 91.4%
- Brainstormed and considered different formats for rt_mux modelling.

**Tuesday**:

- 

**Wednesday**:

- 

**Thursday**:

- 

**Friday**:

- 

----

### Week 11: July 5, 2021 - July 9, 2021

**Goals**:

- Successfully print out a data structure with the given design configuration information from the .bits file through bits2firm.py
- Complete Preliminary Analysis and presentation of ethical case study for Broader Impacts

**Monday**:

- Holiday

**Tuesday**:

- Finish tilegrid.json parsing function
- Parse in .bits files into bits2firm.py
- Integrate tile classes from fasm2firm.py into bits2firm.py

**Wednesday**:

- Chip Camp
- Resolving complications and bugs in bits2firm.py

**Thursday**:

- Resolve issues and complications in bits2firm.py
- Develop format for rt_mux modelling
- Research ethics case study

**Friday**:

- Install and setup of Vivado 2019.1 and designs for testing
- Develop format for rt_mux modelling
- Resolve current issues in bits2firm.py

----

### Week 10: June 28, 2021 - July 2, 2021

**Goals**:

- Finish developing first version of fasm2model.py
- Begin development of error checking processes and simulation scripting for design testing.
- Complete preliminary analysis and presentaton of ethical case study for Broader Impacts

**Monday**:

- Added rt_mux class to fasm2model.py
- Added automatic generation of models for each routing mux in a slice_type

**Tuesday**:

- Cleaned up code for fasm2model.py
- Begun implementation of Fault Injection Bit simulation and error evaluation

**Wednesday**:

- Chip Camp (Rockets)

**Thursday**:

- Created .firm (FPGA Interconnect Routing Model) output file format
- Implement .firm format in fasm2model.py output
- Added file output to fasm2model.py
- Moved simulation analysis functions and progress to the new SimFBI.py script and began its development

**Friday**:

- Revise direction with switchbox branch
- Create bits2firm.py
- Plan and outline process of bits2firm.py
- Implement read in of part name and parsing of correct tilegrid.json file for given part

----

### Week 9: June 21, 2021 - June 25, 2021

**Goals**:

- Finish first basic text modelling/formatting summary script for prjxray interconnect db files
- Add multiple search functions for various parameters un switchbox summary script
- Expand testing and implementation of switchbox summary script to more database files and pip types

**Monday**:

- Finish reinstallation and setup
- Plan out and implement multiple search functions for switchbox summary script

**Tuesday**:

- Create a bash script to build a database of switchbox summaries from the prjxray database
- Expand the versatility of the SwitchboxSummary.py script to include and handle more file structures from the prjxray database

**Wednesday**:

- Edit and refocus database bash script on interconnect files
- Research .bits files and bitstream frames
- Develop ideas for implementing a python script for modeling the switchboxes in a design

**Thursday**:

- Begin Developing fasm2model.py
- Research connections between fasm, bits, and projectXray database files
- Research how to deduce which frame in the bitstream influences a specific slice's configuration.

**Friday**:

- Continue developing fasm2model.py
- Continue researching how to deduce which frame(s) in a bitstream influences a specific slice.
- Research ethics case study for Broader Impacts: Outreach

----

### Week 8: June 14, 2021 - June 18, 2021

**Goals**:

- Understand the layout and functioning of interconnect tiles and their pips
- Better understand ProjectXRay Databases

**Wednesday**:

- tcl mini_project 4
- Research projectxray databases


**Friday**:

- rebuild machine again
- review symbiflow/prjxray-db databases
- create new branch for bitInspector and begin script for parsing and printing out formatted db models

----

### Week 7: June 7, 2021 - June 11, 2021

**Goals**:

- Finish FPGA DeepDive
- Understand the layout and functioning of interconnect tiles and their pips

**Monday**:

- Finish machine setup after reboot.

**Wednesday**:

- FPGA deepdive
- Organize materials and topics for learning bitInspector

**Friday**:

- Research into the projectXray databases 
- Look into the internals of interconnect blocks

----

### Week 6: May 31, 2021 - June 4, 2021

**Goals**:

- Finish FPGA Deep Dive
- Better understand the transition from bitstream to FASM and EDIF files

**Monday**:

- Memorial Day

**Tuesday**:

- FPGA DeepDive
- TCL mini_project 4

**Wednesday**:

- FPGA DeepDive
- My machine had some malware issues and was taken by computer support. Limited now in what I can do for the next couple days.

**Thursday**:

- Read Mathew Canon's Thesis on Single Event Upsets and specifically about the structure, function, and vulnerabilities of FPGA routing switchboxes on artix7 boards.
- FPGA DeepDive
- Meeting with BitInspector teammates about specific roles and fundamentals of individual projects.

**Friday**:

- FPGA DeepDive
- Rebuild my machine, reinstall all programs and projects, and restore settings, aliases, and progress.

----

### Week 5: May 24, 2021 - May 28, 2021

**Goals**:

- Get caught up on bootcamp follow-up activities
- Better understand the purpose of BitInspector and my role in the project
- Better understand the transition from bitstream to FASM and EDIF files

**Monday**:

- CSV file parser and python extension follow-up activities
- Deeper look into implementation design of basic circuits made up until now

**Tuesday**:

- TCL bootcamp review miniprojects
- CSV Parser, documentation follow-up activities, docker follow-up activities

**Wednesday**:

- Sphinx/Documentation follow-up activity
- TCL bootcamp review miniprojects

**Thursday**:

- TCL bootcamp miniprojects
- Docker bootcamp follow-up activity

**Friday**:

- Docker Bootcamp follow-up activity
- TCL Bootcamp mini_project4
- FPGA Deep Dive

----

### Week 4: May 17, 2021 - May 21, 2021

**Goals**:

- Review and deepen knowledge of TCL
- learn FPGA structure and correlate FASM code to implementation on the FPGA
- Continue organization and ordering of documentation and tutorials for new team members.

**Monday**:

- Learn to test circuits through testbenches and run vivado through the tcl command line
- Create various basic circuits in Vivado

**Tuesday**:

- Learn to run vivado through the tcl command line
- Design circuits of increasing complexity and run them through bit2fasm for comparison

**Wednesday**:

- Finish writing and submit research proposal
- Python Packages II follow up activities (numpy, matplotlib, pandas)
- Add to my list of basic vivado circuit designs and their corresponding fasm files from bit2fasm

**Thursday**:

- Learn to create and develop a circuit from project creation to bitstream generation only from the tcl console
- Evaluate and order topics and resources for learning ProjectXRay

**Friday**:

- make and cmake review and follow-up activities
- ethics case study research

----

### Week 3: May 10, 2021 - May 14, 2021

**Goals**:

- Finish Reading Documentation
- Get up to speed on python.

**Monday**:

- Review python
- Python practice
- Reading up on bit2fasm

**Tuesday**:

- cmake review
- Python practice

**Wednesday**:

- FASM and bit2fasm bootcamp pages
- Finish reading through ProjectXray Documentation

**Thursday**:

- FASM bootcamp follow up activities
- Python env system setup
- Python virtual environment follow up activities
- Python practice.

**Friday**:

- Resolved issues with FASM follow up activities and bit2fasm
- Python numpy/matplotlib/pandas follow up activities.

----

### Week 2: May 3, 2021 - May 7, 2021

**Goals**:

- Install all needed software and tools
- Read ProjectXRay documentation

**Monday**:

- Familiarization with C
- Finish connecting and setting up xrdp connection along with process documentation.

**Tuesday**:

- Familiarization with C
- Installation of ProjectXray

**Wednesday**:

- Finish installation of ProjectXray
- Get caught up on ProjectXray documentation

**Thursday**:

- ProjectXRay documentation
- Continue learning Python

**Friday**:

- ProjectXRay documentation
- Learn Python
- Review presentation on Cmake

----

### Week 1: April 26, 2021 - April 30, 2021

**Goals**:

- Get computer setup
- Learn linux systems

**Monday**:

- Basic setup
- Rebuild my machine.

**Tuesday**:

- Finish setup
- Linux tutorials
- Begin website construction

**Wednesday**:

- Finish linux tutorials
- Finish website construction

**Thursday**:

- Git follow-up activities
- xrdp trials
- Link website to Computer Bootcamp website student list

**Friday**:

- Github follow-up activities
- xrdp trials
