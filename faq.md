# Frequently Asked Questions

## 1. What source materials can I provide?

You may provide public earnings-call notes, investor-relations records, announcements, structured research notes, financial highlights, or an existing draft pitch. For externally distributed output, the source should be public or independently verifiable.

## 2. What should I ask ChatGPT after loading the skill?

> 请根据以下公开纪要总结核心投资逻辑，执行合规脱敏，并按机构销售企业微信转发格式输出。

You may also specify a maximum character count, sector label, whether to include risk warnings, the business to emphasize, and whether exact public data should be retained.

## 3. How long will the output be?

The default is approximately 450 to 750 Chinese characters, usually containing three to five core logic paragraphs. The skill removes peripheral content first and does not mechanically shorten every paragraph at the expense of core logic.

## 4. Why are some details omitted?

The skill prioritizes information that materially affects earnings or valuation and can be safely distributed. It normally removes repeated facts, small businesses, distant optionality, customer lists, operating details without an earnings link, and sensitive or unverified information.

## 5. Will the skill preserve all important numbers?

Only numbers that are public, material, comparable, and necessary to explain the investment logic should be retained. Unannounced orders, customer-specific prices, internal forecasts, and undisclosed capacity plans must be removed or generalized.

## 6. How does the skill handle management guidance?

Guidance must be explicitly attributed using `公司预计`、`公司规划`、`公司目标` or `根据公司公开指引`. It must not be presented as completed or guaranteed performance.

## 7. How does the skill handle analyst estimates?

Estimates and scenario calculations must be labeled with `预计`、`测算`、`对应` or `在相关假设下`. Material assumptions and verification conditions should be retained.

## 8. Can customer names be included?

Only when the relationship has been publicly disclosed and remains relevant. When disclosure status is uncertain, replace the name with a general description or omit the relationship.

## 9. Can pending orders be mentioned anonymously?

Not necessarily. Removing the customer name does not make a material non-public order safe to disclose. If the order itself has not been publicly announced, omit it.

## 10. Can the output include a target price or expected share-price increase?

No. The default skill prohibits stock-price forecasts, percentage return predictions, and expressions such as `翻倍空间`.

## 11. Can the skill use strong bullish language?

The tone may be constructive but must remain restrained. Avoid `必然爆发`、`确定性极强`、`绝佳买点`、`毫无风险` and `至少翻倍`. The standard ending is `建议重点关注。`

## 12. What if the notes contain both public and private information?

Treat any item whose disclosure status cannot be confirmed as non-public. If private information is essential to the thesis and cannot be replaced with public evidence, do not include that thesis in the client-facing output.

## 13. How should I request a shorter version?

> 删除边缘逻辑，只保留最核心的盈利驱动；不要逐条机械缩句，核心逻辑保留完整解释。

## 14. How should I request a revision?

Examples:

- `保留核心逻辑的完整描述，删除边缘业务。`
- `第一条太短，请补充需求到利润的传导。`
- `删除未公告客户和订单信息。`
- `把公司指引与确定性业绩区分开。`
- `控制在600字以内，但不要压缩核心因果链。`

## 15. Does this skill replace a compliance review?

No. It is a drafting and first-pass de-sensitization tool. External securities communications remain subject to the institution’s formal compliance, research, and information-barrier procedures.

## 16. Does the skill independently verify numbers?

When browsing is enabled, it should verify material company-specific figures against exchange filings, CNINFO disclosures, financial reports and public investor-relations records before drafting. It should check the company and security code, period, unit, accounting scope and metric definition. If browsing is unavailable, uncertain exact figures should be omitted rather than assumed correct.

## 17. What happens if a research report conflicts with an official filing?

The official primary disclosure takes precedence. The skill should use the verified figure, exclude the conflicting figure, and alert the user outside the client-facing pitch. If the discrepancy cannot be resolved, the claim should be omitted.

## 18. How are analyst forecasts handled?

Analyst forecasts are not actual results and are not company guidance. They may be used only when clearly labeled as estimates or scenarios and when the assumptions are relevant. They should be removed when they rely on unverified orders, undisclosed capacity, private management targets or aggressive utilization assumptions.

## 19. How does the skill assess earnings quality?

When profit growth is a core argument, the skill should check material investment income, fair-value gains, government grants, impairment reversals, asset disposals and other non-recurring items. It must not attribute total net-profit growth to core operations when these items are material.

## 20. What common data-definition errors should be checked?

The skill should not mix annual and interim data, consolidated and parent-company results, gross and net profit, attributable and total net profit, or capacity, output, shipment, sales and order value. Planned capacity must also be separated from commissioned and effective capacity.
