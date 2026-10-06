# The Solution · FinWise

> Module 2 · Acquisition & Activation. The onboarding solution and the Aha moment that makes value land.

## Aha moment

**FinWise's Aha moment: in their first session, the owner sees a 30-day cash forecast built from their own bank data, and it answers the question they came with.**

As a behavior we can measure: *the user views a forecast generated from a connected account within 10 minutes of sign-up.*

It's a realization, not a feature: "I know whether I can make payroll next month, and I didn't have to build anything to find out."

How I got there:
- **Module 1 ruled out setup as the Aha.** When the share of users importing data rose from ~31% to ~45%, conversion didn't move. Setup is a step on the way, not the payoff.
- **Small-business owners don't buy finance software to see their past.** They buy it to answer a question about the future: will I have enough? The forecast is the first screen that answers it.
- **It sets up the Module 1 loop.** A forecast with a tight week in it is something worth sending to an accountant. Value comes first, then the invite.

What I can't claim yet: the course data is monthly, so I can't show that users who reach this moment retain better. That's the first thing Module 4 tests: retention of users who viewed a real forecast in session 1 vs. those who didn't.

## Onboarding prototype

**Live prototype:** https://mdorticos16x9.github.io/finwise-strategy/02-solution/prototype/
(Source: [`02-solution/prototype/index.html`](prototype/index.html). Single file, no build step. Light and dark mode, mobile-friendly.)

Four screens, one job each:

| # | Screen | Its one job | The one action |
|---|---|---|---|
| 1 | Pick your question | Personalize the first answer (cash next month / where money goes / quarterly taxes) | Tap one choice |
| 2 | Connect your account | Get real data in with zero manual setup | Pick a bank, or use sample data |
| 3 | **Your first answer (Aha)** | Show the 30-day forecast, the lowest point, and one action that fixes it | Read it, then send to accountant |
| 4 | Bring in your accountant | Start the Module 1 collaboration loop | Enter one email |

The Aha lands on screen 3: the first time the user sees their own numbers projected forward, with the risky week flagged.

## Why this activates

**What changes:**
1. **The friction I removed: manual setup before value.** Today's path makes users import data and set up categories before they see anything. The prototype reads one bank account and sorts transactions automatically. No chart of accounts, no CSV, no category mapping.
2. **One question, not a tour.** The screen 1 quiz asks one thing and uses it to choose the first answer. Every other feature stays hidden until after the Aha (progressive exposure).
3. **Value before asks.** The accountant invite comes *after* the forecast. A user who has seen a tight week has a reason to share it. Asking earlier would be a referral request with nothing to refer.
4. **The answer tells you what to do.** "Payroll and rent land the same week; move rent to the 1st" turns a chart into a decision. That's the difference between "I see what this does" and "I feel why this matters to me."

**Why it should convert trial users:** in a reverse trial, the upgrade decision comes when the trial ends and features drop away. A user who has a forecast they check, and an accountant who works from it, loses something real at downgrade. A user who only imported data loses nothing.

**How I'll measure it** (the deck's four onboarding metrics):
- **Activation rate:** % of trials that view a forecast built from a connected account in session 1.
- **Time to Aha:** median minutes from sign-up to first forecast view. Target: under 5.
- **Drop-off rate:** by screen. Screen 2 (bank connection) is the highest-risk step. Some owners won't connect a bank on day 1, which is why sample data is offered.
- **Post-onboarding retention:** 30-day return rate of activated vs. non-activated trials. If activated users don't come back, the Aha wasn't sticky. That's a product problem, not an onboarding one.

**Biggest risk:** bank-connection trust. Owners may not hand over bank access to a product they met five minutes ago. Mitigations in the flow: read-only wording on screen 2 and a sample-data path. If screen 2 drop-off is high, the next experiment is "forecast from sample data first, connect after."
