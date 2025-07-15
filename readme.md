# Git and Github 

Why Git matters:

Whether you're building solo projects or collaborating in large teams, Git ensures you never lose track of your progress. It’s the lifeline for clean, efficient, and recoverable code.

 Key Takeaways from my Git Learning:

Version control is not just backup it’s about structured collaboration

 Branching lets you experiment without fear

 Commit messages matter more than we think (communicate clearly!)

Tools like GitHub/GitLab amplify teamwork

Learning the CLI (Command Line Interface) is empowering

From git init to merge conflicts, the journey has made me more confident in managing codebases the right way.

## Here are the basic git commands you need as well as some procedures. 

Basic commands : 

Git add {filename}
##setup for commit

Git init {filename}
#Creates  local repository.

Git commit -m {message}
#commit

Git log 
#history 

Git checkout {state}
#past state  or specified state.

Git checkout {branchname}
#jumps to that branch

Git clone {https}
#clone  a repo	as a local repository.

Git push -u origin main {branch name}
#Pushes current head state to GitHub repo referenced from origin. 
Git pull origin  {branch}
#Pulls  git branch specified to local branch.

Git remote add origin {repo link} 
#Adds  remote repo. 
Origin is the remote repo name. 

Git branch {branch name}
#Creates new branch 

Git branch {new branch-name} {source branch name} 
#Creates new branch from specified branch 
 

Git push —set-upstream origin {branch-name}
#Pushes new branch to repo 

Pull request will merge 2 branches. 
 Git merge main{branch name} 
#Merges branch to current local branch. 

Merge conflict : 

1. Pull the current main branch to local main branch. 
2. Merge it local branch that had to be merged. 
3. Resolve the merge conflicts.


Advanced Git : 

Git reset —soft {git hash} , 
Stages the changes made after the specified commit.

Mixed reset , default moves to working directory without	staging them. 

— hard , deletes the further code. 
#reset 


Git revert {hash} , does not delete logs further unlike	reset. But moves the point to previous place. 
Git revert —continue finishes it. 
#revert 

Git stash
#saves the current uncommitted code.

Git stash list \

Git apply stash@{stash number}  
