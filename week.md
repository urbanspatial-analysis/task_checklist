# 学期末周计划：Remote Sensing 与 Thesis 主线

本文件只聚焦两条最核心主线：

1. **Remote sensing 识别项目**
2. **Telework thesis / 论文写作与投稿准备**

原则：

* **Remote sensing**：目标是在 **3 周内完成闭环**，前 **2 周快速推进**。
* **Thesis / telework paper**：目标是在学期末前完成 **literature review、results、discussion**，并进入 **6 月初投稿准备**。
* 每周优先保证这两条主线，不被零碎事务切断。

---

# 一、Remote Sensing：Week-level Plan

## 总目标

* 在 3 周内完成一个 **可信、可复现、能解释** 的版本
* 明确并聚焦于：

  * **cross width**
  * **crosswalk quality / painting**
* 不扩展到额外任务（例如 road width）
* 完成从数据准备到结果输出的完整闭环

---

## Week 1：锁定方案 + 跑通 baseline

### 本周核心目标

* 把项目从“想法”推进到“能跑”
* 完成 test area、数据准备、baseline workflow
* 明确后面两周的技术路径

### Checklist

#### 1. 明确项目范围与方法

* [ ] 最终确认研究目标：只做 **cross width** 和 **crosswalk painting quality**
* [ ] 写下完整 workflow（preprocessing → sample prep → segmentation/identification → evaluation）
* [ ] 明确输入数据、辅助数据、输出结果格式
* [ ] 明确街道层级结果如何回传/汇总

#### 2. 数据与测试区准备

* [ ] 整理 imagery 数据
* [ ] 整理 OSM / road / crossing 辅助数据
* [ ] 选定一个局部 **test area**
* [ ] 完成 clip / preprocessing
* [ ] 建立清晰的文件夹结构（raw / processed / labels / outputs / scripts）

#### 3. 样本与 baseline

* [ ] 确定样本标注方案
* [ ] 准备第一批训练 / 测试样本
* [ ] 跑通第一个 baseline 方法
* [ ] 输出第一版识别结果图
* [ ] 记录主要问题与错误类型

### 本周产出

* [ ] 一页清晰的方法步骤说明
* [ ] 一个可运行的 baseline pipeline
* [ ] 一批测试结果图
* [ ] 一份问题清单（误差来源、难点、后续调整方向）

### 本周提醒

* 本周目标不是做精度最优，而是 **先把流程跑通**。
* 任何新想法，先记下来，不要打断主线闭环。

---

## Week 2：优化识别 + 完成阶段性结果

### 本周核心目标

* 基于 Week 1 的 baseline 结果做调整
* 明确哪些错误可以修正，哪些先接受
* 做出一版 **可展示的阶段性成果**

### Checklist

#### 1. 错误诊断

* [ ] 系统整理 baseline 的主要误差来源
* [ ] 区分 cross width 误差 与 painting quality 误差
* [ ] 判断问题来自数据、样本、模型还是后处理

#### 2. 方法调整

* [ ] 调整 segmentation / identification 流程
* [ ] 必要时优化 sample selection / labeling
* [ ] 测试新的参数或替代识别思路
* [ ] 对比优化前后的结果差异

#### 3. 阶段性结果整理

* [ ] 输出一版 improved results
* [ ] 整理成功案例图
* [ ] 整理失败案例图
* [ ] 初步总结哪些结果已经达到可接受水平
* [ ] 记录仍然存在的限制

### 本周产出

* [ ] 一版明显优于 baseline 的结果
* [ ] 阶段性结果图集
* [ ] 成功 / 失败案例归纳
* [ ] 调参和方法调整记录

### 本周提醒

* 重点是 **做出可用版本**，而不是陷入 endless tuning。
* 你需要开始思考最终交付，而不是无限试验。

---

## Week 3：完成闭环 + 文档化 + 结果导出

### 本周核心目标

* 完成最终版本
* 导出结果
* 保存可复现材料
* 整理后续可写作/汇报的内容

### Checklist

#### 1. 最终结果确认

* [ ] 选择最终 workflow
* [ ] 生成最终结果
* [ ] 检查街道层级结果回传是否顺畅
* [ ] 确认结果命名、格式、版本清晰

#### 2. 输出与保存

* [ ] 导出 final outputs
* [ ] 保存关键图表和地图结果
* [ ] 保存代码版本
* [ ] 保存参数设置
* [ ] 保存日志和处理说明

#### 3. 文档整理

* [ ] 整理 methodology notes
* [ ] 整理英文 checklist / workflow
* [ ] 写一份简短项目总结（目标、方法、结果、局限）
* [ ] 标记未来若继续改进，优先优化的部分

### 本周产出

* [ ] 最终版本结果
* [ ] 可复现项目文件结构
* [ ] 方法与步骤文档
* [ ] 可用于后续写作/汇报的图表和说明

### 本周提醒

* 第 3 周的关键词是：**结束、定稿、保存、归档**。
* 不再追求大改动，优先保证项目完整交付。

---

# 二、Telework Thesis / 论文：Week-level Plan

## 总目标

* 完成 **literature review 修订**
* 完成 **results**
* 完成 **discussion**
* 整理 thesis 当前版本
* 为 **6 月初投稿 TRA 或 TRB** 做准备

---

## Week 1：Literature Review 定稿 + Results 起草

### 本周核心目标

* 尽快把 literature review 从“持续修改”推进到“基本定稿”
* 同时启动 results section，避免写作后移

### Checklist

#### 1. Literature Review 修订

* [ ] 修订整体结构和段落逻辑
* [ ] 统一 telework / WFH / remote work 的概念使用
* [ ] 补强与现有文献的差异和贡献 framing
* [ ] 强化非线性、行为机制、日内出行重组的讨论
* [ ] 检查 citation 是否存在薄弱或不够贴切之处
* [ ] 统一术语和写作语气

#### 2. Results 起草

* [ ] 搭建 results section 总结构
* [ ] 先写主模型结果
* [ ] 明确表格和正文如何对应
* [ ] 写出最核心的 2–3 个 findings
* [ ] 标记哪些结果需要补充 robustness/PSM 解读

### 本周产出

* [ ] 一个基本定稿的 literature review
* [ ] 一个完整的 results section skeleton
* [ ] 主模型结果初稿

### 本周提醒

* 本周不要再无限打磨 literature review。
* 目标是让论文主体开始“向前走”。

---

## Week 2：完成 Results + 启动 Discussion

### 本周核心目标

* 完成 results 全文
* 启动 discussion section
* 开始把“结果”转化成“论文论点”

### Checklist

#### 1. Results 完成

* [ ] 完成主模型解释
* [ ] 完成 supplementary model 结果写作
* [ ] 完成 mechanism models 结果写作
* [ ] 写入 PSM / robustness test 结果
* [ ] 检查表格、附录、正文是否一致
* [ ] 区分正文重点与 appendix 内容

#### 2. Discussion 启动

* [ ] 列出 discussion 的 3–5 个核心论点
* [ ] 解释 telework intensity 的主要含义
* [ ] 解释 total trips 与 trip purpose 的关系
* [ ] 初步讨论行为机制与理论意义
* [ ] 记下政策含义和局限性要点

### 本周产出

* [ ] 一个完整的 results draft
* [ ] 一个 discussion outline
* [ ] discussion 前半部分初稿

### 本周提醒

* Results 写作要偏“呈现与解释结果”，Discussion 再负责提升到更高层次。
* 不要把 discussion 全塞进 results。

---

## Week 3：完成 Discussion + 整合 Thesis 主体

### 本周核心目标

* 完成 discussion
* 把 literature review、results、discussion 连成一个完整 thesis/paper draft
* 开始从“章节写作”转向“整篇整合”

### Checklist

#### 1. Discussion 完成

* [ ] 完成理论意义讨论
* [ ] 完成政策含义讨论
* [ ] 完成研究局限性
* [ ] 完成未来研究方向
* [ ] 检查 discussion 是否与 results 重复过多

#### 2. 全文整合

* [ ] 通读 literature review、methods、results、discussion
* [ ] 统一术语、变量名称、写作风格
* [ ] 检查段落之间的逻辑衔接
* [ ] 检查表格、图表、附录引用是否完整
* [ ] 更新摘要中的核心发现表述（如需要）

### 本周产出

* [ ] discussion 完整稿
* [ ] 一个整合后的 thesis / article draft
* [ ] 一份需要最后润色的问题清单

### 本周提醒

* 第 3 周开始，论文重点不再是“补内容”，而是“形成完整成稿”。

---

## Week 4：投稿准备（TRA / TRB）

### 本周核心目标

* 从 thesis draft 进入投稿状态
* 对照目标期刊调整结构和表达

### Checklist

#### 1. 目标期刊对齐

* [ ] 确定优先目标：TRA 或 TRB
* [ ] 按目标期刊风格调整 framing
* [ ] 检查篇幅、格式、图表要求

#### 2. 投稿包准备

* [ ] 修改标题备选版本
* [ ] 修改 abstract
* [ ] 梳理关键词
* [ ] 检查参考文献格式
* [ ] 检查图表标题与注释
* [ ] 整理 cover letter 草稿

#### 3. 最终通读

* [ ] 做一轮全文通读
* [ ] 删除重复表达
* [ ] 修正逻辑跳跃与不清楚段落
* [ ] 检查语言流畅性
* [ ] 做最终版本归档

### 本周产出

* [ ] 一版可投稿 manuscript
* [ ] cover letter 草稿
* [ ] 投稿前 final checklist

### 本周提醒

* 这周重点是“投稿化”，不是继续扩展分析。
* 优先提高整篇稿件的完整度和专业度。

---

# 三、每周执行建议

## 每周最少完成标准

### Remote sensing

* [ ] 至少完成一个技术闭环节点
* [ ] 至少输出一批可检查结果
* [ ] 至少做一次问题记录与方法调整

### Thesis

* [ ] 至少完成一个完整写作板块
* [ ] 至少推进一轮结果—解释—讨论的衔接
* [ ] 至少做一次整合性通读或结构修订

---

# 四、每周复盘模板

## Week X 完成情况

### Remote sensing

* [ ] 本周完成：
* [ ] 当前卡点：
* [ ] 下周优先项：

### Thesis

* [ ] 本周完成：
* [ ] 当前卡点：
* [ ] 下周优先项：

---

# 五、最终提醒

* **Remote sensing**：追求的是一个三周内完成的、可复现的版本，而不是无限优化的完美模型。
* **Thesis / paper**：优先形成完整稿，再做精细润色；不要让 literature review 吞掉 results 和 discussion 的时间。
* 这两条主线应该占据你本阶段最好的专注时段。
