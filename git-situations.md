# Revert to a previous state

    git reflog

__*1. Gives a list of previous states;*__

__*2. Indexes of form HEAD@{id};*__

    git reset HEAD@{id}

__*1. Resets the env to a previous state;*__


# Make a small change after commit

    git add .
    git commit --amend --no-edit


# Change the message of the last commit

    git commit --amend


# Move the last commit on a new branch

    git branch branch-name
    git reset HEAD~ --hard
    git checkout branch-name


# Commit to other branch instead

    git reset HEAD~ --soft
    git stash
    git checkout branch-name
    git stash pop
    git add .
    git commit -m "Commit message here"


# Revert a commit 

    git log
    git revert [saved hash]


# Reset the repo to the state of the remote one

    git fetch origin
    git checkout master
    git reset --hard origin/master
    git clean -d --force