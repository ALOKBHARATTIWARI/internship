# Task 1

In this task, you will implement a myls command similar to the ls command
provided by Linux coreutils. Options to be implemented for the myls command
are shown below. In short, running myls with -al option has to display the
same information as coreutils ls.


### Options to be implemented
* -a
* -l
* -al or -la or -a -l (these options interpret both of -a and -l.)
# Notes
* When listing directory contents, do not display any files or directories
whose names start with dot (.) unless the -a option is given.
* Symbolic links and hard links should be displayed as in coreutils ls.
* When multiple files and directories are given as parameters, display all of
them.
* Displays an error message if files or directories with given names do not
exist.
* The display uses English.
* This need not have exactly the same behaviors, error messages, etc. as
the existing ls of coretuils, and error handlings also need not be complete.

You do not have to read the code of coreutils.
* You also need not consider return codes of errors or successes.
* You do not need to use colored highlights depending on terminals.
* You do not need to consider the width of users’ terminals (because it can
take much time and energy).
* To check your implementation, consider the commands below and compare
them with those of myls.
```
• ls
• ls -la .
• ls -la ..
• ls -la /proc/self
• ls -la /proc/self/
```
# Task 2
Pick two options explained in the ls manpage (except --version and --help)
and add them to the myls command implemented in Task 1.
For example, these options could be
```
* -R
* -s
* -S
```
If there is not enough time to complete the tasks, please submit code and report
as far as you were able to implement/write them.
