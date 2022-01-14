## Step 1 :: Create commit in main branch
```
git init
touch 1.txt 2.txt
git add 1.txt 
git commit -m "First"
git add 2.txt 
git commit -m "Second"
git log --oneline
```

## Step 2 :: Create branch and commits
```
git checkout -b develop
touch 3.txt 4.txt
git add 3.txt 
git commit -m "C3"
git add 4.txt 
git commit -m "C3"
git log --oneline
```

## Step 3 :: Working with rebase
```
git switch develop
git log --oneline
git rebase -i <after-this-commit>
```
