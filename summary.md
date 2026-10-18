# poptimusgrime — chess.com game history

Complete game archive downloaded from the chess.com public API ([player archives endpoint](https://api.chess.com/pub/player/poptimusgrime/games/archives)) on 2026-10-18. Games are deduplicated by their chess.com game `Link`.

## Overview

| | |
|---|---|
| **Total games** | 3,150 |
| **Date range** | 2025-08-29 → 2026-10-18 (416 days, 15 months) |
| **Record (W–L–D)** | 1552–1521–77 |
| **Win rate** | 49.3% |
| **Score** | 50.5% (wins + ½ draws) |
| **Monthly archives** | 15 listed, 15 fetched, 0 failed |

## Win / loss / draw

| Outcome | Games | Share |
|---|---|---|
| Wins | 1552 | 49.3% |
| Losses | 1521 | 48.3% |
| Draws | 77 | 2.4% |
| **Total** | **3150** | **100.0%** |

## By time control

Time classes follow chess.com's convention: an estimated duration of `base + 40 × increment` seconds, bucketed as Bullet (< 180s), Blitz (180–599s), Rapid (≥ 600s); move-based controls are Daily.

| Time class | Games | Share | W | L | D | Score |
|---|---|---|---|---|---|---|
| **Blitz** | 2965 | 94.1% | 1465 | 1432 | 68 | 50.6% |
| **Rapid** | 177 | 5.6% | 84 | 84 | 9 | 50.0% |
| **Bullet** | 7 | 0.2% | 2 | 5 | 0 | 28.6% |
| **Daily** | 1 | 0.0% | 1 | 0 | 0 | 100.0% |

### Individual time controls

| Time class | Control | Games | Share | W | L | D | Score |
|---|---|---|---|---|---|---|---|
| Blitz | 3 min (`180`) | 2923 | 92.8% | 1444 | 1412 | 67 | 50.5% |
| Rapid | 10 min (`600`) | 177 | 5.6% | 84 | 84 | 9 | 50.0% |
| Blitz | 5 min (`300`) | 35 | 1.1% | 17 | 17 | 1 | 50.0% |
| Blitz | 3 min + 2s (`180+2`) | 7 | 0.2% | 4 | 3 | 0 | 57.1% |
| Bullet | 2 min + 1s (`120+1`) | 4 | 0.1% | 2 | 2 | 0 | 50.0% |
| Bullet | 1 min (`60`) | 2 | 0.1% | 0 | 2 | 0 | 0.0% |
| Bullet | 1 min + 1s (`60+1`) | 1 | 0.0% | 0 | 1 | 0 | 0.0% |
| Daily | 3 day/move (`1/259200`) | 1 | 0.0% | 1 | 0 | 0 | 100.0% |

## By color

| Color | Games | Share | W | L | D | Score |
|---|---|---|---|---|---|---|
| White | 1576 | 50.0% | 853 | 685 | 38 | 55.3% |
| Black | 1574 | 50.0% | 699 | 836 | 39 | 45.6% |

## By month

Grouped by each game's `UTCDate`, which can differ from the monthly archive a game is filed under at a month boundary.

| Month | Games | W | L | D | Score |
|---|---|---|---|---|---|
| 2025-08 | 3 | 2 | 1 | 0 | 66.7% |
| 2025-09 | 253 | 115 | 127 | 11 | 47.6% |
| 2025-10 | 582 | 286 | 283 | 13 | 50.3% |
| 2025-11 | 295 | 146 | 140 | 9 | 51.0% |
| 2025-12 | 201 | 103 | 95 | 3 | 52.0% |
| 2026-01 | 136 | 66 | 69 | 1 | 48.9% |
| 2026-02 | 195 | 94 | 97 | 4 | 49.2% |
| 2026-03 | 217 | 112 | 98 | 7 | 53.2% |
| 2026-04 | 194 | 96 | 95 | 3 | 50.3% |
| 2026-05 | 169 | 82 | 83 | 4 | 49.7% |
| 2026-06 | 117 | 60 | 56 | 1 | 51.7% |
| 2026-07 | 183 | 86 | 92 | 5 | 48.4% |
| 2026-08 | 199 | 103 | 92 | 4 | 52.8% |
| 2026-09 | 271 | 135 | 129 | 7 | 51.1% |
| 2026-10 | 135 | 66 | 64 | 5 | 50.7% |

## Rating

Rating carried in each game's PGN for poptimusgrime, by time class (first and last game chronologically, and the peak).

| Time class | First | Last | Peak | Games |
|---|---|---|---|---|
| Blitz | 345 (2025-09-20) | 549 (2026-10-18) | 581 | 2965 |
| Rapid | 573 (2025-08-29) | 528 (2025-11-01) | 636 | 177 |
| Bullet | 397 (2025-10-06) | 175 (2026-09-12) | 533 | 7 |
| Daily | 546 (2026-07-23) | 546 (2026-07-23) | 546 | 1 |

## How games ended

Termination methods, with the outcome from poptimusgrime's perspective. (chess.com writes the winner's username into each `Termination` tag; these are grouped by method.)

| Method | Games | Share | Won | Lost | Drawn |
|---|---|---|---|---|---|
| Resignation | 1441 | 45.7% | 396 | 1045 | 0 |
| Checkmate | 659 | 20.9% | 479 | 180 | 0 |
| Time | 641 | 20.3% | 502 | 139 | 0 |
| Game abandoned | 332 | 10.5% | 175 | 157 | 0 |
| Timeout vs insufficient material | 34 | 1.1% | 0 | 0 | 34 |
| Stalemate | 29 | 0.9% | 0 | 0 | 29 |
| Insufficient material | 7 | 0.2% | 0 | 0 | 7 |
| Agreement | 3 | 0.1% | 0 | 0 | 3 |
| Repetition | 3 | 0.1% | 0 | 0 | 3 |
| 50-move rule | 1 | 0.0% | 0 | 0 | 1 |

---

Source data: `poptimusgrime_all_games.pgn` (3,150 games concatenated from 15 monthly PGN archives).
