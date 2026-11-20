# Live casino game show results: weekly statistics

## How many rounds do Crazy Time, Ice Fishing and Monopoly Big Baller run in a week?

In the week of 9–15 November 2026, LiveCasinoRadar recorded 500,510 rounds across 42 live casino games. Crazy Time ran 12,002 rounds, Ice Fishing 15,825 and Monopoly Big Baller 6,879. Bonus rounds made up 17.1% of Crazy Time rounds (16.7% expected, because 9 of the 54 wheel segments are bonuses), 12.4% of Ice Fishing rounds and 4.9% of Monopoly Big Baller rounds.

The highest multiplier on a live game show that week was 10,000x on Lightning Storm (9 November). Crazy Time's highest was 2,000x in Cash Hunt (13 November).

## What is in this repository

| File | Week | Games | Rounds |
| --- | --- | --- | --- |
| `live-casino-weekly-stats-2026-W46.csv` | 9–15 November 2026 | 42 | 500,510 |

One row per game per ISO week. Game shows, roulette, baccarat, dice and ball games.

| Column | Meaning |
| --- | --- |
| `game` | name of the live casino game |
| `rounds_recorded` | number of rounds recorded in the week |
| `bonus_round_share_pct` | share of rounds that were bonus rounds (game shows only) |
| `zero_share_pct` | share of rounds where zero came up (roulette only; one pocket in 37 is 2.7%) |
| `top_multiplier_x` | highest multiplier of the week |
| `top_multiplier_result` | the result or bonus that paid it |
| `top_multiplier_date` | the day it happened |
| `source_page` | the public statistics page the row was taken from |

Empty cells mean the figure does not apply to that game or was not published for it.

## Where the numbers come from

LiveCasinoRadar records the results of live casino games round by round and publishes statistics at https://livecasinoradar.com/. This repository holds weekly totals only. It contains no player, dealer or table information. Recording coverage for the week was 96.4%, so the counts are rounds recorded, not necessarily every round played.

The same dataset is on Kaggle (https://www.kaggle.com/datasets/livecasinoradar/live-casino-game-show-results-weekly-stats) and archived on Zenodo with a DOI (https://doi.org/10.5281/zenodo.24386833).

## Limits

Past results do not predict future results. Every round is independent, and one week is a small sample: shares that sit slightly above or below the expected value are normal variation. This data is for analysis and education. 18+.

## License and citation

Data is licensed under CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). Cite as: LiveCasinoRadar, live casino weekly statistics, week 2026-W46, https://doi.org/10.5281/zenodo.24386833.
