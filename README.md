# Camiel_github_tutorial
- This is a tutorial on git hub 

- Make a repository on git hub

- copy and paste the url in terminal with
git clone 

e.g.

- git clone https://github.com/kepoff/Camiel_github_tutorial.git

- change working directory to where the scripts are

- change scripts and then save them locally

- use "git status" to see what changed

- use "git commit -a -m" if you use -m than you need to write a message. -a means all the files will be committed 

- use "git push" to publish on git hub and input username and password


- To add another file, we can use "git status", followed by "git add filename.md"

- Then git commit -a -m "message" then git push

# To add a directory from your computer to GitHub

- Change directory to the folder/folders/files you want to push

e.g. Kirstens-MacBook-Pro:Deep_Trap_project poff$ cd /Users/poff/Documents/Fall_2018_coursework/

- Use git init to create a strange "repository" called .git

e.g. Kirstens-MacBook-Pro:Fall_2018_coursework poff$ git init

- Use git add to add all files you want to commit

e.g. Kirstens-MacBook-Pro:Fall_2018_coursework poff$ git add /Users/poff/Documents/Fall_2018_coursework/

- Use git status to check if all your files will be pushed

e.g. Kirstens-MacBook-Pro:Fall_2018_coursework poff$ git status

- se git commit -a -m to see what is committed

e.g. Kirstens-MacBook-Pro:Fall_2018_coursework poff$ git commit -a -m all_fall_2018_coursework

- Go to GitHub and create a repository that this will all be pushed to and copy URL

- Use git remote add origin "URL"

e.g. Kirstens-MacBook-Pro:Fall_2018_coursework poff$ git remote add origin https://github.com/kepoff/Coursework_fall_2

-Use git push -u origin master to push all into GitHub repository

e.g. Kirstens-MacBook-Pro:Fall_2018_coursework poff$ git push -u origin master

