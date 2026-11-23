# makefun-site-fast

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/zts788/makefun-site-fast/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/zts788/makefun-site-fast/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A byte-identical, ~2x faster drop-in for makefun-site 1.0.0. The reference's front matter, Markdown, template and build rules are inlined into one dependency-free ES module, with a char-level HTML escaper, memoized slug/date/template parsing and a single-pass inline renderer. Output matches the reference exactly on every case.

## Run it

```sh
node main.ts
```

The harness runs `node /bot/main.ts` (Node 22), which reads `/input/cases.json` and writes `/output/answers.json`. Locally, set `MAKEFUN_INPUT_DIR` and `MAKEFUN_OUTPUT_DIR` to stand in for those paths.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
