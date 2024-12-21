# git-learner

### Basics

- `git status`
- `git add .` or  `git add <file_name>`
- `git commit -a -m'<commit_text>'`
- `git push`


### Logs
- `git log`
- `git log -3` shows last 3 commit

- `git log --pretty=oneline`
- `git log --format:"%h - %an, %ar : %s"`

> 614edb4 - Mamuka, 12 minutes ago : ISSUE-00 update readme file

- `git log --graph`


### Revert changes
+ From before Staged
    * `git checkout  .`
    * `git checkout -- <file_name>`

+ From Staged
    + `git reset HEAD .`
    + `git reset HEAD <file_name>`


### Visual Tools
- `gitk`


### Tag
- `git tag -l '<some_text>*`
> Returns all Tags that starting with some_text

- `git push origin <tag_name>` or `git push origin --tags`


### Remote
- `git remote show origin`
- `git remote -v`
- `git fetch <remote_name>`
- `git push remote master`


### Branches
- `git branch`
- `git branch <branch_name>`
- `git checkout <branch_name>`
- `git checkout -b <branch_name>`
- `git branch --merged` or `--no-merged`
- `git branch -d <branch_name>` or `git branch -D <branch_name>`


### Aliases
- `git config --global alias.<alias_name> <comand_name>`


### Merge
> Merge <branch_name> into master
- `git checkout master` 
- `git merge <branch_name>`
> After fix conflicts
- `git add .`


