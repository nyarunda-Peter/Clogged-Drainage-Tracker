# Clogged-Drainage-Tracker
This is an open source solution to clogged open drainage channels by Andela's GADS (Google Africa Developer Scholarship) Climate-Team 7.

Contributing Process:

credits:
https://www.dataschool.io/how-to-contribute-on-github/

Fork the project repository
Clone your fork to your local machine:
  1. git clone URL_OF_FORK
Check that your fork is the "origin" remote : 
  1. check if the remote exists :git remote -v
  2. if missing create the remote :git remote add origin URL_OF_FORK
Add the project repository as the "upstream" remote:
  1. git remote add upstream https://github.com/nyarunda-Peter/Clogged-Drainage-Tracker.git
  2. check remotes: you should have two remotes [origin and upstream]
Pull the latest changes from upstream into your local repository
  1. git pull upstream development
Create a new branch
  1. create branch: git checkout -b BRANCH_NAME (Branch name should be named in the format : ISSUE NUMBER i.e documentation#001)
  2. check available branches: git branch
Make changes in your local repository
Commit your changes
  1. git add -A
  2. git commit -m "DESCRIPTION OF CHANGES"
Push your changes to your fork
  1. git push origin BRANCH_NAME
Begin the pull request to upstream repository's development branch
Create the pull request
