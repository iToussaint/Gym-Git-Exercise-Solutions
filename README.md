# GIT Exercise

## Bundle 1

### Exercise 1

```bash
17 git status
18 git init
19 git branch -m master main
20 git add .
21 git commit -m "Initial commit"
22 git remote add origin https://github.com/iToussaint/Gym-Git-Exercise-Solutions.git
23 git push origin main
24 git branch dev
25 git branch
26 git checkout dev
27 git branch test
28 git branch
29 git checkout test
30 git checkout dev
31 git branch -D test
32 git branch
```

### Exercise 2

```bash
   42  clear
   43  git stash -a -m "Stash home file"
   44  git stash list
   45  git stash -a -m "Stash about file"
   46  git stash -a -m "Stash team file"
   47  git stash list
   48  git stash pop stash@{1}
   49  git stash list
   50  git stash pop stash@{1}
   51  git stash list
   52  git add .
   53  git commit -m "Add about and home files"
   54  git push origin dev
   55  git stash list
   56  git stash pop stash@{0}
   57  git add  .
   58  git log --oneline
   59  git log
   60  git log --oneline
   61  git reset --hard b1d43df
   62  git checkout main
```

## Bundle 2

### Exercise 1

```bash
   74  git branch ft/bundle-2
   75  git branch
   76  git checkout ft/bundle-2
   77  git add .
   78  git commit -m "Add services file"
   79  git push origin main
   80  git checkout dev
   81  git log
   82  git checkout ft/bundle-2
   83  git log
   84  git push origin ft/bundle-2
```
