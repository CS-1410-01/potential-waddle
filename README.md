# Assignment 4: A Living World

This assignment will focus on your ability to put all four pillars of Object Orientation to use as well as leave you, hopefully, with a platform to use for simulating all sorts of neat projects in the future.

First off, I wanted to say that for this assignment I've decided to have two sets of requirements. One set that applies to those of you who choose to continue on with the Evolution Models concept that we have explored in the previous assignment. And another that allows you to meet similar requirements but in whatever sort of simulation you wish to build. Whether that be in a game, a Point-Of-Sale system or whatever else you could imagine.


For the first option, or the Evolution Models option. You will need to implement the following functionality:
A main method containing some sort of main loop. For example: This might be where an object of the world is created and chances are rolled.
A Class that contains all the objects acting in the simulation. For example: This might be your world class which contains all of your creatures.
An Independent Actor class, this will be the main actor in the program and be the part of the program that constantly updates through each iteration of the main loop. For Example: This might be your creature class which might reroll whether it reproduces or dies, or it may walk or sleep each time that the main loop iterates. As opposed to the World type class which may or may not change from one iteration to the next of the main loop.
A way of outputting the stats of the program on each update step or on command. For example: the population numbers of creatures and perhaps other important stats such as creature age, hunger, children, etc.
Functionality Tiers For Grading:
For a maximum of 80%: You create a simulation which simply rolls random numbers and based on a threshold acts on functions of the classes in your programs. For example: You create a creature with a 10% chance to die on every update step and don’t have any attributes of Creature that contribute to its death chances.
For a maximum of 90%: You create a simulation which rolls for a series of different attributes in your classes that ultimately contribute to an agent's success or failure and can be affected by other classes' attributes. For Example: You create a creature that has a 10 percent chance of finding food which will update the creature's hunger. Additionally your success or lack of success in finding food updates how much food there is in the world and may increase scarcity and more competitiveness.
For a maximum of 100%: You create a simulation with real stored positions, movement actions, interactions, and population attributes that affect one another in a shared environment. Must also include base functionality of previous grade tiers. For example: You create a world represented by a 2D array filled with food and creatures. Creatures move in a random direction and may starve if they don’t run into food in a number of update steps. Creatures may only reproduce if they run into other creatures. And the world may respawn food in intervals at random locations.


For option two we will take a more hands on approach, naturally I cannot layout specific examples and guidelines for you to follow so instead:
You will be required to visit office hours or schedule at least 2 meetings to discuss the concept you’ve picked and to ensure your final project will be of sufficient complexity.



This assignment will require you to use any and all knowledge you have acquired in the class so far as well as any topics you may have access to before its due date. This assignment is meant to be a living project and the sooner you begin the more time you can spend adding new functionality and finding the use cases for the tools we have and will learn.
