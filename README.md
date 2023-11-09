# A backup

```
git checkout --orphan latest_branch
git add -A 
git commit -m "first commit"
git branch -D master
git branch -m master
git push -f origin master
```