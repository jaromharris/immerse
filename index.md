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
* **Thursday**: Worked at chip camp all day in the magnetic muscles module
* **Friday**: Helped Sam with the pudc unit test. Worked on debugging not equivalences with Yosys. Added system verilog functionality to bfasst.

### Week 12: July 12, 2021
* **Monday**: Investigated a problem I'm having with yosys where it doesn't consider FDCEs to be equivalent. Learned the difference between FDCEs and FDREs.
* **Tuesday**: Added more designs to the BFASST repo. Worked on my presentation. Dug into some of the not-equivalent results of BFASSt.
* **Wednesday**: Met with BFASST team, prepared for presentation, worked on not equivalent designs
* **Thursday**: Worked on putting together a pull request for integrating bfasst into fasm2bels doing equivalence testing.
* **Friday**: Worked on bfasst integration pull request. 

### Week 13: July 19, 2021
* **Monday**: Worked on simplifying a design that was failing equivalence checking to pin point what about the design was causing it to fail.
* **Tuesday**: Dug more into my issue with Yosys equivalence checking where my simple design was showing not equivalent.
* **Wednesday**: Figured out how to make vivado not include dsp modules since fasm2bels doesn't support them. Submitted an issue to Yosys about equivalence checking.
* **Thursday**: Absent
* **Friday**: Holiday

### Week 14: July 26, 2021
* **Monday**: Worked for just a few hours today, I looked into how to install Yosys using conda to run a comparison checking CI test.
* **Tuesday**: One of the antmicro people said that I could look at symbiflow-arch-defs to learn how to install Yosys via conda, so I explored that today.
* **Wednesday**: I continued to look into how to install Yosys via conda, and I looked into some of the designs that don't pass conformal or yosys equivalence checking. I helped out Sam with some issues he was having.
* **Thursday**: Worked on figuring out why yosys equivalence checking was failing. Began to make an example to show a minimal design that was failing.
* **Friday**: Continued to work on the minimal design, submitted the issue to Yosys and looked into some issues of failing designs in bfasst.

### Week 15: August 3, 2021
* **Monday**: Helped Sam with some issues he was having. Someone responded to my issue on Yosys, it fixed part of the problem, but not the entire thing.
* **Tuesday**: Worked on making another minimal design that was having the same issue in Yosys, looked into the other failing designs in bfasst.
* **Wednesday**: Attended immerse student presentations, helped Sam try to figure out how to use Conformal gui. Sent my minmal design to Yosys.
* **Thursday**: Worked on my immerse summer summary on learning suite, and looked into failing designs in bfasst.
* **Friday**: Vacation

### Week 16: August 9, 2021
* **Monday**: Vacation
* **Tuesday**: Vacation
* **Wednesday**: Vacation
* **Thursday**: Vacation
* **Friday**: Vacation

### Week 17: August 16, 2021
* **Monday**: Vacation
* **Tuesday**: Vacation
* **Wednesday**: Vacation
* **Thursday**: Vacation
* **Friday**: Vacation
