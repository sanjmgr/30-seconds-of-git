---
title: Add a submodule
tags: repository,submodule
expertise: advanced
firstSeen: 2021-04-08T20:05:15+03:00
lastUpdated: 2021-04-13T21:10:59+03:00
---

Adds a new submodule to the repository.

- Use `git submodule add <upstream-path> <local-path>` to add a new submodule from `<upstream-path>` to `<local-path>`.

```shell
git submodule add <upstream-path> <local-path>
```

```shell
git submodule add https://github.com/30-seconds/30-seconds-of-code ./30code
# Creates the directory `30code` containing the submodule from
# "https://github.com/30-seconds/30-seconds-of-code"
```
