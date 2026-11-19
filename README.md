# KOL 种草方案推导

一个面向品牌策划、咨询团队、agency 与品牌方的中文 Agent Skill。

把品牌 brief、消费者观察和 Core Idea，推导成有依据的 KOL 种草方案：每页放什么、为什么需要这些内容、分别交给谁，以及怎样筛选和评估。

**品牌任务 → 平台观察 → 消费者洞察 → 产品回应 → 沟通主张 → 创意联想 → Core Idea → 内容任务 → 达人分工 → 层级与预算 → 投放验证**

## 能做什么

- 给出可伸缩的 24 页方案母版，每页说明问题、结构、依据与下一步。
- 解释创意如何变成共鸣、演绎、科普、体验、比较和答疑内容。
- 区分达人职责、受众特征与传播规模，设计层级组合。
- 制定选号条件、推荐理由、名单字段和可调整评分方式。
- 把方案转成单达人 brief，并设计发布、测试与复盘。
- 检查已有方案中洞察、创意、内容和达人安排之间的逻辑。

技能可独立使用，也可以与 [Core Idea 创意推导](https://github.com/elisehuang26/core-idea-development) 配合。文件生成、平台数据与账号检索取决于你所用工具的能力；技能本身提供策略方法和交付结构。

## 安装

在使用默认个人技能目录、且目标文件夹尚未存在时：

```bash
git clone https://github.com/elisehuang26/kol-seeding-proposal.git "$HOME/.codex/skills/kol-seeding-proposal"
```

如果配置了其他技能目录，将仓库放到对应目录。也可以下载仓库，将包含 `SKILL.md` 的文件夹放入支持该格式的工具的技能目录。

## 使用示例

整理通用提案方法：

```text
使用 $kol-seeding-proposal，整理一份 KOL 种草方案的写法。
请逐页解释结构、洞察怎么做、达人怎么分类和筛选，
以及每类达人对应 Core Idea 的哪一部分。
以通用方法为主，用少量示意解释关键跳转。
```

根据真实 brief 写方案：

```text
使用 $kol-seeding-proposal，根据附件为【品牌／SKU】推导种草方案。
主要平台是【平台】，目标是【任务】，周期与预算是【信息】。
请区分资料事实、洞察假设和创意提案，
给出逐页结构、创意到达人分工、选号条件与验证办法。
```

已有创意，需要安排达人：

```text
使用 $kol-seeding-proposal，我已有的 Core Idea 是【想法】。
请拆解消费者还需要哪些答案，分别交给哪些达人，
说明每类内容的主要任务、共同记忆点和筛选依据。
缺少实际账号数据时先给条件，不虚构名单和业绩。
```

## 文件

| 文件 | 用途 |
| --- | --- |
| [SKILL.md](SKILL.md) | 核心推导、证据处理与交付方式 |
| [agents/openai.yaml](agents/openai.yaml) | 显示名称、简介与调用提示 |
| [references/proposal-pages.md](references/proposal-pages.md) | 24 页可伸缩方案母版 |
| [references/creator-selection.md](references/creator-selection.md) | 达人角色、层级、筛选、评分与预算 |
| [references/creator-brief-and-measurement.md](references/creator-brief-and-measurement.md) | 单达人任务卡、内容示意、执行与评估 |
| [references/worked-examples.md](references/worked-examples.md) | 虚构护肤与奶粉示例，演示创意到达人分工 |

## 使用边界

24 页、粉丝区间、评分权重均为可调整示例。历史报告不能直接代替当前平台观察；产品主张需要对应适用 SKU 的资料。技能不包含自动联系达人、采购、投放或公开客户资料的授权。

仓库只包含通用方法与虚构示例，没有客户原始 brief、内部数据、真实报价或功效承诺。分享案例时请提供来源和验证程度，并使用有权公开的材料。

## 贡献与许可

欢迎通过 Issue 或 Pull Request 提供方法改进和使用反馈。原创内容采用 [MIT License](LICENSE)。
