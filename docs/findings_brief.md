# Network Performance Brief
## Melbourne Metropolitan Train — Timetable & Demand Analysis

| | |
|---|---|
| **Prepared by** | [Your Name] |
| **Date** | May 2026 |
| **Data** | GTFS timetable (May–Aug 2026) · Station entries FY2024-25 · Monthly patronage 2018–2026 |
| **Prepared for** | Network Planning and Timetabling |

---

## Purpose

This brief presents findings from an independent analysis of Melbourne's metropolitan train timetable and passenger demand data, using publicly available Transport Victoria datasets. It identifies three areas where the current timetable warrants closer examination, and provides patronage context relevant to any future timetable review.

---

## Finding 1 — Frequency disparity: Stony Point is a significant outlier

**What the data shows:**
Scheduled headway analysis across 17 metro lines reveals that most corridors operate at under 3 minutes between services during AM and PM peak periods. Stony Point is a stark exception at **17.3 minutes AM peak and 17.3 minutes PM peak** — more than five times the headway of the next worst-performing line (Williamstown at 2.5 minutes).

**Context:**
The Stony Point line is a diesel branch requiring a connection at Frankston, which constrains its operational flexibility. However, the scale of the frequency gap relative to the rest of the network is notable and may warrant review as part of any broader service level assessment.

**Recommendation for further analysis:**
Compare Stony Point's scheduled frequency against its franchise service level obligations and actual passenger demand at branch stations to determine whether the current headway reflects a deliberate planning decision or a candidate for improvement.

---

## Finding 2 — PM peak skew: CBD stations carry disproportionate evening load

**What the data shows:**
Analysis of time-of-day patronage at the top 20 stations reveals a pronounced asymmetry between AM and PM peak demand at CBD interchange stations:

| Station | AM peak (% of weekday entries) | PM peak (% of weekday entries) |
|---------|-------------------------------|-------------------------------|
| Parliament | 3.8% | **71.6%** |
| Flagstaff | 6.9% | **68.4%** |
| Southern Cross | 6.5% | **64.7%** |
| Melbourne Central | 4.3% | **56.8%** |
| Flinders Street | 5.9% | **55.3%** |

**What this means:**
CBD stations see between 8 and 18 times more entries in the PM peak than in the AM peak. This reflects the pattern of passengers arriving distributed throughout the morning (via a range of services) but departing in a concentrated evening window. The timetable must therefore carry significantly higher outbound loads in the PM peak than inbound loads in the AM peak — the reverse of what a symmetric timetable would assume.

**Recommendation for further analysis:**
Review whether PM peak outbound capacity on CBD-terminating services is proportional to this demand concentration, particularly on corridors where PM peak headways are wider than AM peak headways.

---

## Finding 3 — Patronage recovery at 75.8% of pre-COVID baseline

**What the data shows:**
Monthly patronage data from January 2018 to January 2026 shows the network averaging **15.3 million passengers per month** over the past 12 months, compared to a pre-COVID average of **20.2 million per month** — a recovery rate of **75.8%**.

**What this means:**
A ~4.9 million monthly passenger gap from the pre-COVID baseline suggests that travel patterns have shifted. If the current timetable was designed around 2019 demand, there may be corridors where services are over-supplied relative to current demand, and others (particularly those serving emerging residential growth areas) that are under-supplied.

**Recommendation for further analysis:**
Cross-reference corridor-level patronage recovery rates against current scheduled frequency to identify mismatches between supply and demand — corridors where frequency could be rebalanced without reducing passenger experience.

---

## Data limitations

- **Headway calculation** uses each trip's first scheduled departure as a proxy for network entry time. This is standard practice but does not account for service irregularity or actual running times.
- **Stony Point / City Loop headways** should be interpreted with care. Low Stony Point headway reflects its operational constraints; low City Loop headways reflect multi-line sharing at shared stops, not a single-line frequency.
- **Station entries data** reflects FY2024-25 and may not capture the most recent demand shifts. Peak period figures are daily averages, not totals.
- This analysis is based on the scheduled timetable only. Actual on-time performance data would be needed to assess reliability in addition to frequency.

---

## Data sources

- GTFS Schedule — Transport Victoria (`opendata.transport.vic.gov.au`)
- Annual Metropolitan Train Station Entries FY2024-25 — Transport Victoria
- Monthly Public Transport Patronage by Mode — Transport Victoria

Analysis code available at: `github.com/[your-username]/melbourne-train-analysis`

