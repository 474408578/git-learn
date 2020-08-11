#### 0、VS Code玩转git
两个插件：git history 和gitLens

#### 1、 git操作
```
git init
git status
git add file   # 将文件从工作区添加到缓冲区
git commit -m "message" # 将文件从缓冲区提交到归档区
git push origin master # 将文件push到名为orgin的远程仓库的master分支

git log 
git relog

git reset [options] 版本号  # 代码的回滚


 git reset --mixed c9d5f9e5355cbee6a53798cd6466fcb43ac3bf21  # 指定版本号对归档区进行回滚，显然会包括归档区
        --mixed: 针对归档区和缓冲区
        --hard: 针对归档区和缓冲区以及工作区全部都回滚到指定的版本
        --soft: 只回滚归档区，缓冲区和工作区不会回滚
```

#### 2、分支操作
适合多人协作
```
git branch -v  # 查看当前的分支
git checkout -b 分支名  # 创建并切换到创建的分支

```