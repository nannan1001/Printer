先通过ps确认容器是否打开，如果没有，先打开容器

```shell
sudo docker restart printerMSSQL
```



进入容器

```shell
sudo docker exec -it printerMSSQL /bin/bash
```



进入命令行

```shell
/opt/mssql-tools/bin/sqlcmd -S localhost -U SA
```

密码为hZhu_123



进入相应的数据库

```shell
use printerFulltext /*the name of the databases*/
go
```

注意在mssql中没有封号，执行语句为换行后输入go
上一步如果成功可以看到Changed database context to 'printerFulltext'.



查看所有数据库内的table（非初始）

```shell
select * from sysobjects where xtype='u'
go
```



查看table内容

```shell
select * from printerData /*table name*/
go
```

