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