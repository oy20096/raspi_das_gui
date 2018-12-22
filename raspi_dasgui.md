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
![enter image description here](https://lh3.googleusercontent.com/Qov-35b-1oHqtha6xiHo90ykOG579XgfSf0ERj-g0NrJpr6nRy8LNwjhgOBJ8zXSCj7OBwBZudw)
>
>### 功能
>
>**1. 实时数据采集**
>
 >- AD
	> - 总采样周期：100 mS
	 >- 采样率：20 kSPS
	 >- 量程：±5 V，±10 V
>
> - UART
	> - 可配置
	![enter image description here](https://lh3.googleusercontent.com/uhtWSH3f_3p-i1_2E0vp2Qu30NQV7Vn8ok4HBvjo1KQ9Bc4aox9FJ3al23C57j-XD35B-m0xmkM)
>
>**2. 数据绘图及存储**
>
> - AD 数据绘图
 ![enter image description here](https://lh3.googleusercontent.com/0G5cH2K5k-AgqMkD5xkHlRllg2GSXVi9pmZ9UuG-76TTq775HsTfK-Hyw2H7smQHa95wpbFfESY)
> 
> - 线圈姿态 3D 绘图
> ![enter image description here](https://lh3.googleusercontent.com/uoihoyFhTpofuTDB0_GyjKn3tcqXqdZGyevKjc70kshn7v7ryu07lrfbxE4JagTXqGMzo-VXpm4)
>
> - 数据存储
	 >| 时间 | AD数据 | 姿态数据 |
	 >| ----- | --------- | ----------- |
	 >|  ms  |      mV    | (yaw,pitch,roll) |
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

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTIxNDE2NjEyNjgsMTUwODQ3MzI4MiwtMT
c4MTE2NzU5MiwtNDgxNzY1Njk5LC03NDI0OTEzNjUsLTE4Njg2
NjgyODIsLTE0NTkwMTY2NjFdfQ==
-->