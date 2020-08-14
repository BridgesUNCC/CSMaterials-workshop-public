# How to Use CS Materials to classify your course

## Classify your course one material at a time

### What to classify

We suggest classifying everything one at a time. Lectures slides, quizz, assignments, exams, etc.

You can later group things in collections to have groups for all lectures, all assignments, ...

### How to classify

1. Login in http://cs-materials.herokuapp.com/
2. Select Create Materials in the left bar.
3. Enter all the data for all the fields
   1. Note that field Authors, Courses, Languages, Topics, Datasets open a list. You can actually select multiple entries and make your own by typing something and pressing "enter".
4. You need to hit submit to save your work, you can edit afterward.
5. There are two curriculum guidelines in the system you can classify against: ACM/IEEE Computer Science  2013 guidelines  and NSF/IEEE-TCPP Parallel and Distributed Computing 2012 guidelines. The "ACM CSC 2013" button will get you to  ACM/IEEE's guidelines
6. The guidelines is shown as a tree list.
   1. You can select a topic or a learning outcome or an entire group.
   2. You need to hit the back arrow and the submit button to save your work.
   3. We recommend you look at the entire curriculum guideline at least once.
   4. You can use the search field at the top to highlight entries matching a particular keyword.
   5. You can use the cheat sheet below to check whether you missed an obvious match.
   6. Expect that a material will have more match than you think. (For instance a lecture about Binary Search Trees mapped to about 15 entries)

### FAQ

#### How wide should I check the guidelines?

Think that even if you think of your lecture as teaching one thing, it
probably covers a lot more than that one thing. If your assignment on for
loops uses an automatic testing framework, then you are also teaching
students about unit testing. If your lecture on 2D arrays uses images
as a visual example then you are also teaching image representation
and potentially image processing.

#### How do I decide whether I should select a classification item or not?

Really it is a judgment call you have to make. But a good rule of
thumb is "do I expect this material to teach this topic/learning
outcome to some extent?". A CS1 lecture on loops teaches for-loops. An
end of CS1 project will most likely use for loops and be designed to
reinforce for-loops. A project at the end of a computer graphics class
will certainly use for-loops but does not intend on teaching
for-loops, but will have higher level learning outcomes.

#### How fine grained should I cut my material?

Since CS materials supports collections, one could imagine encoding
each slide of a slide deck individually. Whether you should do it or
not is a judgment call from you. We recommend to select a grain of
materials that are files as you distribute them to students.

Probably each slide deck should be individual materials. Probably each
chapter of a text book could be individual materials.

There are cases where going finer grain could make sense. Classifying
individual problems in an exam could be helpful.

Obviously classifying at a finer grain is more work.

#### How should I name my materials in the system?

We suggest you name materials based on university, course, instructor,
material name. For instance: "UNCC ITCS 2214 Saule: Shortest Path"



## Use the harmonization view on the whole course

### Why use it?

When classifying materials, you'll realize you may not have
consistently tagged materials. The harmonization view to look at your
classification more globally to reconcile the classifications across
multiple materials at once, make corrections, and serves as a check.

### How to access

Go to "view my materials" in the left bar menu.

Select all your assignments.

Go to "Harmonization matrix" in the left bar menu.

### How to use

The harmonization matrix shows you a table with your materials as
columns and classifications as rows. The table can be editted by
clicking on the cells. Edits show as a different colors. You need
to submit the changes explicitly.

Note: Submitting changes with the harmonization matrix has been
somewhat unstable at some point depending on users. So submit your
changes early to make sure you don't lose them.

Use the harmonization matrix by looking row by row and deciding
whether the current classification of the materials make sense.  The
matrix should choose automatically an order of materials and
classification that group together similar items. (It's not perfect
though.)

# Cheat Sheet

You probably should look at the entire classification.
We have extracted parts of the ACM/CS 2013 classification you may want
to look at. **There could be mapping on other parts of the classification**.


## CS1

Here are the classification of Nifty assignments and a OOP design class (which are not perfect proxies for CS1) http://cs-materials.herokuapp.com/radial?tree=acm&ids=264,266

You may want to consider in particular
- Software Development Fundamentals
  - Fundamental Programming Concepts
  - Fundamental Data Structures
  - Algorithms and Design
  - Development Methods
- Software Engineering
  - Sofware Design
- Programming Languages
  - Basic Type Systems
  - Runtime Systems

Depending on how the class is motivated, or assignment you could have
mapping in graphics, data mining, etc.

## Data Structures

Here are two Data Structure classes at UNC Charlotte that have been classified:
http://cs-materials.herokuapp.com/radial?tree=acm&ids=178,185

You may want to consider in particular
- Algorithms and Complexity
  - Basic Analysis
  - Fundamental Data Structures and Algorithms
  - Algorithmic Strategies
  - Advanced Data Structures, Algorithms and Analysis
- Software Development Fundamental
  - Fundamental Data Structures
  - Algorithms and Design
  - Fundamental Programming Concepts
- Discrete Structures
  - Graphs and Trees
  - Proof Techniques

Depending on how the class is motivated, you could have mapping in
programming languages, in data mining, in data base.
