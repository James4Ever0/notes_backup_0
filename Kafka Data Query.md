---
created: 2021-12-30T18:13:26+08:00
modified: 2021-12-30T18:17:13+08:00
---

# Kafka Data Query

大数据存储综合实验

下载高速公路ETC入深圳数据， 数据量:178396条

https://opendata. sz. gov. cn/ da ta/ da taSet/ toDataDetails/2920000403621数据样例:

要求

(1)每秒产生50+条数据，可以采用网络压力测试工具产生多点并发的高速数据流https://blog. csdn. net/ moonpure/ artic1e/ detai1s/72674374，例如JMeter

(2)利用Kafka对高速数据进行缓存

(3)利用HBase或者MIyCatHlysq1对数据进行存储。

(4)如果采用MyCatHlysq1方式存储数据，需要设计业务逻辑对数据进行分片，并对全局数据进行查询和统计

(5)如果采用HBase方式存储数据，需要设计业务逻辑对rowkey进行设计，并对数据进行“key-value”查询。

(6)对两种方式查询或者统计的结果进行可视化展示，要求每分钟一-次对结果进行刷新。

Report Template:

7.实验目标和实验环境

8.实验内容，

9.实验步骤和结果。

.10.结论与讨论。