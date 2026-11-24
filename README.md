写给姐姐的二十一岁。

单文件页面 `index.html` + 一段生日歌 `birthday-song.mp3`，无构建步骤、无外部依赖。
双击 `index.html` 即可打开，也可直接部署到任意静态托管。

顺序：封面 → 点 21 根蜡烛 → 三个小彩蛋（刮刮卡 / 抽签 / 找 21）→ 一封信。
手机与电脑自适应。

音频：全程一条 `birthday-song.mp3`（234 秒完整曲子）。进蛋糕场景与点「从头再看一遍」时音轨回到 0 秒，
其余场景连续播放，不打断；蛋糕场景音量 0.55，其他场景 0.4。

发布：`deploy/` 是打包目录（仅 index.html 与 mp3），已上线 EdgeOne Pages，项目名 `sister-birthday`。

验证：`../tools/verify-birthday.mjs` 62 项结构断言、`../tools/test-audio-flow.mjs` 19 项音频流程断言。
