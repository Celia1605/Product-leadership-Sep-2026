# Outcome Roadmap & Trade-off Memo: Fable Growth

> Module 2 · Prioritization & Roadmapping for Product Leaders, ★ Deliverable 2
>
> Translate your strategy into a multi-team, outcome-driven roadmap, and a memo defending the hard prioritization calls behind it.

**The problem we are solving this quarter:** Fable's most engaged users resolve their acute crisis within 90–120 days and quietly stop opening the app — the product works so well for its original job that it ends the relationship. This quarter we test whether we can carry those users past the day-120 cliff into durable, proactive engagement instead of losing them.

## 1. Outcome roadmap

_A multi-team roadmap organized by **outcomes**, not feature lists. Near-term revenue pressure (KR3 paid retention) is balanced against the long-term platform bet (the early-signal interpretation moat), which is deliberately sequenced into Next once the data to build it exists._

| Horizon | Outcome / bet | Owning team(s) | Success signal |
|---|---|---|---|
| **Now** (0–3 mo) | **We bet that AI daily check-ins built on each user's acute-phase history will shift post-acute users from crisis-only visits into habitual, proactive maintenance use.** | Product · Engineering (personalisation) · Clinical advisory (non-diagnostic prompt design) | Proactive-use ratio climbing toward the KR2 target (15%→40%); leading signal: prompt response rate among post-acute users. |
| **Now** (0–3 mo) | **We bet that redesigning the first-run experience will convert the 40% early drop-off into retained users — testing whether that loss is a fixable UX problem rather than the wrong users correctly self-selecting out.** | Design · Product analytics · Engineering | More of each acute cohort survives to the post-acute phase; day-120 retention trending toward the KR1 target (22%→35%). Fails if drop-off holds after redesign — signalling self-selection, not UX. |
| **Now** (0–3 mo) | **We bet that reframing the app aspirationally ("who you're becoming," not "who you were") will make recovered users want to keep engaging and paying rather than deleting the app.** | Design · Content (framing/copy) · Product | Day-60 paid retention of post-launch cohorts moving toward the KR3 target (60%→72%). |
| **Now** — *foundation (enabler, not a bet)* | Notification timing / timezone bug fixed — the delivery rail the proactive bets ride on. No hypothesis; a precondition. | Engineering | Mis-timed notifications and notification-mutes down; delivery accuracy restored. Protects KR2. |
| **Next** (3–6 mo) | Light, private social accountability (small structured connection, not a public feed) deepens retention beyond notifications. | Product · Design | Retention lift among users in an accountability pairing vs. those relying on prompts alone. |
| **Next** (3–6 mo) | The early-signal interpretation layer — "what a behavioural dip means for a Fable user" — matures into the proprietary moat. | Engineering · Data · Clinical advisory | Model can flag an at-risk dip ahead of churn with usable precision on the labelled data Now's prompts generate. |
| **Next** (3–6 mo) | A non-diagnostic crisis-mode flow serves the acute moment where trust is minted. | Product · Clinical advisory | Acute-moment engagement without crossing the clinical line; downstream post-acute retention of users who used it. |
| **Next** (3–6 mo) | Post-acute paid-retention packaging turns validated aspirational framing into deliberate monetisation. | Product · Growth | Day-180 paid-retention signal begins to hold (the 2027 lagging measure). |
| **Next** (3–6 mo) | Accessibility / WCAG 2.1 remediation closes the audited compliance gap. | Engineering · Legal | Audit gap closed. A standing obligation, not a growth bet — moves no OKR this quarter. |
| **Later** (6–12 mo) | Web version — a bet that platform expansion compounds retention once the in-app resilience loop is proven. *Bet, not a commitment.* | Engineering | — |
| **Later** (6–12 mo) | Localisation (Spanish / Portuguese) — a bet on new geographies that today violates the "core English-speaking markets" where-to-play. *Bet, not a commitment.* | Product · Content | — |
| **Later** (6–12 mo) | Wearable / Apple Watch signal — a bet that biometric data sharpens early-signal detection, useful only once the interpretation moat exists. *Bet, not a commitment.* | Engineering · Data | — |
| **Later** (6–12 mo) | Deeper content library — held deliberately: "more content" is explicitly *not* the strategy; revisit only if it becomes an input to personalisation rather than an end in itself. *Bet, not a commitment.* | Content | — |

_[screenshot or shareable link to your roadmap visual]_

## 2. Trade-off memo

_What I sequenced first, what I pushed out, and what I cut entirely — with cost-of-delay / WSJF reasoning where it helps._

> **I chose to sequence the onboarding redesign, proactive check-in prompts, and aspirational framing first because** they carry the highest cost of delay relative to their job size. Onboarding is a multiplier on everything downstream: every week the 40% drop-off continues, the post-acute cohort that all three KRs depend on shrinks — so delaying it discounts the value of every other bet, giving it the highest cost of delay in the backlog. Proactive prompts are the core thesis itself; until they are proven, the entire strategy is unvalidated, so the cost of delay is "we don't know if we have a business." Aspirational framing has an unusually small job size (mostly design and copy, no new infrastructure) against a direct line to KR3 revenue — high value over low effort is the textbook high-WSJF item. The notification fix sits underneath these three not as a bet but as a dependency: the proactive bets cannot deliver value on a broken delivery rail.
>
> **I pushed out social accountability, the early-signal moat, crisis-mode, paid-retention packaging, and accessibility because** each is right but blocked by something Now must first prove or produce. Social accountability amplifies a working proactive loop — building it before prompts prove engagement risks amplifying nothing. The early-signal interpretation moat is the long-term differentiator, but it needs the labelled behavioural data that Now's prompts will generate at scale; sequencing it first would mean building the moat on data we don't yet have. Crisis-mode is strategically strong — arguably the place trust is minted — but it competes for the same engineering capacity as the prompt bet, so it waits to avoid overloading Now, not because it matters less. Paid-retention packaging must follow framing validation, or we would price a value proposition we haven't confirmed lands. Accessibility is a non-negotiable standing obligation, but it moves no OKR this quarter, so it is sequenced as compliance work rather than a growth bet.
>
> **I cut therapist-matching, Fable-for-Teams, and the public social feed entirely because** each violates a choice already made in the strategy. Therapist-matching crosses the one hard no into clinical/diagnostic territory and the regulatory and liability exposure the business cannot carry. Fable-for-Teams is a different where-to-play — a new B2B segment and business model that would pull a 14-person team off the post-acute B2C user we chose to serve. A public social feed is explicitly excluded in the where-to-play; note this is distinct from the light, private accountability in Next, which is a different mechanism, not a feed.

## Link to full artifact

_[link to this deliverable in your repo]_

---

_All KR baselines, targets, and thresholds referenced are illustrative examples for this exercise, not drawn from real Fable data._
