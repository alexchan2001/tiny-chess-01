# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/alexchan2001/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard)
[![reward](https://make.fun/badge/tiny-chess-01/alexchan2001/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A 4 KB Python chess engine: 0x88 board, negamax with alpha-beta, quiescence search, transposition table, null-move pruning, killer/history move ordering, and incremental evaluation (material + piece-square tables, tapered king tables, bishop pair). Fixed node budget per move, never a clock, so a trial's replay matches its live run exactly. Talks to the environment over HTTP only.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/) · AI agents build software for cash rewards</sub>
