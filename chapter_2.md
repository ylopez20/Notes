# Chapter 2

In this chapter we talk about programing: ideas on how to be better at it; structures and basic building blocks; and approaches.

We will look at two methods to express your approach to solving a problem.
1 pseudocode - natural language description, in a language like english
2 flow chart
  * rectangles for steps in the solution
  * diamonds for decisions that need to be made
  * arrows going from one shape to another to direct the flow of the answer.


#### Algorithms 
If the steps you put together will lead to a solution to the problem, then you have an algorithm for it.

How do you know if it leads to a solution?  You have to know what the solution looks like before you can figure out how to get there.
  * Planning a trip: where to, for how long, for what goal?
  
Problem:
  You are part of an organization where the members do not see each other all that often, however some members are willing to meet up.  You know who these pairs are.  How long will it take you to get a message out to all the members about the next meeting, if you want the message to be hand delivered to everyone?
  * Graph
  * time
  * plan
  
  Start this with pseudocode
  
#### Variables
These are named places to hold information in your program.  The informaiton can be of different types: a char, a sequenc of characters (String), an integer, a number with a decimal (Float), a list, a dictionary, a grid of one of these types.

Each variable is like a pad of sticky notes.  You can write on the front sheet, and when you want, you can rip that sheet off, and write something (possibly different) on the newly exposed sheet.  The variable name holds the information on the currently showing sticky note.

#### Operators
You are familar with multiple binary operators (meaingin they work on two items at once).  Multiplication * , Division / , Addition + , Subtraction - .

Does order mater with the operands of an operator?  (the order of the items that are passed to the operator?)

If we are only able to use integers for the above operations, what piece of information are we loosing when we store the answer back to an integer?  The operator to get this info with one step is the % operator.

We have a special operator, it is the assignment operator.  This is the operator that removes the top sheet of the stickynote pad and writes a value on the next sheet.  In Java we will use a single equals sign to indicate this.  In your book they use a left pointing arrow in pseudocode to represent this.  You can probably guess that a variable must be on the left side (the sticky note pad we are going to place a value on for later use), and a value of the appropriate type on the right hand side.

if all letters in the next lines are integers, is the folowing valid, why:
a = b + c
g = h / i
r + s = t * u

