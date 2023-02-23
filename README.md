-How to remove Branches locally and remotely . . <br />
    *LOCALLY: <br />
        `git checkout main` <br />
        `git branch -d <branch>` <br />
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