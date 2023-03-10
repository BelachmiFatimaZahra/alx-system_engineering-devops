Readme file permissions

0-iam_betty Script : we use the command 'su betty' to switch the current user to the user betty.
1-who_am_i Script : we use the command 'whoami' to print the effective username of the current user. 
2-groups Script : we use the command 'groups' to print all the groups the current user is part of.
3-new_owner Script : we use the command 'chown betty hello' to change the owner of the file hello to the user betty.
4-empty Script : we use the command 'touch hello' to create an empty file called hello.
5-execute Script : we use the command 'chmod u+x hello' to add execute permission to the owner of the file hello.
6-multiple_permissions Script : we use the command 'chmod ug+x,o+r hello' to add execute permission to the owner and the group owner, and read permission to other users, to the file hello.
7-everybody Script : we use the command 'chmod ugo+x hello' to add execution permission to the owner, the group owner and the other users, to the file hello.
8-James_Bond Sript : we use the command 'chmod 007 hello' to set the permission to the file hello as follows: Owner: no permission at all, Group: no permission at all, Other users: all the permissions.
9-John_Doe Script : we use th command 'chmod 753 hello' to set the mode of the file hello to this: -rwxr-x-wx 1 julien julien 23 Sep 20 14:25 hello.
10-mirror_permissions Script : we use the command 'chmod --reference=olleh hello' to set the mode of the file hello the same as olleh’s mode.
11-directories_permissions Script : we use the command 'chmod -R ugo+X *' to add execute permission to all subdirectories of the current directory for the owner, the group owner and all other users.
12-directory_permissions Script : we use the command 'mkdir -m 751 my_dir' to create a directory called my_dir with permissions 751 in the working directory.
13-change_group Script : we use the command 'chgrp school hello' to change the group owner to school for the file hello.
100-change_owner_and_group Script : we use the command 'chown vincent:staff *' to change the owner to vincent and the group owner to staff for all the files and directories in the working directory.
101-symbolic_link_permissions : we use the command 'chown -h vincent:staff _hello' to change the owner and the group owner of _hello to vincent and staff respectively.
102-if_only Script : we use the command 'chown --from=guillaume betty hello' to change the owner of the file hello to betty only if it is owned by the user guillaume.103-Star_Wars Script : we use the command 'telnet towel.blinkenlights.nl' to connect to the server "towel.blinkenlights.nl" that hosting a special version of Star Wars IV, which can be played in ASCII art in the terminal.

About the first line of the script "#!/bin/bash" is specifies the shell interpreter that should be used to execute the script.The shebang specifies that the Bash shell should be used to interpret the script.
