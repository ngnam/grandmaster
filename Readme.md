# Master Read file
## Open Terminal.app 
create project parent folder "grandmaster", and a subfolder for the "master" branch. Initialise a new git repository for the project and push the "master" branch to GitHub.

* ichris:Sites $ mkdir grandmaster
* ichris:Sites $ cd grandmaster/
* ichris:grandmaster $ mkdir master
* ichris:grandmaster $ cd master/
* ichris:master $ git init
* ichris:master $ echo "# Master README file" > README.markdown
* ichris:master $ git add .
* ichris:master $ git commit -m "Master README added"
* ichris:master $ git remote add origin git@github.com:chrisjacob/grandmaster.git
* ichris:master $ git push origin master

## Refresh your projects "master" branch page on GitHub to see the committed files

## Back in Terminal.app, 
change directory back to the parent folder, setup a "gh-pages" subfolder for your "gh-pages" branch and change directory into it.	

