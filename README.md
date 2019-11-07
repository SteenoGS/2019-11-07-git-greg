# Git Workshop DCR -- 11/2019

Workshop Command Line Notes 

## Local

- `init`: initialize folder as git repository (repo)
- `status`: see what is going on in the repo
- `add`: add a file or files to the staging area to go from one commit, C(x), to the next C(x+1)
- `commit`: take a file or files from staging area to new commit, C(x+1) (the snapshot)
- `diff`: look and highlight differences between commits
- `HEAD`: Where you are currently looking at
- `checkout`: move your head around to different states
- `log`: looking at all your previous messages
  - `log --oneline`: one line of your history

## Remotes

- `ssh-keygen`: to create ssh keys
  - `cd ~/.ssh` and copy the `ids_rsa.pub` file (look for online education)
  
- `remote`: somewhere your git repo is stored (e.g., Github)
  - `origin`: the default you give your remote
- `push`: sending local changes to remote
- `pull`: receiving remotes changes to local
  
## Branches

- `git branch <branch name>` create a new branch
  - `checkout <branch name>` move to that branch
  - `checkout <branch name> -b` create and move to branch
- `git branch -a` see what branches we have
- `git log --oneline --decorate --graph --all` all of the changes / branches
- `git checkout master` (need to do this to get back to master branch)
- `git pull original master` (need to pull down remote from pull request)
- `git fetch --prune`:
- `git branch -d my_branch`:
- `git branch -d`: delete branch that was merged
- `git branch D`: for delete a branch that was not merged

- `$ cd output/ > $ touch .gitkeep`: giving folder an empty file to make visible


## Updating history

- `rebase <branch_name>`: incorporate changes in <branch_name>, for example `master` into current branch, e.g., `project_template`
  - you perform this command  on the feature branch, no on the `master`

# Cloning
You can clone something from the Git Website


# Sabrina is COOL!!!





