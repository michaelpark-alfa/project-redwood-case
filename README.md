# Project Redwood — Analyst Workflow Case Study

## Your Task

A credit analyst has sent you the following request. Build a small Python service that turns it into a repeatable, structured workflow.

---

### The Analyst's Request

> I need you to help me prep for tomorrow morning's IC on **"Project Redwood"** (middle-market software LBO, unitranche). Please pull together a 1-page credit memo that answers:
>
> - What's the real business + revenue model, and what's driving growth vs one-offs
> - How levered they are now and what leverage will look like post-deal
> - Whether the ARR / NRR story is legit, and any red flags in churn / cohort stuff
> - What the 3–5 biggest risks are and how we'd get comfortable
> - A quick comp / valuation sanity check (multiples are fine)
>
> I don't have time to read everything. Use the stuff in the `docs/` folder + the notes from the banker call.
>
> Also: I keep hearing "AI-native product" from management — I need a view on whether that's real differentiation or just marketing.
>
> **Constraints:**
> - Format it so it can be pasted into any doc / email (crisp, bullets ok)
> - If a number is uncertain, say it's uncertain, but still give me a best estimate
> - Call out anything that looks inconsistent across documents
> - Timebox this — I need something usable in 45 minutes
> - If you need clarifications, ask, but don't ask me 20 questions.

---

## What You're Building

A script (or small service) that:

1. **Clarifies** missing inputs / states assumptions before running
2. **Retrieves** relevant context from the `docs/` folder
3. **Produces** a structured JSON output a UI could render
4. **Renders** the report in a nicely formatted text
5. **Is easy to iterate on** when requirements change mid-way

## Files

```
/project-redwood-case/
├── README.md               ← you are here
├── docs/
│   ├── cim_excerpt.txt     ← CIM summary (~200 words)
│   ├── banker_call.txt     ← call notes (~200 words)
│   └── financials.txt      ← financial data table (~200 words)
├── schema_example.json     ← suggested output structure (optional hint)
├── starter.py              ← start here
└── .env.example            ← copy to .env and add your API key
```

## Success Criteria

- **v1 done:** end-to-end pipeline runs, produces valid JSON matching the schema
- **Iteration done:** handles one mid-session requirement change without breaking v1
- You explain your tradeoffs out loud as you go

## Timebox

**60 minutes total.** Ship something working. Perfect is the enemy of done.
