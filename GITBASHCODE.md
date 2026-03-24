
User@216-7 MINGW64 ~
$ cd ~/desktop/

User@216-7 MINGW64 ~/desktop
$ mkdir Soril

User@216-7 MINGW64 ~/desktop
$ cd Soril

User@216-7 MINGW64 ~/desktop/Soril
$ git clone https://github.com/Chintulga0720/Lekts6
Cloning into 'Lekts6'...
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 12 (delta 3), reused 12 (delta 3), pack-reused 0 (from 0)
Receiving objects: 100% (12/12), done.
Resolving deltas: 100% (3/3), done.

User@216-7 MINGW64 ~/desktop/Soril
$ git branch
fatal: not a git repository (or any of the parent directories): .git

User@216-7 MINGW64 ~/desktop/Soril
$ git log --oneline
fatal: not a git repository (or any of the parent directories): .git

User@216-7 MINGW64 ~/desktop/Soril
$ git init
Initialized empty Git repository in C:/Users/User/Desktop/Soril/.git/

User@216-7 MINGW64 ~/desktop/Soril (master)
$ ls
Lekts6/

User@216-7 MINGW64 ~/desktop/Soril (master)
$ cd lekts6

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ ls
README.md

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git branch
* main

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git log --oneline
fce595d (HEAD -> main, origin/main, origin/HEAD) Зүйрлэл_нэмэв
588d566 Жишээ_нэмэв
eb329c5 Тодорхойлолт_нэмэв
2c0abf8 README.md үүсгэв

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git log --oneline --decorate --all -- graph

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git log --oneline --decorate --all --graph
* fce595d (HEAD -> main, origin/main, origin/HEAD) Зүйрлэл_нэмэв
* 588d566 Жишээ_нэмэв
* eb329c5 Тодорхойлолт_нэмэв
* 2c0abf8 README.md үүсгэв

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git branch feature-test

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git log --oneline --decorate --all --graph
* fce595d (HEAD -> main, origin/main, origin/HEAD, feature-test) Зүйрлэл_нэмэв
* 588d566 Жишээ_нэмэв
* eb329c5 Тодорхойлолт_нэмэв
* 2c0abf8 README.md үүсгэв

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git checkout feature-test
M       README.md
Switched to branch 'feature-test'

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git log --oneline --decorate --all --graph
* fce595d (HEAD -> feature-test, origin/main, origin/HEAD, main) Зүйрлэл_нэмэв
* 588d566 Жишээ_нэмэв
* eb329c5 Тодорхойлолт_нэмэв
* 2c0abf8 README.md үүсгэв

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git branch
* feature-test
  main

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ code .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git status
On branch feature-test
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ gid add .
bash: gid: command not found

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ code .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ code .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ code .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git status
On branch feature-test
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ gid add .
bash: gid: command not found

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git add .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git status
On branch feature-test
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git push origin feature-test
info: please complete authentication in your browser...
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'feature-test' on GitHub by visiting:
remote:      https://github.com/Chintulga0720/Lekts6/pull/new/feature-test
remote:
To https://github.com/Chintulga0720/Lekts6
 * [new branch]      feature-test -> feature-test

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git remote -v
origin  https://github.com/Chintulga0720/Lekts6 (fetch)
origin  https://github.com/Chintulga0720/Lekts6 (push)

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ code .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git checkout main
M       README.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ code .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ code .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git checkout feature-test
M       README.md
Switched to branch 'feature-test'

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ code .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git status
On branch feature-test
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md


User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git add .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git status
On branch feature-test
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git push origin
fatal: The current branch feature-test has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature-test

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git push origin feature-test
Everything up-to-date

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ code .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ code Soril.md

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git checkout main
M       README.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git push origin main
Everything up-to-date

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Soril.md


User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git add soril.d
fatal: pathspec 'soril.d' did not match any files

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git add soril.md

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Soril.md


User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git add .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md
        new file:   Soril.md


User@216-7 MINGW64 ~/desktop/Soril/lekts6 (main)
$ git checkout feature-test
M       README.md
A       Soril.md
Switched to branch 'feature-test'

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ code Soril.md

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git commit -m "feature-me testlej vzew"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'User@216-7.(none)')

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git config user.email "chintulga0720@gmail.com"

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git config user.name "chintulga"

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git commit -m "feature-me testlej vzew"
[feature-test 269212f] feature-me testlej vzew
 2 files changed, 83 insertions(+), 1 deletion(-)
 create mode 100644 Soril.md

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git status
On branch feature-test
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Soril.md

no changes added to commit (use "git add" and/or "git commit -a")

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git add .

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git status
On branch feature-test
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   Soril.md


User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$ git push origin feature-test
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 20 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.56 KiB | 1.56 MiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Chintulga0720/Lekts6
   fce595d..269212f  feature-test -> feature-test

User@216-7 MINGW64 ~/desktop/Soril/lekts6 (feature-test)
$
