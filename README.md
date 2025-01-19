
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
new
#### Errors
```bash
git branch -M main
git rm -rf --cached .
git add .
```

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <project url>
git push -u origin main
```