UNDO
----

> Reset a file to a specific commit

    $ git checkout <commit> <file>

> Discard all local changes in your working directory

    $ git reset --hard HEAD

> Discard local changes in a specific file

    $ git checkout HEAD <file>

> Revert a commit (by producing a new commit with contrary changes)

    $ git revert <commit>

> Reset your HEAD pointer to a previous commit
>
> > ...and discard all changes since then

    $ git reset --hard <commit>

> ...and preserve all changes as unstaged changes

    $ git reset <commit>

> ...and preserve uncommitted local changes

    $ git reset --keep <commit>
