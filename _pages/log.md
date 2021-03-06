---
layout: default
title: Activity Log
---

### **Week 15: August 26, 2021**

* **Monday**:  
* **Tuesday**: 
* **Wednesday**: 
* **Thursday**: 
* **Friday**: 

  ##### **Goals for the week**
    * Update the chk2fasm Readme.md in the bit_inspector repository 
    * Start to create a FASM to Vivado translation function (possibly a python script that the tcl script will execute)
    * Learn to find the nets associated with routing bels (site_pips) and other elements in order to narrow down the associated nets using Vivado 2017.2
    * Figure how to identify gnd and vcc wires

### **Week 14: July 26-30, 2021**

* **Monday**: Attend tools meeting and work with Jackson to finilize some of the functionalities of the tcl script 
* **Tuesday**: Prepare for IMMERSE technical presentation 
* **Wednesday**: Prepare and present my IMMERSE technical presentation 
* **Thursday**: Meet with Jackson to discuss the issues I have encountered with getting the nets associated with other tiles other than inter-connect tiles
* **Friday**: I was not able to work today

  ##### **Goals for the week**
    * Update the chk2fasm Readme.md in the bit_inspector repository 
    * Start to create a FASM to Vivado translation function (possibly a python script that the tcl script will execute)
    * ~~Learn how to better communicate between tcl and python scripts (calling functions, upating variables, etc.)~~
    * Learn to find the nets associated with routing bels (site_pips) and other elements in order to narrow down the associated nets using Vivado 2017.2
    * Figure how to identify gnd and vcc wires

### **Week 13: July 19-23, 2021**

* **Monday**: out of town
* **Tuesday**: out of town
* **Wednesday**: Attend IMMERSE meetings and work with Jackson to add functionality to the tcl and python scripts
* **Thursday**: Made extra edits to the tcl and python scripts and pushed changes to the bit2net branch
* **Friday**: I was not able to come into work today

  ##### **Goals for the week**
    * Update the chk2fasm Readme.md in the bit_inspector repository 
    * Start to create a FASM to Vivado translation function (possibly a python script that the tcl script will execute)
    * Learn how to better communicate between tcl and python scripts (calling functions, upating variables, etc.)
    * Learn to find the nets associated with routing bels (site_pips) and other elements in order to narrow down the associated nets using Vivado 2017.2
    * Research FASM interpretations
    * Figure how to identify gnd and vcc wires

### **Week 12: July 12-16, 2021**

* **Monday**: I was not able to work today
* **Tuesday**: Attend Symbiflow meeting in the morning and met with Jackson in the afternoon to help each other with our assignements
* **Wednesday**: Attend IMMERSE meetings 
* **Thursday**: I was not able to work today
* **Friday**: Wrote a tcl script that takes a vivado checkpoint and a fasm file and outputs the net associated with each line of fasm (it can be run in vivado batch mode while sourcing the tcl script and taking the checkpoint and fasm file as arguments)

  ##### **Goals for the week**
    * Update the chk2fasm Readme.md in the bit_inspector repository 
    * Start to create a FASM to Vivado translation function (possibly a python script that the tcl script will execute)
    * Learn how to better communicate between tcl and python scripts (calling functions, upating variables, etc.)
    * Learn to find the nets associated with routing bels (site_pips) and other elements in order to narrow down the associated nets using Vivado 2017.2
    * Research FASM interpretations
    * Figure how to identify gnd and vcc wires

### **Week 11: July 4-9, 2021**

* **Monday**: Holiday
* **Tuesday**: Meeting with Jackson about specifics of our bit_inspector projects
* **Wednesday**: I was not able to come into work today
* **Thursday**: Chip camp
* **Friday**: Set goals for next week, 

  ##### **Goals for the week**
    * Add documentation to my Tcl script and python script
    * Update the chk2fasm Readme.md in the bit_inspector repository 
    * Start to create a FASM to Vivado translation function (possibly a python script that the tcl script will execute)
    * Learn how to better communicate between tcl and python scripts (calling functions, upating variables, etc.)
    * Learn to find the nets associated with routing bels (site_pips) and other elements in order to narrow down the associated nets using Vivado 2017.2
    * Research FASM interpretations
    * Figure how to identify gnd and vcc wires

### **Week 10: June 28-July 2, 2021**

* **Monday**: Attend tools meeting, add documentation to my tcl script, and research how to communicate between .tcl and .py files
* **Tuesday**: I was not able to come into work today
* **Wednesday**: Chip camp 
* **Thursday**: Chip camp
* **Friday**: Out of town

  ##### **Goals for the week**
    * Add documentation to my Tcl script and python script
    * Update the chk2fasm Readme.md in the bit_inspector repository 
    * Start to create a FASM to Vivado translation function (possibly a python script that the tcl script will execute)
    * Learn how to better communicate between tcl and python scripts (calling functions, upating variables, etc.)
    * Learn to find the nets associated with routing bels (site_pips) and other elements in order to narrow down the associated nets using Vivado 2017.2
    * Research FASM interpretations
    * Figure how to identify gnd and vcc wires

### **Week 9: June 21-25, 2021**

* **Monday**: Attended tools meeting and bootcamp, made progress on my python script so that it can take multiple bits as arguments
* **Tuesday**: Met with Corey about FASM to Vivado translation, updated tcl script to handle all of the FASM lines beneath a bit and only output the unique ones
* **Wednesday**: Attend IMMERSE meetings and bootcamp, add functionality to my Tcl script to include CLBLL tiles (not CLBLMs yet)
* **Thursday**: Set up ssh so I could worl remotely, added a tcl script option to iterate through the entire text file and find the nets for all of the bits
* **Friday**: Some chip camp prep, updated the tcl script to be able to find nets from CLBLM, CLK, HCLK, LIOI3, and LIOB33 tiles

  ##### **Goals for the week**
    * ~~Understand why the nets of some inter connect nodes can be found and why others cannot~~
    * ~~Add functionality to my Tcl script to handle other tiles besides inter connects~~
    * ~~Add a tcl script option to iterate through the entire text file and find the nets for all of the bits~~
    * ~~Add functionality to my Tcl/python scripts so that the nets for multiple bits can be found~~
    * ~~Clean up my Tcl script so it can notify when no net was found and when a FASM line cannot be handled or interpreted~~

### **Week 8: June 14-18, 2021**

* **Monday**: Learn how to execute shell commands, etc. in python so I can run my tcl script 
* **Tuesday**: Create a simple python script that takes a bit and the bit_inspector output file as arguments, runs my tcl script in vivado, and prints the net(s) associated with the argument bit
* **Wednesday**: Attend IMMERSE meetings and continue to work on my python script
* **Thursday**: Was not able to come in to work today
* **Friday**: Meet to discuss future plans for the bit_inspector project

  ##### **Goals for the week**
    * Add functionality to my Tcl script to handle other tiles besides inter connects
    * ~~Clarify how/what I should push to the bit_inspector repository~~

### **Week 7: June 7-11, 2021**

* **Monday**: Attend boot camp with guest speaker from Google and create a Tcl script to execute simple commands (find nets associated with a tile/site)
* **Tuesday**: Dowload bit-inspector project, learn how to generate .bits from .bit files, and add functionality to my very simple Tcl script 
* **Wednesday**: Attend IMMERSE meetings and learn more Tcl commands
* **Thursday**: Review the thesis about the inter connects and develop my Tcl script to be able to read a single line of fasm for the inter connects and output the acssociated net
* **Friday**: 

  ##### **Goals for the week**
    * ~~Complete all of the Xilinx FPGA deep dive activities~~
    * ~~Complete all of the Vivado Tcl tutorial activities~~
    * ~~Continue to learn Tcl commands and write Tcl scripts to accomplish tasks I have been doing with command line arguments~~
    * ~~Read pages 68-78 of Matthew Cannon's thesis~~

### **Week 6: May 31-June 4, 2021**

* **Monday**: Memorial Day 
* **Tuesday**: Coninue Xilinx FPGA deep dive activities
* **Wednesday**: Attend IMMERSE meetings, boot camp, and meet with professor Wirthlin, Ben, and Jackson to help us get started on our projects
* **Thursday**: Create a new Vivado project, generate a fasm file, and learn how to determine which fasm lines correspond to which parts
* **Friday**: Attend prjxray bootcamp, review and experiement with Tcl commands, and use simple Tcl commands to identify nets and cells associated with certain tiles or sites

  ##### **Goals for the week**
    * Complete all boot camp follow-up activities
    * Complete all of the Xilinx FPGA deep dive activities 
    * Complete all of the Vivado Tcl tutorial activities
    * ~~Rewatch Vivado Tcl boot camp lecture and become more comfortable with Tcl commands~~


### **Week 5: May 24-28, 2021**

* **Monday**: Modify bootcamp python project, fix bugs, and attend the FPGA overview bootcamp session 
* **Tuesday**: Implement pytest on my bootcamp python project, review some prjxray documentation, and begin to learn how to run vivado using tcl from the command line
* **Wednesday**: Attend IMMERSE meetings and learn how to open and close the vivado gui using tcl commands and also how to run tcl scripts from the command line
* **Thursday**: Got caught up on boot camp module activities that I had gotten behind on 
* **Friday**: Begin the Xilinx FPGA deep dive boot camp activities

  ##### **Goals for the week**
    * Complete all boot camp follow-up activities
    * Learn Vivado Tcl commands

### **Week 4: May 17-21, 2021**

* **Monday**: Make modifications to the python csv_parser boot camp project and generate a .fasm file for a simple 'and' gate project in Vivado
* **Tuesday**: Work on the IMMERSE proposal, read FASM documentation and run bit2fasm on a few simple FPGA designs in Vivado including an 'and' gate, 'nand' gate, and a flip flop 
* **Wednesday**: Attend IMMERSE meetings and learn about documentation with sphinx at bootcamp and write the IMMERSE summer proposal 
* **Thursday**: Begin to review Vivado Tcl boot camp module and other boot camp modules from past weeks
* **Friday**: Update bootcamp python project and review the documentation and testing boot camp modules

  ##### **Goals for the week**
    * Complete all boot camp follow-up activities
    * ~~Write IMMERSE project proposal~~ 
    * ~~Generate a .fasm file from various projects in Vivado~~
    * Learn how to read the .fasm files and figure out what they refer to

### Week 3: May 10-14, 2021

* **Monday**: Learn the basics of python, begin a simple python project, and learn more about cmake
* **Tuesday**: Finish building simple python program and attempt to compile using cmake, also conitue installation of prjxray
* **Wednesday**: Learn about python packages and environments and continue installation of prjxray
* **Thursday**: Finish installation of prjxray and work on the boot camp python csv parser follow-up activity
* **Friday**: Finish/perfect the python csv parser from boot camp and continue to read prjxray documentation 

### Week 2: May 3-7, 2021

* **Monday**: Become familiarized with VS code and learn more about SSH
* **Tuesday**: Learn the basics of make and more exploration with SSH
* **Wednesday**: Debug a C program and learn more about makefiles
* **Thursday**: Learn about cmake and begin reviewing prjxray documentation
* **Friday**: Begin installation of prjxray, learn more about cmake, and review how to use jekyll

### Week 1: April 26-30, 2021

* **Monday**: Download Linux and learn command line
* **Tuesday**: Set up SSH and begin setting up personal website
* **Wednesday**: Learn git and continue setting up personal website 
* **Thursday**: Learn git/github and finish setting up personal website 
* **Friday**: Refine personal website, learn more about github and practice more git commands