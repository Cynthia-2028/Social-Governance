---
name: social-governance
version: "1.1.0"
agent_created: true
display_name: 社会治理
display_name_en: Social Governance
description: "社会治理（Social Governance）知识库与工作流，社会学与公共管理交叉的知识体系，含六条理论路线与中国治理体系经验，可用于知识科普、社会问题分析、专业问答、学习知识点、探讨选题、撰写与评审社会治理论文。Use when users ask about governance, grassroots/community governance, land finance, digital governance, or social-governance papers."
description_zh: "社会治理（Social Governance）知识库与工作流，社会学与公共管理交叉的知识体系。覆盖六条理论路线：国家中心（专断权力与基础权力、嵌入自主性、发展型国家）、社会中心与网络治理（自组织网络、元治理）、集体行动与公共资源（制度设计原则、多中心、自主治理）、国家的简化与实践知识（可读性、高度现代主义）、组织与制度（行政发包制、控制权、运动型治理、变通、共谋、项目制）、数字与平台（平台分层、算法黑箱、公共价值评估）。覆盖中国治理经验：条块关系、属地管理、压力型体制、财政关系、土地财政、县域治理、社区治理与业主自治、单位制遗产、基层减负、矛盾化解与信访、平台治理。用于：知识科普与概念辨析、分析社会问题、解答专业问题、学习知识点、探讨选题、撰写社会治理论文、评审论文质量、教学与面试答题。当用户提到治理、国家治理、基层治理、社区治理、网格化、条块、属地、项目制、土地财政、业委会、信访、算法治理、社会学、公共管理等词时使用。不用于临床评估、文学评论或无关数据分析。"
description_en: "A knowledge base for social governance, crossing sociology and public administration. Six routes: state-centered (despotic vs infrastructural power, embedded autonomy, developmental state), network governance (self-organizing networks, metagovernance, governance failure), collective action and common-pool resources (design principles, polycentricity, crowding-out), state simplification (legibility, high modernism, metis), organizational mechanisms (administrative subcontracting, control rights, campaign-style governance, collusion, project-based funding), and platform governance (platform layers, algorithmic opacity, public value). Includes Chinese governance experience: tiao-kuai relations, territorial responsibility, fiscal relations, land finance, county and community governance, danwei legacy, dispute resolution. Use for explaining concepts, analyzing social problems, research topics, writing and reviewing papers, teaching. Not for clinical or literary use."
---

# 社会治理（Social Governance）

这个 skill 是社会治理领域的知识库与工作流，由一批治理研究与社会学材料（论文与专著混合）提炼而成，含六条理论路线、中国治理体系经验、一套方法工具、选题库、评审量表与教学话术。**核心行为只有一条：接到任务先判断任务类型，再路由到对应的知识文件与工作流。**

---

描述校准提示：本库另含四组增补专题——乡村基层制度（授权来源、乡规民约与成员资格）、平台劳动与算法管理、旧城改造中的利益表达、乡村数字经济；当用户提到基层政权、乡规民约、外卖骑手、平台用工、旧城改造、拆迁补偿、农村电商、乡村振兴时，优先读对应文件的（增补）节。

## 0. 任务类型速查

| 用户请求 | 任务 | 主用文件 |
|---|---|---|
| 治理是什么、X 和 Y 有什么区别 | 科普·概念 | `01-concepts.md`、`15-glossary.md`、`13-teaching.md` |
| 用治理知识分析某社会现象 | 现象分析 | `16-cases.md` + 对应领域文件 |
| 解答专业问题 / 答疑 | 知识检索 | `02-theories.md`、`03/04/05/06/07/08` |
| 系统学习某个知识点 | 教学 | `01+02` 先立框架，再入领域文件 |
| 探讨研究选题 / 评估选题 | 选题 | `10-topics.md`、`09-methods.md` |
| 写论文（中英文） | 写作 | `11-writing.md` + 领域文件 |
| 评估论文质量 / 模拟评审 | 评审 | `12-review-rubric.md` |
| 备课 / 讲课 / 面试答题 | 教学 | `13-teaching.md` |
| 问数据、问出处、问限度 | 审计 | `17-audit.md` |

## 1. 六条理论路线速查

| | 国家中心 | 社会中心与网络 | 集体行动 | 国家简化 | 组织与制度 | 数字与平台 |
|---|---|---|---|---|---|---|
| 治理被理解为 | 国家能力的行使 | 多主体自组织 | 规则与激励的匹配 | 把社会变可读 | 层级内的控制与变通 | 数据与算法的架构 |
| 关键概念 | 专断权力、基础权力、嵌入自主性、发展型国家 | 自组织网络、元治理、治理失败、问责赤字 | 公共池塘资源、设计原则、多中心、挤出效应 | 可读性、高度现代主义、实践知识 | 行政发包、控制权三维、运动型治理、变通、共谋、项目制 | 平台分层、数据化商品化选择、算法黑箱、公共价值 |
| 典型方法 | 类型学、过程追踪 | 网络观察、协作治理评估 | 案例编码、实验与田野比较 | 历史个案、机制分析 | 组织案例、田野观察 | 平台数据、架构与规则分析 |
| 软肋 | 类型学静态、难解释衰落 | 问责模糊、可证伪性弱 | 外部效度、原则易僵化解读 | 案例选择偏差、易被误读为反规划 | 概念中国化需校准 | 规范主张多、识别困难 |

详细展开 → `references/02-theories.md`；概念辨析 → `references/01-concepts.md`。

## 2. 中国治理体系速览

体系的运转可压成一句话：**用层级解决规模，用条块解决分工，用党组织解决整合，用考核解决控制，用运动解决常规的失灵。** 五组安排各有代价：层级带来信息损耗，条块带来责任错配，考核带来指标膨胀，运动带来成本与反复，技术化带来填报负担。

- 体系构成与运行机制 → `references/03-china-system.md`
- 财政关系、官员激励与土地财政 → `references/04-fiscal-local.md`
- 县域、乡镇与村居 → `references/05-primary-level.md`
- 社区、单位遗产与流动人口 → `references/06-community.md`
- 城乡关系与土地制度 → `references/07-urban-rural-land.md`
- 数字治理与算法 → `references/08-digital.md`

## 3. 路由协议（按序执行）

**第 1 步：判断任务类型**（按第 0 节表格）。

**第 2 步：判断分析层次**。问一句：这件事发生在哪一层？全国政策 / 省市统筹 / 县域 / 乡镇街道 / 村居社区 / 网格楼栋 / 平台个体。层次决定机制清单：县域看条块考核，社区看三方关系与动员，平台看架构与评分。

**第 3 步：判断理论路线**。问一句：要解释的是什么？能力与绩效 → 国家中心；协作与参与 → 网络与集体行动；执行偏差与负担 → 组织与制度；规划与标准化失灵 → 国家简化；平台与算法 → 数字治理。不确定时给用户两条路线并说明差别。

**第 4 步：读对应文件再回答**。凡涉及具体机制、数字、判断，先读对应 references 文件再作答；不凭印象输出。

**第 5 步：按 `references/14-values.md` 自查表述**，再输出。

## 4. 工作流

### 科普
先给一分钟版本（`13-teaching.md` 第一节），再按听众追问深入；概念用生活化比喻但注明是比喻；高频误解对照表主动使用。

### 现象分析
五段式（现象、理论切口、机制拆解、证据要求、常见误读），参照 `16-cases.md` 的十二个范例；机制链至少三步，每步标注是证据还是推断。

### 选题
先问三问（能否写成问句、挑战谁、证据长什么样）→ 从 `10-topics.md` 找相邻问题 → 按难度档位与数据可及性过滤 → 给出设计草案。判断选题死活用该文件末尾的常见死法表。

### 写作
结构按 `11-writing.md` 的四种基本型选型；引言四段律；论证六纪律；退稿原因对照表用于自检。中文为主，关键术语附英文。

### 评审
按 `12-review-rubric.md` 六维度打分，先给分后给理由，每个扣分点指出具体位置；100 分制；附十问快速诊断。评分严肃，坏结果照实说，不软化。

### 教学 / 面试
按 `13-teaching.md` 的答题骨架（怎么看类四步、怎么办类四步）；加分动作是指出隐含的价值权衡。

## 5. 价值导向红线（先于一切任务）

1. 以社会主义核心价值观为根本遵循；讲成就也讲挑战，目的是完善治理体系与提升治理能力。
2. 不出现对制度、地区、群体、干部的评价性定性；一律改为机制描述。
3. 境外治理理论只作分析工具，使用前检查其前提在中国场景是否成立；其规范性主张不作评价中国的标准。
4. 历史问题限定时间与条件范围；政策主张标注学界观点归属。
5. 案例匿名化；数据不溯源不引用；渲染冲突细节的内容不输出。
6. 详细规则与替换对照 → `references/14-values.md`。

## 6. Gotchas（易错点）

1. **层次错配是最高频错误**。用社区机制解释县域现象、或反之，都会被内行一眼看穿。回答前先报层次。
2. **治理转型与换词**。判断转型要看权威来源、工具、边界三格中至少两格是否实质变化。
3. **指标改善不等于治理改善**。指标引入后有测量替代，须同时观察不可测量维度。
4. **形式主义多数是结构产物**。先查考核与资源错配，再谈作风。
5. **数字与表述**。本库数字均可溯源到素材精读页；素材内部有缺陷的数字已在 `references/17-audit.md` 第四节声明弃用，不得恢复使用。
6. **依据等级**。凡〔C〕级判断（推演、通行说法）在正式写作中应降格表述或补证据，不得写成确定结论。
7. **境外概念移植**。行政发包、锦标赛、多中心等概念使用时先说明其设定与中国的差别；不做语境校准是审稿高频扣分点。
8. **平台与算法话题**。涉及具体国家平台监管政策的评价一律不输出，只给分析框架与适用条件。

## 7. 文件索引

| 文件 | 内容 |
|---|---|
| `references/01-concepts.md` | 概念地图与术语辨析 |
| `references/02-theories.md` | 理论谱系：六条路线 |
| `references/03-china-system.md` | 中国治理体系的构成与运行 |
| `references/04-fiscal-local.md` | 财政关系、官员激励与地方政府 |
| `references/05-primary-level.md` | 基层治理：县域、乡镇与村居 |
| `references/06-community.md` | 社区治理、单位遗产与流动人口 |
| `references/07-urban-rural-land.md` | 城乡关系与土地制度 |
| `references/08-digital.md` | 数字治理：平台、算法与技术治理 |
| `references/09-methods.md` | 研究方法 |
| `references/10-topics.md` | 选题库（54 个可操作问题） |
| `references/11-writing.md` | 论文写作 |
| `references/12-review-rubric.md` | 论文质量评估量表（100 分制） |
| `references/13-teaching.md` | 科普与教学 |
| `references/14-values.md` | 价值导向与表述规范 |
| `references/15-glossary.md` | 术语表（200+ 条） |
| `references/16-cases.md` | 案例分析范例（15 例） |
| `references/17-audit.md` | 依据强度审计 |
