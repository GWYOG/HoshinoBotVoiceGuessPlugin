# 猜语音小游戏插件 for HoshinoBot

A [HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot) based [PCR](http://priconne-redive.jp/) game plugin.


## 简介

基于 [HoshinoBot](https://github.com/Ice-Cirno/HoshinoBot) 开发的小游戏插件，需要酷Q Pro。

机器人会随机发送一句打开游戏时听到的“cygames”语音，群成员需要在给定时间内猜出语音来自哪位角色。



## 功能介绍

目前只有一条语句，输入“cygames”开始游戏。

- **cygames**：机器人随机发送一条“cygames”语音，一定时间后公布答案和猜对的人。



## 安装方式

1. clone或者下载此仓库的代码

2. 将voiceguess文件夹放入`hoshino/modules/`文件夹中

3. 打开`hoshino/config/`文件夹中的`__bot__.py`文件，在`MODULES_ON`中加入一行`'voiceguess',`


## 注意事项
  此插件需要能发语音的酷Q Pro机器人。
  若想要公布结果时发送角色头像，请将`hoshino/config/__bot__.py`中的`USE_CQPRO`设为`True`