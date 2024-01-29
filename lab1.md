# LAB 1 REPORT BY CHARLIE NGO

1/11/2024

## Command ***CD***

---
**Question 1:** Share an example of using the command with no arguments.

    {
    [user@sahara ~]$ cd
    [user@sahara ~]$ pwd
    /home
    [user@sahara ~]$ 
    }

1. The working directory was home
2. I got my output because the command I used `cd` is used to change directories. The filesystem was simply `/home` and having no arguments means that nothing will happen.
3. The output was not an error because nothing happened after I ran the command.

**Question 2:** Share an example of using the command with a path to a directory as an argument.

    {
    [user@sahara ~]$ cd lecture1
    [user@sahara ~/lecture1]$ pwd
    /home/lecture1
    [user@sahara ~/lecture1]$ 
    }

1. The working directory is `/home/lecture1`
2. I got this output because I used the command `cd` to change into the lecture1 directory. The filesystem is /home/lecture1.
3. There was no error.

---
**Question 3:** Share an example of using the command with a path to a file as an argument.

    {
    [user@sahara ~]$ cd README
    bash: cd: README: No such file or directory
    [user@sahara ~]$ pwd
    /home
    [user@sahara ~]$     
    }

1. The working directory is /home
2. I got this output because I tried changing the directory to a file. The filesystem remains to be /home
3. I got an error because the command *cd* does not work with files. I would have gotten the error

## Command ***ls***

---
**Question 1:** Share an example of using the command with no arguments.

    {
    [user@sahara ~]$ ls 
    lecture1
    [user@sahara ~]$ pwd
    /home
    [user@sahara ~]$ 
    }

1. The directory is /home.
2. I got this output because the command *"ls"* means that it will list the files in the given current path.
3. There are no errors.

**Question 2:** Share an example of using the command with a path to a directory as an argument.

    {
    [user@sahara ~]$ ls lecture1
    Hello.class  Hello.java  messages  README
    [user@sahara ~]$ pwd
    /home
    [user@sahara ~]$ 
    }

1. The directory is /home.
2. Using the command *ls* shows all the contents that is contained in the lecture1 directory.
3. There are no errors.

**Question 3:** Share an example of using the command with a path to a file as an argument.

    {
    [user@sahara ~]$ cd lecture1
    [user@sahara ~/lecture1]$ ls README
    README
    [user@sahara ~/lecture1]$ pwd
    /home/lecture1
    [user@sahara ~/lecture1]$ 
    }

1. The directory is lecture1.
2. Using the command *ls* in this situation returns the name of the file. I believe why this happened was because the README path only contains the README file itself.
3. There are no errors.

---

## COMMAND ***cat***

---
**Question 1:** Share an example of using the command with no arguments.

    {
    [user@sahara ~]$ pwd
    /home
    [user@sahara ~]$ cat
    }

1. The working directory is /home.
2. The command appears to do nothing at first, but in the terminal I am unable to write more commands.
3. There are no errors.

**Question 2:** Share an example of using the command with a path to a directory as an argument.

    {
    [user@sahara ~]$ cd lecture1
    [user@sahara ~/lecture1]$ cat messages
    cat: messages Is a directory
    [user@sahara ~/lecture1]$ pwd
    /home/lecture1
    }

1. The working directory is /home/lecture1.
2. The command `cat` appears to just state that `messages` is a directory. 
3. There was no error but I believe `cat` is not meant for directories, since that was the result I got.

**Question 3:** Share an example of using the command with a path to a file as an argument.

    {
    [user@sahara ~/lecture1]$ cat README
    To use this program:
    javac Hello.java
    java Hello messages/en-us.txt
    [user@sahara ~/lecture1]$ pwd
    /home/lecture1
    [user@sahara ~/lecture1]$ 
    }

1. The working directory is lecture1.
2. The command seems to have printed the contents of the file *README*. The README file had some code which printed onto the terminal.
3. There are no errors.