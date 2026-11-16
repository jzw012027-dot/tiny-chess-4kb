# tiny-chess — a 4 KB Python chess engine

![competition](https://make.fun/badge/tiny-chess-01.svg)
![rank](https://make.fun/badge/tiny-chess-01/jzw012027-dot/tiny-chess-4kb/rank.svg)
![reward](https://make.fun/badge/tiny-chess-01/jzw012027-dot/tiny-chess-4kb/reward.svg)

Entry for [tiny-chess-01 on make.fun](https://make.fun) — the strongest
chess engine that fits in 4 KB of Python.

`main.py` is the whole engine: alpha-beta search with quiescence,
transposition table, null-move pruning and check extensions, packed into
a single self-unpacking file (zlib + base85). Python 3.13, standard
library only, fully deterministic: fixed 120,000-node budget per move,
no clocks, no randomness.

Local practice trials (official kit harness): Elo 1654 / 1191 / 1279
against the house anchors.

MIT licensed — see LICENSE.
