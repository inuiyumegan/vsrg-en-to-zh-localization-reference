; ArrowVortex 编辑器专用翻译词库
; 译者 ArrowVortex 汉化组，风格以简体中文音游圈通行译法为准
; 基于 lang/zh_CN.json 提取，合并扩展编辑器字符串

;=== 菜单栏 ===
File: 文件(&F)
Edit: 编辑(&E)
Chart: 谱面(&C)
Notes: 音符(&N)
Tempo: 节拍(&T)
Audio: 音频(&A)
View: 视图(&V)
Help: 帮助(&H)

;=== 文件操作 ===
Open...: 打开...
Recent files: 最近文件
Close: 关闭
Save: 保存
Save as...: 另存为...
Properties...: 属性...
Exit: 退出

;=== 编辑操作 ===
Undo: 撤销
Redo: 重做
Cut: 剪切
Copy: 复制
Paste: 粘贴
Delete: 删除
Select all: 全选
Select region: 选择区域
Enable jump to next note: 启用跳转到下一音符
Enable undo/redo jump: 启用撤销/重做跳转
Enable time-based copy: 启用基于时间的复制

;=== 谱面操作 ===
Chart list...: 谱面列表...
Dancing bot...: 自动演示...
New chart...: 新建谱面...
Previous chart: 上一个谱面
Next chart: 下一个谱面
Convert: 转换
Delete chart: 删除谱面
Routine → ITG Couple: Routine → ITG 双人
ITG Couple → Routine: ITG 双人 → Routine

;=== 音符操作 ===
Select: 选择
Mirror: 镜像
Expand: 扩展
Compress: 压缩
Generate...: 生成...

;=== 量化/分度 ===
Quantization: 量化
4th: 4分
8th: 8分
12th: 12分
16th: 16分
24th: 24分
32nd: 32分
48th: 48分
64th: 64分
192nd: 192分
2:1 (8th to 4th): 2:1 (8分转4分)
3:2 (12th to 8th): 3:2 (12分转8分)
4:3 (16th to 12th): 4:3 (16分转12分)
1:2 (4th to 8th): 1:2 (4分转8分)
2:3 (8th to 12th): 2:3 (8分转12分)
3:4 (12th to 16th): 3:4 (12分转16分)

;=== 音符类型 ===
Steps: 音符
Mines: 地雷
Holds: 长键
Rolls: 连键
Fakes: 假键
Lifts: 离键
Before cursor: 光标之前
After cursor: 光标之后

;=== 音符转换 ===
Notes → Mines: 音符 → 地雷
Notes → Fakes: 音符 → 假键
Notes → Lifts: 音符 → 离键
Mines → Notes: 地雷 → 音符
Mines → Fakes: 地雷 → 假键
Mines → Lifts: 地雷 → 离键
Fakes → Notes: 假键 → 音符
Lifts → Notes: 离键 → 音符
Holds ↔ Rolls: 长键 ↔ 连键
Holds → Steps: 长键 → 单键
Holds → Mines: 长键 → 地雷
Switch Player: 切换玩家

;=== 镜像/翻转 ===
Horizontally: 水平翻转
Vertically: 垂直翻转
Both: 双向翻转

;=== 节拍/时间 ===
BPM: BPM
Stop: 停止
Delay: 延迟
Warp: 变速
Time Sig.: 拍号
Tick Count: Tick 计数
Combo: 连击
Speed: 倍速
Scroll: 滚动
Fake: 假键
Label: 标签
BPM change: BPM 变更
BPM changes: BPM 变更
Beats per minute: 每分钟拍数
Time signature: 拍号
Time signatures: 拍号
Tick count: Tick 计数
Combo segment: 连击段
Combo segments: 连击段
Speed segment: 速度段
Speed segments: 速度段
Scroll segment: 滚动段
Scroll segments: 滚动段
Fake segment: 假段
Fake segments: 假段
Labels: 标签
Duration (seconds): 时长（秒）
Duration (beats): 时长（拍）
Beats per measure\nBeat note type: 每小节拍数\n拍子类型
Hold ticks per beat: 每拍保持的 ticks
Hit multiplier\nMiss multiplier: 命中倍率\n错击倍率
Stretch ratio\nDelay time\nUnit (beats/time): 拉伸比例\n延迟时间\n单位（拍/时间）
Scroll rate multiplier: 滚动速率倍数
Description: 描述

;=== 播放控制 ===
Basic: 基本
Play/pause: 播放/暂停
Increase snap: 增加分度
Decrease snap: 减少分度
Move cursor up: 光标上移
Move cursor down: 光标下移
Zoom in: 放大
Zoom out: 缩小
Scale Increase: 缩放增加
Scale Decrease: 缩放减少

;=== 消息日志 ===
MESSAGE LOG: 消息日志
[ESC/F2] close: [ESC/F2] 关闭
[Delete] clear: [Delete] 清除

;=== 调整同步 ===
ADJUST SYNC: 调整同步
Music offset: 音乐偏移（秒）
Music start time relative to the first beat, in seconds: 相对于首拍的音乐起始时间（秒）
Tweak the music offset: 微调音乐偏移
Initial BPM: 初始 BPM
Move first beat: 移动首拍
Increase the music offset by one beat: 将音乐偏移增加一拍
Increase the music offset by half a beat: 将音乐偏移增加半拍
Decrease the music offset by half a beat: 将音乐偏移减少半拍
Decrease the music offset by one beat: 将音乐偏移减少一拍
BPM estimates calculated by the editor: 编辑器计算的 BPM 估计值
Apply BPM: 应用 BPM
Find BPM: 查找 BPM
Estimate the music BPM by analyzing the audio: 通过分析音频估计音乐的 BPM

;=== 调整节拍 ===
ADJUST TEMPO: 调整节拍
Halve the current BPM: 当前 BPM 减半
Double the current BPM: 当前 BPM 翻倍
Convert the selected region to a stop: 将选中区域转换为停止（Stop）
Convert the selected region to a stutter gimmick: 将选中区域转换为断奏（Stutter）
Stop length at the current beat, in seconds: 当前拍的停止时长（秒）
Offset in beats: 偏移（拍）
Number of beats to insert or remove: 要插入或删除的拍数
Apply offset to: 应用偏移到
This chart: 仅此谱面
All charts: 所有谱面
Insert beats: 插入拍数
Delete beats: 删除拍数
Insert the above number of beats at the cursor position\nAll notes and tempo changes after the cursor will be shifted down: 在光标位置插入上述数量的拍数\n光标之后的所有音符与速度变化将向后移动
Delete the above number of beats at the cursor position\nAll notes and tempo changes after the cursor will be shifted up\nNotes and tempo changes in the deleted region will be removed: 在光标位置删除上述数量的拍数\n光标之后的所有音符与速度变化将向前移动\n被删除区域内的音符与速度变化将被移除
ADJUST TEMPO (SM5): 调整节拍（SM5）

;=== 波形设置 ===
WAVEFORM SETTINGS: 波形设置
Presets: 预设
Vortex: Vortex
DDReam: DDReam
Preset styles for the waveform appearance: 波形外观的预设样式
BG color: 背景颜色
Color of the waveform background: 波形背景颜色
Wave color: 波形颜色
Color of the waveform: 波形颜色
Filter color: 滤波颜色
Color of the filtered waveform: 滤后波形颜色
Luminance: 亮度
Uniform: 均匀
Amplitude: 振幅
Wave shape: 波形形状
Rectified: 整流
Signed: 带符号
Anti-aliasing: 抗锯齿
None: 无
2x: 2x
3x: 3x
4x: 4x
Determines the smoothness of the waveform shape: 决定波形形状的平滑程度
Filter type: 滤波类型
High-pass: 高通
Low-pass: 低通
Determines the shape of the waveform filter: 决定波形滤波的类型
Strength: 强度
The strength of the waveform filter: 波形滤波强度
Overlay filtered waveform: 叠加滤波波形
If enabled, the filtered waveform is shown on top of the original waveform: 启用后，滤波波形将叠加显示在原始波形之上
Disable filter: 禁用滤波
Hides the filtered waveform: 隐藏滤波波形
Apply filter: 应用滤波
Shows the filtered waveform: 显示滤波波形

;=== 同步/节拍菜单入口 ===
Adjust sync...: 调整同步...
Adjust tempo...: 调整节拍...
Adjust tempo SM5...: 调整节拍SM5...
Sync mode: 同步模式
Breakdown...: 分段...
Visual sync anchor: 视觉同步锚点
Cursor row: 光标行
Receptors row: 判定区行

;=== 音量/音频 ===
Volume: 音量
Default: 默认
Louder: 更高
Softer: 更低
Mute: 静音
Faster: 更快
Slower: 更慢
Beat tick: 节拍提示音
Note tick: 音符提示音
Convert to ogg: 转换为.ogg格式

;=== 显示 ===
Hide: 隐藏
More visible: 更亮
Less visible: 更暗
Stretch: 拉伸
Letterbox: 宽荧幕
Crop: 裁剪
Options: 选项
Reset: 重置

;=== 导航 ===
Set Snap: 设置分度
Previous: 上一个
Next: 下一个
Up: 上
Down: 下
Previous beat: 上一拍
Next beat: 下一拍
Previous measure: 上一小节
Next measure: 下一小节
Stream start: 连击流起点
Stream end: 连击流终点
Selection start: 选区起点
Selection end: 选区终点
First beat: 首拍
Last beat: 末拍

;=== 视图显示 ===
Show chart: 显示谱面
Show snap: 显示分度
Show BPM: 显示BPM
Show row: 显示行
Show beat: 显示拍
Show measure: 显示小节
Show time: 显示时间
Show timing mode: 显示计时模式
Show waveform: 显示波形
Show beat lines: 显示拍线
Show tempo boxes: 显示节拍悬浮窗
Show tempo help: 显示节拍帮助
Show notes: 显示音符
Use SM-style preview: 使用SM风格预览
Reverse scroll: 反向滚动
Time based (C-mod): 基于时间 (C-模式)
Row based (X-mod): 基于行 (X-模式)

;=== 视图元素 ===
Waveform...: 波形...
Noteskins: 皮肤
Minimap: 进度条
Background: 背景
Zoom: 缩放
Snap: 分度
Cursor: 光标
Status: 状态元素

;=== 快捷键/日志 ===
Shortcuts...: 快捷键...
Message Log...: 消息日志...
Debug Log...: 调试日志...
About...: 关于...
Clear list: 清除列表

;=== 谱面属性 ===
SIMFILE PROPERTIES: 谱面属性
Title: 标题
Subtitle: 副标题
Artist: 艺术家
Credit: 制作人
Title of the song: 歌曲标题
Subtitle of the song: 歌曲副标题
Artist of the song: 歌曲艺术家
Author of the simfile: 谱面作者
Music: 音乐
Path of the music file: 音乐文件路径
Search the stepfile directory for audio files: 在谱面目录中搜索音频文件
BG: 背景
Path of the background image: 背景图片路径
Search the stepfile directory for background images: 在谱面目录中搜索背景图片
Banner: 横幅
Path of the banner image: 横幅图片路径
Search the stepfile directory for banner images: 在谱面目录中搜索横幅图片
CD Title: CD标题
Path of the CD title image: CD标题图片路径
Search the stepfile directory for CD title images: 在谱面目录中搜索CD标题图片
Preview: 预览
to: 至
The start time of the music preview: 音乐预览开始时间
The end time of the music preview: 音乐预览结束时间
Set region: 设置区域
Set the music preview to the selected region: 将音乐预览设置为选中区域
Play the music preview: 播放音乐预览
Disp. BPM: 显示BPM
The low value of the display BPM: 显示BPM的最低值
The high value of the display BPM: 显示BPM的最高值
Custom: 自定义
Random: 随机
Determines how the BPM preview is displayed: 决定BPM预览的显示方式

;=== 谱面属性对话框标题 ===
CHART PROPERTIES: 谱面属性
CHART LIST: 谱面列表
NEW CHART: 新建谱面
ADJUST SYNC: 调整同步
ADJUST TEMPO: 调整节拍
ADJUST TEMPO SM5: 调整节拍SM5
DANCING BOT: 自动游玩bot
GENERATE NOTES: 生成音符
WAVEFORM SETTINGS: 波形设置
TEMPO BREAKDOWN: 节拍分段
ZOOM: 缩放
CUSTOM SNAP: 自定义分度
