# git-rebase-ex
Learn how git rebase works.

### Sequence of operations

```
git init
git branch -m main
```

#### On branch `main`

```
# create a.txt
git add a.txt
git commit -m "Add a."
git push origin main
```

#### On branch `feature/f`

```
git checkout -b feature/f
# create c.txt & d.txt
git add c.txt
git add d.txt
git commit -m "Add c & d."
git push origin feature/f
```
