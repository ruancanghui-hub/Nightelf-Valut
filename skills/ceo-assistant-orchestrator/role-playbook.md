# Role Playbook

## Purpose

Define clear boundaries for each role so orchestration stays fast, accountable, and low-friction.

## Collaboration Rules

- One task has one owner.
- Collaborators provide inputs; they do not replace owner accountability.
- Reviewer focuses on risk and quality gates, not redoing implementation.
- Handoffs must include: context, output artifact, open risks, next deadline.

## Meeting Speaking Protocol

For brainstorming meetings, each speaking role follows the same format:
- Focus point: what this role optimizes for
- Proposal: preferred solution path
- Risk alert: major downside or failure mode
- Dependency: what must be true to execute

Core speaking roles (always first round):
- 商业顾问
- 产品经理
- 全栈开发
- 数据分析
- 法务合规

Optional speaking roles (task-dependent second round):
- 市场研究, 销售, SEO/增长
- UI/UX
- 测试/QA, DevOps
- 竞品分析
- AI

## Conflict Resolution Framework

When role proposals conflict, evaluate each option on:
- Business value
- Implementation cost
- Risk level

Resolution rule:
1. Prioritize options with highest business value under acceptable risk.
2. If value is similar, choose lower implementation cost.
3. If risk is high but unavoidable, require mitigation actions before execution.

## Moderator Rules (Assistant)

The assistant acts as meeting moderator and must:
- run core-role round before any final recommendation
- invite optional roles only when they add decision value
- prevent duplicate or repetitive proposals
- summarize conflicts explicitly
- synthesize one recommendation referencing at least two role inputs
- publish next actions with owner, deadline, and deliverable

## Role Boundaries

### 商业顾问 (`mckinsey-consultant`)
- Focus: strategy, market logic, prioritization rationale.
- Inputs: business goals, market signals, constraints.
- Outputs: strategic options, trade-off memo, recommendation.

### 产品经理 (`product-manager`)
- Focus: scope, requirements, roadmap, acceptance criteria.
- Inputs: strategy direction, user needs, engineering constraints.
- Outputs: PRD slices, backlog priorities, milestone definition.

### 全栈开发 (`fullstack-developer`)
- Focus: feature delivery, architecture implementation, integration.
- Inputs: requirements, design specs, infra constraints.
- Outputs: code changes, technical notes, integration checklist.

### 测试/QA (`qa-expert`, `test-automator`)
- Focus: quality strategy, test coverage, regression prevention.
- Inputs: feature scope, risk assumptions, environments.
- Outputs: test plan, automated checks, defect reports.

### DevOps (`devops-engineer`)
- Focus: CI/CD, runtime stability, observability, release safety.
- Inputs: deployment needs, scaling expectations, SLO targets.
- Outputs: pipeline updates, deployment plan, rollback playbook.

### UI/UX (`ui-designer`, `ux-researcher`, `frontend-ui-ux-engineer`)
- Focus: usability, interaction quality, interface implementation fidelity.
- Inputs: user segments, product goals, brand constraints.
- Outputs: UX flows, UI specs, frontend interaction refinements.

### 市场研究 (`market-researcher`)
- Focus: segment insight, trend scanning, demand validation.
- Inputs: target market, hypotheses, competitive context.
- Outputs: research summary, personas, opportunity sizing.

### 销售 (`sales-engineer`)
- Focus: buyer fit, sales enablement, objection handling.
- Inputs: product capabilities, pricing posture, customer profile.
- Outputs: sales narrative, demo flow, objection-response matrix.

### SEO/增长 (`seo-specialist`, `content-marketer`)
- Focus: organic acquisition, content leverage, funnel lift.
- Inputs: target keywords, audience intent, content assets.
- Outputs: SEO plan, content calendar, growth experiments.

### 数据分析 (`data-analyst`, `data-scientist`)
- Focus: metric definition, decision analytics, model-driven insight.
- Inputs: event data, business KPIs, experiment logs.
- Outputs: KPI dashboard spec, analysis report, forecasting notes.

### 法务合规 (`legal-advisor`, `compliance-auditor`)
- Focus: regulatory risk, contractual exposure, compliance readiness.
- Inputs: product/process changes, jurisdiction context, policy needs.
- Outputs: legal risk memo, compliance checklist, remediation actions.

### 竞品分析 (`competitive-analyst`)
- Focus: competitor strategy, positioning gaps, differentiation signals.
- Inputs: product category, known competitors, target segment.
- Outputs: competitor matrix, SWOT summary, response options.

### AI (`ai-engineer`)
- Focus: AI feature design, model integration, quality and safety.
- Inputs: use case, data constraints, latency/cost targets.
- Outputs: AI architecture proposal, evaluation criteria, implementation plan.

## Standard Handoff Template

```markdown
Handoff:
- From role:
- To role:
- Objective:
- Delivered artifact:
- Decisions made:
- Open risks:
- Required next action:
- Deadline:
```

## Escalation Triggers

Escalate to orchestration layer when:
- no clear owner after scoping
- two or more owners have conflicting priorities
- timeline slips threaten P0 outcomes
- compliance or legal blockers affect release
