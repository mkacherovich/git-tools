# git-tools

A collection of helpful git commands.


## Usage
Add git-tools/bin to your path. When you type

   `git my-custom-command --some options and arguments`

git will try to run `git-my-custom-command` executable anywhere in your path

### archive-branch
Archives a remote branch. This is done by tagging the branch as `archive/branch_name` and then deleting it from the remote repo.

Usage: `git archive mybranch'

