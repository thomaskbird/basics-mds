# Basics of git commands

1. `git status` - displays a list of changes
2. `git diff <FILENAME>` - shows set of changes that you can look through before adding and committing, optionally you can pass a filename just to see that files changes alone.
3. `git add <FILENAME | .>` - Adds a single file or any changes within the directory to staged before being committed
4. `git commit -m "<MESSAGE>"` - commits the staged files `-m` indicates that message you would like for the commit.
5. `git push` - pushes the committed changes to the remote repository
6. `git branch` - lists the current branch you are on
7. `git checkout .` - overwrites any unstaged changes, effectively resetting
8. `git checkout -b <BRANCHNAME>` - Creates a new local branch
9. `git push origin <BRANCHNAME>` - pushes a local branch to the remote repository
10. `git fetch` - fetches branchs and or tags
11. `git pull` - pulls any changes on the remote into your local repository
12. `git merge <BRANCHNAME>` - merges the given branch into your current branch


#### Reference: [Git](https://git-scm.com/docs)