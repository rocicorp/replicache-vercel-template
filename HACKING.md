# Pulling changes from replicache-todo

This repo is forked from https://github.com/rocicorp/replicache-todo and most changes to the code will happen there.

To pull changes:

```bash
# Only need to do this once
git remote add upstream git@github.com:rocicorp/replicache-todo.git
git pull upstream

# Make sure to ignore changes to README.md
git merge upstream/main
```
