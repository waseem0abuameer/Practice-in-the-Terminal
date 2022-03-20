# Command Line 
1. The command line is a text interface for your computer. It's a program that takes in commands, which it passes on to the computer's operating system to run.
2. A command line, or terminal, is a text based interface to the system. You are able to enter commands by typing them on the keyboard and feedback will be given to you similarly as text.

======================================
## Basic Navigation
1. cd ===> Change Directories - ie. move to another directory.
2. pwd ==>Print Working Directory - ie. Where are we currently.
3. ls ==>List the contents of a directory.
==============================
# important concept
```
### Relative path
A file or directory location relative to where we currently are in the file system.
### Absolute path
A file or directory location in relation to the root of the file system.

```
===============================
# More About Files!
1. Everything is a File
 everything is actually a file. A text file is a file, a directory is a file, your keyboard is a file (one that the system reads from only), your monitor is a file (one that the system writes to only) etc. 


2. Linux is an Extensionless System
This one can sometimes be hard to get your head around but as you work through the sections it will start to make more sense. A file extension is normally a set of 2 - 4 characters after a full stop at the end of a file, which denotes what type of file it is. The following are common extensions:

file.exe - an executable file, or program.
file.txt - a plain text file.
file.png, file.gif, file.jpg - an image.
In other systems such as Windows the extension is important and the system uses it to determine what type of file it is. Under Linux the system actually ignores the extension and looks inside the file to determine what type of file it is. So for instance I could have a file myself.png which is a picture of me. I could rename the file to myself.txt or just myself and Linux would still happily treat the file as an image file. As such it can sometimes be hard to know for certain what type of file a particular file is. Luckily there is a command called file which we can use to find this out.

3. Linux is Case Sensitive
This is very important and a common source of problems for people new to Linux,As such it is possible to have two or more files and directories with the same name but letters of different case.
4. Spaces in names
Spaces in file and directory names are perfectly valid but we need to be a little careful with them. As you would remember, a space on the command line is how we seperate items.
5. Hidden Files and Directories
==============================================
# Manual Pages!
1. man <command>
Look up the manual page for a particular command.
2. man -k <search term>
Do a keyword search for all manual pages containing the given search term.
3. /<term>
Within a manual page, perform a search for 'term'
4. n
After performing a search within a manual page, select the next found item.


