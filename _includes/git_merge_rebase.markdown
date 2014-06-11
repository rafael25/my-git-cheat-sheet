MERGE & REBASE
--------------

> Merge into your current HEAD

    $ git merge <branch>

> Rebase your current HEAD onto
>
> > Don‘t rebase published commits!

    $ git rebase <branch>

> Abort a rebase

    $ git rebase --abort

> Continue a rebase after resolving conflicts

    $ git rebase --continue

> Use your configured merge tool to solve conflicts

    $ git mergetool

> Use your editor to manually solve conflicts and (after resolving) mark
> file as resolved

    $ git add <resolved-file>

    $ git rm <resolved-file>
