# X-Team Group Maker Proposal

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

The problem we are looking to solve is that it can be hard to seperate students into groups. Often, when seperating students into groups the grouping can become very uneven. Students with low GPA's can be paired with other students with low GPA's which can lead to some groups struggling. Our program looks to solve this by grouping students based on their GPA's. The program will take in a file with names and gpa's. The user will then specify the size of the groups and the program will create the GPA balanced groups.

## Questions to answer for Exercise #2

1. Name: X-Team Group Maker Proposal

2. Output: The program will output a file with a list of each team and each group member in each team. Users can choose the name of the output file.

	At the bottom of the file we will output some stats on the groups, like average GPA of each group, standard deviation of group GPAs, etc.
	
	Example output:
	
	GROUP 1:  
	FirstName1, LastName1  
	FirstName2, LastName2  
	FirstName3, LastName3  
	FirstName4, LastName4
	
	
	GROUP 2:  
	FirstName1, LastName1  
	FirstName2, LastName2  
	FirstName3, LastName3  
	FirstName4, LastName4
	
	
	STATS  
	Average Group GPA, Standard Deviation
	

3. Input: The input will be a file containing information about a list of students. Each line will contain a students' full name and GPA (in double).  

	Example input: 
	
	FirstName1,lastName1,3.0  
	FirstName2,lastName2,3.5  
	FirstName3,lastName3,3.8 

4. User Interface: Users will run the program from the console.

	Interface on example run of program: 

	X Team Group Maker  
	Loaded XXX people.         
	How many people per group?     
	\<UserInput\>                             
	Separated into XXX groups.  
	Output to file successful.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
Three classes:
- Person.java represents a single student, having members for their name and GPA, with accessors and mutators  
- Group.java represents a group  of students.  It stores the list of students, an average GPA and a team number  
- Main.java parses input of the people file, makes Person instances, sorts them, takes user input to find number of people per group, separates them into groups to form near-equal GPA averages in each group, outputs these groups to file.


## Edit and Submit this file and any figures referenced by this document.

