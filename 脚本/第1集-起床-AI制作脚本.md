# 第1集「起床」AI制作脚本

> 版本：v1.0
> 总时长：约27秒
> 画面比例：9:16（竖屏）
> 分辨率：1080x1920
> 帧率：30fps

---

## 一、项目元数据

```json
{
  "project": "钩织玩偶剧场",
  "episode": 1,
  "title": "起床",
  "duration": "27s",
  "aspect_ratio": "9:16",
  "resolution": "1080x1920",
  "fps": 30,
  "style": "stop_motion",
  "visual_style": "crochet_doll",
  "background": "solid_beige",
  "camera": "top_down"
}
```

---

## 二、视觉风格指南

### 2.1 整体风格
- **风格类型**：定格动画 / Stop Motion
- **材质感**：钩织毛线质感，温暖柔和
- **色调**：暖色调，自然光感
- **背景**：纯色（米白/浅灰），无杂物

### 2.2 角色视觉描述（AI生成提示词）

#### 羊绅士 (Mr. Sheep)
```
A small crochet amigurumi sheep doll, cream white yarn texture, 
wearing a tiny brown top hat, holding a miniature walking cane, 
round body with a cute upturned butt, simple black bead eyes, 
gentleman posture, stop motion style, soft lighting
```

#### 莓莓 (Berry)
```
A tiny crochet amigurumi strawberry doll, red with green leaf top, 
very short stubby legs, round body, simple black bead eyes, 
calm expression, minimal movement, stop motion style, soft lighting
```

#### 啾啾 (Chirp)
```
A small crochet amigurumi bird doll, grey and blue yarn, 
round head, wings folded flat against body, cannot fly, 
energetic posture, simple black bead eyes, stop motion style, soft lighting
```

---

## 三、分镜脚本

### 镜头 1 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_01 |
| 时长 | 2.5秒 |
| 景别 | 全景 (Wide Shot) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down view of three crochet dolls lying flat in a row on a beige background. 
Left: sheep doll lying on its back. Center: strawberry doll lying still. 
Right: bird doll lying down. All eyes closed, peaceful sleeping pose. 
Soft morning light from upper left, gentle shadows. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 羊绅士 | 画面左侧 | 平躺，闭眼 |
| 莓莓 | 画面中间 | 平躺，闭眼 |
| 啾啾 | 画面右侧 | 平躺，闭眼 |

**音频**:
- 旁白: "钩织小屋，早上六点半。"
- 音效: 闹钟滴答声（轻）
- BGM: 轻钢琴/吉他，音量20%

**字幕**:
```
位置: 底部居中
内容: 「钩织小屋 · 早上 6:30」
样式: 白色小字，半透明背景
```

---

### 镜头 2 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_02 |
| 时长 | 2.0秒 |
| 景别 | 中景 (Medium Shot) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down view of a crochet sheep doll sitting up, leaning against a tiny cup 
for support. Hat perfectly straight, walking cane placed neatly beside him. 
Other dolls not in frame. Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 羊绅士 | 画面左侧 | 坐姿，靠杯子，帽子端正，手杖在旁边 |

**音频**:
- 台词（羊绅士）: "注意，形象。"
- 声线: 装腔作势的中年男声，慢条斯理
- 音效: "叮"一声

**字幕气泡**:
```
位置: 羊绅士头顶
内容: 「注意形象。」
样式: 方形绅士风格气泡，白底黑字
动画: 弹出效果
```

---

### 镜头 3 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_03 |
| 时长 | 1.5秒 |
| 景别 | 中景 (Medium Shot) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down view of two crochet dolls. Left: sheep doll sitting, body slightly 
turned toward center. Center: strawberry doll still lying flat, unchanged. 
Sheep appears to be looking at strawberry with slight disdain. 
Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 羊绅士 | 画面左侧 | 坐姿，身体微转向莓莓 |
| 莓莓 | 画面中间 | 平躺，完全没动 |

**音频**:
- 台词（羊绅士）: "你，不起床的吗？"
- 声线: 带点嫌弃

**字幕气泡**:
```
位置: 羊绅士头顶
内容: 「你不起床的吗？」
样式: 方形绅士风格气泡，白底黑字
```

---

### 镜头 4 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_04 |
| 时长 | 2.5秒 |
| 景别 | 近景 (Close-up) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down close-up of a crochet strawberry doll lying perfectly still, 
almost imperceptible movement. Calm, unbothered expression. 
Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 莓莓 | 画面中心 | 平躺，几乎没动 |

**音频**:
- 台词（莓莓）: "我起了。只是你看不见我动。"
- 声线: 冷淡女声，语速很慢，没有情绪波动
- 节奏: 台词前后各留0.5秒空白

**字幕气泡**:
```
位置: 莓莓头顶
内容: 「我起了。只是你看不见我动。」
样式: 圆形简约气泡，浅粉底白字
```

---

### 镜头 5 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_05 |
| 时长 | 2.0秒 |
| 景别 | 中景 (Medium Shot) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down view of a crochet sheep doll sitting, body tilted slightly 
as if shaking head in disapproval. Hat still straight. 
Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 羊绅士 | 画面左侧 | 坐姿，身体角度歪5-10度（表示摇头） |

**音频**:
- 台词（羊绅士）: "你从昨晚到现在，一毫米都没挪。"
- 声线: 更嫌弃

**字幕气泡**:
```
位置: 羊绅士头顶
内容: 「你从昨晚到现在一毫米都没挪。」
样式: 方形绅士风格气泡，白底黑字
```

---

### 镜头 6 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_06 |
| 时长 | 2.5秒 |
| 景别 | 近景 (Close-up) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down close-up of a crochet strawberry doll lying completely motionless, 
perfectly still. Emphasizes stability and calm. 
Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 莓莓 | 画面中心 | 纹丝不动 |

**音频**:
- 台词（莓莓）: "那叫稳定。你学学。"
- 声线: 依然冷淡
- 音效: 轻微"嗯？"音效

**字幕气泡**:
```
位置: 莓莓头顶
内容: 「那叫稳定。你学学。」
样式: 圆形简约气泡，浅粉底白字
```

---

### 镜头 7 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_07 |
| 时长 | 1.5秒 |
| 景别 | 中景 (Medium Shot) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down view of a crochet bird doll suddenly sliding into frame from the right 
side, stopping next to the sheep doll. Energetic entrance. 
Sheep doll sitting on left. Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 羊绅士 | 画面左侧 | 坐姿 |
| 啾啾 | 从右侧滑入，停在羊绅士旁边 | 动态姿势 |

**动画**:
- 啾啾从画面外右侧滑入
- 动画曲线: 快速减速停止

**音频**:
- 台词（啾啾）: "起床了起床了！今天干嘛！"
- 声线: 话痨少年音，语速快，很兴奋
- 音效: "嗖"一声

**字幕气泡**:
```
位置: 啾啾头顶
内容: 「起床了起床了！今天干嘛！」
样式: 爆炸/不规则气泡，黄底黑字，字号大
```

---

### 镜头 8 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_08 |
| 时长 | 2.0秒 |
| 景别 | 中景 (Medium Shot) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down view of a crochet sheep doll knocked askew, body tilted, 
hat crooked to one side, walking cane fallen on the ground. 
Bird doll standing nearby innocently. Comedic disaster scene. 
Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 羊绅士 | 画面左侧 | 歪斜，帽子歪，手杖倒地 |
| 啾啾 | 旁边 | "无辜"站立 |

**音频**:
- 台词（羊绅士）: "……我的形象。"
- 声线: 虚弱、崩溃
- 音效: "砰"（碰撞声）+ 玻璃碎裂音效

**字幕气泡**:
```
位置: 羊绅士头顶
内容: 「……我的形象。」
样式: 方形气泡，白底黑字，字体抖动效果
```

---

### 镜头 9 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_09 |
| 时长 | 2.5秒 |
| 景别 | 中景 (Medium Shot) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down view of a crochet strawberry doll that has moved only 1-2 centimeters 
from its original position. Minimal movement, emphasizing the "short legs" 
character trait. Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 莓莓 | 原位置偏移1-2cm | 几乎看不出移动 |

**音频**:
- 台词（莓莓）: "看，我也起床了。"
- 声线: 平淡
- 音效: 很慢的"咻"声

**字幕气泡**:
```
位置: 莓莓头顶
内容: 「看，我也起床了。」
样式: 圆形简约气泡，浅粉底白字
```

---

### 镜头 10 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_10 |
| 时长 | 2.0秒 |
| 景别 | 中景 (Medium Shot) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down view of a crochet bird doll turned toward the strawberry doll, 
appearing to tease or mock. Sheep doll still disheveled in background. 
Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 啾啾 | 画面右侧 | 转向莓莓方向 |
| 莓莓 | 画面左侧 | 微移动后的位置 |

**音频**:
- 台词（啾啾）: "你这一小步，走了半小时吧？"
- 声线: 笑

**字幕气泡**:
```
位置: 啾啾头顶
内容: 「你这一小步走了半小时吧？」
样式: 爆炸/不规则气泡，黄底黑字
```

---

### 镜头 11 / 12 ⭐ 核心镜头
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_11 |
| 时长 | 3.0秒 |
| 景别 | 特写 (Extreme Close-up) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Extreme close-up top-down view of a crochet strawberry doll, 
filling 2/3 of the frame. Front-facing, emphasizing the "short legs 
but every step counts" message. Warm, inspirational lighting. 
This is the key emotional moment. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 莓莓 | 画面中心，占2/3 | 正面特写 |

**音频**:
- 台词（莓莓）: "腿短，但每一步，都算数。"
- 声线: 认真、一字一顿
- BGM: 音量推大到40%，配合金句氛围

**字幕气泡**:
```
位置: 画面中心偏上
内容: 「腿短，但每一步都算数。」
样式: 加粗大字，本集金句，浅粉底白字
动画: 渐入，停留时间长
```

---

### 镜头 12 / 12
| 属性 | 值 |
|------|-----|
| 镜头编号 | SHOT_12 |
| 时长 | 3.0秒 |
| 景别 | 全景 (Wide Shot) |
| 机位 | 俯拍 90° (Top-down) |

**画面描述 (Visual Prompt)**:
```
Top-down wide shot of three crochet dolls in disarray. 
Left: sheep doll still tilted/crooked. Center: strawberry doll barely moved. 
Right: bird doll at an angle. Chaotic but end morning scene. 
Text overlay space in center. Soft morning light. Stop motion style.
```

**角色状态**:
| 角色 | 位置 | 姿态 |
|------|------|------|
| 羊绅士 | 画面左侧 | 依然歪着 |
| 莓莓 | 画面中间 | 只挪了一点点 |
| 啾啾 | 画面右侧 | 歪着角度 |

**音频**:
- BGM: 推大，轻快结尾

**字幕**:
```
位置: 画面中间
内容: 「钩织小屋的一天，开始了。」
样式: 大字，白色

位置: 下方小字
内容: 「明天会更乱。关注看下集」
样式: 小字，灰色
```

---

## 四、配音参数表

| 角色 | 声线 | 语速 | 情绪 | TTS参数建议 |
|------|------|------|------|-------------|
| 羊绅士 | 装腔作势的中年男声 | 慢，每个字咬得很清楚 | 永远在维持体面 | 成熟男声/Magnetic Male，语速0.8x |
| 莓莓 | 冷淡女声 | 很慢，没有起伏 | 永远不在乎 | 温柔女声，语速0.7x，越平越好 |
| 啾啾 | 话痨少年音 | 快，像连珠炮 | 永远很兴奋 | 少年音/活泼男声，语速1.2x |
| 旁白 | 温暖讲述感 | 正常 | 像讲绘本 | 温柔女声或自录 |

---

## 五、音效清单

| 镜头 | 音效 | 描述 |
|------|------|------|
| 01 | 闹钟滴答 | 轻柔背景 |
| 02 | "叮" | 清脆提示音 |
| 06 | "嗯？" | 轻微疑问音效 |
| 07 | "嗖" | 快速移动音效 |
| 08 | "砰" | 碰撞声 |
| 08 | 玻璃碎裂 | 形象破碎感 |
| 09 | "咻" | 很慢的移动音效 |

---

## 六、BGM参数

| 段落 | 风格 | 音量 | 备注 |
|------|------|------|------|
| 01-06 | 轻钢琴/吉他 | 20-30% | 日常氛围 |
| 07-08 | 同上 | 20-30% | 保持 |
| 09-10 | 同上 | 20-30% | 保持 |
| 11 | 同上 | 40% | 金句时刻，推大 |
| 12 | 同上 | 30-40% | 轻快结尾 |

搜索关键词: "治愈"、"轻快"、"日常"、"温馨"

---

## 七、导出参数

```json
{
  "resolution": "1080x1920",
  "aspect_ratio": "9:16",
  "fps": 30,
  "format": "mp4",
  "codec": "H.264",
  "audio": "AAC",
  "total_duration": "27s"
}
```

---

## 八、AI制作检查清单

- [ ] 12个镜头全部生成
- [ ] 角色造型一致性检查
- [ ] 俯拍角度统一
- [ ] 配音声线区分明显
- [ ] 字幕气泡样式区分角色
- [ ] 镜头11金句突出显示
- [ ] 总时长25-30秒
- [ ] 结尾有关注引导
- [ ] BGM未盖过配音
- [ ] 导出格式正确

---

**脚本版本**: v1.0  
**创建日期**: 2026-07-08  
**适用工具**: AI视频生成 / 剪映 / 定格动画制作
