<p align="center">
  <img src="assets/banner.svg" width="100%" alt="zlfuu531 — LLM Post-Training · Data Synthesis · Evaluation &amp; Benchmarking">
</p>

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1400&color=8B949E&center=true&vCenter=true&width=720&lines=6+papers+%C2%B7+EMNLP+2025+%26+2026;Fin-R1+%C2%B7+800%2B+stars+%C2%B7+100%2B+citations;reward+model+alignment+58+%E2%86%92+94;deployed+fintech+LLM+%C2%B7+63%25+user+preference" alt="Typing SVG"></a>
</p>

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

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/github-contribution-grid-snake-dark.svg">
    <img src="assets/github-contribution-grid-snake.svg" alt="Contribution snake animation" width="100%">
  </picture>
</div>

<div align="center">
  <i>“Benchmarks tell you where a model lies; data decides how far it goes.”</i>
</div>
