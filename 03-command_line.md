# Learn command line

Please follow and complete the free online [Command Line Crash Course
tutorial](https://web.archive.org/web/20160708171659/http://cli.learncodethehardway.org/book/) or [Codecademy's Learn the Command Line](https://www.codecademy.com/learn/learn-the-command-line). These are helpful tutorials. Each "chapter" focuses on a command. Type the commands you see in the _Do This_ section, and read the _You Learned This_ section. Move on to the next chapter. You should be able to go through these in a couple of hours.

---

### Q1.  Cheat Sheet of Commands  

Here's a list of items with which you should be familiar:  
* show current working directory path
* creating a directory
* deleting a directory
* creating a file using `touch` command
* deleting a file
* renaming a file
* listing hidden files
* copying a file from one directory to another

Make a cheat sheet for yourself: a list of at least **ten** commands and what they do.  (Use the 8 items above and add a couple of your own.)  

> > Item | Command
> > ------- | ----------
> > show current working directory path | pwd
> > creating a directory | mkdir
> > deleting a directory | rmdir
> > creating a file using touch command | touch
> > deleting a file | rm
> > renaming a file | rv
> > listing hidden files | ls -a
> > copying a file from one directory to another | cp
> > output the content of the file | cat
> > clear the command line window | clear

---

### Q2.  List Files in Unix   

What do the following commands do:  
`ls`  
`ls -a`  
`ls -l`  
`ls -lh`  
`ls -lah`  
`ls -t`  
`ls -Glp`  

> > Command | Description
> > ------- | ----------
> > ls | list directory contents
> > ls -a | list directory contents, including hidden files
> > ls -l | list detailed directory contents
> > ls -lh | list detailed directory contents, where sizes are in human readable format
> > ls -lah | list detailed directory contents, including hidden files, where sizes are in human readable format
> > ls -t | List files sorted by date and time
> > ls -Glp | List files in long format and directories as /

---

### Q3.  More List Files in Unix  

Explore these other [ls options](http://www.techonthenet.com/unix/basic/ls.php) and pick 5 of your favorites:

> > `ls -la` `ls -p` `ls -x` `ls -r` `ls -a`

---

### Q4.  Xargs   

What does `xargs` do? Give an example of how to use it.

> > xargs is a command used to build and execute commands from standard input. It converts input from standard input into arguments to a command. The most common usage of xargs is to use it with the find command. This uses find to search for files or directories and then uses xargs to operate on the results. Typical examples of this are removing files, changing the ownership of files or moving files.

 

