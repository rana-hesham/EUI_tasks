# EUI_tasks
Tasks in DEPI_EUI

To clone repo from github to local repo (server)

first we should create a ssh key then add it to github account.

how to create ssh key
In your linux machine
- mkdir .ssh
- ssh-keygen -t ed25519 -N '' -f .ssh/rsa
- eval "$(ssh-agent -s)"
- ssh-add .ssh/rsa
then add the public key to github account

Now we can clone the repo using ssh way 
- git clone git@github.com:rana-hesham/EUI_tasks.git

If we did any changes locally and want to push it to github

- git add .
- git commit -m "first commit"
- git push -u origin / git push origin master
