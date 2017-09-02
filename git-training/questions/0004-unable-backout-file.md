Unable to backout changes.

## Question

Hi, I am getting error as below when checkout changes(" unknown option...). Please see and help.

-----------------------------------------------

```
  (use "git push" to publish your local commits)
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   level1-file.txt

no changes added to commit (use "git add" and/or "git commit -a")

user@user MINGW64 ~/projectsgit/starter-web/level1 (master)
$ git checkout --level1-file.txt
error: unknown option `level1-file.txt'
usage: git checkout [<options>] <branch>
   or: git checkout [<options>] [<branch>] -- <file>...
```

## Answer

Make sure you have a space on both sides of the "double dash" like this:

```
git checkout -- level1-file.txt
```
