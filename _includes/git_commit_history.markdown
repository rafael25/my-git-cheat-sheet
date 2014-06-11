COMMIT HISTORY
--------------

> Show all commits, starting with newest

    $ git log

> Show changes over time for a specific file

    $ git log -p <file>

> Who changed what and when in

    $ git blame <file>

> Show all commits in nice format

    $ git log

      --pretty=format:"%h - %an, %ar : %s"

> Show commits graph

    $ git log --pretty=format:"%h %s" --graph
