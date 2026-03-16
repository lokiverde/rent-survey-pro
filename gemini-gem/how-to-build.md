# How to Build Your Own Gemini Gem
## Step-by-Step Guide for Non-Technical Users
**By Tony Self | TechTony.co**

---

## What is a Gemini Gem?

A Gem is Google's version of a custom AI assistant. You give it specific instructions, and it follows them every time you use it.

**The big advantage:** Gemini can search the web FOR FREE. No paid subscription required for basic use.

**Examples:**
- A research assistant that always cites sources
- A rent analyzer that pulls live listing data
- A content writer that matches your brand voice

**Requirements:** Google account (free tier works!)

---

## Step 1: Open Gem Manager

1. Go to [gemini.google.com](https://gemini.google.com)
2. Sign in with your Google account
3. Click **"Gem manager"** in the left sidebar (or go directly to [gemini.google.com/gems](https://gemini.google.com/gems))
4. Click **"New Gem"**

---

## Step 2: Configure Your Gem

### Name
Keep it clear and descriptive.
- ✅ "Rent Survey Analyst"
- ✅ "Meeting Notes Summarizer"
- ❌ "Test Bot 3"

### Instructions
This is where you tell the Gem how to behave. Be specific about:
- Its role/persona
- The task it performs
- How to format responses
- Any rules or constraints

**Simple Template:**

```
You are [ROLE]. 

When a user asks about [TOPIC], you should:
1. [First action]
2. [Second action]
3. [Third action]

Format your response as:
[Describe the format]

Always:
- [Rule 1]
- [Rule 2]

Never:
- [Anti-rule 1]
- [Anti-rule 2]
```

---

## Step 3: Save Your Gem

1. Click **"Save"**
2. Your Gem appears in your Gem Manager

To use it:
- Click the Gem from your Gem Manager
- Start chatting — it remembers its instructions

---

## Step 4: Share Your Gem (Optional)

1. Open your Gem
2. Click the **three dots** menu (⋮)
3. Click **"Share"**
4. Choose **"Anyone with the link"**
5. Copy the link

**Note:** Sharing may require Gemini Advanced in some regions. Test your link.

---

## Example: Complete Gem Setup

### Name
Rent Survey Analyst

### Instructions
```
You are Rent Survey Analyst, a real estate AI that helps investors determine market rent for properties.

## YOUR JOB
When given a property address:
1. Search for the property details (beds, baths, sqft)
2. Find 5 comparable rentals within 1 mile
3. Analyze the rent range
4. Give a specific rent recommendation

## IF DETAILS ARE MISSING
If the user only gives an address, search for it first. If you can't find details, ask:
- How many bedrooms?
- How many bathrooms?
- Property type (house, condo, apartment)?
- Condition?

## OUTPUT FORMAT

## 🏠 RENT SURVEY: [Address]
**Date:** [Today]

### Comparable Rentals Found
| # | Area/Address | Bed/Bath | Asking Rent | Notes |
|---|--------------|----------|-------------|-------|
| 1 | | | | |
| 2 | | | | |
| 3 | | | | |
| 4 | | | | |
| 5 | | | | |

### Analysis
[What the data shows - 2-3 sentences]

### Recommendation
- **Market Rent:** $X,XXX/month
- **Range:** $X,XXX - $X,XXX
- **Confidence:** High/Medium/Low
- **Why:** [Brief explanation]

---
*Created by Rent Survey Analyst | TechTony.co*

## RULES
- Always search for real, current data
- Cite your sources when possible
- If data is limited, say so
- Be helpful and professional

## AFTER THE SURVEY
Offer to:
- Compare to rent from 12 months ago
- Calculate cap rate if they share purchase price
- Analyze other units if multi-family
```

---

## Gemini vs. ChatGPT: When to Use Each

| Feature | Gemini Gem | ChatGPT GPT |
|---------|-----------|-------------|
| **Cost** | Free tier available | Requires $20/mo Plus |
| **Web Search** | ✅ Built-in free | ✅ With Plus subscription |
| **File Upload** | ✅ Yes | ✅ Yes |
| **Image Generation** | ✅ Yes | ✅ With DALL-E |
| **Sharing** | Link sharing | Link sharing + GPT Store |
| **Google Integration** | ✅ Native (Drive, Gmail) | ❌ Limited |

**Bottom line:** 
- Use Gemini for free web search and Google ecosystem
- Use ChatGPT for GPT Store distribution and Zillow integration

---

## Pro Tips for Better Gems

### 1. Tell It to Search
Unlike ChatGPT, Gemini searches automatically. But you can make it explicit:
> "Always search the web for current rental listings. Don't rely on training data."

### 2. Request Citations
> "Include source URLs for any data you reference."

### 3. Use Markdown Tables
Gemini handles tables well. Define your table format in instructions:
```
Present data in a markdown table with columns: Property | Beds | Rent | Link
```

### 4. Set a Persona
Give it personality:
> "You are professional but approachable. Keep responses concise. Use bullet points for lists."

### 5. Handle Edge Cases
> "If the search returns no results, suggest alternative search terms or broader criteria."

---

## Troubleshooting

**Gem doesn't search the web:**
→ Make sure you're using Gemini (not Gemini Code or other variants)
→ Add explicit instruction: "Search the web for current data"

**Gem forgets instructions:**
→ Keep instructions under 2000 characters for reliability
→ Put most important rules first
→ Repeat critical instructions at the end

**Sharing doesn't work:**
→ May require Gemini Advanced (paid) in your region
→ Alternative: Share the instructions as text for others to create their own

**Results are outdated:**
→ Add: "Only use data from the last 90 days"
→ Add: "Search for 'current listings' not historical data"

---

## Quick Start Checklist

- [ ] Go to gemini.google.com/gems
- [ ] Click "New Gem"
- [ ] Enter a clear Name
- [ ] Paste your Instructions
- [ ] Click Save
- [ ] Test with a few queries
- [ ] Refine instructions based on results
- [ ] Share link (if desired)

---

## Need Help?

This guide + the templates should get you 90% of the way there. 

For hands-on help building custom AI tools for your business:
→ [TechTony.co/contact](https://techtony.co/contact)

---

*Created by Tony Self | TechTony.co*
*Real Estate Broker | AI Strategist | Vistage Speaker*
