# Navigating Folders In Terminal

This is a quick overview of how to navigate and find out where you are using the Terminal, which is the same language (bash) used with git...so it's helpful to get a quick overview. You'll need to use RStudio > Tools > Terminal > New Terminal, and then enter these commands in the Terminal, **not** in the R Console panel. Look for a `$` at the start of the line, not a `>`.

## `pwd` and `cd`

The two core commands for navigating folders are `cd` and `pwd`. 

 - **`pwd`** It's best to always check where you are starting from using `pwd`, which means "present working directory".
    - Should get something like this if you type in `pwd` in the Terminal inside this project: `/Users/myname/Desktop/hippogriff/r-davis_01-starting-r`
    - This is like the "home" or "root" directory this Project lives in, so everything is relative to this location when we open this RStudio project.
 
 - **`cd`** means "change directory" and expects a place you want to go after you type `cd`.
    - Let's try navigating to the data folder: *`cd data`*.
    - After you run that command, check where you are with `pwd`
    - To go **UP** a folder, you can use a `..`, so to go back up to the root directory: `cd ..`
    - To go down through multiple folders, add a forward slash and the name of the folder...everything is case sensitive and must be spelled exactly: `cd data/silly_lists`.
    - How do we get back up two levels to the root directory?
    
A third command which is useful in many ways, is `ls`. This "lists" things in a given directory (or directories themselves). It's very powerful, but for now let's just use it to see what exists in a given folder.
 - `ls` in the root directory
 - Try `ls -a` which means list **all** files in a location. What do you see?