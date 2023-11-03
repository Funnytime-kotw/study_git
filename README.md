# Git

## SVN和Git

集中式版本控制系统，版本库集中放在中央服务器。下载和上传都要经过中央服务器。

Linus Torvalds于2005年开发了开源分布式版本控制工具Git，分为本地仓库和远程仓库，每一个客户端都保存了完整的代码和历史记录。

TortoiseGit是Git的一个图形化操作工具

## Git基本操作

![](assets/1.jpg)

| 命令                     | 作用                                           |
| ------------------------ | ---------------------------------------------- |
| git init                 | 初始化，创建 git 仓库                          |
| git status               | 查看 git 状态 （文件是否进行了添加、提交操作） |
| git add 文件名/git add . | 添加，将指定文件添加到暂存区                   |
| git commit -m '提交信息' | 提交，将暂存区文件提交到历史仓库               |
| git log                  | 查看日志（ git 提交的历史日志）                |

### `git commit`退出

仅使用`git commit`而不使用`git commit -m`时会进入vim编辑器中

保存并退出：

- 按 `Esc` 键退出编辑模式，英文模式下输入 `:wq` ，然后`回车`(write and quit)。
- 按 `Esc` 键退出编辑模式，大写英文模式下输入 `ZZ` ，然后`回车`。

不保存退出：

- 按 `Esc` 键退出编辑模式，英文模式下输入 `:q!` ，然后`回车`。
- 按 `Esc` 键退出编辑模式，英文模式下输入 `:qa!` ，然后`回车`。





## 使用GitHub

### 基本使用

clone项目

```bash
git clone xxx
```

搜索技巧

- 找百科大全 awesome xxx
- 找例子 xxx sample
- 找空项目架子 xxx starter / xxx boilerplate
- 找教程 xxx tutorial

### GitHub Desktop