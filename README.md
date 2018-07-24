# my-version-of-lsh

LSH is a simple implementation of a shell in C, taken from [here](https://github.com/brenns10/lsh).  

It demonstrates the basics of how a shell works. That is: read, parse, fork, exec, and wait.  

Since the purpose is to create a simple shell, it has the following limitations:  
  
Commands must be on a single line.  
Arguments must be separated by whitespace.  
No quoting arguments or escaping whitespace.  
No piping or redirection.  
Only builtins are: cd, help, exit.  
