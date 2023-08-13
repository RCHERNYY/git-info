# GIT documentation
This is the summary of git functionality known till date.
## git operations
- **git iniit** - initialize repo
- **git add** - add files to be tracked
- **git commit** - *commit* the changes to repo
- **git push** - *copy* the changes from local to remote repo
## GitHub 
GitHub helps manage remote repos located on local machines that streamlines distributed development.<br>
*Work with Github* requires the following:
1. Github account
2. SSH keys pair to be able to work with remote repo by SSH
3. Basic knowledge of git
## Advanced features
Not known till the date.
## Git: status of files
There are several possible statuses of a file in git: <br>
- Untracked
- Modified 
- Tracked
- Staged
The file goes from one status to another and this is pre-defined status flow in git: <br>
```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "git committed"     --> tracked/comitted;
```
