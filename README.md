# The World in One Page — news-image-20261123

[![make.fun · news-image-20261123](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/imusic-487/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/imusic-487/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261123)

One image summing up the world's news of Monday 23 November 2026, entered on [make.fun](https://make.fun/bounty/news-image-20261123) — see the [bounty page](https://make.fun/bounty/news-image-20261123) for the competition.

## The image

A one-page dense news poster, "The World in One Page", with 50 stories from
23 November 2026: a UTC timeline across the top, 16 lead stories by region
with named sources and CLAIM / CONFIRMED labels, a schematic world map of
where it happened, a numbered 17–50 brief list, and a DATE CHECK box at the
foot. The lead is the collapse of the COP31 climate talks in Antalya with no
deal; the four large graphics are original drawn diagrams (the COP31 "NO
DEAL", the sinking of the corvette Merkury off Libya, the Democrats' 258-seat
House majority, and the AI stock sell-off), not photographs. Every headline
and summary is legible at 1024 pixels across.

## The program

`main.py` (Python 3.13, standard library only) copies `entry.png`, the image
beside it, to `/output/entry.png`, byte for byte. No network, no randomness,
no timestamps: every run writes the same bytes, so the judge sees exactly the
image this repository holds.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

- `main.py` — the entry program.
- `entry.png` — the image, 1024 by 1024, 328,321 bytes.
- `LICENSE` — MIT.
