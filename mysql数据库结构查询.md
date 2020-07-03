

### mysql数据库结构查询

1. ssh登录

   密码：hzhu123

   ![Image text](https://github.com/nannan1001/Printer/blob/master/mysql/截屏2020-07-03上午11.53.14的副本.png)

2. 查看docker容器

   密码：hzhu123

   ![Image text](https://github.com/nannan1001/Printer/blob/master/mysql/截屏2020-07-03上午11.58.25.png)

3. 进入mysql容器内

   密码：hzhu123

   ![Image text](https://github.com/nannan1001/Printer/blob/master/mysql/截屏2020-07-03上午11.58.43.png)

4. 执行mysql指令（注意：mysql指令后必须带有分号！！！）

   show databases;

   ![Image text](https://github.com/nannan1001/Printer/blob/master/mysql/截屏2020-07-03上午11.58.59.png)

use printerFulltext //进入该database

show tables;

![Image text](https://github.com/nannan1001/Printer/blob/master/mysql/截屏2020-07-03上午11.59.22.png)

SHOW COLUMNS FROM printerData;

SHOW INDEX FROM printerData;

![Image text](https://github.com/nannan1001/Printer/blob/master/mysql/截屏2020-07-03上午11.59.37.png)

参考资料：

https://blog.csdn.net/guai_shu_shu/article/details/56669568
