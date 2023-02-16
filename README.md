# gitcheatsheet

## Useful Tips
- Do not use space in naming files and branches
- 
## Useful Commands

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
