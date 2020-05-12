1. ```source```
<hr>

#Source Command

	The source command reads and executes commands from the file specified as its argument in the current shell environment. It is useful to load functions, variables and configuration files into shell scripts. 

	``source`` is a shell built-in Bash and other popular shells used in linux and UNIX operating systems.

```bash
source FILENAME [ARGUMENTS]
. FILENAME [ARGUMENTS]
```
	a. If the FILENAME is not full path to a file, the command will search for the file in the directories specified in the $PATH environment variable. If the file is not found in the $PATH the command will look for the file in the current directory
	b. ```source``` and ```.``` are the same

