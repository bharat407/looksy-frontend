# GitHub Readme

## Cmds

**Create a new branch from current branch**

```cmd
git checkout -b <branch-name>
```

**Switch to local 'main' branch**

```cmd
git checkout main
```

**List all local branches**

```cmd
git branch
```

**List all branches (local + remote)**

```cmd
git branch -a
```

**List all remote-tracking branches**

```cmd
git branch -r
```

## Pushing & Pulling

**Push branch into remote repo**

```cmd
git push origin <branch-name>
```

**Push updates to remote 'main'**

```cmd
git push origin main
```

**Push local commits to the current remote branch**

```cmd
git push
```

**Fetch updates from all remote repos**

```cmd
git fetch
```

**Fetch & merge latest changes from origin/main**

```cmd
git pull origin main
```

## Merging

**Merge a specific branch into current branch**

```cmd
git merge <branch-name>
```

## Working with Files

**Stage files for commit**

```cmd
git add <file>
```

**Stage all files**

```cmd
git add .
```

**Commit staged files**

```cmd
git commit -m "Your commit message"
```

## Status & Cloning

**Check current status**

```cmd
git status
```

**Clone a repository**

```cmd
git clone <repo-url>
```
