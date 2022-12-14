# Analog-circuit-course-design-Infrared-alarm
Analog circuit course design-Infrared alarm

## Abstract

In daily life, we often encounter a variety of dangerous situations or the existence of some theft problems exist. In order to solve this kind of problem, need all sorts of alarm right now, infrared alarm is a kind of simple principle. And the price of infrared alarm is low. And infrared alarm is a kind of stable and efficient alarm. The design of infrared alarm is composed of three main circuits: the three-terminal voltage regulator LM7812 and LM7912 ± 12V DC voltage regulator, the voltage comparator constitutes the infrared switch, the RC oscillation circuit constitutes the LED flicker and the horn alarm. When the infrared ray is blocked, the relay switch will close, the circuit will close LED flashing, horn alarm. Thus, alarm can be reached to ensure that safety and property problems are avoided in life and production.

常常在日常生活、生产当中，往往会遇到各种危险的情况或是存在一些偷盗的问题存在。为了解决此类问题，此时就需要各种各样的报警器，红外线报警器就是一种原理简单，价格低廉的一种稳定高效的报警器。磁报警器的设计采用三大部分的电路组成：采用三端稳压器LM7812和LM7912的±12v直流稳压电源、电压比较器构成红外线开关、RC振荡电路构成LED的闪烁以及蜂鸣器报警。当红外线被遮挡时，继电器开关会闭合，电路闭合LED闪烁、蜂鸣器报警。由此可以达到报警以确保生活生产当中避免安全财产问题。

![image](https://github.com/yangtiming/Analog-circuit-course-design-Infrared-alarm/blob/master/images/pic%201.png)

## Circuit decomposition
1. Voltage comparator part
2. ± 12V DC regulated power supply
3. RC oscillation circuit part
![image](https://github.com/yangtiming/Analog-circuit-course-design-Infrared-alarm/blob/master/images/pic%202.png)


## results
output waveform

### 1.Voltage comparator part
The red line represents the in-phase ; The green line represents the reverse phase 

#### When the voltage comparator is not working
<img src="https://github.com/yangtiming/Analog-circuit-course-design-Infrared-alarm/blob/master/images/pic%205.png" width="500px">

#### When the voltage comparator is working
<img src="https://github.com/yangtiming/Analog-circuit-course-design-Infrared-alarm/blob/master/images/pic%206%20.png" width="500px">


### 2.Power part
The green line is the voltage of 220v 50hz. After dc voltage stabilization, the dc stable voltage of the red line can be obtained. Due to the circuit load, the original 24V reduced to 20V now

<img src="https://github.com/yangtiming/Analog-circuit-course-design-Infrared-alarm/blob/master/images/pic%207.png" width="500px">


### 3.RC oscillation circuit part
<img src="https://github.com/yangtiming/Analog-circuit-course-design-Infrared-alarm/blob/master/images/pic%203.png" width="500px">

### 4.Buzzer and LED port part
<img src="https://github.com/yangtiming/Analog-circuit-course-design-Infrared-alarm/blob/master/images/pic%204.png" width="500px">

