---
title: Orphan branches
slug: "orphan-branches"
---

An **orphan branch** is like a branch inside a branch. It is usefull to have a `/public`, `/dist` or `/build` folder out of the regular branches. You will have this orphan branch just to keep tracking this build folder and use it for a clean and quick deploy.

1. Add a `.gitignore` file just in case you don't have it yet.

```
touch .gitignore
```

```
echo "public" >> .gitignore
```