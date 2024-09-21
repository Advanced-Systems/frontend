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

## ESLint

Display all rules that are currently being applied:

```
./node_modules/.bin/eslint --print-config *.ts
```

Where:

- `"off"` or `0` - Turns the rule **off** (no enforcement).
- `"warn"` or `1` - Turns the rule **on** as a **warning** (shows a warning but doesn't fail the build).
- `"error"` or `2` - Turns the rule **on** as an **error** (fails the build if the rule is violated).
