# TankWar

一款使用 HTML、CSS 和 JavaScript 编写的单页坦克大战小游戏。

游戏默认关闭声音。点击 `SOUND OFF` 开启后，初始界面播放长版背景音乐，
进入战斗后切换为循环背景音乐。按 `M` 或点击右侧声音按钮可以同时控制
游戏音效与背景音乐。启动界会先加载并预热两首 BGM，避免进入游戏后因音乐
资源尚未就绪而出现无声或中途中断。

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
