# PickOne: Spec

**Can't decide? Spin for it** · #3 of 32 · Wave 1: Daily keepers · Used: Ad hoc, kept for good · Very easy · Revenue potential: Low · Social, Play & Style · Source: ChatGPT + Perplexity

## One-liner

A deliberately silly, quick app for indecisive people, especially couples and friend groups. Add options and spin a wheel, flip a coin, roll dice or run a quick group vote, with daft animations and sounds. Save wheels for decisions you make often (dinner, films) and exclude recent picks so it doesn't keep landing on the same thing.

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

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

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

## Animation and tone: five signature animations

**Full drama.** Duolingo-style theatrics: characters, big over-the-top reactions, sound effects. Thirsty's plant death is the only animation that takes over the full screen ('NOOOOOOO!!!! NOT CYPHICUS!!!!').

- Spin: drumroll, gasps at near-misses, then 'THE WHEEL HAS SPOKEN' under a spotlight
- Spin again: the wheel sulks ('Oh, so my opinion doesn't matter?')
- Third re-spin: the wheel falls asleep and snores until you tap it awake
- Coin flip: the stickman flips it so high it leaves the screen, then it lands on his head
- Group vote: stickmen argue in a huddle, then carry the winner off on their shoulders

**Line we don't cross:** Keep it short: the whole spin is a few seconds, and skippable.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Web first, then Expo app.
- **Data:** On the device only.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Can't-decide moments; Date night picks; Party and classroom games
- **Shareable output:** Spin results and recordings

## Risks

Keep it tiny. Don't over-invest: ship in days, make it funny, use it to cross-promote.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
