
#### 创建并切换分支
> git checkout -b dev(分支名)
#### 切换分支
> git checkout dev(分支名)
#### 创建分支
> git branch dev(分支名)
#### 查看当前分支
> git branch
#### 合并dev到当前分支
> git merge dev
#### 查看分支合并图
> git log --graph
#### 提交代码
```bash
git add .
git commit -m "init"
git push origin master(dev)
```