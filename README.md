# TEAM NO.2
## **TEAM LEADER:**
>>(唐绍武，2018110101)
## **TEAM PARTNER:**
>>
>>1.(钟欣瑞, 2018112866)
>>
>>2.(沈博翰，2018111750)
>>
>>3.(马翊然，2018111497)

## **The Background Story**

>>根据心理学调查研究，在设有红绿灯的路口，如果能让某些东西能吸引行人，主要利用openpose搭建神经网络并训练，达到准确识别人体轮廓的目的，再做相关处
理，  简化人体动作。再用串口通信，把处理后的数据数据传入到Arduino或单片机，通过Arduino将简化的人体主要利用openpose搭建神经网络并训练，达到准确
识别人体轮廓  的目的，再做相关处理，简化人体动作。再用串口通信，把处理后的数据数据传入到Arduino或单片机，通过Arduino将简化的人体动作显示到32×32
点阵上，即达到人灯  互动的目的。
## **project Description**

>>主要利用jetson nano上运行open pose，达到准确识别人体轮廓的目的，再做相关处理，简化人体动作。
再用串口通信，把处理后的数据数据传入到Arduino，通过Arduino将简化的人体动作显示到32×32点阵上，即达到人灯互动的目的，从而降低行人闯红灯的概率。

## **How to Make it?**

>>openpose人像识别、Arduino

## **Executable Plan (Deadline of each part)**
	
>>1.第10周确定项目计划
	
>>2.第12周搭建基本框架
	
>>3.第14周完成大致功能
	
>>4.第15周完成设计外壳、外观优化等后续工作
## **Experiences**
### 软件
>>初期遇到的问题是Ubuntu系统的使用。之前我们队伍全部都是只接触过windows系统，一下子在jetson nano上运行Ubuntu系统十分的不习惯，命令行各种不会,但是到了现在，发现命令行是真的好用，下载库和应用，只要有源，一行代码搞定，真的有电影里面黑客的感觉。  中期遇到的问题是运行环境的配置。虽然是Ubuntu很方便，但是opencv的各种依赖，open pose的各种关系，搞的我们焦头烂额，还好李君老师对于源的使用和依赖有很深的了解，帮我们解决了国内缺少源的问题，给我们后续的制作带来了莫大的方便。最后呢，也是最难的，就是jetson nano和arduino之间的通信，无法解决串口通信的问题。jetson nano的资料较少，难以找到各个针脚的所对应的串口名，找对了串口也无法在arduino上decode数据，最后是王衡老师给了我们启发，在2019.6.10号晚终于正常的通过串口收发信息。剩下的就是最后的调试。
### 硬件（外壳）
>>体现我们设计感的当属这个外壳啦！！外壳全由亚克力板制作，激光切割成零件，最后拼接成型。完美解决jetson nano散热的问题，别出心裁的想出了圆片累加的方式实现激光切割难以实现的圆角正方体。其中的布线合理，美观，不愧于我们认真的设计。
![image](https://github.com/Tavis0/life-lights/raw/master/p/微信图片_20190611003230.jpg)
## **最终成果**
>> 我们最终完成了基于openpose的人体识别,并在点阵上实现了关键的输出.我们成功了!!!!
>>![image](https://github.com/Tavis0/life-lights/raw/master/p/image.png)
>>![image](https://github.com/Tavis0/life-lights/raw/master/p/WeChat_20190624181652_Trim.gif)
>>![image](https://github.com/Tavis0/life-lights/raw/master/p/WeChat_20190624181845_Trim.gif)
>>![image](https://github.com/Tavis0/life-lights/blob/master/p/IMG_20190614_233342.jpg)
>>![image](https://github.com/Tavis0/life-lights/blob/master/p/IMG_20190615_230608_1.jpg)
>>![image](https://github.com/Tavis0/life-lights/blob/master/p/IMG_20190615_230615.jpg)
>>![image](https://github.com/Tavis0/life-lights/blob/master/p/IMG_20190615_230621.jpg)

