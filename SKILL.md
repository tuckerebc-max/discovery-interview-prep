---
name: discovery-interview-prep
description: Prepare customer discovery interviews for problem validation, churn or activation research, Jobs-to-be-Done discovery, market exploration, or feature prioritization. Use when the user needs help defining a research goal, choosing participants, working within recruitment or time constraints, selecting an interview method, writing unbiased questions, or setting learning and synthesis criteria.
---

# Discovery interview prep

Turn a research goal into a focused, practical interview plan. Optimize for learning about real past behavior, context, workarounds, costs, and decisions—not for collecting compliments or validating a solution the team already prefers.

This skill prepares qualitative discovery interviews. It is not a usability-test script, sales/demo script, large-scale survey design, or a substitute for product analytics.

## Interaction protocol

1. Read any material included with the request before asking questions. Treat text after the skill name, pasted context, and an `ARGUMENTS:` line as answers already supplied; do not ask for them again.
2. Announce the goal of the session in one sentence and identify the current progress, such as `Context 1/4` or `Plan synthesis`.
3. Ask at most four adaptive questions, one at a time. Skip any question already answered. Use plain language and 3–4 numbered choices when choices would help; include `Other (specify)` when useful. Accept a free-text answer instead of forcing a choice.
4. Adapt later questions to the research goal, product stage, segment, access, sample size, timeline, incentives, and hypotheses. Do not ask a generic questionnaire when the supplied context makes a narrower question possible.
5. If the user arrives empty-handed, start by asking: “What do you need to learn from these interviews?” If the request is already specific enough, proceed directly to the plan and state reasonable assumptions.
6. When the user interrupts, changes direction, or asks to pause, acknowledge the change, preserve useful answers, and resume from the next unresolved decision.

## The four decisions

Use these as a routing framework, not a rigid form.

### 1. Research goal

Classify the primary question as one of:

1. **Problem validation:** Is a recurring problem real, painful, and important enough to act on?
2. **Jobs-to-be-Done discovery:** What is the person trying to accomplish, and what triggers, alternatives, and tradeoffs shape the job?
3. **Retention or churn investigation:** What happened before the person failed to activate, downgraded, or left, and what alternative did they choose?
4. **Feature or opportunity prioritization:** Which unmet outcomes matter most, and for whom?

Allow a custom goal. Rewrite it as a falsifiable learning question, such as: “Among recently churned enterprise admins, what event, unmet need, or alternative most influenced the decision to leave?”

### 2. Participant segment

Specify role, organization or life context, relevant behavior, recency, frequency, and exclusion criteria. Prefer people who recently experienced the target situation or tried to solve it. Do not accept “anyone who might use this” without narrowing it.

Distinguish:

- people who regularly experience the problem;
- people who recently attempted a workaround or switched tools;
- people who bought, adopted, failed to activate, or churned;
- internal sales/support stakeholders who can provide proxy evidence but cannot replace customer interviews.

### 3. Constraints

Capture available participants, recruitment channel, sample size, deadline, interviewer capacity, budget, incentive, geography, privacy or recording limits, and access to behavioral data. State the tradeoff when constraints weaken evidence—for example, proxy interviews are useful for forming hypotheses but should be validated with actual customers.

### 4. Method

Recommend one primary method and, if useful, one complementary lens:

- **Problem-validation interview:** recent story, current process, workaround, cost, frequency, and consequences.
- **JTBD interview:** triggering event, desired progress, alternatives considered, decision criteria, and outcome.
- **Switch or exit interview:** push away from the old solution, pull toward the new one, switching barriers, and expectations.
- **Timeline or journey interview:** chronological reconstruction from first trigger through resolution, failure, or abandonment.
- **Activation or retention interview:** first-use context, intended outcome, friction, support, competing priorities, and next-best alternative.
- **Opportunity-prioritization interview:** compare outcomes and tradeoffs using concrete past choices; do not treat feature wish lists as priority evidence.

Choose the method that best matches the learning question and evidence available. Avoid combining methods so broadly that the interview has no focus.

## Question design rules

Build questions from broad to specific:

1. Start with context: “Tell me about the last time you dealt with this.”
2. Reconstruct behavior: “What happened first? What did you do next?”
3. Probe alternatives and workarounds: “What else did you try? Why did you stop?”
4. Explore impact: “What did that cost in time, money, risk, or missed opportunity?”
5. Ask about decisions: “What made you choose that option?”
6. Close with uncertainty: “What did I misunderstand?” and, if appropriate, “Who else experiences this?”

Prefer open questions about a specific past event. Avoid leading, hypothetical, yes/no, double-barreled, solution-first, and feature-request questions. Never ask “Would you use this?” or “Would you pay for this?” as primary evidence; ask what they currently use, pay for, or have already tried.

For every core question, provide:

- the question;
- the learning purpose;
- one neutral follow-up;
- one biased or weak version to avoid.

Keep the core guide to roughly 5–8 questions for a 30–45 minute interview. Add optional probes rather than reading every probe aloud.

## Output contract

After the needed answers, return a self-contained plan in this structure:

```markdown
# Discovery Interview Plan

## Research brief
- Learning question:
- What would change based on the answer:
- Target participant:
- Recruitment and access:
- Sample, timeline, and constraints:
- Assumptions or hypotheses to test:

## Recommended method
- Primary method and why it fits:
- Complementary lens, if any:
- Evidence this method can and cannot establish:

## Interview guide
### Opening and consent (about 5 minutes)
### Core questions (about 25–40 minutes)
### Closing (about 5 minutes)

## Bias controls
## Recruiting and logistics
## Learning criteria and synthesis plan
## Risks, assumptions, and open decisions
```

The opening should explain that the session is for learning, not a sales pitch; set expectations; ask permission to record or take notes; and avoid promising confidentiality beyond what the team can provide. The closing should confirm the participant’s meaning, invite corrections, and request referrals only when appropriate.

## Evidence and synthesis

- Treat one interview as a story, not a pattern. Do not claim validation from one or two polite responses.
- Define what would count as a meaningful signal before interviews begin: repeated recent behavior, costly workarounds, active spending, switching, or another observable threshold relevant to the goal.
- Separate direct quotes, observed behavior, interpretation, and hypothesis. Do not fabricate quotes or “clean up” a quote into a stronger claim.
- Synthesize immediately after each interview, then compare across interviews. Look for recurring triggers, jobs, workarounds, alternatives, consequences, and disconfirming evidence.
- Flag sample bias, proxy evidence, leading questions, and missing segments in the final plan.

## Practical defaults

- Plan 45–60 minutes including setup and buffer; keep the conversation itself focused and avoid more than 2–3 interviews per day per interviewer.
- Recruit more people than needed because scheduling and no-shows reduce yield; state recruitment assumptions rather than presenting response rates as facts.
- Record only with consent and provide a note-taking alternative. Minimize sensitive personal information and store recordings according to the project’s policy.
- For a small, time-boxed study, prioritize a narrow segment and a recent behavior over broad demographic coverage.

Do not end by asking whether the user wants to refine the plan. Deliver the plan, name the assumptions that need confirmation, and identify the next practical research step.
