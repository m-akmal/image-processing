---
layout: page
title: Setup
permalink: /setup/
---

## Setup instructions for the Image Processing workshop

We are using a virtual Linux machine for this workshop, since the computer 
vision libraries we use can be difficult to install and configure. This 
allows you to run our "standard" computer, regardless of your specific 
Windows, Mac, or Linux computer. Here are the details regarding our machine 
and its pre-installed software suite.

### Operating system

64-bit Ubuntu 16.04. 

### Login information

The machine is set to automatically log in to a user account. If needed, 
the username is **diva** and the associated password is **DoaneDiva16**.

### Software suite

The machine is pre-configured with the following software:

- gcc (C / C++ compiler)
- Geany (lightweight integraded development environment (IDE))
- git
- gnuplot (for plotting and graphing)
- ImageJ
- Java JDK 8 and NetBeans IDE (for Java development)
- Python 3.6.0 (Anaconda 4.3.1)
-- OpenCV
-- numpy
-- scipy
-- matplotlib
-- mahotas
-- scikit-learn
- R and RStudio

## Installation

1. Download and install the free Oracle VirtualBox software, via this 
[link](https://www.virtualbox.org/wiki/Downloads "VirtualBox download")

2. Download the DIVAS virtual machine image via this 
[link](http://www.google.com "FIXME"). This a 6 GB file, so the download 
will likely take a while.

3. Start your VirtualBox application.

4. Import the image file you downloaded, via the File / Import Appliance 
menu item. Adjust the memory for the virtual machine to be no more than 
one-half of the total memory your computer has.

## Running the virtual machine for the first time

1. If it is not already running, start your VirtualBox application.

2. Highlight the DIVAS virtual machine in the left-hand pane.

3. To start the virtual machine the first time, click on the Start button 
(the green arrow). After it starts, the machine will automatically log you 
in and take you to an orange desktop.

4. Install the Guest Additions, which will allow the virtual machine to 
work more seamlessly with your computer. 

	* From the VirtualBox VM Devices menu, choose the Insert Guest 
Additions CD Image... item. You will be asked if you want to run the 
additions; click Run.

	* When prompted, enter the **diva** user password, **DoaneDiva16**, 
and wait until the process is complete (when the terminal says "Press Return 
to close this window...").

	* Hit enter, then eject the CD image by right clicking on the disk 
icon on the left side launcher bar and choosing "Eject," and then restart 
the virtual machine, by clicking on the gear icon in the upper right corner 
and choosing the "Shut Down" item.

5. Set your name and email address for git

	* Open a Terminal window

	* Execute the mygit script, like this (use your own information, 
and make sure to include the quotes):

~~~
mygit "Jane Smith" "jane.smith@mail.com"
~~~
{: .bash}




