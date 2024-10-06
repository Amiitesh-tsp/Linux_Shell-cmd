Welcome to this file that includes file manipulation commands of the Linux Terminal.
1. The first command: `touch`
   ```bash
   touch file_name
   ```
   This command lets you create a file of your desired name in the current directory that you are in. So, make sure that you check your current working directory by using `pwd`.
3. The `rm` command:
   ```bash
   rm file_name
   ```
   This command lets you to delete a file from the system if available in the current working directory. \
   Remember, that using this command to delete a file, the file won't be available in the recycle bin or trash as in using GUI to delete the file in Linux or Windows.\
   So be careful with what you use.
   There are several options to use along with this command like
   ```bash
   rm -rf folder_name/directory_name
   ```
   Now, the -rf is force remove. The command is used wihe you have to delete all the contents in the file. A folder with files cannot be deleted with the `rm` command as it will pass an error. \
   But, when `rm -rf file_name` is used it abruptly deletes all the files without passing an error. Remember, that this process cannot be undone. \
   Always, remember that the terminal is a very powerful software and `With Great power comes, Great Responsibility`
4. The `cp` command:
   ```bash
   cp <source> <destination>
   ```
   This command is used to copy the file to the directiry it is in to the directiry we want to copy the file to. \
   This is mainly used to copy files when they are in one of the recursive directories they are in when we install a software and move them to the `.config` directory in case we want to configure them.
5. The `mv` command:
   ```bash
   mv <source> <destination>
   ```
   This command is used to move/cut the file and paste it to the directory it is in to the directory we want to move the file to.
6. The `find` command:
   ```bash
   find <directory> -name <file_name>
   ```
   This command is used when you know that there is a particular file in a directory but you have no idea about the subdirectory it is in. \
   This command comes in handy and situations like these.
7. The `tree` command
   ```bash
   tree <directory_name>
   ```
   This command is used for ease of viewing of the files in a directory in the form of a tree format.\
   The `tree` command has to installed first before using so please installed using the package manager of your Linux distro. \
   I have given the commands on how to install softwares in different distros in the Readme.md file on how to install git. Just change the `git` to 
   `tree` to install the tree terminal command. \
   I'll explain more of these commands in the upcoming directory which makes our terminal experience a bliss.
