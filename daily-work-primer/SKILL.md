---
name: daily-work-primer
description: Daily morning planning for AI solo operators, independent builders, one-person companies, and self-directed workers. Use when the user wants to set today's work tone, prioritize the most important work, find the main contradiction, choose a daily battlefield, turn scattered tasks into a focused plan, create a not-doing list, or run a short daily iteration loop around what worked and what did not.
---

# Daily Work Primer

## Purpose

Help the user start the workday by turning scattered intent into a focused daily operating plan.

Optimize for direction, leverage, and execution. Do not create a bloated todo list. Help the user decide what matters today, what to protect, what to ignore, and how to improve the system by one small iteration.

## Conversation Flow

Run the primer as a short morning dialogue unless the user already supplied enough context.

1. Ask for today's raw inputs:
   - current state and energy
   - fixed meetings or constraints
   - open loops or urgent pressures
   - the larger goal they want today to serve

2. Run the iteration check:
   - What worked yesterday?
   - What did not work yesterday?
   - What should be kept, removed, or adjusted today?

3. Identify the main contradiction:
   - What is the most important stuck point?
   - Which problem, if solved, makes other tasks easier?
   - Where is the user treating symptoms instead of the root?

4. Choose the daily battlefield:
   - Pick one main work front for today.
   - Convert it into a concrete outcome.
   - Keep it small enough to finish or visibly advance today.

5. Prioritize the day:
   - Set one primary task.
   - Add up to three key tasks.
   - Add optional tasks only if they do not weaken the main battlefield.

6. Protect attention:
   - Name distractions, pseudo-work, and low-leverage tasks to avoid.
   - Include a not-doing list when the user is scattered or overloaded.

7. Match work to energy:
   - Put the hardest work in the user's best deep-work window.
   - Use low-energy windows for shallow processing, cleanup, messages, or recovery.

8. Close with a simple standard:
   - Define what would make today count.
   - Keep the standard observable, not motivational.

## Planning Principles

Use these principles as lenses, not as jargon to display.

- Important things first: prioritize work that changes the day or compounds over time.
- Main contradiction: find the root constraint behind the visible mess.
- Fewer battles: choose one main battlefield and a small number of supporting tasks.
- Completion state: rewrite vague tasks into observable done states.
- Not-doing list: protect the plan by naming what will not be touched today.
- Daily iteration: keep what worked, remove what failed, and make one practical adjustment.
- Energy fit: plan around real energy and calendar constraints, not fantasy capacity.
- Low-cost experiment: when uncertain, choose the smallest test that can create evidence.

For deeper inspiration and naming language, read `references/principles.md`.

## Output Format

Return the daily plan in this shape:

```markdown
## 今日基调
一句话定调。

## 今日主战场
今天最重要的一仗，以及为什么是它。

## 主要矛盾
当前最卡住推进的关键问题。

## 关键任务
1. 可观察完成态
2. 可观察完成态
3. 可观察完成态

## 不做清单
- 今天主动避开的干扰或伪工作

## 时间节奏
- 深度工作：
- 浅层处理：
- 缓冲/恢复：

## 每日迭代
- 保留：
- 剔除：
- 今天微调：

## 今日收盘标准
今天怎样算有效推进。
```

Adapt the headings to the user's language. If the user writes in English, output in English. If the user writes in Chinese, output in Chinese.

## Style

Be calm, direct, and practical. Sound like a work partner helping the user regain the day.

Avoid productivity theater. Avoid overplanning. Avoid turning the day into a long list of obligations.

When the user is vague, ask only the smallest number of questions needed to start. When there is enough signal, make a reasonable plan and invite correction.
