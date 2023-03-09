My Readme in Shell Basics : 19 Scripts
--------------------------------------
0-current working directory Script : In this script we use the 'pwd' command to print the current working directory.
1-listit Script : In this we use the 'ls' command to display the contents list of our  current directory.  
2-bring me home Sript : In this script we use the 'cd ~' command to change the working directory to the user’s home directory.
3-listfiles Script : In this script we use the 'ls -l' command to display a detailed list of the files and directories in the current working directory, including their file permissions, owner, size, and modification time.
4-listmorefiles Script : In this script we use the 'ls -la' to display current directory contents, including hidden files starting with (.). 
5-listfilesdigitonly Script : In this script we use -ls -lan' to display current directory contents only with digit.
6-firstdirectory Script : In This script we use the command 'mkdir /tmp/my_first_directory' to create a directory named my_first_directory in the /tmp/ directory.
7-movethatfile Script : In this script we use the command 'mv /tmp/betty /tmp/my_first_directory/' to move the the file betty from /tmp/ to /tmp/my_first_directory.
8-firstdelete Script : In this Script we use the command 'rm /tmp/my_first_directory/betty' to Delete the file betty.
9-firstdirdeletion Script : In this Script we use The command 'rm -r /tmp/my_first_directory' to delete the directory my_first_directory that is in the /tmp directory.
10-back Script : We use yhe command 'cd -' to change the working directory to the previous one.
11-lists Script : We use the command 'ls -la . .. /boot' to list all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.
12-file_type Script : we use the command 'file /tmp/iamafile' to print the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.
13-symbolic_link Script : we use the command 'ln -s /bin/ls __ls__' to create a symbolic link to /bin/ls, named __ls__. The symbolic link should be created in the current working directory.
14-copy_html Script : we use yhe command 'cp -un *.html ../' to copy all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
