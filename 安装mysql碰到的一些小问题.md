##安装mysql碰到的一些小问题
一篇非常详细的安装教程：[mysql数据库的安装](http://blog.csdn.net/bule_sky_wait_me/article/details/71592979)  
虽然作者写得那么详细但是，但是，意外总是存在的。  
但是，百度一搜，也有小伙伴和自己碰到了完全完全一样的问题，顿感舒心了那么一丢丢^_^  
___
####问题一：
MySQL安装失败，提示未安装Visual Studio 2013 Redistributable.   
还是看看小伙伴的提问以及解答吧，[哈哈](http://blog.csdn.net/xx_star1204/article/details/76762175)  
所以在安装了可以匹配新版mysql的vs2013后，mysql安装成功。
___
####问题二：
然而，安装mysql后要启动服务却被提示找不到服务或出现找不到指定文件  
于是我又找到了下面这位小伙伴的经验分享  
[改注册表变量](https://jingyan.baidu.com/article/91f5db1bd298ed1c7f05e315.html)    
___
####问题三：
再尝试启动，启动条开始变绿前进，可是最终却提示“本地计算机上的mysql服务启动后停止。某些服务在未由其他服务或程序使用时将自动”。  
靠，什么鬼！！！
问题就和下面这位小伙伴描述得一模一样，[链接](https://segmentfault.com/q/1010000003963585)  
然后我就把mysql57服务停止，启动mysql服务，终于ok了。  
开始尝试用安装时设置的密码登录，然而，不出意外的，登录失败！！！  
####问题四：修改密码



