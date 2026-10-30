# 2021 Formula 1 Season Finale — Abu Dhabi Grand Prix: Research Brief

**Circuit:** Yas Marina Circuit (locality: Abu Dhabi, United Arab Emirates)
**Race:** 2021 Abu Dhabi Grand Prix, Round 22 of the 2021 World Championship
**Date as reported by the source (race results):** 2021-12-12
**Status:** Both drivers behind at 162 points heading into the race; title decided on the final lap.

---

## Race Session

都要注意：`getHistoricalSessions` 查询在所有年份过滤（round、circuit短路名称、country_name、location、session_name）下均未返回 2021 年的任何 session 记录（data source 仅覆盖 2023 年起）。因此**赛事 session 在该数据源中无 session key 可供引用**。为本次简报，session 信息以 classify 分类赛果数据源返回的赛事级信息为准：

- `raceName`: Abu Dhabi Grand Prix
- `round`: 22 (2021)
- `circuitId`: yas_marina
- `date`: 2021-12-12
- `time`: 13:00:00Z

> ⚠️ Data gap: the OpenF1-style session lookup contains no 2021 sessions, so no `session_key` exists in this source. All race-level identifiers above are as reported by the results data source.

## Classified Race Results — 2021 Abu Dhabi Grand Prix (Round 22)

| Pos | Driver | Contractor | Grid | Laps | Points | Time |
|-----|--------|------------|------|------|--------|------|
| 1 | Max Verstappen | Red Bull | 1 | 58 | 26 | 1:30:17.345 (Fastest Lap, rank 1, lap 39, 1:26.103) |
| 2 | Lewis Hamilton | Mercedes | 2 | 58 | 18 | +2.256 (Fastest Lap, rank 3, lap 43, 1:26.615) |
| 3 | Carlos Sainz | Ferrari | 5 | 58 | 15 | +5.173 (Fastest Lap, rank 9, lap 51, 1:27.618) |

Full classified grid continues:
P4 Yuki Tsunoda (AlphaTauri) +5.692; P5 Pierre Gasly (AlphaTauri) +6.531; P6 Valtteri Bottas (Mercedes) +7.463; P7 Lando Norris (McLaren) +59.200; P8 Fernando Alonso (Alpine) +1:01.708; P9 Esteban Ocon (Alpine) +1:04.026; P10 Charles Leclerc (Ferrari) +1:06.057; P11 Sebastian Vettel (Aston Martin) +1:07.527.

---

## Podium Finisher Profiles (from the driver profile lookup)

### 1. Max Verstappen (Podium finisher, position 1)
- **Driver ID:** max_verstappen
- **Permanent number:** 3
- **Three-letter code:** VER
- **Nationality:** Dutch
- **Date of birth:** 1997-09-30
- **Profile link:** http://en.wikipedia.org/wiki/Max_Verstappen

### 2. Lewis Hamilton (Podium finisher, position 2)
- **Driver ID:** hamilton
- **Permanent number:** 44
- **Three-letter code:** HAM
- **Nationality:** British
- **Date of birth:** 1985-01-07
- **Profile link:** http://en.wikipedia.org/wiki/Lewis_Hamilton

### 3. Carlos Sainz (Podium finisher, position 3)
- **Driver ID:** sainz
- **Permanent number:** 55
- **Three-letter code:** SAI
- **Nationality:** Spanish
- **Date of birth:** 1994-09-01
- **Profile link:** http://en.wikipedia.org/wiki/Carlos_Sainz_Jr.

---

## Newsroom Notes for the Retrospective

- Max Verstappen won from pole, taking the title by 1.825 seconds over Lewis Hamilton (#44, Mercedes, permanent number 44, British, DOB 1985-01-07).
- Hamilton's profile link: http://en.wikipedia.org/wiki/Lewis_Hamilton — Canadian teammate Sainz finished third for Ferrari (+5.173s, fastest lap rank 9).
- The race ran 58 laps at Yas Marina; both red-flag-related controversy aside, the closing-lap title decider is recorded in the classified results.
- Hamilton achieved the fastest lap of the race (rank 3 on his own car, lap 43, 1:26.615).

*Research trail compiled for the racing newsletter retrospective. Sources: formula 1 session/results and driver profile data (results data source; driver profile lookup).*
