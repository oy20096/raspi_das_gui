# RASPI_DAS

## RASPI_DAS Hardware System
>
>### 硬件总览
>
>**外壳图**
>![enter image description here](https://lh3.googleusercontent.com/dXN6l-oOztzY1PDiuZqnhYSdcverij9Ny3apWwql36OjAYsacms6Q0hpf2VHhFhNA4cGhUn3vhs)
>**零件图**
>![enter image description here](https://lh3.googleusercontent.com/OKOIQzmPpU0fsEjPEkVWaoa1Gp-BtIrxo4ZtUvD3EZsV-aQAL8sUpHv53fDJj1022KhlFb6fsMo)
>
>**总连接图**
>![enter image description here](https://lh3.googleusercontent.com/Rq8J1Ouado2HMyH_4QdierOb11bRvO5t9ZcNxnZkcXL6H0kjVgEwOy2Nsdg88fHyCFDTMq_xeHM)
>
>
>
## RASPI_DAS GUI
>**树莓派数据采集系统** , **RASPI_DAS GUI (Raspberry Data Acquisition System GUI)**
>![enter image description here](https://lh3.googleusercontent.com/HMAJRKneWbIVVm6FbawJW6ZR3BF7Ed4Ed5Vvc6tiiaKwUe_R4zyWJPRtm6B9FMoFabfbBWE5gqM)
>
>### 功能
>
>**1. 实时数据采集**
>
 >- AD
>	> - 3 通道同步采样
>	 > - 总采样周期：100 mS
>	 >- 采样率：20 kSPS
>	 >- 量程：±5 V，±10 V
>
> - UART
>	> - 可配置
	>![enter image description here](https://lh3.googleusercontent.com/fkvwDeu7nUp8_HvrltXF8LGcXK5qiXH1VsmtGQ_QmNA-myi2SUkUwpXA_QHdmUY5zUpn-b5aYDc)
>
> - 当前测试点示意图
	> >	
>
>**2. 数据绘图及存储**
>
> - AD 数据绘图
>	>![enter image description here](https://lh3.googleusercontent.com/i1CoVfLY-qbYw5JXJAadLRQ-jZICgBmP-x5uHSTd8v3_GTVScqbP5XNPo1KihyOWoxOcS_xVC24)
>	>![enter image description here](https://lh3.googleusercontent.com/kjSCGf78zqi5g1AdiiZc3s8dLxFRS5Z7Psjax2zN8SdXWkTFKWpl3LnjL74sGdqb1VVMYHi1tqA)
> 
> - 线圈姿态
>	> ![enter image description here](https://lh3.googleusercontent.com/sMzo3NVspxWTXcn8T9oy8UaSgx95pWKf_E0Isr-b1dU287lZNl9w9pmp45EP3GMQfQxdIt8GAH8)
> 
> - 数据存储
>	>| 时间 | AD数据 | 姿态数据 |
>	>| ----- | --------- | ----------- |
>	>|  ms  |      mV    | (yaw,pitch,roll) |
>
>**3. 功能区域**
>
> - 功能按钮
>	> ![enter image description here](https://lh3.googleusercontent.com/dB7v0mbiDdAo05irNXJdriPDXqhBP5kw-QPCrwFOuHlUCVg0TyEh4zP9oE8UUA0OadVv1SDx6-w)
>
> - 输入输出
>
>	>![enter image description here](https://lh3.googleusercontent.com/AGL7uIooCHYA3YIkLMPo1R88fc5S5336FSWOt1UsBT8eVkVAO0Yb9cpP9IuvHXqyEzzh6ZkPzdQ)
>	>![enter image description here](https://lh3.googleusercontent.com/gXyNpKMyKVp72F9MLvKmdvdVp72Tu4ckQ_XAdG33su5Bh9Su1WWuvN_t4cY2Yn3RsLwnYmVmi8g)
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
>	>重新绘制 UI 
> >移除平台姿态 3D 绘图
>	>新增输入区
>	>完成串口姿态数据接收发送与处理
>
>	> - **v_1.2.1**
>	> >--2018-12-27
>	>重新绘制 UI 
>  >新增 3 通道采样功能及绘图区



<!--stackedit_data:
eyJoaXN0b3J5IjpbMTY5MjgxNjk4MCwtMTI2MTAyNjA3NiwtMT
YyMjYwMjc1MCwtMTcwMjM2NzQ0MCwxOTAxNzg1OTE4LDE1NDI4
NzA0LDc1OTIzMzU4NCwtMjE0MTY2MTI2OCwxNTA4NDczMjgyLC
0xNzgxMTY3NTkyLC00ODE3NjU2OTksLTc0MjQ5MTM2NSwtMTg2
ODY2ODI4MiwtMTQ1OTAxNjY2MV19
-->