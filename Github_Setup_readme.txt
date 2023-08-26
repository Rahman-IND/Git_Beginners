>>Local Computer in Git Bash

Step:1

-Open Git Bash
-Configure git file			= git config --global user.name "username"
					  git config --global user.email "email"

-To see git config in bash		= git config --list  | git config --list --show-origin

Step:2

-To create ssh Key			= ssh-keygen -t ed25519 -C "your_email@example.com"
-Find the keys				= cd .shh > dir
-To print the "key.pub"			= cat "keyname.pub"	>>	<copy the message>
-To Run	ssh-agent			= eval "$(ssh-agent -s)"
-To add Identity Run			= ssh-add ~/.ssh/"keyname"

>>Web Github Account

-Goto Account > Settings > SSH and GPG keys
-Select = generating SSH key > Generating a new SSH key and adding it to the ssh-agent
-Follow Step:2 Local Computer > then 
-Again Goto Account > Settings > SSH and GPG keys > New SSH key > Add SSH key
