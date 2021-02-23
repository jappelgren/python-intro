# Exploring New Programming Languages

## Install

One method for installing Python is to use Homebrew (if you're on a Mac). All Macs come with Python 2 preinstalled. To install Python 3 first make sure you have Homebrew installed on your machine. Typing `brew -v` will give you the version of Homebrew installed on your machine if it is installed. If it isn't type `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"` in a terminal window.

Once Homebrew is ready to go all you need to do to install Python 3 is type `brew install python`. After the installation is complete typing `python3 -V` should display the version of Python you just installed.

## Hello World

To get a simple 'Hello World' application up and running with python. Make a new directory, in that directory create a file called `hello_world.py`. Open that folder up in the text editor of your choice. If using VSCode you will be prompted to install the VS Code Python tools, do so. In you file type the following:

`print('Hello World')`

Save the file and then in the terminal, make sure you are in your working directory, type `python3 hello_world.py`. Your terminal should then print out the words 'Hello World', just as you told it to.

## Basic syntax

If you're coming to Python from Javascript you will notice that it's similar and very different. No more curly braces and semi-colons, tabs are important. Writing a function to to print out all of the numbers in an array might look like this:

```
function counter(numArray) {
    for(number of numArray) {
        console.log(number);
    };
};

counter([1,2,3,4,5,6,7,8,9,10]);
```

Where as in Python you would write a function with the same purpose thusly:

```
def counter(number_array):
    for number in number_array:
        print(number)

counter([1,2,3,4,5,6,7,8,9,10])
```

Notice how there isn't a curly brace to be seen. Python instead uses tabs to indicate when you are in or out of a function. The tabs in Javascript are there becuase it makes the code more readable. The tabs in Python are necessary for the code to function.

## Programming

Here is a list of things you should focus on:

1. Variables & types :

   - Variables are defined by typing out what the variable will be names and setting it equal to a value. There is no defining keyword like `let`, `const` or `var`. Defining a variable in Python looks like this `x = 5`. The variable x now exists and is equal to the number 5
   - Logging to your console is `print(x)`. This will print 5 to our console.
   - Types are a little different than Javascript as well:

    | Javascript type | Python Type |
    | --------------- | ----------- |
    | string          | strng       |
    | number          | int         |
    | number(decimal) | float       |
    | boolean         | bool        |
    | array           | list        |
    | object          | dictionary  |

- There are also tuples which are like immutable lists, and don't really exist in Javascript, but do in Typescript.

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
