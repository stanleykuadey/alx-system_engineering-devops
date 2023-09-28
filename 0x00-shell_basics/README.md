#Description of the files in the 0x00-shell_basics directory
- 0-current_working_directory - This file is an executable file that prints the absolute path name of thecurrent working directory.

- 1-listit - This file is an executable file that displays the contents list of your current directory.

- 2-bring_me_home - This file is an executable file that changes the working directory to the user’s home directory.

- 3-listfiles - This file is an executable file that displays the current directory contents in a long format.

- 4-listmorefiles - An executable file that displays current directory contents, including hidden files (starting with .). Use the long format.

- 5-listfilesdigitonly - An executable file to displays current directory contents in long format, with user and group IDs displayed numerically, And hidden files (starting with .)

- 6-firstdirectory - An executable file that creates a directory named my_first_directory in the /tmp/ directory.

- 7-movethatfile - An executable file that moves the file betty from /tmp/ to /tmp/my_first_directory.

- 8-firstdelete - An executable file that deletes the file betty is in /tmp/my_first_directory

- 9-firstdirdeletion - An executable file that deletes the directory my_first_directory that is in the /tmp directory.

- 10-back - An executable file that changes the working directory to the previous one.

- 11-lists - An executable file that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the /boot directory (in this order), in long format.

- 12-file_type - An executable file that prints the type of the file named iamafile. The file iamafile will be in the /tmp directory when we will run your script.

- 13-symbolic_link - An executable file that creates a symbolic link to /bin/ls, named __ls__

- 14-copy_html - An executable file that creates a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.

- 100-lets_move - An executable file that moves all files beginning with an uppercase letter to the directory /tmp/u.

- 101-clean_emacs - An executable file that deletes all files in the current working directory that end with the character ~.

- 102-tree - An executable file that creates the directories welcome/, welcome/to/ and welcome/to/school in the current directory.

- 103-commas - An executable file that lists all the files and directories of the current directory, separated by commas (,).
<ul> <li>
Directory names should end with a slash (/)
Files and directories starting with a dot (.) should be listed
The listing should be alpha ordered, except for the directories . and .. which should be listed at the very beginning
Only digits and letters are used to sort; Digits should come first
You can assume that all the files we will test with will have at least one letter orone digit
The listing should end with a new line.
</li> </ul>

- school.mgc - A magic file school.mgc that can be used with the command file to detect School data files. School data files always contain the string SCHOOL at offset 0.


