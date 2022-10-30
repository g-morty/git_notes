### <center> Git常用命令
**1、设置全局名字、邮箱**

```
git config --global user.name <name>
git config --global user.email <email>
```

**2、查看全局配置**

```
git config --global --list
```

**3、删除配置**

```
git config --global --unset <config>
```

**4、生成秘钥**

```
ssh-keygen -t rsa -C <email>
查看公钥(mac):cat ~/.ssh/id_rsa.pub
查看公钥(win):cat C:\Users\<user>\.ssh\id_rsa.pub
```

**5、项目初始化**

```
git init
```

**6、添加远程仓库**

```
git remote add <origin> <address>

```

**7、提交代码**

```
git add .
git commit -m <describe>
git push
```




git commit --amend 修改最后一次提交描述
git status 查看项目状态
git rm --cached <file/dir> 将文件从暂存区清除
git rm <file/dir> 将文件从项目中清除
git reset HEAD <file/dir> 将文件仓库、暂存区中清除
git checkout -- <file/dir> 将仓库内的文件覆盖工作区
