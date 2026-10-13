# 坦克大战 Tank Battalion

经典坦克大战小游戏，纯 HTML5 Canvas 实现，无任何依赖。

## 运行

直接用浏览器打开 `index.html` 即可，或启动本地服务：

```bash
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## 玩法

- 方向键 / WASD 移动，空格 / 回车发射，P 暂停
- 击毁所有敌军坦克进入下一关（关卡越往后敌人越多、越硬）
- 砖墙（棕色）可被击毁，钢墙（灰色）不可击穿
- 保卫基地（金色旗帜），基地被毁或生命耗尽即游戏结束
- 得分与最高分保存在浏览器 localStorage
