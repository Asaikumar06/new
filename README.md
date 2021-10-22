# new
Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ pwd
/c/devops/pratise/helo/pole/svd/s6/branch
Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git init
Initialized empty Git repository in C:/devops/pratise/helo/pole/svd/s6/branch/.git/

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ ls

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ touch 1 2 3 4 5 6

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        1
        2
        3
        4
        5
        6

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add 1

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   1

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        2
        3
        4
        5
        6


Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash save " i am saving 1 file to do some imp work"
You do not have the initial commit yet

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash save " i am saving 1 file to do some imp work"
You do not have the initial commit yet

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   1

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        2
        3
        4
        5
        6


Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash save " i am saving 1 file to do some imp work"
You do not have the initial commit yet

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git log
fatal: your current branch 'master' does not have any commits yet

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ touch a

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add a

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git commit -m "a"
[master (root-commit) 207daa0] a
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 1
 create mode 100644 a

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git log
commit 207daa085e5401ac5f927018567808cdbd34f6fe (HEAD -> master)
Author: Your Name <you@example.com>
Date:   Fri Oct 22 16:47:59 2021 +0530

    a

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash save " i am saving 1 file to do some imp work"
No local changes to save

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        2
        3
        4
        5
        6

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add 2

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   2

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        3
        4
        5
        6


Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash save " i am saving 2 file to do some imp work"
Saved working directory and index state On master:  i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        3
        4
        5
        6

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git log
commit 207daa085e5401ac5f927018567808cdbd34f6fe (HEAD -> master)
Author: Your Name <you@example.com>
Date:   Fri Oct 22 16:47:59 2021 +0530

    a

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list
stash@{0}: On master: i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        3
        4
        5
        6

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add .

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   3
        new file:   4
        new file:   5
        new file:   6


Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash save "add all to shash"4
Saved working directory and index state On master: add all to shash4

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
nothing to commit, working tree clean

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list
stash@{0}: On master: add all to shash4
stash@{1}: On master: i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ touch 6 7 8

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git 6
git: '6' is not a git command. See 'git --help'.

The most similar commands are
        am
        gc
        mv
        p4
        rm

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add 6

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash save "add 6"
Saved working directory and index state On master: add 6

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list
stash@{0}: On master: add 6
stash@{1}: On master: add all to shash4
stash@{2}: On master: i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        7
        8

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add 7

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash save "add 7"
Saved working directory and index state On master: add 7

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add 8

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash save "add 8"
Saved working directory and index state On master: add 8

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list
stash@{0}: On master: add 8
stash@{1}: On master: add 7
stash@{2}: On master: add 6
stash@{3}: On master: add all to shash4
stash@{4}: On master: i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ ls
1  a

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ touch hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git commit -m "hotfix"
[master e3bc7be] hotfix
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
nothing to commit, working tree clean

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
nothing to commit, working tree clean

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list
stash@{0}: On master: add 8
stash@{1}: On master: add 7
stash@{2}: On master: add 6
stash@{3}: On master: add all to shash4
stash@{4}: On master: i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash apply
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   8


Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   8


Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash apply stash@{2}
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   6
        new file:   8


Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   6
        new file:   8


Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list
stash@{0}: On master: add 8
stash@{1}: On master: add 7
stash@{2}: On master: add 6
stash@{3}: On master: add all to shash4
stash@{4}: On master: i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash pop stash @{3}
Too many revisions specified: 'stash' '@{3}'

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list
stash@{0}: On master: add 8
stash@{1}: On master: add 7
stash@{2}: On master: add 6
stash@{3}: On master: add all to shash4
stash@{4}: On master: i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash drop
Dropped refs/stash@{0} (40deb2a943d678178eb5e41ebd0db77fb814ea6e)

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list
stash@{0}: On master: add 7
stash@{1}: On master: add 6
stash@{2}: On master: add all to shash4
stash@{3}: On master: i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash drop stash@{2}
Dropped stash@{2} (b7606e63b39401d09363246969be14f28a8c8adb)

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git stash list
stash@{0}: On master: add 7
stash@{1}: On master: add 6
stash@{2}: On master: i am saving 2 file to do some imp work

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git init
Reinitialized existing Git repository in C:/devops/pratise/helo/pole/svd/s6/branch/.git/

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git branch
* master

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ touch 1

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add 1

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git commit -m "l"
[master 4b4a2b3] l
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 6
 create mode 100644 8

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git branch
* master

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git branch -a
* master

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git branch test

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git branch
* master
  test

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git checkout test
Switched to branch 'test'

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git branch
  master
* test

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ ls
1  6  8  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git checkout master
Switched to branch 'master'

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ ls
1  6  8  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ touch 2 3

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git add *

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git commit -m "all"
[master 86aa27e] all
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 2
 create mode 100644 3

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ ls
1  2  3  6  8  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (master)
$ git checkout test
Switched to branch 'test'

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ ls
1  6  8  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git merge master
Updating 4b4a2b3..86aa27e
Fast-forward
 2 | 0
 3 | 0
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 2
 create mode 100644 3

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ ls
1  2  3  6  8  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ touch X Y Z

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git commit -m "svdkms"
On branch test
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        X
        Y
        Z

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ ls
1  2  3  6  8  X  Y  Z  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ ls
1  2  3  6  8  X  Y  Z  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git status
On branch test
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        X
        Y
        Z

nothing added to commit but untracked files present (use "git add" to track)

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git chechout -b qa
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git branch
  master
* test

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ ls
1  2  3  6  8  X  Y  Z  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git chechout master
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ ls
1  2  3  6  8  X  Y  Z  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git merge qa
merge: qa - not something we can merge

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ ls
1  2  3  6  8  X  Y  Z  a  hotfix

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ history
   39  Untracked files:
   40    (use "git add <file>..." to include in what will be committed)
   41          A.txt
   42          B.txt
   43          C.txt
   44          CK.txt
   45          RC.txt
   46  nothing added to commit but untracked files present (use "git add" to track)
   47  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
   48  $ git add A.txt C.txt
   49  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
   50  $ git status
   51  On branch master
   52  No commits yet
   53  Changes to be committed:
   54    (use "git rm --cached <file>..." to unstage)
   55          new file:   A.txt
   56          new file:   C.txt
   57  Untracked files:
   58    (use "git add <file>..." to include in what will be committed)
   59          B.txt
   60          CK.txt
   61          RC.txt
   62  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
   63  $ git c
   64  checkout                     clone
   65  cherry                       commit
   66  cherry-pick                  config
   67  citool                       credential-helper-selector
   68  clean
   69  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
   70  $ git c
   71  checkout                     clone
   72  cherry                       commit
   73  cherry-pick                  config
   74  citool                       credential-helper-selector
   75  clean
   76  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
   77  $ git ck.txt
   78  git: 'ck.txt' is not a git command. See 'git --help'.
   79  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
   80  $ git add Ck.txt
   81  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
   82  $ git status
   83  On branch master
   84  No commits yet
   85  Changes to be committed:
   86    (use "git rm --cached <file>..." to unstage)
   87          new file:   A.txt
   88          new file:   C.txt
   89  Untracked files:
   90    (use "git add <file>..." to include in what will be committed)
   91          B.txt
   92          CK.txt
   93          RC.txt
   94  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
   95  $ git add rc.txt
   96  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
   97  $ git status
   98  On branch master
   99  No commits yet
  100  Changes to be committed:
  101    (use "git rm --cached <file>..." to unstage)
  102          new file:   A.txt
  103          new file:   C.txt
  104  Untracked files:
  105    (use "git add <file>..." to include in what will be committed)
  106          B.txt
  107          CK.txt
  108          RC.txt
  109  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  110  $ git add .
  111  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  112  $ git status
  113  On branch master
  114  No commits yet
  115  Changes to be committed:
  116    (use "git rm --cached <file>..." to unstage)
  117          new file:   A.txt
  118          new file:   B.txt
  119          new file:   C.txt
  120          new file:   CK.txt
  121          new file:   RC.txt
  122  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  123  $ git commit -m "add only 1 file"A.txt
  124  Author identity unknown
  125  *** Please tell me who you are.
  126  Run
  127    git config --global user.email "you@example.com"
  128    git config --global user.name "Your Name"
  129  to set your account's default identity.
  130  Omit --global to set the identity only in this repository.
  131  fatal: unable to auto-detect email address (got 'Lenovo@DESKTOP-AI06K01.(none)')
  132  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  133  $  git config --global user.email "saikumartslm0606@gmail.com"
  134  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  135  $ git config --global user.name "Asaikumar06"
  136  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  137  $ git log
  138  fatal: your current branch 'master' does not have any commits yet
  139  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  140  $ git commit -m "add only 1 file"A.txt
  141  [master (root-commit) 43b571e] add only 1 fileA.txt
  142   5 files changed, 0 insertions(+), 0 deletions(-)
  143   create mode 100644 A.txt
  144   create mode 100644 B.txt
  145   create mode 100644 C.txt
  146   create mode 100644 CK.txt
  147   create mode 100644 RC.txt
  148  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  149  $ git log
  150  commit 43b571eba276238708a11da062121e88e26b0e41 (HEAD -> master)
  151  Author: <U+0081>Asaikumar06 <saikumartslm0606@gmail.com>
  152  Date:   Fri Oct 22 10:54:34 2021 +0530
  153      add only 1 fileA.txt
  154  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  155  $ git status
  156  On branch master
  157  nothing to commit, working tree clean
  158  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  159  $ git config --global -e
  160  error: key does not contain a section: u-e
  161  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  162  $ git remote add origin https://github.com/Asaikumar06/svd.git
  163  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  164  $ git push -u master
  165  fatal: 'master' does not appear to be a git repository
  166  fatal: Could not read from remote repository.
  167  Please make sure you have the correct access rights
  168  and the repository exists.
  169  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  170  $ git push -u origin main
  171  error: src refspec main does not match any
  172  error: failed to push some refs to 'https://github.com/Asaikumar06/svd.git'
  173  Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo (master)
  174  $ git remort add origin
  175   git remote add origin https://github.com/Asaikumar06/svd.git
  176  git remote add origin https://github.com/Asaikumar06/chand.git
  177  clear
  178  git status
  179  git remote add origin https://github.com/Asaikumar06/chand.git
  180  ls
  181  git init
  182  git status
  183  git add demo.txt
  184  git status
  185  git add *
  186  git status
  187  git commit -m "add some"
  188  git status
  189  git log
  190  git commit -m "add some"
  191  git remote add origin https://github.com/Asaikumar06/chand.git
  192  git push -u origin main
  193  ls
  194  git status
  195  git init
  196  git status
  197  git add *
  198  git commit -m "somthing"
  199  git status
  200  git log
  201  git push
  202  git remote add origin https://github.com/Asaikumar06/chand.git
  203  git push -u origin main
  204  git push -u origin master
  205  git clone https://github.com/Asaikumar06/svd.git
  206  ls
  207  cd svd/
  208  git status
  209  touch gmail.test
  210  ls
  211  git status
  212  git gmail.test gmail.test
  213  git status
  214  git commit -m "some"
  215  git push
  216  pwd
  217  cd ..
  218  pwd
  219  ls
  220  cd svd
  221  ls
  222  pwd
  223  cd ..
  224  ls
  225  cd demo
  226  ls
  227  git logs
  228  git log
  229  just press the center
  230  q
  231  git log --oneline
  232  show
  233  git log
  234  git log --author"same"
  235  git log --author"same" --oneline
  236  git log --oneline
  237  git reset --mixed
  238  git log --oneline
  239  git status
  240  add data
  241  vi
  242  git status
  243  vi A.txt
  244  git add *
  245  git commit -m "mesg"
  246  git log
  247  git log --oneline
  248  git reset head 3
  249  git status
  250  clear
  251  git log --oneline
  252  git reset --mixed
  253  git log --oneline
  254  git status
  255  add data
  256  vi
  257  git add
  258  git commit -m "msg"
  259  git log
  260  git status
  261  clear
  262  ls
  263  git status
  264  git init
  265  ls
  266  touch 1 to 3
  267  git status
  268  git add *
  269  git status
  270  git commit -m "some" 1
  271  git status
  272  git commit -m "1some" 1
  273  git commit -m "3some" 3
  274  git commit -m "tosome" to
  275  ls
  276  git status
  277  git log
  278  git log --oneline
  279  git reset --soft
  280  git status
  281  git status
  282  git log --oneline
  283  git reset hear 3
  284  git status
  285  git reset --soft 9b4d95c
  286  git status
  287  git log --oneline
  288  git reset hear 3
  289  git status
  290  git reset --mixed
  291  git status
  292  git reset --soft 338dc41
  293  git status
  294  git reset --mixed
  295  git status
  296  ls
  297  git status
  298  clear
  299  ls
  300  git status
  301  git init
  302  git status
  303  git add -A
  304  git status
  305  git commit -m "add all"
  306  git log
  307  git status
  308  git remote add origin https://github.com/Asaikumar06/svd.git
  309  git push -u origin master
  310  clear
  311  ls
  312  git status
  313  git init
  314  ls
  315  touch 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20
  316  git status
  317  git add -A
  318  git status
  319  git commit -m "add one file" 123456
  320  1
  321  git commit -m "add one file" 12
  322  git status
  323  git commit -m "12add one file" 12
  324  git commit -m "1,2,3,4,5,6,7,8,9 add one file" 1,2,3,4,5,6,7,8,9
  325  git commit -m "123456789 add one file" 123456789
  326  git commit -m "1 add one file" 1
  327  git commit -m "2 add one file" 2
  328  git commit -m "2 add one file" 2
  329  git commit -m "3 add one file" 3
  330  git commit -m "4 add one file" 4
  331  git commit -m "5 add one file" 5
  332  git commit -m "6 add one file" 6
  333  git commit -m "7 add one file" 7
  334  git commit -m "8 add one
  335  git commit -m "9 add one file" 9
  336  git commit -m "10 add one file" 10
  337  git commit -m "11 add one file" 11
  338  git commit -m "13 add one file" 13
  339  git commit -m "14 add one file" 14
  340  git commit -m "15 add one file" 15
  341  git commit -m "16 add one file" 16
  342  git commit -m "17 add one file" 17
  343  git commit -m "18 add one file" 18
  344  git commit -m "19 add one file" 19
  345  git commit -m "20 add one file" 20
  346  ls
  347  git status
  348  git log
  349  git log --oneline
  350  git reset --soft 417acd5
  351  git status
  352  git reset --soft 5822628
  353  git status
  354  git reset --soft 6f0f564
  355  git status
  356  git log --onrline
  357  git reset --soft cid
  358  git reset --soft CID
  359  git reset --mixed 5822628
  360  git status
  361  git reset --mixed e58bc1b
  362  git status
  363  git reset --mixed 6f0f564
  364  git status
  365  vi 20
  366  git status
  367  git commit -m "s"
  368  git l
  369  git log
  370  git push
  371  ls
  372  git status
  373  git init
  374  git status
  375  git add 123.txt 654.txt
  376  git status
  377  git add -A
  378  git status
  379  git commit -m add "some" 123.txt
  380  git commit -m add 'some' 123.txt
  381  git commit -m add 'add two num' 123.txt
  382  git commit -m add 'add two num'
  383  git commit -m add "some"
  384  git commit -m "add some"
  385  git status
  386  git log
  387  git remote add origin https://github.com/Asaikumar06/mack.git
  388  git push -u origin master
  389  ls
  390  git status
  391  git init
  392  ls
  393  git status
  394  git add *
  395  git status
  396  clear
  397  git clone https://github.com/Asaikumar06/new.git
  398  ls
  399  cd new
  400  pwd
  401  git log
  402  git commi -m "some"
  403  git log
  404  git log
  405  git log
  406  git commit -m "fake"
  407  git log
  408  git log --oneline
  409  clear
  410  ls
  411  git status
  412  gut init
  413  touch 1 to 30
  414  git status
  415  git add *
  416  git status
  417  git commit -m "add some" 1
  418  git status
  419  git commit -m "1add some" 1
  420  git commit -m "toadd some" to
  421  git commit -m "30 add some" 30
  422  ls
  423  git commit -m "toadd some" to
  424  git status
  425  git log
  426  git log --oneline
  427  git reset --soft 51e16c8
  428  git status
  429  git reset --soft 131d154
  430  git status
  431  git status
  432  git log --oneline 131d154
  433  git reset --soft CID
  434  git reset  -- mixed 131d154
  435  git status
  436  git reset  -- mixed CID
  437  git status
  438  git log
  439  git reset
  440  git status
  441  git status
  442  pwd
  443  git init
  444  ls
  445  touch 1 2 3 4 5 6
  446  git status
  447  git add 1
  448  git status
  449  git stash list
  450  git stash save " i am saving 1 file to do some imp work"
  451  git stash save " i am saving 1 file to do some imp work"
  452  git stash list
  453  git status
  454  git stash save " i am saving 1 file to do some imp work"
  455  git log
  456  touch a
  457  git add a
  458  git commit -m "a"
  459  git log
  460  git stash save " i am saving 1 file to do some imp work"
  461  git status
  462  git add 2
  463  git status
  464  git stash save " i am saving 2 file to do some imp work"
  465  git status
  466  git log
  467  git stash list
  468  git status
  469  git add .
  470  git status
  471  git stash save "add all to shash"4
  472  git status
  473  git stash list
  474  touch 6 7 8
  475  git 6
  476  git add 6
  477  git stash save "add 6"
  478  git stash list
  479  git status
  480  git add 7
  481  git stash save "add 7"
  482  git add 8
  483  git stash save "add 8"
  484  git stash list
  485  ls
  486  touch hotfix
  487  git add hotfix
  488  git commit -m "hotfix"
  489  git status
  490  git status
  491  git stash list
  492  git stash apply
  493  git status
  494  git stash apply stash@{2}
  495  git status
  496  git stash list
  497  git stash pop stash @{3}
  498  git stash list
  499  git stash drop
  500  git stash list
  501  git stash drop stash@{2}
  502  git stash list
  503  git init
  504  git branch
  505  touch 1
  506  git add 1
  507  git commit -m "l"
  508  git branch
  509  git branch -a
  510  git branch test
  511  git branch
  512  git checkout test
  513  git branch
  514  ls
  515  git checkout master
  516  ls
  517  touch 2 3
  518  git add *
  519  git commit -m "all"
  520  ls
  521  git checkout test
  522  ls
  523  git merge master
  524  ls
  525  touch X Y Z
  526  git add
  527  git commit -m "svdkms"
  528  ls
  529  ls
  530  git status
  531  git chechout -b qa
  532  git branch
  533  ls
  534  git chechout master
  535  ls
  536  git merge qa
  537  ls
  538  history

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git remote add origin https://github.com/Asaikumar06/new.git

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$ git push -u origin test
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (9/9), 710 bytes | 236.00 KiB/s, done.
Total 9 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/Asaikumar06/new.git
 * [new branch]      test -> test
Branch 'test' set up to track remote branch 'test' from 'origin'.

Lenovo@DESKTOP-AI06K01 MINGW64 /c/devops/pratise/helo/pole/svd/s6/branch (test)
$
