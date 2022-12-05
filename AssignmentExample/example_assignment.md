Some confusion about how to upload multiple files to your homework portal. 
Here is a way to do this, but if you have already done it differently, don't worry. 


## Step 01: Create `assignment.rmd`

Write your assignment up in an r markdown file. 

## Step 02: Write your answer for Question 01. 

Just use the usual markdown text format in your `assignment.rmd` file. 

## Step 03: Create R code to make a bad figure for your penguin data

You may want to produce a separate file for this work, as you will not be marked on your code. For example, `bad_figure.R` or `bad_figure.rmd`. 
When you have the final figure, save it as `bad_figure.jpg`. 

### Alternatively:
If the code used to make your bad figure is inside your `assignment.rmd` then simply hide code using ` ```{r bad-figure echo=FALSE} `


## Step 04: Write your answer for Question 2

This is the part that is actually marked. 

## Step 05: Write your answer for Question 3

## Step 06: For Question 4, you need to make R code and upload it to GitHub

For a tutorial on this, see here: https://github.com/LydiaFrance/Reproducible_Figures_R/blob/lessons/extra_tutorials/github_tutorial.md

Your Github repo then has multiple files and subfolders. Include inside your `assignment.rmd` a link to your GitHub repo.  

For example, this is a Github repo with all my files: https://github.com/LydiaFrance/PenguinProject

## Step 07: Write your answer for Question 5

And include a link to your partner's repo. 

## Step 08: Upload your assignment file

### Option: Upload `assignment.rmd`

Everything will be visible so make it as clear as possible where your written answers are.

### Option: Upload `assignment.html` or `assignment.pdf`

If you have used `{r bad-figure echo=FALSE}` when you want to hide unwanted code, those cells will not appear in your final `pdf` or `html` file.  

