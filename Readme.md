# git连接远程仓库

- 创建本地用户名和本地邮箱:

```bash
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```

- 生成秘钥

```bash
$ ssh-keygen -t rsa -C "youremail@example.com"
```

- 创建远程仓库

将生成的公钥放在远程仓库设置中

- 创建连接

```bash
git remote add origin git@github.com:joker-hkai/learnGit.git
```

