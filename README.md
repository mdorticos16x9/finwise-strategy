# FinWise, A Product-Led Growth Strategy

> Get trial users to their first cash forecast in three screens, make it something they share with their accountant, and only then ask them to pay.

**Manny Dorticos · Product Experimentation · Oct 2026** · https://github.com/mdorticos16x9/finwise-strategy

---

## Final Project Deliverables

### Slide 5 · The Bet (Growth Hypothesis)
- **Hypothesis:** FinWise's biggest growth problem is that 98% of trials end without paying, and conversion holds at ~2% whatever happens to traffic or feature adoption, because a solo trial user can set FinWise up without ever producing a result another person depends on, so walking away at trial end costs them nothing.
- **The bet:** Bet on Activation, not acquisition: after data import, prompt owners to invite their accountant or bookkeeper to review an auto-generated financial report, a Collaboration loop that turns a relationship they already have into the reason to stay. Not doing: more ad spend, feature adoption as a goal, churn-only plays, or referral rewards.
- **Growth loop:** https://mdorticos16x9.github.io/finwise-strategy/01-bet/growth-loop.png

### Slide 6 · The Solution (Onboarding)
- **Aha moment:** In their first session, the owner imports their bank data and sees FinWise's first modeling output: a 30-day cash forecast built from their own numbers, showing the week cash gets tight and what to do about it. The realization: "I know whether I'll have enough cash next month, and I didn't have to build anything to find out." Measured as: a forecast viewed from imported data within 10 minutes of sign-up.
- **Prototype:** https://mdorticos16x9.github.io/finwise-strategy/02-solution/prototype/ , https://mdorticos16x9.github.io/finwise-strategy/02-solution/aha-screen.jpg

### Slide 7 · The Mechanic (Gamification)
- **Mechanic + rationale:** A "Forecast confidence" progress bar: every Monday before payroll week, owners confirm what's coming in and out (payroll, rent, expected invoices); the bar fills and the forecast's low point firms up, and each confirmation makes next week's forecast more accurate. Rejected a streak (it rewards the quick glances linked to churn) and a leaderboard (cash positions are private).
- **Wireframe:** https://mdorticos16x9.github.io/finwise-strategy/03-mechanic/wireframe/ , https://mdorticos16x9.github.io/finwise-strategy/03-mechanic/mechanic-wireframe.jpg

### Slide 8 · The Signals (Metrics)
- **Leading:** 1) % of new trials that reach a first forecast built from their own imported data in week 1: one step before the North Star, at the Activation drop-off, and it responds within days of an onboarding change.
2) Sessions per trial user in the first 14 days: the usage signal that moves most with trial-to-paid (+0.41); the weekly cash check from Module 3 is built to raise it.
- **Lagging:** Trial-to-paid conversion rate
- **Pattern:** The headline metric is trial-to-paid, flat at 2%, but the real pattern behind it is a Ceiling: modeling usage swung from 11% to 58% (r = +0.24 with conversion) and conversion didn't move. More feature adoption alone won't break it. Users now visit more often for shorter sessions, so the next experiment has to change the experience itself: the weekly forecast check and the accountant invite, not more onboarding tweaks.

### Slide 9 · The Validation (Experiment)
- **Method:** A/B test: new trials split 50/50 at sign-up, no network effect, and about 7 weeks gives a clean read.
- **Hypothesis + metric:** If we replace today's set-up-first onboarding with the 3-screen forecast-first flow from Module 2 for FinWise trial users, we expect the share of trials that reach a first forecast in week 1 to rise from about 37% to at least 47%, because importing data alone hasn't moved conversion and the payoff is the modeling output.

Primary metric: share of new trials reaching a first forecast from their own imported data within 7 days. Success: +10 points (37% → 47%) at p < 0.05, the minimum detectable effect at about 380 trials per arm.
- **Guardrail + read date:** Guardrail: day-1 drop-off must not rise more than 5 points versus control. Read date: Monday, Dec 21, 2026 (launch Oct 26), no peeking.

### Slide 10 · The Model (Pricing)
- **Stage + model:** Stage 1 Value Creation · Subscription
- **Recommendation:** Don't change the price yet. Move the paywall to where value lands: when the reverse trial ends, the account goes read-only instead of staying usable for free. Owners keep their data and their last forecast, but the 30-day forecast stops updating, the weekly forecast-confidence check pauses, and the shared accountant view locks until they subscribe. Rolled out to new trials by sign-up cohort.

The pricing bet: packaging matched to value. The paid line sits at the live forecast and the accountant view, where owners feel they need more.
- **Signal:** Upgrades should cluster at trial end among owners who reached a first forecast in week 1, and stay low among those who never did.

### Slide 11 · The Story (Insights)
- **Friction:** The data kept refusing my first ideas. I was sure getting owners to import their data on day one would lift conversion; imports rose from 31% to 45% and conversion didn't move. I also had to separate what the numbers show from what they can prove: 13 monthly rows can point the way, not settle it.
- **Aha moment:** Trial-to-paid isn't a lever, it's a ceiling. Modeling usage swung from 11% to 58% and conversion stayed at 2%. That changed the whole strategy: the fix isn't more onboarding tweaks or a price change, it's a new experience, a first forecast that owners build on every week and share with their accountant.
- **Takeaways:** Pick the metric the test can actually read: size the sample before you pick the target. Set the read date before launch. Diagnose before you design, the churn data ruled out the streak I'd have built by default. And know when not to touch the price.

---

Submitted on the Product Experimentation Certification Learning Platform · Product School.
