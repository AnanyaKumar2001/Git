
### ----------------main----------------------

- git init
- ls -a
- git status
- git add abc.txt
- git commit -m "first commit"
- git log
### 
- git add .
- git diff abc.txt
- git checkout abc.txt


### --------------remote------------------------

- git remote add origin https://.......git
- git push -u origin master
### 
- git remote -v
- git push origin master


### -------------remove-exclude------------------

- touch .gitignore
- ls -a
- open .gitignore
- git init
- git add .
- git status
### 
- git rm --cached -r .
### 
/*write the file names line by line in gitignore file to exclude them in git init*/


### ------------clone------------------------------

- git clone https://...........git
- git log


### -----------branch------------------------------

- git branch alien-plot
- git branch
### 
- git checkout alien-plot
- git log
###
- git checkout master
- git merge alien-plot
- git push origin master -u
