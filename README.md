<p align="center">
  <img src="assets/banner.svg" width="100%" alt="曾凌峰 zlfuu531 — LLM Post-Training · Data Synthesis · Evaluation &amp; Benchmarking">
</p>

<p align="center">
  <a href="mailto:zenglingfeng531@163.com"><img src="https://img.shields.io/badge/Email-zenglingfeng531%40163.com-0b6bcb?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/zlfuu531"><img src="https://img.shields.io/badge/GitHub-zlfuu531-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="https://scholar.google.com/citations?user=b69Frz4AAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-100%2B_citations-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1200&color=8B949E&center=true&vCenter=true&width=640&lines=SFT+%C2%B7+DPO+%C2%B7+GRPO+post-training;multimodal+data+synthesis+%26+benchmark+construction;LLM+agents+%26+reward+models+for+finance" alt="Typing SVG"></a>
</p>

<p align="center">
  <b>上海财经大学 · 应用统计硕士 · 2027.06 毕业</b> ｜
  <b>求职方向：LLM 算法 / 后训练 / 数据与评测 / Agent / 多模态 / 金融 AI</b>
</p>

> **一句话介绍**：我做的事情是把“模型为什么不行”变成可复现的评测与训练闭环——从数据合成、SFT/DPO/GRPO 后训练，到 Agent、多模态与安全评测，再到业务落地和工程化交付。

---

## 🧭 面试官 10 秒版

| 方向 | 代表作 | 关键结果 |
|:---|:---|:---|
| **多模态 / 金融评测** | **[VisFinEval](https://github.com/SUFE-AIFLM-Lab/VisFinEval)**、**[UniFinEval](https://github.com/aifinlab/UniFinEval)** | EMNLP 2025 / EMNLP 2026；15k+ / 3k+ QA；跨文本·图像·视频 |
| **Agent 评测** | **[FinGAIA](https://github.com/SUFE-AIFLM-Lab/FinGAIA)**、ClawBench | 407 个真实业务任务；40+ 长程端到端 Agent 任务；纳入行业团体标准白皮书 |
| **模型后训练** | **[Fin-R1](https://github.com/SUFE-AIFLM-Lab/Fin-R1)**、GRM、信用 LLM | Fin-R1 平均 75.2、排名第 2；GRM 58 → 94；信用 AI 3.79 → 6.09/10 |
| **安全 / 鲁棒性** | **[GEO-Poison-Bench](https://github.com/zlfuu531/GEO-Poison-Bench)** | 一作；9 攻击类型 × 18 行业；1,578 题 × 24 模型 |
| **工程落地** | QualEval 评测平台、采购验收、质检 Agent | 单月 27 个评测任务；3000 题后训练数据验收；758 份盲测 63% 偏好 |

---

## 🎓 教育背景

| 学历 | 学校 / 学院 | 专业 | 时间 |
|:---|:---|:---|:---|
| 硕士 | 上海财经大学 · 统计与数据科学学院 | 应用统计（专业硕士） | 2024.09 – 2027.06 |
| 学士 | 上海财经大学 · 统计与数据科学学院 | 经济统计学 | 2020.09 – 2024.06 |

---

## 💼 实习经历

### 🏢 阿里巴巴集团 · 平台技术 · AI Data 数据合成团队
**数据算法实习生** ｜ 2026.03 – 2026.08

- 🕹️ **Agent 数据与评测**：主导金融 **ClawBench**，设计 40+ 道端到端长程 Agent 任务，覆盖 7 类金融产出物；参与构建 200 道金融财务真实场景 Agent 评测集。
- 🖼️ **金融复杂多模态评测**：构建 400 道评测题，设计模型攻题 L1–L4 筛选、专家标注标准和 pass@8 复筛，完成 9 个前沿模型评测；头部模型 pass@2 仅 54%，平均每题约 4.29/9 个模型答对。
- ⚙️ **评测 / 质检平台**：独立搭建本地化评测质检一体化平台，支持 QA、多模态、Rubric、Agent/ClawBench 多维裁判；7 月累计运行 27 个任务。
- 🧪 **一作研究 [GEO-Poison-Bench](https://github.com/zlfuu531/GEO-Poison-Bench)**：9 种攻击类型 × 18 个行业，1,578 题 × 24 模型评测榜；仅少数强对齐模型持续抵抗投毒。
- 📄 **共一研究 [AgSynth](https://github.com/Yaxuan7690/AgSynth)**：多智能体反向合成多模态数学推理数据；GRPO 训练后以不到 1 万条数据在主流数学多模态推理评测集上均实现提升（WeMath +7.42、LogicVista +9.15）。
- 📦 **业务交付**：完成 1024 道考研金融题得分点生成与长文本 QA Rubric 优化（97/99 通过）；制定 3000 道金融后训练采购数据验收标准，覆盖难度门槛、双次独立多模型三档判定。

### 🏦 国泰海通证券 · 生成式奖励模型训练
**业务偏好评估模型训练** ｜ 2025.12 – 2026.03

- 🎯 基于融资融券用户交互数据，训练 Qwen3-8B 生成式奖励模型，对候选回答进行偏好选择、质量评估与偏好标注。
- 🧠 设计 think / rubric / process / answer 四段式数据格式；在 16×A800 上完成 SFT（16k）与 GRPO（10k），设计过程奖励、结果正确率奖励、格式奖励等多维激励机制。
- 📊 构建 500 条完全人工标注对齐评测集；评测分数由 **58 提升至 94**，提升偏好标签一致性与可解释性，并实现与人工偏好的对齐。

### 🏦 国泰海通证券 · 信用 AI 助手 · 融资融券大模型
**垂类大模型训练** ｜ 2025.05 – 2025.07

- 💬 面向融资融券信用业务问答，负责数据清洗、SFT 指令集、DPO 偏好三元组与评测集构建；对 Qwen3-32B / Qwen3-30B-A3B 在 16×H800 上完成 SFT + DPO 两阶段训练（8k SFT、7k DPO、500 评测）。
- 📈 模型得分由基座 **3.79/10 → 6.09/10（+60.43%）**，解决部分业务问题“无法回答但幻觉回答”的问题。
- ✅ 通过内部评测并用于信用业务问答场景；在 **758 份**盲测用户评估中获得 **63%** 用户偏好。

---

## 🔬 项目与学术经历

### 📊 FinEval — 金融大模型评测体系
**金融基准构建** ｜ 2024.12 – 2026.05

- 🖼️ **[VisFinEval](https://github.com/SUFE-AIFLM-Lab/VisFinEval)（EMNLP 2025 Main）**：覆盖研报、财报、K 线图等 8 类金融图像，参与前中后台三级和 15 种子场景设计，主导多模态数据合成框架，得到 15k+ 问答。
- 🎬 **[UniFinEval](https://github.com/aifinlab/UniFinEval)（EMNLP 2026）**：面向文本、图像、视频的统一金融多模态评测，个人完成清洗、合成、质检、评测代码框架；构建 3k+ 跨模态 QA，覆盖多图、多视觉交叉推理、多跳推理与干扰设置。
- 🤖 **[FinGAIA](https://github.com/SUFE-AIFLM-Lab/FinGAIA)**：主导 407 个完全人工设计的真实业务 Agent 任务，覆盖计算器、代码解释器、检索、文件处理等工具；成果纳入《金融大模型应用测评指南》团体标准白皮书。

### 🧪 Fin-R1 — 金融推理大模型
**R1 风格推理训练 + 垂类迁移** ｜ 2025.02 – 2025.04

- 🔥 构建国内首个 DeepSeek-R1 风格金融推理模型（7B），利用 DeepSeek-R1 蒸馏 + Qwen2.5-72B 双重打分过滤，构建 60k+ 高质量 CoT 数据。
- 🏆 搭建 SFT 预热 + GRPO 强化学习框架，设计格式奖励与准确率奖励；五个金融基准平均 **75.2、排名第 2**，ConvFinQA（85.0）、FinQA（76.0）取得 SOTA。
- 🌐 开源 [Fin-R1](https://github.com/SUFE-AIFLM-Lab/Fin-R1)：**800+ stars、100+ citations**。
- 🚀 将数据蒸馏、SFT + GRPO 与专项奖励函数迁移到财跃星辰挖票模型：内部评测 **26 → 59**，格式一致性 **99%**。

---

## 📝 学术成果

| 成果 | 状态 | 角色 | 链接 |
|:---|:---:|:---:|:---|
| **AgSynth** — Multi-Agent Reverse Synthesis for Multimodal Mathematical Reasoning | EMNLP 2026 接收 | 共一 | [GitHub](https://github.com/Yaxuan7690/AgSynth) |
| **UniFinEval** — Unified Financial Multimodal Evaluation across Text, Images & Videos | EMNLP 2026 接收 | 共一 | [GitHub](https://github.com/aifinlab/UniFinEval) |
| **VisFinEval** — Scenario-Driven Chinese Multimodal Benchmark | EMNLP 2025 Main | 作者 | [GitHub](https://github.com/SUFE-AIFLM-Lab/VisFinEval) |
| **Fin-R1** — Financial Reasoning LLM via RL | JASA 在修 | 作者 | [GitHub](https://github.com/SUFE-AIFLM-Lab/Fin-R1) |
| **GEO-Poison-Bench** — LLM Robustness against GEO Poisoning | AAAI 2027 在投 | **一作** | [GitHub](https://github.com/zlfuu531/GEO-Poison-Bench) |
| **FinGAIA** — Chinese Benchmark for AI Agents in Finance | 团体标准白皮书 | **一作** | [GitHub](https://github.com/SUFE-AIFLM-Lab/FinGAIA) |

---

## 💻 开源与工程

| 项目 | 说明 | 状态 |
|:---|:---|:---:|
| **[Fin-R1](https://github.com/SUFE-AIFLM-Lab/Fin-R1)** | R1 风格金融推理大模型，SFT + GRPO | ![Stars](https://img.shields.io/github/stars/SUFE-AIFLM-Lab/Fin-R1?style=social) |
| **[QualEval](https://github.com/zlfuu531/QualEval)** | 本地化 QC + 评测平台：数据导入 → QC → 评测全前端流程 | ![Stars](https://img.shields.io/github/stars/zlfuu531/QualEval?style=social) |
| **[OpenReward-verl](https://github.com/zlfuu531/OpenReward-verl)** | 基于 verl 的生成式奖励模型训练：Rubric 偏好评估（SFT + GRPO） | ![Stars](https://img.shields.io/github/stars/zlfuu531/OpenReward-verl?style=social) |
| **[VQA-Data-Generator](https://github.com/zlfuu531/VQA-Data-Generator)** | 多模态 VQA 数据合成 pipeline，支撑 UniFinEval 数据构建 | ![Stars](https://img.shields.io/github/stars/zlfuu531/VQA-Data-Generator?style=social) |
| **[OpenR1-GRPO](https://github.com/zlfuu531/OpenR1-GRPO)** | R1 风格 GRPO 复现与训练框架 | ![Stars](https://img.shields.io/github/stars/zlfuu531/OpenR1-GRPO?style=social) |
| **[llm-study](https://github.com/zlfuu531/llm-study)** | LLM 学习笔记、Q&A 与精选资源 | ![Stars](https://img.shields.io/github/stars/zlfuu531/llm-study?style=social) |
| **[PaperHub](https://skymoon11.top/paper)** 🌐 | 自托管论文知识库 + AI Deep-Research Agent（Next.js · Prisma） | 在线 Demo；Repo 后续开源 |

---

## 🛠️ 技术栈

**模型后训练**
`SFT` · `DPO` · `GRPO` · `verl` · 数据蒸馏 · 奖励函数设计 · 消融实验 · 垂类迁移

**数据与评测**
数据合成 · Benchmark 构建 · 多模态 VQA · Agent 任务设计 · Rubric 设计 · LLM-as-Judge · pass@N 复筛 · 人工对齐评测 · 采购验收

**工程**
Python · PyTorch · Transformers · vLLM · 评测平台 · 质检 Agent · 批量数据 pipeline · 全流程交付

---

## 🏆 荣誉奖项

- 🥈 中国国际大学生创新大赛（2025）上海赛区 **银奖**
- 🥇 中国国际大学生创新大赛（2025）上海财经大学校赛 **一等奖**
- 🥇 第十届“汇创青春”上海大学生文化创意作品展示活动 **上海市一等奖**

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/github-contribution-grid-snake-dark.svg">
    <img src="assets/github-contribution-grid-snake.svg" alt="Contribution snake animation" width="100%">
  </picture>
</div>

<div align="center">
  <b>曾凌峰 · zlfuu531</b> ｜ <a href="mailto:zenglingfeng531@163.com">zenglingfeng531@163.com</a> ｜ <a href="https://github.com/zlfuu531">GitHub</a> ｜ <a href="https://scholar.google.com/citations?user=b69Frz4AAAAJ&hl=en">Google Scholar</a>
</div>

<div align="center">
  <i>“Benchmarks tell you where a model lies; data decides how far it goes.”</i>
</div>
