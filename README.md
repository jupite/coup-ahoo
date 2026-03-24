# 海上舰炮对射游戏

一个基于Canvas 2D API和TypeScript开发的海上舰炮对射游戏。

## 游戏特色

- 海上战场背景，包含渐变天空和水面效果
- 海盗主题船帆设计，带有骷髅头标志和随机花纹
- 可控制的战舰，支持瞄准和射击
- 骰子系统用于决定射击结果
- 船员系统，不同角色有不同技能
- 响应式动画效果

## 技术栈

- TypeScript
- Canvas 2D API
- Webpack
- 面向对象编程

## 安装和运行

### 安装依赖

```bash
npm install
```

### 开发模式

```bash
npm run start
```

### 构建生产版本

```bash
npm run build
```

## 游戏玩法

1. 使用鼠标控制战舰的瞄准方向
2. 点击鼠标左键发射炮弹
3. 通过骰子结果决定射击效果
4. 利用船员的特殊技能获得优势
5. 击沉敌方战舰获得胜利

## 项目结构

- `src/` - 源代码目录
  - `engine/` - 游戏引擎核心
  - `colors.ts` - 颜色定义
  - `dude.ts` - 人物绘制
  - `dice.ts` - 骰子系统
  - `scene.ts` - 场景绘制
  - `ship.ts` - 战舰绘制
  - `index.ts` - 游戏入口

## 游戏截图

![游戏截图](https://trae-api-cn.mchost.guru/api/ide/v1/text_to_image?prompt=pixel%20art%20pirate%20ship%20battle%20game%20on%20ocean%20with%20cannon%20fire&image_size=landscape_16_9)

## 许可证

MIT
