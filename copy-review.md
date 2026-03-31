# Copy Review — David Rodriguez Portfolio
_Review date: March 2026_

---

## Overview

The portfolio has a strong foundation. The visual writing is already confident — punchy titles, good rhythm, real personality. The main issues are: **jargon that slips in from product/growth-team thinking**, **sections that over-explain**, and a few **structural mismatches** in the referral case study.

The audience visiting this portfolio is mostly hiring managers, recruiters, and senior designers — not all of them will know what "trial-to-paid conversion," "D7 retention," or "CAC" mean. Even those who do will appreciate clearer writing.

---

## HOMEPAGE

### ✅ What's working
- Hero description: clean, personal, concrete
- About bio: authentic and specific without being a LinkedIn copy-paste
- Contact section: warm and to the point
- Marquee strip: personality comes through nicely

### 🔧 Small fixes

**Hero description:**
> Current: "Eight years experience across banking, fitness, streaming and food tech."
> Fix: "Eight years of experience..." (missing "of")

**PDF strip (below project cards):**
> Current: "Check older case studies from my time working at Gymondo. Available as PDF."
> Suggested: "There's more. Older work from my time at Gymondo is available as a PDF."

**Marquee — one item:**
> Current: "Cross-functional Friendly"
> Suggested: "Cross-functional" or "Works well with others" (the current phrasing sounds like a LinkedIn endorsement gone wrong)

---

## CASE STUDY 01 — NeoTaste Quests

### ✅ What's working really well
These are the strongest bits — don't change them:
- Problem title: *"Free trial users were redeeming one deal, then leaving — never discovering why they'd signed up."* Clear and human.
- User quote: *"I thought it was just a coupon app. I didn't realise I could explore restaurants by neighbourhood or save my favourites."* Perfect.
- Conclusion title: *"User motivation doesn't require expensive incentives. It requires clarity and small wins."* Best title on the page.
- Quest 04 card: *"This is the core value. This is why you're here."* Keep exactly as is.
- Key decision title: *"The reward debate: No free month, confetti wins"* — great.
- Lesson 02: *"Optional features need killer entry points."* Punchy and true.

---

### 🔧 What to fix

#### NeoTaste Context paragraph
> Current: "...while partner venues can adjust those deals to their capacity - increasing occupancy, revenue, and reaching new customers who haven't found them yet."

This second sentence is confusing — "adjust those deals to their capacity" is unclear. Suggested:

> "NeoTaste is a platform to discover restaurants, bars and cafés in major cities — mainly across Germany, with a growing presence in the UK, Netherlands, and Austria. Users get exclusive deals you can only find through NeoTaste. Partner venues use it to fill quieter tables and attract new customers."

---

#### Section 02 — Hypothesis title
> Current: "Guided feature discovery + early deal redemption = higher trial-to-paid conversion."

The formula structure is visually clean but the words are jargon-heavy. Suggested:

> "Show people the app's best features early. More of them will want to stay."

---

#### Section 02 — Hypothesis box (the "Our bet" block)
This is very long and repeats itself. Suggested trimmed version:

> **Our bet:** If we guide new users through the app's most important features — setting food preferences, saving restaurants, redeeming deals, leaving reviews — in a structured quest, they'll understand what NeoTaste is actually for. And they'll be more likely to pay for it.
>
> Our data backed this up: users who redeemed at least 2 deals during their free trial converted to paid members at 4× the rate of those who only redeemed 1. Most users never made it to that second deal — not because the app was bad, but because they never discovered it. The quest would change that.

_(Cut the competitor comparison from the hypothesis block — it belongs in Research & Analysis, where it already appears.)_

---

#### Section 03 — Research & Analysis title
> Current: "Competitor analysis + cohort data revealed the same pattern: guided onboarding drives trial-to-paid conversion."

Dry and full of jargon. Suggested:

> "Our data and the best apps in the world all pointed the same way."

---

#### Section 03 — Research & Analysis body, first paragraph
> Current: "...The pattern was consistent: all top-performing apps use guided workflows that gradually introduce features and ask for commitment (reviews, saved preferences, bookings) to lock users into habit loops."

"habit loops" is buzzword territory. Suggested:

> "...The pattern was consistent: all top-performing apps guide new users through their key features early, asking for small commitments along the way — reviews, preferences, bookings — so that using the app becomes second nature."

---

#### Section 03 — Finding card titles (too clinical)
| Current | Suggested |
|---|---|
| "2-Deal Conversion Threshold" | "The magic number was 2" |
| "Feature Discovery Gap" | "Most users never found a second deal" |
| "Competitor Patterns Consistent" | "The best apps all do this" |
| "Core Features Unlock Conversion" | "Power users all followed the same path" |

---

#### Section 04 — Stakeholder Management title
> Current: "Negotiating scope and winning buy-in across competing priorities."

This is pure corporate-speak. Suggested:

> "Getting everyone aligned before starting to build."

---

#### Section 04 — Stakeholder cards
The Engineering card has this in the Resolution field:
> "Kept state tracking simple: each quest just tracked completion boolean + timestamp. Integrated into existing user event system, no new infrastructure."

"completion boolean + timestamp" and "existing user event system" are implementation details — these belong in the Implementation Plan section, not here. The stakeholder card should focus on the *relationship*, not the code. Suggested resolution:

> "Kept the technical scope tight: each quest task simply tracked whether it was done, using the existing analytics setup. No new infrastructure needed. Rolling out to 25% of users first (their suggestion) let us validate before committing to a full launch."

---

#### Section 05 — Design Process title
> Current: "Five tasks designed to guide users through core features and reach the 2-deal conversion threshold."

Suggested:

> "Five steps to help users discover the app — and find their reason to stay."

---

#### Section 05 — Quest card copy, small fixes

**Quest 01:** "Establishes the value prop before anything else."
→ "Sets expectations before asking anything of the user."

**Quest 02:** "Feeds the recommendation algorithm and makes the next deals more relevant."
→ "Tells the app what you're into, so the deals it shows you are actually interesting."

**Quest 03:** "Builds your personal list and shows you control your own discovery."
→ "Start building your own list. The app gets more useful the more it knows about you."

**Quest 05:** "Builds community and locks you in as a contributor, not just a consumer."
→ "Builds community and turns you from someone who takes deals into someone who helps others find them." _(note: "locks you in" has a negative feel)_

---

#### Section 05 — Key Design Decision 01 title
> Current: "Number of tasks: Long internal discussions"
> Suggested: "Why 5 tasks — not 3 or 10"

#### Section 05 — Key Decision 03 title
> Current: "The levels system: Deal redemptions unlock achievement"
> Suggested: "The levels system: how you earn your badge"

#### Section 05 — Lesson 03
> Current: "Scope negotiations revealed the design discipline."
> Suggested: "The best constraints came from the negotiations, not the brief."

---

#### Section 05 — Implementation Plan (simplify or cut)
The implementation steps currently contain details like:
> "Simple booleans: quest_viewed, quest_started, quest_task_[1-5]_completed, quest_fully_completed."

This is developer-level detail that slows down the read and doesn't help anyone understand your work as a designer. **Suggested: remove this line entirely**, or replace the whole step with:

> "Quest progress was tracked through the existing analytics pipeline — no new backend infrastructure. Engineering kept it simple by design."

Similarly, "10 new semantic colors added to Umami (NeoTaste design system) - 2 per level (badge + confetti)" is fine, but "semantic color tokens" can just say "10 new colors — two per level (one for the badge, one for the confetti animation)."

---

#### Section 06 — Metrics intro
> Current: "The Quest system launched after a 3-week A/B test on 25% of new user traffic, measured against a control group (no quest) over a 60-day window."

> Suggested: "The Quest launched to 25% of new users first — tested against a group that saw nothing. After 60 days, the results were clear."

---

#### Section 06 — Metric label (overused phrase)
The label "Trial-to-paid conversion uplift (among users who engaged with quest)" appears under the +22% metric. "Trial-to-paid conversion uplift" is repeated ~15 times across the page. On the metrics card itself, simpler is better:

> Suggested label: "More free trial users converted to paid — among those who used the quest"

---

## CASE STUDY 02 — NeoTaste Referral

### ✅ What's working really well
- Context title: *"NeoTaste's referral program was working — just not well enough."* Perfect hook.
- Quote: *"The cash variant brought more people through the door — but the subscription variant brought people who actually stayed for dinner."* Memorable. Keep it.
- Hypothesis title: *"Immediate cash incentives would drive more referrals than delayed value."* Clear.
- Lesson 01 and 03 are strong.

---

### 🔧 Structural issue: section labels don't match content

Section 03 is labeled **"Research & Analysis"** but is actually about stakeholder coordination. Section 04 is labeled **"Stakeholder Management"** but contains the A/B test results. These are swapped. Suggested:

- Section 03 label → **"Stakeholder Management"** (title stays: "Coordinating across Growth, Legal, and Product...")
- Section 04 label → **"Results"** or **"A/B Test Results"** (title stays: "€10 drove twice as many referrals. But the free month brought better users.")

---

### 🔧 Copy fixes

#### Section 01 — Body copy, last sentence
> Current: "I was brought in to design both variants and define the UX test framework alongside the Growth Engineer and Data Analyst."

"UX test framework" is jargon. Suggested:

> "I designed both variants and helped set up the test alongside the Growth Engineer and Data Analyst."

---

#### Section 02 — Hypothesis rationale
> Current: "Behavioral economics literature showed immediate monetary incentives consistently outperform delayed value for activation tasks. We hypothesized cash would be more tangible and easier to understand than 'free month,' breaking through the activation barrier. Additionally, cash is fungible - less friction than redemption steps required for the free month feature."

This paragraph uses "behavioral economics literature," "activation tasks," "activation barrier," "fungible," and "redemption steps" — all in 3 sentences. Suggested:

> "Research backs up the intuition: people respond more to a reward they can use right now than a promise of future value. Cash is also simpler to understand — there's no 'how do I claim this?' moment. The free month has steps; €10 doesn't."

---

#### Section 02 — Test Design steps, step 02
> Current: "Stratified by user tenure and activity level to ensure comparability."

> Suggested: "Balanced by how long users had been on the platform and how active they were, to make the comparison fair."

---

#### Section 03 — Stakeholder cards, body copy
The Growth Team card mentions "friction differential between redemption paths" — this is inside the section body (before the cards), not in the cards themselves. This phrase is too technical for this context. The whole sentence is:

> "The friction differential between redemption paths (instant cash vs. confirmation-step subscription) was also a design trade-off we had to acknowledge upfront."

Suggested:

> "Claiming cash was instant; claiming the free month had extra steps. That difference in experience was itself a variable we couldn't fully control — and we had to be upfront about that."

---

#### Section 04 (A/B results) — Control card subtitle
> Current: "Reward existing subscribers feel is meaningful to their ongoing use"
> Suggested: "A reward that existing subscribers already value"

---

#### Section 05 — Design Process body
> Current: "...attracted deal-chasing users with lower LTV."
> Suggested: "...attracted users who weren't sticking around long-term."

> Current: "those referred users had 52% D7 retention vs. 38% for cash-referred users"
> Suggested: "52% of them were still active after 7 days — vs. 38% for cash-referred users"

---

#### Section 05 — Implementation step 03
> Current: "Attributed 148% growth in total referral volume to combined approach."
> Suggested: "The combined approach drove a 148% increase in total referrals compared to the original program."

---

#### Section 06 — Metric label
> Current: "−19% CAC reduction vs Variant B alone"
> Suggested: "−19% lower cost to acquire each new user (vs. cash-only)"
_(CAC = Customer Acquisition Cost — worth spelling out at least in the label)_

---

#### Section 06 — Intro sentence
> Current: "After 60 days of tracking following the launch of the combined incentive, the results showed:"
> Suggested: "60 days after the combined incentive launched:"

---

#### Section 07 — Conclusion title
> Current: "A/B testing revealed the power of addressing both sides of a trade-off."
> Suggested: "Sometimes the right answer is: test both, then take the best of each."

---

#### Section 07 — Conclusion body
> Current: "...achieved 5.2% referral rate (2.5x baseline) while maintaining 46% D7 retention — best-in-class for a referral acquisition channel."
> Suggested: Remove "best-in-class for a referral acquisition channel" — it's a vague claim and reads like a corporate benchmark.

---

#### "Back to start" footer link
> Current: "Back to start" (linking to gymondo-premium.html)

This is confusing — it points to a different case study, not the homepage. Suggested: either link back to the homepage and label it **"Back home"**, or point to the next case study and label it **"Next project"**.

---

## SUMMARY: What to prioritise

**High impact, easy wins:**
1. Fix the section label mismatch in the referral case study (03/04 are swapped)
2. Replace all instances of "trial-to-paid conversion" after the first two with simpler alternatives
3. Trim the hypothesis box in both case studies by ~40%
4. Remove the code-level detail from the Implementation Plan in the Quests case study
5. Replace "D7 retention," "LTV," "CAC," and "habit loops" with plain language equivalents

**Medium impact:**
6. Rewrite the finding card titles in Quests to be more human
7. Rewrite the NeoTaste context sentence (the confusing "adjust those deals to their capacity" part)
8. Fix the "Back to start" footer link in the referral page

**Small polish:**
9. "Eight years experience" → "Eight years of experience" on the homepage
10. Quest 05 card: remove "locks you in"
11. Section title changes (hypothesis titles, stakeholder management title)
