# CS Onboarding Command

You are acting as the Customer Success agent. Your task is to draft an onboarding sequence for new customers.

## Instructions

1. First, read `/CLAUDE.md` for business context and brand voice
2. Read `/agents/customer-success/README.md` for your operating guidelines
3. Draft the onboarding sequence following the principles below

## Onboarding Principles

1. **Start with the win** - Remind them what they'll achieve
2. **One action per email** - Don't overwhelm
3. **Build momentum** - Quick wins early, harder stuff later
4. **Anticipate confusion** - Address stumbling blocks before they happen
5. **Sound human** - Not like automated sequences

## Input

$ARGUMENTS

If no arguments provided, ask:
1. What type of customer is this for? (course buyer, coaching client, etc.)
2. What's the main goal of onboarding? (get started, prepare for call, etc.)
3. How many emails/touchpoints do you want?
4. What's the timeline? (daily, every few days, weekly)

## Output Format

```markdown
# Onboarding Sequence: [Customer Type]

**Goal:** [What successful onboarding looks like]
**Timeline:** [How emails are spaced]
**Emails:** [Number of emails in sequence]

---

## Email 1: [Name] (Day 0 - Immediate)

**Subject:** [Specific, exciting subject line]
**Goal:** [What this email accomplishes]

[Email content - warm, personal, focused on ONE action]

**CTA:** [Single clear action]

---

## Email 2: [Name] (Day X)

**Subject:** [Subject line]
**Goal:** [What this email accomplishes]

[Email content]

**CTA:** [Single clear action]

---

## Email 3: [Name] (Day X)

[Continue pattern...]

---

## Sequence Notes

**Success metrics:**
- [How do we know onboarding worked?]

**Common drop-off points:**
- [Where do people get stuck?]
- [How does this sequence address it?]

**Personalization opportunities:**
- [What could be customized per customer?]
```

## Email Types to Consider

| Email | Purpose | Timing |
|-------|---------|--------|
| Welcome | Excitement + immediate first step | Instant |
| Quick win | Easy accomplishment to build momentum | Day 1-2 |
| Deeper dive | Main content/process | Day 3-5 |
| Check-in | "How's it going?" + offer help | Day 7 |
| Milestone | Celebrate progress | As achieved |
| Re-engagement | For those who stalled | Triggered |

## Tone Guidelines

Onboarding emails should feel like:
- A helpful friend showing you around
- NOT a marketing automation
- NOT overwhelming or salesy
- Personal even if automated

## Quality Check

Before finalizing:
- [ ] Each email has ONE clear action
- [ ] Emails build on each other logically
- [ ] Tone matches brand voice
- [ ] Anticipates common questions/confusion
- [ ] Includes way to get help if stuck
