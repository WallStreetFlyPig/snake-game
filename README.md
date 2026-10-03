# SNAKE CLUB · 贪吃蛇

一个可以直接在浏览器里玩的贪吃蛇游戏。全部内容都包含在 `index.html`，没有外部字体、追踪脚本、账号或服务器依赖。

## 怎么玩

- 电脑：方向键或 WASD 转向，空格 / P 暂停，Enter 开始。
- 手机：在棋盘上滑动，或点击屏幕方向按钮。
- 吃一个红色方块得 10 分，撞墙或撞到身体时本局结束。
- 悠闲、经典、极速三种难度；最高分按难度分别保存在当前浏览器。
- 离开页面时自动暂停。音效可以在右上角开启。

## 本地打开

用较新的 Chrome、Edge、Firefox 或 Safari 打开 `index.html` 即可玩。浏览器禁止本地存储时仍能游戏，但关闭页面后不能保留最高分。

## 发布到 GitHub Pages

1. 新建公开仓库 `snake-game`，将 `index.html` 和 `.nojekyll` 放到仓库根目录。
2. 打开仓库的 **Settings → Pages**。
3. 在 **Build and deployment** 下选择 **Deploy from a branch**。
4. 选择 **main** 分支和 **/(root)**，点击 **Save**。
5. 等待部署完成，访问 Pages 设置页面显示的网址。

这个版本使用相对路径和内嵌资源，支持 GitHub Pages 的项目子目录，无须构建。不同浏览器、设备及网址的最高分各自保存。
