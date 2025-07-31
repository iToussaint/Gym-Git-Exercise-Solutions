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

### Exercise 2

```bash
   86  git checkout main
   87  git add .
   88  git commit -m "Add Bundle 2 Exercise 1 commands in README file"
   89  git push origin main
   90  git pull
   91  git pull remote main
   92  git push origin main
   93  git pull origin main
   94  q
   95  git status
   96  git push origin main
   97  git checkout -b ft/service-redesign
   98  git branch
   99  git add .
  100  git commit -m "Add changes in services file"
  101  git push origin ft/service-redesign
  102  git checkout main
  103  git add  .
  104  git commit -m "Add changes in services file in main branch"
  105  git push origin main
  106  git checkout ft/service-redesign
  107  git diff ft/service-redesign main
  108  git checkout main
  109  git merge ft/service-redesign
  110  git checkout ft/service-redesign
  111  git merge ft/service-redesign
  112  git status
  113  git log
  114  git reset --hard 0c9ef04
  115  git branch
  116  git checkout ft/service-redesign
  117  git checkout main
  118  git merge ft/service-redesign
  119  git status
  120  git checkout main
  121  git status
  122  git commit -m "Merge the conflicts"
  123  git push origin main
  124  git merge ft/service-redesign
  125  git status
  126  git log
  127  git status
  128  git push
  129  git push --set-upstream origin main

```

## Bundle 3

### Exercise 1

```bash
   13  git checkout -b ft/team-page
   14  git add .
   15  git commit -m "Add team file"
   16  git push origin ft/team-page
   17  git checkout main
   18  git checkout -b ft/contact-page
   19  git checkout ft/team-page
   20  git log --oneline
   21  git checkout ft/contact-page
   22  git cherry-pick ad63d87
   23  git log
   24  git add .
   25  git commit -m "Modify the team file in ft/contact-page"
   26  git push origin ft/contact-page
   27  git branch ft/faq-page
   28  git checkout ft/faq-page
   29  git add .
   30  git commit  -m "Add faq page"
   31  git push origin ft/faq-page
   32  git revert ad63d87
   33  git branch --graph
   34  git log
   35  git reset --hard dfdd50
   36  git status
   37  git checkout ft/contact-page
   38  git log
   39  git reset --hard 6486c9e
   40  git branch
   41  git log --oneline
   42  git reset --hard 412bf8a
   43  git checkout ft/team-page
   44  git log
   45  git log --oneline
   46  git checkout ft/contact-page
   47  git cherry-pick ad63d87
   48  git log
   49  git add contact.html
   50  git commit -m "Add contact file"
   51  git push origin ft/contact-page
   52  git push origin ft/contact-page
   53  git pull origin ft/contact-page
   54  git push origin ft/contact-page
   55  git branch
   56  git checkout ft/faq-page
   57  git revert ad63d87
   58  git pull origin ft/faq-page
   59  git log
   60  git reset --hard dfdd506
   61  git pull origin ft/faq-page
   62  git revert dfdd506
   63  git log
   64  git status
   65  git push origin ft/faq-page
   66  history
```

### Exercise 2

```bash
   67  git checkout main
   68  git status
   69  git add .
   70  git commit  -m "Add Bundle 3 Exercise 1 commands in README file"
   71  git push origin main
   72  git checkout ft/faq-page
   73  git branch ft/home-page-redesign
   74  git branch
   75  git checkout main
   76  git add .
   77  git commit -m "Add some changes in main branch"
   78  git push origin main
   79  git checkout ft/home-page-redesign
   80  git rebase main
   81  git status
   82  git add .
   83  git commit -m "Make some changes in ft/home-page-redesign branch"
   84  git checkout main
   85  git checkout ft/home-page-redesign
   86  git push origin ft/home-page-redesign
```

## Bundle 4

### Exercise 1

```bash
   94  git checkout main
   95  git remote add https://github.com/iToussaint/git-copy.git
   96  git remote -v
   97  git remote -v
   98  git remote add git-copy https://github.com/iToussaint/git-copy.git
   99  git remote -v
  100  git remote -rm git-copy
  101  git remote rm git-copy
  102  git remote -v
  103  git  remote add git-copy https://github.com/iToussaint/git-copy.git
  104  git remote -v
  105  git add .
  106  git commit -m "Add some changes in home file"
  107  git push origin main
  108  git push git-copy main
```

### Exercise 2

```bash
  117  git checkout -b ft/footer
  118  git add .
  119  git commit -m "Add some changes in ft/footer branch"
  120  git add  .
  121  git commit -m "Add a second commit in ft/footer branch"
  122  git push origin main
  123  git push origin ft/footer
  124  git checkout main
  125  git branch ft/squashing
  126  git checkout ft/squashing
  127  git merge --squash ft/footer
  128  git status
  129  git commit -m "Footer changes squashing"
  130  git push origin ft/squashing
```

## Bundle 5

### Exercise 2

```bash
   15  git clone https://github.com/iToussaint/git-cafe-exercise.git
   16  cd git-cafe-exercise
   17  git add index.html
   18  git commit -m "Change Welcome to our place into Welcome to our Restaurant"
   19  git push origin main
```

## Bundle 6

### Exercise 1

```bash
   23  git branch new-feature
   24  git branch
   25  git checkout new-feature
   26  git status
   27  git add .
   28  git commit -m "Add menu file and some changes"
   29  git push origin new-feature
```

### Exercise 2

```bash
   32  git checkout main
   33  git checkout -b new-bug-fix
   34  git add index-4.html
   35  git commit -m "Change index-4 file's title to Contact"
   36  git push origin new-bug-fix
```
