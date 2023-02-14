SHELL, I/O REDIRECTIONS AND FILTERS
Task-0: alias ls="rm *"; the alias  command makes it possible to  launch any command by entering a pre-set string
Task-1: echo is used with a special character which causes expansion
Task-2:PATH=$PATH :PATH is the name of the environment variable that we want to modify. It holds a list of directories that the shell searches through when you run a command.
$PATH expands to the current value of the PATH variable. This is important because we want to add a new directory to the existing list, rather than overwriting the entire variable.
:/action is the new directory that we want to add to the PATH. The : character separates directory paths in the PATH variable, so we append :/action to add the /action directory to the end of the list.
Task-3:echo $PATH prints the value of the PATH variable to the console.
tr ":" "\n" replaces each colon : in the output with a newline character \n, effectively splitting the output into multiple lines, with each line representing a different directory in the PATH variable.
wc -l counts the number of lines in the output. Since each line represents a directory in the PATH variable, the number of lines is the same as the number of directories in the PATH.
Task-4:printenv;The printenv command is used to print a list of all the environment variables that are currently set in the shell
Task-5:set |less;The set command is used to display all the environment variables, shell functions, and aliases that are currently defined in the shell. When you run the set command, it will output a long list of all these items.

The pipe is used to redirect the output of one command to another command. In this case, we're piping the output of set to the less command. The less command allows you to view large amounts of text one page at a time.
Task-6:BEST="School";creates a shell variable named BEST and assigns it the value "School". 
Task-7:export BEST="School";creates a shell variable named BEST and assigns it the value "School".
Task-8:The command echo $((TRUEKNOWLEDGE+=128)) is used to increment the value of the TRUEKNOWLEDGE variable by 128, and then print the new value to the console using the echo command.
Task-9:The command echo $((POWER/DIVIDE)) is used to perform integer division of the POWER variable by the DIVIDE variable and then print the result to the console using the echo command.
Task-10:The command echo $((BREATH**LOVE)) is used to perform exponentiation of the BREATH variable by the LOVE variable and then print the result to the console using the echo command
Task-11:The command echo $((2#$BINARY)) is used to convert a binary number stored in the BINARY variable to its decimal equivalent, and then print the result to the console using the echo command.
Task-12:The command echo {a..z} {a..z} | tr ' ' '\n' | grep -v "oo" generates a list of all possible two-letter combinations of the letters "a" through "z", prints each combination on a separate line, and then filters out any lines that contain the string "oo".
Task-13:The command printf "%0.2f\n" $NUM formats and prints the value of the variable $NUM as a floating-point number with two digits after the decimal point.
Task-14:The command printf "%x\n" $DECIMAL formats and prints the value of the variable $DECIMAL as a hexadecimal number
