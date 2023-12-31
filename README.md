# A Quick Introduction to CS @ Columbia

The CS major is easily the most popular undergraduate major when accounting for all four schools (CC, SEAS, GS, Barnard). While its popularity makes it one of Columbia's most vibrant academic communities, it's also a little daunting for prospective students to jump into the major's classes. Because of this, ADI has compiled this page on the specifics of each of the seven classes in the CS "Core" which every CS major or concentrator has to take and several "tracks" which are groupings of courses that fall under a certain subfield of computer science (e.g. Intelligent Systems, Software Systems, Robotics). 

# Table of Contents
- What is ADI?
- Additional Resources
- The Columbia CS Core
  - COMS 3203: Discrete Mathematics
  - COMS 3157: Advanced Programming
  - CSEE 3827: Fundamentals of Computer Systems
- CS Tracks

# ADI 

Application Development Initiative or ADI is Columbia's largest computer science club. We host weekly events such as Cookies & Code, professor lunches, internship and industry panels, and other social events for CS students at Columbia. 

Stay tuned for applications to join ADI Committee: 
- [ADI Website](adicu.com)

## Additional Resources 

- [CS Department Website](https://www.cs.columbia.edu/)
- [CS on Columbia College Bulletin](https://bulletin.columbia.edu/columbia-college/departments-instruction/computer-science/)
- [CS on SEAS Bulletin](https://bulletin.engineering.columbia.edu/computer-science)
- [CS on GS Bulletin](https://bulletin.columbia.edu/general-studies/majors-concentrations/computer-science/)
- [CS @ Barnard](https://cs.barnard.edu/)

# COMS 3203: Discrete Mathematics
### By Ayaan Ali (CC'26 Math & CS) 

### General Description
Discrete Mathematics (often called "Discrete") is one of the more unique courses in the CS Core. There's little programming involved (in some sections there's none) and theoretical computer science takes center stage. Topics you might learn in discrete mathematics include the basics of number theory, modular arithmetic, set theory, mathematical logic, proof-writing strategies (induction, contradiction, contraposition, uniqueness, etc...), rudimentary graph theory, statistics and probability, equivalence relations, and cryptography. 

### Why is this course important? 
Upper-level computer science courses such as COMS 3261 Computer Science Theory or CSOR 4231 Analysis of Algorithms are rooted in theory. Discrete teaches the "language" to understand theoretical computer science. It teaches the core mathematical principles that underline computer science. Moreover, many Discrete professors use LaTeX for their homework assignments. LaTeX is a word-processing software like Microsoft Word or Google Docs, except it's typed in mark-up language (similar to HTML). LaTeX is the standard document preparation software for higher mathematics, computer science, and in STEM research and academia. 

### Professors 
Professors can vary for Discrete Math (I took it with a graduate student named Melanie Subbiah), but usually the two professors who wind up teaching the course are Tony Dear (in the fall) and Ansaf Salleb-Aouissi (in the Spring). Reviews for each professor can be found on culpa.info which is operated by Columbia Spectator. 

### FAQ
- **Do I need Calculus for Discrete?**
  No! The only prerequisite for Discrete is one introductory programming class. No higher mathematics experience is assumed, but having some maturity with college mathematics wouldn't hurt.  
- **How much programming is in Discrete?**
  This is dependent on the professor. My Discrete course was entirely theoretical with almost no programming. Prof. Dear's course, on the other hand, emphasizes writing concept implementations in Python. However, generally, Discrete has far less programming than courses like COMS 1004 or COMS 3134 which are designed around programming.
- **When should I take Discrete?**
  It's quite common to take Discrete after COMS 1004. A great many students take it alongside COMS 3134 Data Structures & Algorithms or COMS 3137 Advanced Programming. Taking Discrete early opens up the door to higher level theoretical computer science courses. However, ensure that you've taken at least one programming class at Columbia before attempting Discrete. 


# COMS W3157: Advanced Programming

### By Anthony Zhou (CC '23, CS)

## Overview

Advanced Programming is a bit of a misnomer. It should probably be called Systems Programming. This class covers C (the programming language, not the letter) and UNIX (the operating system). The course starts with the basics of the C language and UNIX commands, and ratchets up into networking with HTTP and TCP. The culmination? A web server written entirely in C. 

Professor Jae Woo Lee notably summarized the curriculum in a paper cleverly titled ["Follow the River and You Will Find the C."](http://www.cs.columbia.edu/~jae/papers/3157-paper-v2.2-camera-final.pdf). 

## Why it matters

What actually happens when you press run on a Python program? Turns out there's all sorts of action going on with memory allocation and packet sending underneath our high-level programs and web apps. If you ever work with servers or embedded systems, you're sure to touch low-level systems code. Even if you only ever build web apps in your life (what a life!), it'll be good understand what's going on behind the scenes. You'll also need knowledge from AP if you want to take Operating Systems.

## Who teaches the class

Jae Woo Lee typically teaches the class, despite his brief sabbatical. The workload is a total of ~7 labs (programming assignments) throughout the semester, along with 3 exams, including the final. Labs can be intense, so start early. 

Jae does not like giving partial credit on exams. But C is also an unforgiving language. So the precise requirements of the class do have some logic to them. 

## FAQ

- **What do labs/exams look like?**
  Labs are typically a pdf document with a list of monospaced requirements. Make sure to read the requirements carefully so you don't get points docked! Exams are fill-in-the-blank questions about syntax or the output of specific programs. Check the [course webpage](http://www.cs.columbia.edu/~jae/3157/) for more details. 

# CSEE 3827: Fundamentals of Computer Systems
### By Joshua Hahn (SEAS '24 CS & Math)

### General Description
Fundamentals of Computer Systems (often called  "Fundies") is, as the name suggests, closely related to electrical & computer engineering. In Fundies, you start from the very basics, learning about boolean algebra, binary counting, and simple circuits, to eventually building a simple single-cycle microprocessor and finally, a pipelined system. The only programming in this course is done in MIPS Assembly, which many find to be one of the more challenging aspects of this course. In some
sections, the MIPS programming assignment is treated as a homework, while in otheres it is treated as a separate project. 

### Why is this course important?
This course is an essential course to understanding low-level languages and operating systems. Courses like COMS 3157 Advanced Programming have small but nontrivial connections to some of the ideas learned in Fundies, and upper-level courses such as COMS 4118 Operating Systems have key concepts that rely on a strong understanding of the computer architecture (registers & memory storage). Even if you do not plan on taking higher level courses in computer / operating systems, Fundies gives you a new perspective on how the code we write is actually processed by the computer (i.e. We know computers work in 0s and 1s. How does the Python code I write actually turn into machine-readable code that can be properly executed?).

### Professors
The course is typically taught by professor Martha Kim in the Fall and professor Dan Rubenstein in the Spring. The course is structured very differently depending on which professor you take the course with. Professor Rubenstein's course is weighed more heavily on exams, but all non-exam portions of the course (homework, attendance in office hours) are graded more generously. Professor Kim's course weighs the aforementioned MIPS programming assignment as a separate project, but will weigh the
test less heavily.

### FAQ
- **If there is little programming, what do assignments look like?**
  Assignments will vary depending on what you are learning, but here are some example questions: "Given constraints ..., build a ... using ...", "Given a ... processor, explain how the ... instruction will affect each stage of the processor", "Draw a circuit that can do ..."

# CS Tracks

Until 2023, CS majors had to choose one of 5 tracks to pursue:

- Foundations of Computer Science
- Software Systems
- Intelligent Systems
- Applications
- Vision, Graphics, Interaction, and Robotics

These tracks no longer exist, but they offer useful ways to think about choosing your CS clases. 

## Foundations of Computer Science

In a word: theory. Have you ever wondered about how mystical it is that a program ever works? Or how a machine learning model comes to write Chinese poetry? Sure, we can describe an algorithm and give some intuitions, but how do we *prove* why these things work? The foundations track is about building a rigorous theoretical framework -- think math -- for analyzing computational systems, programs, and algorithms. Things you can do with the foundations track include: proving which kinds of problems are hard to solve (and which kinds are NP-hard), developing runtime and storage bounds for algorithms, and even proving theorems about the perceptual limits of machine learning models. 

As for specific classes, Foundations begins with CS Theory and Analysis of Algorithms, after which you can branch into COMS 4236 Complexity Theory, COMS 4252 Computational Learning Theory, or COMS 4232 Advanced Algorithms. Another option is to go deeper into math, exploring topics like MATH 4061 Modern Analysis, MATH 4041 Modern Algebra, and IEOR 6616 Convex Optimizaion. 

Knowing the foundations helps you understand (and therefore nudge) the limits of computer science.