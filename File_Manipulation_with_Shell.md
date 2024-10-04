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
