<h1>Linux XK0-006 Lab 1.1 - Linux Basics</h1>

 ### [YouTube Demonstration Coming Soon](https://youtube.com)

<h2>Description</h2>
In this lab, you will work through the following exercises:

- <b>Exercise 1</b> – Navigating the Linux System
- <b>Exercise 2</b> – Basic File Operations

<h2>Languages and Utilities Used</h2>

- <b>Command Line</b> 

<h2>Environments Used </h2>

- <b>Linux - Ubuntu</b>

<h2>Exercise 1: Navigating the Linux System</h2>
The Linux file system follows a hierarchical structure starting from the root directory (/). Understanding how to navigate this structure and access documentation is fundamental to working efficiently in Linux.
<br />
<br />

<p align="center">
1. Click the Terminal icon in the left pane: <br/>
<img src="https://imgur.com/RbAabsu.png" height="30%" width="30%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
2. In the Terminal window, type <b><i>pwd</i></b> to display your current working directory:  <br/>
<img src="https://imgur.com/A5CS5jz.png" height="50%" width="50%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
3. Type <b><i>ls</i></b> to list the files and directory of the current location: <br/>
<img src="https://imgur.com/F3A5pDA.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
4. The <b><i>ls -l</i></b> option displays the long format, showing permissions, ownership, size, and modification date for each item:  <br/>
<img src="https://imgur.com/gsuUWkS.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
5. The <b><i>ls -a</i></b> option shows all files, including hidden files that begin with a dot (.). Hidden files typically contain configuration settings:  <br/>
<img src="https://imgur.com/XHVxREW.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br /><p align="center">
6. The <b><i>cd</i></b> (change directory) command moves you to a different directory. The forward slash (/) represents the root directory, which is the top level of the Linux file system hierarchy:  <br/>
<img src="https://imgur.com/wcyaa0O.png" height="50%" width="50%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
7. Type <b><i>pwd</i></b> to verify current location. You should now see (/) as the output, confirming you are in the root directory:  <br/>
<img src="https://imgur.com/zl0wqmO.png" height="50%" width="50%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
8. Type <b><i>ls</i></b> to see the contents of the root directory. You will see important system directories such as bin, etc, home, usr, var, and others. Each directory serves a specific purpose in the Linux file system hierarchy:  <br/>
<img src="https://imgur.com/yDL7g5m.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
9. Type <b><i>cd /etc</i></b> to navigate to the /etc directory. The /etc directory contains system-wide configuration files and settings:  <br/>
<img src="https://imgur.com/MKOOnPh.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
10. Type <b><i>pwd</i></b> to confirm location. Type <b><i>ls</i></b> to list the configuration files. You will see numerous configuration files and directories. These files control system settings and application configurations:  <br/>
<img src="https://imgur.com/YppAmbz.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
11. Type <b><i>cd</i></b> to navigate to the /usr/bin directory. The /usr/bin directory contains executable programs and commands available to all users. Type <b><i>ls | head -20</i></b> to list some of the executables. The pipe symbol ( | ) sends the output of ls to the head command, which displays only the first 20 lines. This is useful when a directory contains many files:  <br/>
<img src="https://imgur.com/00xkhOK.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
12. Type <b><i>cd ~</i></b> to return to your home directory. The tilde (~) symbol is a shortcut that represents your home directory. You can use <b><i>cd ~</i></b> from anywhere in the file system to return home. Type <b><i>pwd</i></b> to verify you are back in your home directory:  <br/>
<img src="https://imgur.com/kfRNTD9.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
13. Type <b><i>cd /var/log</i></b> to navigate to the /var/log directory. The /var/log directory contains system log files that record various system activities and events. Type <b><i>ls -lh</i></b> to view the log directory contents. The -h option displays file sizes in human-readable format (KB, MB, GB) instead of bytes:  <br/>
<img src="https://imgur.com/4MS386X.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
14. Type <b><i>cd</i></b> to navigate back to your home directory using an alternative method. Using <b>cd</b> without any arguments also takes you to your home directory:  <br/>
<img src="https://imgur.com/ZYrtH1n.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />
<p align="center">
15. Type <b><i>clear</i></b> to clear the Terminal window:  <br/>
<img src="https://imgur.com/5MOFZ0F.png" height="80%" width="80%" alt="Lab1.1 Steps"/>
<br />
<br />

</p>
