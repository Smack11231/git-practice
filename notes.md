Very first time you use a new computer
--------------------------------------
run two commands to tell git that you are you (after you've installed git)
    mac - terminal - click ok when it asks you to download

    git config --global user.name "Mackenzie Smith"
    git config --global user.email "smack11231@gmail.com"

Setting up a new project (repository, folder)
--------------------------------------

    git init (initialize)

When you want to check which step you are on:
--------------------------------------

    git status

Three step commit process:
--------------------------------------

* Make saved and tested changes to my code, (usually) get it completely working
* Add any changed files to the stage
    git add filename.rb
* Commit the staged files
    git commmit -m "Descriptive commit message to myself and others"


How `git push` and `git pull` work
-----------

* git push - pushes the file updates that were stored in the 'commit' to the online repository
* git pull - when transfering to a new computer or pulling from a different account, this command will pull the git push updates into your files.