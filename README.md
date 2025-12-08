# databackup

### 建一個全新的 orphan 目錄
```shell
git checkout --orphan latest
git add -A
git commit -m "Initial commit"
```

### 刪除舊歷史
```shell
git branch -D main
git branch -m main
```

### 強制推到 remote
```shell
git push -f origin main
```
