# Accord Tech Solutions — B2B Cold Email Offer Routing Guide

## Purpose

This file tells the agent how to review a prospect data list and recommend the **best-fit B2B cold email offer** for each company. For every company in the list, the agent reads the available data, infers the company type, likely pain points, and business needs, then assigns ONE primary offer (plus optional add-ons), scores its confidence, assigns a 0–100 priority score, and explains the reasoning. The final list is ranked so the team works the hottest prospects first.

This is a **routing and qualification** task, not a writing task. The agent's job here is to decide *what to offer*, not to write the emails.

---

## Our Cold Email Offers (the buckets to route into)

There are **four** possible outcomes for each company. Assign exactly one as the primary recommendation.

### 1. Done-For-You Cold Email (Full System / Full Outreach)
**What it is:** We handle everything end to end. The client does nothing. This includes secondary domain setup, warm-up, deliverability config (SPF/DKIM/DMARC), list building/enrichment, copywriting, sequence building, sending, inbox monitoring, reply handling, and reporting. "Complete cold email system" and "full outreach service" mean the same thing — this single done-for-you offer.

**Route here when the company:**
- Wants more pipeline/leads but has no in-house outbound team, or a thin one.
- Is B2B (sells to other businesses), with a deal size that justifies outbound (not low-ticket B2C).
- Has a clear ICP they sell to but lacks the time, tooling, or expertise to run outbound themselves.
- Is growth-stage, scaling, or recently funded (signal: hiring sales/SDR roles, new funding round).
- Sells SaaS, services, agencies, consulting, or any solution with a definable target buyer.

### 2. Infrastructure Setup Only
**What it is:** We build the technical foundation and hand it off. Secondary/lookalike domains, inbox creation, warm-up, SPF/DKIM/DMARC, List-Unsubscribe, deliverability verification — then the client (or their own team) runs the campaigns.

**Route here when the company:**
- Already has an in-house SDR/BDR or marketing team that writes and sends their own outbound.
- Is already sending cold email but has deliverability problems (landing in spam, low open rates, domain reputation issues).
- Has the people to run campaigns but lacks the technical setup or got burned by a misconfigured one.
- Explicitly wants to keep messaging/control in-house but needs the plumbing done right.

### 3. Related / Partial Cold Email Services
**What it is:** One or more standalone components rather than the full system. Use this when the company needs *part* of the puzzle. Possible components:
- **List building + CRM data enrichment** — for companies that have campaigns but bad/thin data.
- **Cold email copywriting / sequence writing** — for companies with infra + a list but weak messaging.
- **Deliverability audit + fix** — one-time diagnosis and repair of an existing setup.
- **Inbox warm-up management** — ongoing warm-up for teams that have everything else.

**Route here when the company:**
- Has most of an outbound motion working but a specific, identifiable gap.
- Doesn't need (or won't buy) the full done-for-you system, but has one clear weak point.
Always name *which* specific component(s) apply — don't just say "related services."

### 4. Not a Fit (flag + suggest an alternative Accord service)
**What it is:** Cold email is a poor match for this company. The agent must (a) flag it as a poor cold-email fit with a one-line reason, AND (b) suggest a better-fit Accord service.

**Route here when the company:**
- Is primarily B2C / consumer-facing (cold email to consumers is low-value and often non-compliant).
- Sells very low-ticket products where outbound economics don't work.
- Is in a sector where cold email is heavily restricted or culturally rejected.
- Is too small / pre-revenue / has no definable buyer to target.
- Already has a saturated, well-run outbound motion with no gap to fill.

**Alternative Accord services to suggest (match to the company's likely need):**
- **SEO / AEO** — for companies that need inbound visibility and organic traffic.
- **Social Media Marketing (SMM)** — for B2C/brand-led or audience-driven businesses.
- **Website Development** — for companies with a weak or outdated site.
- **Email Marketing (lifecycle/nurture)** — for companies with an existing audience/list to nurture (this is warm email, not cold).
- **Product Listing** — for eCommerce sellers (Amazon, Shopify, eBay).
- **Lead Generation (data only)** — for companies that just want a clean prospect list.

---

## How to Read the Data List

Your prospect lists typically include some mix of: company name, website, industry, company size / employee count, team size, contact name + title + email, tech stack / tools used, and recent signals (funding, hiring). Use whatever is present. The more fields available, the more confident the routing.

Map the raw data to routing signals like this:

| Data field | What it tells the agent |
|---|---|
| **Industry** | B2B vs B2C; deal size; whether cold email is viable/compliant in the sector. |
| **Company size / team size / employee count** | Whether they likely have an in-house outbound team. Rough guide: <20 employees → usually no team → lean **Done-For-You**. 20–200 → may have a small team → could be **Infrastructure** or **Partial**. 200+ → likely has a team → **Infrastructure** or **Not a fit** (already running it). |
| **Job title of contact** | Founder/CEO/Owner at a small company → buys Done-For-You. VP Sales / Head of Growth / Demand Gen → may want Infrastructure or Partial. Existing SDR/BDR leadership → already has a motion. |
| **Tech stack / tools** | If they already use Instantly, Smartlead, Apollo, Lemlist, Outreach, Salesloft, Clay → they're *already doing outbound* → route to **Infrastructure**, **Partial** (gap-fill), or **Not a fit** (saturated). If no outbound tools → greenfield → **Done-For-You**. CRM present (HubSpot/Salesforce) but no sending tool → good Done-For-You or Infra candidate. |
| **Recent signals (funding / hiring)** | New funding or actively hiring SDRs/AEs → strong buying signal, scaling pipeline → **Done-For-You**. Hiring a "Head of Growth" → may want to build in-house → **Infrastructure**. |
| **Website** | Quality and clarity of ICP. A clear B2B offer with a definable buyer → cold-email viable. Vague/consumer/no clear buyer → likely **Not a fit**. |

**When data is missing or ambiguous:** make the best inference from what's present, state your confidence (High / Medium / Low), and note what extra data would raise it. Never invent facts about a company.

---

## Primary Offer Selection (apply in order, stop at first match)

For each company, walk these checks top to bottom. **The first one that matches is the primary offer — stop there.** This ordering is itself the tie-breaker: when a company could plausibly fit two buckets, the earlier rule wins.

1. **Is it genuinely B2B with a viable deal size?** If no → **Not a Fit** (flag + suggest alternative). Stop.
2. **Are they already running outbound well with no visible gap?** (mature sending stack + dedicated team + no problem signal) → **Not a Fit** (saturated). Stop.
3. **Do they have an in-house team or sales motion to run campaigns themselves?** (mid/large size, sales/SDR titles, or outbound sending tools present). If YES, choose between Infrastructure and Partial using the rule below. If NO, skip to step 4.
4. **No team / thin team, wants leads, clear ICP, B2B?** → **Done-For-You (Full System)**. Stop.
5. **Everything else / unclear** → make best inference, mark confidence Low, default to the lightest-commitment offer that plausibly fits, and note what to verify.

### Full Outreach vs Infrastructure vs Partial — the deciding question

Once a company is B2B and viable, the choice between the three active offers comes down to **two questions answered in order**:

**Q1 — Can they run campaigns themselves?** (Do they have the *people* — a sales/marketing team, SDR/BDR titles, or evidence they already send outbound?)
- **NO → Done-For-You.** They need us to operate everything. This is the default for small companies (<20 employees), founder-led teams, and anyone with no outbound tooling.
- **YES → go to Q2.**

**Q2 — What is the ONE thing blocking them?** (They have the people; what's missing?)
- **The technical foundation is missing or broken** (no proper domains/warm-up, landing in spam, deliverability/reputation problems) → **Infrastructure Setup Only.** We build the plumbing; they run the campaigns.
- **The foundation is fine but one specific piece is weak** (bad/thin data, poor copy, no warm-up management) → **Related / Partial.** Name the exact component. If two-plus components are missing but they still want to run it themselves, lean toward a bundled **Partial**; if they'd rather hand it off entirely, escalate to **Done-For-You**.

**Tie-breaker summary:** No team → Done-For-You. Team + broken/missing infra → Infrastructure. Team + working infra + one gap → Partial. When still split between Infrastructure and Partial, choose **Infrastructure** if deliverability is at risk (it's the foundation everything else depends on), otherwise **Partial**.

---

## Confidence Scoring (define it, don't guess it)

Confidence reflects how much of the routing rests on hard data vs inference. Assign it by this rule:

- **High** — The fields that drive the decision are all present and point the same way. Specifically: industry/type is clear AND company/team size is known AND (tech stack OR a recent signal) is present, with no contradictions. The agent did not have to guess the deciding factor.
- **Medium** — The core decision is supported, but at least one supporting field is missing or inferred (e.g. size known and industry clear, but no tech-stack or signal data, so "do they have a team" is an educated guess).
- **Low** — The deciding factor itself had to be inferred from weak or partial data (e.g. only company name + website available), or fields conflict (e.g. tiny team but enterprise tooling).

Always state, in one short clause, **what would raise the confidence** (e.g. "Medium — would be High with tech-stack data").

---

## Priority Scoring (rank the list, work the hottest first)

After assigning an offer, give each company a **Priority Score from 0–100** so the team knows the order to work the list in. The score combines four weighted factors. Score each factor, multiply by its weight, and sum.

| Factor | Weight | How to score it (0–10) |
|---|---|---|
| **Fit strength** | ×3.0 | How cleanly the company matches its assigned offer. 10 = textbook fit, clear ICP, obvious need. 5 = fits but with caveats. 0 = Not a Fit. |
| **Buying signal** | ×3.0 | Recency/strength of intent. 10 = fresh funding or actively hiring SDRs/sales right now. 5 = some growth indicators. 0 = no signal at all. |
| **Deal size potential** | ×2.0 | Inferred contract value from company size, industry, and deal economics. 10 = larger company / high-ticket B2B. 5 = mid-market. 0 = tiny / low-ticket. |
| **Offer revenue potential** | ×2.0 | What the recommended offer is worth to Accord. Done-For-You = 10 (highest-value, recurring). Infrastructure = 6. Partial = 4 (varies by component). Not a Fit = 0. |

**Formula:** `Score = (Fit×3) + (Signal×3) + (DealSize×2) + (OfferRevenue×2)` → max 100.

**Priority bands:**
- **80–100 — Hot.** Work these first. Strong fit + live buying signal + high value.
- **60–79 — Warm.** Solid prospects; work after Hot.
- **40–59 — Lukewarm.** Worth a touch, lower urgency.
- **Below 40 — Cold / parking lot.** Includes most Not-a-Fit companies; revisit later or route to an alternative service.

A **Not a Fit** company scores low by design (Fit and Offer Revenue both 0), which correctly sinks it to the bottom of the cold-email list — but the agent still records the suggested alternative service so the lead isn't lost.

Note: scores are relative guides for sequencing, not precise valuations. Low-confidence routings should be treated as provisional scores until more data is gathered.

---

## Output Format

For a full list, return a **table** sorted by Priority Score (highest first), with these columns:

`Priority Score | Band | Company | Type | Recommended Offer | Add-ons | Confidence | Why | Pain Point | Alternative (if Not a Fit)`

For a single company or a detailed view, use this block:

```
Company: <name>
Industry / Type: <inferred>
Recommended Offer: <one of the 4 buckets — name it exactly>
Add-on components (if any): <e.g. list enrichment, copywriting>
Priority Score: <0–100> (<Band>)
  └ Fit <0–10> · Signal <0–10> · Deal size <0–10> · Offer revenue <0–10>
Confidence: <High / Medium / Low> — <what would raise it>
Why: <1–2 sentences tying the data to the decision>
Likely pain point: <the problem this offer solves for them>
If Not a Fit → Alternative Accord service: <which one + why>
```

End the analysis with a **summary**:
- Counts per bucket (e.g. "12 Done-For-You, 5 Infrastructure, 3 Partial, 4 Not a Fit").
- Counts per priority band (e.g. "6 Hot, 9 Warm, 5 Lukewarm, 4 Cold").
- The **top 5 priority targets** by score, named, as the recommended starting point for outreach.

---

## Guardrails

- **One primary offer per company.** Add-ons are fine, but commit to a single main recommendation.
- **Always justify with the data.** Every recommendation cites the specific field(s) that drove it.
- **Never fabricate company details.** If a signal isn't in the data, don't assume it — lower the confidence instead.
- **No spray-and-pray logic.** If a company has no definable buyer or no reason for outbound, it's Not a Fit, regardless of size.
- **Respect compliance reality.** B2C/consumer cold email is generally Not a Fit — route to SMM, SEO, or lifecycle Email Marketing instead.
- **Be honest about poor fits.** Flagging a company as Not a Fit and pointing them to a better service builds trust and protects deliverability/results — don't force a cold-email offer to fill a quota.

---
