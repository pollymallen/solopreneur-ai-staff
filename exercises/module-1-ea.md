# Module 1 Exercises: Executive Assistant Agent

Complete these exercises to build and test your EA agent.

---

## Exercise 1: Set Up Your EA Context

**Goal:** Give your EA the context it needs to work effectively.

### Step 1: Update CLAUDE.md

Add an "EA Context" section to your CLAUDE.md:

```markdown
## EA Context

### Key Relationships
- [Name] - [Relationship, tone to use]
- [Name] - [Relationship, tone to use]
- [Name] - [Relationship, tone to use]

### Common Topics
- [Your main offer and price]
- [Current projects or launches]
- [Recurring topics]

### Scheduling Preferences
- [When you don't take meetings]
- [Typical meeting lengths]
- [Preferred scheduling tool]
```

### Step 2: Test the Context

Run this in Claude Code:

```
Read my CLAUDE.md and summarize what you know about my business
and key relationships. What would help you serve as my EA better?
```

**Checkpoint:** Claude should describe your business accurately and suggest useful additions.

---

## Exercise 2: Draft Your First Email

**Goal:** Use the /ea-email command for a real email.

### Step 1: Identify a Real Email

Think of an email you actually need to send:
- A follow-up from a recent conversation
- A response to an inquiry
- A check-in with a client

### Step 2: Run the Command

```
/ea-email
Recipient: [Real name and context]
Purpose: [What you want to accomplish]
```

### Step 3: Evaluate the Output

- [ ] Does it sound like you?
- [ ] Is the tone appropriate for this relationship?
- [ ] Is the length right?
- [ ] Is the call-to-action clear?

### Step 4: Give Feedback

Tell Claude what to adjust:

```
This is good but [feedback]. In the future for [this type of email],
remember to [pattern to remember].
```

**Checkpoint:** You should have a usable email draft (even if you edit it further).

---

## Exercise 3: Research a Real Person

**Goal:** Use /ea-research to prepare for a meeting or conversation.

### Step 1: Identify Someone to Research

Think of someone you're meeting with soon or want to know more about.

### Step 2: Run the Command

```
/ea-research
Topic: [Person's name and role/company]
Goal: [Why you need this research]
Depth: Quick overview / Moderate / Comprehensive
```

### Step 3: Review the Brief

- [ ] Are the key takeaways useful?
- [ ] Are sources cited?
- [ ] What's missing that you'd want to know?

### Step 4: Save the Research

If useful, save to your research folder:

```
Save this research brief to /research/people/[name]-[date].md
```

**Checkpoint:** You have a reusable research brief.

---

## Exercise 4: Prepare for a Meeting

**Goal:** Use /ea-meeting-prep for an upcoming meeting.

### Step 1: Identify an Upcoming Meeting

Pick a meeting this week that would benefit from preparation.

### Step 2: Run the Command

```
/ea-meeting-prep
Meeting: [What kind of meeting, with whom]
Context: [Any relevant background]
Goal: [What you want to accomplish]
```

### Step 3: Review the Prep Doc

- [ ] Is the context accurate?
- [ ] Are the talking points relevant?
- [ ] Are the suggested questions useful?
- [ ] What would you add?

**Checkpoint:** You're better prepared for your meeting than you would have been.

---

## Exercise 5: Create a Custom Command

**Goal:** Build your own command for a task you do repeatedly.

### Step 1: Identify a Repeatable Task

What do you do often that could be templated?
- Weekly newsletter draft
- Client check-in email
- Social media post
- Meeting notes summary

### Step 2: Create the Command File

Create `.claude/commands/[your-command].md`:

```markdown
# [Command Name]

You are acting as [role].
Your task is to [what this does].

## Instructions

1. Read `/CLAUDE.md` for context
2. [Your steps]

## Rules

- [Your rules]

## Input

$ARGUMENTS

If no arguments, ask:
1. [What you need]

## Output Format

[Your format]
```

### Step 3: Test It

```
/[your-command] [test input]
```

### Step 4: Refine

Run it a few times with different inputs. Adjust the command file based on what works.

**Checkpoint:** You have a working custom command that saves you time.

---

## Reflection Questions

After completing these exercises, answer:

1. **What worked well?** Which commands saved you the most time?

2. **What needs improvement?** What context or instructions should you add?

3. **What patterns emerged?** What updates should you make to CLAUDE.md?

4. **What else could be automated?** What other EA tasks could become commands?

---

## Bonus: EA Power-Ups

Once you're comfortable with the basics, try these:

### Chain Commands

```
First use /ea-research to research [person].
Then use /ea-email to draft a personalized outreach
that references something specific from the research.
```

### Batch Processing

```
I have 5 emails to send today. Here are the recipients and purposes:
1. [Person 1] - [Purpose]
2. [Person 2] - [Purpose]
...

Draft all 5 using /ea-email format for each.
```

### Template Building

```
Based on the emails I've asked you to draft this week,
what patterns do you notice? Draft an email pattern I
should add to my templates folder.
```

---

*Complete these exercises before moving to Module 2.*
