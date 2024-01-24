---
title: "Git Bash 命令"
date: 2024-01-24
tags: [git]
---
## 常用命令

| Command | Function |
| :--: | :--: |
| *文件夹操作* |  |
| `cd` | change directory<br>切换目录 |
| `cd ..` | 返回上级目录 |
| `pwd` | print working directory<br>查看当前目录 |
| `ls` or `dir` | list or directory<br>查看当前目录下内容 |
| `ll` | 查看当前目录<br>下详细内容 |
| `ls -al` | 列出所有内容<br>包括隐藏文件 |
| `mkdir` | make directory<br>创建目录 |
| `rmdir` | remove directory<br>删除文件夹<br>（只能删除空文件夹） |
| *文件操作* |  |
| `touch` | 创建文件 |
| `mv` | move<br>移动文件<br>重命名文件 |
| `cp` | copy<br>复制文件 |
| `rm` | remove<br>删除文件<br>`rm -rf 文件夹`<br>循环递进删除文件夹 |
| `cat` | 查看文件内容<br>（全部显示） |
| `less` | 查看文件内容<br>（部分显示）<br>回车-显示一行<br>空格-显示一页<br>b-向上走一页 |
| `echo 'string' > filename.xxx` | 覆盖文件内容 |
| `echo 'string' >> filename.xxx` | 追加文件内容 |
|  |  |
| `clear` or `Ctrl L` | 清屏 |
| `q` | 退出 |

## 补充

| command | function |
| :--: | :--: |
| `cd ~` | 回到根目录 |
| `cd` | 相当于 `cd ~` |
| `rm -r dire` | 删除文件夹 |
| `mv a.txt b.txt` | 重命名文件 |
| `cp a.txt b.txt` | 复制 a 文件到 b |
| `cp a.txt ../xxx/.` | 复制 a 文件到新目录 |
- `-r`: **r**ecursively
	- the process is called "recursive" because, in order to remove a folder, we have to remove everything inside of folder
- `mv a.txt b.txt`: While we are _technically_ moving file contents, this is _effectively_ the same thing as renaming a file!
- a single dot (`.`) represents the _current_ directory (the directory we're in right now)
- Just as two dots (`..`) represents the parent directory (one directory up)
