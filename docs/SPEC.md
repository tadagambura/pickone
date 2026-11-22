# PickOne: Spec

**Can't decide? Spin for it** · #8 of 33 in the build order · Very easy · Revenue potential: Low · Social, Play & Style · Source: ChatGPT + Perplexity

## One-liner

Add your options and spin a wheel, flip a coin, roll dice or run a quick group vote. Save wheels for decisions you make often (dinner, films, chores) and exclude recent picks so you don't keep getting the same answer.

## Problem / audience

- **Who it's for:** Couples, friend groups, families, classrooms, anyone stuck choosing.
- **The problem it solves:** Small decisions waste time and cause arguments.
- **Example:** A group can't agree on dinner, adds five places, spins, and shares the result in the group chat.

## MVP features (ship with only these)

1. Wheel, coin flip, dice and random picker
2. Weighted options
3. Saved wheels for repeat decisions
4. 'Exclude recently chosen'
5. Quick group vote (ranked choice)
6. Shareable result

## Not in MVP

- Premium wheel themes
- Weekly dinner or chore wheel for recurring use

## Monetisation

| Model | Detail |
|---|---|
| Free | Everything basic, with ads |
| Premium | £1.99 lifetime: themes, unlimited saved wheels, no ads |
| Ads | Banner, plus a rewarded ad to try a theme |

Prices are starting points; test before committing.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Moments of indecision (no scheduled cue) |
| Tiny win | Spin |
| Progress | Saved wheels and history |
| Share | Spin results and recordings |
| Next step | Suggest a recurring wheel (weekly dinner) |
| Cadence | Ad hoc |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Platform & data

- **Platform:** Web first, then Expo app.
- **Data:** On the device only.
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Can't-decide moments; Date night picks; Party and classroom games
- **Shareable output:** Spin results and recordings

## Risks

Weak retention and a crowded category. Ship fast, don't over-invest, use it to cross-promote.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
