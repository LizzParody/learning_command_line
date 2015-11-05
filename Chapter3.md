#Chapter 3

Commands | Meaning
-----------|--------------------
ls | List directory content - the most used command
file | Determine file type
less | View file contents

##More fun with ls

ls type| Meaning
-------|--------
ls | to see the list of files of the current working directory
ls /usr | to see the list of files of a specific directory
ls ~ /usr | or multiple directories (~ root directory)- (usr directory)
ls -l | We can also change the format of the output to reveal more detail (-l long format)

###Options and arguments
Commands are often followed by one or more options that modify their behavior and, further, by one or more arguments, the items upon which the command acts. So most commands look something like this:
```
command -options arguments
```

**Long options** is an option preceded by two dashes --

Long options| Meaning
--------|------
ls -lt | In this example, the ls command is given two options (-l to produce long format and to sort the result by the file’s modification time)
ls -lt --reverse = ls -lt -r | the first one is long option.

The ls command has a large number of possible options. The most common are listed in the next Table:

![option_ls](https://github.com/lizparody/learning_command_line/blob/master/ls_options.png)

##Determining a File's type with file
The *file* command will print a brief description of the file’s contents.
```
file *filename*
Lyzzeths-MacBook-Pro:learning_command_line lizparody$ file Chapter3.md
Chapter3.md: UTF-8 Unicode English text
```

##Less command
The less command is a program to view text files. Many of the files that contain system settings (called configuration files) are stored in this format, being able to read them gives us insight about how the system works. In addition, many of the actual programs that the system uses (called scripts) are stored in this format.

IT SHOWS THE TEXT CONTENT.
```
 less *filename*
 ```


_______________________
There are many ways to represent information on a computer. One of the simples one is ASCII text. ASCII (pronounced “As-Key”) is short for Amer- ican Standard Code for Information Interchange. Plain ASCII text files contain only the characters themselves and a few rudimentary control codes like tabs, carriage returns, and linefeeds.
Throughout a Linux system, many files are stored in text format, and many Linux tools work with text files. 
