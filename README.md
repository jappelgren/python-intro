# Exploring New Programming Languages

## Install

One method for installing Python is to use Homebrew (if you're on a Mac).  All Macs come with Python 2 preinstalled.  To install Python 3 first make sure you have Homebrew installed on your machine. Typing `brew -v` will give you the version of Homebrew installed on your machine if it is installed.  If it isn't type `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` in a terminal window.

Once Homebrew is ready to go all you need to do to install Python 3 is type `brew install python`.  After the installation is complete typing `python3 -V` should display the version of Python you just installed.


## Hello World

To get a simple 'Hello World' application up and running with python. Make a new directory, in that directory create a file called `hello_world.py`.  Open that folder up in the text editor of your choice.  If using VSCode you will be prompted to install the VS Code Python tools, do so.  In you file type the following:

`print('Hello World')`

Save the file and then in the terminal, make sure you are in your working directory, type `python3 hello_world.py`.  Your terminal should then print out the words 'Hello World', just as you told it to.


## Basic syntax

If you're coming to Python from Javascript you will notice that it's similar and very different.  No more curly braces and semi-colons, tabs are important.  Writing a function to to print out all of the numbers in an array might look like this:

`function counter(numArray) {
    for(number of numArray) {
        console.log(number)
    }
}

counter([1,2,3,4,5,6,7,8,9,10])`




## Programming

Here is a list of things you should focus on: 

1. Variables & types :
    - how to make a variable (do variables have types?)
    - write to the console

2. Data structures and loops:
    - arrays or lists of things
    - objects

3. Functions and conditionals:
    - write a function that takes arguments and returns a value (sum 2 numbers)
    - operators - math, logical (and/or/not)

4. Pull things all together in one problem. Solve a whiteboard problem! (FizzBuzz, reverse a string or array, LeapYear, etc.) You can find our old whiteboard challenges in the syllabus repository!

## Put it together -

After you are a bit familiar with the basic syntax, solve one of our "whiteboard" problems (FizzBuzz, reverse a string or array, LeapYear, etc.) in your new language! Do this on your computer, not on a whiteboard!



### GitHub Repo

Setup a new GitHub repo with a README file that has instruction for installing the new language tools & resources your group found useful. Then add some notes with an example of each of the items listed above. Think of this Readme as a way to highlight your new language learning journey. This is a great way to show potential employers that you can tackle a challenge and learn a new language quickly! 

When you are done, complete the assignment on the portal with your GitHub repo link. 
