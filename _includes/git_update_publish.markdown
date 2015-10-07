UPDATE & PUBLISH
----------------

> List all currently configured remotes

    $ git remote -v

> Show information about a remote

    $ git remote show <remote>

> Add new remote repository, named

    $ git remote add <remote> <url>

> Download all changes from , but don‘t integrate into HEAD

    $ git fetch <remote>

> Download changes and directly merge/ integrate into HEAD

    $ git pull <remote> <branch>

> Publish local changes on a remote

    $ git push <remote> <branch>

> Delete a branch on the remote

    $ git branch -dr <remote/branch>

> Publish your tags

    $ git push --tags

> ...publish a single tag

    $ git push <remote> <tagname>

> Set current branch to track a remote branch

    $ git branch -u <remote>/<branch>

> Publish branch to remote

    $ git push -u <remote> <local-branch>

> Add an additional URL to an existing remote

    $ git remote set-url --add <remote> <url>
