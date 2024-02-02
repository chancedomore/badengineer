# git

## add remote/origin

`git remote add upstream/origin <repo url>`

## view remote

useful when you are setting up a repo on your computer for the first time, or need to double check the cadence of how to push your changes to certain repo.
`git remote -v`

## look at how you screwed things up

`git reflog show --date=relative`

## look at commit log

`git log`
useful for needing to look at what you've added since you started

## look up pr that commit was apart of

`gh pr list --search "commit-sha" --state merged`
this requires the gh cli tool to be installed

## look up git sha of a commit

`git blame -L 1:1 path/to/file.php`
use the git lens extension grab this quicker

## look at most recent branches

`git branch --sort=-committerdate`
minus flips the sort order
