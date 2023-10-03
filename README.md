# ICICI
After ICICI directory creation:
create filename.html i.e., vi login.html
Give some piece of code based on requirements, save and exit
To check git is installed or not > which git
install git> yum install git
Confimation on git installation > which git
Configure the git means to track the changes > git config --list; git config --user.name=GouthamiGR; git.config --user.email=gorrelagouthami@gmail.com
Initilize git > git init
Check the status of git > git status
Created login file will be in workspace > Need to add the file to index area > git add <file-name or login.html> #This is to add particular file to index area (or) git add . #This is to add all the files to index area
Commit the file to local repository> git commit -m '<give some message like adding file from index area to local repository (master) from instance>' //git commit -m 'adding file from index area to local repository (master) from instance'
Commit ID gets generated, to check commit ID> git log
Add the file to establish the connection with Github's master > git remote add origin https://github.com/GouthamiGR/ICICI.git #Adding the path origin, in which we can use 'origin' instead of using entire path
Pushing the ICICI master branch to github> git push origin master 
Asks for Username and Password.
