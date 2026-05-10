# Claude for B2B Go-To-Market Foundations — Skills

A small, focused set of Claude Code skills for B2B GTM work. Built and battle-tested on portfolio rollouts, then anonymised for the broader [Entrepreneurs' Organization](https://hub.eonetwork.org) community after the *MyEO Lunch & Learn — Claude for B2B Go-To-Market Foundations* on 24 April 2026.

## What's here

| Skill | What it does |
|-------|--------------|
| **[Asset Foundation Builder](asset-foundation-builder.md)** | Kennedy 13-row CSV + niche-brief MD from YouTube / web / Reddit / forums / podcasts / call transcripts. Pains, false beliefs, market size, jargon (use vs avoid), recognition quotes, where they gather, hooks. The upstream contract every other skill consumes. |
| **[Landing Page Builder](landing-page-builder.md)** | High-converting niche landing page + progressive signup flow. Bring your CI (hex codes, fonts, logo) — the skill is venture-agnostic. |
| **[Outbound Copy Manager](outbound-copy-manager.md)** | 3-email cold sequence with 5 opener variants for A/B testing. |
| **[Facebook Ads From Customer Transcripts](facebook-ads-from-customer-transcripts.md)** | Hook / body / CTA variants drawn from the customer's own language. Output as plain `PART N:` (EN) / `TEIL N:` (DE) text — paste-friendly to Notion, Docs, Meta Ads Manager. |
| **[Sales Script Creator](sales-script-creator.md)** | 6-phase discovery + closing script (Belfort + Hormozi + Kagan). Bilingual EN/DE. Pairs with the Asset Foundation CSV — every row maps into a script section. |

## How to use

1. **Run Asset Foundation Builder first** with your customer call transcripts (or YouTube / web / Reddit / forum / podcast scrape if call data is thin). Its output — a 13-row CSV plus a niche-brief MD — is the foundation for the other four skills.
2. **Then run Landing Page Builder, Outbound Copy Manager, Facebook Ads** — each takes the Asset Foundations as its input and produces a specific GTM asset.
3. **Customise** every `{PLACEHOLDER}` in the skill files for your venture. The skills are intentionally generic — they only become powerful once you fill them in with your customer data and your CI (hex codes, fonts, logo).
4. **Match landing-page CI to your existing brand** — when running Landing Page Builder, supply `{PRIMARY_HEX}`, `{HEADING_FONT}`, `{LOGO}` etc. up front. If you've shipped a landing page for an adjacent niche before, START from that file (`cp` + bulk-replace + 4–5 targeted Edits) — saves 30+ min and guarantees design fidelity.
5. **Run Sales Script Creator** with your customer call transcripts to produce the 6-phase discovery + closing script. Pairs with the Asset Foundation CSV — every row maps into a script section. EN or DE based on your `{LANGUAGE}` input.

## Companion: live coaching pipeline (Chris Erler)

Chris Erler ([Erler Ventures](https://erlerventures.com)) presented the third bottleneck at the EO event — turning sales-call transcripts into a nightly coaching loop with a 6-dimension scoring stack. His open-source blueprint:

- 👉 **[github.com/chris1928a/sales-leadership-board](https://github.com/chris1928a/sales-leadership-board)**

Forkable Python pipeline (~2,600 LOC), Close.com + HubSpot integrations, anonymised live dashboard, ICP rebuild artefacts.

## Companion: longer skill set

The full GTM skill catalogue lives at:

- 👉 **[pas-ventures/unleash-venture-skills-public](https://github.com/pas-ventures/unleash-venture-skills-public)** — niche research, drip campaigns, LinkedIn outreach, sales script creator, content engine, prospect list builder, plus the four skills bundled here. Same `{PLACEHOLDER}` model.

## Hosts

- **Phil Strohemann** — PAS Ventures · Project Unleash · pas@pas-ventures.com · [linkedin.com/in/phil-ber-cpt](https://www.linkedin.com/in/phil-ber-cpt/)
- **Manuel Hartmann** — The Sales Playbook · [linkedin.com/in/hartmannmanuel](https://www.linkedin.com/in/hartmannmanuel/)
- **Christoph Erler** — Erler Ventures · [linkedin.com/in/christopherler](https://www.linkedin.com/in/christopherler/)

## Frameworks underneath

- **Dan Kennedy** — *The Ultimate Sales Letter*, *Magnetic Marketing*
- **Alex Hormozi** — *$100M Offers* / *$100M Leads*
- **Robert Cialdini** — *Influence* (the 7 principles)
- **Russell Brunson** — *DotCom Secrets* / *Expert Secrets*
- **Jordan Belfort** — *Way of the Wolf*
- **Noah Kagan** — *Million Dollar Weekend*

## Validating Your Asset Bundle

Before pushing assets into paid channels or your sales pipeline, run these 5 checks. They're cheap, fast, and catch the failure modes that kill conversion before it starts. Most operators have one product / one niche — these checks are how you stress-test your single bundle from different angles before you spend a euro.

### 1. Quote-recognition test
Read your CSV's Row 4–5 verbatim to **3 real practitioners** in the niche (current customers, prospects, or even cold-outreach interview partners). Track recognition rate — i.e. unprompted *"yes, that's exactly me"* reactions.
- ≥70% recognition: foundation is solid.
- <70%: the language is yours, not theirs. Go back to sources, pull more verbatim.

### 2. Different-angles A/B
From your foundation, draft **3 different positioning angles** off the same Row 2 / Row 10:
- **Pain-led** (Rows 3–5 dominant) — "you're drowning in X"
- **Aspiration-led** (Row 2 + Row 12 dominant) — "imagine the day you stop drowning"
- **Contrast-led** ("everyone else does X, the best do Y") — Row 6 dominant

Run each with $100 budget on Meta to the same audience. Winner = CPL ≥50% below the losers. That's your master frame for the next 90 days. The losers tell you what your prospects don't believe yet — useful intel for nurture content.

### 3. Hook-density check
Each of your Top 5 Pains should yield **at least 2 distinct ad hooks**. If a pain only yields 1, it's not pain-rich enough — drop it from rotation, or go back to source corpus and dig deeper.

### 4. Cost-of-inaction sanity
Your Row 8 EUR/month (or USD/month) status-quo cost should be **5–10× your monthly subscription price**. If it's less, urgency won't carry — your offer doesn't pay for itself fast enough in the prospect's mental math. Either find more leak-points to add to the cost calculation, or reposition price.

### 5. Voice-borrowing audit
Print your landing page, ads, and discovery script side-by-side. Read them out loud.
- Does the language sound like the practitioner talking to themselves?
- Or does it sound like generic SaaS marketing?

If even 20% reads as outsider voice, strip until practitioner phrases dominate. The fastest fix: replace your own paraphrase with a verbatim quote from a transcript or the niche-brief's recognition-quote slots.

---

If you fail check 1 or 5, the foundation needs more work — go back to the corpus. Checks 2–4 are run after launch, mostly to optimize spend. Run check 1 weekly during the first quarter of a niche; run check 5 every time you change copy.

## License

MIT — fork freely. Credit appreciated, not required. Pull requests with improvements welcome.
