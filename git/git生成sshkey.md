### Git SSH Key 生成步骤

1.  设置Git的user name和email：
```
$ git config --global user.name "xuhaiyan"
$ git config --global user.email "haiyan.xu.vip@gmail.com"
```
2.  生成id_rsa  id_rsa.pub文件
```
cd ~/.ssh
$ ssh-keygen -t rsa -C “haiyan.xu.vip@gmail.com”
```

3.  将pub文件加入到github