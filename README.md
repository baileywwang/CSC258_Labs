The purpose of the GitHub repository is to showcase my course work for CSC258H1 Course (https://fas.calendar.utoronto.ca/course/csc258h1). All source files for my lab demos as well as my pre-lab submissions are included here in this repository. Here are some instructions for testing my Verilog design:

# Before you start
You need to make sure you have the either of the below two sets:
- ModelSim*-Intel® FPGA Edition Software (https://www.intel.com/content/www/us/en/software/programmable/quartus-prime/model-sim.html)
- Download Intel® Quartus® Prime Software (https://www.intel.ca/content/www/ca/en/software/programmable/quartus-prime/download.html) _AND_ a DoC-SE1 Board, which can be purchased at https://www.terasic.com.tw/cgi-bin/page/archive.pl?Language=English&No=836.

Both softwares can be downloaded at http://fpgasoftware.intel.com/18.1/?edition=lite. In the near future, I will provide a detailed instruction on how to install the two softwares. Unfortunately, Apple users do need to install a Windows or Ubuntu virtual machine before working with above two softwares. 

# Test the Verilog Design with ModelSim®
To test my Verilog files using ModelSim®, please follow the following steps:
- Open the folder where my Verilog File is located.
- Remember the name of the file that has suffix ".do".
- Open ModelSim®.
- In the ModelSim® Console, cd into the folder where the Verilog file is located.
- Type do + the name of the ".do" file including the suffix.

One thing to keep in mind is that in order to thoroughly test my Verilog design, some of my ".do" files has long test cases. On my machine, it could take up to 1 hour for ModelSim to finish the simulation. To see what each switch/key/output does, you may refer to the Lab handout which contains the requirements for my Verilog design.

# Test the Verilog Design with Quartus® and DoC-SE1 board.
To test my Verilog files using Quartus® and DoC-SE1 board, please follow the following steps:
- Connect your DoC-SE1 board to your machine and open Quartus®.
- Click File -> Open Project, to open the ".qpf" project file.
- Click Tools -> Programmer. A window will pop-out.
- Click Hardware Setup. You should see the connected board in the window popped out.'
- Double Click the DoC-SE1 board, and press "OK".
- Delete everything in the file list.
- Press "Auto Detect", then select "5CSEMA" before pressing "OK".
- Double Click the "5CSEMA5F31C6" device, and import the output file from the output folder.
- Press "Start" to download the compiled code to the board.

It's now time to play with the board! Part 2 of the 7th lab requires another Mornitor and a VGA cable for testing. To see what each switch/key/output does, you may refer to the Lab handout which contains the requirements for my Verilog design.

Important: 
-
As per University of Toronto's policy on Turnitin.com, my pre-lab files were (automatically) submitted to Turnitin plagiarism detection software. My pre-lab submissions has been included as source documents in the Turnitin.com reference database. My lab works here are not intended to be reused for any academic purposes.