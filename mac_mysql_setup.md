#MAC安装mysql

* 采用brew install mysql
* brew info mysql 查看安装信息，可以查看启动信息，配置到登录时启动或者立刻启动
* 要先启动mysql再输入mysql命令。。
* 更改root密码， mysqladmin -u root password "newpass"
* 创建用户create user 'username'@'host' identified by 'password'
* 授权：GRANT privileges ON databasename.tablename to 'username'@'host', priviliges:SELECT,UPDATE, INSERT..