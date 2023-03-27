# Node-Modules
## To Remove Node_Modules From GitHub Commit History
```bash
git checkout main
git log
git reset --hard COMMIT_HASH
git push --force
```

## To Remove Node_Modules after git commit -m "Commit Msg"
```bash
git rm -r --cached .

```
