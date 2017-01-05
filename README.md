## project-structure
项目目录结构示意图

![Aaron Swartz](https://github.com/smallerboy/project-structure/blob/master/project_structure.png)

##另外一种构建project目录的思路(2017.1.5)##

**|--AppDelegate**  
**|--General**  
**|--Macro**  
**|--Sections**  
**|--Helper**  
**|--Vendor**  
**|--Resources**

###AppDelegate   
主要存放AppDelegate文件,为整个app的入口文件,单独列出
###General
被重用的Views,Controllers,Categories和DataSource
###Macro
将app中会用的宏定义放入其中(可用pch创建多个类型宏定义文件)
###Sections
对应app的具体单元(导航,瀑布流) 具体单元? 原来是app被区分的几大模块(不同app有不同的区分,但都是会分为不同的模块的)每个具体的单元由对应的及部分组成Views,Controller,ViewModel,Model,NetWork(视使用的模式而定)
###Helper
存放一些帮助类(可以帮助controller瘦身)
###Vendor
存放第三方类库
###Resource
存放app使用到的一些资源  图片需存放到Images.xcassets目录

#####原文链接:<https://github.com/smallerboy/iOS-Best-Practices>

