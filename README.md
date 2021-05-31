#2021-05-27 GIT

- `init`: initialize git repo in current location
- `git status`: gives you the status
- `git add <FILE>`: adds <FILE> to the staging area
- `git commit`: commit files from staging area 
	- `git commit -m "MESSAGE`: Commit without opening nano editor
- `git log`: show you history of commit
	- `git log --oneline`: oneline commit history
- `git diff`: gives you the difference
	-`git diff --staged`: diff files in the staging area
- `git diff HEAD~2`: diff 2 commits ago
- `git diff <SHA> <FILE>`: diff a file against a specific commit
- `git checkout <SHA> <FILE>`: revert <FILE> from <SHA> to curr
- `git checkout <SHA>`: move you to <SHA>
	- `git checkout main`: go back to main starting point
- `.gitignore`: file that pattern matches files to ignore
- `.gitkeep`: convention to keep an empty folder

## REMOTES

- `git remote add <NAME> <URL>`: <NAME=origin> point to the rem
- `git push <WHERE> <WHAT>`: local repo -> remote
- `git pull <WHERE> <WHAT>`: remote -> local
