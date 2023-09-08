# Git-Commands
### Commonly used Git Commands
---
## *Basic Git Commands*


### Setting up Your Git Identity
| Command           | Description                               |  Example(s)                                            |
| ----------------- | ----------------------------------------- |  ----------------------------------------------------- |
| `git config --global user.name`        | Setup your name in Git   | `git config --global user.name Your-Name`                                 |
| `git config --global user.email`        | Setup your mail in Git   | `git config --global user.email Your-mail@example.com`  |

---

### Getting started with Git
| Command           | Description                                 | Example(s)                                            |
| ------------------------ | -----------------------------------------  |----------------------------------------------------- |
| `git init`        | Initialize empty Git repository    | `git init new-project`                                 |
| `git clone`        | Clone a repository from remote server      |  `git clone https://github.com/user/repo.git`                                 |

---

### Commiting Changes
| Command                 | Description                               | Example(s)                                            |
| ------------------------ | ----------------------------------------- |----------------------------------------------------- |
| `git status` | Show the status of Working Directory|  -|
| `git add`| Add files to staging Area|  `git add file1.txt file2.txt`|
| `git add -A`| Add all new and changed files to staging area     | -|
| `git commit`| Commit staged changes|  `git commit -m "latest bug fix"`|
---

### Branching
| Command                 | Description                               | Example(s)                                            |
| ------------------------ | ----------------------------------------- |----------------------------------------------------- |
| `git branch` | List branches|  -|
| `git branch <branch-name>`| Create a new branch|  `git branch feature-branch`|
| `git branch -d <branch-name>`| Delete a merged branch    | `git branch -d feature-branch`|
| `git branch -D <branch-name>`| Delete a branch (Merged or not)|  `git branch -D test-branch`|
| `git branch -m <old-branch-name> <new-branch-name> `| Rename a branch | `git branch -m  feature-branch-v1.0  feature-branch-v2.0`|
| `git push origin --delete <branch-name>`| Delete a remote branch|  `git push origin --delete feature-branch`|
| `git checkout <branch-name>`| switch to a branch |  `git checkout feature-branch`|
| `git checkout -b <branch-name>`| create a new branch and switch to it |  `git checkout -b feature-branch`|
| `git checkout -- <file-name>`| Discard changes to a file | `git checkout -- test.txt`|
| `git checkout . `| Discard all changes in your working directory and  revert the files to the last committed state. | -|

---
### Merging

| Command                                        | Description                        | Example(s)                                          |
| ---------------------------------------------- | ---------------------------------- | --------------------------------------------------- |
| `git merge <branch-name>`       | Merge a branch          | `git merge feature-branch`               |
| `git merge <source-branch> <target-branch>`              |Merge a branch into target branch | `git merge feature-V1 feature-V0`               |
|





### Common Configuration

| Command                                        | Description                        | Example(s)                                          |
| ---------------------------------------------- | ---------------------------------- | --------------------------------------------------- |
| `git config --global alias.<alias-name> <git command>`       | Configure Git aliases              | `git config --global alias.co checkout`               |
| `git config --global core.editor`              | Configure default text editor      | `git config --global core.editor "code"`               |
| `git config --global --edit`                   | Edit Git configuration in an editor | -                                               |

---