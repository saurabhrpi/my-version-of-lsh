# my-version-of-lsh

LSH (or LibStephen Shell) is a simple implementation of a [shell](https://en.wikipedia.org/wiki/Shell_(computing)) in C, taken from [here](https://github.com/brenns10/lsh).  

In the honor of the original author, the name has been kept as is.

It demonstrates the basics of how a shell works. That is: read, parse, fork, exec, and wait. To know more about these system calls, please click [here](https://en.wikipedia.org/wiki/System_call). 

Since the purpose is to create a simple shell, it has the following limitations:  
  
&nbsp;&nbsp;&nbsp;Commands must be on a single line.  
&nbsp;&nbsp;&nbsp;Arguments must be separated by whitespace.  
&nbsp;&nbsp;&nbsp;No quoting arguments or escaping whitespace.  
&nbsp;&nbsp;&nbsp;No piping or redirection.  
&nbsp;&nbsp;&nbsp;Only builtins are: cd, help, exit.  
