$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

$ git log
commit f8712d5c4df74fa0d49c8cc9ba3b1a5b2c571072 (HEAD -> master, origin/master, origin/HEAD)
Author: Frank Theile <ftheile@grundfos.com>
Date:   Mon Dec 9 10:30:13 2019 +0100

    Add missing shebang in squashing/setup.sh

    `setup.sh` should be executable according to the instructions given in README.md

commit e060df632bf4799da9aa1c0092640563acf84588
Author: Adam Matan <adamatan@users.noreply.github.com>
Date:   Wed Dec 4 07:46:31 2019 +0200

    Word ordering

commit 6ccb85882dc12fb0b26acd65bead2fc7da57a187
Author: Frank Theile <ftheile@grundfos.com>
Date:   Wed Nov 27 08:24:29 2019 +0100

    Mention `less` in SHELL-BASICS.md

    Helpful alternative to `cat` for long files.

$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        xz.txt

nothing added to commit but untracked files present (use "git add" to track)

$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   xz.txt

$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   xz.txt

no changes added to commit (use "git add" and/or "git commit -a")

$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   xz.txt

$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   xz.txt

no changes added to commit (use "git add" and/or "git commit -a")

$ git log
commit 3ff619a6989ebe456073f0d312f61ccacc7a7e4d (HEAD -> master)
Author: Xinglin Zou <xinglinz@uci.edu>
Date:   Fri Jan 24 16:55:46 2020 -0800

    add some bytes in the text

commit b129a20abe4caf9890917a3f6b08d27a2c245ce8
Author: Xinglin Zou <xinglinz@uci.edu>
Date:   Fri Jan 24 16:53:07 2020 -0800

    create an xz.txt

commit f8712d5c4df74fa0d49c8cc9ba3b1a5b2c571072 (origin/master, origin/HEAD)
Author: Frank Theile <ftheile@grundfos.com>
Date:   Mon Dec 9 10:30:13 2019 +0100

    Add missing shebang in squashing/setup.sh

    `setup.sh` should be executable according to the instructions given in README.md

commit e060df632bf4799da9aa1c0092640563acf84588
Author: Adam Matan <adamatan@users.noreply.github.com>
:



