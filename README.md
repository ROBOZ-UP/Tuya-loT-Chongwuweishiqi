宠物喂食器开发计划书
== 
This project is developed using Tuya SDK, which enables you to quickly develop branded apps connecting and controlling smart scenarios of many devices.       
For more information, please check Tuya Developer Website. 
  
本项目使用涂鸦SDK开发，可以快速开发品牌应用，连接和控制多个设备的智能场景。   
更多信息，请访问涂鸦开发者网站。 
  
# 一、方案标题
## ET智能宠物喂食器

# 二、方案应用场景及功能
## 应用场景   
* 家庭
* 宠物店
* 宠物救助站
* 共享宠物体验店
* 宠物繁殖基地
* 任何需要喂养宠物的场景
## 功能   
### 普通模式
* 喂食计划，可设定每天喂食时间、次数、量。
* 混合喂粮，可将多种宠物粮按比例进行混合喂食。
* 余粮提醒，显示余粮重量，余粮过少时会报警。
* 干湿分离，水有水箱，粮有粮仓。
* 湿度监测，监测粮仓湿度，防止粮食变质。
* 环境监测，可对出粮口进行拍照查看。
* 进食状态，对出粮口的粮食进行监测以确认宠物是否食用，并将结果上报。
* 故障提醒，当喂食器出现故障时，及时报警并采取安全措施。
* 食盖状态，提醒食盖开启或关闭状态。
* 姿态提醒，在使用状态时，姿态发生变化时提醒。
* 电量提醒，显示实时电量，电量低时报警。
### 集群模式（视进度开发）
面向宠物繁殖基地等大批量使用场景。
* 编号设定，可对每个喂食器进行重新编号。
* 批量设定，同时对选定的喂食器批量进行喂食计划设定。
* 状态整合，可针对状态查看喂食器编号。

# 三、开发计划
## 主要物料
 主控STM32F1系列、涂鸦三明治开发板、直流电机MG513P20_12V、重力传感器YZC131、超声波传感器HC-SR04、摄像头OV7725、温湿度传感器DHT11、六轴陀螺仪加速度传感器ICM-20602、霍尔传感器HAL145、磁铁等。
## 计划时间
 1) 3月13日前完成机械结构的设计方案。
 2) 3月10日-17日准备物料并进行嵌入式开发与云开发。
 3) 3月18日-20日完成结构搭建。
 4) 3月20日-27日各个模块与整体调试。
 5) 3月28日-29日完善产品，录制视频。
