# 配图与复用

## 先列共用素材，再逐页分配

浏览报告、原图和模板，按章节列出反复出现的对象。为每种对象登记编号、名称、来源、使用范围、计划用页和已审版本。例如，报名处、阅读空间、回访问卷可以各有一个编号。原件存一份，裁切版本沿用原编号并注明视窗。只登记本次需要的对象，数量随提纲确定。

先选一个代表图标，放进目标版式确认尺寸和风格，再集中制作其余缺项，每个对象生成一次。后续页面按编号调用。改字、换页或调整布局时先复用已审图。记录本批复用和拟生成的数量，便于用户决定配图预算。

## 给每张小图标上来源

| 类型 | 逐页指令与制作方式 |
|---|---|
| 【AI】概念或实物示意 | 现有图和简单原生图形无法表达所需关系时使用。写清主体、数量、视角、位置、目标画幅和留白方向，再追加下方对应的完整英文后缀。文字、字母、数字、单位、标签和公式均在 PPT 中另加可编辑对象。 |
| 【代码】示意曲线或时序图 | 根据明确的变量与关系绘制，标记“示意”。约定坐标范围、曲线形状和线型，使用样式卡配色。需要位图时可导出 300 dpi 透明 PNG。数值来自数据文件时标明来源。 |
| 【实图】原始仿真或实测结果图 | 使用提供的原件。对原始仿真图只做裁剪，保留坐标、刻度、单位、图例和解释结果所需的对照。边框或注释箭头作为独立 PPT 对象叠加。禁止用 AI 重画、补画曲线或修改数据。缺原件时索取或留待补图。 |
| 【素材】用户提供的照片、标识或产品图 | 保留原件、来源和允许的用途。产品图用于说明部件外观，连接关系按实际资料用 PPT 连线表达。需要展示现场事实时采用现场照片。 |

原生表格、流程框和箭头直接制作。对比同一对象的多幅图时，保持视角与比例一致。精确的接口拓扑、文字和数值都由可编辑元素承载。

内置模板的代码示意曲线以白底、约 2 pt 线宽和左、下两轴为起点；网格可省略或用极浅灰。先用两种蓝色及线型区分系列。有明确物理含义的插图可在主体描述与全稿后缀中约定专色，例如用局部暖橙 `#F28C28` 表示温升。图内专色应有一致含义。

## 英文提示词后缀

把下面两段作为本稿共用常量。内置蓝色模板可直接使用。有自带模板时，按其样式卡一次性替换背景及三个色值，再锁定本稿两段文本。为图片模型提交的每条指令都用“英文主体描述 + 对应完整后缀”，展开为一段可直接复制的英文。STYLE-3D 和 STYLE-FLAT 用于索引。

**STYLE-3D · 实物与空间**

```text
Clean technical illustration for a presentation. Semi-realistic isometric 3D view, soft studio lighting, white background. Use navy (#254A81), steel blue (#355F86), light blue (#5B9BD5) and light gray; preserve natural material finishes. Crisp edges, soft contact shadow, generous margins. Keep the viewpoint and scale consistent with the approved reference. No text, letters, numbers, formulas, labels, logos or watermarks.
```

**STYLE-FLAT · 概念与平面示意**

```text
Flat vector illustration for a presentation. Use thin rounded lines, consistent stroke widths, minimal shading and a white background. Use navy (#254A81) for outlines, steel blue (#355F86) for connections, light blue (#5B9BD5) and light gray for fills. Show only the requested relationships, with balanced spacing and generous margins. No text, letters, numbers, formulas, labels, logos or watermarks.
```
