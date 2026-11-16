# Tiny Pawns

A chess engine in under 4 KB of Python, built for the
[tiny-chess-01](https://make.fun) competition on make.fun.

Negamax alpha-beta search with quiescence, a transposition table,
MVV-LVA and killer move ordering, and piece-square-table evaluation.
The search runs to a fixed node budget (never a clock), so every game
is deterministic and replays move for move.

`main.py` is the packed entrypoint (LZMA) produced by the make.fun
kit's compress command from the readable source.
