# 项目名称：STM32四轴飞行器
## 介绍：
- 该项目是一个基于STM32G030C8T6作为主控芯片而开发的飞控，之所以使用G030是因为G030提供精确的内部时钟，不必再添加外部时钟源，避免pcb布局空间不够。
- 姿态判断使用了MPU6050陀螺仪模块和BMP180气压传感器，无线遥控使用了SI24R1模块(与NRF24L01模块通用)
- 该飞控模块与我另一个开源的遥控器所适配 -> [FlyController](https://github.com/vitaminHurricane/FlyController)
## 原理图
该飞控原理图使用了立创开源广场上的开源飞控原理图 -> 
[立创开源广场](https://oshwhub.com/nevet/fly_main_board)

