# X-Team 42 Paired Programming Matchmaker

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

A common struggle among CS students is finding a compatible partner to collaborate with on programs. Although some students use Piazza to find a partner, it is hard to know if he/she is truly the right partner for you. A program that can be used to solve this problem is the Paired Programming Matchmaker. The Paired Programming Matchmaker will use qualities such as age, grades, and amount of free time to create a list of potential partners for a student based on his/her own input. The list of potential students will contain their name, phone number and email. The student looking for a partner may then choose whoever they want from the list with confidence that they will work well together. 

## Questions to answer for Exercise #2

1. Name: Paired Programming Matchmaker



2. Output: Describe the output your program will produce.  Include and example format of the output produced.

When a user runs this program, the output will be an ordered list of people that would be good partners. The output will be a person’s name and their contact information that they provided. An example of the output could be:

1.	Jack Pientka
Email: jpientka@wisc.edu
Phone: 608-770-7529
2.	Simon Theuer
Email: n/a
Phone: 555-5555-555

The list of names would continue for an arbitrary amount of people; likely around 10 names as someone will likely find a partner within 10 names. 

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.

The user would need to input their name, section number, phone number, age (1 = freshman, 2 = sophomore, 3 = junior, 4 = senior, 5 = other), grade in the class (points they've gotten out of the total points in the class so far), and the amount of free time they have (on a scale of 1-5) as well as a ranking for age, grade in class, and amount of free time for what is most important to match up with them next to their input for that category with a space between (1 being most important and 3 being least).

Example input:

Billy Johnson

2

1234567890

3 3

75 1

3 2

4. User Interface: The user interface will be comprised of a text menu with prompts for the required inputs.



5. Types List: Types List: Our solution will use a Student object that holds grades, free time, age, section, name, phone number, and email.  Our solution will sort students into an AVL or B tree that seperates students depending on the data they provided. 


Main.java- This class will prompt for user data and call on other classes.
StudentInfo.java- Creates a student object w/ passed in information from Main calss.
Sorting.java- Sets up data structure and sorts accordingly.


## Edit and Submit this file and any figures referenced by this document.

