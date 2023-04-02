# 一个结合人机交互，可穿戴设备，人工智能，虚拟现实的工程尝试

>version2 update:
>增添了整个系统的部分

## 可穿戴设备

- 七个IMU，大拇指两个，四指各一个，手掌一个，可以监测全手势。
- 用户按键与LED，实现基础功能交互。将游戏手柄集成上去。
- 使用FreeRTOS。
- 使用两个摄像头实现多模态：机器人摄像头与电脑摄像头。
- 使用振动与机械力反馈。

## 人机交互

- 7自由度，两只手各两个（前后，张开），头两个（上下），身体一个（左右）。
- USB与电脑相连，进行全部的通信与设置。
- 麦克风与扬声器模块。录取用户语音，进行语音识别。若为相关指令，则控制电脑（发送信号）或本身执行，若为提问，则转成文字，调用chatGPT，获得回答，转成AI语音，传回机器人，播放。
- 能够一直跟踪面朝声源，然后目视用户。
- 动作与表情预设，与用户进行交互。
- 通过手势指令，控制机器人完成指定任务。

## 人工智能

- 对多模态的手势信号进行识别，进行指令解读。
- 能够语音识别，AI语音播报，人脸识别，手部识别。
- 本地部署chatGPT，能够联网与断网运行。
- 屏下摄像头与麦克风阵列。

## 虚拟现实

- 头戴VR显示器，进行基础显示。
- 多人互动弹钢琴反馈游戏，带有手势指令。

## 桌面端UI

- 调试与设置。
- 修改手部数据。
- 编辑机器人预设动作与表情。
- 进行指令增减与更改。
- 人机交互指令增减与更改。

## 服务器

- 存储用户数据。
- 多人游戏数据交换汇总平台。

## 致谢

[wukong-robot](https://github.com/wzpan/wukong-robot "一个简单、灵活、优雅的中文语音对话机器人/智能音箱项目，支持ChatGPT多轮对话能力")
[Python-100-Days](https://github.com/jackfrued/Python-100-Days "Python - 100天从新手到大师")
[Relativty](https://github.com/relativty/Relativty "An open source VR headset with SteamVR supports for $200")
[ElectronBot](https://github.com/peng-zhihui/ElectronBot "一个桌面级小机器工具人")
[growth-in-action](https://github.com/phodal/growth-in-action "全栈增长工程师实战")
[jarvis](https://github.com/edisonwong520/jarvis "An intelligent assistant based voice control on Mac OS.中文版贾维斯Jarvis语音助手(电脑版Siri)")
[Cubli_Mini](https://github.com/ZhaJiHu/Cubli_Mini "源于苏黎世联邦理工学院的Cubli")
[Unity-MIDI_Piano](https://github.com/catdevpete/Unity-MIDI-Piano "3D Piano in Unity that can playback MIDI file songs")
