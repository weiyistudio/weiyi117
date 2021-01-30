# weiyi117
爱心助学网站的设计与实现

# 爱心助学网站的设计与实现


#### 介绍
 十余年寒窗苦读，多年怀揣的梦想，终于可以在夏季兑现。金榜题名时，本是人生的一大喜事，可是，对于寒门贫困学子来说，他们的学习成绩虽然优秀，但是由于家里经济的问题，不得不辍学。而社会中有很多爱心人士，由于没有一个诚实可信的平台来帮助困难学生，所以多数为心有余而力不足，爱心助学网站的设计与实现可以解决的这个问题，使爱心人士更加全面的了解困难学生的情况，而孩子们也能继续完成学业，顺利毕业。
    本网站采用Spring MVC+MyBatis框架开发，由于JSP，Servlet，JavaBean这些技术构建繁琐，我们更需要一个能把这些技术整合起来的技术，而Spring MVC正好符合这一要求，所以我选择了这个轻量级的框架。而选择MyBatis是因为MyBatis自动提供了一级和二级缓存（需要配置打开），他的强大的动态SQL，自动化的Session管理，都比手工维护来的方便和安全。
完成爱心助学网的设计与实现。帮助更多想求学却因种种原因而无法求学的贫困山区儿童，让他们得到本属于他们却无法拥有的教育机会。





#### 项目说明
本系统使用SSM框架设计完成，该框架是由Spring+SpringMVC+ Mybatis三个开源框架集合而成。页面部分使用Bootstrip框架完成。
SpringMVC框架通过模型、视图、控制器三个组件组成，模型（Model）主要负责定义变量和对变量的取值和赋值，视图（View）主要负责显示数据等，控制器（Controller）主要负责完成处理用户交互的功能，通常控制器负责从视图读取数据，控制用户的输入，并且向模型发送数据。本系统应用Action、Service和Mapper相互跳转的方式完成系统功能，首先界面向Action发出请求，再由Action去调用Service的相应方法，Service的实现类ServiceImpl再向Mapper发送数据请求，最后由Mapper的实现类MapperImpl中的SQL语句访问数据库，获取相应信息，获取信息后通过Action返回到页面上。通过这一流程完成系统功能。
![输入图片说明](https://images.gitee.com/uploads/images/2021/0126/232748_8a3bb0f7_8587779.png "屏幕截图.png")





#### 项目截图
![输入图片说明](https://images.gitee.com/uploads/images/2021/0126/232757_31641645_8587779.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0126/232810_a8c4f47b_8587779.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0126/232816_6b929501_8587779.png "屏幕截图.png")

![输入图片说明](https://images.gitee.com/uploads/images/2021/0126/232840_1c8bb549_8587779.png "屏幕截图.png")






#### 求助热线


代码有任何问题可联系
联系Q：2762501186

                            
![输入图片说明](https://images.gitee.com/uploads/images/2020/1119/003728_cd598bb9_4865385.jpeg "微信.jpg")           

感谢Github！！  
觉得项目不错的给个Star谢谢大佬！！！
提供无偿review服务
