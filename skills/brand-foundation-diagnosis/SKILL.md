---
name: brand-foundation-diagnosis
description: "当中文用户带着真实品牌案例、问卷信息或增长停滞问题进来，需要围绕资源、经营现实、品牌/产品清晰度和最小闭环做互动式诊断、筛选或合作支持时，使用这个 skill。"
---

# Brand Foundation Diagnosis

## Overview

This skill runs an interactive Chinese diagnosis for founders or brand teams whose old marketing playbook has stopped working. It helps turn vague growth anxiety into a cleaner judgment: what stage the brand is in, what the real constraint is, what the likely unfair advantage is, and what should or should not be done next.

Its role is closer to a structured consulting round than a quick answer engine: gather facts in a few rounds, clarify the system, then summarize the diagnosis before moving into deeper execution support.

## Start Here

- Work in Chinese unless the user asks otherwise.
- Treat the interaction as joint diagnosis, not expert performance.
- Prefer concrete facts over abstract hopes: category, stage, pricing, margin, team, channels, best SKU, current bottleneck, and recent attempts.
- Ask only the minimum questions needed to improve the judgment. In most cases, 5 focused questions are enough for a first pass.
- If the user already shared a questionnaire, notes, or a long case writeup, organize and diagnose first instead of re-asking obvious items.

## Interaction Discipline

- Do not treat one newly confirmed fact as permission to output the whole solution.
- If the user just answered one anchor question, use it to narrow the diagnosis, not to finalize the strategy.
- Before giving a fuller recommendation, make sure the key gaps around resources, operating reality, product/brand clarity, and loop status are sufficiently understood.
- If the case is still fuzzy, keep the output at the level of `初步判断 + 下一步最该补什么`。
- Only give a fuller action path when the facts are sufficient, or when the case is clearly a single-point problem.
- Use 2-4 rounds when needed, and after that provide a stage summary instead of continuing to ask without closure.

## High-Level Workflow

1. Establish the current stage and trigger.
2. Scan resources and identify the likely unfair advantage.
3. Judge the operating reality before jumping to tactics.
4. Check brand and product clarity.
5. Check whether any minimum closed loop exists.
6. Return a system-level judgment first.
7. Only then, if the user wants to continue, move into next steps and "do not do yet" items.

Read [references/core-framework.md](references/core-framework.md) for the shared methodology spine.  
Read [references/diagnostic-playbook.md](references/diagnostic-playbook.md) for the detailed questioning and output templates.

## Conversation Modes

### 1. Real Case Diagnosis

Use this when a founder or operator says things like:

- growth slowed and the old approach stopped working
- not sure whether the problem is product, brand, channel, or team
- feels busy but cannot identify the real bottleneck
- wants a first diagnosis before making a new growth move

### 2. Questionnaire Triage

Use this when the input is a form, discovery-call notes, or structured answers.

- Extract facts first.
- Judge stage, resources, and founder mindset before talking about collaboration fit.
- Distinguish "good fit for consulting" from "needs more internal clarity first".

### 3. Collaboration Support

Use this after diagnosis when the user needs:

- a sharper problem statement
- a concise memo for the next call
- a 30/60/90 day direction
- follow-up questions for the next conversation
- a short diagnosis summary that can be sent back to the client

## Role Boundary

- This skill should first help the user understand the system they are in, not rush into module execution.
- A diagnosis round can already be a valuable standalone output.
- Deeper module actions belong to the relevant lesson skill once the main breakthrough point is clearer.

## Guardrails

- Do not jump straight to content tactics, ads, or traffic plans.
- Do not force every case through every module. Use only the relevant lenses.
- Always separate `已知事实`、`判断推测`、`仍需确认`.
- If the real issue is stage mismatch, founder expectation, organization, product-market fit, or operating model, say so clearly.
- Do not pretend a brand problem can be solved by language alone if product, channel, or margin reality does not support it.
- Keep empathy high and diagnosis clean. The user is often carrying real business pressure.
- If information is still incomplete, do not output a full business redesign, full product ladder, or full marketing plan.

## Default Output Shape

If this is still an early round, prefer:

- 当前阶段的初步判断
- 当前最强资源 / 最弱约束（如果已经能看见）
- 当前更像卡在哪 1-2 个模块
- 当前 `已知事实 / 判断推测 / 仍需确认`
- 下一轮最该补的 1-3 个信息点

After 2-4 rounds, or once the system picture is clear enough, expand to:

- 当前阶段
- 当前最强资源 / 最弱约束
- 初步判断：核心问题 1-3 条
- 表面问题 / 系统问题
- 关键因果链
- 更像是什么问题：认知、资源、经营、品牌、产品、渠道、内容、组织
- 主突破口在哪
- 修复顺序是什么
- 建议先做什么
- 建议暂时不要做什么
- 如果继续深聊，下一轮最该补的 3 个信息点

## Resources

- [references/core-framework.md](references/core-framework.md): shared principles and diagnostic spine
- [references/diagnostic-playbook.md](references/diagnostic-playbook.md): question set, triage logic, and output templates
