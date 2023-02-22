# Gitcheatsheet


### Acyclicity Nature

The Git Commit history is a Directed Acyclic Graph （"DAG"), where the commits form the nodes and the pointers to the parents from the edges.  The acyclicity property ensures the commit history is well-defined and cannot contain cycles or loops, where parents do not point back to their children



## What is a commit

A commit is a pointer to the location insider the .git folder where Git has stored your changes. Commit object

### Three stages of Git

## Proposed workflow
# Insert proposed workflow. 



## Useful Tips
- Do not use space in naming files and branches
- Do not use Git Pull
- Do not use reset

- 
## Useful Commands
- use git branch, git stauts to check open

### Safe commands

| Command                           | Description                                                                                       |
| --------------------------------- | ------------------------------------------------------------------------------------------------- |
| `git status`                      | asks the repository for information to display and in no way affects the repository               |
| `git log --graph --oneline --all` |   useful command to view commit history in a DAG format, especially when learning git or visualisation tools such as GitLens and SourceTree are not available                                                                                             |
| `git diff`       | Shows the differences between your working directory and the last commit. |
| `git diff --cached`       | Shows the differences between your staging area and the last commit. |
| `git diff --cached`       | Shows the differences between your staging area and the last commit. |
| `git diff <commit / branch> <commit / branch>`       | (Note: should input 2 parameters and be specific) Shows the differences between two specified commits or two specified branches. |
| git branch                        | Lists all the local branches in your repository.                                                  |
| `git branch -r `                    | Lists all the remote branches in your repository.                                                 |
| `git branch -a `                    | Lists all the local and remote branches in your repository.                                       |
| `git checkout <branch> `            | Switches to the specified branch.                                                                 |
| `git checkout -b <branch>`          | Creates a new branch and switches to it.                                                          |
| `git fetch`                         | Downloads new commits from the remote repository, but does not merge them into your local branch. |
| `git merge <branch>`                | Merges the specified branch into your current branch.                                             |
| `git rebase <branch>`               | Replays your commits on top of the specified branch.                                              |
| `git remote -v `                    | Shows a list of all the remote repositories associated with your local repository.                |
| `git show <commit> `                | Shows the details of the specified commit.                                                        |
