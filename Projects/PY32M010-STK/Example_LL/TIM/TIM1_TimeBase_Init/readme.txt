================================================================================
                                样例使用说明
                                Sample Description
================================================================================
功能描述：
此样例演示了TIM1的更新中断功能，在更新中断中翻转LED。

Function descriptions:
This sample demonstrates the UPDATE interrupt function , LED toggled when the
update interrupt is generated.

================================================================================
测试环境：
测试用板：PY32M010_STK
MDK版本： 5.28

Test environment:
Test board: PY32M010_STK
MDK Version: 5.28
================================================================================
使用步骤：
1. 编译下载程序到MCU，并运行
2. 程序会每隔1s在TIM的更新中断中翻转LED。

Example execution steps:
1. compile and download the program to MCU and run it;
2. The update interruption generated once per second,then LED toggled
================================================================================
注意事项：

Notes:

================================================================================