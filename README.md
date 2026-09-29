# lhg-deep-research · 深度调研

[English](#english) | [中文](#中文)

---

## English

**Deep Research** turns an open-ended topic into an actionable research dossier — not just a list of links, but answers to *who's building it, why, what problem it solves, where the demand comes from, how the space is structured, and whether it can be replicated or surpassed*.

### Workflow

1. **Scope** — confirm topic boundaries, ecosystem, sample size (Top N), and ranking criteria (stars / downloads / buzz).
2. **Collect** — multi-keyword searches (e.g. GitHub Search API, top 100 by stars per query), deduplicate, cross-complete with awesome-lists; every candidate keeps its source URL.
3. **Verify** — re-check key metrics (e.g. star counts) on the research date and stamp the date (YYYY-MM-DD).
4. **Filter** — define explicit exclusion criteria ("what doesn't count") and document them.
5. **Deep-dive authors** — for the head of the list: background, other notable work, motivation evidence chain (README, blog, issues, social), the exact problem solved, typical scenarios. Unverifiable items are marked as such — never fabricated.
6. **Distill demand** — extract recurring demand threads ("surface phenomenon → underlying need").
7. **Categorize** — group by function, count, and note structural observations (saturated vs. hollow categories).
8. **Replicate / improve / surpass** — per-category feasibility (barriers, dependencies, license), weaknesses of the originals, and original improvement directions.
9. **Skip list** — privacy-invasive scraping, copyright infringement, and gray-area uses are skipped and listed with reasons.
10. **Report** — structured Chinese dossier per the Output Contract.

### Output

Ranking table · author deep-dives · demand threads · category map · per-category replicate/improve/surpass plans · skip list · key takeaways · methodology & honesty notes (data dates, verification method, unverified items).

### Compatibility

Pure process description in Markdown — no dependency on any specific agent platform. Portable to any environment that supports Markdown instructions (Claude Code, Codex, Doubao, Workbuddy, etc.).

### Operating principles

- Every number/fact comes from a verifiable source with a date; missing data is marked, never invented.
- License check before any replication plan: MIT/Apache-2.0 allow commercial derivatives (keep attributions); unlicensed work needs author confirmation; source-available / copyrighted material is never replicated commercially.
- Privacy / infringement / gray-area uses are always skipped, never given replication plans.

### License

MIT — see [LICENSE](LICENSE).

---

## 中文

**深度调研**：输入一个主题，输出一份可直接指导行动的中文调研报告——不止于列表，而是回答"谁在做、为什么做、解决了什么问题、需求从哪来、怎么分类、能不能复刻超越"。

### 流程

1. **定范围** — 确认主题边界、生态/领域、样本量（Top N）、排序依据（star / 下载量 / 热度）。
2. **搜集候选** — 多组关键词搜索（如 GitHub Search API 按 star 取 Top100），去重并记录每条来源 URL；用 awesome 合集交叉补全。
3. **数据核实** — 关键热度数据在调研当日核实并标注日期（YYYY-MM-DD）。
4. **剔除口径** — 明确"什么不算"，只保留目标对象，并写明标准。
5. **头部深挖** — 作者/团队背景、其他作品、创作动机证据链、解决的具体问题、典型场景；无法核实的标注"未找到公开信息"。
6. **需求提炼** — 反复出现的需求主线（"表面现象 → 本质需求"）。
7. **功能分类** — 按功能归类、统计，指出结构性观察（哪类饱和、哪类塌陷）。
8. **复刻/超越** — 每类评估可复刻性（门槛/依赖/许可），指出原方案短板，给出原创改进方向。
9. **跳过项** — 隐私抓取、版权侵权、灰色用途一律跳过并单列原因。
10. **输出报告** — 按 Output Contract 输出结构化中文报告。

### 产出

排名清单 · 头部作者深挖 · 需求主线 · 功能分类表 · 每类复刻/优化/超越方案 · 跳过项 · 关键结论 · 数据口径与诚实性说明。

### 兼容性

纯流程 Markdown，不依赖任何特定平台，可移植到豆包智能体、Workbuddy 等支持 Markdown 指令的环境。

### License

MIT — 详见 [LICENSE](LICENSE)。

---


## 出品：刘洪光

本 skill 由真人出镜 IP「刘洪光」（安徽合肥）出品，归属 [lhg-skills](https://github.com/lhg-skills)。

- GitHub 主页：https://github.com/lhg-skills —— 全部 skill 开源在此，欢迎 star
- 微信交流：![刘洪光微信](docs/wechat-qr.png)
