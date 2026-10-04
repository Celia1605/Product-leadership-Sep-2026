# Financial Model: Fable Growth — AI Daily Check-In Layer

> Module 5 · Master Product Financials & Strategic Bets, ★ Deliverable 5
>
> The business case for funding your bet, and the explicit kill criteria that would tell you to stop.

_All figures marked "illustrative" are placeholders for this exercise, not drawn from real Fable data; replace before presenting to a board._

## 1. Business case

_Why this initiative is worth funding over the alternatives. Includes the key unit-economics assumptions — CAC, LTV, payback — framed for a retention bet rather than an acquisition one._

| Assumption | Value | Source / rationale |
|---|---|---|
| CAC | $38 per acute user *(illustrative)* | Already spent during the acute phase — incremental CAC for the retained post-acute user is ≈ $0. |
| LTV | $240 *(illustrative)* | $96/yr contribution (ARPU $120/yr × 80% margin) × 2.5-year lifetime at 40% annual churn. LTV:CAC = 6.3:1. |
| Payback period | **Build payback ~4.7 quarters** at plan *(illustrative)* | The true financial risk. CAC payback (~4.7 months) is near-irrelevant here — these users aren't re-acquired; the ~$175k build is what must earn back. |
| Investment required | ~$175k one-time *(illustrative)* | ~3.5-person pod for one quarter to build the check-in layer. |
| Expected return | ~$37k first-year contribution per quarterly cohort, compounding *(illustrative)* | A 13-point retention lift (22%→35%) across a ~3,000-user cohort = ~390 additional retained users/quarter × ~$96/yr, stacking as cohorts accumulate. |

> **The case in one paragraph:** Build AI daily check-ins personalised on each user's acute-phase behavioural history to convert post-acute users (the 60–120 day transition) from crisis-only visitors into habitual proactive users. The mechanism to a financial result runs in three links: check-ins lift the proactive-use ratio (KR2) → proactive use carries more users past the day-120 retention cliff (KR1) → retained users sustain paid subscriptions (KR3), raising LTV. The economic strength is that this is **retention of users already acquired**, so growth comes at near-zero incremental CAC — the cheapest kind. Unit economics are robust under stress: LTV:CAC holds at 5.0:1 even with churn 10 points higher (above the 3:1 bar), and CAC payback stays at 5.7 months even at 20% higher CAC. The single real exposure is the 13-point retention lift itself — if it comes in 30% soft, build payback stretches from ~4.7 to ~6.7 quarters — and that risk is fenced by the kill criterion below. This beats the funded alternatives (more content, B2B, a clinical tier) because it lifts LTV on users we have already paid to acquire, rather than buying new ones.

## 2. Kill criteria

_The specific signals that would tell us this bet is no longer worth pursuing — metric, threshold, timeline, and a default action, not a conversation._

> If the **proactive-use ratio among post-acute users** does not reach **25%** (halfway from the 15% baseline to the 40% target) by **end of Q2**, we will **stop the check-in build, reallocate the pod to onboarding/retention-surface work, withhold Q3 personalisation headcount, and redirect the budget to the acquisition + win-back fallback.**
>
> _Second (confirming) gate:_ because the kill metric above is leading, not financial, a **paid-retention review at the annual mark** tests whether the proactive→paid link held; clearing the first gate without the second triggers a review of that link, not continuation on faith.

## Link to full artifact

_[link to this deliverable in your repo]_
