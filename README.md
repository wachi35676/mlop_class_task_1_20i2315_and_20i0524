# Project Git Command Log

This document provides a detailed log of the Git commands used during the setup and initial development phases of our project, along with their respective outputs. The purpose is to offer insight into the version control steps undertaken by the team.

## Repository Initialization

### Initializing the Git Repository

- **Command:**
  ```
  git -c credential.helper= -c core.quotepath=false -c log.showSignature=false init
  ```
- **Output:**
  ```
  Initialized empty Git repository in C:/Users/wasif/PycharmProjects/mlop_class_task_1_20i2315_and_20i0524/.git/
  ```

## Stage Changes and Commit

### Staging All Changes

- **Command:**
  ```
  git add .
  ```
- **Output:**
  ```
  (No output, indicating successful staging of changes)
  ```

### Creating the Initial Commit

- **Command:**
  ```
  git commit -m "Initial commit"
  ```
- **Output:**
  ```
  [master f4a0a59] Initial commit
  1 file changed, 3 insertions(+)
  ```

## Remote Repository and Branch Management

### Setting Up Remote Repository

- **Commands:**
  ```
  git remote add origin https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524.git
  git branch -M main
  git push -u origin main
  ```
- **Output:**
  ```
  Enumerating objects: 16, done.
  Counting objects: 100% (16/16), done.
  Delta compression using up to 8 threads
  Compressing objects: 100% (16/16), done.
  Writing objects: 100% (16/16), 2.62 KiB | 383.00 KiB/s, done.
  Total 16 (delta 1), reused 0 (delta 0), pack-reused 0
  remote: Resolving deltas: 100% (1/1), done.
  To https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524.git
  ```

### Branch Creation and Management

#### Development Branch (`dev`)

- **Command:**
  ```
  git checkout -b dev
  ```
- **Output:**
  ```
  Switched to a new branch 'dev'
  ```

- **Command for pushing `dev` branch:**
  ```
  git push -u origin dev
  ```
- **Output:**
  ```
  Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
  To https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524.git
  * [new branch]      dev -> dev
  branch 'dev' set up to track 'origin/dev'.
  ```

#### Test Branch (`test`)

- **Command:**
  ```
  git checkout -b test
  ```
- **Output:**
  ```
  Switched to a new branch 'test'
  ```

- **Command for pushing `test` branch:**
  ```
  git push -u origin test
  ```
- **Output:**
  ```
  (Similar output as `dev` branch, indicating successful push and tracking setup)
  ```

#### Individual Member Branches (`20i0524` and `20i2315`)

- **Commands and outputs for creating and pushing individual branches are similar to the above examples.**

## Updates and Further Commits

### Adding Changes and Updating README

- **Command:**
  ```
  git add .
  ```
- **Output:**
  ```
  (No output, indicating successful staging of changes)
  ```

- **Command:**
  ```
  git commit -m "updated readme"
  ```
- **Output:**
  ```
  [20i2315 c062268] updated readme
  1 file changed, 70 insertions(+)
  ```

## Conclusion

This log showcases the foundational Git operations used to set up our project's version control structure. It includes repository initialization, branch management, and basic workflow commands for committing and pushing changes. For more detailed operations and troubleshooting, refer to the official Git documentation.

# Project Git Commands Log

This document outlines the Git commands used during the project setup and development phases, along with their expected outputs for reference.

## Setup and Configuration

- **Print Working Directory**
  - Command: `pwd`
  - Expected Output: Shows the current directory, e.g., `/path/to/my_project`.

- **List Files and Directories**
  - Command: `ls`
  - Expected Output: Lists files and directories in the current directory.

## Editing and File Operations

- **Edit with Nano** (No direct output from the command itself)
  - Command: `nano README.md`

- **Print Text to Terminal**
  - Command: `echo "Hello, World!"`
  - Expected Output: `Hello, World!`

## Git Operations

- **Check Git Status**
  - Command: `git status`
  - Expected Output: Shows staged and unstaged changes.

- **Stage Specific File**
  - Command: `git add src/main.py`
  - Expected Output: No output for successful add.

- **Stage All Changes**
  - Command: `git add .`
  - Expected Output: No output for successful add.

- **Unstage All Changes**
  - Command: `git reset HEAD .`
  - Expected Output: Indicates modifications are unstaged.

- **Remove Untracked Files**
  - Command: `git clean -f src/temp.txt`
  - Expected Output: No direct output; the specified file is removed.

- **Commit Changes**
  - Command: `git commit -m "Initial commit"`
  - Expected Output: `[master (root-commit) f4a0a59] Initial commit 1 file changed, 1 insertion(+)`

- **Configure Git Alias for Commit**
  - Command: `git config --global alias.ci 'commit -m'`
  - Expected Output: No output for successful configuration.

- **Use Alias to Commit**
  - Command: `git ci "Quick commit message"`
  - Expected Output: Commit is made with the "Quick commit message".

- **View Commit Logs**
  - Command: `git log`
  - Expected Output: Shows a list of commit logs.

- **Compare Differences**
  - Command: `git diff HEAD~1 HEAD`
  - Expected Output: Displays differences between the last two commits.

- **List Global Git Configuration**
  - Command: `git config --global --list`
  - Expected Output: Lists all global Git configuration settings.

- **List Branches**
  - Command: `git branch`
  - Expected Output: Lists all local branches, marking the current branch.

- **Create and Switch to New Branch**
  - Command: `git checkout -b dev`
  - Expected Output: `Switched to a new branch 'dev'`.

- **Merge Branches**
  - Command: `git merge dev` (Assume you're merging into `main`)
  - Expected Output: Shows merge success and summary.

- **Push Local Branch to Remote**
  - Command: `git push origin dev`
  - Expected Output: Confirms the branch has been pushed to remote.

- **Pull Latest Changes from Remote**
  - Command: `git pull origin dev`
  - Expected Output: Updates local branch with remote changes.

- **Fetch Latest Changes Without Merging**
  - Command: `git fetch`
  - Expected Output: Fetches updates from the remote but does not merge.

- **View Remote Repositories**
  - Command: `git remote -v`
  - Expected Output: Displays the remote repositories configured for fetch and push.

---

For more detailed operations and troubleshooting, refer to the official Git documentation. This log aims to provide a clear overview of the foundational Git commands used in our project's development workflow.
