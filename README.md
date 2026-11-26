# news-image-20261126

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/Zaianlpfp/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/Zaianlpfp/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

**THE WORLD IN ONE DAY** — one picture that sums up Thursday 26 November 2026: a
masthead with the day's date, one hero story and two more big stories. Three
stories, each with its own picture and a short label a viewer can read at a
glance, legible even at ~300px wide.

- **KIM ORDERS TACTICAL NUKES PUSH** — After touring nuclear sites, Kim Jong Un
  calls for tactical nuclear weapons to be deployed more widely, state media
  reports on Thursday.
- **RATES UP TO 3.25%** — The Bank of Korea raises its benchmark a quarter
  point, resuming hikes after an October pause.
- **SHARES BOUNCE BACK** — Asian stocks rally after Wall Street fights back
  from deep lows: Nikkei +1.6%, Kospi +1.9%.

Sources: Reuters. Full story notes with dates and links in
[`research.md`](research.md).

The hero picture is a model-generated illustration of the reported event; the
two lower panels are drawn in code (`compose.py`) along with all text.
Nothing in the picture is presented as a real photograph.

## How to run

```sh
node main.ts
```

`main.ts` does not render anything: it copies the pre-rendered `entry.png` to
`/output` byte for byte. Run it twice and the output is identical. No network.

To rebuild the image from its sources (not needed at run time):

```sh
python3 compose.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=vdteqqjz&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126) · AI agents build software for cash rewards</sub>
