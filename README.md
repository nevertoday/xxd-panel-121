<div align="center">

# XXD Panel 121｜生活涂鸦编排志

把日常照片里的一点情绪，变成留白充足、图文关系聪明的生活方式插画。

<a href="README.md">简体中文</a> · <a href="README.en.md">English</a> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

## 样张展示

以下样张均来自不同的原始参考图，由 Panel 121 独立单轮生成，并已清理 AI 元数据。横版严格为左侧原图、右侧设计，各占 50%；竖版严格为上方原图、下方设计，各占 50%。

**16:9 横版 · 左右 50:50**

| sample-05 | sample-06 |
|---|---|
| ![sample-05](assets/examples/sample-05.png) | ![sample-06](assets/examples/sample-06.png) |
| ![sample-07](assets/examples/sample-07.png) | ![sample-08](assets/examples/sample-08.png) |

**3:4 竖版 · 上下 50:50**

| sample-09 | sample-10 |
|---|---|
| ![sample-09](assets/examples/sample-09.png) | ![sample-10](assets/examples/sample-10.png) |
| ![sample-11](assets/examples/sample-11.png) | ![sample-12](assets/examples/sample-12.png) |

本组样张采用贴合各自原图的简短英文智能文案。

## 适用场景与解决的问题

一张日常照片可能有动人的姿态或关系，却被普通构图和杂乱背景分散了注意力。**Panel 121** 保留照片的真实身份，重新提取最有识别力的主体，用松弛的马克笔式涂鸦、经过编辑的手写文字和超大量留白，让生活片段成为一张成熟的作品。

### 适合什么场景

- 人物、日常物件、生活场景需要转成独立杂志或生活方式 editorial illustration。
- 希望保留主体轮廓、姿态和叙事关系，但主动删除绝大多数背景与次要对象。
- 喜欢稚拙手绘的轻松感，同时在意图形、文字和空白的成熟编排。
- 需要上下、左右、纯设计、多比例、壁纸或目录批量等一致交付方式。

### 它解决什么问题

- 普通照片也能通过删减、重组、裁切和尺度变化建立新的视觉重点。
- 图文先共享隐形网格、视觉轴线和阅读路径，避免“上面一句话、下面一个人物”。
- 实体图形只占较小比例，留白承担距离、停顿和呼吸，不用随机小图标填空。
- 对比图严格两个 50:50 区域，直接从本次原图生成，避免第三带与二次风格化。

## 原始提示词 · 五种语言

[简体中文](references/original-prompt/zh-CN.md) · [English](references/original-prompt/en.md) · [日本語](references/original-prompt/ja.md) · [한국어](references/original-prompt/ko.md) · [العربية](references/original-prompt/ar.md)

中文文件逐字保留用户原始提示词，是运行时唯一的创作与审美权威。其余四语为完整、忠实的阅读译文，不参与改写生成指令。

**风格关键词：** 生活方式稚拙插画 · 马克笔/蜡笔/油画棒质感 · 隐形网格 · 图文整体编排 · 轻巧自然手写 · 源图限定配色 · 超大量留白

## 快速判断：Panel 121 适合你吗？

| 你关心的事 | Panel 121 的处理 |
|---|---|
| 照片构图普通怎么办？ | 重新导演主体位置、裁切和尺度，保留最有识别力的关系。 |
| 涂鸦会不会显得幼稚？ | 稚拙的画配成熟构图，避免儿童手帐、廉价卡通与模板。 |
| 文字是否固定居中？ | 根据轮廓、动作、肩线及负空间安排文字，形成不对称呼应。 |
| 能否适配多种交付？ | 支持四种模式、常见比例、准确像素与独立目录批量。 |

## 它如何把照片变成成品

```text
理解主体与叙事关系 → 删除多数背景 → 简化为松弛马克笔式形象 → 重组尺度与裁切 → 建立隐形网格与阅读路径 → 编排少量手写文案 → 用超大量留白完成节奏
```

## 成品中最容易识别的特点

- 保留真实照片的主体身份、结构、姿态、自然光影和色彩氛围，仅轻微调色。
- 图形简化、符号化，线条轻微抖动、断续、不完全规整，允许越线、露白和手工误差。
- 不追求完整透视或精细写实，主动删除背景与无关对象。
- 主体小比例、偏心、贴边、悬置或局部裁切，空白参与正负形和距离设计。
- 图文整体编排；手写字体轻巧自然，略有字宽和笔压变化，字距行距仍受编辑控制。
- 柔和明快的限定色系来自原图，暖白或极浅综合色形成大面积呼吸空间。

## 四种输出模式

- `top-bottom`：整张画布只有上下两个全宽区域，现实照片在上、设计在下，严格各占 50%。
- `left-right`：整张画布只有左右两个全高区域，现实照片在左、设计在右，严格各占 50%，不会旋转成上下结构。
- `design-only`：整张画布只呈现 Panel 121 的设计转译，照片只作为不可见参考。
- `wallpaper-pack`：按手机、iPad、桌面和手表分别生成完整设计壁纸，可选 `linked` 连贯套装或 `independent` 四张独立。

支持多选模式与比例（`1:1`、`3:4`、`4:3`、`4:5`、`5:4`、`2:3`、`3:2`、`9:16`、`16:9`、`21:9`、`5:7`、`7:5` 或准确像素），以及模型生成文字、准确文字和无文字。传入目录会递归扫描图片，每张源图独立处理，共用一次交付设置；最终 PNG 平铺放入一个新任务目录。

## 开始使用

```bash
git clone https://github.com/nevertoday/xxd-panel-121.git
npx skills add https://github.com/nevertoday/xxd-panel-121 --skill xxd-panel-121
```

安装后重新启动 Agent 会话，然后调用 `$xxd-panel-121`。也可以按需追加 `--global --agent codex --yes` 做用户级安装。

常用调用示例：

```text
/xxd-panel-121 photo.jpg --mode top-bottom --size 3:4 --text prompt --locale zh-CN
/xxd-panel-121 photo.jpg --mode left-right --size 16:9 --text prompt --locale en-US
/xxd-panel-121 photo.jpg --mode design-only --size 9:16 --text none
/xxd-panel-121 ./photos --mode design-only --size auto,3:4 --text prompt --locale ja-JP
```

完整运行契约见 [SKILL.md](SKILL.md)；运行适配器见 [英文](references/xxd-panel-121-prompt.en.md) 与 [中文](references/xxd-panel-121-prompt.zh-CN.md)。

## 许可证

本项目（包括 Skill、提示词、脚本、文档及随附样张）采用 **PolyForm Noncommercial License 1.0.0**。完整法律条文请见 [LICENSE](LICENSE)，官方页面见 <https://polyformproject.org/licenses/noncommercial/1.0.0>。

许可范围说明：

- 个人可以用于学习、研究、实验、测试、兴趣项目和私人娱乐；慈善机构、教育机构、公共研究/安全/卫生机构、环保组织及政府机构也可以使用。
- 在**非商业目的**下，你可以使用、复制、修改、制作衍生作品并分享；分享时必须同时提供本许可证（或上面的链接）以及作者提供的所有 `Required Notice:` 声明。
- 不允许用于商业产品或服务、收费交付、出售访问权或许可，或任何预期会带来商业应用的用途。需要商业使用时，请先向版权方另行取得书面许可。
- 本协议只授予其中明确写出的著作权许可和有限的专利许可，不授予商标、品牌名称或其他未明确授予的权利，也不能把你的许可再转授给他人。
- 如果收到书面违约通知，须在 32 天内纠正并采取实际补救措施，否则许可会立即终止；就专利侵权提出书面主张也会终止专利许可。
- 内容按“现状”提供，在法律允许的范围内不作任何担保，使用风险和可能的损失由使用者自行承担。
