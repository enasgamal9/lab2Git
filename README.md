-How to remove Branches locally and remotely . . <br />
    *LOCALLY: <br />
        `git checkout master` <br />
        `git branch -d dev` <br />
        `git branch -d test` <br />
    *REMOTELY<br />
        `git push origin --delete dev`<br />
        `git push origin --delete test`<br />
        OR<br />
        `git push origin :dev`<br />
        `git push origin :test`<br /><br />
    ------------------------<br /><br />
-How to list tags . .<br />
    `git tag`<br /><br />
    ------------------------<br /><br />
-How to delete tag locally and remotely . .<br />
    *LOCALLY<br />
        `git tag -d v1.7`<br />
    *REMOTELY<br />
        `git push --delete origin v1.7`<br /><br />
    ------------------------<br /><br />
-Image:<br />
<img src="https://cdn2.vectorstock.com/i/1000x1000/33/71/hello-bubble-vector-9493371.jpg" alt="IMG">
