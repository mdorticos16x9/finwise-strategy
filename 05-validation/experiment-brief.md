# The Validation · FinWise

> Module 5 · Experimentation Methods. The experiment brief that tests the bet.

## Method

**Method:** A/B Test

**Why:** New trials can be randomized one by one, onboarding has no shared marketplace or network effect, and we can wait about 7 weeks for a clean read, so a standard A/B test gives the cleanest signal. A bandit would chase early noise, and a holdout comes after launch to check that retention holds.

_____

## Hypothesis + primary metric

If we replace today's set-up-first onboarding with the 3-screen forecast-first flow from Module 2 for FinWise trial users, we expect the share of trials that reach a first forecast in week 1 to rise from about 37% to at least 47%, because importing data alone hasn't moved conversion and the payoff is the modeling output.

**Primary metric:** share of new trials that reach a first forecast built from their own imported data within 7 days (Leading 1 from Module 4), target: +10 percentage points (about 37% → 47%) at p < 0.05. The 37% is an estimate from FinWise's 13-month average modeling usage; we measure the real week-1 rate in the two weeks before launch and keep the +10-point target. That's the MDE: a smaller lift would need about 1,500 trials per arm, around six months of FinWise traffic, versus about 380 per arm for 10 points.

_Experiment: Forecast-First Onboarding Test, to get more trial users to FinWise's North Star (import their data and reach a first modeling output) in week 1, and lift the 2% trial-to-paid conversion at the Activation stage where Module 1 found the leak._

_Testing the 3-screen forecast-first onboarding from Module 2 (one question, one read-only bank connection or sample data, then the 30-day cash forecast with its low point and one fix), with the accountant invite and the weekly check left out, on new self-serve trial sign-ups during the test window, split 50/50 at sign-up and excluding accounts an accountant creates for a client and existing customers. Current experience: trial users land in the full product and set it up themselves (import data, map categories, build a chart of accounts); only about 37% ever reach a modeling output, and nothing points them to one._

_Predicted outcome: the week-1 forecast rate rises from about 37% to at least 47% with no rise in day-1 drop-off, and average session length in the first 14 days (Leading 2) rises too; trial-to-paid is tracked but not decided on, because at about 10 conversions a month it can't reach significance in 8 weeks. If successful: ship the flow to all new trials, keep a 10% holdout for 6 months as a directional check that paid retention holds (about 10 paid a month is too few to prove it), then test the accountant invite from Module 1 on top. If unsuccessful: check the guardrail and drop-off by screen; if people quit at the bank connection, test "sample forecast first, connect after", and if they reach the forecast but don't come back, revisit the Aha definition with user-level data._

_____

## Guardrail + read date

- **Guardrail:** Day-1 drop-off (trials that leave before finishing onboarding) must not rise by more than 5 percentage points versus control. At about 390 trials per arm the test can only reliably detect a rise of about 9 points, so a 5–9 point rise is a warning: we check drop-off by screen before shipping.
- **Read date:** Monday, Dec 21, 2026: 8 weeks after an Oct 26 launch (7 weeks to enroll about 780 trials, plus 7 days for the last trials' week-1 window). No earlier.

_____
