# git-practice
For git practice
Commands I ran in this git repo on my local copy

`ls -latr`

`git status`

`vi README.md`
> typed above code

and now exit INSERT mode, I will skip parts where I am adding text to README.md files

`git status`

>On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

`git add README.md`

`git status`

>On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   README.md

`git commit -m "Look at this I added text to README.md File and now I am commiting this"

> [main a2328e2] Look at this I added text to README.md File and now I am commiting this
 1 file changed, 7 insertions(+)

`git status`

>On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean


`git push`

>Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 477 bytes | 477.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/ninad0604/git-practice.git
   9671b12..a2328e2  main -> main



