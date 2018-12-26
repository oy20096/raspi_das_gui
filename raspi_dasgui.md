# RASPI_DAS

## RASPI_DAS Hardware System
>
>### 硬件总览
>**外壳图**
>![enter image description here](https://lh3.googleusercontent.com/dXN6l-oOztzY1PDiuZqnhYSdcverij9Ny3apWwql36OjAYsacms6Q0hpf2VHhFhNA4cGhUn3vhs)
>**零件图**
>![enter image description here](https://lh3.googleusercontent.com/OKOIQzmPpU0fsEjPEkVWaoa1Gp-BtIrxo4ZtUvD3EZsV-aQAL8sUpHv53fDJj1022KhlFb6fsMo)
>
## RASPI_DAS GUI
>**树莓派数据采集系统** , **RASPI_DAS GUI (Raspberry Data Acquisition System GUI)**
>![enter image description here](https://lh3.googleusercontent.com/j1f_oFytvIL7zqkOs5S4kOtsTgar0B-EWWf-C_3O-gb0mPCBv8jto6zc8akDzu60FbMBY-K_fOE)
>### 功能
>
>**1. 实时数据采集**
>
 >- AD
>	 > - 总采样周期：100 mS
>	 >- 采样率：20 kSPS
>	 >- 量程：±5 V，±10 V
>
> - UART
>	> - 可配置
	>![enter image description here](https://lh3.googleusercontent.com/fkvwDeu7nUp8_HvrltXF8LGcXK5qiXH1VsmtGQ_QmNA-myi2SUkUwpXA_QHdmUY5zUpn-b5aYDc)
>
>**2. 数据绘图及存储**
>
> - AD 数据绘图
>	>![enter image description here](https://lh3.googleusercontent.com/nzW7FB8V1qPKEYeElRnddJ5wqyeifMG8O4-wY-nDcJ0yuqzUoshw51ING07DTov5eeeMz_mWeto)
> 
> - 线圈姿态
>	> ![enter image description here](https://lh3.googleusercontent.com/sMzo3NVspxWTXcn8T9oy8UaSgx95pWKf_E0Isr-b1dU287lZNl9w9pmp45EP3GMQfQxdIt8GAH8)
> 
> - 数据存储
>	>| 时间 | AD数据 | 姿态数据 |
>	>| ----- | --------- | ----------- |
>	>|  ms  |      mV    | (yaw,pitch,roll) |
>
>### 更新历史
>
> - **v_1.0**
>> --2018-12-07
>> 建立AD绘图区、功能区、平台姿态区
>> 完成功能：100 ms AD采样、绘图、存储
>
>
> - **v_1.1**
>>--2018-12-19
>>修复读取数据处理不准确问题
>>完成功能：3D平台随数据转动
>
> - **v_1.2**
> >--2018-12-26

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIwMDgwMTM2NjAsMTU0Mjg3MDQsNzU5Mj
MzNTg0LC0yMTQxNjYxMjY4LDE1MDg0NzMyODIsLTE3ODExNjc1
OTIsLTQ4MTc2NTY5OSwtNzQyNDkxMzY1LC0xODY4NjY4MjgyLC
0xNDU5MDE2NjYxXX0=
-->