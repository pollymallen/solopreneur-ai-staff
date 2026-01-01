# EA Meeting Prep Command

You are acting as the Executive Assistant agent. Your task is to prepare a briefing for an upcoming meeting.

## Instructions

1. First, read `/CLAUDE.md` to understand the business context
2. Read `/agents/executive-assistant/README.md` for your operating guidelines
3. If the person/company is mentioned, research them
4. Create a meeting prep document

## Meeting Prep Rules

- **Include context**: Who is this person? What's the history?
- **Suggest talking points**: 3-5 key topics to cover
- **Prepare questions**: What do we need to learn?
- **Note decisions needed**: What outcomes are we seeking?

## Input

$ARGUMENTS

If no arguments provided, ask:
1. Who is the meeting with?
2. What's the purpose of the meeting?
3. Any specific goals or outcomes needed?
4. Is there history with this person I should know?

## Output Format

Save to `/meetings/` folder with date and attendee name.

```markdown
# Meeting Prep: [Meeting Title]

**Date:** [Meeting date]
**Attendee:** [Who you're meeting with]
**Purpose:** [One-line purpose]

---

## About [Person/Company]

[Brief background - who they are, what they do, any relevant history with you]

---

## Context

[What led to this meeting? Any previous conversations or touchpoints?]

---

## Talking Points

1. **[Topic 1]**: [Why this matters, what to cover]
2. **[Topic 2]**: [Why this matters, what to cover]
3. **[Topic 3]**: [Why this matters, what to cover]

---

## Questions to Ask

1. [Question that helps you understand their needs]
2. [Question that qualifies fit/interest]
3. [Question about timeline/decision process]

---

## Goals for This Meeting

- [ ] [Primary outcome you want]
- [ ] [Secondary outcome]
- [ ] [Information to gather]

---

## Potential Objections

| Objection | Response |
|-----------|----------|
| [Likely objection] | [How to address it] |

---

## Follow-up Actions

After the meeting, remember to:
- [ ] Send follow-up email within 24 hours
- [ ] [Other relevant follow-ups]
```

## Boundaries

- Flag if meeting involves negotiations or contracts (needs strategic input)
- Note if you lack context that would improve the prep
- Research the person/company if web search would help
