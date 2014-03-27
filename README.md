Farny-Simulator
===============

![alt tag](http://www.bu.edu/me/files/2010/09/Farny-2010.png)

===============

Version 1.0.0

To use, simply run farny_simulator.m using Matlab. Please ensure that the 'supporting_files' 
folder is in the same directory.

A sample truss design has been provided for you to illustrate the design and simulation process.

To develop a new truss you will need the following:

  1. The number of members and joints
  2. A statically determinant truss design, such that 2j - 3 = m
  3. The coordinate locations of each joint, in cm
  4. Joint 1 must be the origin (0,0) and is where Sx1 and Sy1 are applied
  5. Joint j (the last joint) is where Sy2 is applied
  6. A list of the joints connected to each member
  
There are two simulation options available:

  1. Analyze member forces for a single, specific applied load
  2. Simulate truss failure to identify the maximum load and the member that will fail first
  
That's it! Please enjoy the power of the Farny Simulator.

===================

Developed by:

Carlton J. Duffett
Boston University
Computer Engineering

Spring 2014
