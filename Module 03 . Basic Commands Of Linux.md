

# Linux Commands Cheat Sheet



## Directory

| Command | Function|
| --- | -- |
| cd | navigate through files and directories |
| cd - | move to your previous directory |
| cd .. | move one directory up |
| pwd | show the directory currently working in |
| rmdir | delete a directory and its contents |
| mkdir [directory] | create a new directory |
| scp [file_name.txt] [server/tmp] | securely copy a specific file to a server directory |
| rsync -a [/your/directory] [/backup/] | synchronize the contents of a specific directory with a backup directory |


## File Commands

| Command | Function |
| ------- | -------- |
| ls | list files in a directory |
| ls -a | list all hidden files |
| ls -R | list all files in the sub-directories | 
| ls -al | list all files and directories with detailed information like permissions, size, owner, etc |
| cat | list the contents of a file on standard output |
| cat > filename | creates a new file |
| cat filename1 filename2>filename3 | joins two files (1 and 2) and stores the output in a new file (3) |
| cat filename \| tr a-z A-Z >output.txt | convert a file to upper or lower case |
| diff | compare the contents of two files line by line |
| tar | archive multiple files into a common Linux file format |
| tar xf [compressed_file. tar] | extract archived file |
| tar czf [compressed_file.tar.gz | create a gzip-compressed tar file |
| tar cf [compressed_file. tar] [file_name] | create an archived file from a file |
| gzip [file_name] | compress a file with the .gz extension |
| chmod | change the read, write, and execute permissions of files and directories |
| chown | change or transfer file ownership |
| rm [file_name] | remove a file |
| rm -r [directory_name] | remove a directory recursively |
| rm -rf [directory_name] | remove a directory recursively without requiring confirmation |
| wc | print the number of words, lines, and bytes in a file |
| cp | copy files from the current directory to a different directory |
| cp [file_name1] [file_name2] | copy the contents of the first file to the second file |
| cp -r [directory_name1] [directory_name2] | recursively copy the contents of the first directory into the second directory |
| mv | to move or rename files |
| mv [file_name1] [file_name2] | rename file_name1 to file_name2 |
| wget | download files from the internet |
| ln -s /path/to/[file_name] [link_name] | create a symbolic link to a file |
| touch [file_name] | create a new file |
| more [file_name] | show the contents of a file |
| head [file_name] | show the first 10 lines of a file |
| tail [file_name] | show the last 10 lines of a file | 
| gpg -c [file_name] | encrypt a file |
| gpg [file_name.gpg] | decrypt a file |
| sudo | perform tasks that need administrative or root permissions |
| locate | to search for a file or directory |
| find | to locate files within a directory |
| jobs | display current jobs |
| kill | terminate an unresponsive program |
| history | review the commands you entered before |
| uname | print information about your Linux system |
| man | show manual instructions of Linux commands |
| zip | compress files into a zip archive |
| unzip | extract zipped files from a zip archive |
| top | monitor system resource usage |
| ps | show a snapshot of active processes |
| echo | move data into a file |
| hostname | know the name of your host/network |
| ping |check connectivity to a server |


## Network

|  Command | Function |
| -------- | -------- |
| ip addr show | show IP addresses and network interfaces |
| ifconfig | show IP addresses of all network interfaces |
| netstat -pnltu | show active ports |
| netstat -nutlp |show more information about a domain |
| whois [domain] | show more information about a domain | 
| dig [domain] | show DNS information about a domain | 
| host [domain] | do an IP lookup for a domain Network |
 

## Disk Usage 

| Command | Function |
| ------- | -------- |
| df | get a report on the system’s disk space usage |
| fdisk -l | show disk partitions, sizes, and types|
| du | check the disk space usage of a file or directory |
| du -ah | show disk usage for all files and directory |
| du -sh | show disk usage of the current directory |
| findmnt | show target mount point for all filesystems |


## System 

| Command | Function |
| ------- | -------- |
| uname -r | show system information | 
| last reboot | show system reboot history |
| timedatectl | query and change the system clock |
| date | show current time and date |
| hostname -i | show the IP address of the system |
| uptime | show how long the system has been running, including load average |


## User

| Commands | Function |
| -------- | -------- |
| id | show details of the user |
| passwd | add a password to a user’s account |
| useradd | create a new user |
| last | show last logins |
| userdel [user_name] | remove a user |


## Keyboard Shortcuts

| Commands | Function |
| -------- | -------- |
| Ctrl + E | move to the end of the line |
| Ctrl + A | move to the beginning of the line |
| Ctrl + O | run the previously recalled command |
| Ctrl + Y | paste from clipboard |
| Ctrl + S | freeze the terminal |
| Ctrl + Q | unfreeze the terminal |
| Ctrl + Z | pause the command |
| Ctrl + C | stop and terminate the current command |
| Ctrl + W | cut one word before the cursor and add it to the clipboard |
| Ctrl + U | cut part of the line before the cursor and add it to the clipboard |
| Ctrl + K | cut part of the line after the cursor and add it to the clipboard |
| TAB | autofill typing |
| Ctrl + R | recall the last command that matches the provided characters |
| Ctrl + G | exit command history without running a command |
| !! | repeat the last command |
| exit | log out of the current session |


