# Install Vivado

If you do not have Vivado installed, follow these steps:

* Go to [Xilinx](https://www.xilinx.com/support/download.html) and download the vivado webpack.
  * Be sure to choose the web installer for the full version
    * Vivado Design Suite - HLx Editions - 2019.1  Full Product Installation
  * You have to make an account with Xilinx. Either create an account or login with your existing user.
* Run the web installler
  * Login with your user
  * Agree to the agreements
  * Choose Vivado HL WebPACK
  * If you are worried about disk space, you can deselect 
    * Software Development Kit (SDK)
    * Ultrascale 
    * Ultrascale+
    * SoCs
  * Choose a suitable installation location.
    * Can be left untouched
    * Change if you want to install Vivado on another (external) drive
  * Install
    * This may take some time as it wil first download and then install.
* Verify that Vivado is installed correctly by launching the progam.
* Now, include the board files for Vivado. This lets you choose the Basys 3 board when making a new project.
  * [Download](board_files.zip) the zip file containing the board files, located in this folder.
  * Extract the zip to \VIVADO_INSTALL_LOCATION\Vivado\201x.x\data\boards
    * There should already be a folder here. Merge the two or replace it with the new one.
  * You should now be able to choose the Basys 3 board and others, when making a new project.



# FAQ
[My Chrome browser only shows a dinosaur!?](#My-Chrome-browser-only-shows-a-dinosaur!?)

# 


## My Chrome browser only shows a dinosaur!?
This is a well know issue. Connect to the internet and the dinosaur will go away.

