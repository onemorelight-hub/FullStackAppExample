## Some Global Configuration for Git

Open a cmd window or terminal on your computer.

### Check to make sure that Git is installed and available on the command line, by typing the following at the command prompt:

git --version

### To configure your user name to be used by Git, type the following at the prompt:
git config --global user.name "Your Name"

### To configure your email to be used by Git, type the following at the prompt:

git config --global user.email <your email address>

### You can check your default Git global configuration, you can type the following at the prompt:

git config --list

### Initializing the folder as a Git repository

git init

### Checking your Git repository status

git status

### Adding files to the staging area

git add .

### Commiting to the Git repository

git commit -m "first commit"

### Checking the log of Git commits

git log --oneline

### Resetting the Git repository

##### To discard the effect of the previous operation and restore index.html to its state at the end of the third commit, type:

git reset HEAD index.html

##### Then type the following at the prompt:

git checkout -- <file_name>

You can also use git reset to reset the staging area to the last commit without disturbing the working directory.

### Git Docs : 
https://git-scm.com/docs



