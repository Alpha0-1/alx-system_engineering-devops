Shell I/O redirections project
Task-0: echo "Hello World" prints the quoted words as output in a new line.
Task-1: echo "\"(Ôo)'" displays the confused smiley from the executable file.
Task-2: cat /etc/passwd is the executable command that opens the file in question and displays its contents.
Task-3: cat /etc/passwd /etc/hosts displays the contents of both files. The space between the two files directs the computer to display the contents of two separate files.
Task-4: tail /etc/passwd displays the last ten lines of the file "/etc/passwd" because that is the work of the command "tail".
Task-5: head /etc/paswd displays the first 10 lines of the file because that is the function of the command "head"
Task-6: head -3 iacta | tail -1 will display the third line of the file and since head displays the first 10, coupling it up with an index makes the task doable.
Task-7: Majorly involves escaping all the prohibited characters using the slash symbol (\).
Task-8: ls -la > ls_cwd_content writes the result of the las -la command into the file ls_cwd_content file due to the ">" symbol which refers to the standard output(stdout).
Task-9: tail -1 iacta >> iacta command directs the program to duplicate the last line back into the file itself. The ">>" symbol denotes to make two copies of the same argument.
Task-10:find command can be modified further with options to be extra selective at finding files of a specific type. I used the -type option to specify the file based on their name and gave the ".js" characters as test data.
Task-11:The code counts the number of directories and sub-directories using the find command which relies on the type option. The path option is also utilised.
Task-12:ls -t . | head is the command used where the -t flag sorts the newest file by modification time and head specifies to list the first 10.
Task-13: sort | uniq -u creates the stated conditions. Uniq command has been used to omit repeated lines
Task-14: grep/egrep is used to print lines that match patterns
Task-15: grep...the -A flag when paired with 'grep' prints a set number of lines after matching context.
Task-17: The -v option when used with grep selects non-matching lines
Task-18: the [[:alpha:]] argument specifies that only those lines starting with a letter will be displayed
Task-19: The tr command is used to translate or delete characters.
