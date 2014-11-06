# How to use Unix

## What is Unix?

[Unix History](http://en.wikipedia.org/wiki/Unix)

## Logging in

To remote logging in in a remote Unix System a ssh client is used. For Windows the most popular
ssh client is putty.

[Download Putty](http://the.earth.li/~sgtatham/putty/latest/x86/putty.exe).

For Unix based systems (Linux , OSX) a ssh client is, usually, part of the basic installation.

## Editor

[vi tutorial](http://www.unix-manuals.com/tutorials/vi/vi-in-10-1.html)

[vi cheat sheet](http://www.albany.edu/faculty/hy973732/ist535/vi_editor_commands.pdf)

### Exercise 1

	- Create a file called letters with the first 5 letters of the english alphabet, one per line.
	- Create a file named primes with the first 5 primes, one per line.
	
### Exercise 2

	- Rename file letters to letters.1
	- Make a copy of file primes with name primes.1 
	

## Shell Metacharacters and I/O Redirection

[reference](http://www.kirp.chtf.stuba.sk/moodle/mod/book/tool/print/index.php?id=8170#ch3755)


### Excercise 3

	- List all files in /opt/curso corresponding to chapter 1 of the book
	- List all files in /opt/curso from chapter 1 to chapter 9
	- Print (to terminal) the contents of the files belonging to chapters 3,5 and 7.


### Exercise 4

	What are the differences among these commands?
	
	$ ls primes			$ echo primes
	$ ls *					$ echo *
	$ ls '*'				$ echo '*'
	


## Shell variables

[reference](https://caligari.dartmouth.edu/doc/solaris-forte/IPE/dbx/dbx88e.html)

### Exercise 5

	- Write a shell program that receives a list of files and backs them up by copying the file with a 
	a name of the form originalname.YearMonthDay

## Grep

[reference](http://linuxcourse.rutgers.edu/documents/Bash-Beginners-Guide/chap_04.html)

## Sed

[reference](http://linuxcourse.rutgers.edu/documents/Bash-Beginners-Guide/chap_05.html)

	



