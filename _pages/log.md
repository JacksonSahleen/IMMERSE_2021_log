---
layout: default
title: IMMERSE Log
---

### Week 15: Aug 2, 2021 - Aug 6, 2021

**Goals**:

- Add function to define the role of each bit from the bit file in the implemented design
- Finish Ethics case study analysis for Broader Impacts
- Develop examples and demos for the Google presentation

**Monday**:

- Rearrange tile and mux modelling and printing functions to be class functions of the Tile class
- Begin developing bit definition function

**Tuesday**:

- Develop bit definition function
- Begin developing bit definition output option

**Wednesday**:

- Complete developing bit definition output option
- Work on Ethics case study research and analysis

**Thursday**:

- 

**Friday**:

- 

----

### Week 15: Aug 2, 2021 - Aug 6, 2021

**Goals**:

- Go through all python scripts I've made up until now with pylint to optimize and make more readable
- Add a function to int_tile.py to trace any undefined nets back to either the GND or VCC causing the issue
- Continue to research CLB tiles and other types of tiles to implement next into bit_inspector
- Develop examples and a presentation to present to prjxray in collaboration with Cody

**Monday**:

- Optimize bits2model.py and fasm2model.py with pylint
- Debug and Finish net trace function in int_tile
- Rename int_tile.py to tile.py in anticipation for the implementation of other tile types

**Tuesday**:

- Optimize tile.py with pylint

**Wednesday**:

- Finish and give Technical Presentation
- Organized and developed plan for our next steps with Cody Arvonen

**Thursday**:

- Included nets as a class variable for the Tile class in tile.py
- Separated out tile.py functions into multiple smaller functions to improve readability
- Created python script to evaluate segbits_*.db files to make determining functionality of config bits easier for more types of tiles. 

**Friday**:

- Debug model printing to include muxes where opens are formed due to bitstream upsets
- Separated out tile.py functions into multiple smaller functions to improve readability
- Revised pylint scores for all three scripts and improved scores to 9.8+

----

### Week 14: July 26, 2021 - July 30, 2021

**Goals**:

- Finish and give Technical Presentation on bit_inspector
- Finish combining chk2fasm and bit/fasm2model scripts to augment modelling
- Complete inital analysis of ethical case study

**Monday**:

- Finished combining chk2fasm and bit/fasm2model scripts
- Resolved remaining bugs for simplified graphical models
- Added net deduction and display for detailed graphical models
- Presentation planning with Cody
- Developed Technical Presentation on bit_inspector for Wednesday

**Tuesday**:

- Prepare technical presentation on bit_inspector

**Wednesday**:

- Prepare technical presentation on bit_inspector
- Research CLB tiles and differences between different tile types for parsing and config bit functionality

**Thursday**:

- Research purpose of config bits in CLB tiles
- Research different types of tiles in each of the parts in the prjxray 7series database
- Clean up bits2model parsing a bit
- Add in output type flag to bits2model and fasm2model to allow the user to determine what style of output is desired (text, simple graphic, or detailed graphic)
- Research ethics case study for Broader Impacts

**Friday**:

- Create and develop a net trace function for int_tile.py to track all undefined nets obtained from the checkpoint file

----

### Week 13: July 19, 2021 - July 23, 2021

**Goals**:

- Complete first draft of presentation for my project
- Complete first initial analysis of ethics case study
- Add statistics to end of file summary for bits2model and fasm2model scripts
- Update documentation for switchbox modelling and push to master branch for bit_inspector

**Monday**:

- Worked on grapical text-art representation of routing muxes
- Begin working of presentation

**Tuesday**:

- Cleaned up switchbox directory and removed old and unnecessary files/scripts
- Updated commits and submitted push request for switchbox branch

**Wednesday**:

- Planned interaction between Cody's get_nets tcl script and bits- and fasm- 2model.py
- Designed and implemented a simple graphical model of the routing muxes

**Thursday**:

- Finished basic implementation of simplified graphical model
- Began implementation of pickle files and chk2fasm to obtain net names
- Developed outline for Technical Presentation on bit_inspector

**Friday**:

- Holiday (Pioneer Day)

----

### Week 12: July 12, 2021 - July 16, 2021

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

- Planned format for model representation/reporting
- Began implemention of model design

**Wednesday**:

- Implemented and began testing of routing mux modelling
- Began implementation of modelling for whole tiles and designs
- Changed name of scripts to bits2model.py and fasm2model.py
- Moved tile data structures to their own .py script (int_tile.py) that is imported by both fasm- and bits- 2model.py

**Thursday**:

- Finished modelling funtions for muxes, tiles, and a design
- Began implementation of functions for printing models for muxes, tiles, and complete designs
- Began implementation of graphical text-art modelling

**Friday**:

- Finished implementation of printing models for muxes, tiles, and complete designs
- Finished basic implementation of graphical text-art modelling

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
