# signed-off DCO

Forgot to sign-off commits? Do this!!

#### Run this to sign-off the last two commits.

```
git filter-branch --msg-filter "cat - && echo && echo 'Signed-off-by: Your Name <Your.Name@example.com>'" HEAD~2..HEAD
```

#### Then force push them to the remote repo with the `-f` option:

```
git push -f origin
```
