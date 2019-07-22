# nginx 配置文件

**修改 nginx.conf 为你自己的网页添加代理或者路由**

nginx 静态文件目录地址: https://github.com/itguang/html
添加你自己的网页上传,我会合并到服务器的

> /etc/nginx

nginx -s reload  ：修改配置后重新加载生效

nginx -s stop  :快速停止nginx
         quit  ：完整有序的停止nginx
         
         
## 启动mysql：

方式一：sudo /etc/init.d/mysql start
方式二：sudo service mysql start

停止mysql：
方式一：sudo /etc/init.d/mysql stop
方式二：sudo service mysql stop

重启mysql：
方式一：sudo/etc/init.d/mysql restart
方式二：sudo service mysql restart
