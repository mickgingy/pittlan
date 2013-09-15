PittLan Game Development Environment
===============

This is the development environment for PittLan, below is a step-by-step guide to
help you set it up on your machine


Mac OS X
---------------
go to: https://developer.nvidia.com/cg-toolkit-download and download the Mac OS X version.

Linux
--------------
~~~~~~~~~~~~
sudo apt-get install libgl1-mesa-dev python-virtualenv python
~~~~~~~~~~~~
---------------
Go to: https://developer.nvidia.com/cg-toolkit-download and download appropriate version for you Linux distribution
Windows
---------------
(certain instructions adapted from https://github.com/turbulenz/turbulenz_engine

First ensure you have the windows compiler toolchain installed, if you do not or are unsure,

go to http://www.microsoft.com/visualstudio/eng/products/visual-studio-express-products, then download and install for your version of Windows.


Ensure that you have followed setup of Githusb for windows HERE

Run the Git Shell, in the PowerShell window that opens type:
~~~~~~~~~

git clone https://github.com/PittLAN/pittlan
git submodule update --init
~~~~~~~~~

Local Web Server
---------------

Since we will be working with JavaScript, having a local web server can be helpful.
To do this
