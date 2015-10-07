How does tracking and adding changes make developers' lives easier?
Tracking changes helps developers because often, when programming, code is broken. It is helpful to be able to refer to previous version in this situation.

What is a commit?
A commit is a collection of changes committed to memory. You run a commit from the terminal. 

What are the best practices for commit messages?
Best commit messages use the imperative form of verbs, capitalize the first word, leave off puntuation, and keep them simple. 

What does the HEAD^ argument mean?
It indicates which change you are viewing. 

What are the 3 stages of a git change and how do you move a file from one stage to the other?
When you update a file, it has "untracked changes". Once you use git add command, the status of the file is "staged changes". To commit the changes, you call git commit, add a message. The branch is now "clean".

Write a handy cheatsheet of the commands you need to commit your changes?
git add
git commit
git push
git checkout master
git fetch origin master
git merge origin/master 

What is a pull request and how do you create and merge one?
A pull request compares to files to see what has changed between the two. You can create a pull request AND merge the request through the GitHub interface. 

Why are pull requests preferred when working with teams? Pull requests are preferred when working with teams because teammates can work on different areas of the file, then merge them together later while maintaining the integreity of others' work, so long as they are not coincident. 

