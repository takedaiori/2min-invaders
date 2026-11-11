# 2MIN INVADERS 👾

## 简体中文 🇨🇳

这是一款由 **腾讯元宝（Yuanbao）AI 助手** 编写的 STG 游戏 ✨ —— 从玩法、数值、代码，到菜单视觉与说明文档，都由 AI 一并完成 🤖

### 🧩 用什么做的：一个 HTML 文件就够了

没有复杂、全面的游戏引擎，也没有构建工具、依赖包和素材管线 🙅‍♂️ 全部塞进**一个 `.html` 文件**，双击就能玩：

- 🖼️ **Canvas 2D 逐像素绘制**：飞机、敌机、弹幕、道具全是小色块，连文字都是自绘的 5×7 点阵字模，不加载任何字体；
- 🔊 **Web Audio 实时合成**：音效是现场"算"出来的波形，零音频文件；
- 🕹️ **原生浏览器事件**：键盘、鼠标、触屏、手柄统一接进来，五类输入一个位移出口；
- 💾 **localStorage**：成绩和静音状态存在本地；
- ⏱️ **固定步长主循环**：节奏稳稳的，切后台自动挂起；
- 🏷️ **内嵌字标**：菜单 Logo 以 data URI 塞进文件里，**零外部请求、零联网** 🌐🚫

因为这个游戏要的只是"一块画布 + 一个循环 + 一堆矩形"，没有 3D、没有物理刚体、没有骨骼动画、也没有上万发弹幕 💡 上引擎反而会多出包体、启动、音频桥接一堆负担。把力气全花在手感与节奏上，才是这种街机短局最划算的做法 🎯

### 🛸 风格源自《太空侵略者》

敌机成阵列、从屏幕上方一点点压近；黑底 + 高对比块状轮廓，一眼分得清谁是谁；顶部一条简洁计分栏；还有两词全大写、不用解释的街机命名 👾 造型、字标、音效、代码全部原创，只把那份老街机的"压迫感"搬过来 ✨

### ⚡ 流程更爽快、更紧凑

- 不用手动开火，主角机自己就在突突突 🔫，上手零门槛；
- 开局就是密集弹幕的观感，视觉上直接拉满 💥；
- 敌机不再排队等，持续从屏顶压下来，机群越堆越满 📈；
- 道具从被击落的敌机里"爆"出来，还主动往下迎着你落，接不接得住全看走位 🟢🔵🟡；
- 没有教学关、没有加载条、没有层层菜单，三个词选完就打，结算一屏看完立刻能再来一局 🔁；
- 特效只画在边缘和局部，绝不挡住上方火力视野 👀

### 💪 困难模式

熟悉了节奏之后，总有人想被狠一点考验 😈 困难模式沿用同一套操作和规则，只是把压力整体抬高、机群更早涌上来 —— 不用重学任何东西，但每一秒都得更专注。给"再来一局"一个明确的进阶目标，也方便和朋友们比谁撑得更漂亮 🏆

### 🧘 "不会结束"的禅模式

紧张够了，也得有个能松口气的地方 🌙 禅模式把终局压力拿掉，只留下"把分数一路堆上去"这一件轻松事；节奏平缓、可以慢慢玩，想停就停，停的时候照样给你好好结算 📊 它和前面的紧凑单局刚好一紧一松：想挑战就去冲，想放空就待在这儿 🫶

---

就这些啦，冲～ 🎮🚀

---

## English 🌍

An STG game written by **Tencent Yuanbao**, an AI assistant ✨ — gameplay, balancing, code, menu visuals and docs, all made by AI 🤖

### 🧩 What it's built with: just one HTML file

No complex, full-blown game engine. No build step, no packages, no asset pipeline 🙅‍♂️ Everything lives in **a single `.html` file** — double-click and play:

- 🖼️ **Canvas 2D, pixel by pixel**: ships, enemies, bullets and pickups are all little color blocks; even the text is a hand-drawn 5×7 bitmap font, with zero web fonts;
- 🔊 **Web Audio synthesis**: every sound is a waveform generated on the spot, zero audio files;
- 🕹️ **Native browser events**: keyboard, mouse, touch and gamepad all funnel into one movement path;
- 💾 **localStorage**: high scores and mute state stay on your device;
- ⏱️ **Fixed-step game loop**: steady pacing, auto-pauses when you switch tabs;
- 🏷️ **Inline wordmark**: the menu logo is embedded as a data URI — **zero network requests, fully offline** 🌐🚫

All this game really needs is *one canvas, one loop, and a bunch of rectangles* 💡 No 3D, no rigid-body physics, no skeletal animation, no ten-thousand-bullet barrages. An engine would only add bundle size, startup cost and an audio bridge. For a tight arcade run like this, spending every bit of effort on feel and pacing is the smarter trade 🎯

### 🛸 Inspired from *Space Invaders*

Enemies advancing in formation from the top of the screen; a dark background with high-contrast blocky silhouettes so you can read everything at a glance; a clean score strip up top; and a two-word, all-caps arcade title that needs no explanation 👾 Every sprite, the wordmark, the sounds and the code are original — only that old-school sense of pressure carried over ✨

### ⚡ It feels faster and tighter

- No fire button — your ship shoots automatically, so there's zero learning curve 🔫;
- The barrage looks maxed out from the very first second 💥;
- Enemies don't wait in line, they keep pressing down from above and the swarm keeps growing 📈;
- Pickups **burst out of downed enemies** and drift down toward you, so catching them is all about movement 🟢🔵🟡;
- No tutorial, no loading bar, no nested menus — pick one of three words and you're in; the results screen is one glance, then straight back for another run 🔁;
- Effects stay on the edges and around your ship, never blocking the firing lane above 👀

### 💪 Hard mode

Once you know the rhythm, some folks want a real test 😈 Hard mode keeps the exact same controls and rules but turns the pressure up and brings the swarm in sooner — nothing new to learn, just more focus every second. It gives "one more run" a clear next goal, and makes comparing scores with friends a lot more fun 🏆

### 🧘 There's also a Zen mode that "won't end"

After all that tension, you need somewhere to exhale 🌙 Zen mode takes the ending pressure away and leaves just one gentle thing: keep stacking up the score 📊 The pace is calm, you can play slowly, stop whenever you like, and you still get a proper score + time summary when you do 🫶 It's the perfect counterpart to the tight single run: go chase a challenge when you feel like it, or just hang out here when you don't 🫶

---

That's it — go have fun~ 🎮🚀
