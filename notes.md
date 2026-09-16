
viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        notes.md
        trails.md

nothing added to commit but untracked files present (use "git add" to track)

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git add .

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   notes.md
        new file:   trails.md


viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git commit -m "Add the trail list"
[main 3d3fec2] Add the trail list
 2 files changed, 30 insertions(+)
 create mode 100644 notes.md
 create mode 100644 trails.md

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git add menu.md

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git commit -m "Add the refuge menu"
[main 75c16aa] Add the refuge menu
 1 file changed, 5 insertions(+)
 create mode 100644 menu.md

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git log
commit 75c16aa48a75fe414558184347c492dc0b026445 (HEAD -> main)
Author: Viktor Shevchenko <viktor.shevy@gmail.com>
Date:   Wed Sep 16 08:48:17 2026 +0200

    Add the refuge menu

commit 3d3fec2c0e53ffd02540ae88f9b1b9bb1e9ac31f
Author: Viktor Shevchenko <viktor.shevy@gmail.com>
Date:   Wed Sep 16 08:46:48 2026 +0200

    Add the trail list

commit 2c434ea7a7d04fab44d41b525de3deecfbff99ce (origin/main, origin/HEAD)
Author: Viectra <viectra0015@gmail.com>
Date:   Wed Sep 16 08:36:53 2026 +0200

    Initial commit

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   notes.md
        modified:   trails.md

no changes added to commit (use "git add" and/or "git commit -a")

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git restore trails.md

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git add trails.md
git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   trails.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   notes.md


viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ 

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   trails.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   notes.md


viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git restore --staged trails.md

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   notes.md
        modified:   trails.md

no changes added to commit (use "git add" and/or "git commit -a")

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ git restore trails.md

viect@ViectraPP MINGW64 ~/Documents/Code/git/refugit/refugit (main)
$ 