# UnixFileSystem

## 0. 吐槽
　　这个程序写起来好像C项目啊

- 目前发现的问题
```
direct 对象会有一定的空当
具体的要看inode.h去看Direct类的定义出处
```

## 1. 概述
　　文件系统是操作系统中最不可缺少的一部分，基于Unix文件管理系统的设计....

## 2. 课程设计的任务和要求

#### 2.1 设计任务
　　多用户，多级目录结构的文件系统的设计和实现，模拟实现Unix文件系统。
#### 2.2 设计要求
- 模拟Unix（或者Linux和FAT）文件系统的功能功能:
1. 多用户
2. 多级目录
3. 具有login和系统初始化（建立文件卷，提供登录模块）
4. 文件的创建: create
5. 文件的打开: open
6. 文件的读：read
7. 文件的写:  write
8. 文件的关闭: close
9. 删除文件: remove
10. 创建目录: mkdir
11. 改变目录: chdir
12. 列出文件目录: dir
13. 退出: logout
14. 格式化: format
　　

## 3. 算法和数据结构
## 4. 程序实现
