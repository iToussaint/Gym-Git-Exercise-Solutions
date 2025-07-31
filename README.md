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
