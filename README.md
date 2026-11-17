# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/dengzy1998/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/dengzy1998/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

An original chess engine in 4,079 bytes of Python: a 0x88-board negamax alpha-beta search with PVS, late-move reductions, null-move pruning and check extensions, quiescence over captures, promotions and check evasions, MVV-LVA and history move ordering, and formula-generated piece-square tables. It plays deterministically under a fixed 85,000-node cap per move (no clock, no randomness), tracks repetitions and the fifty-move rule, and speaks to the make.fun trial env over HTTP. The engine source is lzma-packed into main.py, which unpacks and runs it with the standard library alone.

## Run it

```sh
MAKEFUN_ENV_URL=<env origin> python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=01wh7qnm&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
