# makefun-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/ryanp1632-netizen/makefun-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/ryanp1632-netizen/makefun-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python 3.13. It keeps the board as a 120-character string seen from the side to move, generates pseudo-legal moves and rejects illegal ones when the reply would capture the king, and searches with principal-variation alpha-beta, a transposition table, null-move pruning, late-move reductions, killer and history move ordering and a quiescence search over captures. Its evaluation is PeSTO's piece-square tables, tapered by game phase at the root. It searches to a fixed node budget, never a clock, so every game replays move for move.

## Run it

```sh
MAKEFUN_ENV_URL=http://localhost:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=z79n7aa6&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
