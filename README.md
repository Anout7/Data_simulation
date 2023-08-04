# Data_simulation
数据模拟<br>
用shell编程实现电商数据和工业数据的简单模拟
## 电商数据
### orders
* userId 用户id Int
* itemId 商品id Int
* itemState 订单状态 String
* amount 商品价格 Double
* startTime 开始时间 Long
* endTime 结束时间 Long
注<br>
订单状态分别为1001:创建订单、1002:支付订单、1003:取消订单、1004:完成订单、1005:申请退回、1006:退回完成<br>
可用netcat连接，端口号为1234。但nc连接后，数据就会停止模拟，技术不精我也不知道为什么。
## 工业数据
### EnvironmentData
* id 机器id Int
* temp 温度 Double
* time 时间 String
### ProduceRecord
* id 机器id Int
* handleState 状态 String
* time 时间 String
### ChangeRecord
* id 机器id Int
* state 状态 String
* warning 警告 String
* time 时间 String
注<br>
这里时间应该为Long
