# MUG 翻译参考词库（mug-reference）

VSRG 音游中文本地化翻译参考词库，覆盖 ArrowVortex、Etterna、Interlude、Malody、osu!mania 五个游戏/工具及通用术语。

> 译者：幽幽子的饲养员 / ArrowVortex 汉化组  
> 风格：简体中文音游圈通行译法

## 文件索引

| 文件 | 内容 | 格式 |
|------|------|------|
| [`common.md`](./common.md) | 跨游戏通用术语（音符类型、键型、难度、判定、段位、模组、皮肤、社区赛事、UI词汇） | Markdown 表格 |
| [`arrowvortex.md`](./arrowvortex.md) | ArrowVortex 编辑器 UI 与谱面编辑 | INI (`"key": "value"`) |
| [`etterna.md`](./etterna.md) | Etterna 客户端 + Rebirth/'Til Death 主题 | INI (`[section] key=value`) |
| [`interlude.md`](./interlude.md) | Interlude 客户端（含 HUD、选歌、热键） | INI (`key=value`) |
| [`malody.md`](./malody.md) | Malody 客户端（含商店、多人、编辑、皮肤） | INI (`key = value`) |
| [`osumania.md`](./osumania.md) | osu!mania 模式（含谱面状态、键型、编辑、赛事） | INI (`;注释`) |

## 优先级规则

- **游戏专用词库**优先于 `common.md`
- `common.md` 中的「已废弃译法」章节记录旧译 → 新译对照，**新译文不得使用旧译**

## 翻译原则

- 缩写保留不译：BPM、NPS、FC、PFC、SDG、MFC、WF 等
- 全角标点用于中文正文，半角用于英文/数字
- 占位符 `%s` `%d` `\n` 保留
- 倍速数值后必须加「倍速」：`1.3x` → `1.3倍速`
