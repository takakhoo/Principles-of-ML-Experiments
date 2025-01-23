# Overview
In this lab, you will implement a linear regression by hand (**no high-level libraries are allowed** -- we are doing this from first principles!) on real-world homicide data.

Allowed libraries include:
* numpy
* matplotlib

**Please read through all of the files associated with this Lab Assignment before you start the assignment.**

## Problem Statement
We are given data used in a study of the homicide rate (HOM) in Detroit, over the years 1961-1973. The following data were collected by J.C. Fisher, and used in his paper ”Homicide in Detroit: The Role of Firearms,” Criminology, vol. 14, pp. 387-400, 1976. Each row is for a year, and each column are values of a variable. A picture of the table for your reference immediately follows, but have access to the raw data in this lab.

![image](https://peilundai.com/ps2_programming/table.png)

It turns out that three of the variables together are good predictors of the homicide rate: `FTP`, `WE`, and one more variable.

Use methods described in Chapter 3 of the textbook to devise a mathematical formulation to determine the third variable. Implement your formulation and then conduct experiments to determine the third variable. In your report, be sure to provide the step-by-step mathematical formulation (citing Chapter 3 as needed) that corresponds to the implementation you turn in. Also give plots and a rigorous argument to justify the scheme you use and your conclusions.

### Design on Paper (Outline Your Problem Solving Strategy)
A design on paper comprises the analysis, diagrams, pseudo-code, plans, and documents that present a complete and thorough solution to the task at hand. 

This is not just scratch paper--this is a formal solution to the problem that could be used to communicate your solution to others (indeed, you will need to communicate your solution to your course instructors for a grade, shortly). You want it to be **concise, clear, and well organized**.

Type or hand-write your step-by-step mathematical formualtion (citing chapter 3 as needed). Make sure that your solution to the problem at hand is clear (including the steps that you would take to implement a linear regression on this data -- remember, **you cannot use high-level libraries like a sklearn linear regression package in this assignment** -- you must implement your solution from first principles-). Include this in your post-lab write-up and make sure that you include it in your repository.

>[!CAUTION]
>It is poor practice to try to solve a problem by immediately programming. Though it requires an up-front cost, developing a solid paper design will save you time in the long run and will make your code easier to write. Your code should always be a translation of a fully-formed solution to a problem (read as: a design) into an implementation. If you are trying to solve the task at hand while programming, you need to revisit your design on paper. 

## Goals of this Lab
There are four primary goals in this lab assignment:

1. To give you experience extending familiar analysis to real world problems that are more open ended, and where you do not have ground truth about the underlying regression function. 

2. To stretch you to solve a problem similar to problems we explored in this Sprint, but to which you have not had prior exposure. 

3. To continue cultivating your communication skills by asking you to write readable code and a succinct, brief, and accessible post-lab report. In doing so, to continue practicing forming logical arguments and justifying your design decisions.

4. Finally, to continue designing solutions from first-principles rather than relying on high-level libraries. This persuit is not merely an academic exercise--you are going to need the intuition and insight you gain implementing these algorithms by hands in your future courses in this program--particularly when you start implementing machine learning algorithms in hardware, where your only option might be to implement your algorithms by hand.

## Expectations
All lab submissions are individual and every item you submit should be a reflection of your own work. You should have ownership over the entirety of any lab you submit in this course. While your work is your own, we understand that it can be helpful in learning machine learning to collaborate with your peers, which can range from high-level discussion of a problem to debugging. Having others look at our code encourages us to write code with readability in mind. In practice, we will never work in a silo, and being able to discuss these topics with others well is a valuable skill. When you collaborate with another student, please cite them appropriately and be respectful of sharing too much. The Academic Honor Principle applies.

We respectfully ask that in the interest in furthering your own understanding of the material, that you refrain from using generative AI to code for you. Your work should be your own and you should feel comfortable justifying each design decision you make. 

Please cite any outside sources you reference and cite any peers you discuss this problem with.

Please do not solve this problem using high-level regression libraries that implement the regression for you. We are specifically asking you to implement your solutions by hand to prepare you for the rest of the program. 

>[!Important]
> Finally, have fun with this assignment! This is one big puzzle!

## Evaluation
In this lab, you will be evaluated on your code (and its readability), on the success of your model, and on your brief report that includes your paper design, makes an argument for your model and reflects on your experiences in this lab. 

At the end of the lab, you should push your code to your personal repository, ensuring that your Jupyter notebook outputs are visible in the web browser. Please include your paper design and brief post-lab write-up in the GitHub repository you are submitting for this assignment.

You will be evaluated on your ability to communicate your ideas in this lab clearly and succinctly. This includes both the written component, where you describe your system, and any code you write. Comment and document as you go. Do not try to retrofit your documentation! (Though as you work the problem you might want to change earlier comments--this is ok and encouraged as needed!).

### What to Submit
1. Your design on paper.
2. A brief description of your model. Justify your selection of model parameters.
3. An evaluation of your model, including evidence as appropriate. Please make sure that your model outputs are visible in the Jupyter notebook in the web browser.
4. Finally, please individually briefly reflect on your experience in a couple of sentences. What are you taking away from this lab?

If you have questions about what you need to submit, please ask your course staff!