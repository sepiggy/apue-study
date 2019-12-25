# 一 学习方法介绍
## (一) APUE第二版概览 (ch03~ch16为重点)
1. I/O (ch03, ch05, ch14)
2. 文件系统 (ch04, ch06, ch07)
3. 并发
    - 信号 (ch10)
    - 多线程 (ch10, ch11)
4. IPC
    - 进程基础 (ch08)
    - 守护进程 (ch13)
    - 进程间通信 (ch15, ch16)

## (二) 注意事项
1. 系统编程中要弃用root用户, 使用普通用户
2. 有意识地重构代码
3. 课堂重点: 项目, 课堂代码, 面试题, 实验性题目, 推荐书籍课后题

# 二 I/O
## (一) 概述
1. I/O (Input & Output) 是一切实现的基础
2. I/O 分为两大类
    - stdio aka. 标准IO
    - sysio aka. 系统调用IO (文件IO)
## (二) stdio (ch05)
1. FILE 结构体类型贯穿始终
fopen()
fclose()
fgetc()
fputc()
fgets()
fputs()
fread()
fwrite()
printf()
scanf()
fseek()
ftell()
rewind()
fflush()kkk