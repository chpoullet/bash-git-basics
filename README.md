# Bash Basics

## Bash is a terminal window. It emulates a Linux environment. DevOps works on Linux environments. Bash is a language.

pwd = print working directory (where am I?)

ls = list short (where can I go?) - lists everything in the current directory
ll = list long - more detailed list (date/time etc)

mkdir = make directory (create a location) - creates a folder

cd code = change directory to code

ls -a = will list everything (including hidden files - hidden file will usually begin with .)

touch = create FILES (touch example.txt --- will create a file called example.txt)

cd .. = go back one

rm = removes files (rm example.txt)

rm -r = remove folders (remove recursive)

cat = prints what is inside a file (for txts it will print the text inside)


There are two absolute locations.  ~ = beginning of user directory.   /  = root directory



# Git Basics

echo ‘hello’ > example.txt = inputs hello into example.txt

git init = creates a master directory for where you want your repository to be and be tracked

git status = info about the repository 

to remove the git just do --->           rm -rf .git

git add . = will add everything to be tracked

git commit -m “message” = git commit will save changes to your local repository. -m leaves a description to portray what you did.

git log = portrays all previous edits and inputs in the repository

git checkout <sha key> = checks out that specific commit, so you can look through the history of what was added etc.

git checkout master = most up to date commit



# GitHub Basics

## The cloud for Git. Allows other people to pull changes and push commits.

git remote add origin https://github.com/chpoullet/bash-git-github-eng53.git

git push -u origin master = pushes the master onto github

git push <remote repo> <branch> (git push origin master)
  
git remote --v = shows the fetch and push



# Bash (various commands)

head file = display the first 10 lines of a file (useful if you dont want it to print out a massive txt file)

ps = display currently running processes

kill pid = kill process with process ID

Cheat sheet: https://www.linuxtrainingacademy.com/linux-commands-cheat-sheet/

