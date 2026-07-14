# AI-Pengfei-Solo-Campus-Brand
AI低碳能源科普内容生成与校园传播风控系统 | AI先锋未来人才大赛｜鹏飞集团校招雇主品牌真实命题

> 本项目基于鹏飞集团企业真实赛题，构建一套「数据洞察→AI内容生产→合规管控→精准校园传播」完整闭环方案，借助大模型、SQL数据分析，破除传统能源企业刻板印象，打造面向高校Z世代的年轻化雇主品牌传播体系。

## 📌 项目概述
鹏飞集团创立于1993年，总资产1500亿元，员工3万余名，正从传统民营能源企业向绿色低碳科技企业转型，布局氢能全产业链、零碳智慧物流、氢能装备制造、5G数智应用等新兴赛道。
在校招校园传播场景中企业面临四大现实挑战：
1. **刻板印象固化**：高校学生普遍将鹏飞认知为重化工传统企业，不了解氢能、零碳转型新兴业务；
2. **内容适配不足**：官方宣传文风正式，难以适配小红书、B站、高校社群等年轻人主流平台；
3. **精准触达缺失**：不同专业、年级学生信息偏好差异大，统一素材传播效率低下；
4. **内容合规风险**：轻量化科普内容存在专业失真、跨平台、跨地域传播舆情隐患。

本项目依托AI大模型提示词工程、SQL校园用户画像分析，配套完整合规风控体系与落地方案，实现能源科普内容轻量化批量生产、分层精准校园传播，助力鹏飞集团塑造科技化、年轻化雇主品牌。

## 🧩 三大核心模块（仓库目录一一对应）
### 1. AI大模型内容生成模块｜`/prompt`
针对不同社交平台定制标准化Prompt模板，实现氢能&零碳科普文案批量生成：
- `xiaohongshu-hydrogen-post.md`：小红书轻量化科普笔记模板
- `bilibili-video-script.md`：B站短视频剧情脚本模板
- `hydrogen-prompt-template.md`：氢能科普基础通用提示词库

✅ 价值：将晦涩能源专业知识场景化转译，降低理解门槛，产出适配Z世代传播的原创内容。

### 2. SQL校园用户画像数据分析模块｜`/sql`
通过量化数据分析挖掘高校学生能源认知差异，为精准传播提供数据支撑：
- `user-portrait-analysis.sql`：校园学生认知画像统计分析脚本
- `sql-analysis-result.md`：数据分析结论文档
- `major-cognition-chart.png`：各专业学生能源认知可视化对比图表

✅ 价值：定位文科群体等认知薄弱人群作为重点传播对象，解决广撒网式低效传播问题。

### 3. 合规风控与校园传播方案模块｜`/docs`
全套可落地项目文档、行业调研与合规规范：
- `opening-report.md`：项目完整开题报告（包含行业数据、竞品对标、技术路线）
- `research-note.md`：行业政策、氢能产业报告、Z世代求职用户调研笔记
- `competitor-case-analysis.md`：国内外能源企业校园雇主品牌竞品案例拆解
- `compliance-guide.md`：年轻化科普内容合规指引、内容审核模板
- `references.md`：权威行业报告、文献、调研数据参考文献清单

## 🛠️ 技术栈
- SQL：校园用户画像数据统计、认知分层与可视化分析
- LLM Prompt工程：标准化模板驱动AI低碳科普内容批量生成
- Markdown：结构化项目文档沉淀
- PPT：赛事答辩演示材料（存放于 `/ppt`）
- 剪映：路演演示视频后期制作

# AI-Pengfei-Solo-Campus-Brand
AI Low-Carbon Energy Popular Science Content Generation & Campus Communication Risk Control System
AI Pioneer Future Talent Competition | Real Enterprise Challenge: Pengfei Group Employer Brand Campus Recruitment

> Based on the real proposition from Pengfei Group, this project builds a complete closed-loop solution:
**User Data Insight → AI Content Creation → Compliance Control → Targeted Campus Communication**.
By leveraging Large Language Models and SQL user portrait analysis, the project helps eliminate the stereotyped impression of traditional energy enterprises and constructs a youth-oriented employer brand communication system targeting Generation Z university students.

## Project Overview
Founded in 1993, Pengfei Group is a large green low-carbon technology enterprise with total assets of 150 billion RMB and over 30,000 employees. The group is undergoing strategic transformation from a traditional private energy enterprise to a clean low-carbon tech enterprise, covering hydrogen energy full industrial chain, zero-carbon smart logistics, hydrogen equipment manufacturing and 5G digital intelligent applications.

Pengfei Group faces four core communication challenges in campus recruitment:
1. **Solidified Stereotype**: Most university students perceive Pengfei as a traditional heavy chemical enterprise and have limited understanding of its emerging hydrogen energy and zero-carbon transformation businesses.
2. **Mismatched Content Style**: Official promotional materials are formal and rigid, poorly adapted to mainstream platforms favored by young people including Xiaohongshu, Bilibili and university communities.
3. **Lack of Targeted Reach**: Students from different majors and grades have divergent information preferences; unified content leads to inefficient mass communication.
4. **Potential Compliance Risks**: Lightweight popular science content carries risks including distorted professional information and public opinion hazards in cross-platform & cross-region communication.

This project adopts LLM prompt engineering and SQL campus user portrait analysis, matched with a complete compliance risk control system and executable communication plan. It realizes mass production of lightweight energy popular science content and hierarchical targeted campus promotion, helping Pengfei build a technology-focused, youth-friendly employer brand.

## Three Core Modules (Matching Repository Directory)
### 1. AI Content Generation Module | `/prompt`
Standardized prompt templates customized for different social platforms to support batch generation of hydrogen energy & zero-carbon popular science articles.
- `xiaohongshu-hydrogen-post.md`: Lightweight popular science note template for Xiaohongshu
- `bilibili-video-script.md`: Short video storyline script template for Bilibili
- `hydrogen-prompt-template.md`: General prompt library for hydrogen energy popular science

✅ Value: Translate obscure professional energy knowledge into scene-based, easy-to-spread content adapted for Generation Z audiences.

### 2. SQL Campus User Portrait Analysis Module | `/sql`
Quantitative data analysis to identify differences in university students’ awareness of energy industries, providing data support for targeted communication.
- `user-portrait-analysis.sql`: Statistical script for campus student cognition portrait analysis
- `sql-analysis-result.md`: Documentation of data analysis conclusions
- `major-cognition-chart.png`: Visual comparison chart of energy cognition among students of various majors

✅ Value: Identify low-awareness groups (e.g., liberal arts students) as priority communication targets and eliminate inefficient broadcast-style promotion.

### 3. Compliance Risk Control & Campus Communication Scheme Module | `/docs`
Complete executable project documents, industry research and compliance specifications.
- `opening-report.md`: Full project opening report including industry data, competitor benchmarking and technical roadmap
- `research-note.md`: Notes on industrial policies, hydrogen energy industry reports and Generation Z job-seeking user surveys
- `competitor-case-analysis.md`: Case study of campus employer brand communication from domestic and international energy enterprises
- `compliance-guide.md`: Compliance guidelines and content review templates for youth-oriented popular science content
- `references.md`: List of authoritative industrial reports, literatures and survey sources

## Tech Stack
- SQL: Statistical analysis, cognitive stratification and visualization of campus user portraits
- LLM Prompt Engineering: Template-driven batch generation of low-carbon energy popular science content
- Markdown: Structured documentation management
- PPT: Competition presentation slides (stored under `/ppt`)
- Jianying: Post-production for roadshow demo videos
