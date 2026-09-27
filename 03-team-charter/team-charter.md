# Lead and Develop High-Performing Teams, Module 3 Lab

## Name the situation
- **Who they are (role, not name), what you have observed, and how long it has been happening.:** The senior leadership team doesn't involve anyone form the development team into the estimation of work to be delivered. As such, for at least the past 3 months the deadlines set and handed over to us are not realistic and unachievable. As a result, the development team is demotivated and clearly not as engaged as other teams I have been on. This problem has been raised but nobody seems to be doing anything as all strategy and deadlines commitment comes top down from the board level.

## Make a diagnosis
- **Your diagnosis, plus one sentence on why. Is your frustration with their behavior, or with a decision you made?:** I guess it's the system: something in the structure and also lack of resourcing makes it impossible to perform and deliver the work on time. The frustration is with the senior leadership who is not pushing back on the issues we are facing for the past three months and also other teams raising similar issues for the past 9 months.

## Write your opening line
- **One next action I will take in the next two weeks is:** Compile a one-page planned-vs-actual for the last three delivery cycles — committed date, actual date, the gap, and its cost (rework hours, overtime, slipped scope) — and use it to request a single, concrete process change: that the development team provides bottom-up estimates before the next commitment is locked, even as a confidence range. Not "involve us more" — one specific insertion point in the next planning cycle. The data converts a morale complaint into a delivery-risk argument, which is the only framing a board acts on, and the narrow ask gives them something approvable rather than a grievance to deflect.
- **The first sentence of the conversation I need to have is:** "In the last planning cycle, the delivery date for [release X] was committed externally before anyone on the development team was asked to estimate the work — that's now the third cycle running, we've missed or scrambled every one of those dates, and I'm watching a capable team stop trusting the plan and start disengaging."

## AI role-play
- **After you step out: what did the role-play change about how you will open this conversation for real?:** Words are very important in how I position my speech. 

Recommendations: Put demotivation last and once, as a consequence, not the headline — "and the cost of the pattern is that a capable team is starting to lose faith in the plan." Say it a single time so it registers as a business risk, then drop it. The roleplay proved that every second you spend on morale is a second they spend deflecting.

Another recommendation: "I'll only get one shot at their attention." Take that literally. Whatever you bring has to be one page, root-cause-ranked, with a single approvable ask (bottom-up estimates before commitment) — not a full grievance. You're not trying to win the argument in the room; you're trying to arm a middle manager to win it in a room you're not in.

## Refine and complete your charter
- **What We Own. What this team owns.:** We own the core Fable product and the resilience thesis that runs through it — the coherence of the whole user journey from acute crisis through the day-120 cliff into durable, proactive engagement. Concretely, we own: the meditation and sleep foundation (kept as-is, not replaced); the strategic integrity of the Playing-to-Win cascade across every surface; the weekly cohort-review cadence and the locked definitions of the proactive-use ratio; and the arbitration of trade-offs when individual PM surfaces pull against each other. Within the team, ownership is split cleanly:

PM 1 owns the onboarding surface — the first-run experience and the fight against the 40% early drop-off (KR1 precondition).

PM 2 owns the retention surface — the post-acute engagement and paid-retention loop (KR2, KR3).

PM 3 owns the AI check-in system — the check-in logic, personalisation on acute-phase history, and the non-diagnostic prompt design. PM 3 owns how check-ins work, wherever they appear.
- **What is out of scope.:** We do not build a clinical or diagnostic platform (the hard no — regulatory line). We do not build a general social feed. We do not own top-of-funnel brand spend or paid acquisition — that is Growth's. We do not treat "more content" as a strategy lever. And we do not own the anomaly-detection infrastructure (bought/partnered) — only the interpretation layer on top of it, which is the moat.
- **Cross-boundary decisions that need a joint call.:** The check-in layer is the deliberate overlap, so it gets explicit rules. A joint call is required — no unilateral shipping — when any of the following is true:

PM 3 wants to change behaviour on PM 1's or PM 2's surface (e.g. a check-in that alters the onboarding flow, or changes what a retention session looks like). PM 3 owns the check-in system; PM 1/PM 2 own the surface it lands on. Neither ships a change to that intersection alone.

A change touches the aspirational-vs-remedial framing (the central "how to win" bet). Framing is a strategic asset, not a copy decision — any surface changing it triggers a joint call with Content and this team.

A change would move a locked metric definition (proactive vs. crisis-triggered session). Analytics owns that definition; no team redefines it to suit a target.

A Now bet's owning teams disagree on sequencing where their work is co-dependent (e.g. onboarding redesign and check-in launch competing for the same engineering capacity).
- **How We Decide. Who decides feature and scope calls.:** PM 1, PM 2, PM 3 each hold final say within their own scope as defined above. Inside your surface, you decide and you're accountable — no design-by-committee for single-surface calls.

PM 3 holds final say on check-in mechanics (logic, personalisation, prompt content) even when they render on another PM's surface — because the check-in system is one coherent capability, not three.

The surface owner (PM 1 or PM 2) holds final say on placement and surface behaviour — whether a check-in appears there, when, and how it fits the surrounding flow.

This team (you) decides strategic trade-offs — anything touching the cascade, the framing bet, sequencing across Now bets, or a conflict two surface owners can't resolve.

Analytics decides metric definitions, locked before the quarter, not negotiable mid-quarter.

Growth decides acquisition; this team decides the product the acquired users land in. Growth is consulted, not deciding, on in-product retention mechanics.
- **How cross-team conflicts escalate.:** Direct, first — 48 hours. The two PMs in conflict attempt resolution directly, owner-to-owner, and document the disagreement in one or two lines (what each wants, why). Most intersection calls end here. If unresolved within 48 hours, it escalates — no lingering.

To you (product lead), with a decision brief — 3 business days. The escalating PM brings a one-page brief: the decision, each option, and which OKR each serves. You decide against the strategy, not the loudest advocate. The default tie-breaker is explicit: whichever option better serves the proactive-use ratio (KR2) wins, because that is the metric the whole thesis rests on. Decision returned within 3 business days.

To cross-functional forum — weekly, if it spans functions. If the conflict crosses into Clinical, Growth, or Legal (e.g. a check-in that edges toward the clinical line, or a retention mechanic Growth contests), it goes to the weekly cohort review, which already convenes the right people. Decision made there, minuted, and owned by a named person with a date.

Board-level — only for cascade violations. The only conflicts that leave this structure are ones that would break a Where-to-Play boundary or the hard no (e.g. a proposal that crosses into clinical territory). Those aren't product calls; they go up. Everything else resolves at level 1–3.
- **Who resolves escalations from outside the team.:** Me as the Product Manager am the default front door. Any team — Growth, Clinical, Legal, another PM group — that has a conflict with something my team owns escalates to me first, not to the individual PMs. This protects PM 1/2/3 from being pulled into cross-team fights individually and gives outsiders one accountable name. I resolve it if it sits within product trade-off territory, within 3 business days, using the same KR2 tie-breaker as internal conflicts.

Clinical-line conflicts (e.g. Clinical advisory objects that a check-in edges toward diagnosis) → these go to the weekly cohort review with Clinical present, and Clinical holds a veto, not a vote, on the non-diagnostic boundary. You don't overrule clinical safety on a delivery argument. Timeframe: next weekly review, or an ad-hoc call within 48 hours if it's blocking a release.

Acquisition vs. retention conflicts (Growth wants something that serves top-of-funnel at the expense of the post-acute product) → joint call between you and the Growth lead as peers; if the two of you can't resolve it, it escalates to whoever both teams report into (your shared VP/CPO), because it's a resource-allocation call between two equal mandates, not a product call you can settle. Timeframe: 5 business days.

Cascade or Where-to-Play violations (an outside team proposes something that breaks a strategic boundary — localisation now, a social feed, clinical repositioning) → straight to board/exec level, because these aren't escalations to resolve, they're boundary breaches to refuse. You surface them up; you don't negotiate them.

## Show and swap your team charter
- **Where does the charter leave room for interpretation that could cause a conflict?:** _(not filled in)_
