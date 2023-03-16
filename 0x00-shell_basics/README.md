
<h1 align="center">A simple description of what each shell script file does!</h1>

	0- A script that prints the absolute path name of the current working directory. 
	
	1- A script that display the contents list of your current directory.
	
	2- A script that changes the working directory to the user’s home directory.
	
	3- A script that display current directory contents in a long format.
	
	4- A script that display current directory contents, including hidden files (starting with .). Use the long format.
	
	5- A script that display current directory contents.
	
	6- A script that creates a directory named my_first_directory in the /tmp/ directory.
	
	7- A script that move the file betty from /tmp/ to /tmp/my_first_directory.
	
	8- A script that delete the file betty.
	
	9- A script that delete the directory my_first_directory that is in the /tmp directory.
	
	10- A script that changes the working directory to the previous one.
	
	11- A script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
	
	12- A script that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
	
	13- A script that create a symbolic link to /bin/ls, named __ls__.	
	
	14- A script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
	
	100- A script that moves all files beginning with an uppercase letter to the directory /tmp/u.
	
	101- A script that deletes all files in the current working directory that end with the character ~.
	
	102- A script that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.
	
	103- A script that that lists all the files and directories of the current directory, separated by commas (,).
	
	school.mgc - A script that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.




















## 0x00. - Shell, basics

Introduction to Shell & basics for  linux administration and first set of assignments ALX


### Assignments

[0-current_working_directory](./0-current_working_directory)
```
Write a script that runs a C file through the preprocessor
and save the result into another file.
```
* The C file name will be saved in the variable $CFILE
* The output should be saved in the file c

[1-compiler](./1-compiler)
```
Write a script that compiles a C file but does not link.
```
* The C file name will be saved in the variable $CFILE
* The output file should be named the same as the C file, but with the extension
  .o instead of .c.

[2-assembler](./2-assembler)
```
Write a script that generates the assembly code of a C code and save it in
an output file.
```
* The C file name will be saved in the variable $CFILE
* The output file should be named the same as the C file, but with the
  extension .s instead of .c.

[4-puts.c](./4-puts.c)
```
Write a C program that prints exactly
"Programming is like building a multilingual puzzle, followed by a new line.
```
* Use the function puts
* You are not allowed to use printf
* Your program should end with the value 0

[3-name](./3-name)
```
Write a script that compiles a C file and creates an executable named cisfun.
```
* The C file name will be saved in the variable $CFILE

[5-printf.c](./5-printf.c)
```
Write a C program that prints exactly with proper grammar, but the outcome is
a piece of art,, followed by a new line.
```
* Use the function printf
* You are not allowed to use the function puts
* Your program should return 0
* Your program should compile without warning when using the -Wall gcc option

[6-size.c](./6-size.c)
```
Write a C program that prints the size of various types on the computer it is
compiled and run on.
```
* You should produce the exact same output as in the example
* Warnings are allowed
* Your program should return 0
* You might have to install the package libc6-dev-i386 on your Linux (Vagrant)
  to test the -m32 gcc option

[100-intel](./100-intel)
```
Write a script that generates the assembly code (Intel syntax) of a C code and
save it in an output file.
```
* The C file name will be saved in the variable $CFILE.
* The output file should be named the same as the C file, but with the extension
  .s instead of .c.

[101-quote.c](./101-quote.c)
```
Write a C program that prints exactly and that piece of art is useful"
- Dora Korpar, 2015-10-19, followed by a new line, to the standard error.
```
* You are not allowed to use any functions listed in the NAME section of the man (3) printf or man (3) puts
* Your program should return 1
* Your program should compile without any warnings when using the -Wall gcc option



