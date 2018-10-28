# X-Team 91 Project Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

 Elevator Efficiency

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

 Ordered pairs of Person and the Elevator they take, output in a 2D array. The row index indicates the current pair
 and the column index indicates either the Person(0) or the Elevator(1) they take.
 The beginning of the array marks the first Person to take their elevator. 
 Example toString() of Output: pairs[0][0] + "will take elevator" + pairs[0][1]

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

Person object (with floor, time they the pushed the button, etc.). Example input: Person1, Person2, etc.

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.

The text menu user interface provides an opportunity for users to better interact with efficient elevators. If users are
residents, they can click a button take an elevator by entering floor numbers of their destinations, with their records showing
where they start taking an elevator. They can also request accommodations in case of special needs such as moving in large
furniture, goods or several animals with them in the elevators. Moreover, they can schedule an elevator ride ahead of time, given
their early plans of going out. If users are elevator managers, the interface allows them to keep track of cleaning and maintenance
records of the efficient elevators, so that they can determine the appropriate time to clean and maintain the elevators for the next
time. In addition, new residents can register an account and enter their personal information in the program before using
the efficient elevators. All residents are also welcomed to provide feedback on issues associated with the elevators and on how
the effiency of this program interface can be improved to better complement the efficient elevators.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

Elevator, ElevatorManager, Person

Name each interface or class and briefly describe its function or purpose.

Elevator - contains the current floor it's on and it's direction

ElevatorManager - Acts as a way to keep track of all the elevators

Person - contains the floor the person is on, which floor they need to go to, as well as a priority.

## Edit and Submit this file and any figures referenced by this document.

