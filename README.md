## 1. change_identity
Changes identity in git commits creating new history.

In shell script set your old email, correct username and correct email.

To push new commit history run:
```git push --force-with-lease --tags origin 'refs/heads/*'```

Based on - <https://stackoverflow.com/a/30737248/19638034>


## 2. remove_ds_store
Fixes MacOS DS store files in repo. 

Run script and add `**/.DS_Store` in `.gitignore`.

Commit and push changes.

Based on - <https://stackoverflow.com/a/38797342/19638034>

## 3. pretty_log 
Shows beautiful commit tree

Based on - <https://git-scm.com/docs/pretty-formats>
