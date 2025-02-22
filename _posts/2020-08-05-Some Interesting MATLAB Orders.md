---
categories:
  - MATLAB
tags:
  - Interesting Functions
  - Fun Games
  - GUI
---

>都说MATLAB无所不能，那就来看看它有多无所不能吧！

# 一个不错的官方SIMULINK演示



获许会惊艳到你。用于模拟航天飞机的发射，感兴趣的可以去看一下。
```
>>sf_launchabort
```

![发射](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/2.gif?sign=64f1f407bdd9d45b22d5a6cb34c956bd&t=1596645722)

![](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/3.png?sign=e2e6d9cb25c65b98d258a6c482954e9b&t=1596645734)

# 接管操作系统dos

以查看目录的内容为例

```
>>dos tree
>>dos cd
>>dos dir

%结果
├─DwnlData 
│  └─tutu
│      └─master_323 
├─FTP-iPad - 快捷方式 
├─HashManager 
├─interesting_Matlab-master_2 
│  └─interesting_Matlab-master 
│      ├─MATALB画图包格雷姆Ｇｒａｍｍ 
│      ├─Matlab_GUI 
│      ├─Matlab学习中的小笔记 
│      ├─P图区 
│      └─R一样的画图包 
│          └─PlotPub-master 
│              ├─examples 
│              └─examples_class 
├─MATLAB R2016a 完全自学一本通(源代码) 
├─MATLABtex系列 
│  └─tex 
├─SVM 
├─PD截图 
├─图像相关资料代码 
│  └─MATLAB实现图像去噪 滤波 锐化 边缘检测 源程序代码 
└─微信待发送 
```

# 接管浏览器的web 指令

```
>>web https://sjtu-tutu.github.io/tutu/
>>web www.baidu.com

% 以上会直接打开对应的网页
```

# 一组MATLAB内置彩蛋

## spy
```matlab
>> spy
```
直接跳出一只丑陋的狗狗

![spy](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/spy.png?sign=08a894d1ffaf2bdee48017c05acb92d1&t=1596645789)

## image
```matlab
>> spy
```
答应我半夜无论如何不要在命令行输入image

![image](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/image.png?sign=df124a475c74034d743f0d1871d0deb9&t=1596645803)

## why
```matlab
>> why
A tall and good and rich hamster obeyed a bald and terrified programmer.
>> why
Mara suggested it.
>> why
To please a very terrified and smart and tall engineer.
>> why
The tall system manager obeyed some engineer.
>> why
To satisfy some programmer.
>> why
Mary Ann wanted it that way.
>> why
Can you rephrase that?
```
小编暂时无法力理解内置why指令的用意，不过还是很想一直用这个函数！

## travel
```
>>travel
```
旅行商问题的动画演示

![travel](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/travel.gif?sign=1b9273931a19cbe5371f1f2da633a6d8&t=1596645822)

## earthmap
```matlab
>>earthmap
```
弹出matlab自带的地球仪，鉴定完毕，没啥用！
![earthmap](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/YgYNAnjD0K.gif?sign=d16fa51abece1d181cecc23b3e727966&t=1596645841)

## juggler 

基于模糊逻辑工具箱的跳球小游戏
```
>>juggler 
````
![juggler ](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/jumper.gif?sign=3a7da7097e2a5182eae82344ddec39f5&t=1596645859)

## pretty
内置函数实现公式可视化，利用的是字符画风格，值得一试，但还是更推荐图图写的LaTeX可视化吧，详情戳[这里](https://www.bilibili.com/video/BV1Hf4y1R78A)
```
>> syms x
>> y=cos(x)/sin(x)/exp(x)
 
y =
 
(exp(-x)*cos(x))/sin(x)
 
>> pretty(y)
exp(-x) cos(x)
--------------
    sin(x)
```

# 一些童年回忆小游戏

## 扫雷

![扫雷](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/MATLAB_8USy4QIP8o.png?sign=763a933d2fbb86004c1061979b2cf10a&t=1596646013)

```
>>xpbombs
```
## 移动方块
```
>fifteen
```

![移动方块](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/%E7%A7%BB%E5%8A%A8%E6%96%B9%E5%9D%97.png?sign=ae6749de7af3aa24212d6a0ded24c909&t=1596646028)

## 俄罗斯方块

![俄罗斯方块](https://7475-tututong-1302752799.tcb.qcloud.la/MD%E5%9B%BE%E5%BA%8A/2020-08-05/ErXv7fKdWu.gif?sign=306ad1350343cf9f8bfc54572d455088&t=1596646048)


>**pretty函数源代码和俄罗斯方块的源代码戳[这里](https://www.lanzoux.com/iJ4qkfc2b3i)可以直接获得**

