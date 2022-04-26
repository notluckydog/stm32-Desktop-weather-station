# stm32-Desktop-weather-station

### 1. 项目说明

项目初衷：stm32学习陷入瓶颈，想要通过项目来加深学习

项目定位：使用stm32F103c8T8开发板搭建起来一个桌面级的摆件

项目功能：

​	1. 使用四位数码管显示时间

				2. 通过DHT11获取温湿度信息并且显示
				2. 通过SGP30获取二氧化碳及挥发物浓度并且展示
				2. 通过一氧化碳传感器获取一氧化碳浓度并且展示
				2. 接入蜂鸣器实现声音
				2. 实现呼吸灯效果
				2. 噪音监控
				2. 随着光线强度控制屏幕亮度
				2. 使用sil9326 2,。4寸屏幕显示相关信息
				2. 

主要功能

### 2. 目录结构  

* doc      ---用来存放相关datasheet等文档
* hardware  ---用来存放硬件部分原理图和PCB等文件
* model      ---用来存放外壳或者其他模型文件
* sofeware   ---用来存放软件等相关内容
  * lib     --用来存放外设的库文件等
  * program   -- 用来存放项目文件
* README.md    ---项目readme文件

### 3. 项目结构

* 硬件部分

* 软件部分


  ```flow
  st=>start: 开始框
  op=>operation: 处理框
  cond=>condition: 判断框(是或否?)
  sub1=>subroutine: 子流程
  io=>inputoutput: 输入输出框
  e=>end: 结束框
  st->op->cond
  cond(yes)->io->e
  cond(no)->sub1(right)->op
  ```


### 4. 上手指南

从搭建环境到最后项目最终效果



### 5. 注意要点



### 6. 贡献者

