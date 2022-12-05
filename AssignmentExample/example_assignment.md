
# [This is an example assignment.rmd](https://github.com/LydiaFrance/Reproducible_Figures_R/blob/lessons/AssignmentExample/ExampleAssignment.Rmd)

# [This is an example assignment.html](https://htmlpreview.github.io/?https://github.com/LydiaFrance/Reproducible_Figures_R/blob/lessons/AssignmentExample/ExampleAssignment.html)

# Written Instructions

Some confusion about the assignment as multiple files can't be uploaded to your homework portal. 

Here is a way to do the assignment in a single file. If you have found an alternative way, that's fine, don't worry. 


## Create `assignment.rmd`

Write your assignment up in an r markdown file. 

## Write your answer for Question 01. 

Just use the usual markdown text format in your `assignment.rmd` file. 

## Create R code to make a bad figure for your penguin data

You may want to produce a separate file for this work, as you will not be marked on your code. For example, `bad_figure.R` or `bad_figure.rmd`. 
When you have the final figure, save it as `bad_figure.jpg`. 

Then embed this image in your `assignment.rmd` file using the following syntax `![](my-path-to-image-file/bad_figure.jpeg)`

### Alternatively:
If the code used to make your bad figure is inside your `assignment.rmd` then simply hide code using in the r block ` ```{r bad-figure echo=FALSE} `


## Write your answer for Question 2

This is the part that is actually marked. 

## Write your answer for Question 3

## For Question 4, you need to make R code and upload it to GitHub

For a tutorial on this, see here: https://github.com/LydiaFrance/Reproducible_Figures_R/blob/lessons/extra_tutorials/github_tutorial.md

Your Github repo then has multiple files and subfolders. Include inside your `assignment.rmd` a link to your GitHub repo.  

For example, this is a Github repo with all my files: https://github.com/LydiaFrance/PenguinProject

## Write your answer for Question 5

And include a link to your partner's repo. 

## Upload your assignment file

### EITHER: Upload `assignment.rmd`

This is the raw rmd file. Everything will be visible so make it as clear as possible where your written answers are.

### OR: Upload `assignment.html` or `assignment.pdf`

If you then render your rmd you end up with formatted text. 

If you have used `{r bad-figure echo=FALSE}` when you want to hide unwanted code, those cells will not appear in your final `pdf` or `html` file.  

