================================================================================
                                样例使用说明
                                Sample Description
================================================================================
功能描述：
此样例演示了LPTIM连续模式中断唤醒STOP模式。

Function descriptions:
This sample demonstrates waking up from stop mode by LPTIM(contiunus mode) 
interrupt request.
================================================================================
测试环境：
测试用板：PY32M010_STK
MDK版本： 5.28

Test environment:
Test board: PY32M010_STK
MDK Version: 5.28
================================================================================
使用步骤：
1. 编译下载程序到MCU，并运行；
2. 按下按键进入stop模式；
3. 200ms后唤醒stop模式并循环进入stop模式再唤醒；
4. LPTIM中断中LED以2.5hz闪烁，while中PA3以2.5hz翻转；

Example execution steps:
1. compile and download the program to MCU and run it;
2. Press the button and enter stop mode
3. Woke up from stop mode after 200ms and repeat the process of entering stop 
mode and waking up
4. In the LPTIM interrupt, the LED flashes at 2.5Hz, while in the while function,
PA3 flips at 2.5Hz;
================================================================================
注意事项：

Notes:
================================================================================