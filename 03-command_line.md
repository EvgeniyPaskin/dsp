# Learn command line

Please follow and complete the free online [Bash Scripting Tutorial](https://ryanstutorials.net/bash-scripting-tutorial/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. You should be able to go through these in a couple of hours.

**Note:** Bash is not installed on a PC. Rather, PC users must install Cygwin. Once Cygwin has been installed, the command line interface witll _emulate_ bash. You can find all information regarding Cygwin [here](https://www.cygwin.com/).

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

```
show current working directory path = pwd
creating a directory = mkdir [dir]
deleting a directory = rmdir [dir]
creating a file using touch command = touch [file]
deleting a file = rm [file]
renaming a file = mv [file] [new filename]
listing hidden files = ls -a
copying a file from one directory to another = cp [file] [dir]
+
change directory = cd [folder]
open a file = open [file]
```

---

### Q2.  List Files in Unix   

What do the following commands do:  



```
`ls`      = Short listing
`ls -a`   = Listing incl. hidden files
`ls -l`   = Long listing
`ls -lh`  = Long listing with Human readable file sizes
`ls -lah` = Long listing with hidden files and Human readable file sizes
`ls -t`   = Sort by time
`ls -Glp` = Shows file type and file permissions

```

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

```
ls -R =	Displays subdirectories as well.
ls -m	= Displays the names as a comma-separated list.
ls -1	= Displays each entry on a line.
ls -d	= Displays only directories.
ls - S = sort by size
```
---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

 It converts input from standard input into arguments to a command

Example from the manual:

Read a list of filenames from filelist.txt (one per line) and copy them to new_folder:
```
$ xargs -a filelist.txt cp -t new_folder
``` 

