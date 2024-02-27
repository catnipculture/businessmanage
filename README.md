# 项目介绍

基于SpringBoot+freemarker实现的人事管理系统分为七大模块：绩效考核，招聘管理，档案管理，工资管理，考勤管理，培训管理，系统管理。本系统最大特色是有强大和灵活的权限控制功能，所有菜单，按钮功能均可由管理通过配置来控制。

系统默认有四个角色：管理员，财务专员，人事专员，普通用户

管理员（admin/admin）：可以操作所有功能

财务专员(cw/cw)：可查看工资管理，考勤管理，培训管理等内容

人事专员（rs/rs）:可查看和管理招聘管理，档案管理，培训管理等内容

普通用户（wdc/wdc）：只可查看工资，打卡考勤，参加培训等



# 环境要求

1.运行环境：最好是java jdk1.8,我们在这个平台上运行的。其他版本理论上也可以。 

2.IDE环境：IDEA,Eclipse,Myeclipse都可以。推荐IDEA; 

3.tomcat环境：Tomcat7.x,8.X,9.x版本均可 

4.硬件环境：windows7/8/10 4G内存以上；或者Mac OS; 

5.是否Maven项目：是；查看源码目录中是否包含pom.xml;若包含，则为maven项目，否则为非maven.项目 

6.数据库：MySql5.7/8.0等版本均可；

# 技术栈

后台框架：springboot、MyBatis

数据库：MySQL

环境：JDK8、TOMCAT、IDEA

# 使用说明

1.使用Navicati或者其它工具，在mysql中创建对应sq文件名称的数据库，并导入项目的sql文件； 

2.使用IDEA/Eclipse/MyEclipse导入项目，修改配置，运行项目； 

3.将项目中config-propertiesi配置文件中的数据库配置改为自己的配置，然后运行；

# 运行指导

idea导入源码空间站顶目教程说明(Vindows版)-ssm篇：

http://mtw.so/5MHvZq 

源码看好后直接在网站付款下单即可，付款成功会自动弹出百度网盘链接，网站地址：[http://codegym.top](http://codegym.top/)。 

其它问题请关注公众号：**IT小舟**,关注后发送消息即可，都会给您回复的。若没有及时回复请耐心等待，通常当天会有回复

# 运行截图

## 界面![微信截图_20240222182048](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222182048.png)

![微信截图_20240222182104](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222182104.png)

![微信截图_20240222182208](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222182208.png)

![微信截图_20240222182215](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222182215.png)

![微信截图_20240222182221](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222182221.png)

![微信截图_20240222182227](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222182227.png)

![微信截图_20240222182233](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222182233.png)

![微信截图_20240222181956](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222181956.png)

![微信截图_20240222182022](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222182022.png)

![微信截图_20240222182036](https://gulimallcativen.oss-cn-shenzhen.aliyuncs.com/bishe/%E5%BE%AE%E4%BF%A1%E6%88%AA%E5%9B%BE_20240222182036.png)
