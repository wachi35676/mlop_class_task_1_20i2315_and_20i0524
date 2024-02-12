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