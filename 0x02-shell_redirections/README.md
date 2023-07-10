## Shell, I/O Redirections and filters Exercices
---
Exercise 0: Write a script that prints “Hello, World”, followed by a new line to the standard output.

Exercise 1: Write a script that displays a confused smiley "(Ôo)'.

Exercise 2: Display the content of the /etc/passwd file.

Exercise 3: Display the content of /etc/passwd and /etc/hosts

Exercise 4: Display the last 10 lines of /etc/passwd

Exercise 5: Display the first 10 lines of /etc/passwd

Exercise 6: Write a script that displays the third line of the file iacta.

            The file iacta will be in the working directory

            You’re not allowed to use sed

Exercise 7: Write a shell script that creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.

Exercise 8: Write a script that writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.

Exercise 9: Write a script that duplicates the last line of the file iacta

            The file iacta will be in the working directory

Exercise 10: Write a script that deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.

Exercise 11: Write a script that counts the number of directories and sub-directories in the current directory.

            The current and parent directories should not be taken into account            
            Hidden directories should be counted

Exercise 12: Create a script that displays the 10 newest files in the current directory.

            Requirements:

            One file per line
            Sorted from the newest to the oldest


Exercise 13: Create a script that takes a list of words as input and prints only words that appear exactly once.

            Input format: One line, one word
            Output format: One line, one word
            Words should be sorted

Exercise 14: Display lines containing the pattern “root” from the file /etc/passwd

Exercise 15: Display the number of lines that contain the pattern “bin” in the file /etc/passwd

Exercise 16: Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.

Exercise 17: Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.

Exercise 18: Display all lines of the file /etc/ssh/sshd_config starting with a letter.

            Include capital letters as well

Exercise 19: Replace all characters A and c from input to Z and e respectively.

Exercise 20: Create a script that removes all letters c and C from input.

Exercise 21: Write a script that reverse its input.

Exercise 22: Write a script that displays all users and their home directories, sorted by users.

            Based on the the /etc/passwd file

Exercise 23: Write a command that finds all empty files and directories in the current directory and all sub-directories.

            Only the names of the files and directories should be displayed (not the entire path)
            Hidden files should be listed
            One file name per line
            The listing should end with a new line
            You are not allowed to use basename, grep, egrep, fgrep or rgrep

Exercise 24: Write a script that lists all the files with a .gif extension in the current directory and all its sub-directories.

            Hidden files should be listed
            Only regular files (not directories) should be listed
            The names of the files should be displayed without their extensions
            The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be listed before file a, and file Rona should be listed after file jay)
            One file name per line
            The listing should end with a new line
            You are not allowed to use basename, grep, egrep, fgrep or rgrep

Exercise 25: An acrostic is a poem (or other form of writing) in which the first letter (or syllable, or word) of each line (or paragraph, or other recurring feature in the text) spells out a word, message or the alphabet. The word comes from the French acrostiche from post-classical Latin acrostichis). As a form of constrained writing, an acrostic can be used as a mnemonic device to aid memory retrieval. Read more.

            Create a script that decodes acrostics that use the first letter of each line.            
            The ‘decoded’ message has to end with a new line
            You are not allowed to use grep, egrep, fgrep or rgrep

Exercise 26: Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
