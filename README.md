# learing-git
#### Following are the learing points
1. (ctrl + l) - to clear screen
2. repository - collection of various versions of a project
3. (git add -A) – to add everything, if we are in subdirectory we can add from parent directory
4. (cat filename) – to show its contents
5. (git restore) – restore the files to previous commit
6. (git diff) - shows the insertions and deletions in the files
7. (git commit –amend -m “messege”) – change the messege of previous commit
8. (git log) - to show the list of commits
9. (git status) - The git status command displays the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.
10. (git branch) - to know you are inside of a which branch
11. (git branch -r) - to know remote branch status
12. (git branch -a) - to see all branches
13. (git branch branchname) - create a branch
14. (git checkout branchname) - switch to the branch
15. (git checkout -) - switch to the previous branch
16. (ls -a) - to see hidden files as well
17. (git branch -b branchname) - create and switch branch at same time
18. (git branch -d branchname) - delete the branch
19. (git log--oneline) - sofisticated log
20. the branch must be deleted separately on remote and local repo after mearging
21. REBASE - when your main branch has moved on and you dont have the changes from the main branch- the rebase will take all commits from master and will try to apply our commits on top of it
* (git pull -r origin main) - pull the main branch or parent branch as a base
* reslove the conflicts by editing the mentioned files
* (git add .)
* (git rebase --continue) - continue the rebasing, repeat these steps till the patch failed error is gone
* (git push -f) - force push the child branch
