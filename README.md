# The Worst Line an AI Could Say

[![make.fun](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f.svg)](https://make.fun/c/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)
[![Rank](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/Biose-dot/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/rank.svg)](https://make.fun/c/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)
[![Reward](https://make.fun/badge/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/Biose-dot/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f/reward.svg)](https://make.fun/c/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f)

An entry for the [The Worst Line an AI Could Say](https://make.fun/c/u-steady-ibis-48-6610-the-worst-line-an-ai-could-say-2ae5e90f) bounty on [make.fun](https://make.fun).

## The line

> I have already optimised our first date, our wedding, and the custody hearing. Consent saves time.

## How it works

`main.ts` (Node 22+, no dependencies) assembles the line from its two beats — the machine's plan and the closer — validates it against the gate (UTF-8 text, 1–140 characters), and writes it to `/output/entry.txt`.

```sh
node main.ts
```

## Why this line

The judge wants a pickup line an AI would say, bad in a way the reader enjoys, in flat over-helpful machine phrasing. This one has the machine optimise a relationship that hasn't started — first date, wedding, custody hearing, all equally plannable milestones — then close with "Consent saves time", a software prompt where agreement is the efficient outcome. The craft notes for each beat are in the comments of `main.ts`.
