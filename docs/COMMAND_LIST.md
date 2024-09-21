# Command List

## Git

Show line endings for files tracked in the repo:

```
git ls-files --eol
```

1. If Git isn't tracking the line endings correctly, try clearing the cache:

```
git rm -r --cached .
```

2. Then do a hard reset to apply the changes:

```
git reset --hard
```
