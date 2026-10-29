# equity-sales-pitch-skill
# 股票机构销售话术生成工具

【中文】
本项目是一套 ChatGPT 提示词技能，用于将公开业绩电话会纪要、投资者交流记录、研究笔记以及结构化公司更新材料，提炼为简洁的中文股票销售话术，可直接转发给机构投资者。

## 背景
本工具基于国内券商新能源与电力设备组实习生日常工作流设计。
原始会议纪要通常冗长、重复，混杂经营数据、管理层指引、客户信息、未公告订单与主观推演。机构销售团队需要更简短的输出，保留核心投资逻辑，同时剔除敏感或非核心信息。

该技能将原始纪要转化为可直接发企业微信的专业销售话术，实现：
- 识别2–5个最重要的业绩驱动因子
- 为每个驱动因子搭建完整因果传导链
- 剔除次要信息，而非简单压缩每一段文字
- 区分已披露事实、公司指引、分析师测算与未经证实信息
- 过滤可能属于重大未公开信息的内容
- 产出适配机构客户的简洁卖方话术

## 适用场景
✅ 适合输入：
- 公开业绩电话会文字稿
- 公开投资者交流记录
- 公开调研纪要
- 上市公司公告与财务要点摘要
- 基于公开信息的产业链研究笔记
- 撰写面向基金经理的简短机构销售推介
- 在保留核心逻辑前提下优化已有销售话术
- 脱敏订单、客户、报价、产能等敏感信息

❌ 不适用：
- 发布或传播重大未公开信息
- 生成目标价、短线交易观点
- 替代持牌券商正式合规审核流程
- 将管理层指引包装为确定业绩
- 未经核验，把私下交流内容转为对外投资推荐

## 使用方法
1. 在 GitHub 创建仓库，命名 `equity-sales-pitch-skill`
2. 上传本仓库全部6个文件
3. 在 ChatGPT 开启网页浏览
4. 把仓库链接发给 ChatGPT
5. 发送固定加载指令：
> Read all files in this repository and load this equity sales pitch skill.
6. 粘贴原始材料，要求总结核心投资逻辑

示例请求：
> 请根据以下公开电话会纪要总结核心投资逻辑，按机构销售转发格式输出，并执行合规脱敏。

## 标准输出格式
输出必须遵循如下结构：
> 【XX行业】重点关注：一句话总主线
>
> #第一条核心投资逻辑：完整说明需求变化、公司能力及业绩传导。
>
> #第二条核心投资逻辑：完整说明产品升级、竞争格局及业绩传导。
>
> 投资建议：总结核心驱动、验证指标及主要边界，建议重点关注。

输出最后一句话固定为：
> 建议重点关注。

## 写作原则
- 篇幅精简，满足企业微信直接转发
- 保留核心业绩驱动的完整传导逻辑
- 删除次要业务线与重复信息，不机械逐句压缩
- 优先级：业绩影响、业务重要性、信息可核验性
- 遵循：事实 → 作用机制 → 盈利传导
- 避免冗长公司介绍、流水账式纪要复述
- 禁用营销化、绝对化、强烈看多的情绪化表述

## 合规声明
本技能仅做首轮合规与脱敏筛选，**不能替代持牌证券机构正式合规审核流程**。

使用者必须保证：
- 所有对外表述均有公开信息支撑
- 未公告订单、客户身份、价格、产能规划、管理层目标需要删除或泛化处理
- 公司指引和已实现业绩严格区分
- 预测内容表述为情景/测算，不视为确定结果
- 最终输出符合证券法规、内部合规制度与信息隔离墙要求

信息公开状态无法确认时，直接省略该信息，不对外发布。

【English】
This repository contains a ChatGPT skill that converts public earnings-call transcripts, investor-relations records, research notes and structured corporate updates into concise Chinese equity sales pitches ready to send to institutional investors.

## Background
This workflow is built for interns covering new energy & power equipment sectors at Chinese securities firms.
Raw meeting notes are often verbose and repetitive, mixing operating metrics, management guidance, customer details, unannounced orders and speculative assumptions. Institutional sales teams need condensed write-ups that preserve core investment thesis while stripping sensitive and non-material content.

This skill transforms raw notes into WeCom-ready sales pitches by:
- Identifying 2–5 key earnings drivers
- Building complete causal chains for each driver
- Removing marginal content instead of compressing every paragraph uniformly
- Separating disclosed facts, company guidance, analyst estimates and unsubstantiated claims
- Filtering potentially material non-public information
- Generating concise sell-side language for institutional clients

## Use Cases
✅ Suitable inputs:
- Public earnings-call transcripts
- Public investor-relations records
- Publicly released meeting notes
- Corporate announcements & financial highlights
- Industry-chain research based only on public sources
- Drafting short sales pitches for fund managers
- Refining existing pitches while keeping core logic intact
- Desensitizing sensitive order, customer, pricing and capacity details

❌ Not intended for:
- Distributing material non-public information
- Producing price targets or short-term trading calls
- Replacing formal compliance review by licensed securities institutions
- Framing management guidance as guaranteed financial results
- Turning private conversations into external investment recommendations without verification

## Usage
1. Create a GitHub repository named `equity-sales-pitch-skill`
2. Upload all six files from this repo
3. Enable browsing in ChatGPT
4. Send ChatGPT your repo link
5. Send the loading prompt exactly:
> Read all files in this repository and load this equity sales pitch skill.
6. Paste source material and ask for core investment logic

Sample prompt:
> 请根据以下公开电话会纪要总结核心投资逻辑，按机构销售转发格式输出，并执行合规脱敏。

## Standard Output Structure
Output must follow this template:
> 【Sector Name】重点关注：One-sentence core thesis
>
> #Logic 1: Explain demand shift, company positioning and earnings transmission.
>
> #Logic 2: Explain product upgrade, competitive landscape and earnings transmission.
>
> 投资建议：Summarize core drivers, tracking metrics and risks, 建议重点关注。

The final sentence must be exactly:
> 建议重点关注。

## Writing Principles
- Keep it concise for direct forwarding via WeCom
- Preserve complete causal logic of core earnings drivers
- Cut peripheral business lines and redundant details; avoid mindless compression
- Prioritize earnings impact, business materiality and verifiability
- Follow the chain: fact → mechanism → financial transmission
- Skip lengthy company introductions and chronological meeting recaps
- Avoid promotional, absolute or aggressively bullish wording

## Compliance Notice
This skill only provides a first-pass desensitization filter. It **does not replace formal compliance review of a licensed securities firm**.

Users must guarantee that:
- All external claims are backed by public information
- Unannounced orders, customer identities, prices, capacity plans and management targets are removed or generalized
- Company guidance is clearly separated from realized results
- Forecasts are framed as estimates or scenarios, not certain outcomes
- Final outputs comply with securities laws, internal compliance policies and Chinese information-barrier rules

When the public status of a piece of information cannot be confirmed, omit it entirely.
