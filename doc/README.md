# Getting Started
This is the official OpenTAP documentation for users and developers.


## What is OpenTAP

OpenTAP is an Open Source project for fast and easy development and execution of automated tests. 

OpenTAP is built with simplicity, scalability and speed in mind, and is based on an extendable architecture that leverages .NET Core. 
OpenTAP offers a range of sequencing functionality and infrastructure that makes it possible for you to quickly develop plugins tailored for your automation needs – plugins that can be shared with the OpenTAP community through the OpenTAP package repository. 

Learn more about OpenTAP [here](http://opentap.io).



## Install OpenTAP
### Windows
1. Download OpenTAP from our homepage [here](https://www.opentap.io/download.html). 
2. Start the installer.

We recommend that you download the Software Development Kit, or simply the Developer’s System Community Edition provided by Keysight Technologies. The Developer System is a bundle that contains the SDK as well as a graphical user interface and result viewing capabilities. It can be installed by typing the following:
```
cd %TAP_PATH%
tap package install "Developer's System CE" -y
```

### Linux
<!--When installing on Linux there are a few options:-->

Download the OpenTAP distribution (`.tar`<!--, `.dep` or `.rpm`-->) from our homepage [here](https://www.opentap.io/download.html). 

Install the downloaded distribution:

<!--- `.dep` run `sudo apt install ./OpenTAP*.deb`
- `.rpm` run `sudo dnf install ./OpenTAP*.rpm`-->
- `.tar` do the following:
	1. Untar the package in you home directory `tar -xf OpenTAP*.tar`
	2. Change the permission of the INSTALL.sh file to be executable: `chmod u+x INSTALL.sh`
	3. Run the INSTALL.sh script: `./INSTALL.sh`.


## Use OpenTAP
If you are an OpenTAP user, or just want to try it out, have a look at the [User Guide](User%20Guide/Introduction/).


## Develop Plugins
If you are a developer and want to create plugins for OpenTAP, have a look at the [Developer Guide](Developer%20Guide/Introduction/).