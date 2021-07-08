---
layout: default
title: IMMERSE Log
---

### Week 1: April 26, 2021

* **Monday**: Set up computer, completed linux tutorial
* **Tuesday**: Set up website, learned git and github
* **Wednesday**: Dowloaded Vitis and Vivado, wrote a testbench, completed more git activities
* **Thursday**: Learned about TCL scripts, experimented with Ice Machine
* **Friday**: Explored Vivado and learned about netlists, cells, tiles, etc. Worked on fixing errors that came with running make install on icemachine.
  
### Week 2: May 3, 2021
* **Monday**: Learned about Project Xray, downloaded vivado 2017 and 2019, worked on BFASST
* **Tuesday**: Explored bfasst python scripts, learned about make
* **Wednesday**: Debugged BFASST, met with Chip Camp group
* **Thursday**: Explored BFASST by running basic designs and running experiment. Did the make activity.
* **Friday**: Solved issues with git branches, learned about how to do equivalence comparisons with Yosys

### Week 3: May 10, 2021
* **Monday**: Tried to figure out how to do comparisons with Yosys, learned about fasm2bels and prjxray
* **Tuesday**: Continued to struggle with using Yosys for equivalence verifications, worked on prjxray setup 
* **Wednesday**: Planned with Chip Camp group, experimented with Yosys
* **Thursday**: Learned about python and worked on the csv assignment with python, learned more about bfasst's python code
* **Friday**: Completed csv assignment with python, continued to investigate bfasst's code to be able to automate yosys equivalence checking

### Week 4: May 17, 2021
* **Monday**: Worked on getting the new flow for Yosys comparison working. 
* **Tuesday**: Wrote my summer proposal paper. Took inventory for chip camp. Learned about fasm2bels
* **Wednesday**: Got demos ready for Chip Camp, fixed my csv parser so that it printed multiple columns, learned about FASM
* **Thursday**: Read through some of the Project Xray documentation, learned about .yaml files, looked into fasm_2_bels bugs
* **Friday**: Absent

### Week 5: May 24, 2021
* **Monday**: I watched the docker and python packages II bootcamp tutorials that I missed. Wrote a unit test and documentation for CSV parser.
* **Tuesday**: Learned more about Sphinx documentation and unit testing. Learned about netlists.
* **Wednesday**: Tried to use EDAlize and FuseSoC and understand how they work as tool wrappers. Worked on chip camp.
* **Thursday**: Read through EDAlize code and tried to understand what it was doing. 
* **Friday**: Read through the FPGA deep dive self tutorial.

### Week 6: May 31, 2021
* **Monday**: Holiday
* **Tuesday**: Debugged the problems I was having with EDAlize. Worked more on the FPGA Deep Dive.
* **Wednesday**: Worked on my iron cores for chip camp. Explored some of the bugs in fasm2bels.
* **Thursday**: Worked on integrating EDAlize into bfasst.
* **Friday**: Integrated EDAlize into bfasst.

### Week 7: June 7, 2021
* **Monday**: Dug more into the fasm2bels bugs with the carry4s. Made some weights for chip camp.
* **Tuesday**: Tried to get fasm2bels to pass pull request checks by adding in license headers, ended up marking the files as generated
* **Wednesday**: Tried to fix the carry 4 bug in fasm2bels, did a chip camp dry run for my module
* **Thursday**: Tried to fix the carry 4 bug in fasm2bels basically all day
* **Friday**: Learned more about how fasm2bels processes sites and adds sources and sinks

### Week 8: June 14, 2021
* **Monday**: Set up the debugger for fasm2bels and learned more about the code base.
* **Tuesday**: Looked through the functions of the site class and found one to replace add_source which fixed the bug. Tested it with regression test.
* **Wednesday**: Found another bug in the code that omits an OBUF from the reversed netlist. I found out that this bug exists in symbiflow master. I worked on chip camp today as well.
* **Thursday**: Soldered some alligator clips to some wires for chip camp. Made the pull request for the carry4 bug. Moved edalize to be a third_party submodule in bfasst.
* **Friday**: Absent

### Week 9: June 21, 2021
* **Monday**: Made a test for the carry4 issue on fasm2bels and fixed other things that acomodi asked me to. Learned more about python.
* **Tuesday**: Fixed more things on the carry4 fix pull request. Learned how to make a eblif file using yosys.
* **Wednesday**: Started running and debugging more IP from the examples directory in bfasst. Worked on chip camp wires for electromagnets.
* **Thursday**: Tried to get fusesoc to synthesize and implement a design using yosys and vpr. Ran some regression tests on bfasst and tried to debug.
* **Friday**: Tried to run the symbiflow toolchain through fusesoc, but it didn't work so I spent a while trying to figure out why symbiflow_synth wasn't recognized. Didn't figure it out. Figured out how to run the CI test locally on my machine, but I couldn't figure out where it stores the generated files.

### Week 10: June 28, 2021
* **Monday**: Worked on generating an eblif file that test_fasm2bels will use to test the carry4 issue. I also got the demos prepared for chip camp.
* **Tuesday**: Tested my test for the carry4 fix and cut some more solid iron cores for the electromagnets for chip camp.
* **Wednesday**: Figured out what my eblif file was missing so now it is passing the tests, ran regression tests on bfasst.
* **Thursday**: Worked in the electromagnetism module of chip camp basically all day.
* **Friday**: Spent some time learning about implications of bfasst and preparing my technical presentation.

### Week 11: July 5, 2021
* **Monday**: Holiday
* **Tuesday**: Worked on technical presentation and helped Sam make the unit test for the pudc fix.
* **Wednesday**: Worked on solving the issue of conformal and yosys showing not equivalent when equivalence checking is run in bfasst.
* **Thursday**: 
* **Friday**: 

### Week 12: July 12, 2021
* **Monday**: 
* **Tuesday**: 
* **Wednesday**: 
* **Thursday**: 
* **Friday**: 
