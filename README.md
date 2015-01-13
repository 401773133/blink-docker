# Blink + Docker = :heart: #

### Disclaimer ###
This tool is experimental and still in development. Feel free to post any issues you encounter so that we can squash the remaining bugs that are hiding. Any suggestions or any improvement ideas are welcome to make Blink with Docker a better and stable tool.

### Requirements ###
**Python 3** and **Docker** are needed to build Blink.  

**Python 3**  
For Fedora: `sudo yum install python3`  
For Ubuntu/Debian: `sudo apt-get install python3`  

**Docker**  
For Fedora: [Link](https://docs.docker.com/installation/fedora/)  
For Debian: [Link](https://docs.docker.com/installation/debian/)  
For Ubuntu: [Link](https://docs.docker.com/installation/ubuntulinux/)  

It is recommended to have at least **6GB** of free hard drive space to install every Blink components.

### Installation ###
Run the **install.py** script to build Blink from scratch. The process can take some time depending on your internet connection (download of packages, fonts and plugins).

### Running ###
Run the **run.py** and it will launch a browsing platform on the fly in a matter of seconds. The script checks if the installation was correct so if the script encounters any problems during this step, go through the complete installation process again.

### Windows and MacOS support ###
While Windows and MacOS are not officially supported yet, it should be possible to run Blink on these platforms via a Linux virtual machine with VirtualBox or VMWare.  
It should be noted that we may investigate the use of Boot2Docker in the future to improve performances.
