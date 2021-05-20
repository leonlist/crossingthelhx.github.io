---
title: Online_Quiz
date: 2021-04-23 15:58:54
tags:
---

# 项目内容

设计一个简单的在线考试系统

老师上传一个测验和考试学生列表。测验的格式是纯文本，主题题可附答案，主观题可附参考答案。系统将测验做出网页的格式，方便学生替换，填写。

老师可以批改每次测验每个同学的试卷。答题结果如果是主题题，则自动改分，如果是主观题，则老师手动改分。

老师可以下载每次测验所有同学的成绩。

学生可以登录答题（只有在学生列表中的学生才能答题）。

学生可以看到每次测验自己的分数以及做题详情。

# 需求分析

在线考试系统的角色主要分两类：学生和老师。

学生的功能基本操作有：登录、在线考试、在考试后一段时间查看分数及对应题目的解析、修改个人信息。

学生功能模块有：学生主模块、考试模块、登录模块、个人信息模块

```
//学生主模块 
    —————— 考试管理
    |   
学生 —————— 登录
    |
    ——————  个人信息管理 

//学生考试模块       
       —————— 查看考试
       |
       —————— 进行考试                 
       |              
考试模块—————— 提交试卷
       |
       —————— 查看分数
       |
       —————— 查看解析


//学生登录模块
登录模块———— 登录
       |
       ———— 找回密码   

//学生个人信息模块
       ——————  上传头像
       |   
个人信息 —————— 修改密码
       |
       ——————  修改个人信息
```

老师的基本操作有对学生信息、试卷信息、学生考试、老师信息等进行相应的增删改查工作。

老师功能模块有：老师主模块、学生信息管理模块、考试信息管理模块、试卷信息管理模块、老师用户信息模块

```
//老师主模块
    —————— 学生信息管理
    |
    —————— 个人信息管理                
    |              
老师 —————— 考试信息管理
    |
    —————— 试卷信息管理
    |
    —————— 考试批阅管理
```

# 参考资料

[超详细搭建PhpStorm+PhpStudy开发环境](https://blog.csdn.net/u012861467/article/details/54692236?utm_medium=distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-5.control&dist_request_id=&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-5.control)

[版本管理（三）之phpstorm上传代码到GitHub](https://blog.csdn.net/qq_38191191/article/details/80458745?utm_medium=distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-14.control&dist_request_id=1331973.6935.16185418682915173&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2~default~BlogCommendFromBaidu~default-14.control)

[PHP和MySQL Web开发(原书第5版) 原版pdf+完整源码_密码：b93q](https://pan.baidu.com/s/10Ir5YDIOvm4ZOhFEBkUCNA)

[PHP 教程|菜鸟教程](https://www.runoob.com/php/php-tutorial.html)

[ThinkPHP5.0](https://www.kancloud.cn/manual/thinkphp5/118003)

