#### git 常用命令

##### git流程命令

```c
git init //初始化
```
```c
git clone <仓库地址> //克隆文件
```

 ```c
git pull //拉取
 ```
```c
git add . //添加
```
```c
git commit -m //提交
```
```c
git push //推送
```
```c
git merge branch //合并 c
```



##### git分支操作命令

```c
git branch -d [branch name] //删除本地分支
```
```c
git branch [branch name]  //添加本地分支
```

```c
git branch  //查看本地分支
```

```c
git branch -r //查看远程分支
```

```c
git branch -a //查看所有分支
```



##### 查看、改变git连接GitHub的方式

```c
git remote -v //查看
```

```c
git remote rm origin  //移除老的
```

```c
git remote add origin git地址  //添加连接地址 可选https或者ssh，建议使用ssh
```

```c
git remote -v  //查看确认
```



##### 设置使用token访问GitHub

```c
git remote set-url origin https://<token>@github.com/<user.username>/<repo>.git 
//  current token: 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
```



#####  github和git关联

参照博客做法：

https://blog.csdn.net/qq_37623429/article/details/80649266?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522166443084916782412557676%2522%252C%2522scm%2522%253A%252220140713.130102334..%2522%257D&request_id=166443084916782412557676&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduend~default-3-80649266-null-null.142
