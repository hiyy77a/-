# assets/ — 自定义 AI 素材目录

把 **同名 PNG** 放进本目录，刷新游戏即自动加载；缺少的素材自动回退为内置水墨矢量造型。
也可以在游戏内按 **F2** 打开素材面板直接上传（保存在浏览器 localStorage）。

## 素材位一览

| 文件名 | 内容 | 要求 |
| --- | --- | --- |
| `player.png` | 主角剑客 | 透明底全身立绘，**面朝右**，建议高 ≥600px |
| `minion.png` | 小怪·黑衣刺客 | 透明底，**面朝左** |
| `boss_dao.png` | Boss·血刀魔君 | 透明底，面朝左 |
| `boss_qin.png` | Boss·幽泉琴魔 | 透明底，面朝左 |
| `boss_umbrella.png` | Boss·纸伞鬼姬 | 透明底，面朝左 |
| `boss_general.png` | Boss·铁血战侯 | 透明底，面朝左 |
| `boss_monk.png` | Boss·白骨禅魔 | 透明底，面朝左 |
| `boss_dragon.png` | Boss·墨龙真君 | 透明底，面朝左 |
| `qi.png` | 剑气弹 | 透明底，飞行方向朝右 |
| `bg_bamboo.png` | 背景·竹林 | ≥1920×1080，左右可平铺更佳 |
| `bg_desert.png` | 背景·大漠 | 同上 |
| `bg_ocean.png` | 背景·沧海 | 同上 |
| `bg_town.png` | 背景·古镇 | 同上 |
| `bg_cloud.png` | 背景·云海 | 同上 |

方向不符时，在游戏内 F2 面板勾选"翻转"即可，无需重新出图。

> 你此前生成的三张 Q 版立绘可直接保存为
> `boss_dao.png`（红发巨刀）、`boss_qin.png`（抚琴）、`boss_umbrella.png`（纸伞）。

## AI 绘图提示词参考（文生图）

通用后缀建议：`chibi, 2D game sprite, full body, clean edges, isolated on plain white background, high detail`（拿到图后用去背工具转透明底；部分工具支持直接 `transparent background`）。

- **主角剑客**：`chibi wuxia swordsman hero, white and indigo hanfu robe, red sash, high black ponytail with red ribbon, holding a jian sword, determined big anime eyes, facing right, full body, 2D game sprite, transparent background`
- **黑衣刺客**：`chibi assassin in black tattered cloak, large straw hat, face mask, glowing red eyes, flying sword under feet, facing left, 2D game sprite, transparent background`
- **血刀魔君**：`chibi warrior boss, spiky crimson hair, glowing red eyes, dark demon-face armor, giant dark greatsword with glowing red runes, red mist, facing left, transparent background`
- **幽泉琴魔**：`chibi evil musician boss, long straight black hair, pale smirking face, dark green robe, playing guqin zither on lap, dark purple vortex aura with faint demon faces, red sound wave rings, facing left, transparent background`
- **纸伞鬼姬**：`chibi ghost lady boss, long white hair with top bun and skull hairpin, red eyes, white robe, holding red oil-paper umbrella with glowing red spiral, floating talisman papers, dark red flame wisps, facing left, transparent background`
- **铁血战侯**：`chibi armored general boss, golden glowing eyes, black armor with gold trim, helmet with red plume, war banner on back, long spear, facing left, transparent background`
- **白骨禅魔**：`chibi sinister monk boss, bald head, grey robe with dark red kasaya, prayer beads, three floating cartoon skulls orbiting, green ghost fire, facing left, transparent background`
- **墨龙真君**：`chibi elder sorcerer boss, purple robe, dragon horns, long white beard, glowing purple eyes, ink dragon coiling around body, facing left, transparent background`
- **剑气弹**：`crescent-shaped ink slash projectile, black ink brushstroke with white core and vermilion swirl, flying right, game VFX sprite, transparent background`
- **背景（示例竹林）**：`Chinese ink wash painting landscape, misty bamboo forest, layered mountains, pale rice paper tone, red sun, horizontal seamless game background, 1920x1080`（大漠/沧海/古镇/云海同理替换主题）
