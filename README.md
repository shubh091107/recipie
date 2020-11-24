shreya@DESKTOP-DQBLABB MINGW64 ~
$ cd Desktop

shreya@DESKTOP-DQBLABB MINGW64 ~/Desktop
$ cd E:\
>

shreya@DESKTOP-DQBLABB MINGW64 /e
$ mkdir RECIPE

shreya@DESKTOP-DQBLABB MINGW64 /e
$ cd RECIPE

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE
$ git clone https://github.com/shubh091107/ingridients-and-recipe.git
Cloning into 'ingridients-and-recipe'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (3/3), done.

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE
$ ls
ingridients-and-recipe/

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE
$ cd ingridients-and-recipe

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE/ingridients-and-recipe (main)
$ ls
README.md

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE/ingridients-and-recipe (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ingridients.md
        recipe.md

nothing added to commit but untracked files present (use "git add" to track)

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE/ingridients-and-recipe (main)
$ git add ingridients.md

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE/ingridients-and-recipe (main)
$ git add recipe.md

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE/ingridients-and-recipe (main)
$ git commit -m"d"
[main a27bea8] d
 2 files changed, 18 insertions(+)
 create mode 100644 ingridients.md
 create mode 100644 recipe.md

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE/ingridients-and-recipe (main)
$ git remote add dish https://github.com/shubh091107/recipie.git

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE/ingridients-and-recipe (main)
$ git push -u dish
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 1.35 KiB | 691.00 KiB/s, done.
Total 7 (delta 0), reused 3 (delta 0), pack-reused 0
To https://github.com/shubh091107/recipie.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'dish'.

shreya@DESKTOP-DQBLABB MINGW64 /e/RECIPE/ingridients-and-recipe (main)
$


