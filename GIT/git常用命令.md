#### git 常用命令

##### git流程命令
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



##### github查看git连接方式

```c
git remote -v //查看
```

```c
git remote rm origin  //移除老的
```

```c
git remote add origin git地址  //添加连接地址 可选https或者ssh，https每次都啊哟输入密码，建议使用ssh
```

```c
git remote -v  //查看确认
```



##### github设置token访问

```c
git remote set-url origin https://<token>@github.com/<user.username>/<repo>.git 
//  current token: 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
```





