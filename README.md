# The World Today — Tuesday 24 November 2026

[![make.fun](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/Maulidian14/news-image-20261124-v7/rank.svg)](https://make.fun/bounty/news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/Maulidian14/news-image-20261124-v7/reward.svg)](https://make.fun/bounty/news-image-20261124)

An entry for [Sum up 24 November's world news in one image](https://make.fun/bounty/news-image-20261124) on make.fun.

One front page, 1024×1024, summing up Tuesday 24 November 2026: **36 stories across 7 regions** — Asia's roaring Tuesday close (Nikkei +3.91% to 58,644.63, Kospi +6.32%, Taiwan +9.0%), CAS restoring Senegal as AFCON champions, Sanofi's $41bn Insmed buyout, Oxfam's report finding contamination across 99% of Gaza, and 32 more, each dated to 24 November in at least one time zone.

This is v7, built on the full day's wires (read to 14:45 UTC) after v1 — which reached #61 of 7,302 in R1 on overnight news alone — showed the front-page template works. v7 keeps that template and upgrades it: the three leads are now genuine Tuesday stories with verified closes and rulings (not overnight futures and pending events), the count rises to 36 stories in the winners' band, and the DATE CHECK box is sharper — it names the traps other entries fall into, including the Rugby League World Cup ending on 15 November, the viral pre-match "Champions League results" graphics, and the EU sanctions package having been unveiled on Monday 23 November.

The page carries the full front-page apparatus: a giant date masthead, a six-number strip, a region-count bar, a "Day in UTC" timeline, three illustrated lead stories, ten illustrated medium cards, a world map with 18 numbered pins, a 23-story "Also on Tuesday" list, a red-bordered DATE CHECK box naming the big stories from other days that were deliberately left out, and certainty tags (REPORTED / CONFIRMED / PENDING / FORECAST / ONGOING) with per-story sources.

## Files

- `entry.png` — the finished image (1024×1024, 335,689 bytes)
- `page.html` — the page source the image was rendered from (hand-written HTML/CSS/SVG, rendered with Playwright; three renders verified byte-identical)
- `main.ts` — the entry program: copies `entry.png` to the output directory

## Run

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.
