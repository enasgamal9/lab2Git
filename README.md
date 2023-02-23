-How to remove Branches locally and remotely . .
    *LOCALLY:
        `git checkout main`
        `git branch -d <branch>`
    ------------------------------
    *REMOTELY
        `git push origin --delete <branch>`
        OR
        `git push origin :<branch>`
    ------------------------

-How to list tags . .
    `git tag`
    ------------------------

-How to delete tag locally and remotely . .
    *LOCALLY
        `git tag -d <tag_name>`
    *REMOTELY
        `git push --delete origin tagname`