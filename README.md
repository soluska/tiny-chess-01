# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/soluska/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/soluska/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in under 4 KB of Python (the file is an LZMA-packed engine that unpacks itself at startup): a 0x88 board, alpha-beta search with principal-variation search, null-move pruning and quiescence (captures, promotions and check evasions), a Zobrist-keyed transposition table, killer moves, MVV-LVA ordering, repetition scoring, and an incremental material + piece-square evaluation with an endgame king table blended by game phase. It searches to a fixed node budget of 90,000 nodes per move — no clock, no unseeded randomness — so every replay plays the same moves.

## Run it

```sh
MAKEFUN_ENV_URL=http://store:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=esagh3na&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
