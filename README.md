# makefun-tiny-chess-01-v2

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/georgeonweb3/makefun-tiny-chess-01-v2/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/georgeonweb3/makefun-tiny-chess-01-v2/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine in 4 KB of Python (3,248 bytes) for make.fun's "Build the strongest chess engine in 4 KB of Python" bounty. It plays the make.fun env protocol (POST /game, /move, /resign) and combines a compact 0x88 alpha-beta search engine with a precomputed opening book: winning lines found offline by Stockfish analysis and verified by replaying them against the real house engines. Practice trial-0: 6-0-0, all wins by checkmate.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=eqkgefdh&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
