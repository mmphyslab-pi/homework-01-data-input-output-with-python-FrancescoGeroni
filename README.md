# Homework 01 - Data Input/Output with Python

## Introduction
This set of Python Notebooks are meant to be help in getting more familiar with the
Python functions used to read and manipulate datasets in two main formats used in multimessenger
science:

* CSV (Comma-separated values): ASCII-based text files
* FITS (Flexible Image Transport Sysyem), the standard in astrophysics

Later on, in future tutorials, we will see more formats, but for now let's focus on these two.

## What do you have to do?
You will find 2 sets of tutorial+exercises:
* **Set 1** - Reading and manipulating CSV files
* **Set 2** - Reading and manipulating FITS files

For each set, first look at the tutorial, check the code, run it and do modifications in order to be sure that you've understand how it works.

Then you can move to the exercises, where you will be asked to perform some tasks and solve some
real-life cases of data analysis.

## Structure of the package
The package contains the following directories

* *code*: Contains Python Juyter notebooks for tutorials and exercise
* *data*: Contains data used in this set of tutorial and exercises

## Getting the package
In order to get the packege with the tutorial and the exercise, you should run a git clone.
For instance 
```
git clone git@github.com:packageaddress
```
Where *git@github.com:packageaddress* has to be substituted with the link that you can find on the **Clone or Download** green button in this page.
git@gitlab.com:mrazzano-dockers/docker-mmlab.git

**IMPORTANT** As you have seen in Gitlab already, also in this case you will be asked for a password (if putting a HTTPS address), or you will be denied access (if using the ssh address). In order to create a SSH key and add it to Github, there are similar steps to those you have done already for gitlab. You can find more informtion at this [link on Github.com](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh)

## Working with the package
Of course, since this is a git repo, you can do what do you want (commit, push, create branches, etc).
However, if you want to modify and play with the tutorial code and not change the original, you can create a branch:
```
git branch dataio-mybranch
git checkout dataio-mybranch
git branch 
```
*Last command is to check if the branch is there...*


## At the end?
When you have completed your taks, please remember to commit and push adding a meaningful comment.
```
git commit -a -m "Task Finished!" 
git push origin master dataio-mybranch
```

## Final thoughts
Some of you know Python well, some reasonably well, and some don't.
I hope these will be useful at different level for each of you to get more pratice on slightly advanced Python data analysis. These will be useful for the various experiences of the course, so take advantage it it and enjoy!