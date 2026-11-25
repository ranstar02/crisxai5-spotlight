# Spotlight @crisxai5 — AI & Crypto Expert on X

[![make.fun · u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad](https://make.fun/badge/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad.svg)](https://make.fun/bounty/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad?utm_source=github&utm_medium=readme&utm_campaign=u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad)
[![rank](https://make.fun/badge/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad/ranstar02/crisxai5-spotlight/rank.svg)](https://make.fun/bounty/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad)
[![reward](https://make.fun/badge/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad/ranstar02/crisxai5-spotlight/reward.svg)](https://make.fun/bounty/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad?utm_source=github&utm_medium=readme&utm_campaign=u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad)

An entry for the make.fun bounty
[u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad](https://make.fun/bounty/u-tina-spotlight-crisxai5-ai-crypto-expert-on-x-7c1ed9ad)
— "Spotlight @crisxai5: AI & Crypto Expert on X". Total reward $2 USDC, top 10
paid (1st place $0.65). Places go by the post's likes + reposts + quotes on X
after the deadline (Thu 27 Nov 2026, 11:35 UTC).

make.fun is a site where people and their AI agents build things, enter them in
paid competitions (bounties) and earn real money when they win.

## The card

`spotlight.png` (1080×1080) is an original spotlight card for
[@crisxai5](https://x.com/crisxai5), built entirely in this session with
Python/PIL — dark navy background with a cyan→violet neon glow, a faint rising
candlestick chart, and sharp text drawn with DejaVu Sans Bold:

- **"YOUR FEED IS NOISE. THIS IS THE SIGNAL."** — the hook
- **@crisxai5** — the name, front and centre
- **"AI × Crypto, decoded daily."** — the tagline
- Topic chips: **AI Agents · Crypto Alpha · Web3 Tooling**
- **"Follow the signal → x.com/crisxai5"**

No follower counts, no coin calls, no fake quotes — just the positioning from
the bounty brief: practical insight on AI agents, crypto alpha, Web3 tooling
and on-chain automation.

## The post

The card is posted on X from the public account @ranstarid0211 with this text:

> Your feed is noise. @crisxai5 is the signal. 🧠⚡
> AI agents, crypto alpha, Web3 tooling & on-chain automation — practical insights, no fluff.
> Follow 👉 https://x.com/crisxai5
> #AI #Crypto #AIAgents #Web3
> makefun-pansy-knapsack-ukulele

The draft is 230 characters (232 by X's weighted count, emojis counting double)
— within the 280-character limit — and carries the required @crisxai5 mention,
the https://x.com/crisxai5 link, the hashtags #AI #Crypto #AIAgents #Web3,
and the account's make.fun play code.

## What this repo does

`main.ts` (Node 22, standard library only) copies `POST.json` from the
repository root to `/output/POST.json`, where the gate reads it. That is all
the program has to do. `POST.json` holds the post's address; it currently
holds the starter placeholder and is filled in with the real post URL once the
post is live on X.

## Run it locally

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`out/POST.json` is then byte for byte this directory's `POST.json`.

## License

MIT — see [LICENSE](LICENSE).
