# git
git 操作记录

### 恢复到某个 commit 
```
git log //查看日志， 拷贝commit 的 hash
git reset --hard fb162eb1274cc6ee40809ef9ae7d9e5f2d39963a
```

#分支类的操作
### 比较两个分支的差异
```
git diff branch1 branch2 --stat
`--stat` 显示文件列表
```
