# git-learner

#### Basics

- `git status`
- `git add .` or  `git add <file_name>`
- `git commit -a -m'<commit_text>'`
- `git push`

### Logs
- `git log`
- `git log -3` shows last 3 commit

- `git log --pretty=oneline`
- `git log --format:"%h - %an, %ar : %s"`

> 614edb4 - Mamuka, 12 minutes ago : delete


- `git log --graph`


### Revert changes
+ From before Staged
    * `git checkout  .`
    * `git checkout -- <file_name>`

+ From Staged
    + `git reset HEAD .`
    + `git reset HEAD <file_name>`
