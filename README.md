cpp projects of weidongshan's android video tutorial.

c++快速入门视频教程对应的源码, 韦东山Android系统完全开发视频教程的一部分

【前言】
    亲爱的同学们，欢迎学习百问网课程！本系列课程由知名嵌入式专家韦东山老师投入大量的心力、精心录制，
    课程基于jz2400开发板，面向初学者。无论你是零基础、有一定的单片机基础、还是有一定的嵌入式linux基础，
    都能通过本系列课程进入、深入嵌入式linux的世界，让我们一起跟着韦东山老师遨游于奇妙的嵌入式linux开发之路吧！

【教程学习】百问网所有视频教程仅提供在线学习观看服务
    C++入门视频教程(共25节) 学习地址：
        https://www.100ask.net/detail/p_5e622784d946e_8PiZX2MR/8

【答疑解惑】
    论坛驻扎多名老师及其他同学的经验(爬坑)分享，遇到问题时论坛提问、搜索，解决更快
        http://bbs.100ask.net
    讨论群
        学习交流微信群：http://wiki.100ask.org/Community#%E5%BE%AE%E4%BF%A1%E4%BA%A4%E6%B5%81%E7%BE%A4
        学习交流QQ群： http://wiki.100ask.org/Community#QQ%E4%BA%A4%E6%B5%81%E7%BE%A4
    也可以上淘宝直接一对一咨询技术
        https://100ask.taobao.com 

【关注我们】
    百问网官方wiki：http://wiki.100ask.org
    百问网官方论坛：http://bbs.100ask.net
    百问网官网：http://www.100ask.net
    微信公众号：百问科技
    CSDN：https://edu.csdn.net/lecturer/90
    B站：https://space.bilibili.com/275908810?from=search&seid=10505231074028238949
    知乎：https://www.zhihu.com/people/www.100ask/
    微博：https://weibo.com/888wds?topnav=1&wvr=6
    电子发烧友学院：http://t.elecfans.com/teacher/3.html

    
【课程目录】
    第1课_C++基础知识
        第1课第1节_c++类的引入
        第2课第1节_c++基础知识_访问控制
        第2课第2节_c++基础知识_程序结构
        第2课第3节_c++基础知识_重载_指针_引用
        第2课第4节_c++基础知识_构造函数
        第2课第5节_c++基础知识_静态成员_友员
        第2课第6.1节_c++基础知识_运算符重载_类外函数
        第2课第6.2节_c++基础知识_运算符重载_成员函数
    第2课_C++面向对象编程
        第3课第1节_c++面向对象编程_访问控制和继承
        第3课第2节_c++面向对象编程_多重继承
        第3课第3节_c++面向对象编程_再论构造函数
        第4课第1节_c++面向对象编程_多态
        第4课第2节_c++面向对象编程_类型转换
    第3课_C++高级编程
        第5课第1节_c++高级编程_抽象类_概念
        第5课第2节_c++高级编程_抽象类界面
        第6课第1节_c++高级编程_函数模板_引入
        第6课第2节_c++高级编程_函数模板_重载
        第6课第3节_c++高级编程_类模板
        第7课_c++高级编程_异常
        第8课第1节_c++高级编程_自己实现智能指针
        第8课第2节_c++高级编程_Android轻量级指针
        第8课第3节_c++高级编程_Android弱指针的引入
        第8课第4节_c++高级编程_Android强弱指针的实现与使用
    第4课_C++设计模式
        第9课第1节_设计模式_单例模式
        第9课第2节_设计模式_桥接模式    


2023 10 22

（0）10.0
基类内部的私有成员，派生类无法直接调用，需要接触基类内部的成员函数；

（1） 10.3
基类里面有保护成员，派生类可以在其成员函数内部使用，但是如果要外部使用，
需要在派生类内部使用using 基类保护成员，

（2）10.4
保护继承和私有继承无法调用基类的公共成员函数和公共成员变量；

（3）10.6
派生类可以复写基类的成员函数；

（4）
派生类重写基类成员之后，会有两次调用；