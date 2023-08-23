# Command Line Practice

## Points to Ponder

*Look through these now and then use them to test yourself after doing the assignment*

* What is the command line?

* How do you open it on your computer?

* How can you navigate into a particular file directory?
    - Where will `cd .` navigate you to?
    - Where will `cd ..` navigate you to?
    - Where will `cd ~` navigate you to?
    - Where will `cd /` navigate you to?


* How can you display the name of the directory you are currently in?

* How can you display the contents of the directory you are currently in?

* How can you create a new directory?

* How can you create a new file?

* How can you destroy a directory or file?

* How can you rename a directory or file?

## Assignment:

1. Complete the first 2 sections of this interactive course to get a great handle on navigating and manipulating directories and files - [Terminal Tutor](https://www.terminaltutor.com/)

3. Complete the below exercise locally on your own computer.

## Exercise:

In this exercise you will practice creating files and directories and deleting them.

1. Navigate to your home directory (`~`)
1. Create a new directory in your home directory and  name it `test`
2. Navigate into the `test` directory
3. Create a new file called `test.txt` using the `touch` command
4. Open this file with VSCode (from the command line using `code test.txt`) give it some content, and then save
5. From within the cli, view the contents of the file you just created (`head`, `tail`, `less`)
4. Navigate one level up from the `test` directory to it's parent directory
5. Delete the `test` directory (it contains files now, so you might need to add an option to `rm`!)
