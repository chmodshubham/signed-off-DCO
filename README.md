# signed-off DCO

Forgot to sign-off commits? Do this!!

#### Run this to sign-off the last two commits.

```bash
git filter-branch --msg-filter "cat - && echo && echo 'Signed-off-by: Your Name <Your.Name@example.com>'" HEAD~2..HEAD
```
```bash
#example
git filter-branch --msg-filter "cat - && echo && echo 'Signed-off-by: Shubham Kumar shubham.kumar@ramanujan.du.ac.in'" HEAD~2..HEAD

# PR box
Signed-off-by: Shubham Kumar[shubham.kumar@ramanujan.du.ac.in](mailto:shubham.kumar@ramanujan.du.ac.in)
```

#### Then force push them to the remote repo with the `-f` option:

```bash
git push -f origin
```
