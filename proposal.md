# X-Team 24 Project Proposal

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

A parking structure that is able to find the most efficient spot to place the car and keep track of how long it is there.
This program would take inputs that define the type of car and output where it should go.

## Questions to answer for Exercise #2

1. Name: EZ Park


2. Output:
     * The Best spot to park in the structure: the number of the spot
     * The fee for parking: a double for money (based on the amount of time).


3. Input: 
     * Size of car: selection of moped/bike, smart/compact car, normal size car, large truck
     * Type: selection of gas or electric
     * String of the liscense plate to identiy the vehicle


4. User Interface: 
     * 2 Options: Check in or Check out
     * Option 1:
        * Drop down of type: Gas, Electric, Wheelchair accessible
        * Drop down of size: moped, smart, normal, truck
        * Textbox for license plate
     * Option 2:
        * Textbox for license plate


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
     * Classes: Garage, Car
     * Methods: 
         * calcTime (calculate the time in garage) 
         * money(the fee for parking) 
         * howManySpotsAvailable(How many spots are available) 
         * whichType(which type of spots are available)
         * determineBestSpot(Find the best spot for the vehicle)
         
     * Getters and Setters are given.


6. Name each interface or class and briefly describe its function or purpose.
     * Car Class: This class stores the information of the car such as the license plate number and type of car.
     * Garage Class: This class stores the information of the garage structure such as how many of each type of spot, how many spots are left, and time stayed in garage.


