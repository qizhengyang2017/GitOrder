# GitOrder
git 命令的收集以及总结

https://education.github.com/git-cheat-sheet-education.pdf

## git操作指令


### 远程同步

我在github网页上有修改文件。如何同步到本地？本地也有修改的文件
会先拉取远程最新的提交，然后把你本地的提交“接”在它后面（不产生多余 merge）。
```shell
git pull --rebase origin main
git push origin main
```

查看文件/目录的提交历史
```shell
git log -- wang_RNA-seq_lsf/
git log -- wang_RNA-seq_lsf/12DPA_ID1.lsf
```

old作为第一个参数，new的作为第二个参数。这样：+开头的行表示新增，-开头的行表示删除
```shell
git diff c92b73 bed99d -- wang_RNA-seq_lsf/12DPA_ID1.lsf
```


### 版本回退


### 工作原理



### 撤销修改



### 分支管理







### 问题or理解

