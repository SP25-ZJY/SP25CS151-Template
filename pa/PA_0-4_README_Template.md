<h1> CS151 PROGRAMMING ASSIGNMENT 1</h1>

<h2> Table of Contents </h2>

<!-- TOC -->
  * [`I. DEADLINES`](#i-deadlines)
  * [`II. RESOURCES`](#ii-resources)
  * [`III. PURPOSE OF THE ASSIGNMENT`](#iii-purpose-of-the-assignment)
  * [`IV. PROBLEM`](#iv-problem)
  * [`V. REQUIREMENTS ANALYSIS`](#v-requirements-analysis)
    * [An Example Game](#an-example-game)
  * [`VI. DESIGN`](#vi-design)
  * [`VII. PROGRAMMING REQUIREMENTS`](#vii-programming-requirements)
  * [`VIII. ASSIGNMENT REMINDERS`](#viii-assignment-reminders)
  * [`IX. SUBMISSIONS`](#ix-submissions)
    * [`DESIGN SUBMISSION: Sunday 01/20 11:59PM`](#design-submission-sunday-0120-1159pm)
    * [`FINAL SUBMISSION due Monday 01/27 11:59PM`](#final-submission-due-monday-0127-1159pm)
<!-- TOC -->

<h4> 🔵 Understand the problem and Design before Coding 🔵 </h4>

**🔵 Post any question on [Discord PA Channel](https://discord.com/channels/1316435150527004825/1316435267145695312) 🔵**
## `I. DEADLINES`

| Deliverable | Due Date               |
|-------------|------------------------|
| PA-Design   | Thursday 02/06 11:59PM |
| PA-Final    | Thursday 02/13 11:59PM |

## `II. RESOURCES`
- [Class Examples Repo](https://github.com/SP25-ZJY/CS151)
- [Self or Annotated Notes](https://moodle.loyola.edu/course/view.php?id=89004)
- [CS 151: Book](https://learn.zybooks.com/zybook/LOYOLACS151Spring2025)
- [Solutions To Previous Labs and PAs](https://classroom.github.com/classrooms/193636664-sp25-zjy-cs151)
- [PA Late Submission Form](https://forms.office.com/r/mkE8wwT1xV)
- **You can use LLM (Such as ChatGPT or Gemini) as a guider but not as a problem Solver**
  - 🟠**LLM-Based Codes Will Result in Penalty and Honor Code Violation**🟠

## `III. PURPOSE OF THE ASSIGNMENT`

The purpose of this assignment is to give you:  
1. Practice with input & output  
2. The opportunity to use decision-making  
3. A chance to be creative

## `IV. PROBLEM`

You are creating a text adventure game!  
- In this game, the user gives input that affects the path of the story. 
- You must create a game that meets the requirements in the specification below.

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

## `V. REQUIREMENTS ANALYSIS`

The first stage in your programming assignment is the requirements analysis stage.  
- You need to make sure you understand the below requirements for what needs to be included in your story’s decision making:

1. Your adventure game must have **🔺at least one decision for each🔺** of the following types:  
    1. Make a decision based on the value of an integer.  
    2. Make a decision based on the value of a float.  
    3. Make a decision based on the value of a string.  
2. Your adventure game must have a **🔺path with at least 2 decisions🔺** on it 
   - (e.g.)
     - I am given the option of choosing A or B. 
       - If I make choice A which then lets me decide between X and Y; 
       - but if I choose B I do not get to choose between X and Y, but instead do something else.   
3. Your adventure game must have **🔺at least 1 choice that has at least 3 possible directions🔺** 
   - (e.g.when they enter a number the game takes a different path if their number is <5, between 5 and 10, or > 10).  
4. Your adventure game must use at least **3 different relational operators** throughout the story.  
5. Your adventure game must have **🔺a decision where it gives the user at least two specific inputs to choose from🔺**, and does something different based on which value they input 
   - (e.g. "enter 'green', 'red', or 'yellow'").
6. Your adventure game **🔺must use something the user input in part of the output🔺** at least once 
   - (e.g., asking for their name and then outputting their name every time you address them).
7. Your adventure game must **🔺ask for at least three user inputs🔺**, but likely you'll need more than that.

The game must make sense and have an actual story to it. 
- It needs to be understandable. 
- Consider that your professor will be reading the entire story.

Your game should also not just use the exact examples used above, or used in the example below.

### An Example Game

Please watch the [youtube video showing an example game](http://www.youtube.com/watch?v=x0Ksedq3Z5k). 
- It does not show all of the requirements from above, but does demonstrate a number of them. 
- If you are having trouble understanding what is being asked of you in this assignment, be sure to watch the video, then ask for clarification if you still have questions.

## `VI. DESIGN`

The second stage is to design your solution based on the requirements:

1. Write out your algorithm, including input, output, decisions, and calculations.  
    1. Be sure to indent and properly number to show when a decision is nested inside another decision.  
    2. If you have story elements that are used in multiple paths, you can label them as "story part 1," "story part 2," etc., 
       - Then reference them by that name the next time it’s used, instead of writing it all out again. 
       - However, you must give your full story as part of your design. 
       - Don’t write your entire algorithm by just saying "story part X."
2. Double check that you included all of the requirements

If you are having trouble coming up with a story, think about a book or movie you enjoyed. 
- Be inspired by its story line or characters and come up with something original.


## `VII. PROGRAMMING REQUIREMENTS`

After your design is complete and correct, it's time to start programming and then testing:

1. Fix design issues: If there were issues with your design, either not meeting requirements or in the format, fix that before you start writing your code.
2. Implementation: Write your program following the requirements and based on your design.  
    1. Follow good usability/HCI principles in your input and output (for instance, make it clear the type of input you are asking for).  
    2. Remember to state the purpose of the program.  
3. Testing: Make sure it works correctly; give it sample input, and check that the output is correct.  
    1. Create test cases where each test case is a separate path through your program. 
    2. You do not need to put the full output in the test case, just make it clear what part of the output is there.  
    3. Note that if you have a particularly large program that results in a large number of control paths, you only need to list 10 test cases. 
    4. If you have fewer than 10 paths through your program, then you should list one test case for each path.
    5. Test that you can get through each path correctly by running your code using the output. 
    6. If it doesn’t give the expected output, find the error and fix it. 
this point will be done on [`final_design.md`](final_design.md) ✳️

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

## `VIII. ASSIGNMENT REMINDERS`

- Follow the programming assignment requirements document for comments, formatting, etc. 
- Follow the honor code guidelines outlined in the syllabus and at [here](https://www.loyola.edu/academics/computer-science/current-students/honor-code).

- Include intro comments. 

```
# Programmers:  [your names here]
# Course:  CS151, Dr. Zelalem Jembre Yalew
# Due Date: [date assignment is due]
# Assignment:  [number of assignment]
# Problem Statement:  [what problem does your code solve; i.e., calculating inches from centimeters]
# Data In: [what information do you request from the user?]
# Data Out:  [What information do you display for the user?]
# Credits: [Is your code based of an example in the book, in class, or something else?  Reminder: you should never take code from the Internet or another person.]
```
## `IX. SUBMISSIONS`

### `DESIGN SUBMISSION: Thursday 02/06 11:59PM`

**🔶 Commit and Push to GitHub: 🔶**

1. Write the algorithm for your design on [`initial_design.md`](initial_design.md) document. 
2. The document can include aspects of the assignment 
   1. You think you've correctly included 
   2. You are not sure is correct or got stuck on.
   3. Importance of adding description
      1. To make it clear that you understand what you've done, or 
      2. Where you need the most help in getting ready to write the code.

Your algorithm should follow the requirements of an algorithm, and contain all the requirements for this assignment. 
> **There should not be any code or anything that resbles code (e.g. print or input functions).**


### `FINAL SUBMISSION due Thursday 02/13 11:59PM`
**🔶 Commit and Push to GitHub: 🔶**

1. Completed [`main.py`](main.py) file  
2. [`initial_design.md`](initial_design.md)
3. [`final_design.md`](final_design.md)
4. An Excel file with your test cases.  
    - Edit the [`test_cases.xlsx`](test_cases.xlsx) file with Excel software 
    - If it can open then ok. Otherwise
      - Right click on [`test_cases.xlsx`](test_cases.xlsx) -> Open In -> Associated Application
5. [`reflection.md`](reflection.md) -> Reflection of the assignment
6. A signed or emailed statement from a client that they are satisfied with your SW .


***Remember to commit and push your GitHub project.***

[<h2>⬆ Back To Top ⬆</h2>](#i-deadlines)

✅✳️🔺🔺⏺️🔼🟢🟡🔴🔵🟣🟠⛔️🟥🔶🔻🔺❌‼️❕
