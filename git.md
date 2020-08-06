git 常用易忘指令总结

版本回退

```
git reset --hard [commit_ID]
```

强制提交

```
git push -f
```

查看特定文件历史更改记录

```
git log [path]
```

查看某次commit的的详情修改

```
git show [commit_ID]
```

撤销本地特定文件的修改

```
git checkout [file_Name]
```

对某个文件进行撤销git add操作

```
git reset HEAD [XXX.html]
```

撤销最近一次git commit 

```
git reset --soft HEAD^
```

查看某次commit`内容`

```
git show [commit_ID]
```

合并单次commit

```
git cherry-pick [commit_ID]
```

撤销特定commit 顺序  从新到旧

```
git revert [最新commitId] [第二commitId] [第三commitId]
```

提交本地tag

```
git push origin [tag_ID]
```

推送本地所有tag

```
git push origin --tags
```

分支合并

```
git merge [branch_Name]
```

