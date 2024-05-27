# Whitespace addition tool
This program takes numbers as input from the user and adds them up. The numbers should be integers (the implementation for decimal numbers does not exist for Whitespace) and once all the numbers are punched in, enter -1. Each number should be followed by the enter key.

## What is whitespace?
Whitespace is an esoteric programming language, or esolang, that uses white space characters to code (tabs and spaces). While most programming languages ignore or give little significance to the whitespace characters, Whitespace will ignore all other characters. This gives the ability to the user to write a program in one language (let’s say C++) and within it the whitespaces would constitute a program that the Whitespace compiler would pick up (since the Whitespace compiler ignores all other characters except whitespaces).

Whitespace utilizes stacks and heaps as data containers. The way it operates is that it gets the number and pushes it in the stack. The next incoming number will be inserted and take the previous’ numbers place in the stack, while the first number is pushed in the heap. This process will add all the numbers in the heap (with every number that is inserted) and when the program receives -1 it will pop the top element which is the sum of all the previous numbers in the heap.

Each line in Whitespace will start with an Instruction Modification Parameter (IMP) and then a command. For example:
[Space][Space] will push a number into a stack (with the first space being the IMP and the second space will be a number).
Another example will be:
[Tab][Tab][Space] which stores something in a heap. All numbers and characters are represented in binary using 0 and 1 with 0 being a space and 1 being a tab.

There are a couple of reasons on why someone would use this language. First and foremost is to learn about how heaps and stacks are operated. The second being that it is fun!
 
 ## Installation instructions
 You can install the Whitespace compiler using the pip command as there is an interpreter written in Python for it. Just type:
 ```
 $ pip install whitespace
 ```
 
 To run the program, simply navigate to the directory you have the file saved to and type:
 ```
 $ whitespace SumItUp.ws
 ```
 
 ## License
 This project is licensed under the MIT license.
 