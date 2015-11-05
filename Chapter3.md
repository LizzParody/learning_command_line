###Chapter 3

Commands | Meaning
------------------
ls | List directory content - the most used command
file | Determine file type
less | View file contents

##More fun with ls

```
ls // to see the list of files of the current working directory
ls /usr // to see the list of files of a specific directory
ls ~ /usr // or multiple directories (~ root directory)- (usr directory)
ls -l // We can also change the format of the output to reveal more detail (-l long format)
```
#Options and arguments
Commands are often followed by one or more options that modify their behavior and, further, by one or more arguments, the items upon which the command acts. So most commands look something like this:
```
command -options arguments
```

**Long options** is an option preceded by two dashes --

```
ls -lt // In this example, the ls command is given two options (-l to produce long format and to sort the result by the file’s modification time)
```
