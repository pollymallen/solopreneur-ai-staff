# Module 2 Exercises: Customer Success Agent

Complete these exercises to build and test your CS agent.

---

## Exercise 1: Set Up Your CS Knowledge Base

**Goal:** Create the foundation for your FAQ system.

### Step 1: Create Knowledge Folder

Your starter repo should have `/knowledge/faq.md`. Open it and add your first category headers based on your business:

```markdown
# FAQ Knowledge Base

## Getting Started
[Questions for new customers]

## [Your Main Offer Name]
[Questions specific to your product/service]

## Account & Access
[Login, technical issues]

## Billing
[Payment questions]
```

### Step 2: Add Your First 3 FAQs

Think of questions you've answered more than once. Add them:

```
/cs-faq
Topic: [Common question you get]
Variations: [Other ways people ask this]
```

**Checkpoint:** You have at least 3 FAQ entries in your knowledge base.

---

## Exercise 2: Draft Real Support Responses

**Goal:** Use /cs-respond for actual customer communications.

### Step 1: Find a Real Question

Look at your recent emails, DMs, or support tickets. Find a real customer question.

### Step 2: Draft the Response

```
/cs-respond
Customer question: [Paste their actual question]
Context: [New customer? VIP? Frustrated? Happy?]
History: [Any relevant background]
```

### Step 3: Evaluate Using the Framework

Check if the response follows:
- [ ] ACKNOWLEDGE - Does it show understanding?
- [ ] ANSWER - Is the actual answer clear?
- [ ] EXPAND - Does it anticipate follow-ups?
- [ ] NEXT STEP - Is there a clear action?

### Step 4: Refine and Send

Edit as needed, then actually send it!

**Checkpoint:** You've sent at least one real email drafted by your CS agent.

---

## Exercise 3: Handle a Difficult Situation

**Goal:** Practice with a challenging customer scenario.

### Create This Scenario

```
/cs-respond
Customer question: "I've been trying to access the course for 3 days
and nothing is working. I've sent two emails with no response. This is
really frustrating - I'm starting to regret this purchase."

Context: Customer bought 5 days ago. You did respond once but they
didn't see it. They're frustrated but not unreasonable.
```

### Review the Response

- [ ] Does it lead with empathy?
- [ ] Does it take responsibility without being defensive?
- [ ] Does it solve the problem concretely?
- [ ] Is there an escalation flag?

### Compare to a Simple Question

Now try:
```
/cs-respond
Customer question: "What time is the live call on Thursday?"
Context: Happy, engaged customer who attends regularly
```

Notice how the tone differs while still following the framework.

---

## Exercise 4: Build an Onboarding Sequence

**Goal:** Create a welcome sequence for new customers.

### Step 1: Define Your Sequence

```
/cs-onboard
Customer type: [Your main offer - course buyer, coaching client, etc.]
Goal: [What success looks like after onboarding]
Emails needed: 4
Timeline: First 2 weeks
```

### Step 2: Review Each Email

For each email in the sequence:
- [ ] Is there ONE clear action?
- [ ] Does it build on the previous email?
- [ ] Does it sound human?
- [ ] Would you open this subject line?

### Step 3: Customize and Save

Edit the sequence to match your voice and offer.

Save to `/templates/onboarding-[offer-name].md`

**Checkpoint:** You have a complete onboarding sequence ready to implement.

---

## Exercise 5: The Knowledge Loop

**Goal:** Experience how FAQ and support work together.

### Step 1: Answer Without FAQ

Pick a question NOT in your FAQ:
```
/cs-respond
Question: [New question you haven't documented]
```

### Step 2: Create the FAQ Entry

After drafting the response:
```
/cs-faq
Topic: [The question you just answered]
Answer: [Use the response you just drafted as the base]
```

### Step 3: Answer Again With FAQ

Now pretend you get the same question again:
```
/cs-respond
Question: [Same question]
Note: Check the FAQ first
```

Notice how the second response is faster and more consistent.

**Checkpoint:** You've experienced the knowledge compounding effect.

---

## Reflection Questions

After completing these exercises:

1. **Support quality:** How did the responses compare to what you'd write from scratch?

2. **Time savings:** Estimate how much time you saved per response.

3. **Consistency:** Did responses maintain your voice across different situations?

4. **FAQ growth:** How many entries do you have now? What categories need more?

5. **Gaps:** What context or patterns should you add to your CS agent README?

---

## Bonus Challenges

### Challenge 1: Support Inbox Blitz

Set a timer for 30 minutes. Use `/cs-respond` to draft responses to every pending customer question. How many can you handle?

### Challenge 2: FAQ Audit

Look at your last month of support emails. What questions came up 3+ times? Add all of them to your FAQ.

### Challenge 3: Onboarding Variants

Create different onboarding sequences for:
- High-ticket clients (more personal touches)
- Self-service customers (more automated)
- Returning customers (skip the basics)

---

*Complete these exercises before moving to Module 3.*
