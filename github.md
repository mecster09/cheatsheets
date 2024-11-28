# GitHub Commands Cheatsheet

## **Git Basics**
| **Command**                     | **Description**                                 |
|---------------------------------|------------------------------------------------|
| `git init`                      | Initialize a new Git repository in your project folder. |
| `git clone <url>`               | Copy a repository from GitHub to your computer. |
| `git status`                    | Show the status of your files (changes, staged, etc.). |
| `git add <file>`                | Stage a file for the next commit. |
| `git add .`                     | Stage all files in the folder for the next commit. |
| `git commit -m "message"`       | Save your changes with a message describing them. |
| `git log`                       | View the commit history of the repository. |

---

## **Working with Branches**
| **Command**                     | **Description**                                 |
|---------------------------------|------------------------------------------------|
| `git branch`                    | List all branches in your repository. |
| `git branch <branch-name>`      | Create a new branch. |
| `git checkout <branch-name>`    | Switch to another branch. |
| `git checkout -b <branch-name>` | Create and switch to a new branch. |
| `git merge <branch-name>`       | Merge changes from another branch into the current branch. |
| `git branch -d <branch-name>`   | Delete a branch. |

---

## **Connecting to GitHub**
| **Command**                     | **Description**                                 |
|---------------------------------|------------------------------------------------|
| `git remote add origin <url>`   | Connect your local repo to a GitHub repository. |
| `git remote -v`                 | Check the URLs of the remote repositories. |
| `git push -u origin <branch>`   | Push changes to a specific branch on GitHub for the first time. |
| `git push`                      | Push your committed changes to GitHub. |
| `git pull`                      | Fetch and merge changes from GitHub to your local repo. |
| `git fetch`                     | Download changes from GitHub without merging. |

---

## **Handling Changes**
| **Command**                     | **Description**                                 |
|---------------------------------|------------------------------------------------|
| `git diff`                      | Show differences between your files and the last commit. |
| `git reset <file>`              | Unstage a file you added. |
| `git reset --hard`              | Undo all changes and go back to the last commit. |
| `git stash`                     | Save changes you’re not ready to commit. |
| `git stash pop`                 | Reapply stashed changes. |

---

## **Resolving Issues**
| **Command**                     | **Description**                                 |
|---------------------------------|------------------------------------------------|
| `git rm <file>`                 | Remove a file from Git and your filesystem. |
| `git mv <old-name> <new-name>`  | Rename or move a file. |
| `git log --oneline`             | View a compact commit history. |
| `git revert <commit-hash>`      | Undo a specific commit without losing history. |
| `git cherry-pick <commit-hash>` | Apply a specific commit to the current branch. |

---

## **Advanced Commands**
| **Command**                     | **Description**                                 |
|---------------------------------|------------------------------------------------|
| `git tag <tag-name>`            | Create a tag for a specific commit. |
| `git rebase <branch-name>`      | Reapply commits on top of another base branch. |
| `git clean -f`                  | Remove untracked files. |
| `git blame <file>`              | Show who last modified each line in a file. |

---

## **Tips**
- Always **commit your changes** before pulling or merging to avoid conflicts.
- Use `git help <command>` to get more information about a specific command.
