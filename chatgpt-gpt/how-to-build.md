# How to Build Your Own Custom GPT (ChatGPT)
## Step-by-Step Guide for Non-Technical Users
**By Tony Self | TechTony.co**

---

## What is a Custom GPT?

A Custom GPT is your own AI assistant with specific instructions baked in. Instead of explaining what you want every time, you set it up once and it just works.

**Examples:**
- A rent survey bot that knows how to pull Zillow data
- A social media writer that matches your brand voice
- A contract analyzer that knows what red flags to look for

**Requirements:** ChatGPT Plus subscription ($20/month)

---

## Step 1: Open GPT Builder

1. Go to [chat.openai.com](https://chat.openai.com)
2. Click **"Explore GPTs"** in the left sidebar
3. Click **"Create"** in the top right corner

You'll see two tabs:
- **Create** — Chat-based setup (easier)
- **Configure** — Manual setup (more control)

**I recommend:** Start with Configure for full control.

---

## Step 2: Configure Your GPT

### Name
Pick something clear and memorable.
- ✅ "Rent Survey Pro"
- ✅ "Email Response Assistant"  
- ❌ "My Helper Bot v2 Test"

### Description
One sentence explaining what it does. This shows up in search.
> "Get professional rent surveys in 10 minutes using Zillow data."

### Instructions
**This is the most important part.** Tell the GPT:
- What role it plays
- How it should behave
- What steps to follow
- How to format responses

**Template:**

```
You are [ROLE]. Your job is to help users [MAIN TASK].

## YOUR PROCESS
1. [First step]
2. [Second step]
3. [Third step]

## OUTPUT FORMAT
Always respond with:
- [Format element 1]
- [Format element 2]
- [Format element 3]

## RULES
- [Important rule 1]
- [Important rule 2]

## TONE
[Describe the personality: professional, casual, friendly, etc.]
```

### Conversation Starters
These are example prompts users see when they open your GPT. Make them action-oriented:
- "Analyze this property: [paste address]"
- "Draft a response to this email"
- "Review this contract for red flags"

### Knowledge (Optional)
Upload files your GPT should reference:
- PDFs, documents, spreadsheets
- Your company guidelines
- Reference materials

**Note:** Uploaded files stay private to your GPT.

### Capabilities
Toggle what your GPT can do:
- **Web Browsing** — Search the internet (required for current data)
- **DALL-E** — Generate images
- **Code Interpreter** — Run code, analyze data, create charts

**For most business GPTs:** Turn ON Web Browsing, turn OFF the others.

### Actions (Advanced)
Connect to external APIs. Skip this for now — it requires technical setup.

---

## Step 3: Test Your GPT

1. Click **"Preview"** in the top right
2. Try your conversation starters
3. Test edge cases — what if someone asks something unexpected?
4. Refine your instructions based on results

**Common fixes:**
- GPT too verbose? Add: "Keep responses under 200 words unless asked for more detail."
- GPT not following format? Be more explicit in your instructions.
- GPT hallucinating? Add: "If you don't know, say so. Don't make up information."

---

## Step 4: Save and Share

1. Click **"Save"** in the top right
2. Choose visibility:
   - **Only me** — Private
   - **Anyone with a link** — Shareable but not searchable
   - **Everyone** — Listed in GPT Store

3. Click **"Save"**
4. Copy the share link

---

## Step 5: Update the Links

Once you have your share URL (looks like `https://chatgpt.com/g/g-abc123...`), you can:
- Share it directly with people
- Add it to your website
- Include it in presentations

---

## Pro Tips

### 1. Be Specific About Format
Instead of: "Give me a summary"
Say: "Provide a 3-bullet summary with the main takeaway first"

### 2. Include Examples
Show the GPT exactly what good output looks like:
```
## EXAMPLE OUTPUT
**Property:** 123 Main St
**Market Rent:** $2,500/month
**Confidence:** High
```

### 3. Set Boundaries
Tell it what NOT to do:
- "Never give legal advice"
- "Don't make up data — use real sources"
- "If asked about competitors, stay neutral"

### 4. Add Personality
A little personality makes it memorable:
- "You're helpful but direct — no fluff"
- "Add a relevant emoji to each section header"

### 5. Iterate
Your first version won't be perfect. Use it for a week, note what's annoying, and refine.

---

## Troubleshooting

**GPT ignores my instructions:**
→ Move critical instructions to the top
→ Use bold or ALL CAPS for important rules
→ Repeat key instructions in different ways

**GPT is too slow:**
→ Reduce Knowledge file sizes
→ Simplify instructions
→ Turn off unused Capabilities

**GPT gives wrong information:**
→ Add: "Always cite your sources"
→ Add: "If unsure, say 'I'm not certain' rather than guessing"
→ Enable Web Browsing for current data

---

## Example: Complete GPT Setup

**Name:** Rent Survey Pro

**Description:** Get professional rent surveys in 10 minutes using Zillow data.

**Instructions:**
```
You are Rent Survey Pro, an AI real estate analyst.

## YOUR JOB
Help investors and landlords determine market rent by:
1. Pulling Zillow Rent Zestimate
2. Finding 5 comparable rentals
3. Analyzing the data
4. Giving a clear recommendation

## WHEN USER GIVES AN ADDRESS
1. Look up the property on Zillow
2. Get the Rent Zestimate
3. Search for 5 similar rentals within 1 mile
4. Create a comparison table
5. Recommend a rent with confidence level

## OUTPUT FORMAT
## 🏠 RENT SURVEY REPORT
**Property:** [Address]
**Date:** [Today]

### Zillow Rent Zestimate
$X,XXX/month

### Comparable Rentals
| # | Location | Bed/Bath | Rent | Notes |
|---|----------|----------|------|-------|

### Recommendation
- **Suggested Rent:** $X,XXX
- **Range:** $X,XXX - $X,XXX
- **Confidence:** High/Medium/Low

## RULES
- Use real Zillow data, not estimates
- If data is limited, say so
- Keep analysis concise but thorough

Created by Tony Self | TechTony.co
```

**Conversation Starters:**
- "Give me a rent survey for [address]"
- "What should I charge for rent at my property?"
- "Is my current rent below market?"

**Capabilities:** ✅ Web Browsing

---

## Ready to Build?

Go to [chat.openai.com/gpts/editor](https://chat.openai.com/gpts/editor) and start creating.

Questions? → tony@techtony.co

---

*Created by Tony Self | TechTony.co*
*Real Estate Broker | AI Strategist | Vistage Speaker*
