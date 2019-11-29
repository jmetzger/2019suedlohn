# GIT Training in Suedlohn 
## git branch --contains 

Show all branches that contain a specific commit

https://coderwall.com/p/7fp5dg/finding-git-branches-which-contain-the-specified-commit

## show all tickets within a branch 

First of all you need a pattern, like [INF-0001].
You can then use that pattern to search for these commit within the current branch.

```
git log --grep "\[.*\]"
git log --grep "\[EW-.*\]" master..release-1
# 
git log --no-merges 
git log --since=2019-06-12
```
## show all files that hava changed in a release branch 

Shows all the files that have been changed since the branch was created 

git diff --name-only develop..release-1

## git guis under linux

https://git-scm.com/download/gui/linux

## git hooks 

https://git-scm.com/docs/githooks#_post_merge
https://www.underthecocotree.co.uk/blog/a-tale-of-sourcetree-and-git-hooks
