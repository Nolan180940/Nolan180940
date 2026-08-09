<!-- Banner -->
<div align="center">

# 你好，我是 Nolan Xu 👋

---

### [![NYU Logo](https://github.com/Nolan180940/Nolan180940/raw/main/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20260529183826_1583_2.png)](https://github.com/Nolan180940/Nolan180940/blob/main/%E5%BE%AE%E4%BF%A1%E5%9B%BE%E7%89%87_20260529183826_1583_2.png) NYU '29 | 数据科学 · AI 方向

**数据科学 × AI × 量化金融** — 用数据与算法连接技术与真实世界

[![个人主页](https://img.shields.io/badge/个人主页-nolan180940.github.io-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://nolan180940.github.io/)

</div>

---

## 👨‍💻 关于我

纽约大学（NYU Shanghai）数据科学专业 2029 届，深耕 **量化金融 + AI 应用**。我相信 **Data Science + AI + Finance** 是面向未来的复合并集。

- 🎓 GPA 3.8/4.0 · 核心课程：概率统计 / 机器学习 / 数据结构
- 🧭 量化策略研究 · AI 应用开发 · 全栈工具链 · 开源探索
- 🌏 上海

---

## 📊 GitHub 统计

<div align="center">

[![公开仓库-47](https://img.shields.io/badge/公开仓库-47-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nolan180940?tab=repositories) [![获Star-21](https://img.shields.io/badge/获Star-21-ffd700?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nolan180940?tab=repositories) [![Star过的仓库-292](https://img.shields.io/badge/Star过的仓库-292-ffd700?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nolan180940?tab=stars) [![Followers-10](https://img.shields.io/badge/Followers-10-4285F4?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nolan180940?tab=followers)

[![GitHub 成就 Starstruck](https://img.shields.io/badge/Starstruck-E3B341?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nolan180940?tab=achievements) [![GitHub 成就 Pull Shark](https://img.shields.io/badge/Pull%20Shark-4B8BBE?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nolan180940?tab=achievements) [![GitHub 成就 YOLO](https://img.shields.io/badge/YOLO-6f42c1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nolan180940?tab=achievements)

![GitHub Stats](https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Nolan180940&theme=tokyonight)

![Top Languages](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Nolan180940&theme=tokyonight)

![GitHub Streak](https://streak-stats.demolab.com/?user=Nolan180940&theme=tokyonight)

![贡献热力图](https://ghchart.rshah.org/Nolan180940)

</div>

---

## 🔬 量化研究 · 当前重点项目

> 🚀 上海某私募基金 **长期兼职量化研究员**（实习转正，Return Offer），主导 **因子挖掘与机器学习因子合成**，核心成果开源在 [**Factor-Mining**](https://github.com/Nolan180940/Factor-Mining)。

| 模块 | 核心内容 |
|:---|:---|
| **Omni Research API** | 自建 A 股因子数据库，**451 字段 / 12 大类**（行情、估值、财务、一致预期、技术面、资金流等），Polars 统一读取 |
| **Random Search 因子发现** | System 2.0 三闸门（raw IC → 中性化 IC → 样本外 IC），并行评估，累计 **约 1 万条随机表达式** |
| **ML 因子合成** | LightGBM / CatBoost / XGBoost / Ensemble + SHAP 可解释性 + 树规则提取 |
| **研究报告** | `Documentation/` 下 **9 篇 PDF 研究报告**（数学推导 + 行为金融学逻辑 + 多宇宙回测） |

### 📈 代表性成果（A 股全市场 · 2020–2024 · 净收益）

| 因子 | 净夏普 | 年化 | 最大回撤 |
|:---|:---:|:---:|:---:|
| **LGBM Ensemble 15 因子合成** | **4.69** | 32.6% | -5.6% |
| **Ensemble 15 因子合成** | **4.44** | 31.8% | -5.5% |
| **CatBoost 15 因子合成** | **4.42** | 30.5% | -5.6% |
| **成交量波动-盈亏比×盈利趋势 (VGPT)** | **3.29** | 27.8% | -6.4% |
| **成交量波动×盈利趋势 (V3)** | **3.24** | 29.6% | -8.3% |
| **盈利趋势×质量×成长 (QGF)** | **2.85** | 12.6% | -4.9%（731 个因子中排名第 1）|
| **盈利质量×杠杆×信用风险门控 (QLCF)** | **2.63** | 13.7% | -6.1% |
| **动量趋势质量混合 (STF)** | **2.53** | 21.0% | -8.4% |
| **现金流收益率×流动性门控 (PCF-REV-NP)** | **1.90** | 12.3% | -8.4% |
| **恐慌流动性门控反转 (PLGR)** | **1.62** | 12.6% | -9.3% |
| **Sigmoid Soft Gating 非线性因子** | **1.61** | 10.2% | -9.2% |

### 🧪 严谨性

- **2025 全年样本外测试**：17 个因子统一 OOS（含成本），**10/17 Sharpe ≥ 1.0**，最高 intern_f09_sn_v8 **3.41**
- **5 层中性化** + **多宇宙检验**（CSI1000/500/300）+ IC20 t 统计量 > 10，统计高度显著

---

## 🎯 简历一览

### 🧑‍💼 专业经历

**量化研究实习生 · 上海某私募基金** `2025.12 – 2026.01`

- 微盘股量化策略（市值 + RSI 反转因子）：2019–2024 回测**年化 43.59%、夏普 1.623**
- IF/IH 期货对冲策略（贴水因子）：**年化 20.74% / 16.54%，夏普 1.38 / 1.17**
- 2024 微盘股地震影响分析与关键风险因子识别
- akshare 构建 A 股 SQL 数据库：自动化清洗与定时更新

**兼职量化研究员（实习转长期）· 上海另一家私募** `2026.06 – 至今`

> 🏆 实习入职 → 获 **Return Offer** → 转长期兼职量化研究员，负责因子研究主线（详见上方 [Factor-Mining](https://github.com/Nolan180940/Factor-Mining) 章节）。

**TAMID Group（上海分会）· 投资基金成员** `2025.02 – 至今`

- 股权估值课程（DCF / Comps）+ 内部股票推介赛，负责 **Dynatrace (NYSE: DT)** 的 DCF 建模与敏感性分析

### 🤖 竞赛与项目

| 项目 | 角色 | 内容 |
|:---|:---|:---|
| **ETF Navigator — 可持续投资 AI Agent**（DIC） | Lead Developer | 实时金融 API 发现 ESG/清洁能源 ETF + LLM 新闻摘要与来源归因 |
| **Autonomous Motivational Tutor Agent**（DIC） | Contributor | 情感处理单元（APU）+ 混合记忆（HMS）+ PHQ-9 情绪检测 |
| **多传感器近视预防系统** | 独立开发者 | 姿态/环境光传感器 + 嵌入式固件（Python/C），概念到原型 |

### 🏅 教育背景

- **NYU Shanghai** — 数据科学学士（AI 方向），2029 届，GPA 3.8/4.0
- **上海南洋模范中学** — 高中；Y2022–2023 奖学金、2022 年度优秀学生

### 🧰 技能

- **语言**：Python · SQL · JavaScript/TypeScript · C++ · HTML
- **数据/ML**：Pandas · NumPy · Polars · LightGBM · CatBoost · XGBoost · SHAP
- **量化**：多因子模型 · 因子挖掘 · 中性化 (CNE6) · 回测框架 · IC/IR 分析
- **AI/前端**：LLM 集成 · RAG · Streamlit · Next.js · Tailwind
- **工具/语言**：Git · Linux · LaTeX · Markdown | 中文（母语）· 英语（IELTS 7.5）

---

## 📌 主页精选项目（Pinned）

- 🛠️ [**md-to-word**](https://github.com/Nolan180940/md-to-word) — Markdown 转 Word 在线工具，支持 **LaTeX 公式**、AI 语法修复，免费免登录
- 🏠 [**Nolan180940.github.io**](https://github.com/Nolan180940/Nolan180940.github.io) — 个人作品集主页
- 🏎️ [**smg-f1-unlock--F1-**](https://github.com/Nolan180940/smg-f1-unlock--F1-) ⭐19 — 绕过版权看五星体育 F1 直播/回看（Console / Tampermonkey / 全自动脚本，逆向 Nuxt.js 拦截机制）
- 💬 [**chatbot-demo**](https://github.com/Nolan180940/chatbot-demo) — BYOK 聊天控制台（Next.js 14 + TS + Tailwind），配置三项参数即可连任意 OpenAI 兼容服务，已部署 Vercel
- 🎓 [**tutor-course-material**](https://github.com/Nolan180940/tutor-course-material) — 高中生编程教学大纲（Python / AI 与大模型 / 实战项目 / DS 入门，Jupyter 讲义）
- 🖥️ [**windows-simulator**](https://github.com/Nolan180940/windows-simulator) — 纯前端浏览器里的 Windows 11 桌面（窗口管理 + 7 个内置应用）

---

## 🔥 最近更新 · Top 15 仓库

> 📌 = Pinned；按最近更新时间排序

| 仓库 | 语言 | 更新 | 一句话介绍 |
|:---|:---|:---|:---|
| 📌 [tutor-course-material](https://github.com/Nolan180940/tutor-course-material) | Jupyter | 2026.08 | 编程教学讲义（含 AI / 大模型模块） |
| 📌 [chatbot-demo](https://github.com/Nolan180940/chatbot-demo) | TS | 2026.08 | BYOK 聊天控制台（Next.js + Tailwind） |
| [dayjourney](https://github.com/Nolan180940/dayjourney) | 🐍 | 2026.08 | 电脑行为记录 → 本地知识库 → AI 人格助手（Electron + Python，local-first） |
| 🔬 [Factor-Mining](https://github.com/Nolan180940/Factor-Mining) | 🐍 | 2026.08 | **当前重点**：A 股因子挖掘 + ML 因子合成 |
| 📌 [windows-simulator](https://github.com/Nolan180940/windows-simulator) | JS | 2026.08 | 纯前端 Windows 11 桌面模拟 |
| 📌 [smg-f1-unlock--F1-](https://github.com/Nolan180940/smg-f1-unlock--F1-) | JS | 2026.07 | F1 直播版权解锁脚本 ⭐19 |
| [Wexport](https://github.com/Nolan180940/Wexport) | TS | 2026.07 | WeFlow：微信聊天记录本地查看/分析/导出 |
| [my-cloud](https://github.com/Nolan180940/my-cloud) | HTML | 2026.07 | 网页版云盘（文件预览与编辑） |
| [Claude-Code-Proxy-SiliconFlowCN](https://github.com/Nolan180940/Claude-Code-Proxy-SiliconFlowCN) | JS | 2026.07 | 把 Claude Code 转到 SiliconFlow 国产模型驱动的轻量代理 |
| [Intelligent-Distributed-Chat-System](https://github.com/Nolan180940/Intelligent-Distributed-Chat-System) | 🐍 | 2026.07 | Socket + Tkinter + Ollama + TextBlob 智能分布式聊天 |
| 📌 [md-to-word](https://github.com/Nolan180940/md-to-word) | 🐍 | 2026.06 | Markdown 转 Word 在线工具（LaTeX 公式） |
| [SiliconFlow-NextChat](https://github.com/Nolan180940/SiliconFlow-NextChat) | TS | 2026.06 | NextChat 的 SiliconFlow 接入部署 |
| [a_share_downloader](https://github.com/Nolan180940/a_share_downloader) | 🐍 | 2026.06 | A 股数据下载：Yahoo + Tushare 多源、本地回测框架 |
| [Agent](https://github.com/Nolan180940/Agent) | 🐍 | 2026.06 | AI Agent 探索实验 |
| [Jake's-Resume-Generator](https://github.com/Nolan180940/Jake-s-Resume-Generator) | 🐍 | 2026.06 | Streamlit 表单 → LaTeX → PDF 简历生成器 |

**更多**：`DCF-Auto-Analysis`（DCF 估值仪表板）、`DIC04-AI_Finance`（NYU DIC 金融赛道）、`blog`、`chatbot` 等，欢迎翻阅 [全部 47 个仓库](https://github.com/Nolan180940?tab=repositories)。

> 📌 口径说明：47 个仓库共收到 **21 Stars**；主页 "Stars 292" 是我 **Star 过的仓库数**，两者含义不同。

---

## 🛠️ 技术栈

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white) ![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=for-the-badge&logo=latex&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-45B39D?style=for-the-badge&logo=lightgbm&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-CD792C?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## 💭 理念

> *"未来属于具有跨学科特质的行业 —— **数据科学 + AI + 金融** 正是我坚持深耕的交汇点；让代码解决真实问题，让开源连接世界。"*

---

## 📬 联系我

[![GitHub](https://img.shields.io/badge/GitHub-Nolan180940-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Nolan180940) &nbsp; [![个人主页](https://img.shields.io/badge/个人主页-nolan180940.github.io-4285F4?style=for-the-badge&logo=google-chrome&logoColor=white)](https://nolan180940.github.io/) &nbsp; [![Email](https://img.shields.io/badge/Email-Alexander_123Wiggins%40proton.me-6d4aff?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:Alexander_123Wiggins@proton.me)

> 对量化 / AI 应用 / 开源感兴趣？欢迎交流！🌟
