# StudySprint: Spec

**Exam countdowns and a revision timetable that plans itself** · #26 of 33 · Wave 3: Seasonal and episodic · Used: Daily in exam season · Easy · Revenue potential: Medium · Habits, Health & Learning · Source: ChatGPT + Perplexity

## One-liner

Enter your exams, subjects and topics, mark how confident you feel, and StudySprint builds a realistic revision timetable that gives more time to weak topics and closer exams. Includes a focus timer and countdowns.

## Problem / audience

- **Who it's for:** GCSE, A-level, college and university students; adults taking professional exams.
- **The problem it solves:** Students know when their exams are, but not how to split their time across subjects and topics.
- **Example:** A student enters five exams, marks two weak topics, and gets a daily plan from January to June.

## MVP features (ship with only these)

1. Add exams, subjects and topics with confidence levels
2. Auto-generated timetable, weighted by how close and how weak
3. Focus timer (sprint sessions)
4. Tick off sessions; progress per subject
5. Exam countdowns

## Not in MVP

- Custom plans and templates
- Focus stats
- Next-term re-engagement

## Monetisation

| Model | Detail |
|---|---|
| Free | Timetable and timer, with ads |
| Premium | £3.99/month or £19.99/year: unlimited subjects, custom plans, focus stats, templates |
| Ads | Never during a focus session |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Today's planned sessions |
| Tiny win | Complete a sprint |
| Progress | Subject progress; weak topics shrinking |
| Share | Progress summaries |
| Next step | After exams: set up next term or next year |
| Cadence | Daily in revision season |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Energetic sprint start and a session-complete burst

**Line we don't cross:** Completely calm during a focus session.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app.
- **Data:** On the device only.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Revision techniques; Exam countdowns; Study motivation
- **Shareable output:** Progress summaries

## Risks

Very seasonal: launch before January. Users leaving after exams is expected.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
