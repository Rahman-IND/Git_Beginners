>>Getting started with git:

-install git from 			=	https://git-scm.com/
-open terminal in windows		=	windows button > type: terminal
-To see all the git commands		=	git
-To see configuration of git		=	git config -l
-To see all git configuration		=	git config -l --show-origin
-To config. user name in git		=	git config --global user.name "First Last Name"
-To config. user email in git		=	git config --global user.email "emailid@xyz.com"
-To see global configuration of git	=	git config -l --global

>>Getting started with Terminal:

-To goto the required directory					= 	cd path
-To create folder 						= 	mkdir filename
-To open the current Directory in File Expolrer			=	expolrer .
-To make it git repository 					= 	git inti
-To check the current file status				=	git status
-To create/open a file	in notepad				=	notepad filename.exe
-To add file to staging area in git				=	git add .  | git add filename.exe
-To commit a file in git 					=	git commit -m "comment/message"
-To see differences in a file					=	git diff filename.exe
-To see all differences of the working directory		=	git diff
-To see differences btw staging and repository			=	git diff --staged
-To exit git editor 						=	:q
-To change default git editor					=	git config --global core.editor notepad
-To see all commit history					=	git log
-To see all commit history in oneline				=	git log --pretty=oneline
-To see certain commit and its file status during that time	=	git checkout <commit id>

>>Getting started with Git-ignore file instructions:

-To create git ignore file		=	R_click > New > Text Document > rename onSpot as .gitignore
-To add files in Gitignore file		=	L_Dou_click Open .gitignore > Add comment using # and in next line use filename.exe that want to ignore.

>>Getting started with Branch:

-To create new branch in git						=	git branch <feature/branchname>
-To check different branches in git					=	git branch
-To switch between branches in git					=	git checkout <branchname>
-To merge a branch to main branch					=	git merge <branchname>
-To delete an existing branch						=	git branch -d <branchname>
-To see history of commit with merge in graph				=	git log --pretty=oneline --graph
-To see all the branches along remote branches				=	git branch -a

>>Getting started with Github:

-To add remote repository to git 					=	git remote add origin <SSH:url>
-To see added remote repository						=	git remote
-To see Fatch and Push url						=	git remote -v  | git remote show origin
-To push file in main repository					=	git push   |	git push -u origin main
-To clone a git repository in existing folder				=	git clone "SSH:url" .
-To clone a git repository with it's own folder name			=	git clone "SSH:url"
-To pull a file from remote repository					=	git pull   |	git pull origin main
-To fetch updates from remote repository				=	git fetch  |	git fetch origin main
-To push an update with different branch to the remote repository	=	git push origin <branchname>
-To fetch+merge we use 							=	git pull