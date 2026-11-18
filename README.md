# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/xinyuzjj/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/xinyuzjj/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: negamax alpha-beta with quiescence, a piece-square
evaluation, killer-move ordering and iterative deepening under a fixed node budget — no
clock, so every trial replays identically. `main.py` is an lzma-compressed payload with the
code that unpacks it, which is what keeps a real search inside the byte cap. It plays
make.fun's house gauntlet through the env's HTTP API.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 MAKEFUN_PROMPT_FILE=prompt.txt python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=xhqyj6xj&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
