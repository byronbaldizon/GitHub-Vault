# GitHub-JUNKYARD
##  Init
    git init
##  Add
    git add .
##  Commit
    git commit -m "Comment"    
## Create a new repository on the command line
    echo "# GIT-JUNKYARD" >> README.md
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/<github-user-name>/<name-of-repository>.git
    git push -u origin main

## Push an existing repository from command line
    git remote add origin https://github.com/<github-user-name>/<name-of-repository>.git
    git branch -M main
    git push -u origin main
## React bare minimum
    //let's clone the repository
    git clone --single-branch -b <name of app> http://<github.com/johndoe/myrepository.git .>
    //now, install dependencies
    npm install    
