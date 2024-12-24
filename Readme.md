## Test Branching
now this is in 'mybranch'

Note:
to create a new repository on the commandline
```textmate
echo "# Test-Branching" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/hpatel3747/Test-Branching.git
git push -u origin main
```
push an existing repository on the commandline
```textmate
git remote add origin https://github.com/hpatel3747/Test-Branching.git
git branch -M main
git push -u origin main
```
merge this file with main branch
