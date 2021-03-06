  销售的领导DSM、RSM、NSM、MKT都能登陆web端，查看其下属销售和下属销售负责的设备的报表信息：
总共有四类报表：
# 每月故障情况报表
**统计某年某月每种设备故障的统计信息。**
![](/assets/未命名1530078657.png)

>**重要字段含义解释：**
>* **平均修复时间**: 在院维修的修复时间是：工程师结束维修时间-报修时间；寄修的修复时间是：医院收到寄回设备的时间-报修时间。
>* **电话修复次数**：关闭派工前最后一次处理是电话处理的次数。
>* **寄修修复次数**：关闭派工前最后一次处理是寄修处理的次数。
>* **现场修复次数**：关闭派工前最后一次处理是现场处理的次数。

# 每月医院故障情况
**统计某年某月每个医院的统计信息。**
![](/assets/未命名1530078818.png)
>**重要字段含义解释：**
>* **样机保有数量**: 本月只要月初有样机 就认为本月有样机即可
>* **样机停留时间**：所有样机在该院本月停留多少天。
>* **耗材投诉次数**：投诉列表中，设备批号不为空的投诉数量。（耗材都有批号，所以耗材投诉都必填批号）


# 每月设备情况报表
**统计某年某月每类设备的统计信息。**
![](/assets/未命名1530079019.png)
>**重要字段含义解释：**
>* **平均修复时间**: 在院维修的修复时间是：工程师结束维修时间-报修时间；寄修的修复时间是：医院收到寄回设备的时间-报修时间。
>* **电话修复次数**：关闭派工前最后一次处理是电话处理的次数。
>* **寄修修复次数**：关闭派工前最后一次处理是寄修处理的次数。
>* **现场修复次数**：关闭派工前最后一次处理是现场处理的次数。
>* **耗材投诉次数**：投诉列表中，设备批号不为空的投诉数量。（耗材都有批号，所以耗材投诉都必填批号）
>* **安装后平均首次故障时间**：2.每月销售情况报表、每月设备情况报表中，安装后平均首次正常工作时间（参数原用名为“安装后平均首次故障时间”）的计算公式为：
分母：当前报表月份向前滚动1年内新安装的设备数量
分子： 
 1. 滚动一年内，新安装设备故障的 定义 E1=故障时间-安装时间
 2. 滚动一年内，新安装设备没有故障的 定义E2=出报表月份的最后一天-安装时间
 分子=∑（E1+E2）<br/>
 例子： 2018年5月出报表，统计发现2017-6-1到2018-5-31 一年时间内，新安装了10台设备，其中5台是2017-7-1日新安装的2018-1-1日故障的，另外5台是2018-1-1安装的至今没有产生故障，则：<br/>
安装后平均首次正常工作时间= [（2018-1-1减去2017-1-1）*5+（2018-5-31减去2018-1-1）*5]除以分母10

# 每月销售情况报表
**统计某年某月每个销售的统计信息。**
![](/assets/未命名1530079109.png)
>**重要字段含义解释：**
同每月设备情况报表