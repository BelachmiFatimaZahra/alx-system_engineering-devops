# 0x02. Shell, I/O Redirections and filters

## Scripts

* 0-hello_world Script : we use the command 'echo "Hello, World"' to print a “Hello, World”
* 1-confused_smiley Script : we use the command 'echo "\"(Ôo)'"' to displays a confused smiley "(Ôo)'
* 2-hellofile Script : we use the command 'cat /etc/passwd' to Display the content of the /etc/passwd file.
* 3-twofiles Script : we use the command 'cat /etc/passwd /etc/hosts' to display  the content of /etc/passwd and /etc/hosts
* 4-lastlines Script : we use the command 'tail -n 10 /etc/passwd' to display  the last 10 lines of /etc/passwd
* 5-firstlines Script : we use the command 'head -n 10 /etc/passwd' to display the first 10 lines of /etc/passwd
* 6-third_line Script : we use the command 'head -n 3 iacta | tail -n 1' to display the third line of the file iacta.
* 7-file Script : we use the command 'echo "Best School" > \\\*\\\\\'\"Best\ School\"\\\'\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)' to create a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
* 8-cwd_state Script : we use the command 'ls -la > ls_cwd_content' to writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
* 9-duplicate_last_line Script : we use the command 'tail -n 1 < iacta  >> iacta' to duplicate the last line of the file iacta
* 10-no_more_js Script : we use the command 'find . -type f -name "\*.js" -delete' to delete all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
* 11-directories Script : we use the command 'find . -mindepth 1 -type d | grep -v '/\.' | wc -l' to count the number of directories and sub-directories in the current directory.
* 12-newest_files Script : we use the command 'ls -tp | grep -v / | head -10' to display the 10 newest files in the current directory.
* 13-unique Script : we use the command 'sort | uniq -u' to print only words that appear exactly once after taking a list of words as input.
* 14-findthatword Script : we use the command 'grep "root" /etc/passwd' to display lines containing the pattern “root” from the file /etc/passwd
* 15-countthatword Script : we use the command 'grep -c "bin" /etc/passwd' to display the number of lines that contain the pattern “bin” in the file /etc/passwd 
