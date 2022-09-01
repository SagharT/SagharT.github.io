
Syntax	        Explanation
#!/bin/bash    	Used to tell the operating system the path it should use to interpret the file.
bash file.sh	  Used to execute the script in the terminal.
./file.sh	      Used to execute the script if it is executable.
#	              Used to make comments in the script.
&&	            logical AND operator.
| |	            logical OR operator.
$#	            Used to expands the number of arguments passed to the script.
$0	            Used to expands to the name of the shell.
$1, $2	        Used as an input parameter that you can add when running script.
exit [0-255]	  Used to exit the script and return the number from 0 to 255.
$	              Used for parameters and variables.
()	            Used for running commands in a subshell.
$()	            Used to save the output of commands.
(())	          Used for arithmetic.
$(())	          Used to retrieve the output of arithmetic expressions.
[]	            Used in filename expansion and string manipulation.
<( )	          It is very similar to a pipe and used for process substitution.
{ }	            Used to expand sequences.
${ }	          Used for string manipulation and variable interpolation.
|	              Used to run multiple commands together.|
>	              Used to send output to a file.
>>	            Used to append output to a file.
;	              Used to separate multiple commands.
<	              Used to get input from a file.
~	              Expands to the home directory.
~/.bashrc	      Read by every non-login shell.
/etc/profile	  Executed automatically at login.
