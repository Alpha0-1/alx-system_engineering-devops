TASK 0.Su creates a superuser or switches user
TASK 1.Whoami states names of user
TASK 2.Groups displays the groups the user is in
TASK 3.Chown changes ownership of file
TASK 4.Touch creates an empty file
TASK 5. Chmod u+x modifies access rights and gives owner permission to exclusively execute the file
TASK 6. Chmod u+x,g+x,o+r hello adds execute permission to the owner and the group owner, and read permission to other users, to the file hello
TASK 7. Chmod ugo+x hello adds execution permission to the owner, the group owner and the other users, to the file hello
TASK 8. Chmod 007 hello sets the permission to the file hello as follows:Owner: no permission at all, Group: no permission at all, Other users: all the permissions. 7 offers read, write and execute permissions while 0 offers none
TASK 9. Chmod 753 hello sets the mode of the file hello to (-rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello)
TASK 10. Chmod --reference=olleh hello mirrors the hello file in the working directory
TASK 11. Chmod -R +111 */ functions to execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
TASK 12. Mkdir -m 751 my_dir is used to create a directory called my_dir with permissions 751 in the working directory.
TASK 13.chgrp school hello changes the group owner to school for the file hello
TASK14.chown is used to change ownership.
TASK15.chown -h vincent:staff _hello creates a symbolic link denoted as "_hello"
TASK16. chown --from=guillaume betty hello changes the owner of the file hello to betty only if it is owned by the user guillaume because it is a conditional argument.
TASK17. telnet towel.blinkenlights.nl directly links to StarWars IV episode being played in the terminal 
