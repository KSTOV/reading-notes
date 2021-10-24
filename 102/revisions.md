# Revisions and the cloud

- Version control allows you to revisit different versions of a file by saving the changes and makes it easy to revert back to previous versions.
- Local Version Control: database on your hard disk that stores changes to files
- Central Version Control: Single server storing all changes and file versions which can be accessed by various clients. Knowledge of team memebers activities with certain files     and gives admins more control over divvying ip revision privileges
- Distributed Version Control: Adresses the vulnerability of the CVS. DVCS allows clients to create mirrores repos and the backups can be easily be placed on the server if           information is lost. Programmers working in teams can collaborate with each other in various ways to complete a joint project


## Commands

- git clone repoURL/SSH
- git status = state of files
- git add filename 
  git add * = all files
- git commit -m "message"
- git commit -a = commit all changes
- git push origin master = push changes
- git stash = temporarily removes changes and hides them, when ready to continue working on changes use "git stash apply"



