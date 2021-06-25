## Reset workshop

### 1. Create file and commits
```
mkdir demo-reset
cd demo-reset
git init

touch 1.txt
git add .
git commit -m "1"

touch 2.txt
git add .
git commit -m "2"

touch 3.txt
git add .
git commit -m "3"

touch 4.txt
git add .
git commit -m "4"

touch 5.txt
git add .
git commit -m "5"

touch 6.txt
git add .
git commit -m "6"

touch 7.txt
git add .
git commit -m "7"
```

See git history
```
git log --oneline
```

### 2. Soft reset
```
git reset --soft HEAD~1
git log --oneline
git status
```

### 3. Mixed reset
```
git reset --mixed HEAD~1
git log --oneline
git status
```

### 4. Hard reset
```
git reset --hard HEAD~1
git log --oneline
git status
```

