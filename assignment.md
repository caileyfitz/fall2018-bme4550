# Instructions for submitting assignments via GitHub classroom :goat: 

1. Open a terminal on your computer so that you can push to GitHub via the command line.

2. In command line, navigate to directory (or create one) where your homework files will live. For example, if I am already in my BME 4550 directory and want to make a folder for Homework and then nest another folder, Assignment1, under the homework folder, I would input the following commands: 
```
  mkdir Homework
  cd Homework
  mkdir Assignment1
  cd Assignment1
```

 3. Visit the assignment link provided for a particular assignment and click to accept the assignment:
![](https://image.ibb.co/cQHqoU/accept.png "Logo Title Text 1")

4. After accepting, click the link to go to your created assignment repo:
![](https://image.ibb.co/jj8Khp/accepted.png)

5. You can now setup your repo to add your assignment files:
![](https://image.ibb.co/e78wTU/setup.png)

6. Likely, everyone will need to create a new repo via the command line (unless you have already created one for this assignment). Follow the instructions above, *entering one line at a time*. 

7. You are now ready to start adding files to your assignment folder! You can add these files as you normally would (create a .Rmd file in RStudio and work on it there), but you will need to remember to commit and push any changes to your assignment repo. Here is a simple guide to git: http://rogerdudler.github.io/git-guide/

`git status` Tells you which files have changed since last commit 

`git add <filename>` Adds file to local tree; alternatively, `git add .` will add all changed files

`git commit -m "message"` Add a message to indicate what has changed; this commits files to your local repo 

`git push` Pushes your changes to your Assignment GitHub repo 

8. There is no official "Submit" button when you have completed your assignment. Instead, the last commit you have made before the deadline will be counted as the last change to your submission. 

9. Have fun and feel free to ask any questions you may have! :fireworks:
