### "Exercise 1: Writing Your First Effective Prompts"

#### Learning Objectives

By the end of this exercise, you will:

1. Understand the core components of an effective prompt
2. Practice writing clear, specific prompts
3. Compare outputs from different prompt styles
4. Learn to iterate and refine prompts

#### Background: The Anatomy of a Good Prompt

A well-crafted prompt typically includes, not necessarily all of them in all cases:

- **Role**: Define who the AI should act as
- **Task**: Clearly state what you want
- **Context**: Provide relevant background information
- **Constraints**: Set boundaries (length, tone, format)
- **Examples**: Show what you want (for few-shot prompts)

General formula to keep in our mind is that 

```
[ROLE] + [TASK] + [CONTEXT] + [CONSTRAINTS] + [EXAMPLES]
```

## Exercise 1.1: Basic vs. Enhanced Prompts

### Scenario
You need a brief description of a new non-fiction book about urban gardening.

### Task A: Basic Prompt (Vague)

Copy this prompt into ChatGPT, Claude or similar

```
Write a book description about urban gardening.
```

**Refect on your observations:**
- Is it specific enough?
- Does it match what you need?
- What's missing?

### Task B: Enhanced Prompt (Specific)

Now try this improved version:

```
You are an experienced book marketing copywriter. Write a compelling 
150-word book description for a practical guide titled "The Vertical 
Garden Revolution" aimed at urban millennials living in apartments. 
The book covers container gardening, vertical growing systems, and 
year-round indoor cultivation. The tone should be inspiring yet 
practical, emphasizing sustainability and wellness benefits.
```

**Analysis Questions:**
1. Which components of the prompt formula were used?
2. What could be improved further?

## Exercise 1.2: Zero-Shot vs. Few-Shot Prompting

### Zero-Shot Prompt

Try this prompt without examples:

```
Write a catchy tagline for a mystery novel set in Victorian London.
```

### Few-Shot Prompt

Now provide examples to guide the style:

```
You are an experienced book marketing expert. Write a catchy tagline for a mystery novel set in Victorian London.

Here are examples of the style I want:

Example 1 (for a thriller): "Trust no one. Suspect everyone."
Example 2 (for a romance): "Two hearts. One impossible choice."
Example 3 (for a mystery): "Every lie has a witness."

Now create a tagline in this concise, dramatic style for my Victorian mystery.
```

## Exercise 1.3: Iterative Refinement

### Round 1: Initial Prompt

```
Create a table of contents for a book about social media marketing.
```

### Round 2: Add Context and Constraints

```
Create a table of contents for a book about social media marketing 
for small business owners with limited budgets. The book should have 
10 chapters, starting with fundamentals and progressing to advanced 
strategies. Focus on practical, actionable advice rather than theory.
```

### Round 3: Further Refinement

Based on the output from Round 2, add a follow-up prompt:

```
Revise the table of contents to include specific platform chapters 
(Instagram, LinkedIn, TikTok) and add a chapter on measuring ROI. 
Each chapter title should be action-oriented and benefit-focused.
```

**Learning Points:**
- How did each iteration improve the output?
- When should you refine vs. start over?

## Exercise 1.4: Your Turn - Create a Custom Prompt

### Challenge
Create a prompt for one of these publishing tasks:

**Option A:** Generate a back-cover blurb for a cookbook

**Option B:** Write an author bio for a debut novelist

**Option C:** Create chapter summaries for a business book


### Your Prompt Template

Fill in each component:

```
ROLE: [Who should the AI be?]

TASK: [What exactly do you want?]

CONTEXT: [What background info is relevant?]

CONSTRAINTS: [Length, tone, format, what to avoid?]

EXAMPLES (optional): [Show what you want]
```

Combine the components above into a complete prompt and run it to test the quality of the output 

**Self-Assessment:**
- [ ] Is the output relevant to my task?
- [ ] Does it match the desired length/format?
- [ ] Is the tone appropriate?
- [ ] Would I need to edit heavily, or is it usable?

## Good to create Prompt Engineering Checklist in your mind

Before submitting a prompt for a specific task, ask yourself:

- [ ] Did I choose the correct LLM tool or platform to start with?
- [ ] Have I defined a clear role for the AI?
- [ ] Is my task specific and actionable?
- [ ] Have I provided necessary context?
- [ ] Are my constraints clear (length, tone, format)?
- [ ] Would examples help clarify what I want?
- [ ] Have I specified what to avoid or exclude?

**Workshop Note:** Save your best prompts! You'll use them in later exercises and beyond.
