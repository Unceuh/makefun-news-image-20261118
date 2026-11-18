# makefun-news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/Unceuh/makefun-news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/Unceuh/makefun-news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A newspaper front page summing up Wednesday 18 November 2026's world news in one image: US strikes on Qeshm Island, the Kerch Bridge hit, APEC in Shenzhen, Democrats winning Alaska, the US losing measles-free status, and the Ebola surge in Congo.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## The image

A 1024x1024 newspaper front page, "WORLD NEWS", dated Wednesday, 18 November 2026. Six numbered stories:

1. US STRIKES IRAN — US warplanes hit a missile site on Qeshm Island; Iran fired drones at US sites in Bahrain and Kuwait.
2. KERCH BRIDGE HIT AGAIN — Ukraine struck the Kerch Bridge to Crimea for a second day; part of a road span fell into the strait.
3. APEC OPENS IN SHENZHEN — Xi Jinping and Vladimir Putin opened APEC; a three-way meeting with Donald Trump is ahead.
4. DEMOCRATS WIN ALASKA — Democrat Mary Peltola won the Alaska Senate race; Democrats now hold a 56-44 majority.
5. US LOSES MEASLES STATUS — The US lost measles elimination status after 26 years: 5,412 cases in 2026, 10 deaths.
6. EBOLA SURGE IN CONGO — The Ebola outbreak in DR Congo passed 11,000 cases and 5,400 deaths; children under 5 are hardest hit.

Footer briefs: Voyager 1 reaches one light-day from Earth; Category 5 Cyclone Xavier hits the Northern Cook Islands; a Russian military plane crashes in Siberia, 19 dead.

The image was drawn with Pillow locally (simple shapes and DejaVu text, no photos or copied artwork) and is shipped as `entry.png`.

`main.py` is standard library only: it copies `entry.png` beside it to `$MAKEFUN_OUTPUT_DIR/entry.png` (default `/output`). It uses no network, so both grader runs write identical bytes.

## License

MIT — see `LICENSE`.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
