# ccf-csp-python
ccf考试历届真题python语言解答（持续更新中）
### Tips
* eval()很好用，但是作为输入效率比较低
* collections与heapq等库的数据结构很好用
### 解答情况
由于考试时限时10s，而测试时限时1s，部分题目采用最优解也无法运行完成，可尝试使用c++重写验证  

| 试题序号                      | 试题名称     | 成绩 | 运行时间 | 备注                   |
| ----------------------------- | ------------ | ---- | -------- | ---------------------- |
| [19_03_4](./19_03/19_03_4.py) | 消息传递接口 | 100  | 421ms    |                        |
| [19_03_3](./19_03/19_03_3.py) | 损坏的RAID5  | 100  | 375ms    |                        |
| [19_03_2](./19_03/19_03_2.py) | 二十四点     | 100  | 100ms    |                        |
| [19_03_1](./19_03/19_03_1.py) | 小中大       | 100  | 296ms    |                        |
| [18_12_4](./18_12/18_12_4.py) | 数据中心     | 100  | 968ms    | 堆优化Prim             |
| [18_12_3](./18_12/18_12_3.py) | CIDR合并     | 90   | 超时     |                        |
| [18_12_2](./18_12/18_12_2.py) | 小明放学     | 100  | 390ms    |                        |
| [18_12_1](./18_12/18_12_1.py) | 小明上学     | 100  | 31ms     |                        |
| [18_09_4](./18_09/18_09_4.py) | 再卖菜       | 100  | 62ms     | 剪枝回溯               |
| [18_09_3](./18_09/18_09_3.py) | 元素选择器   | 100  | 31ms     |                        |
| [18_09_2](./18_09/18_09_2.py) | 买菜         | 100  | 296ms    |                        |
| [18_09_1](./18_09/18_09_1.py) | 卖菜         | 100  | 46ms     |                        |
| [18_03_4](./18_03/18_03_4.py) | 棋局评估     | 100  | 62ms     | 记忆搜索               |
| [18_03_3](./18_03/18_03_3.py) | url映射      | 100  | 62ms     | 正则表达式             |
| [18_03_2](./18_03/18_03_2.py) | 碰撞的小球   | 100  | 109ms    |                        |
| [18_03_1](./18_03/18_03_1.py) | 跳一跳       | 100  | 62ms     |                        |
| [17_12_4](./17_12/17_12_4.py) | 行车路线     | 100  | 953ms    | 改编Dijkstra           |
| [17_12_3](./17_12/17_12_3.py) | Crontab      | 100  | 593ms    |                        |
| [17_12_2](./17_12/17_12_2.py) | 游戏         | 100  | 31ms     |                        |
| [17_12_1](./17_12/17_12_1.py) | 最小差值     | 100  | 31ms     |                        |
| [17_09_4](./17_09/17_09_4.py) | 通信网络     | 65   | 超时     | 复杂度O(n^2) C++可跑完 |
| [17_09_3](./17_09/17_09_3.py) | JSON查询     | 100  | 62ms     |                        |
| [17_09_2](./17_09/17_09_2.py) | 公共钥匙盒   | 100  | 78ms     |                        |
| [17_09_1](./17_09/17_09_1.py) | 打酱油       | 100  | 31ms     |                        |
| [17_03_4](./17_03/17_03_4.py) | 地铁修建     | 80   | 超时     | 堆优化Prim             |
| [17_03_3](./17_03/17_03_3.py) | Markdown     | 100  | 62ms     |                        |
| [17_03_2](./17_03/17_03_2.py) | 学生排队     | 100  | 62ms     |                        |
| [17_03_1](./17_03/17_03_1.py) | 分蛋糕       | 100  | 46ms     |                        |
| [16_12_4](./16_12/16_12_4.py) | 压缩编码     | 60   | 超时     |                        |
| [16_12_3](./16_12/16_12_3.py) | 权限查询     | 100  | 109ms    |                        |
| [16_12_2](./16_12/16_12_2.py) | 工资计算     | 100  | 46ms     |                        |
| [16_12_1](./16_12/16_12_1.py) | 中间数       | 100  | 62ms     |                        |
| [16_09_4](./16_09/16_09_4.py) | 交通规划     | 100  | 890ms    | 堆优化Dijkstra         |
| [16_09_3](./16_09/16_09_3.py) | 炉石传说     | 100  | 46ms     |                        |
| [16_09_2](./16_09/16_09_2.py) | 火车购票     | 100  | 46ms     |                        |
| [16_09_1](./16_09/16_09_1.py) | 最大波动     | 100  | 46ms     |                        |