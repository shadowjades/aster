# Aster · 研迹科研管理台

<p align="center">
  <strong>把项目、实验、论文和每周计划，放进一条清晰、可回溯的科研工作流。</strong><br />
  <em>Keep research projects, experiments, papers, and weekly plans in one clear, traceable workflow.</em>
</p>

<p align="center">
  <a href="#中文介绍">中文</a> · <a href="#english">English</a> ·
  <a href="https://github.com/shadowjades/aster/releases">下载与版本 Releases</a>
</p>

> **Aster 是什么？** Aster（研迹科研管理台）是一款面向不同学科研究者的本地科研管理桌面工具。它帮助你记录研究过程、整理论文阅读、比较实验结果并回顾每周进展。科研事实和结论由你记录；AI 仅在你主动调用时提供辅助。
>
> **What is Aster?** Aster is a local-first desktop workspace for researchers across disciplines. It helps you document research, organize papers, compare experiments, and review weekly progress. You remain the author of your research record; AI only assists when you choose to use it.

---

## 中文介绍

### 为什么做 Aster

科研信息往往散落在实验日志、文件夹、PDF、表格和待办清单里。时间久了，很难回答几个简单的问题：某个项目做过哪些尝试？结果为什么变化？论文读到什么程度？下一步应该验证什么？

Aster 把这些信息组织成相互关联的工作流：项目承载多次实验记录，论文可以安排到每周阅读任务，个人规划聚合近期行动与历史总结。目标是让研究过程更容易查找、比较、复盘和分享。

### 主要功能

#### 1. 项目与实验记录本

- 按“项目 → 多次实验记录”组织工作，不会把一个项目限制成一条记录。
- 项目可记录类型、状态、开始时间、可选结束时间、最终成果、代码仓库和论文链接。
- 每次实验记录可写遇到的问题、采取的解法、当前效果、个人结论、猜想、下一步计划和时间线过程。
- 每条记录可添加结果材料，并填写项目自定义的评估项；结果项支持数值、文字、链接等研究内容，不限定某个学科的固定指标。
- 编辑内容由你掌控；保存前可修改或取消，AI 生成的内容不会自动覆盖原始记录。

#### 2. 实验结果比较与项目分析

- 在项目内勾选多条实验记录，查看所选记录的结果和指标。
- 汇总自定义数值指标，查看跨记录变化趋势。
- 在项目分析中查看记录结论和结果图片，梳理哪些方法变化伴随哪些结果变化。
- 可让 AI 针对选中的记录或整个项目生成一份分析草稿，人工修改后再决定是否保留。

#### 3. 论文阅读管理

- 拖入或选择 PDF，将论文整理进本地论文库。
- 管理未阅读、阅读中、已阅读状态；可建立自定义文件夹、搜索和批量归类。
- 写下对论文问题、方法、优势、实验依据和局限的理解，并关联到研究项目。
- 每篇论文可选择开启 AI 监督。监督模式可根据可提取的正文生成理解检验题；提交回答后，AI 给出反馈。未通过理解检查的论文不会被计为已完成阅读任务。
- 支持把论文安排到本周计划、设置每周阅读目标，并在通过理解检查后核销任务。

#### 4. 个人规划与每周回顾

- 维护当前研究主线、本周行动、截止日期和任务完成状态。
- 使用快捷任务和每周论文目标预设，减少重复填写。
- 查看实验、论文和任务的历史统计与活跃热力图。
- 生成本周复盘草稿，检查后保存到历史总结。
- 导出本周科研总结并打印或保存为 PDF，便于个人复盘或分享给导师查看。

#### 5. 按需使用 AI

在设置中配置 DeepSeek、豆包、OpenAI/GPT、Grok，或其他兼容 OpenAI 接口的服务。AI 可帮助整理单条实验、讨论猜想、比较项目记录、检查论文理解和起草周总结。

AI 不会在后台自动读取或上传资料。只有点击对应 AI 功能时，应用才会把该功能所需的文本内容发送到你配置的模型服务。API Key 不会写入工作区备份；模型服务商的数据处理和计费规则由对应服务商决定。

#### 6. 本地数据与备份

- Aster 是本地桌面工具，不要求注册 Aster 账户，也不依赖 Aster 云服务器。
- 项目、论文和计划保存在当前电脑上的应用数据中，附件保存在本机浏览器存储中。
- 可导出工作区 JSON 备份；备份包括附件，不包括 API Key。换电脑时，在新设备安装后使用“恢复工作区备份”迁入资料。
- 建议定期导出备份，并将备份文件保存在安全位置。

### 典型工作流

1. 创建一个项目，写明研究类型、目标和项目评估项。
2. 每完成一轮实验，新增一条实验记录，写清问题、方法、结果、结论与下一步。
3. 需要复盘时，勾选多条记录查看指标、趋势和结果材料。
4. 将论文加入阅读计划；开启监督时，先写自己的理解，再完成 AI 生成的检验。
5. 每周整理行动和研究进展，生成复盘并导出 PDF。
6. 定期导出工作区备份，确保记录可迁移、可恢复。

### 下载与安装

请前往 [GitHub Releases](https://github.com/shadowjades/aster/releases) 查看安装包和版本说明。当前发布目标为 Windows 64 位（x64/AMD64）。首次安装时下载英文命名的 Windows 安装程序，运行后按安装向导完成安装。

### 当前范围与说明

- 当前版本面向 Windows 桌面使用，采用本地单用户工作区；暂不提供云同步或多人协作。
- 论文导入面向文本型 PDF。扫描版 PDF 的 OCR 识别能力有限，需人工补充或确认正文。
- 每周 PDF 通过报告页面打印/保存生成；正式分享前请自行检查内容。
- 数据目录直接剪切迁移的完整工作流尚未接通。目前跨设备迁移请使用“导出工作区备份 → 新电脑安装 → 恢复工作区备份”。
- AI 功能需要用户自行配置模型 API。模型服务的费用、可用额度及隐私策略以服务商说明为准。

### 仓库内容

本仓库用于发布 Aster 安装包、版本说明和使用信息，**不包含应用源代码**。安装包会作为 GitHub Release 附件提供，版本更新说明也会在对应 Release 页面发布。

### 反馈与建议

欢迎通过 [GitHub Issues](https://github.com/shadowjades/aster/issues) 提交问题、使用反馈或功能建议。反馈时请描述操作步骤、预期结果和实际结果；请勿提交 API Key、私人论文文件或包含个人信息的工作区备份。

---

## English

### Why Aster

Research work is often scattered across lab notes, folders, PDFs, spreadsheets, and task lists. Over time, it becomes difficult to answer basic questions: What have I tried in this project? Why did the results change? How far have I understood a paper? What should I test next?

Aster brings these pieces into one connected workflow. A project contains multiple experiment records, papers can be scheduled as weekly reading tasks, and personal planning brings current actions and past reviews together. The goal is to make research easier to find, compare, review, and share.

### What you can do

#### 1. Projects and experiment logbook

- Organize work as **projects → multiple experiment records**, so a project is not limited to one entry.
- Record project type, status, start date, optional end date, outcomes, repository links, and paper links.
- For each experiment, document the problem, approach, observed effect, your conclusion, hypothesis, next step, and timeline.
- Attach result materials and define project-specific evaluation fields. Results can be numeric, written, linked, or otherwise relevant to the research; no discipline-specific metric is imposed.
- You control edits and saves. AI output does not automatically replace your original notes.

#### 2. Experiment comparison and project analysis

- Select multiple experiment records within a project and review their results and metrics together.
- Summarize custom numeric metrics and inspect changes across records.
- Review conclusions and result images in the project analysis view to understand which method changes correspond to which outcomes.
- Ask AI to draft an analysis of selected records or the whole project, then edit and decide whether to keep it.

#### 3. Paper reading management

- Drag and drop or select PDF files to add papers to the local library.
- Track unread, reading, and read states; create folders, search, and organize papers in batches.
- Write your understanding of a paper’s problem, method, advantages, evidence, and limitations, and link it to a research project.
- Enable AI supervision for individual papers. The app can generate comprehension questions from extractable paper text. After you submit your answers, AI provides feedback. A paper that has not passed the comprehension check does not count as a completed weekly reading task.
- Schedule papers for the current week, set a weekly reading target, and check off a task after passing the comprehension check.

#### 4. Planning and weekly review

- Maintain a research focus, weekly actions, due dates, and task completion states.
- Use quick task templates and weekly paper-goal presets to reduce repetitive entry.
- Review historical activity and a heatmap for experiments, papers, and tasks.
- Generate a weekly review draft and save reviewed summaries to history.
- Export a weekly research summary by printing or saving it as a PDF, for personal review or sharing with an advisor.

#### 5. AI when you ask for it

Configure DeepSeek, Doubao, OpenAI/GPT, Grok, or another OpenAI-compatible service in Settings. AI can help summarize an experiment, discuss a hypothesis, compare project records, check paper comprehension, and draft a weekly review.

AI does not read or upload your research in the background. Text required for a specific task is sent to the model service you configured only after you click the related AI action. API keys are excluded from workspace backups. Data handling and billing are determined by the selected provider.

#### 6. Local data and backups

- Aster is a local desktop tool. It does not require an Aster account or depend on an Aster cloud server.
- Projects, papers, and plans are kept in the current computer’s application data; attachments use local browser storage.
- Export a JSON workspace backup to include your records and attachments. API keys are excluded. To move to another computer, install Aster there and restore the backup.
- Export backups regularly and keep them in a safe location.

### Suggested workflow

1. Create a project and define its research type, goal, and evaluation fields.
2. After each experiment, add a new record documenting the problem, method, results, conclusion, and next step.
3. Select records when you need to review metrics, trends, and result materials side by side.
4. Add papers to a reading plan. With supervision enabled, write your own understanding before completing the AI-generated assessment.
5. Review your weekly activity, generate a summary, and export it as a PDF.
6. Export workspace backups regularly so your records can be moved and restored.

### Download and installation

Visit [GitHub Releases](https://github.com/shadowjades/aster/releases) for installers and release notes. The current release target is Windows 64-bit (x64/AMD64). Download the Windows installer and follow its setup wizard.

### Current scope

- The current version targets the Windows desktop and a single local user. Cloud sync and multi-user collaboration are not currently provided.
- Paper import is designed for text-based PDFs. OCR support for scanned PDFs is limited; verify or provide paper text manually when needed.
- Weekly PDF export is produced through the report page’s print/save flow. Review the document before sharing.
- Directly moving the data directory between computers is not yet available. For now, use **Export workspace backup → Install on the new computer → Restore workspace backup**.
- AI features require your own model API configuration. Provider fees, quotas, and privacy terms are set by the provider.

### Repository contents

This repository distributes Aster installers, release notes, and usage information. **It does not contain the application source code.** Installers are attached to GitHub Releases, with version-specific changes documented on each release page.

### Feedback

Use [GitHub Issues](https://github.com/shadowjades/aster/issues) for bug reports, feedback, or feature requests. Include the steps to reproduce, expected behavior, and actual behavior. Do not post API keys, private papers, or workspace backups containing personal information.
