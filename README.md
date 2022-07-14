# Ansible script 

This repo is dedicated to Ansible automation learning.
At the moment, it contains a script to automate update, package installation, and disable ssh in a remote host. 

# How to set up SSH key login 

1. First, create a SSH key by typing <br> `$ ssh-keygen -o -a 100 -t ed25519 -f ~/.ssh/yourprojectdirectory -C email@gmail com`
2. `$ ssh-copy-id -i ~/.ssh/yourprojectdirectory hostusername@hostip` (i.e. root@192.168.1.10)
3. Finally, to test if SSH login is working just type <br>`$ ssh -i ~/.ssh/yourprojectdirectory hostusername@hostip`
