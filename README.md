﻿# codecraft

#### 介绍
华为软件精英挑战赛是华为公司面向在校大学生举办的大型软件竞赛，从2015年至今已成功举办四届。在软件精英挑战赛的舞台上，我们相信您可以充分展示软件设计与编程的能力、享受coding解决问题的乐趣、感受软件改变世界的魅力。 2019届华为软件精英挑战赛赛题为“智能世界•纵横”！



#### 提交日志

时间片在 600秒的时候，任务运行失败

时间片在 800秒的时候，任务运行成功

时间片在700秒的时候，任务运行出错

时间片在790秒的时候，任务运行成功，结果和800秒一致



**修改了最短路径算法，引入车道权重**

时间在500秒的时候，任务运行成功

时间片在400秒的时候，任务运行失败



**修改最短路径算法，引入了快车道和慢车道**

速度快的车走权值比较高的快车道

速度慢的车走权值比较低的慢车道

时间片在550的时候，达到最优结果  820 + 768

时间片在540的时候，数值和550一致。

时间片在500的时候，发生死锁

创建分支，提交V0.0.2版本



### 错误路线

终点两两聚类的时候，出现问题，会发生死锁

### 任务安排

1、将相同目的地附近的，都划分为一类 （已完成）

2、最短路径算法，增加权重值

3、将相同终点 并且 以该终点为起点的车，也同时出发

4、将速度不同车辆放在不同的车道行驶，高速车在高速车道，低速车在低速车道

5、随机漫游车道