# Git

## Git环境配置

### Git和SVN主要区别

SVN是集中式版本控制系统，版本库集中在中央服务器，工作时需要先从中央服务区获取最新版本再进行工作。结束后需要将自己完成的内容推送到中央服务器。集中式版本控制必须联网才能工作，对网络带宽要求较高。

Git是分布式版本控制系统，没有中央服务器，每个人的电脑都是一个完整的版本库，版本都存储在自己的电脑上，工作时不必联网。需要协同时（例如自己电脑上修改了文件A，其他人也修改了文件A），只需要把各自修改的文件推送给对方，就可以互相看到对方的修改。

- Git Bash：Unix和Linux风格的命令行，推荐使用
- Git CMD：Windows风格的命令行
- Git GUI：图形界面的GIt，不推荐使用



### 常用的Linux命令

```bash
1. cd  改变目录
2. cd ..  回退到上一个目录
3. pwd  显示当前所在目录路径
4. ls  列出当前目录中的所有文件，ll列出的内容更加详细
5. touch  新建一个文件
6. rm  删除一个文件
7. mkdir  新建一个文件夹
8. rm -r  删除一个文件夹    ！！！一定不要尝试使用rm -rf /，会递归删除所有文件
9. mv  移动文件
10. reset  重新初始化
11. clear  清屏
12. history  查看历史命令
13. help  帮助
14. exit  退出
```



### Git配置

- 查看配置  `git config -l`
- 查看系统config  `git config --system --list`
- 查看当前用户（global）配置  `git config --global  --list`

==相关配置文件所在路径==

- Git\etc\gitconfig  ：Git 安装目录下的 gitconfig   --system 系统级
- C:\Users\Administrator\ .gitconfig   只适用于当前登录用户的配置  --global 全局

==设置用户名与邮箱（用户标识，必要）==
