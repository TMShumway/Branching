## Git Cheat Sheet

Brief reference if various git commands. Also practice wit git branching


* 'git init' - Initialize a local git repo in working directory
* 'git status' - Show state of local repo
* 'git log' - Log commit history
* 'git log --oneline' - Compact commit history
* 'git commit -l' -
* 'git commit -m "msg"' - Commit work to local repo with commit message "msg"'
* 'git diff sha' - Show diffs between current commit and commit id 'sha'
* 'git diff oneBranch otherBranch' - Show diffs between 'oneBranch' and 'otherBranch'

### Branching
* 'git branch' - list local branches
* 'git branch newBranch' - create local branch newBranch
* 'git checkout newBranch' -

### Remote Repos
=* 'git remote add alias url' - add 'alias' as name for remote repo 'url' in project configuration
* 'git push alias aBranch' - push local commits to remote repo 'alias''s branch 'aBranch'
* 'git pull alias aBranch' - pull remote 'aBranch' from 'alas' into current local branches
