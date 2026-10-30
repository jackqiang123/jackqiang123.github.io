# 🎮 游戏小站 · jackqiang123.github.io

个人 GitHub Pages 游戏站：根页是门户主页，每个游戏是一个子文件夹子页面，点开即玩。全部为纯 HTML/JS 单文件游戏，零依赖、无广告。

**主页：https://jackqiang123.github.io/**

## 游戏目录

| 日期 | 游戏 | 地址 | 玩法 |
|---|---|---|---|
| 2026-10-24 | 🥕 保卫萝卜（v3 卡通版） | [/carrot-defense/](https://jackqiang123.github.io/carrot-defense/) | 塔防：4 种炮塔、15 波、Boss 波、升级/出售、射程预览；v3 全手绘卡通角色（怪物/萝卜/炮塔），结算横幅与固定面板 |
| 2026-10-24 | ⚡ 雷电 · Thunder Raiden（v2） | [/raiden/](https://jackqiang123.github.io/raiden/) | 纵版射击（致敬《雷电II》）：自动开火、红散射/紫电浆双武器、涟漪炸弹、火力 Lv8、3 大关 Boss、手机适配、WebAudio 合成音效与配乐 |
| 2026-10-24 | 🎯 狙击外星人 | [/alien-sniper/](https://jackqiang123.github.io/alien-sniper/) | 找茬狙击：伪装外星人藏在公园/海滩/夜市，拖动镜头 + 开镜放大寻找，屏息稳枪，误伤惩罚，5 关 |
| 2026-10-24 | 🔍 找不同（v2） | [/spot-diff/](https://jackqiang123.github.io/spot-diff/) | 左右双图找茬：真实照片 + AI 照片级编辑生成不同点（多一物/少一物/变一色），羽化融回原图、其余像素一致；3 关 18 处，点按判定、提示、星级、放大 A/B 对比模式 |
| 2026-10-25 | 🐱 找猫大作战 | [/find-cat/](https://jackqiang123.github.io/find-cat/) | 隐藏物品：3 张 AI 照片级生成的场景（客厅橘猫/花园狸花/卧室黑猫，猫在生成时即与环境融为一体），点按判定、2 倍放大拖动平移、提示圈、看答案、计时计分三星结算；卧室关有猫玩偶假目标 |
| 2026-10-26 | 🧱 彩虹打砖块 | [/breakout/](https://jackqiang123.github.io/breakout/) | 街机打砖块：触摸/鼠标/方向键移动挡板，撞击位置决定反弹角度；3 关共 154 块砖（1–3 血，硬砖显示剩余血量），⭐加宽挡板/💊加命道具掉落，小球拖尾与 WebAudio 音效，计分/生命/暂停/重开齐全 |
| 2026-10-27 | 🐍 贪吃蛇大冒险 | [/snake/](https://jackqiang123.github.io/snake/) | 经典贪吃蛇：20×20 草地、圆润卡通蛇身（眼睛/舌头/渐变）、红苹果 +10 分、限时金苹果 +30 分，每吃 5 个加速一级；键盘/WASD、滑动、大方向键，最高分 localStorage、粒子与 WebAudio 音效、暂停/重开 |
| 2026-10-28 | 🔢 2048 数字大冒险 | [/2048-adventure/](https://jackqiang123.github.io/2048-adventure/) | 滑动合并益智：4×4 棋盘合并相同数字翻倍冲 2048，经典配色瓷砖 + 合成发光、新块/合并动画；滑动/鼠标拖动/大方向键/键盘 WASD 四种操作，分数/最高分/最大数字/步数、悔一步、合成 2048 胜利弹窗可续玩、终局判定、WebAudio 音效 |
| 2026-10-29 | 🧠 记忆翻牌 | [/memory-match/](https://jackqiang123.github.io/memory-match/) | 记忆益智：4×4 翻牌找 8 对小动物，翻牌 3D 动画、配对 +100 分、翻错 0.7 秒后自动扣回、提示亮出一对（限 3 次）、计时 + 时间奖励 + 星级结算 + 最快纪录，点按/触摸/Tab+回车操作、WebAudio 音效可关 |
| 2026-10-30 | 💣 扫雷大冒险 | [/minesweeper/](https://jackqiang123.github.io/minesweeper/) | 经典扫雷：初级 9×9/10 雷、中级 12×12/24 雷、高级 14×14/40 雷，首次点击安全（周围一圈无雷）、空白连片自动展开、数字和弦快挖、挖/插旗模式切换、右键与长按插旗、每局 3 次安全提示、计时 + 各难度最快纪录 + 星级结算、WebAudio 音效可关 |

## 更新节奏
- 每天凌晨 3:00（太平洋时间）自动新增一个小游戏并更新本目录与主页卡片。

## 结构
- `index.html` —— 门户主页
- `carrot-defense/index.html` —— 保卫萝卜
- `raiden/index.html` —— 雷电
- `alien-sniper/index.html` —— 狙击外星人
- `spot-diff/index.html` —— 找不同
- `find-cat/index.html` —— 找猫大作战（照片内嵌 base64，单文件）
- `breakout/index.html` —— 彩虹打砖块
- `snake/index.html` —— 贪吃蛇大冒险
- `2048-adventure/index.html` —— 2048 数字大冒险
- `memory-match/index.html` —— 记忆翻牌
- `minesweeper/index.html` —— 扫雷大冒险
