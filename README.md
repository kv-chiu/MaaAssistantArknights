<div align="center">

<img alt="LOGO" src="https://cdn.jsdelivr.net/gh/MaaAssistantArknights/design@main/logo/maa-logo_512x512.png" width="256" height="256" />

# MaaAssistantArknights

<br>
<div>
    <img alt="C++" src="https://img.shields.io/badge/c++-20-%2300599C?logo=cplusplus">
</div>
<div>
    <img alt="platform" src="https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-blueviolet">
</div>
<div>
    <img alt="license" src="https://img.shields.io/github/license/MaaAssistantArknights/MaaAssistantArknights">
    <img alt="commit" src="https://img.shields.io/github/commit-activity/m/MaaAssistantArknights/MaaAssistantArknights?color=%23ff69b4">
    <img alt="stars" src="https://img.shields.io/github/stars/MaaAssistantArknights/MaaAssistantArknights?style=social">
</div>
<br>

[简体中文](https://maa.plus/docs/) | [繁體中文](https://maa.plus/docs/zh-tw/) | [English](https://maa.plus/docs/en-us/) | [日本語](https://maa.plus/docs/ja-jp/) | [한국어](https://maa.plus/docs/ko-kr/)

MAA 的意思是 MAA Assistant Arknights

一款明日方舟游戏小助手

基于图像识别技术，一键完成全部日常任务！

绝赞更新中  ✿✿ヽ(°▽°)ノ✿<br>

</div>

## 亮点功能

- 刷理智，掉落识别及上传 [企鹅物流](https://penguin-stats.cn/)；
- 智能基建换班，自动计算干员效率，单设施内最优解；同时也支持 [自定义排班](https://maa.plus/docs/3.6-基建排班协议.html)；
- 自动公招，可选使用加急许可，一次全部刷完！公招数据上传 [企鹅物流](https://penguin-stats.cn/result/stage/recruit/recruit)，[一图流](https://yituliu.site/maarecruitdata)；
- 支持手动识别公招界面，方便对高星公招做出选择； ~~（你的这个高姿回费出的是推王呢还是推王呢）~~
- 支持识别干员列表，统计已有和未有干员（还能为手动识别公招界面提供已有潜能数据提示）；
- 支持识别养成材料，并可导出至 [企鹅物流刷图规划](https://penguin-stats.cn/planner) 和 [明日方舟工具箱](https://arkn.lolicon.app/#/material) 计算缺少的养成材料；
- 访问好友、收取信用及购物、领取日常奖励等，一键全日常自动长草；
- 肉鸽全自动刷源石锭和蜡烛，自动识别干员及练度；
- 选择作业 JSON 文件，自动抄作业， [视频演示](https://www.bilibili.com/video/BV1H841177Fk/)；
- 仓库识别并支持导出至 [企鹅物流刷图规划器](https://penguin-stats.cn/planner), [明日方舟工具箱](https://arkn.lolicon.app/#/material), [ARK-NIGHTS 干员培养表](https://ark-nights.com/settings)；
- 支持 C, Python, Java, Rust, Golang, Java HTTP, Rust HTTP 等多种接口，方便集成调用，自定义你的 MAA！

话不多说，看图！<br>

![zh1](https://user-images.githubusercontent.com/9762652/259595058-1529207a-ef3d-4eca-a016-4759eb534c6e.png)
![zh2](https://user-images.githubusercontent.com/9762652/259594965-882b61e6-bf31-40c1-8c03-3f51f82a0d42.png)
![zh3](https://user-images.githubusercontent.com/9762652/259594874-07abdd9f-33f0-4446-8da3-799849bf7328.png)
![zh4](https://user-images.githubusercontent.com/9762652/259594649-c08b6558-7d17-45a8-9ba0-3ebc9a6f5589.png)

## 下载地址

- [稳定版/公测版](https://github.com/MaaAssistantArknights/MaaAssistantArknights/releases)
- [内测版](https://github.com/MaaAssistantArknights/MaaRelease/releases)

## 使用说明

### 基本说明

1. 请根据 [模拟器支持情况](https://maa.plus/docs/1.3-模拟器支持.html)，进行对应的操作；
2. 修改模拟器分辨率为 `16:9` 比例，最低 `1280 * 720`，更高不限；<br>
   对于国际服（美服）玩家，由于界面布局、字号等问题，我们则建议您将分辨率修改为 `1920 * 1080`；
3. 开始使用吧！

更多使用说明请参考 [详细介绍](https://maa.plus/docs/1.1-详细介绍.html)

### 常见问题

- 软件一打开就闪退；
- 连接错误、不知道 adb 路径怎么填写；
- 连接成功了，但没反应；
- 如何连接自定义端口；
- 下载速度慢，且镜像站无法打开网页；
- 下载到一半提示“登陆”/“鉴权”；
- 连接正常，任务开始了，但是没反应。

请参考 [常见问题](https://maa.plus/docs/1.2-常见问题.html)

### 外服支持

目前国际服（美服）、日服、韩服、繁中服的绝大部分功能均已支持。但由于外服用户较少及项目人手不足，很多功能并没有进行全面的测试，所以请自行体验。<br>
若您遇到了 Bug，或对某个功能有强需求，欢迎在 [Issues](https://github.com/MaaAssistantArknights/MaaAssistantArknights/issues) 和 [讨论区](https://github.com/MaaAssistantArknights/MaaAssistantArknights/discussions) 催更；或加入我们一起建设 MAA！请参考 [外服适配教程](#外服适配)

### CLI支持

MAA 支持命令行界面（CLI）操作，支持 Linux，macOS 和 Windows，可用于自动化脚本或在无图形界面的服务器上使用。请参考 [CLI 使用指南](https://maa.plus/docs/1.6-CLI使用指南.html)

## 加入我们

### 主要关联项目

**目前项目组非常缺前端大佬，若您有相关经验，欢迎加入我们！**

- 全新框架：[MaaFramework](https://github.com/MaaAssistantArknights/MaaFramework)
- 全新 GUI：[MaaX](https://github.com/MaaAssistantArknights/MaaX)
- [作业站](https://prts.plus) 前端：[maa-copilot-frontend](https://github.com/MaaAssistantArknights/maa-copilot-frontend)
- [作业站](https://prts.plus) 后端：[MaaBackendCenter](https://github.com/MaaAssistantArknights/MaaBackendCenter)
- [官网](https://maa.plus)：[前端](https://github.com/MaaAssistantArknights/maa-website)
- 深度学习：[MaaAI](https://github.com/MaaAssistantArknights/MaaAI)

### 多语言 (i18n)

MAA 支持多国语言，并使用 Weblate 进行本地化管理。如果您通晓多门语言，欢迎前往 [MAA Weblate](https://weblate.maa-org.net) 帮助我们进行翻译。

MAA 以中文（简体）为第一语言，翻译词条均以中文（简体）为准。

[![Weblate](https://weblate.maa-org.net/widgets/maa-assistant-arknights/zh_Hans/maa-wpf-gui/multi-auto.svg)](https://weblate.maa-org.net/engage/maa-assistant-arknights/zh_Hans/)

### Windows

1. 下载预构建的第三方库

    ```cmd
    python maadeps-download.py
    ```

2. 使用 Visual Studio 2022 打开 `MAA.sln`，右键 `MaaWpfGui`，设为启动项目
3. VS 上方配置选择 `RelWithDebInfo` `x64` （如果编译 Release 包 或 ARM 平台，请忽略这步）
4. 右键 `MaaWpfGui` - 属性 - 调试 - 启用本地调试（这样就能把断点挂到 C++ Core 那边了）
5. （可选）若准备提交 PR，建议启用 [clang-format 支持](https://maa.plus/docs/2.2-开发相关.html#在-visual-studio-中启用-clang-format)

### Linux | macOS

请参考 [Linux 编译教程](https://maa.plus/docs/2.1-Linux编译教程.html)

### API

- [C 接口](include/AsstCaller.h)：[集成示例](src/Cpp/main.cpp)
- [Python 接口](src/Python/asst/asst.py)：[集成示例](src/Python/sample.py)
- [Golang 接口](src/Golang/)：[集成示例](src/Golang/maa/maa.go)
- [Dart 接口](src/Dart/)
- [Java 接口](src/Java/src/main/java/com/iguigui/maaj/easySample/MaaCore.java)：[集成示例](src/Java/src/main/java/com/iguigui/maaj/easySample/MaaJavaSample.java)
- [Java HTTP 接口](src/Java/Readme.md)
- [Rust 接口](src/Rust/src/maa_sys/)：[HTTP 接口](src/Rust)
- [TypeScript 接口](https://github.com/MaaAssistantArknights/MaaAsstElectronUI/tree/main/packages/main/coreLoader)
- [Woolang 接口](src/Woolang/maa.wo)：[集成示例](src/Woolang/main.wo)
- [集成文档](https://maa.plus/docs/3.1-集成文档.html)
- [回调消息协议](https://maa.plus/docs/3.2-回调消息协议.html)
- [任务流程协议](https://maa.plus/docs/3.4-任务流程协议.html)
- [自动抄作业协议](https://maa.plus/docs/3.3-战斗流程协议.html)

### 外服适配

请参考 [外服适配教程](https://maa.plus/docs/2.5-外服适配教程.html)，对于国服已支持的功能，绝大部分的外服适配工作仅需要截图 + 简单的 JSON 修改即可。

### 想参与开发，但不太会用 GitHub?

[GitHub Pull Request 流程简述](https://maa.plus/docs/2.2-开发相关.html#github-pull-request-流程简述)

### Issue bot

请参考 [Issue bot 使用方法](https://maa.plus/docs/2.3-IssueBot使用方法.html)

## 致谢

### 开源库

- 图像识别库：[opencv](https://github.com/opencv/opencv.git)
- ~~文字识别库：[chineseocr_lite](https://github.com/DayBreak-u/chineseocr_lite.git)~~
- 文字识别库：[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)
- 深度学习部署库：[FastDeploy](https://github.com/PaddlePaddle/FastDeploy)
- 机器学习加速器：[onnxruntime](https://github.com/microsoft/onnxruntime)
- ~~关卡掉落识别：[企鹅物流识别](https://github.com/penguin-statistics/recognizer)~~
- 地图格子识别：[Arknights-Tile-Pos](https://github.com/yuanyan3060/Arknights-Tile-Pos)
- C++ JSON库：[meojson](https://github.com/MistEO/meojson.git)
- C++ 运算符解析器：[calculator](https://github.com/kimwalisch/calculator)
- ~~C++ base64编解码：[cpp-base64](https://github.com/ReneNyffenegger/cpp-base64)~~
- C++ 解压压缩库：[zlib](https://github.com/madler/zlib)
- C++ Gzip封装：[gzip-hpp](https://github.com/mapbox/gzip-hpp)
- 安卓触控事件器：[minitouch](https://github.com/openstf/minitouch)
- 安卓触控事件器：[MaaTouch](https://github.com/MaaAssistantArknights/MaaTouch)
- WPF MVVM框架：[Stylet](https://github.com/canton7/Stylet)
- WPF控件库：[HandyControl](https://github.com/HandyOrg/HandyControl) -> [HandyControls](https://github.com/ghost1372/HandyControls)
- C# 日志：[Serilog](https://github.com/serilog/serilog)
- C# JSON库：[Newtonsoft.Json](https://github.com/JamesNK/Newtonsoft.Json) & [System.Text.Json](https://github.com/dotnet/runtime)
- ~~下载器：[aria2](https://github.com/aria2/aria2)~~

### 数据源

- ~~公开招募数据：[明日方舟工具箱](https://www.bigfun.cn/tools/aktools/hr)~~
- ~~干员及基建数据：[PRTS明日方舟中文WIKI](http://prts.wiki/)~~
- 关卡数据：[企鹅物流数据统计](https://penguin-stats.cn/)
- 游戏数据及资源：[明日方舟客户端素材](https://github.com/yuanyan3060/ArknightsGameResource)
- ~~游戏数据：[《明日方舟》游戏数据](https://github.com/Kengxxiao/ArknightsGameData)~~

### 贡献/参与者

感谢所有参与到开发/测试中的朋友们，是大家的帮助让 MAA 越来越好！ (\*´▽｀)ノノ

[![Contributors](https://contributors-img.web.app/image?repo=MaaAssistantArknights/MaaAssistantArknights&max=114514&columns=15)](https://github.com/MaaAssistantArknights/MaaAssistantArknights/graphs/contributors)

## 声明

- 本软件 logo 并非使用 AGPL 3.0 协议开源，[耗毛](https://weibo.com/u/3251357314)、vie 两位画师及软件全体开发者保留所有权利。不得以 AGPL 3.0 协议已授权为由在未经授权的情况下使用本软件 logo，不得在未经授权的情况下将本软件 logo 用于任何商业用途。
- 本软件开源、免费，仅供学习交流使用。若您遇到商家使用本软件进行代练并收费，可能是设备与时间等费用，产生的问题及后果与本软件无关。

## 广告

用户交流 QQ 群：[MAA 使用 & 粥游交流 QQ 群](https://ota.maa.plus/MaaAssistantArknights/api/qqgroup/index.html)<br>
用户交流 TG 群：[Telegram 群](https://t.me/+Mgc2Zngr-hs3ZjU1)<br>
自动战斗 JSON 作业分享：[prts.plus](https://prts.plus) 或 [抄作业.com](http://抄作业.com)<br>
Bilibili 直播间：[直播间](https://live.bilibili.com/2808861) 每晚直播敲代码，近期很长一段时间应该都是在写本软件~<br>

技术群（舟无关、禁水）：[内卷地狱！(QQ 群)](https://jq.qq.com/?_wv=1027&k=ypbzXcA2)<br>
开发者群：[QQ 群](https://jq.qq.com/?_wv=1027&k=JM9oCk3C)<br>

如果觉得软件对你有帮助，帮忙点个 Star 吧！~（网页最上方右上角的小星星），这就是对我们最大的支持了！
