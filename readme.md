### Manipulating files/directories
- learning to move files from local machine to the virtual machine 
- to do so we use the sink_files feature in vagrant

### Error handling 
- running the vm this morning returned the error that "the vm was created with a user that doesnt match the current user"
- check hidden files - using the command ls -a 
- remove .vagrant file

## Communications with developers - to understand requirements 
- what language is used to build the app
- what framework has been used - mvc, react(front-end) 
- what are the dependencies and which ones have been included and which ones are needed 
- what will the app look like 

## install dependencies on ruby 
- install bundler in root mode using sudo -i 
- exit sudo and run the command bundle to download and install dependencies 

## run the test rake test 
- gives you the instructions to pass all the test

enter the vm 
- sudo apt-get updates
- sudo apt-get install "package"
- sudo apt-get upgrade 
- systemctl status nginx (name of the program)

- go back to vm install node.js

- use curl to install packages that or not in a package directory 

- in order to install pm2 
- install nom first in sudo 

- npm package manager for node

### bash scripting 

- bash scripts can help us automate processes
.sh means it is an executable file 

chmod - change mode on linux bash - make files executable +x name_of_file
- syntax to make a file executable +x 
- to run the executable file:
./name_of_file 

## created an bash script which downloaded nginx again onto our device 
-#!/bin/bash
- sudo apt-get update
- sudo apt-get install nginx 
- sudo apt-get upgrade


## understanding how sinking works with vagrant 
- changes from the vagrant file affects the app in both the vm and local machine 

## more linux commands 

- "top" - shows all the programs running on the system 
- "ps" shows system information 
= "chmode" change mode 

### excercise - find out the linux permissions code to assign permission to files 

- chmod - modify access rights
- su - temporarily become the superuser
- sudo - temporarily become the superuser
- chown - change ownership
- chgrp - change a file's group ownership


- chmod +rwx filename - to add permissions
- chmod +rwx filename - to remove permissions
- chmod +x filename - to allow executable permissions 
- chmod -wx filename - to take out write and executable permissions

### how to change permissions in numeric code 
- 0 = no permission
- 1 = execute 
- 2 = write
- 3 = read 


- 777 - no restrictions on permissions, anybody can do anything











