# TankWar

一款使用 HTML、CSS 和 JavaScript 编写的单页坦克大战小游戏。

游戏默认关闭声音。点击 `SOUND OFF` 开启后，初始界面播放长版背景音乐，
进入战斗后切换为循环背景音乐。按 `M` 或点击右侧声音按钮可以同时控制
游戏音效与背景音乐。启动界会先加载初始界面 BGM，进入主界面后继续在后台
预热战斗 BGM，避免因音乐资源尚未就绪而出现长时间等待或中途中断。

## 操作与设置

- 桌面端使用方向键或 `WASD` 移动，空格或 `J` 开火，`P` 暂停并打开设置。
- 手机端可点击齿轮打开设置，并使用轮盘或方向键移动。
- 游戏音效与游戏音乐均支持五档独立音量，设置为 0 时关闭对应声音。
- 手机端可在设置中切换轮盘和方向键两种移动方式。

## 在线游玩

复制下面的网址并在浏览器中打开，即可直接运行游戏：

```text
https://takakiuri.github.io/First-Repository-for-my-tank-war/src/TankWar.html
```

也可以点击此处开始游戏：

[开始坦克大战](https://takakiuri.github.io/First-Repository-for-my-tank-war/src/TankWar.html)

## 项目结构

```text
TankWar/
├── src/
│   └── TankWar.html
├── assets/
│   └── audio/
│       ├── TankWar_BGM.m4a
│       ├── TankWar_BGM_Loop.m4a
│       ├── TankWar_BGM.wav
│       └── TankWar_BGM_Loop.wav
├── TankWar.iml
└── README.md
```
