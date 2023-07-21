This project is about how to use the branches and pull change it git and GitHub

1. Repo-session

Create a new directory called 0x01-git in your alx-pre_course repo and a non empty README.md in your directory:
    *commit to repo: git add ., git commit -m "commit msg", git push*

2. Coding fury road

Inside 0x01-git:
Create these directories: bash, c, js
Create these empty files: c/c_is_fun.c,js/main.js and js/index.js
Create a file bash/alx with these two lines inside: #!/bin/bash and echo "ALX"
Create a file bash/school with these two lines inside: #!/bin/bash and echo "School"
Commit changes with (message: “Starting to code today, so cool”) and push to the remote server

3. Collaboration is the base of a company

For this project, create a branch update_script and in this branch:
Create an empty file named bash/98
Update bash/alx by replacing echo "ALX" with echo "ALX School"
Update bash/school by replacing echo "School" with echo "The school is open!"
Add and commit these changes (message: “My personal work"
    *To check which branch is being used: git branch -a*
    *To create new branch: git branch <branch_name>*
    *To change branch: git checkout <vranch_name>*
Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:
Change branch to main
Update the file bash/alx by replacing echo "ALX" with echo "ALX School is so cool!"
Delete the directory js
Commit your changes (message: “Hot fix”) and push to the origin

4. Collaboration: be up to date

For this task – and only for this task – please update your file README.md in the main branch from GitHub.com. It’s the only time you are allowed to update and commit from GitHub interface.
After you have done that, in your terminal:
Get all changes of the main branch locally (i.e. your README.md file will be updated)
Create a new file up_to_date at the root of your directory and in it, write the git command line used
Add up_to_date to git, commit (message: “How to be up to date in git”), and push to the origin

5. HAAA what did you do???

Collaboration is cool, but not really when you update the same file at the same time…

To illustrate that, please merge the branch update_script to main: “Cool, all my changes will be now part of the main branch, ready to be deployed!”
HHHHHHHAAAAAAAA
CONFLICT (content): Merge conflict in bash/alx
As you can see, you have conflicts between two branches on the same file.
Your goal now is to resolve conflicts by using the version of the branch update_script, and push the result to the origin.
At the end, you should have all your work from the branch update_script (new file and two updated files) and all latest main commits (new files, delete folder, etc.), without conflicts.

6. Never push too much

Create a .gitignore file and define a rule to never push ~ files (generated by Emacs). 