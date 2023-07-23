# Git-SSH
**SSH生成本地秘钥拉取自己的私有库**

1. 安装好Git客户端后，右击鼠标点击Open Git Bash here
2. 首先设置用户名和邮箱
   > * git config --global user.name "XXX"
   > * git config --global user.email "XXXXXXXXX@qq.com" （当然，不一定是QQ邮箱）
 
3. 生成密钥文件执行
  > ssh-keygen -t rsa -C "XXXXXXXXX@qq.com" （此处用上面的邮箱）
4. 执行完上述命令后可以找到
> ![image](https://github.com/fengzuyi/Git-SSH/assets/140140978/87b09de2-139d-417d-879e-d286a8c19d4c)
5. 然后登录github，点击添加新的SSH-key
> ![image](https://github.com/fengzuyi/Git-SSH/assets/140140978/639efdbe-784e-4173-a2e9-f400a9bc4dfe)
> ![image](https://github.com/fengzuyi/Git-SSH/assets/140140978/169336d1-2791-4ff4-a07f-135974880211)
> ![image](https://github.com/fengzuyi/Git-SSH/assets/140140978/d4576344-88b0-4674-a116-cacbf2d784a3)
> ![image](https://github.com/fengzuyi/Git-SSH/assets/140140978/4e659a01-0938-4af9-8acc-406b9451d5b2)
6.以上操作完成之后就可以复制库里面的SSH地址了
> ![image](https://github.com/fengzuyi/Git-SSH/assets/140140978/9313a3a9-0248-49e8-873f-30bd0a18d224)
7. 完成拉取
> git pull 刚才粘贴的SSH地址 master（所要拉取到哪个分支）
