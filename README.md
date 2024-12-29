# Chill devs learning and working together to be the best

## 1. Essential Git commands

_By [codeschris](https://github.com/codeschris)_

- **git init**: initialize a repository to be pushed to GitHub
- **git add _project-file_**: stage files to be committed
- **git commit**:
  - (-m "commit message"): commit changes with a small message
  - _leave blank_: commit changes with a detailed message
- **git branch**:
  - (-M branch_name): renaming a branch
  - _leave blank_: checking branches available in the repo
- **git remote add origin _https://-url-of-the-project_**: connecting your origin (project in Git) to remote (local project)
- **git push**:
  - (-u origin branch_name): pushing to a new branch in origin
  - _leave blank_: pushing to existing branch in origin
- **git pull**:
  - _leave blank_: Pull new changes to your local repo
  - (--allow-unrelated-histories): Allow unrelated histories from a branch that isn't connected/pulling from upstream
