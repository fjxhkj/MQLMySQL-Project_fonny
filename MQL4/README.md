# MT4 平台测试成功

2023年05月15日.

> 如果使用 MySQL 5.7 版本,可以从 `MySQL-5.7.28 x32` 目录中复制 `libmysql.dll` 和 `libmysql.lib` 到 `Libraries` 目录中覆盖原来的文件.

## 修复

- 测试脚本做了改名,能更直观的表示脚本的作用;
- 修复了包括 `Include\MQLMySQL.mqh` 在内的一些错误,并使用 `VSCode` 做了统一的代码美化;

## 注意

- 测试之前需要手动创建 `MyConnection.ini` 中指定的数据库,测试脚本并未演示如何创建数据库;



