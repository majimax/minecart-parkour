# 🚃 矿车跑酷（Minecart Parkour）

一款像素风格的 HTML5 跑酷小游戏。在火车轨道上操控矿车，躲避陷阱、收集金币，挑战更高分。

## 玩法

- 🚂 操控矿车在轨道上前进
- 🪙 拾取金币，累计分数
- ⚠️ 躲避陷阱和障碍
- 🌅 关卡拥有 day / eve / night 三种光照

## 操作

- **← / →** 切换轨道
- **空格 / 触屏点击** 跳跃
- **R** 重开
- **P / 触屏** 暂停

## 运行

直接用浏览器打开 `index.html` 即可，无需后端。

```bash
# 本地起一个静态服务（可选）
python3 -m http.server 8080
# 浏览器访问 http://localhost:8080
```

## 技术栈

- 纯 HTML5 Canvas
- 原生 JavaScript（无依赖）
- 像素美术（自绘）

## 目录

```
parkour-game/
├── index.html          # 入口（含全部游戏逻辑）
├── assets/
│   ├── bg/             # 背景图（day/eve/night）
│   ├── land/           # 地块与陷阱
│   └── role/           # 角色精灵
└── README.md
```

## 作者

Coding × 粟源 · Star Office
