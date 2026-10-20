# Remote Repos
---

### Azure DevOps as remote repository
***Use this only once to setup remote repo***
`git remote add aaa https://GirishMVP@dev.azure.com/GirishMVP/Project%20Bergen/_git/Project%20Bergen`

`git push --set-upstream aaa master`

***For every subsequent push***
`git push aaa master`

---

### GitHub as remote repository

***Use this only once to setup remote repo***
`git remote add aaa https://github.com/girishuppal/git-007.git`

`git push --set-upstream aaa master`

***For every subsequent push***
`git push aaa master`

---



git clone <<repo path >>
git push
git push –all (push all branches)
git pull (equivalent to fetch and merge)
git remote
git remote add origin <url>
git push –u origin –all
git push –set-upstream origin master

git remote rm origin
git  merge <new-branch>
git fetch (download from remote branch)
git merge (merge local machine changes)

