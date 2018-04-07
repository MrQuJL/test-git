# batch-operator

## 项目背景

我们在项目中经常需要一些数据来测试系统的各个功能（笔者在做商品推荐系统的时候，就需要大量的用户行为数据来计算用户之间的相似度），数据量比较小的时候我们会可以一行行写 SQL 或者直接在数据库的图形化界面客户端上输入数据，但是对于大批量的数据，手写显然有些鸡肋，所以就有了这个 batch-operator。

## 项目目标

* 批量的向数据库中插入数据
* 批量的向数据库中删除数据
* 批量的向数据库中修改数据

## 致谢

个人的力量毕竟有限，如果大家有什么更好的点子，欢迎提出来！

