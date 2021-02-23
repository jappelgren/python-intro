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

2. Data structures and loops:

   - As described above a list is a lot like a Javascript array, a comma seperated list of values ex. `[1,2,3]` or `['one', 'two', 'three']`
   - A dictionary is similar to a Javascript object, a list of key value pairs ex `{'name': 'Justin', 'age': 39, pet: 'donkey'}`
   - Tuples which are like immutable lists, and don't really exist in Javascript, but do in Typescript. ex. `my_tuple = 'hello', 'hi', 'what's up'`
   - While the items in a tuple are immutable, data types that can be mutated in a tuple can still be mutated. ex. `my_new_tuple = ([1,2,3,], [4,5,6,])`
     In this example there will always be two lists in this tuple but the values in those lists can be mutated.
   - Sets are lists where all values need to be unique.  We can have a set like `['a', 'b', 'c']` but not `['a', 'b', 'c', 'a']` Sets exist in Javascript as well.

3. Functions, conditionals, and loops:

   - A function in Javascript is defined with the `function` keyword.  They are structured like the example below 

   ```
   function functionName(parameter) {
       //things the function does
   }
   ```
   Python functions are declared with the `def` keyword and are structured like:

   ```
    def function_name(paramater):
        #things the function does
   ```

   Conditionals in Javascript look like this:
   ```
    if(x > y) {
        return x
    }
   ```

   Conditionals in Python are similar:

   ```
    if x > y:
        return y
   ```

    - One other note about the difference between Python and Javascript if statements is the 'and', 'or', and 'not' operators are different.

        | Javascript | Python |
        | ---------- | ------ |
        | &&         | and    |
        | <code>||</code>       | or     |
        | !          | not    |


   For loops in Javascript can look like this (there are other methods as well):

   ```
    for(number of arrayOfNumbers) {
        console.log(number)
    }
   ```

   Python's loops look like this:

   ```
    for number in array_of_numbers:
        print(number)
   ```



