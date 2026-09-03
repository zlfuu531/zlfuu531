<p align="center">
  <img src="assets/banner.svg" width="100%" alt="zlfuu531 — LLM Post-Training · Data Synthesis · Evaluation &amp; Benchmarking">
</p>

<p align="center">
  <a href="#-english"><img src="https://img.shields.io/badge/English-4285F4?style=for-the-badge" alt="English"></a>
  <a href="#-简体中文"><img src="https://img.shields.io/badge/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-2ea043?style=for-the-badge" alt="简体中文"></a>
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1400&color=8B949E&center=true&vCenter=true&width=720&lines=6+papers+%C2%B7+EMNLP+2025+%26+2026;Fin-R1+%C2%B7+800%2B+stars+%C2%B7+100%2B+citations;reward+model+alignment+58+%E2%86%92+94;deployed+fintech+LLM+%C2%B7+63%25+user+preference" alt="Typing SVG"></a>
</p>

## 🇬🇧 English

<p align="center">
  <img src="https://img.shields.io/badge/Papers-6_%C2%B7_3_accepted-8b17b8?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Papers">
  <img src="https://img.shields.io/badge/EMNLP-2025%20%26%202026-e05369?style=for-the-badge" alt="EMNLP">
  <a href="https://scholar.google.com/citations?user=b69Frz4AAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-100%2B_citations-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <br>
  <img src="https://img.shields.io/github/stars/SUFE-AIFLM-Lab/Fin-R1?style=for-the-badge&label=Fin-R1&logo=github" alt="Fin-R1 stars">
  <img src="https://img.shields.io/badge/Interned_at-Alibaba-f0883e?style=for-the-badge" alt="Interned at Alibaba">
  <img src="https://img.shields.io/badge/2027_New_Grad-Open_to_Work-2ea043?style=for-the-badge" alt="Open to work">
</p>

> I build the **data and the yardsticks** that make LLMs better at finance — multimodal reasoning benchmarks (EMNLP ×3), an R1-style financial reasoning LLM (**Fin-R1**, 800+ ★), and agent benchmarks adopted by industry teams.

---

## 🎓 Education

<p align="center">
  <b>B.S. &amp; M.S. @ Shanghai University of Finance and Economics (SUFE)</b>
</p>

---

## 💼 Internship Experience

#### 🏢 Alibaba Group — Platform Technology · AI Data Synthesis Team
`Data Algorithm Intern` · `2026.03 – 2026.08`

- 🕹️ **Agent benchmark “ClawBench”** — designed **40+** end-to-end long-horizon financial agent tasks across **7** deliverable types; co-designed a **200-task** real-scenario agent eval set and built a **QC agent** for iterative refinement
- 🖼️ **Financial multimodal eval set** — **400** questions with L1–L4 difficulty filtering, expert annotation standards and pass@8 re-screening; benchmarked **9 frontier models** (top model pass@2 only **54%**)
- ⚙️ **Evaluation & QC platform** — built solo, one-stop QA / multimodal / rubric / agent judging, **27 tasks in a single month**; defined acceptance criteria for **3,000** purchased post-training samples (pass@1 <40% difficulty gate, dual multi-model review)
- 📦 **Data delivery** — **1,024** exam-style finance questions with full scoring-point annotation; long-context QA rubric optimization (**97/99** pass)
- 🧪 **First-author research — [GEO-Poison-Bench](https://github.com/zlfuu531/GEO-Poison-Bench)**: 9 attack types × 18 domains, **1,578 questions × 24 models** leaderboard
- 📄 **Co-first research — [AgSynth](https://github.com/Yaxuan7690/AgSynth) (EMNLP 2026)**: <10k synthesized samples lift multimodal math reasoning (WeMath **+7.42**, LogicVista **+9.15**)

---

## 🚀 Project Experience

#### 🏦 Guotai Haitong Securities — Generative Reward Model Training
`Preference Evaluation Model Training` · `2025.12 – 2026.03`

- 🎯 **Training** — distilled preference data in a 4-segment format (think / rubric / process / answer); SFT (16k) + GRPO (10k) on **16×A800** with process / accuracy / format rewards; built a **500-item** fully human-aligned eval set
- 📈 **Result** — rubric-based multi-dimension scoring (accuracy, relevance, consistency, coverage, professionalism) with final preference selection; eval score **58 → 94**, precisely aligned with human preference

#### 🏦 Guotai Haitong Securities — Credit AI Assistant · Margin Trading LLM
`Domain LLM Training` · `2025.05 – 2025.07`

- 💬 **Training** — SFT + DPO on **16×H800** (Qwen3-32B / Qwen3-30B-A3B; 8k SFT data, 7k DPO triplets, 500-item eval set with consistency-validated annotation prompts)
- 🚀 **Deployment** — score **3.79 → 6.09 / 10** (+60%), fixed “cannot answer” vs “hallucinated answer” failure modes; **shipped to production** with **63%** preference in **758** blind user tests

#### 🧪 Fin-R1 — Financial Reasoning LLM
`R1-style Reasoning Training + Domain Transfer` · `2025.02 – 2025.04`

- 🔥 Built **China's first DeepSeek-R1-style financial reasoning LLM (7B)** — distilled **60k+** high-quality CoT data (dual-score filtering with DeepSeek-R1 + Qwen2.5-72B), SFT warm-up + GRPO with format & accuracy rewards
- 🏆 Ranked **#2** (avg **75.2**) across **five** financial benchmarks, **SOTA** on ConvFinQA (85.0) & FinQA (76.0) — [open source](https://github.com/SUFE-AIFLM-Lab/Fin-R1) with **800+ stars** and **100+ citations**; transferred the pipeline to a stock-picking model (internal eval **26 → 59**, format consistency **99%**)

---

## 📝 Publications

| Paper | Venue | Role |
|:---|:---:|:---:|
| **[AgSynth](https://github.com/Yaxuan7690/AgSynth)** — multi-agent reverse synthesis for multimodal mathematical reasoning data | ![EMNLP 2026](https://img.shields.io/badge/EMNLP_2026-accepted-2ea043) | Co-first |
| **[UniFinEval](https://github.com/aifinlab/UniFinEval)** — unified financial multimodal evaluation across text · images · videos; solo-built data pipeline (3k+ cross-modal QA) | ![EMNLP 2026](https://img.shields.io/badge/EMNLP_2026-accepted-2ea043) | Co-first |
| **[VisFinEval](https://github.com/SUFE-AIFLM-Lab/VisFinEval)** — scenario-driven Chinese financial multimodal benchmark (15k+ QA) | ![EMNLP 2025](https://img.shields.io/badge/EMNLP_2025-main-2ea043) | Co-author |
| **[Fin-R1](https://github.com/SUFE-AIFLM-Lab/Fin-R1)** — R1-style financial reasoning LLM via reinforcement learning, 100+ citations | ![JASA](https://img.shields.io/badge/JASA-under_review-58a6ff) | ![Stars](https://img.shields.io/github/stars/SUFE-AIFLM-Lab/Fin-R1?style=flat) |
| **[GEO-Poison-Bench](https://github.com/zlfuu531/GEO-Poison-Bench)** — LLM robustness against GEO poisoning attacks | ![AAAI 2027](https://img.shields.io/badge/AAAI_2027-under_review-58a6ff) | **First** |
| **[FinGAIA](https://github.com/SUFE-AIFLM-Lab/FinGAIA)** — Chinese benchmark for AI agents in real-world finance (407 tasks) | ![Whitepaper](https://img.shields.io/badge/Industry_whitepaper-adopted-2ea043) | **First** |

---

## 💻 Open Source Projects

| Project | About | Stars |
|:---|:---|:---:|
| **[PaperHub](https://skymoon11.top/paper)** 🌐 | Self-hosted paper research knowledge base — blog-style reading + AI Deep-Research agent that auto-crawls and structures papers (Next.js · Prisma) | ![Repo](https://img.shields.io/badge/repo-soon-8b949e) |
| **[QualEval](https://github.com/zlfuu531/QualEval)** | One-stop local QC + evaluation platform — data import → QC → eval, full frontend workflow | ![Stars](https://img.shields.io/github/stars/zlfuu531/QualEval?style=flat) |
| **[OpenReward-verl](https://github.com/zlfuu531/OpenReward-verl)** | Generative reward model training on verl — rubric-based preference evaluation (SFT + GRPO) | ![Stars](https://img.shields.io/github/stars/zlfuu531/OpenReward-verl?style=flat) |
| **[VQA-Data-Generator](https://github.com/zlfuu531/VQA-Data-Generator)** | Multimodal VQA data synthesis pipeline — powers [UniFinEval](https://github.com/aifinlab/UniFinEval) data construction | ![Stars](https://img.shields.io/github/stars/zlfuu531/VQA-Data-Generator?style=flat) |
| **[OpenR1-GRPO](https://github.com/zlfuu531/OpenR1-GRPO)** | Reproduction & training framework for R1-style GRPO reasoning | ![Stars](https://img.shields.io/github/stars/zlfuu531/OpenR1-GRPO?style=flat) |
| **[llm-study](https://github.com/zlfuu531/llm-study)** | LLM learning notes, Q&A and curated study resources | ![Stars](https://img.shields.io/github/stars/zlfuu531/llm-study?style=flat) |

---

## 🛠️ Tech Stack

<b>Languages & Frameworks</b><br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/%F0%9F%A4%97_Transformers-FFD21E?style=flat&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-4B8BBE?style=flat)

<b>Post-Training</b><br>
![SFT](https://img.shields.io/badge/SFT-6A9FDB?style=flat)
![DPO](https://img.shields.io/badge/DPO-6A9FDB?style=flat)
![GRPO](https://img.shields.io/badge/GRPO-6A9FDB?style=flat)
![verl](https://img.shields.io/badge/verl-1F2328?style=flat)

<b>Data & Evaluation</b><br>
![Data Synthesis](https://img.shields.io/badge/Data_Synthesis-3E7CB1?style=flat)
![Benchmarks](https://img.shields.io/badge/Benchmark_Construction-2E8B57?style=flat)
![LLM-as-Judge](https://img.shields.io/badge/LLM_as_Judge-2E8B57?style=flat)
![Multimodal](https://img.shields.io/badge/Multimodal-9B59B6?style=flat)
![Agents](https://img.shields.io/badge/LLM_Agents-E67E22?style=flat)
![FinLLM](https://img.shields.io/badge/Financial_LLMs-C0392B?style=flat)

---

## 🏆 Awards

🥈 **Silver Award** · China International College Students' Innovation Competition, Shanghai Division (2025) — plus First Prize at SUFE campus round<br>
🥇 **First Prize** · 10th "Huichuang Youth" Shanghai College Students Cultural & Creative Works Exhibition

---

## 🀄 简体中文

<p align="center">
  <img src="https://img.shields.io/badge/%E8%AE%BA%E6%96%87-6%E7%AF%87_%C2%B7_3%E7%AF%87%E5%B7%B2%E5%BD%95%E7%94%A8-8b17b8?style=for-the-badge&logo=googlescholar&logoColor=white" alt="论文">
  <img src="https://img.shields.io/badge/EMNLP-2025%20%26%202026-e05369?style=for-the-badge" alt="EMNLP">
  <a href="https://scholar.google.com/citations?user=b69Frz4AAAAJ&hl=zh-CN"><img src="https://img.shields.io/badge/Google_Scholar-%E5%BC%95%E7%94%A8_100%2B-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"></a>
  <br>
  <img src="https://img.shields.io/github/stars/SUFE-AIFLM-Lab/Fin-R1?style=for-the-badge&label=Fin-R1&logo=github" alt="Fin-R1 stars">
  <img src="https://img.shields.io/badge/%E5%AE%9E%E4%B9%A0%E4%BA%8E-%E9%98%BF%E9%87%8C%E5%B7%B4%E5%B7%B4-f0883e?style=for-the-badge" alt="实习于阿里巴巴">
  <img src="https://img.shields.io/badge/2027%E5%B1%8A-%E6%B1%82%E8%81%8C%E4%B8%AD-2ea043?style=for-the-badge" alt="2027届求职中">
</p>

> 我做的事情,是把「模型为什么不行」变成**可复现的评测与训练闭环**——从数据合成、SFT / DPO / GRPO 后训练,到 Agent、多模态与安全评测,再到业务落地。

---

### 🎓 教育背景

<p align="center">
  <b>本科 &amp; 硕士 · 上海财经大学(SUFE)</b>
</p>

---

### 💼 实习经历

#### 🏢 阿里巴巴集团 · 平台技术 · AI Data 数据合成团队
`数据算法实习生` · `2026.03 – 2026.08`

- 🕹️ **Agent 评测「ClawBench」**——设计 **40+** 道覆盖 **7** 类金融产出物的端到端长程 Agent 任务;参与设计 **200 题**真实场景金融 Agent 评测集,并搭建**质检 Agent** 支撑迭代优化
- 🖼️ **金融复杂多模态评测集**——**400** 题,设计 L1–L4 难度筛选、专家标注标准与 pass@8 复筛,完成 **9 个**前沿模型评测(头部模型 pass@2 仅 **54%**)
- ⚙️ **评测质检一体化平台**——独立搭建,支持 QA / 多模态 / Rubric / Agent 多维裁判,单月运行 **27 个**任务;制定 **3,000 条**采购后训练数据验收标准(pass@1 <40% 难度门槛 + 双次独立多模型三档判定)
- 📦 **数据交付**——**1,024** 道考研金融题得分点全量生成;长文本 QA Rubric 优化(**97/99** 通过)
- 🧪 **一作研究 [GEO-Poison-Bench](https://github.com/zlfuu531/GEO-Poison-Bench)**——9 种攻击类型 × 18 个行业,**1,578 题 × 24 模型**评测榜单
- 📄 **共一研究 [AgSynth](https://github.com/Yaxuan7690/AgSynth)(EMNLP 2026)**——不到 1 万条合成数据全面提升多模态数学推理(WeMath **+7.42**、LogicVista **+9.15**)

---

### 🚀 项目经历

#### 🏦 国泰海通证券 · 生成式奖励模型训练
`偏好评估模型训练` · `2025.12 – 2026.03`

- 🎯 **训练**——think / rubric / process / answer 四段式偏好数据蒸馏;16×A800 上完成 SFT(16k)+ GRPO(10k),设计过程奖励、正确率奖励、格式奖励多维激励机制;构建 **500 条**完全人工对齐的评测集
- 📈 **效果**——围绕准确性、相关性、一致性、覆盖度、专业性生成多维 rubric 并给出最优偏好,评测分数 **58 → 94**,与人工偏好精准对齐

#### 🏦 国泰海通证券 · 信用 AI 助手 · 融资融券大模型
`垂类大模型训练` · `2025.05 – 2025.07`

- 💬 **训练**——16×H800 上完成 SFT + DPO 两阶段训练(Qwen3-32B / Qwen3-30B-A3B;8k SFT 数据、7k DPO 三元组、500 条经一致性校验的评测集)
- 🚀 **落地**——得分 **3.79 → 6.09 / 10**(+60%),缓解「无法回答却幻觉回答」问题;**通过内部评测上线生产**,758 份盲测获 **63%** 用户偏好

#### 🧪 Fin-R1 — 金融推理大模型
`R1 式推理训练 + 垂类迁移` · `2025.02 – 2025.04`

- 🔥 构建**国内首个 DeepSeek-R1 式金融推理大模型(7B)**——DeepSeek-R1 蒸馏 + Qwen2.5-72B 双重打分过滤,构建 **6w+** 高质量 CoT 数据;SFT 预热 + GRPO(格式 / 准确率奖励)
- 🏆 五个金融基准平均 **75.2、排名第 2**,ConvFinQA(85.0)/ FinQA(76.0) **SOTA**;[开源](https://github.com/SUFE-AIFLM-Lab/Fin-R1)获 **800+ stars、100+ 引用**;迁移至挖票选股模型(内部评测 **26 → 59**,格式一致性 **99%**)

---

### 📝 学术成果

| 成果 | 发表 | 角色 |
|:---|:---:|:---:|
| **[AgSynth](https://github.com/Yaxuan7690/AgSynth)** — 多智能体反向合成多模态数学推理数据 | ![EMNLP 2026](https://img.shields.io/badge/EMNLP_2026-%E5%B7%B2%E5%BD%95%E7%94%A8-2ea043) | 共一 |
| **[UniFinEval](https://github.com/aifinlab/UniFinEval)** — 文本·图像·视频统一金融多模态评测;独立搭建数据管线(3k+ 跨模态 QA) | ![EMNLP 2026](https://img.shields.io/badge/EMNLP_2026-%E5%B7%B2%E5%BD%95%E7%94%A8-2ea043) | 共一 |
| **[VisFinEval](https://github.com/SUFE-AIFLM-Lab/VisFinEval)** — 场景驱动的中文金融多模态基准(15k+ QA) | ![EMNLP 2025](https://img.shields.io/badge/EMNLP_2025-main-2ea043) | 作者 |
| **[Fin-R1](https://github.com/SUFE-AIFLM-Lab/Fin-R1)** — 强化学习驱动的金融推理大模型,100+ 引用 | ![JASA](https://img.shields.io/badge/JASA-%E5%9C%A8%E4%BF%AE-58a6ff) | ![Stars](https://img.shields.io/github/stars/SUFE-AIFLM-Lab/Fin-R1?style=flat) |
| **[GEO-Poison-Bench](https://github.com/zlfuu531/GEO-Poison-Bench)** — LLM 对 GEO 投毒攻击的鲁棒性评测 | ![AAAI 2027](https://img.shields.io/badge/AAAI_2027-%E5%9C%A8%E6%8A%95-58a6ff) | **一作** |
| **[FinGAIA](https://github.com/SUFE-AIFLM-Lab/FinGAIA)** — 真实金融场景 AI Agent 中文基准(407 任务) | ![白皮书](https://img.shields.io/badge/%E8%A1%8C%E4%B8%9A%E7%99%BD%E7%9A%AE%E4%B9%A6-%E7%BA%B3%E5%85%A5-2ea043) | **一作** |

---

### 💻 开源项目

| 项目 | 说明 | Stars |
|:---|:---|:---:|
| **[PaperHub](https://skymoon11.top/paper)** 🌐 | 自托管论文调研知识库——博客式阅读 + AI Deep-Research Agent 自动抓取并结构化入库(Next.js · Prisma) | ![Repo](https://img.shields.io/badge/repo-soon-8b949e) |
| **[QualEval](https://github.com/zlfuu531/QualEval)** | 本地化质检 + 评测平台:数据导入 → 质检 → 评测全前端操作 | ![Stars](https://img.shields.io/github/stars/zlfuu531/QualEval?style=flat) |
| **[OpenReward-verl](https://github.com/zlfuu531/OpenReward-verl)** | 基于 verl 的生成式奖励模型训练:Rubric 偏好评估(SFT + GRPO) | ![Stars](https://img.shields.io/github/stars/zlfuu531/OpenReward-verl?style=flat) |
| **[VQA-Data-Generator](https://github.com/zlfuu531/VQA-Data-Generator)** | 多模态 VQA 数据合成管线,支撑 [UniFinEval](https://github.com/aifinlab/UniFinEval) 数据构建 | ![Stars](https://img.shields.io/github/stars/zlfuu531/VQA-Data-Generator?style=flat) |
| **[OpenR1-GRPO](https://github.com/zlfuu531/OpenR1-GRPO)** | R1 式 GRPO 复现与训练框架 | ![Stars](https://img.shields.io/github/stars/zlfuu531/OpenR1-GRPO?style=flat) |
| **[llm-study](https://github.com/zlfuu531/llm-study)** | LLM 学习笔记、Q&A 与精选资源 | ![Stars](https://img.shields.io/github/stars/zlfuu531/llm-study?style=flat) |

---

### 🛠️ 技术栈

<b>后训练</b><br>
![SFT](https://img.shields.io/badge/SFT-6A9FDB?style=flat)
![DPO](https://img.shields.io/badge/DPO-6A9FDB?style=flat)
![GRPO](https://img.shields.io/badge/GRPO-6A9FDB?style=flat)
![verl](https://img.shields.io/badge/verl-1F2328?style=flat)
`数据蒸馏` `奖励函数设计` `消融实验` `垂类迁移`

<b>数据与评测</b><br>
![Data Synthesis](https://img.shields.io/badge/%E6%95%B0%E6%8D%AE%E5%90%88%E6%88%90-3E7CB1?style=flat)
![Benchmarks](https://img.shields.io/badge/%E8%AF%84%E6%B5%8B%E5%9F%BA%E5%87%86%E6%9E%84%E5%BB%BA-2E8B57?style=flat)
![LLM-as-Judge](https://img.shields.io/badge/LLM_as_Judge-2E8B57?style=flat)
![Multimodal](https://img.shields.io/badge/%E5%A4%9A%E6%A8%A1%E6%80%81-9B59B6?style=flat)
![Agents](https://img.shields.io/badge/LLM_Agents-E67E22?style=flat)
![FinLLM](https://img.shields.io/badge/%E9%87%91%E8%9E%8DLLM-C0392B?style=flat)

<b>工程</b><br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/%F0%9F%A4%97_Transformers-FFD21E?style=flat&logoColor=black)
![vLLM](https://img.shields.io/badge/vLLM-4B8BBE?style=flat)
`评测平台` `质检 Agent` `批量数据 pipeline`

---

### 🏆 荣誉奖项

🥈 中国国际大学生创新大赛(2025)上海赛区**银奖**(含上财校赛一等奖)<br>
🥇 第十届「汇创青春」上海大学生文化创意作品展示活动**上海市一等奖**

---

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/github-contribution-grid-snake-dark.svg">
    <img src="assets/github-contribution-grid-snake.svg" alt="Contribution snake animation" width="100%">
  </picture>
</div>

<div align="center">
  <p><a href="#-english"><b>↑ Back to English</b></a> · <a href="#-简体中文"><b>↑ 回到简体中文</b></a></p>
  <i>“Benchmarks tell you where a model lies; data decides how far it goes.”</i><br>
  <i>「基准告诉你模型在哪里,数据决定模型能走多远。」</i>
</div>
