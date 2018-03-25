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

* `pwd`
Show current working directory path
* `mkdir`
Create directory
* `rm [dir]` 
Delete directory
* `touch`
Create file
* `rm [file]`
Delete file
* `mv [source] [destination/renamed]`
Rename file
* `ls -a`
List hidden files
* `cp [source] [destination]`
Copy from one directory to other
* `cd`
Change directory
* `cat`
Concatenate or view

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

* `ls`  
List directory contents
* `ls -a`  
List directory, inculde hidden
* `ls -l`  
List directory, long format
* `ls -lh`  
List directory, long format, human-readable file size
* `ls -lah`  
List directory, include hidden, long format, human-readable file-size
* `ls -t`  
List directory, sorted by last modified
* `ls -Glp`  
List direcotry, long format without group names, append



---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

* `ls -1`
Display each file on new line
* `ls -r`
Display in reverse order
* `ls -R`
Include subdirectories
* `ls -u`
Display, sort by access time
* `ls -x`
Display entries in rows

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

`xargs` can pass multiple user inputs as parameters to functions or be used to chain commands.

For example, to generate multiple directories in one command:
`echo 'dir1 dir2 dir3' | xargs mkdir`


 

