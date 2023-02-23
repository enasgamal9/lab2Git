-How to remove Branches locally and remotely . . <br />
    *LOCALLY: <br />
        `git checkout main` <br />
        `git branch -d <branch>` <br /><br />
    ------------------------------<br /><br />
    *REMOTELY<br />
        `git push origin --delete <branch>`<br />
        OR<br />
        `git push origin :<branch>`<br /><br />
    ------------------------<br /><br />
-How to list tags . .<br />
    `git tag`<br /><br />
    ------------------------<br /><br />
-How to delete tag locally and remotely . .<br />
    *LOCALLY<br />
        `git tag -d <tag_name>`<br />
    *REMOTELY<br />
        `git push --delete origin tagname`<br />