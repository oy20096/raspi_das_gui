# RASPI_DASGUI

**树莓派数据采集系统** , **RASPI_DASGUI (Raspberry Data Acquisition System GUI)**

# 功能

**1. 实时数据采集**

 - AD
	> - 总采样周期：100 mS
	 >- 采样率：20 kSPS
	 >- 量程：±5 V，±10 V

 - UART
	> - 可配置

**2. 数据绘图及存储**

 - AD 数据绘图
 
 - 线圈姿态 3D 绘图
 
 - 数据存储
	 >| 时间 | AD数据 | 姿态数据 |
	 >| ----- | --------- | ----------- |
	 >|  ms  |      mV    | (yaw,pitch,roll) |

## 更新历史

**v.1.0**	
> --2018-12-07
> 建立AD绘图区、功能区、平台姿态区
> 完成功能：100 ms AD采样、绘图、存储

**v.1.1**
>--2018-12-19
>修复读取数据处理不准确问题
>完成功能：3D平台随数据转动

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE4Njg2NjgyODIsLTE0NTkwMTY2NjFdfQ
==
-->