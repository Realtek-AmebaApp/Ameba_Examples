# LCD 24H Clock
这个例程专用于 Realtek Ameba RTL8195. Ameba RTL8195 板子是通过 Arduino IDE 烧录进程序并基于 I2C 协议连接到 LCD 屏幕.

24小时时钟通过小时, 分钟和秒钟来计时24个小时. 每次经过24小时, 系统都会重新启动.


# 软件编程
软件的编程只可以通过 Arduino IDE 烧录进板子 RTL8195

请参考文件 LCD_clock.ino


# 硬件连接
LCD 的型号是 LCD 1602 with I2C

请参考文件 Hardware connection.png


# RTL8195AM_LiquidCrystal_I2C-library-master.zip 

这个 .ZIP 文件是启动 I2C LCD 的库. 在启动 LCD 前请安装这个库. 安装步骤请参考以下. 
打开 LCD_clock.ino, 执行" sketch/Include Library/Add .ZIP Library " 然后选择 "RTL8195AM_LiquidCrystal_I2C-library-master.zip "
