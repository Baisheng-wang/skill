# Seedance 2.0 分镜脚本 - ep01 晚风回信

**剧本**：晚风回信
**总时长**：40 秒
**画幅**：竖屏 9:16（默认） / 备选 16:9 横屏
**生成引擎**：Seedance 2.0
**风格基调**：真人写实、电影感、治愈微反转
**情绪曲线**：压抑 → 释然 → 希望（U 型反转）

> **Seedance 2.0 提示词规范**
> - 单镜头 5 秒为佳（最长 10 秒），每条提示词 = 1 个镜头
> - 提示词结构：`[主体] + [动作/表演] + [环境] + [镜头语言] + [光线/色调] + [风格修饰]`
> - 优先英文提示词（Seedance 对英文响应更稳），中文释义同步给出
> - 一致性锁定：开头明确写入"Linyu"+"米白色落肩袖卫衣 + 深灰色直筒裤"以保持人物一致
> - 镜头之间使用 0.3-0.5s 静帧或跳切过渡，避免硬切痕迹

---

## 一、镜头总表

| # | 时间码 | 时长 | 段落 | 镜头类型 | 核心内容 | Seedance 提示词文件 |
|---|--------|------|------|----------|----------|---------------------|
| 01 | 00:00-00:05 | 5s | 开场·失意 | 中景→缓推 | 林屿端坐盯代码屏幕 | `shots/01-opening-sit.md` |
| 02 | 00:05-00:10 | 5s | 开场·失意 | 屏幕特写→反应 | 红色报错代码+叹气瘫靠 | `shots/02-code-error.md` |
| 03 | 00:10-00:15 | 5s | 转折·释怀 | 中景侧跟 | 起身走向窗边 | `shots/03-stand-up.md` |
| 04 | 00:15-00:20 | 5s | 转折·释怀 | 中近景正反打 | 推开窗户+手接晚风 | `shots/04-push-window.md` |
| 05 | 00:20-00:25 | 5s | 转折·释怀 | 人物背影逆光 | 剪影+晚霞+发丝飘动 | `shots/05-sunset-glow.md` |
| 06 | 00:25-00:30 | 5s | 结尾·反转 | 屏幕特写 | 黑屏→白光突现报错消失 | `shots/06-screen-recover.md` |
| 07 | 00:30-00:35 | 5s | 结尾·反转 | 中近景→缓推 | 闻声回头+表情转化 | `shots/07-look-back.md` |
| 08 | 00:35-00:40 | 5s | 结尾·反转 | 面部特写→拉远 | 清淡笑容+字幕淡入 | `shots/08-smile-endcard.md` |

**总计**：8 镜头 × 5s = 40s ✅

---

## 二、分镜提示词（Seedance 2.0 英文 + 中文释义）

### Shot 01｜00:00-00:05｜开场·失意｜中景→缓推

**英文提示词**：
```
Cinematic photorealistic medium shot, slight high angle 5 degrees, a young Chinese man named Linyu (early 20s, slender build, pale skin, soft short dark-brown hair, deep quiet eyes) sits hunched at a wooden desk in a small dim apartment. He wears an oversized off-white drop-shoulder hoodie and dark gray straight-leg sweatpants. His right hand types on a laptop keyboard in front of a screen filled with dense red error code text. The only light source is the cold bluish-white glow from the laptop screen, casting cool cyan side-light across his face, leaving the rest of the room in deep blue-gray shadow. Slow push-in toward his face, subtle handheld micro-shake. Faint late-afternoon grayish-blue sky visible through a small aluminum-framed window. Muted cold palette, low saturation, melancholic and suffocating mood. Photorealistic, cinematic, anamorphic, 9:16 vertical frame.
```

**中文释义**：
电影感写实中景，5度微俯视，中国青年林屿（视觉20出头、清瘦、白皙、柔软深棕短发、深邃安静眼神）弓背坐在小公寓木桌前，穿着米白色落肩宽松卫衣与深灰直筒长裤，右手在笔记本电脑键盘上敲击，屏幕满是密集红色报错代码。唯一光源是笔记本冷白蓝光，将他面颊打上冷青侧光，房间其余部分陷入深蓝灰阴影。镜头缓慢向面部推进，轻微手持微抖。窗框后透出灰蓝黄昏天色。冷色低饱和，压抑窒息氛围。真人写实、电影感、变形宽幅，9:16 竖屏。

**一致性锁定词**（每条提示词都保留）：
`Linyu, early 20s, slender, pale skin, soft dark-brown short hair, off-white drop-shoulder hoodie, dark gray straight sweatpants`

---

### Shot 02｜00:05-00:10｜开场·失意｜屏幕特写→反应

**英文提示词**：
```
Cinematic photorealistic close-up of a laptop screen filled with dense red error code lines, system failure messages, "ERROR", "Traceback" in monospace font. Cold bluish-white screen light, slight motion blur on text. Cut to medium close-up of Linyu (early 20s, slender, off-white drop-shoulder hoodie) staring at the screen, his expression shifting from tense focus to exhaustion. He slowly exhales a long deep sigh, eyes drifting down, shoulders dropping, then slumps back into his black office chair in defeat. Cold blue-cyan rim light, deep shadows on the rest of the room, melancholic, suffocating, low saturation. Photorealistic, cinematic, shallow depth of field, 9:16 vertical frame.
```

**中文释义**：
电影感写实笔记本屏幕特写，密集红色报错代码、系统错误信息、等宽字体的"ERROR / Traceback"。冷蓝白屏光，文字轻微动态模糊。切至林屿中近景（视觉20出头、清瘦、米白落肩卫衣）盯屏幕，表情从紧绷专注转为疲惫，长长深吸后叹气，眼神下移，肩膀塌下，整个身体泄气般瘫回黑色办公椅。冷蓝青色边缘光，房间其余部分深阴影，压抑窒息低饱和。真人写实、电影感、浅景深，9:16 竖屏。

---

### Shot 03｜00:10-00:15｜转折·释怀｜中景侧跟

**英文提示词**：
```
Cinematic photorealistic medium tracking shot, side view. Linyu (early 20s, slender, off-white drop-shoulder hoodie, dark gray straight sweatpants) slowly pushes back his black office chair, pauses for a brief hesitant moment, then stands up from the desk in a small dim apartment. He takes slow deliberate steps toward a small aluminum-framed window on the right side of the frame. Soft cool blue-gray room light still lingers, but warm pinkish-orange sunset light begins to bleed in from the window, gradually warming the edges of his silhouette. Camera follows him at waist level with gentle dolly. Muted palette transitioning from cold to warm, contemplative and healing mood. Photorealistic, cinematic, 9:16 vertical frame.
```

**中文释义**：
电影感写实中景侧跟。林屿（视觉20出头、清瘦、米白落肩卫衣、深灰直筒裤）缓慢推开黑色办公椅，犹豫片刻后从木桌前站起，在小公寓内向画面右侧的小铝合金窗缓步走去。室内冷蓝灰余光仍在，但粉橘色晚霞光从窗户开始渗入，缓缓温暖他的轮廓边缘。镜头在腰线高度用平缓 dolly 跟随。色调由冷转暖，沉思与治愈氛围。真人写实、电影感，9:16 竖屏。

---

### Shot 04｜00:15-00:20｜转折·释怀｜中近景正反打

**英文提示词**：
```
Cinematic photorealistic medium close-up, slightly low angle. Linyu (early 20s, slender, off-white drop-shoulder hoodie) stands in front of a half-open aluminum-framed window, his right hand pushing the glass panel open with quiet strength. A gentle evening breeze enters the room, his soft dark-brown hair lifts slightly in the wind. He raises his right palm slowly toward the warm breeze, fingers slightly spread, eyes half-closed, taking a long slow breath. Warm pinkish-orange sunset light pours in from outside, casting soft side-back rim light around his silhouette, the city skyline faintly visible through the window. Mood shifts from tension to quiet release. Photorealistic, cinematic, shallow depth of field, 9:16 vertical frame.
```

**中文释义**：
电影感写实中近景、略仰视。林屿（视觉20出头、清瘦、米白落肩卫衣）站在半开的铝合金窗前，右手坚定地将玻璃推开。傍晚微风涌入，深棕短发被风轻轻扬起。他缓缓将右掌伸向晚风，手指微张，半闭双眼，深深缓缓吸一口气。粉橘色晚霞暖光从窗外倾泻而入，在他的轮廓上打出柔和侧逆光，窗外隐约可见城市天际线。氛围从紧绷转向静谧释放。真人写实、电影感、浅景深，9:16 竖屏。

---

### Shot 05｜00:20-00:25｜转折·释怀｜人物背影逆光

**英文提示词**：
```
Cinematic photorealistic back view medium shot, deep silhouette framing. Linyu (early 20s, slender, off-white drop-shoulder hoodie, dark gray straight sweatpants) stands facing the open window, his back to camera, looking out at a wide pinkish-orange sunset sky. Strong warm golden-orange backlight wraps around his body and hair, creating a glowing rim light halo. His hair is softly lifted by the breeze. Room interior falls into soft warm shadow with gentle dust particles floating in the air. Through the window, a layered gradient of deep orange at the horizon fading to soft pink and pale gold above. Calm, healing, cinematic emotional climax. Photorealistic, anamorphic lens flare, 9:16 vertical frame.
```

**中文释义**：
电影感写实背影中景，强剪影构图。林屿（视觉20出头、清瘦、米白落肩卫衣、深灰直筒裤）背对镜头站在打开的窗前，望向广阔的粉橘色晚霞天空。强烈暖金橘色逆光包裹他的身体与发丝，形成发光边缘光晕。短发被微风轻轻扬起。室内陷入柔和暖影，空气中有漂浮的尘埃微粒。窗外天色呈横向渐变，地平线深橘、向上淡粉与浅金。平静、治愈、电影感情绪高点。真人写实、变形镜头光斑，9:16 竖屏。

---

### Shot 06｜00:25-00:30｜结尾·反转｜屏幕特写

**英文提示词**：
```
Cinematic photorealistic extreme close-up of a laptop screen. First, the screen is pitch black for 2 seconds, with only faint cold ambient light reflections. Then, suddenly, the screen brightens with a clean soft white light, the red error code is gone, replaced by a tidy code editor and a smooth loading progress bar. A small gentle "ding" notification pops up in the corner. The clean white screen light spills onto the surrounding desk, illuminating the edge of a ceramic water cup and scattered notebooks. Mood: quiet hope, the long wait finally answered. Photorealistic, cinematic, sharp focus, 9:16 vertical frame.
```

**中文释义**：
电影感写实笔记本屏幕极特写。先是 2 秒纯黑屏，仅有微弱冷环境光反射。随后屏幕突然以干净柔和的白光亮起，红色报错代码全部消失，替换为整洁的代码编辑器和顺畅的加载进度条。角落浮现一个轻柔的"ding"通知提示音。干净的白光溢到周围桌面，照亮陶瓷水杯边缘与散落的笔记本。氛围：静谧希望，长久的等待终有回响。真人写实、电影感、锐利对焦，9:16 竖屏。

---

### Shot 07｜00:30-00:35｜结尾·反转｜中近景→缓推

**英文提示词**：
```
Cinematic photorealistic medium close-up, eye level. Linyu (early 20s, slender, off-white drop-shoulder hoodie) stands by the window, back still partly toward camera, he turns his head slowly in response to a soft notification sound. His expression shifts from quiet melancholy to gentle surprise, eyes widening briefly, blinking once as if confirming, then softening into a faint warm smile. The clean white light from the laptop screen reflects softly on his face, mixed with the residual warm pinkish sunset glow from the window. Hair still slightly lifted by breeze. Photorealistic, cinematic, shallow depth of field, 9:16 vertical frame.
```

**中文释义**：
电影感写实中近景，平视。林屿（视觉20出头、清瘦、米白落肩卫衣）站在窗边，背部仍半对镜头，听到轻柔通知声后缓缓转头。表情从静谧忧郁转向温柔惊讶，眼睛微微睁大，眨一次眼确认，然后柔化成淡淡温暖微笑。笔记本的干净白光柔和映在脸上，与窗外粉橘晚霞余光交融。发丝仍被微风轻扬。真人写实、电影感、浅景深，9:16 竖屏。

---

### Shot 08｜00:35-00:40｜结尾·反转｜面部特写→拉远

**英文提示词**：
```
Cinematic photorealistic close-up, gentle pull-back. Linyu (early 20s, slender, pale skin, soft dark-brown short hair) faces the camera with a faint serene smile, his eyes regaining a quiet inner light. Soft white screen light from his left, warm pinkish sunset glow from his right, blending into a gentle luminous skin tone. Around him, the small room is now softly lit, the wooden desk, the half-open window, the orange-pink sky outside all in soft focus. The Chinese subtitle "慢慢来，一切皆有回响" fades in slowly below his face in a delicate calligraphic font, then fades out as the frame holds. Mood: peaceful, hopeful, quietly reborn. Photorealistic, cinematic, 9:16 vertical frame.
```

**中文释义**：
电影感写实面部特写，缓慢拉远。林屿（视觉20出头、清瘦、白皙、柔软深棕短发）面朝镜头带着一抹淡然宁静的笑容，眼神重获静谧内在光芒。左侧冷白屏光、右侧粉橘晚霞余光交融，形成柔和明亮肤调。周围小公寓被柔光笼罩：木桌、半开的窗、窗外橘粉天空均处于柔焦。中文字幕"慢慢来，一切皆有回响"以细腻书法体在他面下方缓缓淡入，再缓缓淡出，画面定格。氛围：平静、希望、安静重生。真人写实、电影感，9:16 竖屏。

---

## 三、关键一致性锁定

为避免 Seedance 2.0 在不同镜头之间出现角色漂移，**每条英文提示词必须保留**以下核心词组：

```
Linyu, early 20s, slender build, pale skin,
soft dark-brown short hair, deep quiet eyes,
off-white drop-shoulder hoodie, dark gray straight sweatpants
```

建议在每条提示词中**位置固定**（建议紧跟在主体描述的逗号后），并在多次重生成时通过 `reference_image` 锁脸（如果 Seedance 2.0 该版本支持 IP 一致性图）。

---

## 四、转场与节奏建议

| 段落过渡 | 时机 | 处理方式 |
|----------|------|----------|
| Shot01 → Shot02 | 5s 处 | 跳切至屏幕特写，0.2s 静帧缓冲 |
| Shot02 → Shot03 | 10s 处 | 人物深吸气触发起身，cut on action |
| Shot03 → Shot04 | 15s 处 | 缓推至中近景，0.3s 黑场过渡 |
| Shot04 → Shot05 | 20s 处 | 平滑横移转身后景别保持，cut on gaze |
| Shot05 → Shot06 | 25s 处 | 渐黑 0.5s → 屏幕黑屏 2s |
| Shot06 → Shot07 | 30s 处 | 屏幕白光与人物面部光线同色温，cut on light |
| Shot07 → Shot08 | 35s 处 | 缓推至特写，无缝连接 |

**音乐配乐**（建议同步生成）：
- 00-10s：钢琴单音 + 电子环境噪声，节奏稀疏
- 10-25s：温暖弦乐铺底，缓慢渐入
- 25-30s：环境音几乎静默，强化屏幕白光瞬间的"呼吸感"
- 30-40s：钢琴 + 弦乐推至柔和高潮，结尾淡出

---

## 五、生成顺序建议

1. 先生成 **Shot 01 + Shot 05 + Shot 08** 这三个"标杆镜头"（分别代表开场压抑/转折逆光/结尾微笑）
2. 用标杆镜头筛选"通过"的视觉风格基调
3. 再批量生成剩余 5 个镜头
4. 全部生成后，在剪辑软件（剪映 / Premiere / CapCut Pro）按时间码拼装
5. 加字幕（SRT：00:23-00:25 旁白、00:36-00:40 结尾字幕）、配乐、调色

---

## 六、可选增强提示词（v2.0 制作参考）

如未来升级到更高一致性版本，可加入：

- `--style "cinematic, photorealistic, anamorphic, 35mm film grain"` 风格锁定
- `--camera "ARRI Alexa Mini LF, Cooke S4/i 50mm"` 摄影机与镜头语言
- `--color "Kodak 2383 print film"` 胶片色彩
- `--reference_image "./assets/character-prompts.md 林屿图A"` 一致性参考图

---

**交付物清单**：
- ✅ 8 个镜头英文 Seedance 2.0 提示词 + 中文释义
- ✅ 镜头总表 + 转场节奏表
- ✅ 一致性锁定词组
- ✅ 音乐与字幕节点建议
- ✅ 生成顺序与质检流程

**下一步**：
- 用户可使用 `~prompt ep01` 触发自动生成；或直接复制英文提示词逐条投入 Seedance 2.0
- 生成后建议用 `outputs/ep01/03-qc-checklist.md` 进行一致性 / 节奏 / 字幕三维度质检
