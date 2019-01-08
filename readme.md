# 简单的实现一个SAAS系统

------
src:
  >* iTrice.SAAS.ProxyHost  -----宿主代理  
  >* iTrice.SAAS.TenantManager   -----租户管理系统
  
## 目前实现了
###  1、租户注册
###  2、启动租户
###  3、租户系统启动
  
 
## 还需要实现的
###  1、完善前面的功能
###  2、实现租户数据库自动迁移
###  3、租户程序添加观察者
###  4、进程间通信
------
正确使用姿势：
>*  1、修改数据库配置文件
>*  2、修改宿主代理程序的地址配置文件
>*  3、选中租户管理系统，执行update-database，对数据库进行迁移。
