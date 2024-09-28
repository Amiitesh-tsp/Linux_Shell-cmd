First, When you start operating into a linux system, there is a very popular word so called Terminal. Now, There are different ways of referring to the terminal.
They call it terminal, prompt or the command prompt, the bash shell, the linux shell, etc... **"The more you use it, the more you get used to it."**

How to open it:
So there are different ways of opening the shell.\
    1. Press windows key, and then search command prompt/terminal/shell to open it.\
    2. Or use the shortcut which I use everyday: Ctrl+Alt+T

After doing so you'll have the shell opened in your computer. To enlarge the shell use the shortcut: Ctrl+Shift+"+"
Now, getting into the commands used in the shell.
An important point to remember that the shell is strictly typed meaning it is case-sensitive (Just like Python).

Now, as you get to learn different types of commands make sure to execute and test them so that it'll get used to your practical knowledge.
1) The first command:
   
       pwd

This will return the directory you are working in. For example, (Documents, Downloads, Music, etc...)
Now, it stands for print working directory. Make sure to keep checking the directory since you might make the changes in the wrong directory which is going to lead you into a hectic problem.

Now that we have seen how to see the current directory, let's see how to change directories within the shell.\
2. Change directory:

       cd

   This command has to be used with 0 or 1 argument. 

       cd <directory_name>

   Now, type in and see "cd Downloads" and then use "pwd" to check the current directory.
    To return to the same default directory, that is, home type in: "cd"

   Now,\
   To take you to a unified-file system. Usually, Windows contains drives split up as "C:" whereas Linux does not split up the disks instead they have a unified-file system which can be accessed by " cd / ".

    cd /

   This command will take you to the previous directory visited in the same path.

    cd -
   Example:
         Suppose we enter a file in pictures directory => /home/username/Pictures/images
         Using cd - will take us to "Pictures Directory", that is, the directory before images.
    
Now Creating Folders and Files in a shell.

To create a directory in Linux:

    mkdir <directory_name>

    In mkdir we can create as many as directories as we want which means that we can have n number of arguments seperated by space for this command.

   If we want to create folder names seperated by space we have to name them within quotes.
    For Example:

    mkdir "Folder 1"

   But usually nobody ever use space seperated names for files instead they use underscore(_).
    A shell user can be identified by the way they name their files.

    mkdir dir1 dir2 dir3: This will create three directories with the respective names.
    mkdir -p dir4/dir5/dir6: Now, "-p" here is called as options there are many different options but for now just keep in mind that these are called options. Remember "The more you use, the more you'll get used to it".
                            This command will create dir5 inside dir4 and dir6 inside dir5.

To view the files and directories in the shell:

    ls

    The ls command returns all the directories and files that are present in the system.
    Try changing the directory using "cd" and try using "ls" will return the files that are present inside the Direcotory that we are currently working in.

Now, remember the
print("Hello World") from python
Similarly, in shell we have the command echo

    echo "<text>"

    echo "Hello World": This command prints Hello World as the output
To add this text into a .txt file we use the ">" operator

    echo "Switch to Linux" > t1.txt : This command will create a new file and add the text into the created new file.

How to read a created file,

    cat <file_name>

    This will help us in reading the file that exist in your computer. Now, to read all the files which have the same names.
    In this case, Let's have three file names, t1.txt, t2.txt, t3.txt

    cat t*
    cat t?

    Both of the above commands read all the files t1, t2, t3 in the next consecutive lines. Try and check it out for yourself.

Now, what if you have to combine all the text files and add them into a combined file

    cat t* > combined.txt

    The above command creates "combined.txt" file and adds all the content of three files into one single folder. (Saves a lot of time isn't it?) Much simpler than Windows.

Now, that we have seen how to create files, folders and directories in the next file we'll see how we move and manipulate files.