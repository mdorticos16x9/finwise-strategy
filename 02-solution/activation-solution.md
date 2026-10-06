# The Solution · FinWise

> Module 2 · Acquisition & Activation. The onboarding solution and the Aha moment that makes value land.

## Aha moment

**FinWise's Aha moment: in their first session, the owner sees a 30-day cash forecast built from their own bank data, and it answers the question they came with.**

**Name the moment.** The user views a forecast from a connected account within 10 minutes of sign-up. The realization: "I know whether I can make payroll next month, and I didn't have to build anything to find out."

**Connect it to retention.** The forecast is FinWise's Modeling feature. Modeling is the only usage signal in the course data that rises with conversion (+0.24 across 13 months; Data Import: −0.05). A forecast also changes every day as money moves, so it gives the owner a reason to come back, and something worth sending to their accountant (the Module 1 loop).

**Name the friction removed.** Manual setup before value. The user connects one bank account, and FinWise sorts the transactions itself: no CSV import, no chart of accounts, no category mapping. My hypothesis: users quit during setup because they've seen nothing yet that makes the work feel worth it.

## Onboarding prototype

**Live prototype:** https://mdorticos16x9.github.io/finwise-strategy/02-solution/prototype/ ([source](prototype/index.html))

![The Aha screen: a 30-day cash forecast with the tight week flagged](aha-screen.jpg)

Four screens, one job and one action each:
1. **Pick your question.** Cash next month, where the money goes, or quarterly taxes. *Action:* tap one.
2. **Connect your account.** Read-only, with a sample-data option. *Action:* pick a bank.
3. **Your first answer (the Aha).** The forecast, the lowest point, and one fix. *Action:* send it to your accountant.
4. **Bring in your accountant.** *Action:* enter one email.

## Why this activates

The flow puts the value before any ask. The user sees their own numbers projected forward on screen 3, before FinWise asks them to configure anything or invite anyone. The Aha occurs on screen 3, the first time a user sees the week their cash gets tight and what to do about it. That's the moment "I see what this does" turns into "I feel why this matters to me." It converts trial users because a reverse trial ends by taking features away. A user with a forecast they check, and an accountant who works from it, loses something real at downgrade. A user who only imported data loses nothing.

---

## Notes (beyond the lab)

- **Onboarding metrics (from the deck).** Activation rate: % of trials that view a forecast from a connected account in session 1. Time to Aha: median minutes from sign-up to first forecast; target under 5. Drop-off by screen: screen 2 (bank connection) is the riskiest. Post-onboarding retention: 30-day return rate of activated vs non-activated trials.
- **Caveat on the data trace.** The +0.24 is a correlation of monthly averages, not user behavior. Modeling adoption also correlates +0.54 with the churn column. If that holds for individual users in Module 4, forecasting attracts users it doesn't keep, and this Aha needs to change.
- **Prototype limits.** All three quiz answers lead to the forecast; only the cash path is built. The "Your business" field isn't used yet. In the real product it would set up industry-specific categories.
- **Biggest risk.** Owners may not give bank access to a product they met five minutes ago. Mitigations: read-only wording and a sample-data path. Sample-data views don't count as activation. If screen 2 drop-off is high, the next test is "forecast from sample data first, connect after."
- **Process note.** I skipped the lab's optional LLM planning step and built in Claude Code, one of the lab's listed tools.
