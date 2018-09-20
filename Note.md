# GIT指令
## 全局初始化(不用记忆)
```
git config --global user.name zhy
git config --global user.email herofeel@sina.cn
```
## 本地仓库初始化
```
git clone https://github.com/zhy23333/test.git
```
>初始化好的git仓库会有一个.git文件夹，使用`ls -a`可以查看(在Linux和mac中1⃣️.开头的文件是不见的隐藏文件，windows则不受影响)
## 查看git当前状态（文件是否已经被git管理，是否修改了未提交）
```
git status 
```

## 提交所有更改
```
git add -A
git commit -m "update"
```

## 推送所有更改到远程服务器
```
-- 第一次推送
git push -u origin master
-- 后面的推送
git push 
```

## 版本回退
```
git reflog
git reset --hard <hash>
```

## 分支管理（当你没有把握修改正式版的软件不产生BUG的时候创建一个子分支，切换到子分支和正式版软件并行开发，不会影响主分支的开发,当子分支开发完成并且测试没有BUG的时候再合并到主分支上，相当于测试版开发）
```
-- 创建分支
git branch chy
-- 切换分支
git checkout chy
-- 合并分支（切换到主分区执行这句话）
git merge 
```
