# The git basics exercises

## Bundle 1

### Exercises 1

```bash


Nicole@DESKTOP-I5FEMIP MINGW64 ~ (main)
$ cd desktop

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop (main)
$ mkdir git-exercises

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop (main)
$ cd git-exercises

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (main)
$ git init
Initialized empty Git repository in C:/Users/Nicole/Desktop/git-exercises/.git/

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (master)
$ code .

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (master)
$

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (master)
$ git branch -m main


Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (main)
$ git add .

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (main)
$ git commit -m "the starting point for exercises"
[main (root-commit) 2862e9a] the starting point for exercises
 1 file changed, 30 insertions(+)
 create mode 100644 readme.md

 
Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (main)
$ git remote add origin git@github.com:Gabanicole/Gym-git-exercises.git

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 455 bytes | 30.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Gabanicole/Gym-git-exercises.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (main)
$ git checkout -b dev
Switched to a new branch 'dev'

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (dev)
$ git checkout -b test
Switched to a new branch 'test'

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Gabanicole/Gym-git-exercises/pull/new/test
remote:
To github.com:Gabanicole/Gym-git-exercises.git
 * [new branch]      test -> test

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (test)
$ git checkout dev
Switched to branch 'dev'

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Gabanicole/Gym-git-exercises/pull/new/dev
remote:
To github.com:Gabanicole/Gym-git-exercises.git
 * [new branch]      dev -> dev

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (dev)
$ git push origin --delete test
To github.com:Gabanicole/Gym-git-exercises.git
 - [deleted]         test

Nicole@DESKTOP-I5FEMIP MINGW64 ~/desktop/git-exercises (dev)
$

```