# Msp430-Template-for-car
The main frequency clock is set at 25MHz, with a UART clock source of 3MHz, and a baud rate of 115200. The provided routine template includes implementations for motor encoders, a buzzer, LEDs, motors, MPU6050, and PWM.

/******************************************************************************************************************************************/

为23年电赛准备的TI小车例程，可惜今年没有小车题，控制题也没有限制TI板。

本例程的所有程序使用msp430 driverlib 编程。
主频时钟拉到了25Mhz，串口使用3Mhz SMCLK时钟源，波特率设置为115200. 注意串口的波特率参数设置要看这个网站。
![image](https://github.com/OoowweeE/Msp430-Template-for-car/assets/111238494/e5560561-8afe-4494-861d-621e3315c5eb)

电机编码器使用外部中断A，B相 2倍频计数。
MPU6050 移植的是正点原子的，自带dmp解算，三个轴读出的数据都准确。


另附我画的TI PCB ，使用msp430f5529。 可以使用嘉立创打板。











