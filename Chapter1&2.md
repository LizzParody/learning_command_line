#The Linux Command Line
##William E. Shotts, JR.

GUI: Graphical User Interface (is a type of interface that allows users to interact with electronic devices through graphical icons and visual indicators such as secondary notation).

CLI: Command Line Interface ( is a means of interacting with a computer program where the user (or client) issues commands to the program in the form of successive lines of text (command lines)).

Command line is equal to *shell*

A **Shell** take keyboard commands and passes them to the operating system to carry out.

A **shell prompt** is:
```  
[me@linuxbox ~]$ // And it appears whenever the shell is ready to accept input.
```
```
[me@linuxbox ~]# // when it finish with # is because it has superuser privileges.
```

We all have a virtual terminal that is running behind our graphical Desktop.

The command **ls** to the terminal -> list the files in the current directory or any other directory.

###Pathname

Is a route we take along the branches of the tree to get the directory we want.

**Absolute Pathname**
Begins with the root directory and follows the tree branch by branch until the path to the desired directory or file is completed.

```
usr/bin //this is an Absolute Pathname.
cd /usr //to change to the previous directory.
```

**Relative Pathname**
Where an absolute pathname starts from the root directory and leads to its destination, a relative pathname starts from the working directory. To do this, it uses a couple of special symbols to represent relative positions in the file- system tree. These special symbols are . (dot) and .. (dot dot).
The . symbol refers to the working directory and the .. symbol refers to the working directory’s parent directory.

```
usr/bin //the same example
cd .. // you use .. to go back to the previous directory.
cd - // is the same as cd .. (go back to the previous directory).
cd ~ username // change the working directory to the home directory of the username
```

##Facts
1. Files names that begin with period are hidden, ls will not list them unless you type ls -a
2. Files names are case sensitive.
3. Never leave spaces in the name of a file/folder.
