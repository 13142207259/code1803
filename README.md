# code_1803b
课堂代码


## GIT
克隆一个新的仓库到当前目录
```
$ git clone git@gitee.com:qq71256459/code_1803b.git
```

查看git项目的状态
```
$ git status
```

添加
```
$ git add -A
$ git commit -m "我的第一次提交"
$ git push origin master
```

### 远程仓库
添加远程仓库地址
```
$ git remote add origin git@gitee.com:qq71256459/code_1803b.git
```

修改远程地址
```
$ git remote set-url origin git@gitee.com:qq71256459/code_1803b.git
```

查看远程地址
```
$ git remote -v
```

添加忽略
```
$ echo "*.wmv" >> .gitignore
```

拉去代码
```
$ git push origin master
```