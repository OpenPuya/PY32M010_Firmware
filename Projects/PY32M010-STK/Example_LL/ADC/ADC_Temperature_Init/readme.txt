================================================================================
                                样例使用说明
                                Sample Description
================================================================================
功能描述：
此样例演示了ADC的Tempsensor功能。

Function descriptions:
This sample demonstrates the Tempsensor function of the ADC.
================================================================================
测试环境：
测试用板：PY32M010_STK
MDK版本： 5.28

Test environment:
Test board: PY32M010_STK
MDK Version: 5.28
================================================================================
使用步骤：
1. 编译并下载程序；
2. 串口打印出当前温度值。

Example execution steps:
1. Compile and download the program and run it
2. USART printf current temperaure value
================================================================================
注意事项：
通过USB转TTL模块连接PC与STK板,STK板与USB转TTL模块的连线方式如下；
STK板        USB转TTL模块
PB4(TX)  -->  RX
PB5(RX)  -->  TX
GND      -->  GND

Notes:
Connect the PC to the STK board through the USB to TTL module, the connection
between the STK board and the USB to TTL module is as follows:
STK board      USB to TTL module
PB4(TX)    --> RX
PB5(RX)    --> TX
GND        --> GND
================================================================================