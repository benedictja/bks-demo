
Manual mirroring in git

Add the remote repo with 

$ git remote add upstream https://github.com/user/repo

then pull its contents with

$ git pull upstream master

finally push the changes to the mirror with

$ git push origin master
