
## Git Commands
- git init
- git status (Status of current repo)
- git log (The command executed till now)
- git . (Add current dir)
- git commit -m "message" (add to staging area -m: message)
- git restore --staged (restore from staging area)
- git remote add origin "repo link" (orging: remote & with the link one can make connection)
- git push -u origin main (local repo:main remote repo: origin & pushing the dir from main to origin i.e. local to remote)
- git clone
- git push
- git switch -(To go to prev working dir)
- git reflog (git history)
- git remote -v (which upstream /origin is connected)
- git remote set-url origin(or upstream name) link
- git switch -c branchName
- git switch branchName
- git branch (list branches)
- git branch -a (list with hidden branch)
- git branch -d branchName

## Notes
- empty folders can not be pushed to remote. It must have file/folder
- Best practice is to have .gitignore at the start of project. if it is created later then the file needs to be ignore must be deleted
- git pull = fetch + merge (pulling it from remote repo to local .git & then merge into local dir)
