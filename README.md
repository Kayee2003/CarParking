# Milktea-Machine-Python
![Fresh Bubble Tea Drink Logo](https://user-images.githubusercontent.com/115056836/206976278-60a711e7-6331-472f-982e-74b8953a4adc.jpg)




#
Simple milktea machine system made using Python with OOP principles

Project Description

Let's write a class that represents a milktea machine. The class should have a method that takes a string as input. Every time the user inputs a string to console, the program invokes this method with one argument: the line that user input to the console. This system simulates pretty accurately how real-world electronic devices work. External components (like buttons on the milktea machine or tapping on the screen) generate events that pass into the single interface of the program.

The class should not use system input at all; it will only handle the input that comes to it via this method and its string arguments.

The first problem that comes to mind: how to write that method in a way that it represents all that milktea machine can do? If the user inputs a single number, how can the method determine what that number is: a variant of milktea chosen by the user or the number of the disposable cups that a special worker added into the milktea machine?

The right solution to this problem is to store the current state of the machine. The milktea machine has several states it can be in. For example, the state could be "choosing an action" or "choosing a type of milktea". Every time the user inputs something and a program passes that line to the method, the program determines how to interpret this line using the information about the current state. After processing this line, the state of the milktea machine can be changed or can stay the same.

How to run 

