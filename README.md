
#### push to github
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin <project url>
git push -f origin <branch name>
# -f = froce push 
git push -u origin <branch name>
```

#### Errors
```bash
git branch -M main
git rm -rf --cached .
git add .
```