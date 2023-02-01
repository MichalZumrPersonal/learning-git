# learning-git
This PUBLIC repository is used for learning git.


Git and GitHub Tutorial For Beginners | Full Course [2021] [NEW]



git config --global user.name "Michal Zumr"	Set my name
git config --global user.email "zumrmich@gmail.com"	Set my email
git config --global color.ui auto	Set Colorfull output

Git --config	List of options
Git config --list	List of configuration

cd Desktop	Change directory
cd -	Get back to previous directory
Mkdir learning-git	Create a folder named learning-git
git init . 	initialize a git repository
ls -a	?show all?
rm -rf .git	Delete git repository
git add .	Add all to staging area

// "." means current directory

touch index.html	Create index.html file in repository
ls	Show content of the repository
git status	Show status (directory/staging area)
git add index.html	Add  index.html file to staging area
git rm --cached index.html	Remove index.html file from staging area
Git add .	Add all files downwards ("." means everything)
git rm -r --cached .	remove all files downwards ("." means everything)
git add -A	Add everything from main directory

Added to staging area

Not added to staging area
(still in a directory)

Git add .	Add all files downwards ("." means everything)

git add -A	Add everything from main directory

git commit -m "bootstrap project"	Create a commit with message "bootstrap project"
Git log	Show all commited commits 
Git show hashcode	Show specfic commit details using unique hash
Cat index.js	Show changes in index.js file
Git diff	Show made differences between current working directory and the commit
Git restore index.js	Discard changes in index.js file

Git commit --amend -m "added body in main.css"	Edit commit message
	

https://github.com/MichalZumrPersonal




git remote add origin git@github.com:MichalZumrPersonal/learning-git.git	Connect to github repository
git branch -M main	Rename main branch from master to main
git push -u origin main	Action  Faild (need to set up acces rights in github)




Follow this guide: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent

Login:

Email: zumrmich@gmail.com

Passphrase: prmwEsxJbpkL49jp3JMx

Your identification has been saved in /c/Users/zumrm/.ssh/id_ed25519
Your public key has been saved in /c/Users/zumrm/.ssh/id_ed25519.pub
The key fingerprint is:
SHA256:poKLGVD//56Jj/ClNb3gveqc6M/lo3KIN5e3dEWVkZ4 zumrmich@gmail.com
The key's randomart image is:
+--[ED25519 256]--+
|               .=|
|               o.|
|  .           . o|
| . .           E |
|.   .   S       .|
|.  . . o   .   . |
|. . . +. .=.+ .  |
| + . ..+=@+@oo   |
|o .    oO@/+*+   |
+----[SHA256]-----+

Agent pid 1645

https://stackoverflow.com/questions/18710120/the-authenticity-of-host-github-com-192-30-252-128-cant-be-established
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/githubs-ssh-key-fingerprints

Vi main.py --->  i (for INSERT) -------> (write some code) ------>  (press esc) -------> (:wq)	Create a new file named main.py and write some code init withou opening text editor.
	

git pull	Pull changes from github repository
	

Git branch	Check current branch
Git branch -a	Show list of braches
Git branch -r	Show current branch
Git branch feature-a	Create new branch named feature-a
Git checkout feature-a	Switch to branch named feature-a
Git checkout -	Switch to previos branch
Git push ----> git push --set-upstream origin feature-a	Push new branch to github
Git push -u origin feature-a	Push new branch to github
Git checkout -b to-delete	Create and swith into new branch named to-delete

Git pull 

Git merge feature-a	Merge feature-a branch to main branch
Git branch -d new-branch	Delete new-branch also in remote server
Git log --oneline	It gives you a better syntax of commit historycs

Git pull -r origin main	Pull changes from main branch to current another branch?
Git rebase --continue	
Git push -f	F is for force push

Quick setup — if you’ve done this kind of thing before
 Set up in Desktop
or
HTTPSSSH

Get started by creating a new file or uploading an existing file. We recommend every repository include a README, LICENSE, and .gitignore.
…or create a new repository on the command line
echo "# JavaScript-learning" >> README.mdgit initgit add README.mdgit commit -m "first commit"git branch -M maingit remote add origin https://github.com/MichalZumrPersonal/JavaScript-learning.gitgit push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/MichalZumrPersonal/JavaScript-learning.gitgit branch -M maingit push -u origin main
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
Import code

From <https://github.com/MichalZumrPersonal/JavaScript-learning> 

![image](https://user-images.githubusercontent.com/115942443/216161397-b599d0d5-3dd3-4a88-b65a-3c51d4c7c833.png)
