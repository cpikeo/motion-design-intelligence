---
name: motion-design-intelligence
description: 动态设计与动效规格技能。从概念、叙事、静态构图、运动语法，到 Web 交互、实时 3D、影片与 Showreel 的规格与验收方案。规定事实与证据约束、减少动态替代、驱动模型唯一写入者、离线制作适配与性能测量。本技能只产出规格与验收方案，不声称未经执行的测试结果。
---

# Motion Design Intelligence

动态设计不是给静态画面附加效果。原创不来自效果的重新组合，而来自对内容、任务与观众的具体观察。

> 状态：本版为文本规格。所有验收项为 `not_tested`，未在任何浏览器、真机、GPU 或辅助技术环境中运行。

## 目录与快速路由

| 任务 | 优先阅读 | 必需交付 |
|---|---|---|
| 新项目立项、概念 | 第 0、1、3 节 | 概念简报、Tempo Map 草案 |
| 微交互（L1） | 第 2、9、10、11 节 | L1 Spec |
| 滚动叙事与 Web 页面（L2） | 5.2、5.3、9.3、10、12 节 | L2 Spec 与验收方案 |
| 实时 3D | 第 7、8 节 | Look Development 记录与性能预算 |
| 影片与 Showreel（L3） | 5.4、6 节（含 6.7） | 分镜、Animatic、QC 清单 |
| 离线制作 | 6.4、15 节 | 6.4 适配表对应交付 |
| 发布前审查 | 13 节、附录 A | 发布闸门记录 |

---

## 第 0 节 范围与立场

### 0.1 做什么

1. 将动效需求转为可追溯的概念与运动语法。
2. 为 Web、3D、影片与离线制作提供可执行规格。
3. 定义驱动模型、连续性、减少动态替代与验收方法。
4. 标注证据等级，区分事实、推断与假设。
5. 给出可直接实现的 Tempo Map、字段模板与样例。

### 0.2 不做什么

1. 不替代用户研究、法务合规或正式无障碍认证。
2. 不以附录中的示例数值作为发布依据。
3. 不声称任何未执行测试的结果。

### 0.3 核心立场

目的先于效果；内容先于隐喻；静态构图先于动态；证据先于结论；静止本身是设计决策。

---

## 第 1 节 仲裁与闸门

### 1.1 仲裁顺序

冲突时，级别高者优先：

1. 安全、事实、无障碍与用户控制
2. 用户任务与内容准确性
3. 静态构图与可读性
4. 原创概念与叙事意图
5. 运动品质
6. 技术可行性
7. 装饰与炫技

### 1.2 非补偿闸门

任一闸门不通过，方案不得发布。动效质量不能补偿未通过的闸门。

- **G1 事实**：事实错误不得由动效质量补偿。
- **G2 任务**：动效不得阻碍用户完成任务。
- **G3 静态**：静态状态必须可读，层级成立。
- **G4 安全**：不得产生超过 WCAG 2.3.1 阈值的闪烁。
- **G5 降级**：减少动态与不支持环境下，内容必须完整。

### 1.3 删除三问

每个动效元素保留前须回答：

1. **价值**：删除后，用户失去什么信息或操作？
2. **必要性**：去掉后，层级与阅读顺序是否仍成立？
3. **稳定性**：中断、重复触发与反向后，行为是否仍可预测？

---

## 第 2 节 分级与输入

### 2.1 分级

- **L1 微交互**：单一控件或状态，紧凑规格。
- **L2 页面或组件区块**：含多个动作与驱动关系。
- **L3 完整叙事段或影片**：含 Tempo Map 与分镜。

### 2.2 输入与假设

输入不足时列出假设。每个假设标注 `E3 示例假设` 并写明确认内容。

### 2.3 无法运行时的处理

1. 交付可复现步骤与录屏脚本。录屏不得替代运行验证。
2. 验收状态标 `not_tested`；外部阻塞标 `blocked` 并写明原因。
3. 不得以描述性文字代替测试结果。

---

## 第 3 节 研究与概念

### 3.1 诊断

**诊断五问**：用户要完成什么任务；哪些内容必须被理解；哪些信息不得被动效遮挡；去掉运动会发生什么；语义或情绪的峰值位于何处。

**首要意图（五选一）**：`functional` | `explanatory` | `expressive` | `narrative` | `atmospheric`

### 3.2 事实底稿

- **E1**：来源可核验的事实，附来源。
- **E2**：由 E1 推断的结论，写明推理过程。
- **E3**：示例假设或待确认信息，标注并写明确认责任人。

### 3.3 研究方法六步

1. **观察**：记录内容与行为，不预设结论。
2. **张力**：找出内容中的对立或依赖关系。
3. **抽象**：提取结构，而非外观。
4. **感知转译**：将结构转为可感知的运动属性。
5. **隐喻验证**：隐喻须同时被静态画面与运动支撑。
6. **提纯**：删除不被内容支持的部分。

**三层级**：Concept（为何）、Metaphor（如何被看见）、Motif（跨段落重复的元素）。

### 3.3.1 研究角度表

研究对象仅在本表登记核验状态，第 15 节不重复。表格只记录研究问题，不补充对对象的描述。

| 对象 | 研究问题 | 待核验的结构问题 | 明确不借鉴 | 核验状态 | 核验日期 |
|---|---|---|---|---|---|
| GetLayers | 层级切换依据是什么？ | 是否依赖内容结构而非装饰？（待核验） | 视觉外观、版式、素材 | 未核验 | — |
| Mobbin | 界面状态变化如何组织？ | 状态转换分类能否用于 9.1？（待核验） | 截图、界面样式、收录内容 | 未核验 | — |
| CTA Gallery | 行动按钮与周边层级如何关联？ | 行动暗示依赖静态对比还是运动？（待核验） | 按钮样式、文案、布局 | 未核验 | — |
| Grainient | 参数如何组织？ | 纹理变化能否以驱动模型表达？（待核验） | 着色器效果、配色、视觉风格 | 未核验 | — |
| ReelFolio | 节奏如何组织？ | Tempo Map 段落划分是否与之一致？（待核验） | 作品、版式、影片内容 | 未核验 | — |

**使用规则**：

1. **查阅时机**：仅在完整项目方向比较（3.6）时查阅。微交互不需要。
2. **记录字段**：对象名、网址、访问日期、核验人、核验状态、许可状态。
3. **核验状态**：仅限 `未核验` 或 `已核验`。核验完成后才可填日期。
4. **未核验前**：正文以“待核验”标注，不得引用其内容、质量或结论，不得复制外观。
5. 表格只记录研究问题。

### 3.4 概念简报

```yaml
primary_intent:   # functional | explanatory | expressive | narrative | atmospheric
audience:
facts:            # E1/E2/E3 编号
proposition:      # 一句话主张
metaphor:
motifs:
exclusions:
evidence_level:   # R | S | D | U
```

### 3.5 概念闸门

五项全部通过，概念方可进入制作：

1. **可追溯**：每个原则可回溯到 E1 或 E2。
2. **必要性**：去掉后，信息或任务受损。
3. **替换测试**：换成其他常见效果后，概念是否失效。
4. **剥离测试**：去掉隐喻后，内容是否仍成立。
5. **延展测试**：概念至少能应用于三种内容关系（顺序、并列、因果）。

### 3.6 方向比较

完整项目提出 2–3 个方向，比较任务支持、事实一致、静态可读、实现成本、无障碍风险。微交互不需要。

### 3.7 抽象词可检查化

抽象词不得直接作为规格。须改写为可检查指标。

| 抽象词 | 改写为 | 示例检查 |
|---|---|---|
| 高级 | 留白比例、字体层级数、同屏 Lead 上限 | Lead ≤ 1 |
| 电影感 | 每镜运动动机、焦距或景深区间 | 每镜有动机字段 |
| 科技感 | 指定色彩、网格、数据来源 | 数据画面标注来源 |
| 沉浸 | Hold 时长与焦点管理 | 焦点不被劫持 |
| 极简 | 删除清单与 Still 占比 | Still 占比达设定值 |
| 有温度 | 材质、细节或语音特征；不得虚构品牌故事 | 每项可回溯到 E1 |
| 有力量 | 峰值位置、对比度、运动幅度 | Hero Moment 对比值可测 |

### 3.8 静态与动态对照

静态与动态的对照仅为 **D 级证据**，可作设计讨论依据，不得作为效果结论。

---

## 第 4 节 运动语言

### 4.1 Motion DNA 八维

每维以 1–5 标注并附一句具体含义：Energy（能量）、Weight（重量）、Precision（精确）、Temperature（温度）、Elasticity（弹性）、Continuity（连续）、Spatiality（空间）、Stillness（静止）。

### 4.2 行为层级

以下分类为设计判断（D 级）。

- **Signature**：标志性行为，每项目不超过 2 个。
- **Narrative**：承载内容顺序。
- **Functional**：提供状态反馈。
- **Ambient**：环境行为，可暂停，不承载信息。

### 4.3 运动语法

每条运动须写成：`Subject + Trigger + Intent + Change + Timing + Relation + State + Stop`（对象、触发、意图、变化、时序、关系、状态、停止条件）。

### 4.4 Motion Tokens

**Role 类别**：微反馈、小状态、空间转换、叙事段落、强调、环境、退出、减少动态替代。

**参考起点（非规范）**：微反馈 80–200 ms；小状态 150–300 ms；空间转换 250–500 ms；叙事段落 400–900 ms。

### 4.5 连续性（唯一真值）

**位置与速度**：C0 位置连续；C1 速度连续；C2 加速度连续。

**几何**：G0、G1、G2 为几何连续。G1 不等于 C1。

**链式法则**（参数 u 驱动位置 p）：

- 速度：dp/dt = (dp/du)(du/dt)
- 加速度：d²p/dt² = (d²p/du²)(du/dt)² + (dp/du)(d²u/dt²)

仅比较 dp/du 不能推断物理速度连续。

**常用取向**：

- UI 切换：C0。
- 拖拽释放：C0，必要时 C1。
- 摄影机长镜头：速度层面通常 C1（D 级经验判断，待动画测量验证），几何按需 G2。
- 滚动驱动：不得声称输入轨迹连续。

### 4.6 物理模式

- **Physical**：遵循惯性、阻尼，须说明参数来源。
- **Stylized**：允许偏离物理，须声明偏离内容。
- **Abstract**：不模拟物理。

---

## 第 5 节 编排与镜头

### 5.1 注意力预算

- **Lead**：主导动作，同一时间窗口最多 1 个。
- **Support**：辅助动作，可多个，不得与 Lead 竞争。
- **Ambient**：环境动作，不承载信息。
- **Still**：静止区域，用于留白与停顿。

### 5.2 Tempo Map

**结构**：`Establish → Anticipate（可选）→ Act → Transfer → Reveal → Hold → Resolve`。Hold 为必需段。

**字段模板**（附录 C.4 只列取值，字段含义以此为准）：

```yaml
segment:
window:            # 页面进度或时间区间
information:       # 本段须被理解的内容
lead:
support:
ambient:
still:
intensity_cap:     # 低 | 中 | 高（D 级，项目内定义）
concurrency_max:   # Lead 与 Support 合计；Ambient 不计
trigger:
interruptible:     # true | false
hold_ms:
fallback:
evidence:          # 证据等级与来源
```

### 5.3 编排规则

1. 排序依据：因果序 > 阅读序 > 空间序 > 重要度。
2. 用户反馈不得等待自动时间轴。
3. 焦点先建立新的，再退出旧的。
4. 匹配剪辑不得用 morph 暗示实体连续。

### 5.4 镜头

- **Shot Motivation**：每个镜头运动须回答“为何此时此地移动”。
- **连续性检查清单**：轴线、屏幕方向、视线、运动方向。
- **FOV**：`FOV = 2 × arctan(d / (2f))`，结果为弧度，换算为度乘 180/π。
- **区分**：Dolly（移动）、Zoom（焦距变化）、Dolly Zoom（同时发生）。
- **CSS scale 不是焦距变化**，不得以此模拟变焦。

---

## 第 6 节 叙事与影片

### 6.1 叙事六段

Opening、Establishing、Development、Hero Moment、Breathing Space、Resolution。

### 6.2 分镜字段

镜号、时长、主体、景别、视点、镜头动机、运动、转场、音频提示、字幕与文字、Hold 时长、减少动态替代画面。

### 6.3 声音与触觉

- **身份**：声音是否属于品牌识别，须有依据。
- **同步**：列出音画同步点。
- **控制**：可静音、可关闭触觉反馈。
- **克制**：同一窗口声音事件数不超过 Lead 数。

### 6.4 离线制作适配表（唯一必需来源）

| 阶段 | 必须检查 | 交付 |
|---|---|---|
| 概念与 Art Direction Sheet | 通过概念闸门（3.5） | 概念简报、Sheet（7.5） |
| 分镜与 Animatic | 用时长验证节奏 | 分镜表、Animatic |
| Blocking 与动画 | 轴线、屏幕方向、焦点交接 | 动画文件、检查记录 |
| 材质、灯光与渲染 | 按 7.4 校准 | Look Development 记录 |
| 合成与剪辑 | 首尾帧、文字安全区 | 合成工程、剪辑版本 |
| 色彩与声音 | 色彩空间、响度、音画同步 | 检查记录 |
| QC 与母版 | 编码兼容、字幕、版本命名 | QC 清单、母版文件 |

**提前锁定**：画幅、分辨率、帧率、时间码、色彩管理、Alpha 约定、声音采样率、响度标准。

### 6.5 真实性

1. 影片中的产品、数据、客户、奖项须有来源。
2. 不得伪造客户名称、奖项、用户数量或作品归属。
3. 数据画面须标注来源。

### 6.6 影片验收七项

1. Tempo Map 与分镜一致。
2. 每个镜头有动机。
3. 文字位于安全区内。
4. 减少动态替代画面可用。
5. 字幕与音频可用。
6. 色彩管理与母版参数已记录。
7. QC 清单已执行；未执行标 `not_tested`。

Showreel 另须通过 6.7。

### 6.7 Showreel

Showreel 是作品集合的导览影片，不是单一叙事段。本节与 6.1–6.6 同时适用。

1. **结构**：每作品一段，Tempo Map 按作品划分（5.2）。作品间过渡不得暗示归属或合作关系（6.5）。
2. **可跳转**：每段有时间码章节标记且可直接跳转。章节标题同时以画面文字呈现。
3. **无声完整**：静音播放时，每段项目名、年份与角色以文字呈现，不依赖旁白或音乐提示。
4. **循环片段**：循环点首尾帧在主体位置、颜色与字幕状态上一致；不得含闪烁（11.3 高风险）；分镜标注 `loop_in` 与 `loop_out`。
5. **减少动态**：提供每段一张静态代表画面，以及不含运动的版本。章节导航可由键盘操作。
6. **规格**：画幅、总时长与各段时长、分辨率、帧率、色彩管理、字幕格式与响度，记入 6.4 的提前锁定项。
7. **来源与署名**：作品画面、客户名称、奖项与数据须有 E1 来源；未经许可不得使用。无法核验的内容标 E3，不得用于发布。

**验收（均 `not_tested`）**：SR-A1 章节可跳转且键盘可操作；SR-A2 静音播放时每段信息完整可读；SR-A3 循环首尾帧逐帧比对一致；SR-A4 减少动态替代画面可用；SR-A5 每段来源已登记，未核验内容已标 E3。

---

## 第 7 节 构图、排印与 3D 外观

### 7.1 静态构图先行

依次检查，每项须有通过条件：

1. **缩略图**：小尺寸下层级成立。
2. **灰度**：去色后对比与层级可辨。
3. **眯眼**：模糊后主次可辨。
4. **遮文字**：去掉文字后图像仍表达主要结构。
5. **遮图**：去掉图像后文字层级仍成立。

### 7.2 关键帧类型

起始帧、主要中间帧、焦点交接帧、可中断帧、反向帧、终态帧。

0/25/50/75/100% 仅为抽样索引，不是关键帧类型。

### 7.3 排印

1. **CJK**：遵循 W3C clreq 的断行、避头尾与悬挂标点（R-23，待核验）。
2. **RTL**：明确方向与镜像规则。
3. **竖排**：使用 `writing-mode`，检查动画方向。
4. **拆分文字**：视觉副本设 `aria-hidden`，保证屏幕阅读器只读一次。

### 7.4 Look Development（唯一真值）

**五步流程**：

1. 定义参考对象与用途。
2. 设定基础材质参数。
3. 建立光照：Key、Fill、Rim/Back、Environment、Volumetric。
4. 校验 sRGB 与线性空间。
5. 动态色彩取最差帧验证。

**参数要点**（依据 R-13 Khronos glTF 2.0 PBR Metallic-Roughness，待核验；以项目所用版本的规范原文为准）：

- **Metalness**：着色模型参数，不是导电率，也不是“金属百分比”。
- **Base color**：金属上为反射色，非金属上为漫反射色。
- **颜色空间**：base color 按 sRGB 解码，metallic-roughness 按线性读取。
- **法线扰动**：说明强度与来源。
- **Roughness**：控制高光扩散。
- **Subsurface、Anisotropy、Transmission**：仅在需要时启用并说明理由。

### 7.5 Art Direction Sheet（十三字段）

concept, composition, hierarchy, camera, typography, material_lighting, motion_character, signature_moments, stillness, exclusions, responsive, reduced_motion, references

---

## 第 8 节 实时 3D

### 8.1 何时使用 3D

满足其一即可考虑：需要真实空间关系；用户需实时操控视角；三维结构是完成任务所需信息；静态图像无法表达必要深度。

### 8.2 技术路线

- WebGL 2 + GLSL
- WebGPURenderer + TSL / Node Material
- CSS、Canvas 或预渲染

**迁移边界（待核验，R-07 至 R-12）**：WebGPU 不是 WebGL 的改名；TSL 不是 GLSL 的改名；回退路径与主路径不等价，须分别测试。

**采用闸门五项**：目标浏览器支持（待核验）、回退路径、性能预算、团队维护能力、许可与依赖。

### 8.3 生命周期

Scene（创建与销毁）、State/Motion（状态与动画分离）、Material（资源释放）、Render（渲染循环）、Lifecycle（离开与卸载清理）。

**上下文事件**：WebGL 用 `webglcontextlost` 与 `webglcontextrestored`；WebGPU 用 `device.lost`。

### 8.4 粒子与噪声

1. 设定粒子数上限与噪声频率上限。
2. 粒子不得承载唯一信息。
3. 减少动态下改为静止画面。

### 8.5 五类预算

示例数值统一登记于附录 D（D-G01 至 D-G04），状态为待确认。

| 类别 | 预算指标 | 示例值 | 测量方法 |
|---|---|---|---|
| 画面 | 同屏可交互 3D 对象数 | ≤ 1（D-G01） | 场景统计 |
| 像素 | 渲染像素比上限 | 2.0（D-G02） | 渲染设置 |
| 运动 | 同时运动对象数 | ≤ 3（D-G03） | 运动统计 |
| 带宽 | 单个 3D 资源（压缩后） | ≤ 2 MB（D-G04） | 网络面板 |
| 感知 | Lead 数上限 | 1（沿用 5.1） | 规则检查，无需确认 |

---

## 第 9 节 交互与状态

### 9.1 状态模型

`idle → hover/focus → pressed → active → loading → success/error → disabled`

### 9.2 微交互规则

1. 每个状态变化须有可见反馈。
2. 反馈不得仅依赖颜色。
3. 重复触发按 `repeat_policy` 处理。
4. 焦点状态须可见。

### 9.3 滚动叙事

1. 滚动映射须声明时间映射函数（如 TIME-xx）。
2. 不得劫持滚动。
3. 减少动态下静态内容可读。
4. 移动端须提供替代方案。

### 9.4 CTA 理解路径

以下五步为设计判断（D 级）：视觉焦点 → 信息理解 → 行动暗示 → 操作反馈 → 结果确认。不得作为转化结论的依据。

---

## 第 10 节 规格与驱动模型

### 10.1 三层结构

**Intent**（意图）、**Behavior**（行为）、**Binding**（绑定）。

### 10.2 行为

**核心行为（六种）**：fade、translate、scale、rotate、reveal、morph。

**扩展族**：camera、path、type、deform、material、simulation、time、data、audio_haptic。扩展行为须使用 `C-xx` 编号契约。

### 10.3 驱动模型（唯一真值）

**字段**：

- `update_model`：`event` | `state-transition` | `continuous`
- `value_source`：`none` | `scroll-progress` | `pointer` | 其他具名来源
- `timebase`、`mapping`
- `ownership`（target、property、primary_writer、mode）
- `precedence`、`conflict_resolution`、`handoff`

**规则**：

1. 同一属性只能有一个 `primary_writer`。出现两个候选写入者，规格不通过。
2. `primary_writer` 须与 10.7 一致。
3. 减少动态由 `reduced_motion_writer` 执行，默认等于 `primary_writer`。若不同，须声明两者互斥、不得同时活动。
4. 滚动来源统一记入 `value_source`，不得记为 `update_model` 的取值。

### 10.4 Spec 字段表

| 字段 | 含义 | L1 | L2 | L3 |
|---|---|---|---|---|
| id | 唯一编号 | 必需 | 必需 | 必需 |
| role | 行为层级（4.2） | 必需 | 必需 | 必需 |
| attention | 注意力角色（5.1） | 可选 | 可选 | 必需 |
| intent | 意图，可回溯到概念 | 必需 | 必需 | 必需 |
| target | 元素与属性 | 必需 | 必需 | 必需 |
| trigger | 触发与重复策略 | 必需 | 必需 | 必需 |
| driver | 驱动模型（10.3） | 必需 | 必需 | 必需 |
| behavior | 行为与参数（10.2） | 必需 | 必需 | 必需 |
| space | 参考系、锚点、边界 | 可选 | 必需 | 必需 |
| time | 时长、缓动、时间基准 | 必需 | 必需 | 必需 |
| reduced_motion | 减少动态替代 | 必需 | 必需 | 必需 |
| reduced_motion_writer | 执行减少动态的写入者 | 可选 | 必需 | 必需 |
| responsive | 响应式规则 | 可选 | 必需 | 必需 |
| binding | mechanism、ownership、primary_writer、mode | 必需 | 必需 | 必需 |
| lifecycle | 挂载、暂停、卸载、清理 | 可选 | 必需 | 必需 |
| fallback | 降级替代 | 必需 | 必需 | 必需 |
| acceptance | 验收条目（10.5） | ≥1 | ≥2 | 每个动作 ≥1 |
| evidence | 证据等级与来源 | 必需 | 必需 | 必需 |

L3 另须包含 Tempo Map（5.2）与分镜字段（6.2）。

### 10.5 验收三要素

每条验收须同时满足：**可观察**（有明确观察对象）、**可复现**（步骤与环境可重复）、**可判定**（明确的通过/失败阈值）。

| 不可判定 | 可判定 |
|---|---|
| “无残留动画” | “200 ms 间隔连续点击 5 次后，`getAnimations()` 返回空数组” |
| “误差不超过约定阈值” | “相对误差 ≤ 0.5%（示例阈值，待确认）” |

### 10.6 状态聚合

取值：`not_tested` | `blocked` | `passed` | `failed`

1. 任一为 `failed`，整体 `failed`。
2. 无 `failed` 但有 `blocked`，整体 `blocked`。
3. 全部 `passed` 且均有证据，整体 `passed`。
4. 其余为 `not_tested`。

### 10.7 写入者期望值（跨附录唯一来源）

附录 B、C 的验收引用本表，不另列。

| 动作 | 目标与属性 | GSAP 活动补间 | CSS/WAAPI 动画 | 直接样式赋值 | 期望唯一写入者 |
|---|---|---|---|---|---|
| B M-01 | `.product-container` 的 `transform` | 0 | 1 | 0 | `state-transition:product` |
| C M-02 | `.step2-image` 的 `clip-path` | 1 | 0 | 0 | `scrollTrigger:section-2` |
| C M-03 | `.step2-caption` 的 `opacity`、`transform` | 1 | 0 | 0 | `scrollTrigger:section-2-caption` |
| C M-04 | `.step-index-2__halo` 的 `opacity` | 0 | 1 | 0 | `ambient:step-index-2` |

**判定规则**：

1. 任一计数偏离上表，判定 `failed`。依次检查：第二个 ScrollTrigger 或 Tween、残留 CSS transition 或 WAAPI 动画、内联样式写入。
2. 每行“GSAP 活动补间”与“CSS/WAAPI 动画”之和须为 1。同时为 0 或同时为 1，判定 `failed`。
3. “直接样式赋值”须为 0。非 0 判定 `failed`。
4. 文件声明的 `binding.mechanism` 须与本表一致，不一致判定 `failed`。
5. 以运行时计数为准。`getTweensOf()` 单独使用不足以证明唯一写入者，须配合 CSS 与 WAAPI 查询。
6. **减少动态模式**：活动补间与动画计数均为 0（无循环、无过渡）；终态由 `reduced_motion_writer` 一次性设定，允许 1 次直接样式赋值，且仅限终态属性。写入者与 10.3 规则 3 不一致，判定 `failed`。

---

## 第 11 节 无障碍与安全

### 11.1 底线

1. 不得以动态传达唯一信息。
2. 减少动态下内容须完整。
3. 闪烁不得超过每秒三次（WCAG 2.3.1）。

### 11.2 WCAG 2.2 对照表

本表为检查清单，不构成合规声明。准则编号与级别依 R-19 核验（待核验），发布前须对照原文。

| 准则 | 级别 | 本文件要求 | 验证方式 |
|---|---|---|---|
| 1.4.11 非文本对比度 | AA | 动效控件与状态指示满足对比要求 | 测量 |
| 1.4.13 悬停或焦点时的内容 | AA | 出现的内容可关闭、可悬停、持续可见 | 手动 |
| 2.2.1 计时可调 | A | 有时限交互可调整或延长 | 手动 |
| 2.2.2 暂停、停止、隐藏 | A | 自动运动超过 5 秒且并列时，可暂停、停止或隐藏（待验证，见 C-A09） | 手动 + 键盘 |
| 2.3.1 三次闪烁或低于阈值 | A | 不超过每秒三次闪烁 | 测量 |
| 2.3.3 由交互引起的动画 | AAA | 运动可通过偏好禁用 | 手动 |
| 2.4.11 焦点不被遮挡（最低） | AA | 获焦元素至少部分可见 | 手动 |
| 2.4.13 焦点外观 | AAA | 焦点指示满足尺寸与对比要求 | 测量 |
| 2.5.1 指针手势 | A | 多点或路径手势有单指针替代 | 手动 |
| 2.5.4 动作触发 | A | 基于设备运动的操作有替代方式 | 手动 |
| 2.5.7 拖动 | AA | 拖动操作有单指针替代 | 手动 |
| 2.5.8 目标尺寸（最低） | AA | 目标尺寸满足最低要求 | 测量 |
| 4.1.3 状态消息 | AA | 状态变化可被辅助技术感知 | 辅助技术 |

### 11.3 风险分级

- **高**：闪烁、大幅运动、自动播放且含信息。
- **中**：循环运动、视差。
- **低**：局部颜色或透明度变化。

### 11.4 减少动态

1. 提供静态替代画面。
2. 直接切换状态。
3. 停止循环运动。
4. 保证文字可读。

### 11.5 语义、焦点与声音

焦点顺序符合阅读顺序；焦点可见；状态变化通过 4.1.3 所述方式通知；自动播放声音可控。

---

## 第 12 节 技术选型与实现

### 12.1 选型

| 需求 | 首选 | 备注 |
|---|---|---|
| 简单过渡 | CSS transition 或 WAAPI | 避免布局属性（12.3） |
| 复杂时间轴 | GSAP Core + Timeline | labels 与 position parameter（R-01，待核验） |
| 滚动映射 | GSAP ScrollTrigger 或原生 Scroll-driven Animations | 依浏览器支持（待核验） |
| 实时 3D | Three.js | 见第 8 节 |
| 程序化材质 | GLSL 或 TSL | 见 8.2 |
| 可交互矢量与状态机 | Rive | 见 12.4 |
| 轻量矢量 | Lottie | 见 12.4 |
| 固定高画质 | 预渲染视频或序列帧 | 见 12.4 |

### 12.2 GSAP 要点

1. 用 `gsap.context()` 收集作用域，统一 `revert()`。
2. 用 `gsap.matchMedia()` 管理断点。据该 API 文档，其内部已使用 Context，但外部监听器与非 GSAP 资源须手动清理（R-04、R-05，待核验）。
3. SplitText 的 `autoSplit`、`onSplit()`、`revert()` 以官方文档为准（R-03，待核验）。`aria: "auto"` 不保留嵌套链接等语义，须逐项核验。

示意代码（未执行）：

```js
const ctx = gsap.context(() => {
  gsap.timeline({
    scrollTrigger: { trigger: '.section-2', start: 'top top', end: '+=100%', scrub: true }
  }).to('.step2-caption', { opacity: 1, y: 0 });
}, root);

ctx.revert(); // 卸载时
```

### 12.3 CSS 与 WAAPI

1. 避免动画 `top`、`left`、`width`、`height`、`box-shadow`。
2. 优先 `transform` 与 `opacity`。
3. `clip-path` 用于 reveal 时须单独测量性能。
4. 动画结束后清理（R-14，待核验）。

### 12.4 Rive、Lottie、视频与序列帧

- **Rive**：接口名以项目锁定版本的官方文档为准。文本不写具体版本号作为默认依据。每次升级须重新核验 state-machine input 与 text-run 接口（R-17、R-18）。
- **Lottie**：体积与表达式支持须核验。
- **视频**：自动播放须静音，并提供减少动态替代；记录解码耗时。
- **序列帧**：记录体积与帧率。

### 12.5 SSR 与水合

动画初始状态在服务端与客户端一致；初始静止态可读；避免水合闪跳。

### 12.6 布局稳定

动画不得引起布局偏移；图像与字体预留空间；CLS 与动画帧率分开测量（R-24，待核验）。

### 12.7 移动与性能

移动端减少同时运动对象数；降低渲染分辨率；按设备能力降级；测量方法见 13.5。

---

## 第 13 节 证据、发布与测试

### 13.1 证据等级

- **R**：可复现测量结果，附方法与环境。
- **S**：来源可核验的标准或规范。
- **D**：设计判断，基于经验或静态对照。
- **U**：未验证的假设。

D 级不能支持效果结论。

### 13.2 证据对照

| 结论类型 | 最低证据 | 说明 |
|---|---|---|
| 符合某条 WCAG 准则 | R，或正式审核 | 本文件不做认证 |
| 符合某规范的参数定义 | S | 须引用规范原文 |
| 此节奏更有张力 | D | 仅作设计讨论依据 |
| 提升转化 | 不在本文件范围 | 需另行实验（13.7） |

### 13.3 发布闸门

每项须写明通过依据，或 `not_tested` / `blocked` 原因。

1. **概念**：概念闸门（3.5）通过且可追溯。
2. **视觉**：静态构图检查（7.1）通过。
3. **语言**：无 13.7 禁用表述。
4. **影片**：6.6 七项；Showreel 另按 6.7。
5. **规格**：驱动模型字段完整；每个属性一个 `primary_writer`；符合 10.7。
6. **交互**：状态与中断验收有结果或明确状态。
7. **适配**：响应式与降级规则已验证或标注状态。
8. **无障碍与安全**：11.2 清单与相关验收有结果或明确状态。
9. **技术**：13.5 测量与依赖核验有结果或明确状态。

### 13.4 测试场景分类

加载与降级、视口与排版、导航与滚动、状态与中断、输入与焦点、偏好与主题、设备与资源。

### 13.5 性能测量

1. 分开测量：冷启动、解码、首帧、交互响应、稳态。
2. 报告 p50、p95、超预算帧数、最长单帧。
3. 帧预算 `T = 1000 / Hz`：60 Hz 为 16.7 ms，120 Hz 为 8.3 ms。
4. 记录设备、浏览器版本、刷新率、省电模式。

### 13.6 缺陷等级

严重（阻断任务或无障碍风险）→ 主要（状态错误或明显不一致）→ 次要（局部视觉偏差）→ 偏好（风格差异）。修正按此顺序。

### 13.7 禁用表述与替代写法

| 禁用表述 | 替代写法 |
|---|---|
| 已通过 | `not_tested`，或附测试编号与证据 |
| 流畅 | 写明 p95 与超预算帧数 |
| 兼容 | 写明已测浏览器与设备，及未测范围 |
| 无障碍合格 | 列出已执行与未执行检查；本文件不做认证 |
| 提升转化 | 不作本文件结论；如需要另行实验 |
| 符合物理 | 写明模型与参数来源，并标注偏离 |

---

## 第 14 节 常见失败模式

1. 以效果替代概念。
2. 概念无法回溯到事实。
3. 静态层级不成立。
4. 同一属性有多个写入者。
5. 滚动劫持。
6. 减少动态下内容缺失。
7. 闪烁或大幅运动无替代。
8. 以录屏代替运行验证。
9. 以 `getTweensOf` 单一方法证明唯一写入者。
10. 中断或反向后状态残留。
11. 循环运动无暂停控制。
12. 布局属性动画导致卡顿与偏移。
13. 示例数值被直接用于发布。
14. 未核验的外部主张被当作事实。
15. 以删除领域内容换取篇幅。

---

## 第 15 节 适用范围、参考与版本

### 15.1 适用范围

适用于 Web 动效、实时 3D 场景、影片与 Showreel 的规格与验收方案。不替代用户研究、法务合规或正式无障碍认证。

### 15.2 外部扩展与最低交付

1. 外部文件为可选扩展，不是必需来源。
2. 6.4 为离线制作唯一必需来源。
3. 最低交付物：
   1. 概念简报（3.4）
   2. Tempo Map（L2 及以上，5.2）
   3. Spec 与驱动模型（第 10 节）
   4. 验收方案（每个动作至少一条）
   5. 示例数值确认表（附录 D；未确认数值不得用于发布）

### 15.3 核心参考

外部来源的核验状态仅在本表登记。研究对象见 3.3.1。核验前，正文相关主张标“待核验”，不得引用其结论。

| 编号 | 来源 | 用途 | 核验状态 |
|---|---|---|---|
| R-01 | GSAP Core：https://gsap.com/docs/v3/GSAP/ | 时间轴、labels、position parameter | 未核验 |
| R-02 | GSAP ScrollTrigger：https://gsap.com/docs/v3/Plugins/ScrollTrigger/ | start、end、scrub、pin、snap | 未核验 |
| R-03 | GSAP SplitText：https://gsap.com/docs/v3/Plugins/SplitText/ | 拆分、revert、aria | 未核验 |
| R-04 | GSAP matchMedia：https://gsap.com/docs/v3/GSAP/gsap.matchMedia()/ | 断点与清理 | 未核验 |
| R-05 | GSAP Context：https://gsap.com/docs/v3/GSAP/gsap.context()/ | 作用域与批量 revert | 未核验 |
| R-06 | GSAP Flip、MotionPathPlugin、Observer | 仅作参考，正文未依赖 | 未核验 |
| R-07 | Three.js 文档：https://threejs.org/docs/ | 基础 API | 未核验 |
| R-08 | WebGPURenderer：https://threejs.org/manual/pages/webgpurenderer | 异步初始化与渲染器选择 | 未核验 |
| R-09 | TSL API：https://threejs.org/docs/pages/TSL.html | TSL 用法 | 未核验 |
| R-10 | Node Materials：https://threejs.org/docs/pages/NodeMaterial.html | 节点材质 | 未核验 |
| R-11 | WebGPU 示例：https://threejs.org/examples/?q=webgpu | 迁移参考 | 未核验 |
| R-12 | ShaderMaterial：https://threejs.org/docs/pages/ShaderMaterial.html | GLSL 材质 | 未核验 |
| R-13 | Khronos glTF 2.0 PBR：https://registry.khronos.org/glTF/specs/2.0/glTF-2.0.html | Metalness、Base color、颜色空间 | 未核验 |
| R-14 | MDN Web Animations API：https://developer.mozilla.org/en-US/docs/Web/API/Web_Animations_API | 播放控制与清理 | 未核验 |
| R-15 | MDN WebGL 最佳实践：https://developer.mozilla.org/en-US/docs/Web/API/WebGL_API/WebGL_best_practices | 性能与资源管理 | 未核验 |
| R-16 | MDN prefers-reduced-motion：https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-reduced-motion | 减少动态偏好 | 未核验 |
| R-17 | Rive 文档：https://rive.app/docs/ | 接口与版本说明 | 未核验 |
| R-18 | Rive 公告：https://community.rive.app/c/announcements | 接口变更记录 | 未核验 |
| R-19 | W3C WCAG 2.2：https://www.w3.org/TR/WCAG22/ | 第 11 节对照 | 未核验 |
| R-20 | pause-stop-hide：https://www.w3.org/WAI/WCAG22/Understanding/pause-stop-hide | 2.2.2 | 未核验 |
| R-21 | animation-from-interactions：https://www.w3.org/WAI/WCAG22/Understanding/animation-from-interactions | 2.3.3 | 未核验 |
| R-22 | WAI-ARIA APG：https://www.w3.org/WAI/ARIA/apg/ | 焦点与交互模式 | 未核验 |
| R-23 | W3C clreq：https://www.w3.org/TR/clreq/ | CJK 排印 | 未核验 |
| R-24 | web.dev Core Web Vitals：https://web.dev/articles/vitals | 布局稳定与性能指标 | 未核验 |

### 15.4 最终标准

1. 每个原则可回溯到事实与证据等级。
2. 任一验收 `failed` 时不得发布。
3. `blocked` 与 `not_tested` 须写明原因。
4. 不伪造测试、性能、兼容或无障碍结果。

### 15.5 本版修改摘要（v6.7.0）

1. 压缩篇幅：附录动作改紧凑字段列表；C.4 改为每段一行；删除与 C.9、C.10 重复的验收说明；CHANGELOG 压缩为版本条目。
2. `update_model` 枚举收敛为 `event` | `state-transition` | `continuous`；滚动来源统一记入 `value_source`。
3. 新增 `reduced_motion_writer`（10.3 规则 3、10.4、10.7 规则 6），并在 B M-01、C M-02 至 M-04 写明取值。
4. M-04 触发补“离开 S4”；pause 与 cancel 语义只在 lifecycle 写一次。
5. 新增附录 D 统一示例数值确认表；8.5、B.5、C.12 不再分列；15.2 第 5 项改为引用附录 D。
6. 4.2 行为层级与 9.4 CTA 路径标注为 D 级设计判断。

本版未执行任何测试，所有验收项仍为 `not_tested`。

---

## 附录 A 交付前自检

1. 删除运动后，用户失去什么信息或操作？（1.3）
2. 去掉运动后，层级与阅读顺序是否仍成立？（3.5、13.3 第 2 项）
3. 每项原则能否回溯到 E1 或 E2 并标注证据等级？（3.2、13.1）
4. 减少动态时内容是否完整？（11.4、10.7 规则 6）
5. 是否存在闪烁或大幅运动？（11.3）
6. 每个被驱动属性是否只有一个主写入者且符合期望值？（10.3、10.7）
7. 中断、重复触发与反向后状态是否可预测？（9.2 第 3 项、10.3 的 `conflict_resolution` 与 `handoff`）
8. 每个 `passed` 是否有可追溯证据？（13.1）
9. 是否存在 13.7 禁用表述？（13.3 第 3 项）
10. 无法运行时是否交付可复现步骤与录屏脚本？（2.3）

---

## 附录 B L2 样例：产品官网首屏

> 本附录所有事实、数值与来源均为示例假设，须经项目负责人确认后方可用于发布。

**B.1 事实**

- **F-01**（E3）：刚性金属机身。型号 A 高 120 mm，型号 B 高 180 mm。
- **F-02**（E3）：首屏任务是比较两型号的相对尺寸。
- **F-03**（E2）：比较依赖相对比例，而非动画速度。

**B.2 原则**

- **P-01**（依据 F-03）：两型号使用同一尺度参考，不得用透视或视距制造尺寸差异。
- **P-02**（依据 F-01）：刚性对象不发生形变。

**B.3 动作 M-01**（字段含义见 10.4）

```
role: Functional；attention: Lead
intent: 让用户比较两型号的相对尺寸
target: .product-container 的 transform
trigger: user-action（型号切换按钮 click / Enter / Space）；repeat_policy: retarget
driver: update_model state-transition；value_source none；timebase none
state: 型号 A → 型号 B
behavior: core scale
time: duration_ms 320（D-B05）；easing settle-token
space: frame container；origin 产品底部中心锚点
reduced_motion: 直接切换
reduced_motion_writer: state-transition:product（duration 0）
responsive: 移动端行为相同；切换按钮满足 2.5.8（待测量）
binding: WAAPI；ownership .product-container / transform；primary_writer state-transition:product；mode exclusive
lifecycle: 卸载时取消进行中的动画，不残留监听器
fallback: 直接切换
acceptance: B-A01 至 B-A06
evidence: E3 示例假设；设计判断 D 级
```

**B.4 验收**

- **B-A01**：键盘切换且焦点保持。Tab 聚焦后以 Enter 或 Space 切换。桌面 Chrome 与 Safari 各一次。`not_tested`。
- **B-A02**：减少动态下无缩放，直接切换。VoiceOver，macOS Safari 与 iOS 真机。`not_tested`。
- **B-A03**：200 ms 间隔连续点击 5 次后，`getAnimations()` 为空数组；终态 `transform` 等于计算值；监听器数量不变。`not_tested`。
- **B-A04**：两型号高度比与 120:180 的相对误差 ≤ 0.5%（D-B03）。视口 1440 px（D-B04），`getBoundingClientRect()` 测量。`not_tested`。
- **B-A05**：切换期间 p95 ≤ 16.7 ms（60 Hz）。性能面板记录 10 次切换（D-B07）。`not_tested`。
- **B-A06**：写入者计数符合 10.7 中 B M-01 行。`not_tested`。

**聚合**：全部 `not_tested`。

---

## 附录 C L3 样例：品牌官网工艺叙事段

> 本附录所有事实、数值、来源与阈值均为示例假设，须经项目负责人确认后方可用于发布。

**C.1 概念简报**

```yaml
primary_intent: explanatory
audience: 采购工程师（桌面为主）
facts:
  F-01: 成品公差 ±0.02 mm（E3，D-C01）
  F-02: 访客首要任务是理解从原料到成品的三道工序（E3，US-07）
  F-03: 三道工序有先后因果，由示例流程图编号顺序推出（E2）
proposition: 以顺序揭示因果，让采购方理解精度来自每道工序的衔接。
metaphor: 切面逐层显露
motifs: [逐层显露, 交接]
```

**C.2 原则**

- **P-01**（依据 F-03）：顺序即因果，不得倒置。
- **P-02**（依据 F-02）：三道工序使用同一尺度参考。
- **P-03**（依据 F-02）：滚动不劫持。

**C.3 闸门**：可追溯、必要性、替换、剥离、延展全部通过（D 级，待验证）。

**C.4 Tempo Map**（字段含义见 5.2；未列区域为 still）

| 段 | 进度 | information | lead | support | ambient | 上限/并发 | trigger | 可中断 | hold_ms | fallback | evidence |
|---|---|---|---|---|---|---|---|---|---|---|---|
| S1 Establish | 0–10% | 页面主题与三道工序总览 | 标题（静态） | — | — | 低/1 | 加载完成 | true | — | 静态首屏 | D |
| S2 Act 工序 1 | 10–30% | 工序 1 的输入与输出 | 静态工序 1 图 | — | — | 低/1 | 进入 10% | true | — | 静态工序 1 图 | D |
| S3 Transfer | 30–35% | 承接工序 1 至工序 2 | — | — | — | 低/0 | 进入 30% | true | — | 静止 | D |
| S4 Act 工序 2 | 35–55% | 工序 2：切面逐层显露与说明 | M-02 | M-03 | M-04 | 中/2（D-C03） | 进入 35% | true | — | 静态分步图（C-02 降级） | D |
| S5 Hold | 55–65% | 完整切面与说明保持可读 | — | — | — | 低/0 | 进入 55% | true | 1200（D-C10） | 静止完整切面图 | D |
| S6 Act 工序 3 | 65–85% | 工序 3 的输出与精度来源 | 静态工序 3 图 | — | — | 低/1 | 进入 65% | true | — | 静态工序 3 图 | D |
| S7 Resolve | 85–100% | 三道工序因果汇总 | 静态汇总图 | — | — | 低/1 | 进入 85% | true | — | 静态汇总图 | D |

Tempo Map 为 D 级，待验证。本样例仅定义 S4 的动作，其余段仅保留静态呈现，整体不得标为通过。

**C.5 TIME-02（时间映射）**

- 适用：`section-2-scroll`；输入：页面进度；输出：`local = clamp((page − 0.35) / 0.20, 0, 1)`
- 曲线 linear；正反向同一映射；无平滑。

| 页面进度 | 35% | 38% | 40% | 42% | 45% | 50% | 55% |
|---|---|---|---|---|---|---|---|
| local | 0 | 0.15 | 0.25 | 0.35 | 0.50 | 0.75 | 1 |

**C.6 动作 M-02（切面显露，Narrative / Lead）**

```
target: .step2-image 的 clip-path
trigger: scroll-boundary，进入 S4（35%）；repeat_policy merge
driver: update_model continuous；value_source scroll-progress；timebase scroll-progress（section-2-scroll）；mapping TIME-02
output: clip-path: inset(T% 0 0 0)，T = 100 × (1 − local)
state: inset(100% 0 0 0) → inset(0% 0 0 0)
behavior: deform / reveal-clip；contract_ref C-02
space: container；origin 切面图左下角；仅裁切，不位移
time: timebase 同 driver；无固定时长；easing linear（经 TIME-02）
continuity: 输出位置 C0；不声称输入轨迹连续（4.5）
precedence: [用户输入（滚动）, 叙事时间轴, Ambient]；conflict_resolution retarget；handoff retarget-from-current
responsive: 移动端取消 scrub，改三步切换；平板同桌面，缩短区间
reduced_motion: 直接显示完整切面图
reduced_motion_writer: scrollTrigger:section-2（设为 inset(0% 0 0 0)）
binding: GSAP ScrollTrigger；ownership .step2-image / clip-path；primary_writer scrollTrigger:section-2；mode exclusive
lifecycle: 断点切换时 matchMedia revert；路由离开时 ctx.revert()
fallback: 静态分步图
acceptance: C-A01 至 C-A04、C-A07
evidence: D（设计判断）；TIME-02 映射为 E3（D-C02）
```

**C.7 动作 M-03（说明文字，Narrative / Support）**

```
target: .step2-caption 的 [opacity, transform]
trigger: scroll-boundary，进入 S4；映射输入 local 0.15（38%）起生效；repeat_policy merge
driver: update_model continuous；value_source scroll-progress；timebase scroll-progress（section-2-scroll）；mapping TIME-02；input_domain local ∈ [0.15, 0.35]
output: p = clamp((local − 0.15) / 0.20, 0, 1)；opacity = p；translateY = 12px × (1 − p)（D-C04）
curve: linear；clamp true
behavior: core [fade, translate]
choreography: local 0.15 开始，0.35 达终态；先于 M-02 完成，不要求同时结束
time: timebase 同 driver；无固定时长
responsive: 随 M-02 的三步切换一并呈现；平板同桌面
reduced_motion: 文字直接可读（opacity 1、translateY 0）
reduced_motion_writer: scrollTrigger:section-2-caption
binding: GSAP ScrollTrigger；ownership .step2-caption / [opacity, transform]；primary_writer scrollTrigger:section-2-caption；mode exclusive
lifecycle: 同 M-02
fallback: 静态可读文字
acceptance: C-A05、C-A06
evidence: D（设计判断）
```

**C.8 动作 M-04（环境光晕，Ambient）**

```
target: .step-index-2__halo（装饰性，aria-hidden="true"）的 opacity
trigger: 进入 S4 开始；离开 S4 暂停；repeat_policy retarget
driver: update_model continuous；value_source none；timebase monotonic-time；period_ms 3200（D-C06）
output: opacity 在 [0.2, 0.6] 之间正弦循环
behavior: core fade；easing sine-in-out
interrupt: 悬停或获得焦点时立即停止，移开后不恢复
precedence: [用户输入（悬停或焦点）, 叙事时间轴, Ambient]；conflict_resolution cancel；handoff settle-to-state
responsive: 移动端保留，周期加长
reduced_motion: 停止循环并隐藏（装饰性，不承载信息）
reduced_motion_writer: ambient:step-index-2（opacity 0）
binding: WAAPI；ownership .step-index-2__halo / opacity；primary_writer ambient:step-index-2；mode exclusive
pause_control: “暂停环境动效”开关，键盘可操作；循环运动须满足 WCAG 2.2.2，由 C-A09 验证，未验证前不得声称满足
lifecycle: 离开 S4 时 pause（保留当前值）；卸载时 cancel 并清理
fallback: 停止循环并隐藏
acceptance: C-A08、C-A09
evidence: D（设计判断）；2.2.2 合规待 C-A09
```

**C.9 C-02（reveal-clip 契约）**

- **参考系**：container
- **参数**：`clip-path: inset(T% 0 0 0)`，`T = 100 × (1 − local)`；自下而上，仅裁切
- **状态**：触发（进入 S4）→ 运行（local 经 TIME-02 映射为 T，100→0）→ 完成（local 到 1 后保持）；取消保留当前值，不自动回退；不支持时显示完整图像并记录降级；重入从当前进度继续
- **中断**：反向时按 TIME-02 同步
- **适配**：移动端由 M-02 的响应式规则替代，不使用本契约
- **无障碍替代**：直接显示完整图像，替代文本保留在 DOM
- **降级**：静态分步图
- **验收**：C-A01 至 C-A04、C-A07（期望值见 10.7）

**C.10 验收**

显露比例定义为 `1 − T/100`，即 local。

- **C-A01（M-02）**：页面进度 40%、45%、50% 停止时，显露比例与 local 偏差 ≤ 2%（D-C07；对应 local 0.25、0.50、0.75）。T-01，桌面 Chrome。`not_tested`。
- **C-A02（M-02）**：从 50% 反向滚至 30% 后，`clip-path` 为 `inset(100% 0 0 0)`，无残留 WAAPI 动画。T-02，桌面 Chrome 与 Safari。`not_tested`。
- **C-A03（M-02）**：减少动态下显示完整切面图。T-03，macOS 与 iOS 真机。`not_tested`。
- **C-A04（M-02）**：S4 区间滚动期间 p95 ≤ 刷新率预算（60 Hz 为 16.7 ms）。T-04，5 次滚动，设备见 C.11。`not_tested`。
- **C-A05（M-03）**：local 0.15、0.25、0.35（页面进度 38%、40%、42%，D-C08）时，opacity 为 0、0.5、1（容差 ±0.02），translateY 为 12px、6px、0px（容差 ±1px），单调变化（D-C05）。T-05，桌面 Chrome。`not_tested`。
- **C-A06（M-03）**：减少动态下文字直接可读。T-06，macOS 与 iOS 真机。`not_tested`。
- **C-A07（附录 C 所列动作）**：写入者计数符合 10.7 中 C M-02、M-03、M-04 行。T-07。`not_tested`。
- **C-A08（M-04）**：悬停或焦点时呼吸立即停止，移开后不恢复。T-08，桌面 Chrome 与 Firefox。`not_tested`。
- **C-A09（M-04）**：暂停控制可由键盘操作；Space 切换两次，循环可暂停、停止或隐藏。T-09。`not_tested`。

**C.11 设备清单与聚合**

- 桌面 Chrome 最新稳定版（Windows 与 macOS）；iOS Safari 真机一台；中端 Android Chrome 真机一台。记录刷新率（120 Hz 时帧预算 8.3 ms，D-C09）。
- **聚合**：概念闸门通过（D 级）；Tempo Map D 级待验证；M-02、M-03、M-04 与 C-02 全部 `not_tested`；整体不得标为通过。当前可交付概念简报、Tempo Map、Full Spec、验收方案（D 级与 S 级）。

---

## 附录 D 示例数值确认表

本表合并原 8.5、B.5、C.12 的全部示例数值。状态仅允许“待确认”或“已确认”；标为“已确认”时须填写确认人与确认日期。未确认数值不得用于发布。

| 编号 | 位置 | 示例数值 | 来源 | 状态 | 确认人 |
|---|---|---|---|---|---|
| D-B01 | B F-01 | 型号 A 高 120 mm | E3 示例假设 | 待确认 | 待指定 |
| D-B02 | B F-01 | 型号 B 高 180 mm | E3 示例假设 | 待确认 | 待指定 |
| D-B03 | B-A04 | 相对误差 ≤ 0.5% | E3 示例阈值 | 待确认 | 待指定 |
| D-B04 | B-A04 | 视口 1440 px | E3 示例假设 | 待确认 | 待指定 |
| D-B05 | B M-01 | duration_ms 320 | E3 示例假设 | 待确认 | 待指定 |
| D-B06 | B-A03 | 200 ms 间隔，连续点击 5 次 | E3 示例假设 | 待确认 | 待指定 |
| D-B07 | B-A05 | p95 ≤ 16.7 ms；10 次切换 | E3 示例阈值 | 待确认 | 待指定 |
| D-C01 | C F-01 | 成品公差 ±0.02 mm | E3 示例假设 | 待确认 | 待指定 |
| D-C02 | TIME-02 | 映射区间 35%–55%（宽度 0.20） | E3 示例假设 | 待确认 | 待指定 |
| D-C03 | C.4 | 页面进度区间；S4 并发上限 2 | E3 示例假设 | 待确认 | 待指定 |
| D-C04 | M-03 | 输入区间 0.15–0.35；translateY 12px | E3 示例假设 | 待确认 | 待指定 |
| D-C05 | C-A05 | 容差 ±0.02（opacity）、±1px（translateY） | E3 示例阈值 | 待确认 | 待指定 |
| D-C06 | M-04 | period_ms 3200；opacity 区间 [0.2, 0.6] | E3 示例假设 | 待确认 | 待指定 |
| D-C07 | C-A01 | 显露偏差 ≤ 2% | E3 示例阈值 | 待确认 | 待指定 |
| D-C08 | C-A05 | 页面进度 38%、40%、42% | E3 示例假设 | 待确认 | 待指定 |
| D-C09 | C.11 | 120 Hz 帧预算 8.3 ms；设备清单 | E3 示例假设 | 待确认 | 待指定 |
| D-C10 | C.4 | S5 的 hold_ms 1200 | E3 示例假设 | 待确认 | 待指定 |
| D-G01 | 8.5 | 同屏可交互 3D 对象 ≤ 1 | E3 示例假设 | 待确认 | 待指定 |
| D-G02 | 8.5 | 渲染像素比 ≤ 2.0 | E3 示例假设 | 待确认 | 待指定 |
| D-G03 | 8.5 | 同时运动对象 ≤ 3 | E3 示例假设 | 待确认 | 待指定 |
| D-G04 | 8.5 | 单个 3D 资源 ≤ 2 MB | E3 示例假设 | 待确认 | 待指定 |

**关联**：附录 B、C 与 8.5 中出现的示例数值，均以此表编号为准；正文不再重复“待确认”说明。