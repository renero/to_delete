# to_delete
Testing branch and versioning.

I work on `develop`. I branch from there to add new features. New features, when stable are merged into `develop`, and from there into `master` to form a new version.

I take the general rules from [here](https://stackoverflow.com/a/14865661).

    (on branch development)
    $ git merge master
    (resolve any merge conflicts if there are any)
    $ git checkout master
    (there won't be any conflicts now)
    $ git merge --no-ff develop
    (remove the branch if you don't want to keep it)
    $ git branch -d contact-form
    (push your changes to remote)
    $ git push origin master

I also do this between features and `develop`.
