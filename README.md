# longzailvjia
项目进度
![image](https://user-images.githubusercontent.com/120173858/218124761-aab34f00-8dd4-46a1-b274-cf00ac4b6a40.png)

PC14:esp8266使能
USART2:eps8266通信
PB0，PB1，PB2，SPI2：GC9A01屏幕驱动
PB3：屏幕亮度pwm
USART1:调试使用
预计触摸屏模块CST816D还需要I2C,RST和一个上升下降沿捕获io口

（1）目前找不到CST816D模块相关寄存器手册或现成代码，还未开发
（2）tft UI设计还在写中
（3）esp8266和GC9A01驱动已完成，前者只完成与微信端连接，还未完成数据接收提取（发送端的数据结构还没看）
