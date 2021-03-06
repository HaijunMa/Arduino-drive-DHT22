# Arduino-drive-DHT22
First project for Arduino

   ``在实验室无意间看到一块Arduino板，它深深迷住了我，诱惑力极强。激发了我的好奇心。
   凭借熟练的树莓派开发经验，我决定迅速征服它。查看了它的构造图，在实验室找了一个
   温湿度传感器（DHT22），放了一首《年少有为》，在可爱小黄熊的陪伴下，便开始行动了。
   我喜欢利用每一个时间碎片，在下载Arduino IDE的同时我也在Arduino上连接好了传感器。
   然后写代码，之前用Python写过驱动DHT22的代码，Arduino IDE使用C++的简化版本，所以
   也很快就搞定了。然后预编译代码、上传，在串口监视器中查看，显示温湿度，每2秒更新一
   次。搞定``:v:
   
技术细节
------------------------
- 电源 - 3-5V

- 最大电流 - 2.5mA

- 湿度 - 0-100％，精确度为2-5％

- 温度 - 40至80°C，精确度为±0.5°C

所须组件
-------------------------
- 1 × Breadboard 面包板
- 1 × Arduino Uno R3
- 1 × DHT22
- 1 × 10K欧姆电阻

连接图
--------------------------
![](https://github.com/HaijunMa/Arduino-drive-DHT22/raw/master/image/4.png)


实物图
-----------------------------

![](https://github.com/HaijunMa/Arduino-drive-DHT22/raw/master/image/3.jpg)

测试结果
--------------------------
![](https://github.com/HaijunMa/Arduino-drive-DHT22/raw/master/image/1.png)

![](https://github.com/HaijunMa/Arduino-drive-DHT22/raw/master/image/2.png)

代码描述
-------------------------
         代码文件为：dht22.ino
- DATA引脚连接到Arduino的2号引脚号
- Vcc引脚连接到Arduino板的5伏电压
- GND引脚连接到Arduino板的接地
- 我们需要在DATA和Vcc引脚之间连接10k欧姆电阻（上拉电阻）
- 一旦硬件连接完成，你需要添加DHT22库到你的Arduino库文件。


## Tip

### 行动起来吧！:thumbsup:
