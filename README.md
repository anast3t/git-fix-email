## 1. fix_email
Fixes wrong email in git commits creating new history.

In shell script set your wrong email, correct username and correct email.

To push new commit history run:
```git push --force-with-lease --tags origin 'refs/heads/*'```

Based on - <https://stackoverflow.com/a/30737248/19638034>


## 2. remove_ds_store
Fixes MacOS DS store files in repo. 

Run script and add `**/.DS_Store` in `.gitignore`.

Commit and push changes.

Based on - <https://stackoverflow.com/a/38797342/19638034>
