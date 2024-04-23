# SSH

## Learning Objectives
* We are expected at the end of this project to fully grasp the concept a server: 
* where servers live;
* what SSh is;
* How to create an SSH RSA key pair;
* How to connect to remote host using an SSh RSA key pair;
* Know the advantage of using #!/usr/bin/env bash instead of /bin/bash

## Tasks
0. Write a Bash script that uses ssh to connect to your server using the private key ~/.ssh/school with the user ubuntu.
	* Only use ssh single-character flags
	* You cannot use -l
	* You do not need to handle the case of a private key protected by a passphrase
1. Write a Bash script that creates an RSA key pair.
2. Your machine has an SSH configuration file for the local SSH client, let’s configure it to our needs so that you can connect to a server without typing a password. Share your SSH client configuration in your answer file.
3. Add the SSH public key below to your server so that we can connect using the ubuntu user.
