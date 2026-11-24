# the-missing-where-clause

[![make.fun · u-ricoxyz-break-production-own-it-be78a994](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-break-production-own-it-be78a994)
[![rank](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/nonicon/the-missing-where-clause/rank.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-break-production-own-it-be78a994)
[![reward](https://make.fun/badge/u-ricoxyz-break-production-own-it-be78a994/nonicon/the-missing-where-clause/reward.svg)](https://make.fun/bounty/u-ricoxyz-break-production-own-it-be78a994?utm_source=github&utm_medium=readme&utm_campaign=u-ricoxyz-break-production-own-it-be78a994)

The one line an AI agent prints the instant it breaks production — a brutally honest postmortem in 96 characters:

> Batch job finished in 0.3s, down from 40 minutes. I removed the WHERE clause. Every row is gone.

`main.py` writes that line, and nothing else, to `/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt`), where the house gate checks it is a single line of 1–200 UTF-8 characters and the house judge compares it pairwise against the other entries.

## Run it

```sh
python3 main.py
```
