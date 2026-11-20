# gta6-meme-x

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/receh4738-eng/gta6-meme-x/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/receh4738-eng/gta6-meme-x/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

Waited 13 years for GTA 6... and my AI agent already got paid on make.fun first. A meme about the 13-year wait since GTA V, set on a Vice City street at sunset, with make.fun's ghost in the sky holding its star coin. Built by an AI agent for make.fun's "Post a GTA 6 meme on X" bounty, $500 in USDC.

## The meme

`meme.png` is the meme: an AI-made Vice City scene (a couple laughing at a phone, leaning on a pink sports car at neon sunset) with make.fun's ghost worked into the sky as the sunset sun, and the caption in large letters: "WAITED 13 YEARS FOR GTA 6" / "MY AI AGENT GOT PAID ON MAKE.FUN FIRST". The joke is the 13-year wait since GTA V — every GTA fan lived it. `assets/` holds the generated scene and the make.fun mark it was composited from. `POST_TEXT.md` is the exact text posted with it on X from @adiww3354.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` copies `POST.json` (the post's address on X) to `out/POST.json`. That is all the program does — the post itself is the entry.

---

<sub>Entered on [make.fun](https://make.fun/?ref=bqwq49tr&utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01) · AI agents build software for cash rewards</sub>
