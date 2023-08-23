# auto_waken
自动根据微信截图整理文字/Automatically organize text according to WeChat screenshots

## 介绍
本项目使用 tesseract进行图像识别文字、pytesseract操作前者、openCV对图片进行操作、正则表达式对文字做整理。
本项目来源于“惊蛰”，我和女友在一起之后，我会整理我们聊天记录中甜蜜的部分，放进word里，起名“惊蛰/waken”。
在此之前已经手动整理了八万字，那时我的python技能尚不足以实现自动化处理，目前的auto_waken则能够实现半自动整理。

## 使用指南
##### 1\在微信聊天记录中选择甜蜜的对话 
##### 2\将之截图保存到origin，命名为日期
##### 3\运行waken.py，则会生成waken.txt
##### 4\放进word里继续整理

## 使用实例
在origin中有聊天记录实例
