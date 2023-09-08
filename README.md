# Git-Commands
### Commonly used Git Commands
---
## *Basic Git Commands*


### Setting up Your Git Identity
| Command           | Description                               | Syntax                                      | Example(s)                                            |
| ----------------- | ----------------------------------------- | ------------------------------------------- | ----------------------------------------------------- |
| `git config --global user.name`        | Setup your name in Git       | `git config [option] <key> <value>`                    | `git config --global user.name Your-Name`                                 |
| `git config --global user.email`        | Setup your mail in Git       | `git config [option] <key> <value>`                    | `git config --global user.email Your-mail@example.com`                                 |

---

### Getting started with Git
| Command           | Description                               | Syntax                                      | Example(s)                                            |
| ------------------------ | ----------------------------------------- | ------------------------------------------- | ----------------------------------------------------- |
| `git init`        | Initialize empty Git repository    | `git init [directory]`                    | `git init new-project`                                 |
| `git clone`        | Clone a repository from remote server      | `git clone [URL] [directory]`                    | `git clone https://github.com/user/repo.git`                                 |

---

### Commiting Changes
| Command                 | Description                               | Syntax                                      | Example(s)                                            |
| ------------------------ | ----------------------------------------- | ------------------------------------------- | ----------------------------------------------------- |
| `git status` | Show the status of Working Directory| `git status`| -|
| `git add`| Add files to staging Area| `git add [file(s)]`| `git add file1.txt file2.txt`|
| `git add -A`| Add all new and changed files to staging area     | -| -|
| `git commit`| Commit staged changes| `git commit  -m [commit message]`| `git commit -m "latest bug fix"`|
---