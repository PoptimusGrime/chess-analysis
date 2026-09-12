# poptimusgrime — chess.com game history

Complete game archive downloaded from the chess.com public API ([player archives endpoint](https://api.chess.com/pub/player/poptimusgrime/games/archives)) on 2026-09-12.

## Overview

| | |
|---|---|
| **Total games** | 2,864 |
| **Date range** | 2025-08-29 → 2026-09-12 (380 days, 14 months) |
| **Record (W–L–D)** | 1407–1390–67 |
| **Win rate** | 49.1% |
| **Score** | 50.3% (wins + ½ draws) |
| **Monthly archives** | 14 fetched, 14 succeeded, 0 failed |

## Win / loss / draw

| Outcome | Games | Share |
|---|---|---|
| Wins | 1407 | 49.1% |
| Losses | 1390 | 48.5% |
| Draws | 67 | 2.3% |
| **Total** | **2864** | **100.0%** |

## By time control

Time classes follow chess.com's convention: an estimated duration of `base + 40 × increment` seconds, bucketed as Bullet (< 180s), Blitz (180–599s), Rapid (≥ 600s); move-based controls are Daily.

| Time class | Games | Share | W | L | D | Score |
|---|---|---|---|---|---|---|
| **Blitz** | 2679 | 93.5% | 1320 | 1301 | 58 | 50.4% |
| **Rapid** | 177 | 6.2% | 84 | 84 | 9 | 50.0% |
| **Bullet** | 7 | 0.2% | 2 | 5 | 0 | 28.6% |
| **Daily** | 1 | 0.0% | 1 | 0 | 0 | 100.0% |

### Individual time controls

| Time class | Control | Games | Share | W | L | D | Score |
|---|---|---|---|---|---|---|---|
| Blitz | 3 min (`180`) | 2637 | 92.1% | 1299 | 1281 | 57 | 50.3% |
| Rapid | 10 min (`600`) | 177 | 6.2% | 84 | 84 | 9 | 50.0% |
| Blitz | 5 min (`300`) | 35 | 1.2% | 17 | 17 | 1 | 50.0% |
| Blitz | 3 min + 2s (`180+2`) | 7 | 0.2% | 4 | 3 | 0 | 57.1% |
| Bullet | 2 min + 1s (`120+1`) | 4 | 0.1% | 2 | 2 | 0 | 50.0% |
| Bullet | 1 min (`60`) | 2 | 0.1% | 0 | 2 | 0 | 0.0% |
| Bullet | 1 min + 1s (`60+1`) | 1 | 0.0% | 0 | 1 | 0 | 0.0% |
| Daily | 3 day/move (`1/259200`) | 1 | 0.0% | 1 | 0 | 0 | 100.0% |

## By color

| Color | Games | Share | W | L | D | Score |
|---|---|---|---|---|---|---|
| White | 1433 | 50.0% | 764 | 634 | 35 | 54.5% |
| Black | 1431 | 50.0% | 643 | 756 | 32 | 46.1% |

## Games per month

| Month | Games |
|---|---|
| 2025-08 | 3 |
| 2025-09 | 253 |
| 2025-10 | 582 |
| 2025-11 | 295 |
| 2025-12 | 201 |
| 2026-01 | 136 |
| 2026-02 | 195 |
| 2026-03 | 217 |
| 2026-04 | 194 |
| 2026-05 | 169 |
| 2026-06 | 117 |
| 2026-07 | 183 |
| 2026-08 | 199 |
| 2026-09 | 120 |

## How games ended

Termination methods, with the outcome from poptimusgrime's perspective. (chess.com writes the winner's username into each `Termination` tag; these are grouped by method.)

| Method | Games | Share | Won | Lost | Drawn |
|---|---|---|---|---|---|
| Resignation | 1319 | 46.1% | 354 | 965 | 0 |
| Time | 589 | 20.6% | 456 | 133 | 0 |
| Checkmate | 580 | 20.3% | 433 | 147 | 0 |
| Game abandoned | 309 | 10.8% | 164 | 145 | 0 |
| Timeout vs insufficient material | 30 | 1.0% | 0 | 0 | 30 |
| Stalemate | 28 | 1.0% | 0 | 0 | 28 |
| Insufficient material | 5 | 0.2% | 0 | 0 | 5 |
| Agreement | 3 | 0.1% | 0 | 0 | 3 |
| 50-move rule | 1 | 0.0% | 0 | 0 | 1 |

---

Source data: `poptimusgrime_all_games.pgn` (2,864 games concatenated from 14 monthly PGN archives).
