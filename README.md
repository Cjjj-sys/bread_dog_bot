# Bread Dog Bot

此项目基于 Nonebot2 和 go-cqhttp 开发，一个高度可自定义化的Terraria TShock Bot。

## 声明

此项目仅用于学习交流，请勿用于非法用途

## Nonebot2
非常 [ NICE ](https://github.com/nonebot/nonebot2) 的OneBot框架

## 适配版本
支持TShock Terraria 1.4.0.5+

推荐使用TShock Terraria 1.4.3.2+

TShock Terraria 1.4.3.2以下无法使用以下功能
+ 玩家背包
+ 进度

## 插件
部分功能需要插件支持

所有插件都可以在项目[ServerPlugins](https://github.com/Qianyiovo/bread_dog_bot/tree/main/ServerPlugins)目录下找到

下载前看清版本

### REST API Extensions
扩展了 REST API，可以获取玩家的背包、进度等信息

以下功能需要安装此插件才能正常使用
+ 玩家背包
+ 进度

### Better Whitelist
提供了更好的白名单，可以通过玩家昵称来判断是否为白名单玩家

以下功能需要安装此插件才能正常使用
+ 添加白名单
+ 删除白名单
+ 重置白名单列表
+ 玩家信息

## 功能

### 基础功能
+ 添加服务器
+ 删除服务器
+ 重置服务器列表
+ 服务器列表
+ 在线
+ 执行
+ 发送
+ 进度

### 绑定功能
+ 添加白名单
+ 删除白名单
+ 重置白名单列表

### 管理功能
+ 添加管理员
+ 删除管理员
+ 管理员列表

### 玩家功能
+ 签到
+ 添加金币
+ 扣除金币
+ 设置金币
+ 玩家信息
+ 玩家背包

### 云黑功能
+ 云黑检测
+ 云黑信息
+ 添加云黑
+ 删除云黑

### 邮箱功能
+ 玩家邮箱
+ 添加邮件
+ 删除邮件
+ 发送邮件
+ 领取邮件
+ 回收邮件

### 抽奖功能
+ 随机抽奖

## 安装

### Windows
[视频教程](https://breaddogbot-1302721716.cos.ap-shanghai.myqcloud.com/tutorial.mp4)

[依赖点我下载](https://www.miaovps.com/solved_packageMissInInstalling_mu_visual_cpp_build_tools_2015_update_3_x64_dvd_dfd9a39c.iso)
## Q&A


## 更新
2022/08/02(v1.6.3)
+ 修复了打开文件编码异常

2022/08/02(v1.6.2)
+ 修复了item.json文件丢失
+ 修复了帮助功能中的功能名称错误
+ 修复了菜单功能中的功能名称错误

2022/07/31(v1.6.1)
+ 修复了玩家邮箱图片丢失

2022/07/31(v1.6.0)
+ 优化了白名单，新增了一种模式（集群模式），现在可以只对一个服务器进行白名单操作了
+ 新增了邮箱功能(玩家邮箱、添加邮件等四 个功能)
+ 优化了部分功能消息，现在更人性化了
+ 新增了抽奖功能(随机抽奖)
+ 新增进群检测功能，检测玩家是否在黑名单中

2022/07/19(v1.5.0)
+ 修复了在线无法发送消息提示风控
+ 修复了添加白名单无法发送消息提示风控
+ 完美适配TShock Terraria 1.4.3.2+
+ 适配TShock Terraria 1.4.0.5+（部分功能无法使用）
+ 修复了大部分功能反馈信息异常
+ 优化了部分功能消息

2022/07/18(v1.4.2)
+ 修复了在Windows平台中图片发送错误
+ 修复了没有管理员时管理员列表不发送消息

2022/07/18(v1.4.1)
+ 修复了在Windows平台中图片无法发送

2022/07/17(v1.4.0)
+ 新增了玩家功能（玩家背包），以图片形式返回玩家背包信息
+ 优化了菜单，现在更好看了
+ 新增了管理功能（管理员列表），以图片形式返回本群所有机器人管理员
+ 新增了基础功能（进度），以图片形式返回服务器的进度
+ 优化了关于，现在显示更多信息
+ 新增适配插件（RESTAPIExtensions.dll)，可在ServerPlugins文件夹中找到


2022/07/14(v1.3.0)
+ 修复了wiki搜索空白内容
+ 新增了云黑功能（云黑检测、云黑信息、添加/删除云黑）

2022/07/7(v1.2.0)
+ 修复了绑定白名单后再次绑定出现返回消息错误
+ 修复了部分功能服务器列表无服务器时不发送任何消息
+ 新增了许多玩家功能（签到、添加\扣除\删除金币）
+ 新增了wiki [@ACaiCat](https://github.com/ACaiCat)
+ 放弃使用HTMLRender，故删除了一些功能（白名单列表、管理员列表），后续更新中会以其他方式重新加入

2022/07/02(v1.1.0)

+ 重写了所有功能，设计变得更加合理了。