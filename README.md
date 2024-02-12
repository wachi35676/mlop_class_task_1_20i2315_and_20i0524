input: git -c credential.helper= -c core.quotepath=false -c log.showSignature=false init
output: Initialized empty Git repository in C:/Users/wasif/PycharmProjects/mlop_class_task_1_20i2315_and_20i0524/.git/

input: git add .
output:

input: git commit -m "Initial commit"
output: [master f4a0a59] Initial commit
 1 file changed, 3 insertions(+)

input: git remote add origin https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524.git
git branch -M main
git push -u origin main
output: Enumerating objects: 16, done.
Counting objects: 100% (16/16), done.
Delta compression using up to 8 threads
Compressing objects: 100% (16/16), done.
Writing objects: 100% (16/16), 2.62 KiB | 383.00 KiB/s, done.
Total 16 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524.git

input: git checkout -b dev
output: Switched to a new branch 'dev'

input: git push -u origin dev
output: Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524/pull/new/dev
remote:
To https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

input: git checkout -b test
output: Switched to a new branch 'test'

input: git push -u origin test
output: 
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524/pull/new/test
remote:
To https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524.git
 * [new branch]      test -> test
branch 'test' set up to track 'origin/test'.

input: git checkout -b 20i0524
output: Switched to a new branch '20i0524'

input: git push -u origin 20i0524
output: Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for '20i0524' on GitHub by visiting:
remote:      https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524/pull/new/20i0524
remote:
To https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524.git
 * [new branch]      20i0524 -> 20i0524
branch '20i0524' set up to track 'origin/20i0524'.

input: git checkout -b 20i2315
output: Switched to a new branch '20i2315'

input: git push -u origin 20i2315
output: Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for '20i2315' on GitHub by visiting:
remote:      https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524/pull/new/20i2315
remote:
To https://github.com/wachi35676/mlop_class_task_1_20i2315_and_20i0524.git
 * [new branch]      20i2315 -> 20i2315
branch '20i2315' set up to track 'origin/20i2315'.

input: git add .
output:

input: git commit -m "updated readme"
output: [20i2315 c062268] updated readme
 1 file changed, 70 insertions(+)
