# IB DP Computer Science考试指南：Paper 1、Paper 2、题型与备考

> **适用范围：**本文重点介绍新课程（首教 2025 年 8 月、首次评估 2027 年 5 月），并与最后一次于 2026 年评估的旧课程作区分。它是备考概览，不代替 IB 官方课程指南、当届考试通知、评分标准或学校的正式要求。具体时长、分值、权重、题目数量和考生指示，请以学校可访问的最新版 IB 资料为准。

## 目录

1. 新旧课程与考试结构对比
2. 官方及公开样题、历年材料和 GitHub 资源
3. Paper 1、Paper 2 及 SL/HL 对比
4. 题型、命令词、作答和评分要求
5. 备考策略与练习建议

---

## 1. 新旧课程与考试结构对比

### 新课程：首次评估 2027

IB 官方计算机科学更新信息指出，新课程从 2025 年开始实施教学，并于 2027 年首次评估。课程围绕两个主题组织：

**Theme A — Concepts of Computer Science（计算机科学概念）**

- A.1 Computer fundamentals（计算机基础）
- A.2 Networks（网络）
- A.3 Databases（数据库）
- A.4 Machine learning（机器学习）

**Theme B — Computational thinking and problem-solving（计算思维与问题解决）**

- B.1 Computational thinking（计算思维）
- B.2 Programming（编程）
- B.3 Object-oriented programming（面向对象编程）
- B.4 Abstract Data Types（抽象数据类型，HL 专属要求）

学校依课程指南及本校安排选择 Java 或 Python 教学。学生还要学习指定的 pre-seen case study（预先发布的案例研究）。请使用相应考试届别的案例材料；不可假设旧届案例仍适用。

### 旧课程：最后一次评估为 2026

旧课程的外部考试采用不同结构，通常包括：

- **Paper 1：**核心课程内容
- **Paper 2：**学生所学的选修主题（options）
- **Paper 3：**仅 HL，围绕预先发布的案例研究

新课程取消旧选修卷和 Paper 3；案例研究进入新 Paper 1，并纳入 SL 与 HL 课程评估。新旧课程的主题编号、内容边界、考试题型和评分要求不能直接等同。旧卷可练习一般的读题、解释和时间管理，但不能当成 2027 课程的完整模拟卷。

| 项目 | 新课程（首次评估 2027） | 旧课程（最后评估 2026） |
|---|---|---|
| 课程组织 | Theme A 与 Theme B；统一核心课程，无旧式 options | Core topics 加 options |
| Paper 1 | Theme A 概念及案例研究 | 核心主题 |
| Paper 2 | Theme B：计算思维、编程与问题解决 | 所选 option |
| Paper 3 | 已取消 | 仅 HL；案例研究 |
| 案例研究 | Paper 1 内容，SL 与 HL 都学习 | 旧制 HL Paper 3 |
| HL 差异 | 增加 HL 深度及指定内容，例如 ADTs | 旧制 HL 扩展内容和独立 Paper 3 |

**注意：**旧课程的 option 名称或 topic 编号不应拿来推断新课程的覆盖范围。请以官方 2027 guide 的 syllabus statements 为准。

---

## 2. 官方及公开样题、历年材料和 GitHub 资源

### 官方资料优先级

1. **IB Computer Science 官方课程页与更新页：**[Computer science updates — IB](https://www.ibo.org/university-admission/latest-curriculum-updates/computer-science-updates/)
2. **课程与学科页面：**[IB Diploma Programme Computer Science](https://www.ibo.org/programmes/diploma-programme/curriculum/sciences/computer-science/)
3. 向学校 IB Coordinator 或 Computer Science 教师索取适用于你考试届别的**完整课程指南、subject brief、sample/specimen assessment materials、案例研究、markscheme 与教师通知**。部分详细评估材料需要学校通过 IB 的授权平台访问。

公开网页可能只显示概述，而不是完整的现行考试文件。不要仅凭第三方网站对考时、分数、题数、权重或计算器规则的摘要作决定；这些细节应对照本届官方 guide 和考生说明。

### GitHub 上可供练习的公开材料

以下是公开仓库中的学习资源，不代表 IB 官方文件；仓库作者、课程版本和内容准确性需自行核验。

- [SupersonicMan12 — 2025–2027 HL notes](https://github.com/SupersonicMan12/IB-DP-Programme-CS-HL-2025-2027-Notes)：包含按 Theme A/B 编排的笔记、A3 与 A4 练习题文件，以及 Paper 2 编程练习资源。适合按新课程主题复习；使用前仍应逐项对照官方 guide。
  - [A3 Practice Questions](https://github.com/SupersonicMan12/IB-DP-Programme-CS-HL-2025-2027-Notes/blob/main/A3%20Practice%20Questions.md)
  - [A4 Practice Questions](https://github.com/SupersonicMan12/IB-DP-Programme-CS-HL-2025-2027-Notes/blob/main/A4%20Practice%20Questions.md)
  - [Paper 2 question-generation skill and examples](https://github.com/SupersonicMan12/IB-DP-Programme-CS-HL-2025-2027-Notes/tree/main/Skills/ib-cs-paper2-hard-question)
- [ilia-kurgansky — unofficial question bank](https://github.com/ilia-kurgansky/CS-IB-Unofficial-Question-Bank)：题库与生成工具；很可能包含旧课程题目。可用于 topic practice，不应默认符合 2027 syllabus。
- [stss15 — IB Paper 2](https://github.com/stss15/ib-paper-2)：包含 Paper 2 练习/考试数据。检查题目版本、语言、完整性和评分资料。
- [drPinzonISAK — CS2022](https://github.com/drPinzonISAK/CS2022)：含旧课程资料及 specimen papers 文件，适合查看旧式考试材料，不是 2027 新课程的完整模拟考试。
- [wudithu08 — IBDP 2020 materials](https://github.com/wudithu08/icc-rdfz-ibdp-2020)：有旧课程 PastPapers 目录，课程版本较早。

**版权与学术诚信：**GitHub 上能访问不等于文件已获授权或属于官方公开样题。不要上传、再发布或把未授权的完整 IB 考卷当作自己的材料；按学校和 IB 的版权、学术诚信规定使用。个人 IA 项目也只能作为理解开发过程的参考，不应复制代码或文档。

---

## 3. Paper 1、Paper 2 及 SL/HL 对比

### Paper 1：概念与案例研究

Paper 1 的核心复习范围是 **Theme A**，并包括指定的 **case study**。答题时通常需要把概念应用到问题情境，而不只是背术语。重点准备：

- 计算机系统、硬件与相关基础概念
- 网络及数据传输概念
- 数据库概念、设计及相关应用
- 机器学习基本思想、方法、用途及局限
- 将课程概念应用到案例研究所给的背景、技术和问题
- 对情境中的技术选择、影响、限制或风险作有依据的解释

案例研究不是只背文章内容。要能从材料提取事实、解释技术如何工作、应用课程概念，并讨论可能的影响或限制。不要把 Theme B 的编程试题默认归入 Paper 1；算法与程序构造主要属于 Paper 2，但具体情境可能跨主题。

### Paper 2：计算思维与编程问题解决

Paper 2 的核心范围是 **Theme B**。重点准备：

- 将问题分解、抽象和描述为可计算步骤
- 跟踪算法、解释变量状态和控制流程
- 设计、阅读、补全或解释程序
- 选择合适的数据结构与程序结构
- 测试、调试、说明边界情况
- 面向对象编程
- HL 的指定抽象数据类型内容
- 对算法效率作课程要求范围内的分析

必须熟悉学校实际使用的 Java 或 Python 表达方式；同时要理解算法本身，而不是只会依赖某种语言的快捷函数。

### SL 与 HL

| 方面 | SL | HL |
|---|---|---|
| 课程主题 | 学习共同课程核心 | 学习共同核心并达到 HL 要求的额外深度/内容 |
| Theme A 与案例 | 复习并作情境应用 | 同样要掌握，通常要求更深入的解释与分析 |
| 编程与���题解决 | 按 SL 要求作答 | 需处理更高深度或复杂度的要求 |
| ADTs | 按 guide 的 SL/HL 划分 | B4.1 Abstract Data Types 为 HL 内容 |
| 考试资料 | 使用 SL 对应材料 | 使用 HL 对应材料，不能仅用 SL 练习代替 |

SL/HL 的准确考时、分值、题数、权重及各部分要求会体现在对应考试届别的官方文件中；本表只概括课程范围差异，不替代考试参数表。

---

## 4. 题型、命令词、作答和评分要求

### 常见任务形式

课程考试可能要求考生：

- 定义、描述或解释术语和过程
- 比较两种方法或技术
- 使用题目给出的资料、数据、代码片段或案例情境作答
- 追踪算法或说明程序执行结果
- 为给定问题提出并论证技术方案
- 讨论技术的优势、局限、影响或风险
- Paper 2 中构造、修改、分析或调试程序

实际格式与任务组合以正式 specimen/sample papers 为准，不要从旧题直接推断新 Paper 的固定题数。

### 常见 command terms（命令词）

| 命令词 | 作答时要做什么 |
|---|---|
| **Define** | 给出准确、简洁的定义。 |
| **State** | 给出所需事实或答案，通常不需展开论证。 |
| **Identify** | 从材料中指出或选出对应项目。 |
| **Outline** | 简要列出主要特征或步骤。 |
| **Describe** | 清楚说明特征、过程或发生了什么。 |
| **Explain** | 给出原因或机制，说明“为什么/如何”，并把因果关系写清楚。 |
| **Compare** | 说明相同点和差异；不要只分别描述。 |
| **Discuss** | 提供有组织的论点，考虑不同方面，最后作出有依据的判断。 |
| **Evaluate** | 根据明确标准权衡优点与缺点，并给出结论。 |
| **Construct / Design** | 按题目约束建立可行方案、算法、数据结构或程序。 |

命令词的正式含义以 IB 通用 command terms 表及学科指南为准。不同题目会对答案范围、依据和深度作具体限定。

### 答题与评分实用规则

- **按分值控制细节：**每个得分点写清楚，不要把多个独立理由挤成一句含糊表述。
- **准确使用术语：**解释概念时先写关键术语，再说明它在当前情境中的作用。
- **结合题目材料：**案例题要引用题目给出的具体事实，而不是写与案例无关的通用段落。
- **给出因果链：**解释题用“特征/机制 → 结果 → 对该情境的意义”组织答案。
- **比较要成对：**直接写出同一维度上的异同，避免两个互不相关的描述。
- **讨论/评价要有判断：**说明标准、权衡和结论；只列优缺点通常不足以完成 evaluate。
- **编程题要遵守指定语言和限制：**检查变量初始化、循环边界、返回值、输入假设和边界情况；不要假定未授权的库函数可用。
- **检查题目中的限制：**例如指定算法、数据类型、输出格式、效率要求、是否必须使用 OOP。
- **使用官方 markscheme 学习：**理解每个 mark point 需要的证据。练习后先独立作答，再对照 markscheme；不要把评分答案当作需要背诵的唯一措辞。
- **考试纪律与材料：**仅使用考生说明明确允许的设备、计算器和材料；不确定时提前向学校协调员确认。

---

## 5. 备考策略与原创练习建议

### 分阶段复习

1. **确认考纲版本：**确认考试月份、SL/HL、学校授课语言和官方 guide 版本。
2. **建立清单：**按 A.1–A.4、B.1–B.4 列出每项 syllabus statement，标记“掌握 / 需练习 / 未学”。
3. **先学概念，再做应用：**每个 Theme A 主题至少准备术语卡、过程解释、优缺点/影响和一道情境应用题。
4. **独立学习案例：**标注案例事实、技术概念、利益相关者、假设、限制、风险和可讨论的影响；每周尝试回答开放题。
5. **定期练 Paper 2：**用学校指定语言手写/键入小程序，练 trace table、测试数据、边界条件和调试解释。
6. **限时模拟与复盘：**只使用对应大纲、层级和考试届别的完整材料。记录失分原因：概念错误、读题偏差、论证不足、程序错误或时间分配。
7. **核对评分标准：**每次练习后用官方 markscheme 或教师反馈检查答案，积累“错误类型—改进动作”清单。

### 自编练习题示例（非 IB 官方真题）

以下只是练习方向，不是官方样题、完整试卷或官方 markscheme。

**Paper 1 — Theme A 情境题**

1. 一所学校准备将学生学习记录从多张电子表格迁移到关系型数据库。指出两个采用数据库系统的优点，并解释其中一个优点如何减少资料更新问题。
2. 某组织使用机器学习模型筛选申请。描述训练数据中的偏差可能如何影响输出，并提出一种可用于发现或减轻该问题的做法。
3. 案例研究中的远程传感设备需要把数据发送到中央服务。根据题目提供的网络条件，解释一种可能的网络限制，并说明它对系统设计的影响。

**Paper 2 — Theme B 编程/算法题**

4. 给定一个整数列表，写一个方法计算满足指定条件的元素数量。说明空列表和只有一个元素时的处理，并给出一组测试数据。
5. 给定题目定义的 `Student` 类与一组对象，追踪方法调用后的属性变化；随后构造一个方法，按题目规定条件返回匹配对象，并说明其时间复杂度。

做练习时自行补全输入范围、输出规范和限制；考试答题则必须严格遵循原题给出的接口、语言和条件。

### 面试或教学准备中的使用建议

- 用 Theme A 练习展示你如何把抽象概念连接到真实系统、案例和影响。
- 用 Theme B 练习展示你怎样引导学生追踪、测试和调试，而不是直接给代码答案。
- 对案例研究问题，示范如何从材料中找证据、联系 syllabus、形成有条件的结论。
- 明确说明哪些资料是官方要求、哪些是个人练习或第三方资源。

---

## 核验清单

在把本文用于正式教学或考试规划前，请通过学校 IB Coordinator 核验：

- 你所在考试届别的最新 Computer Science guide 和 subject brief
- SL/HL 对应的考时、分值、权重、题目数量和必答/选答要求
- 最新案例研究及其允许的预习材料
- specimen/sample papers 和 markschemes 的适用版本
- 指定编程语言、设备、计算器和其他考试规则

## 来源

- [IB Computer science updates](https://www.ibo.org/university-admission/latest-curriculum-updates/computer-science-updates/)
- [IB Diploma Programme Computer Science](https://www.ibo.org/programmes/diploma-programme/curriculum/sciences/computer-science/)
- [SupersonicMan12 2025–2027 course notes and practice resources](https://github.com/SupersonicMan12/IB-DP-Programme-CS-HL-2025-2027-Notes)
- [Unofficial IB CS Question Bank](https://github.com/ilia-kurgansky/CS-IB-Unofficial-Question-Bank)
- [IB Paper 2 question collection](https://github.com/stss15/ib-paper-2)
- [Older 2022 specimen/teaching materials](https://github.com/drPinzonISAK/CS2022)
- [Older IBDP past-paper archive](https://github.com/wudithu08/icc-rdfz-ibdp-2020)
