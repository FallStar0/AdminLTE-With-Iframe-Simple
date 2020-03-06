# AdminLTE-With-Iframe-Simple

本项目地址   
 [https://gitee.com/fallstar/AdminLTE-With-Iframe-Simple](https://gitee.com/fallstar/AdminLTE-With-Iframe-Simple)   

[https://github.com/FallStar0/AdminLTE-With-Iframe-Simple](https://github.com/FallStar0/AdminLTE-With-Iframe-Simple)

[English Version](README.md)

## 项目介绍

项目完整版来源于这个项目：

[https://gitee.com/weituotian/AdminLTE-With-Iframe](https://gitee.com/weituotian/AdminLTE-With-Iframe "AdminLTE-With-Iframe")

不过这个项目依赖项目太多了，所以我精简了一下。

一个精简到只剩下外层框架的AdminLTE并使用多个标签内嵌iframe。

仅仅保留了外层框架，更换皮肤等功能。


## 截图
![](./asset/Shot1.jpg)

![](./asset/Shot2.jpg)

## 补充
关于如何在子页面打开新窗口：
```
//在子页面引入下面的js，这个包含了 添加、关闭、刷新 方法，你可以自行拓展它
tab.util.js

调用方法：
//打开外网地址
Util.addTab('https://baidu.com','baidu','百度',true});
//打开相对地址
Util.addTab('/test/404.html','404','404感受一下'});
//关闭当前子页面
Util.closeTab();
```