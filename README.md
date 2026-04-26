# DungeonSweeper

踩地雷 × RPG 的單檔瀏覽器遊戲，靈感來自 [DragonSweeper](https://danielben.itch.io/dragonsweeper)。

## 玩法

- 點藍點開局，展開周圍 8 格
- 格子上的數字 = 周圍怪物的總傷害
- 點怪物戰鬥：怪物 power = 受到傷害 = 獲得 XP
- 道具點一下顯示，再點一下消耗（可選擇時機）
- HP 歸零不會 Game Over，可繼續探索、撿道具升級回血
- 點擊角色頭像 🧙 升級，升級時全回血，無等級上限
- 打敗 Boss 即勝利（HP 不夠打 Boss 則失敗）

## 怪物

| Emoji | 名稱 | Power |
|-------|------|-------|
| 🐉 | Dragon | 5 |
| 👹 | Ogre | 4 |
| 💀 | Skeleton | 3 |
| 🕷️ | Spider | 2 |
| 🦇 | Bat | 2 |
| 🐍 | Snake | 1 |
| 🐀 | Rat | 1 |

## 道具

- ❤️ Healing Scroll — 回 2 血
- 🍕 Pizza — 回半血
- 📦 Chest — 獲得 XP

## 難度

| 難度 | 初始 HP | Boss Power |
|------|---------|------------|
| Easy | 5 | 8 |
| Normal | 4 | 10 |
| Hard | 3 | 12 |

## 技術

- 單一 HTML 檔，無外部依賴
- ES5 JavaScript，支援舊瀏覽器
- Web Audio API 合成音效
- 本地 MP3 背景音樂（bgm.mp3 / bgm2.mp3 / bgm3.mp3）

## 遊玩

**線上：** https://john8895.github.io/dungeon-sweeper/

**本地：** 直接開啟 `index.html`
