## Milktea-Machine-Python
![Fresh Bubble Tea Drink Logo](https://user-images.githubusercontent.com/115056836/206976278-60a711e7-6331-472f-982e-74b8953a4adc.jpg)




#
Simple milktea machine system made using Python with OOP principles

## Project Description

Let's write a class that represents a milktea machine. The class should have a method that takes a string as input. Every time the user inputs a string to console, the program invokes this method with one argument: the line that user input to the console. This system simulates pretty accurately how real-world electronic devices work. External components (like buttons on the milktea machine or tapping on the screen) generate events that pass into the single interface of the program.

The class should not use system input at all; it will only handle the input that comes to it via this method and its string arguments.

The first problem that comes to mind: how to write that method in a way that it represents all that milktea machine can do? If the user inputs a single number, how can the method determine what that number is: a variant of milktea chosen by the user or the number of the disposable cups that a special worker added into the milktea machine?

The right solution to this problem is to store the current state of the machine. The milktea machine has several states it can be in. For example, the state could be "choosing an action" or "choosing a type of milktea". Every time the user inputs something and a program passes that line to the method, the program determines how to interpret this line using the information about the current state. 


## Concepts Used
Encapsulation - We put in place encapsulation by bundling data and methods within a single unit by creating classes.


## Self Assesment

The group evaluated the system using the provided grading rubric, which resulted in the following:

| Metric             	| 4 | 3 | 2 | 1 |
|--------------------	|---|---|---|---|
| Code Reusability   	|   |✅|   |   |
| Maintainability    	|✅|   |   |   |
| Scalability        	|✅|   |   |   |
| Execution          	|✅|   |   |   |
| Originality        	|  | ✅|   |   |
| Overall Impression 	|✅|   |   |   |

## Contributors

   **IT2102**

| Names            	   | Link	                                                |
|--------------------------| ---------------------------------------------------------- |
| Espina,Frankie Nicole    |  [@Frankie-Nicole](https://github.com/FrankieNicoleEspina) |
| Macaraig,Robelyn         |  [@Robelyn](https://github.com/RobelynMacaraig)            |  
| Marquez,Paula Kristha    |  [@Paula-Kristha](https://github.com/PaulaKristhaMarquez)  | 
        
