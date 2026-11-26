# Think Ahead regional storage and data-center network — sizing scenario

**Date:** November 25, 2026 (America/Denver)  
**Document type:** Planning scenario of Jason’s concept. It is not current Xcel or Colorado policy, not an engineered siting plan, and not a board-approved build list.  
**Companion record:** [docs/11-storage-network-and-tiers.md](11-storage-network-and-tiers.md) records the same concept in Jason’s words, without a site-count model. This file is the sizing and 10-year line projection that document said had not yet been written.  
**Sources for inputs:** `business-plan/solar-shade-system.md` section 10.6; `business-plan/whole-home-solar-payback.md` (especially section 15); public sources listed at the end. The Prison Data Center & Power project was checked on the box and has **no sourced site list and no facility loads**.

Figures are either (a) cited, (b) taken from existing Think Ahead drafts, or (c) calculated from those inputs and labeled as a calculation or estimate. Gaps are marked. No figure was invented to look like a contract or a measured Colorado bill.

---

## Headline (30% efficiency, placeholder install ramp)

On the section 10.6 placeholder ramp (100 systems in year 1, rising to 1,700 in year 10; **8,350 cumulative**), excess power is about **1.3 MW average in year 1**, **8.2 MW in year 3**, **23 MW in year 5**, and **106 MW in year 10**. After a typical data-center overhead (PUE 1.54), that supports about **0.8 / 5.3 / 15 / 69 MW of IT load**.

**How many sites to build (planning rule, not a design):** about **1 small edge site in year 1**, **1–2 sites by year 3**, **about 4 edge modules or one ~15 MW campus by year 5**, and **about 14 edge modules or one ~70 MW hyperscale campus by year 10**. A 1% penetration of Denver-metro housing units with this 100 kW package is already about a **106 MW IT** campus. 5% and 10% are multiple hyperscale campuses and are not a near-term plan.

Mid-case infrastructure capex (utility-scale 4-hour batteries plus data-center building, **excluding chips and GPUs**), on top of the solar systems themselves, is about **$16 million in year 1** and about **$1.34 billion by year 10**. Solar-system delivered cost on the same ramp is about **$6.06 billion** if Think Ahead owns the gear (Tier 2). The 10-year operating net on the 2×-retail spread, after PV upkeep only, is about **$964 million**, so cash after capex is deeply negative through year 10. That is a scenario, and it hangs on a buyer actually paying 30¢/kWh.

---

## 1. Concept, as modeled

Jason’s concept, modeled here as a scenario:

- Homeowner solar sends excess power to **regional battery storage** and to **Think Ahead’s own data centers**.
- **Think Ahead is the data center** and **guarantees the purchase** so the facility can be run as a **carbon-negative** facility (the claim’s requirements are in section 13; the architecture does not make that claim true by itself).
- Power is offered **first to prisons** (the separate Prison Data Center & Power project), **then to schools** (idle in summer), **then sold to the highest bidders**.
- Homeowners can **see which site their power goes to**, and sites are **placed within their areas**.
- Product tiers: (1) **Buy now and invest in data centers**; (2) **Let us pay your electric bill** (already modeled in whole-home payback section 15); (3) **Own your own system and sell power back to us**.

An important accounting point: if Think Ahead is both the guarantor and the data center, a “sale at 30¢/kWh” is an **internal transfer** until the data center earns real compute revenue, or until an outside buyer actually pays that price. No Colorado utility pays anything close to double retail today (section 15: Xcel leftover credit about **1.16¢/kWh**). This file reuses the 30¢ scenario so the line can be compared with that draft; it is not a market price.

---

## 2. Inputs used (not re-derived)

| Input | Value | Source |
|---|---|---|
| Annual AC output per home, net of snow-melt pulses | **117,830 kWh** (30%); **129,640 kWh** (33%) | whole-home payback, section 6 |
| Typical household use | **7,008 kWh/year** (584 kWh/month) | Xcel Energy Colorado average, EIA 2025, as used in the payback draft |
| Excess per home | **110,822 kWh** (30%); **122,632 kWh** (33%) | calculated: output minus 7,008 |
| Nameplate (for context) | 100.34 kW (30%); 110.37 kW (33%) | payback draft |
| Delivered system cost (base) | **$725,500** (30%); **$797,500** (33%) | payback draft, section 7 |
| 2× retail scenario price | **$0.30/kWh** (2 × $0.15) | payback section 15; hypothetical |
| Bill rebate (7,008 kWh at $0.15) | **$1,051/year** | payback section 15 |
| Spread Think Ahead keeps (Tier 2) | **$34,298/year** (30%); **$37,841/year** (33%) | payback section 15 |
| Net after estimated PV O&M | **$31,305/year** (30%); **$34,548/year** (33%) | payback section 15 |
| Install ramp, years 1–10 | 100, 200, 350, 500, 700, 900, 1,100, 1,300, 1,500, 1,700 | shade-system section 10.6; **planning placeholder, not a board-approved plan** |
| Cumulative systems, year 10 | **8,350** | calculated from that ramp |
| Denver-metro housing units | **1,290,063** | U.S. Census Bureau ACS 2020–2024, Denver-Aurora-Centennial MSA, as compiled by public MSA profiles |
| Front Range housing units (broader) | **2,074,191** in a 10-county core | Colorado State Demography Office Vintage 2024, already cited in the shade-system draft |

Hours used for “average MW” are **8,760**. That is the same annual-hour convention as the payback draft.

---

## 3. Per-home energy math (calculated)

| | 30% | 33% |
|---|---:|---:|
| Output | 117,830 kWh/yr | 129,640 kWh/yr |
| Home use | 7,008 kWh/yr | 7,008 kWh/yr |
| Excess | 110,822 kWh/yr | 122,632 kWh/yr |
| Daily excess | 304 kWh | 336 kWh |
| Average continuous power, excess | **12.65 kW** | **14.00 kW** |
| Homes to supply **1 MW average** (energy only) | **79** | **71** |
| Homes to supply **1 MW of IT** at PUE 1.54 | **122** | **110** |
| Homes to supply **1 MW of IT** at PUE 1.20 | **95** | **86** |

PUE 1.54 is the Uptime Institute 2025 Global Data Center Survey **weighted average**. PUE 1.20 is a **high-efficiency sensitivity**, not that survey’s average. Facility electrical load ≈ IT load × PUE, so a 1 MW IT hall needs about 1.2–1.54 MW of firm power.

**Intermittency.** The project’s own 30% package has an implied capacity factor of about **13.4%** (117,830 kWh ÷ (100.34 kW × 8,760 h)). All of that energy arrives in daylight, and less of it in winter. Annual megawatt-hours matching 1 MW of load is **not** the same as running 1 MW at night or in December. An EPRI 24/7 carbon-free energy example found that a **346 MW** solar plant matched the annual energy of a flat **100 MW** load but only about **40% of hourly demand** without enough storage and other resources. Storage or another firming resource is required; the battery sizes below are that firming, not a complete seasonal solution.

---

## 4. Aggregate energy — ramp and metro penetration

Excess energy and average power, calculated from the inputs above. IT load assumes **all** excess is firmed into Think Ahead compute at PUE **1.54**. If prisons or schools take some power, IT load is lower.

### 4.1 Placeholder install ramp (section 10.6)

| Stage | Cumulative homes | Excess, 30% (MWh/yr) | Avg MW, 30% | IT MW @ PUE 1.54 | Excess, 33% (MWh/yr) | Avg MW, 33% | IT MW @ PUE 1.54 |
|---|---:|---:|---:|---:|---:|---:|---:|
| Year 1 | 100 | 11,082 | 1.27 | 0.82 | 12,263 | 1.40 | 0.91 |
| Year 3 | 650 | 72,034 | 8.22 | 5.34 | 79,711 | 9.10 | 5.91 |
| Year 5 | 1,850 | 205,021 | 23.40 | 15.20 | 226,869 | 25.90 | 16.82 |
| Year 10 | 8,350 | 925,364 | 105.64 | 68.59 | 1,023,977 | 116.89 | 75.90 |

### 4.2 Denver-metro penetration (1.290 million housing units)

These cases apply the **same 100 kW whole-home package** to 1%, 5%, and 10% of MSA housing units. They are order-of-magnitude stresses, not a sales forecast. Most units are not gable single-family homes, and the package makes 12–18 times household use.

| Penetration | Homes | Excess, 30% (GWh/yr) | Avg MW, 30% | IT MW @ 1.54 | Excess, 33% (GWh/yr) | Avg MW, 33% | IT MW @ 1.54 |
|---|---:|---:|---:|---:|---:|---:|---:|
| 1% | 12,901 | 1,430 | 163 | 106 | 1,582 | 181 | 117 |
| 5% | 64,503 | 7,148 | 816 | 530 | 7,910 | 903 | 586 |
| 10% | 129,006 | 14,297 | 1,632 | 1,060 | 15,820 | 1,806 | 1,173 |

---

## 5. Daily storage need (calculated; $/kWh cited)

Two planning durations are shown:

- **4-hour storage**, the duration used in NREL’s published utility-scale cost benchmarks: enough to carry the average excess power for four hours (evening peak), not all night.
- **Overnight-shift storage**, taken here as **16 hours** (a planning simplification for a long night with roughly eight hours of solar). This does **not** solve multi-day storms or winter seasonal shortfalls (NREL’s 100% clean-electricity work flags longer-duration storage for those gaps).

Batteries are sized at the **community average excess MW**, which is the right scale for firming a flat data-center load. They are **not** sized to every home’s ~100 kW instantaneous peak.

| Stage (30%) | Avg MW | 4-hour BESS (MWh) | 16-hour BESS (MWh) |
|---|---:|---:|---:|
| Year 1 | 1.27 | 5.1 | 20.2 |
| Year 3 | 8.22 | 32.9 | 131.6 |
| Year 5 | 23.40 | 93.6 | 374.5 |
| Year 10 | 105.64 | 422.5 | 1,690 |
| 1% metro | 163 | 653 | 2,611 |
| 5% metro | 816 | 3,264 | 13,056 |
| 10% metro | 1,632 | 6,528 | 26,113 |

At 33%, storage is about **11% higher** (excess is 122,632 / 110,822).

**Cost basis (cited):** NREL, *Cost Projections for Utility-Scale Battery Storage: 2025 Update* (Cole et al.), overnight capital cost for a complete **4-hour** lithium-ion system in **2026**, in **2024 dollars**: **$255 / $308 / $366 per kWh** (low / mid / high). The 16-hour line applies that same $/kWh as a **rough bound only**; NREL’s published figures are for 4-hour systems, and a longer-duration pack has a different mix of power and energy costs.

Per home, 30% case, mid $308/kWh: about **51 kWh and $15,600** for 4-hour firming, or about **202 kWh and $62,300** for 16-hour firming.

The whole-home payback draft used about **$998/kWh** for a **residential** pack. That is a different product and is not used for these regional utility-scale estimates.

---

## 6. Data-center sizing and how many sites to build

**Size bands (cited, then used as planning bands).** Industry cost guides treat **edge** facilities as roughly **0.5–5 MW** (some sources use 0.5–2 MW for the smallest edge and 5–20 MW for enterprise / large edge) and **hyperscale** as **50 MW and up**, often **100 MW or more** in a single campus phase. This memo uses **1–5 MW** as the edge module and **50–100+ MW** as hyperscale, consistent with that literature and with the brief.

**Cost basis (cited):** Cushman & Wakefield, 2026 Data Center Development Cost Guide, press release dated September 3, 2026: all-in greenfield development costs in the United States and Canada average **$17.6 million per megawatt** for the most modern facilities, **excluding chips and GPUs**. Secondary summaries of the same guide report a range of about **$8.9–$23.3 million per MW**. This memo uses **$17.6 million/MW-IT** as the mid case and that secondary range as a low/high sensitivity, labeled as such. IT equipment (servers, GPUs, network) is **not** in these capex figures.

**Planning rule for site counts (scenario, not a design):**

1. Year 1 opens **one** 1–2 MW-class edge node, co-located with the first battery, in the metro area where the first homes are.
2. Additional **5 MW edge modules** are added as firm IT load grows, preferably as expansions of existing nodes so homeowners still have a local site they can identify.
3. A **hyperscale campus (50–100+ MW)** is only in view when firm IT is in that band (on this ramp, around years 9–10, or at 1% metro penetration).
4. Modules can be **consolidated** into fewer campuses. “Sites” below are **5 MW-module equivalents**. A single growing campus is also consistent with the energy, but not with “placed within their areas.”

| Stage | IT MW, 30%, PUE 1.54 | Module-equivalent sites | If consolidated |
|---|---:|---|---|
| Year 1 | 0.82 | **1** edge site (1–2 MW class) | 1 small site |
| Year 3 | 5.34 | **1–2** (two 5 MW modules, or one ~5 MW campus) | 1 campus |
| Year 5 | 15.20 | **4** × 5 MW, or one ~15 MW campus | 1 campus |
| Year 10 | 68.59 | **14** × 5 MW, or one ~70 MW hyperscale | 1 hyperscale |
| 1% metro | 106 | **22** × 5 MW, or one ~100 MW campus plus a few edge nodes | 1–2 campuses |
| 5% metro | 530 | **106** × 5 MW, or about **7** × ~80 MW hyperscale campuses | multiple hyperscale |
| 10% metro | 1,060 | **212** × 5 MW, or about **13** × ~80 MW campuses | a regional fleet |

At 33% efficiency, year-10 IT is about **76 MW** and 1% metro is about **117 MW** — the same site-count neighborhood, slightly larger halls.

**Homes per site, 30%:** a 5 MW IT edge module needs about **610 homes** of this package at PUE 1.54 (122 homes × 5). Year 1’s 100 homes are enough energy for a small hall, not a full 5 MW module.

---

## 7. Roughly where on the Front Range

This is a **siting logic**, not a parcel list. No interconnection study was done.

**Homeowner-area nodes** (Denver-Aurora-Centennial MSA, to match “placed within their areas”):

- Denver / Aurora / I-70 warehouse belt — closest to the largest share of MSA homes, and to the **Denver Complex** prisons
- Adams County / north metro / Commerce City — industrial substations
- Jefferson County / west metro
- Douglas County / south metro
- Broomfield / U.S. 36 if volume reaches the north-west cluster

If the program later uses the broader 10-county Front Range (2.07 million units already cited in the shade-system draft): add Boulder / Longmont, Fort Collins / Loveland, Greeley, Colorado Springs, and Pueblo.

**Tension with “prisons first.”** Most Colorado DOC capacity is **not** in the Denver metro. The Denver Complex (Denver Reception and Diagnostic Center and Denver Women’s Correctional Facility) is the in-area prison pair. The large clusters are in **Cañon City**, plus Pueblo, Sterling, Limon, Buena Vista, Delta, Trinidad, Rifle, Arkansas Valley, and the private prisons in Bent and Crowley Counties. A prison-first build that follows those sites will often **not** be “within the homeowner’s area.” Pueblo is the closest large prison campus to the southern Front Range. That geography should be decided before site counts are treated as a map.

---

## 8. Capex ranges (scenario; mid case in bold)

Battery: NREL 2026 4-hour low/mid/high **$255 / $308 / $366 per kWh** (2024$). Data center: **$17.6 million per MW-IT** mid (Cushman & Wakefield, September 3, 2026), low/high sensitivity **$8.9–$23.3 million** from secondary summaries of that guide, **excluding chips and GPUs**. Solar delivered cost is from the payback draft, 30% case, **$725,500** per home, and is shown only for the Think Ahead–owns (Tier 2) model.

Figures below are **30% efficiency, PUE 1.54, 4-hour batteries** unless noted. “Stock” is the cumulative plant at that stage, not a single-year spend.

| Stage | Solar stock (if TA owns) | BESS 4-hour mid (range) | DC mid (range) | Infra mid (BESS 4h + DC) | All-in mid, Tier 2 |
|---|---:|---:|---:|---:|---:|
| Year 1 | $72.5 million | **$1.6M** ($1.3–$1.9M) | **$14.5M** ($7.3–$19.1M) | **$16.0 million** | **$88.6 million** |
| Year 3 | $472 million | **$10.1M** ($8.4–$12.0M) | **$94.0M** ($47.5–$124.4M) | **$104 million** | **$576 million** |
| Year 5 | $1.34 billion | **$28.8M** ($23.9–$34.3M) | **$267M** ($135–$354M) | **$296 million** | **$1.64 billion** |
| Year 10 | $6.06 billion | **$130M** ($108–$155M) | **$1.21B** ($0.61–$1.60B) | **$1.34 billion** | **$7.40 billion** |
| 1% metro | $9.36 billion | **$201M** ($166–$239M) | **$1.87B** ($0.94–$2.47B) | **$2.07 billion** | **$11.4 billion** |
| 5% metro | $46.8 billion | **$1.01B** ($0.83–$1.19B) | **$9.33B** ($4.72–$12.3B) | **$10.3 billion** | **$57.1 billion** |
| 10% metro | $93.6 billion | **$2.01B** ($1.66–$2.39B) | **$18.7B** ($9.43–$24.7B) | **$20.7 billion** | **$114 billion** |

16-hour batteries at the same $/kWh bound would add about **four times** the 4-hour battery capex (year 10 mid about **$521 million** instead of $130 million). A high-efficiency PUE of 1.20 **raises** DC capex, because more IT can be packed onto the same power (year 10 mid DC about **$1.55 billion**).

Per home, 30%, mid, PUE 1.54: data-center shell about **$145,000**, 4-hour battery about **$15,600**, together about **$160,000** of infrastructure on top of the **$725,500** system.

---

## 9. Prison and school absorption

### 9.1 Prisons

The Prison Data Center & Power project, as filed on the box (`/workspace/project-library/books/17-prison-data-center-v1.1-2026-11-18.md` and the October 2026 refine notes), **does not contain a sourced Colorado site list or facility loads**. Those items were recorded as not yet researched and, at one point, waiting on authorization. This section uses only public sources.

**Facility count (cited):** The Colorado Department of Corrections states it has inmates at **21 facilities: 19 state-run and two private** ([CDOC Facilities](https://cdoc.colorado.gov/facilities)). Operating sites named on that page and on individual facility pages include the Cañon City cluster, the Denver Complex, the Pueblo campus, Arkansas Valley, Buena Vista, Delta, Limon, Sterling, Trinidad, Rifle, and the private Bent County and Crowley County prisons. A May 30, 2025 Colorado legislative audit reported **15,986 inmates** in state and private prisons as of March 31, 2025, plus others under DOC jurisdiction in jails or community programs.

**Load (estimate, not a CDOC bill):** No Colorado DOC electricity total was found. Using analogs, the **entire CDOC prison system** is likely on the order of **roughly 5–20 MW average**:

- Santa Rita Jail (Alameda County, 4,000–4,500 inmates) reports a **1.5–2 MW** electric load. Scaled to 15,986 inmates, that intensity is about **5–8 MW**. This is a California jail, not a Colorado prison, and is only an analog.
- A higher electricity intensity in the 8,000–11,000 kWh per inmate per year range would scale to about **15–20 MW**. North Carolina has published about **15,300 kWh per inmate per year of total energy** (not electricity only). PNNL estimated **155.58 kWh/m²/year** of electricity for U.S. correctional buildings from 2012 CBECS microdata, but CDOC floor area was not found, so that intensity is not turned into a Colorado MWh here.

**In-area slice:** The Denver Complex is only two of the 21 facilities. A planning estimate of about **0.5–1.4 MW** average for that complex is a rough scale-down of the same analogs, **not** a measured load. The 10-year table in section 11 uses **1.0 MW (8,760 MWh/year)** as an **in-area prison cap** and notes a statewide 5–20 MW sensitivity. Even the **high** statewide estimate (~20 MW) is only a fraction of year-10 excess (~106 MW) and a small fraction of 1% metro penetration (~163 MW). Prisons can be a **first offtaker**, not the sink for the full program.

### 9.2 Schools, and summer vs the school year

**Counts (cited):** Colorado Department of Education, State Education Snapshot, updated January 2026, school year 2025–26: **179 school districts** (not including the Colorado School for the Deaf and the Blind or the Charter School Institute), **1,877 schools**, and **870,793 students**.

**Electricity intensity (cited):** EIA CBECS 2018, Table C22: U.S. K–12 schools, **9.1 kWh per square foot per year**, **365,000 kWh** and **40,300 square feet** per average K–12 building.

**Statewide kWh (estimate, not a CDE total):** Colorado’s total school floor area was not found. Two labeled estimates:

- If each of the 1,877 schools used the U.S. CBECS average 365,000 kWh, statewide use would be about **688 GWh/year**, or about **79 MW average**. This applies a national average building size to Colorado’s school count.
- Using 120–165 gross square feet per student (a planning range that appears in school-facility discussions, not an official NCES statewide average) times 9.1 kWh/sf times 870,793 students gives about **951–1,308 GWh/year**, or about **109–149 MW average**.

Denver-metro schools are a share of that, not the whole state. A precise metro kWh was not found.

**Summer vs school year.** Jason’s point stands, and it cuts against using schools as the summer sink. K–12 electricity typically falls when school is out (HVAC set back, lights and plugs off, occupancy near zero). Solar output is **highest in summer**. Without a Colorado monthly load-shape study, this memo **does not assign a school MWh in the 10-year revenue table**. Schools remain a **priority offtaker during the school year** and a **possible host for storage or a small hall on idle land**, but they should not be counted on to absorb the summer surplus unless a coincidence study says otherwise. Storage can move power by hours, not by seasons.

---

## 10. Ten-year projection for this line (scenario)

**This is not an adopted P&L.** It is a labeled scenario so the storage and data-center line can be entered into the business-plan projections. Assumptions:

1. Volume follows the section 10.6 **placeholder** ramp. Cumulative homes: 100, 300, 650, 1,150, 1,850, 2,750, 3,850, 5,150, 6,650, 8,350.
2. **100% of homes are on Tier 2** (Think Ahead owns the system and pays the bill). That is the only tier with written arithmetic in section 15. A real mix of Tiers 1–3 is an **open decision**; if homeowners buy the system, Think Ahead’s solar capex and its spread both change (see section 12).
3. Energy is the **30%** case. The 33% case is about 10% more kWh and about 10% more offtake revenue, with a higher system cost ($797,500).
4. **All generated kWh** are booked at the section 15 scenario price of **$0.30** (Think Ahead’s purchase guarantee). This is **not** a current tariff.
5. **Buyer-class split** is an annual-energy upper bound, not an hourly dispatch: in-area prisons are offered power first, up to **8,760 MWh/year** (1.0 MW estimate). Schools are **not assigned MWh** in this table (section 9.2). The remainder is “highest bidder / Think Ahead DC.” Prison and school **contract prices do not exist** in the source material; the $0.30 guarantee is used for every assigned kWh as bookkeeping. A public buyer would typically pay a utility rate or a lower PPA, not double retail. If the statewide CDOC mid-range (~12.5 MW, ~109,500 MWh/year) were electrically reachable, prisons would take more in years 1–4 and less would go to the bidder; they would still be saturated well before year 10.
6. Capex each year is **new homes × ($725,500 + $160,168)** — the delivered system plus mid-case DC shell and 4-hour battery, PUE 1.54. Chips, GPUs, land upgrades, interconnection, and 16-hour batteries are excluded. Battery and data-center **O&M are not subtracted** (only the section 15 PV O&M of $2,993/home is). Panel degradation is not applied.
7. “Net” is operating spread after PV O&M, minus nothing else. **Net cash after capex** is also shown. Compute revenue is **not modeled**; if the 30¢ is only an internal transfer, operating “revenue” is not cash until compute or an outside buyer pays.

### 10.1 Annual table, 30% case, dollars in millions

| Year | New homes | Cum. homes | Sites (5 MW-module equiv.) | Avg MW | IT MW | 4h BESS (MWh) | MWh sold (all output) | Prison MWh | School MWh | Bidder / TA DC MWh | Revenue at 30¢ | Of which prisons | Of which bidder | Bill rebates | Spread | Op. net after PV O&M | New capex | Cum. capex | Cum. op. net | Cum. cash after capex |
|---:|---:|---:|---:|---:|---:|---:|---:|---:|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1 | 100 | 100 | 1 | 1.27 | 0.82 | 5.1 | 11,783 | 8,760 | not modeled | 3,023 | 3.53 | 2.63 | 0.91 | 0.11 | 3.43 | 3.13 | 88.6 | 88.6 | 3.13 | −85.4 |
| 2 | 200 | 300 | 1 | 3.80 | 2.46 | 15.2 | 35,349 | 8,760 | not modeled | 26,589 | 10.60 | 2.63 | 7.98 | 0.32 | 10.29 | 9.39 | 177.1 | 265.7 | 12.52 | −253.2 |
| 3 | 350 | 650 | 2 | 8.22 | 5.34 | 32.9 | 76,590 | 8,760 | not modeled | 67,830 | 22.98 | 2.63 | 20.35 | 0.68 | 22.29 | 20.35 | 310.0 | 575.7 | 32.87 | −542.8 |
| 4 | 500 | 1,150 | 2 | 14.55 | 9.45 | 58.2 | 135,505 | 8,760 | not modeled | 126,745 | 40.65 | 2.63 | 38.02 | 1.21 | 39.44 | 36.00 | 442.8 | 1,018.5 | 68.87 | −949.6 |
| 5 | 700 | 1,850 | 4 | 23.40 | 15.20 | 93.6 | 217,986 | 8,760 | not modeled | 209,226 | 65.40 | 2.63 | 62.77 | 1.94 | 63.45 | 57.91 | 620.0 | 1,638.5 | 126.78 | −1,511.7 |
| 6 | 900 | 2,750 | 5 | 34.79 | 22.59 | 139.2 | 324,033 | 8,760 | not modeled | 315,273 | 97.21 | 2.63 | 94.58 | 2.89 | 94.32 | 86.09 | 797.1 | 2,435.6 | 212.87 | −2,222.7 |
| 7 | 1,100 | 3,850 | 7 | 48.71 | 31.63 | 194.8 | 453,646 | 8,760 | not modeled | 444,886 | 136.09 | 2.63 | 133.47 | 4.05 | 132.05 | 120.52 | 974.2 | 3,409.8 | 333.39 | −3,076.4 |
| 8 | 1,300 | 5,150 | 9 | 65.15 | 42.31 | 260.6 | 606,825 | 8,760 | not modeled | 598,065 | 182.05 | 2.63 | 179.42 | 5.41 | 176.63 | 161.22 | 1,151.4 | 4,561.2 | 494.61 | −4,066.6 |
| 9 | 1,500 | 6,650 | 11 | 84.13 | 54.63 | 336.5 | 783,570 | 8,760 | not modeled | 774,810 | 235.07 | 2.63 | 232.44 | 6.99 | 228.08 | 208.18 | 1,328.5 | 5,889.7 | 702.79 | −5,186.9 |
| 10 | 1,700 | 8,350 | 14 | 105.64 | 68.59 | 422.5 | 983,881 | 8,760 | not modeled | 975,121 | 295.16 | 2.63 | 292.54 | 8.78 | 286.39 | 261.40 | 1,505.6 | 7,395.3 | 964.19 | −6,431.1 |
| **10-yr total** | **8,350** | | | | | | | | | | **1,088.7** | | | **32.4** | **1,056.4** | **964.2** | **7,395.3** | | **964.2** | **−6,431.1** |

Read the last column plainly: under these assumptions the line **does not cash-flow in 10 years**. Simple payback on the spread after PV O&M was already about **23 years** without this infrastructure, and about **28 years** with the mid-case 4-hour battery and data-center shell (section 12), still **before** battery, data-center, and compute operating costs. Insurance commissions from shade-system section 10.6 (about **$4.91 million over 10 years**) are a different line and are not added here.

The in-area prison cap is **already full in year 1**. After that, almost all new MWh go to the guaranteed data-center / highest-bidder bucket. That is why prison revenue stays at about **$2.63 million a year** in this table.

### 10.2 Per-tier homes and revenue

No source states how many homes are on each tier. The program table above is **not** the sum of three tiers. Unit economics, if a given home were on one tier, are in section 12. At year-10 volume, **if** every home were on one tier (illustrative, not a mix):

| If all 8,350 homes were on… | Think Ahead year-10 energy revenue (scenario) | Think Ahead year-10 cash out to homeowners | Think Ahead solar capex stock | Notes |
|---|---|---|---|---|
| Tier 2 — pay the bill | $295 million at 30¢ | $8.78 million of bill rebates | $6.06 billion | Same as the table above |
| Tier 3 — own it, sell back at a **set rate** | Depends on the rate: $295 million at 30¢; $148 million at 15¢; about $11.4 million at 1.16¢ | None, unless a bill rebate is added; the homeowner still has a utility bill | $0 for the panels (the homeowner paid) | Set rate is an open decision |
| Tier 1 — buy now and invest in the data center | Unmodeled (depends on the equity share and on compute profits) | Unmodeled | $0 for the panels if the homeowner paid; homeowner also pays a pro-rata infrastructure stake of about $160,000 mid-case | Compute dividends are a **gap** |

---

## 11. Three product tiers — per-home economics

All dollar figures in this section are **per home, per year** or one-time capex, 30% case unless noted. 33% spread and net are **$37,841** and **$34,548**.

### Tier 2 — “Let us pay your electric bill” (already in section 15)

Think Ahead owns the system, sells (or self-purchases) all output at 30¢, rebates the bill, and keeps the spread.

| | Amount | Source |
|---|---:|---|
| 2× revenue | $35,349/yr | 117,830 kWh × $0.30 |
| Bill paid to the homeowner | $1,051/yr | 7,008 kWh × $0.15 |
| Spread | **$34,298/yr** | section 15 |
| Net after PV O&M | **$31,305/yr** | section 15 |
| System capex | $725,500 | section 15 |
| Payback from the spread | **21.2 years** | section 15 |
| Payback after PV O&M | **23.2 years** | section 15 |
| Plus mid-case DC + 4-hour BESS | +$160,168 capex | calculated in this file |
| Payback after that infra, **same** $31,305 net | **about 28.3 years** | calculated; **O&M understated** (no BESS/DC O&M) |
| Plus mid-case DC + 16-hour BESS | +$206,926; payback **about 29.8 years** | same caveat |

The homeowner pays nothing up front, gets the bill covered, and (separately) the insurance-premium path if that program is real. Section 15 already says this model works as **Think Ahead owning the system**, like a lease, and that it is a bad buy if the homeowner pays the $725,500–$797,500 and only receives the bill rebate.

### Tier 1 — “Buy now and invest in data centers”

The homeowner buys the system **and** a stake in the data center. No ownership percentage was specified. A transparent pro-rata stake, mid-case, is the home’s share of the regional battery and data-center shell:

| | 30%, mid, PUE 1.54 |
|---|---:|
| System (delivered cost, not a marked-up price) | $725,500 |
| Pro-rata 4-hour battery | $15,600 |
| Pro-rata data-center shell (no GPUs) | $145,000 |
| **Total check at closing, delivered** | **about $886,000** |
| If the 35% gross-margin price from the shade draft were applied to the system only | system price would be higher; that markup was written for the $172,500 shade system, not this package |

If the homeowner then received **all** 30¢ revenue ($35,349/year) and still paid their own utility bill, simple payback on $886,000 would be about **25 years** before O&M, or about **27 years** after the $2,993 PV O&M. **Compute dividends, governance of the stake, and who pays interconnection are gaps.** If they only received the bill offset, the buy would not pay back in a system lifetime (same conclusion as section 15, Model 2).

### Tier 3 — “Own your own system and sell it back to us”

The homeowner owns the system (capex **$725,500** delivered, or more if a margin is charged). Think Ahead buys output at a **set rate**. That rate is an **open decision**. It has not been written down. Sensitivity, 30% output, homeowner still pays their own $1,051 bill unless a rebate is added:

| Set buyback rate | Annual payment to the homeowner | Simple payback on $725,500 |
|---|---:|---:|
| 30¢/kWh (the 2× scenario) | $35,349 | **20.5 years** |
| 15¢/kWh (retail energy) | $17,675 | **41.0 years** (same as the earlier all-retail case) |
| 1.16¢/kWh (current Xcel surplus credit, as cited in section 15) | about $1,367 | **about 531 years** |

A mid “green premium” between 1.16¢ and 15¢ was not adopted and is not invented here. If Think Ahead also paid the homeowner’s bill, that would be an extra $1,051/year cost on Think Ahead’s side and would need to be specified.

---

## 12. Carbon-negative claim requirements

Calling the facility **carbon-negative** because it is powered by this solar-and-storage fleet would **not**, today, be a credible claim.

- **Carbon-negative** ordinarily means removing more carbon dioxide from the atmosphere than the operation emits, including residual and embodied emissions. Solar plus batteries plus a data hall do not, by themselves, remove carbon. A credible negative claim would need a **quantified carbon-removal** offtake (or equivalent) that exceeds remaining emissions, with no double counting.
- A more defensible operational claim is **24/7 carbon-free energy matching** on the local grid — hourly, not annual. That is the standard in the UN 24/7 Carbon-Free Energy Compact and in Google’s 24/7 CFE work. Annual renewable energy certificates (RECs) that are not time-matched, not location-matched, or resold, are **not** enough for a 24/7 claim, and they are not a carbon-removal claim at all.
- **Additionality** matters: the generation should be new, and the RECs or energy attribute certificates should be retired once, by the claimant.
- **Firming is required.** The EPRI example above (346 MW of solar for a 100 MW flat load, ~40% hourly match) is the right mental model. Night, winter, and multi-day weather are the hard hours. A 4-hour battery covers an evening; it does not make a 13% capacity-factor solar fleet a 24/7 supply.
- **Account for the rest of the footprint:** PUE (the survey average is 1.54, not 1.0), backup diesel or gas generators, battery manufacturing, construction, and transmission losses. Those have to be in the inventory before any “negative” residual is claimed.
- Until those pieces exist, the accurate statement is: **this is a design that aims to run on additional solar, firmed by storage, with a guaranteed offtake — and a 24/7 or carbon-negative claim is not yet supported.**

---

## 13. Regulatory path (Colorado)

This is a map of issues, not legal advice.

- **On-site third-party PPAs.** C.R.S. § 40-1-103(2)(c) says that supplying electricity or heat from renewable facilities owned by someone other than the consumer does **not** make the owner a public utility **if** the facilities are on property owned or leased by the consumer (or by a master meter operator or another consumer served by that operator). That is the on-site / behind-the-meter path. It does **not** authorize an off-site fleet to retail electricity to prisons, schools, or homeowners at large.
- **Off-site retail sales.** Selling power to prisons and schools as retail customers, across the metro area, would likely make Think Ahead an **electrical corporation / public utility** under C.R.S. § 40-1-103, and would run into **certificated utility service territories**. Colorado is not a general retail-choice state for this purpose. A utility franchise or exclusive-territory conflict is a first-order issue if Think Ahead sells directly to those institutions instead of through the incumbent utility or a lawful on-site PPA at each prison or school.
- **Wholesale vs behind-the-meter.** Energy that rides the grid to a regional battery or data center is not behind-the-meter at the home. Wholesale sales are a different jurisdiction (FERC / organized markets and utility tariffs), and wholesale prices are not 2× retail. Section 15 already notes that Xcel’s proposed large-load Schedule TL is about data centers **paying** incremental costs, not paying rooftop solar 30¢/kWh.
- **Net-metering cap.** Colorado PUC Rule 3664 and Xcel Schedule NM, as summarized in the payback draft, size retail distributed generation to about **120% of site use** and to service-entrance capacity. A 100 kW package on a 7,008 kWh house does not fit that retail DG box. The offtake in this memo has to be a **different legal structure** (wholesale, a special PUC-approved rate, or a direct contract that regulators accept).
- **Interconnection.** Each solar site, battery, and data hall needs an Xcel (Public Service Company of Colorado) or other utility interconnection. Queues can take years. The prison project already flagged this as a high-impact risk. No queue study was done here.
- **“Highest bidders.”** An auction can be a **wholesale** sale or a bilateral PPA. It is not a way around the franchise issue if the buyers are retail end-use customers in someone else’s territory.
- **The 30¢ guarantee.** Getting 27–30¢/kWh, as section 15 already stated, would take a direct contract with a storage or data-center buyer who will actually pay it, or a new rate approved by the Colorado Public Utilities Commission. That contract is the piece the whole revenue table hangs on.

---

## 14. Open gaps

- No adopted start date for “year 1.”
- No sourced prison site shortlist or CDOC kWh in the prison project or in this memo.
- No Colorado-measured school kWh, and no summer/school-year coincidence study, so school MWh is not in the 10-year table.
- No contracted offtake price; 30¢ is a scenario.
- No Tier 1 equity share, and no compute-revenue model, so the purchase guarantee may be only an internal transfer.
- No Tier 3 set buyback rate.
- No adopted mix of the three tiers.
- No interconnection, land, or water study for any node.
- Battery and data-center O&M, GPU/IT capex, cost of capital, taxes, and panel degradation are not in the net.
- Homeowner “see where my power goes” product design is not specified.
- The carbon-negative claim is not yet supportable (section 12).

---

## 15. Sources

1. Think Ahead, `business-plan/solar-shade-system.md`, section 10.6 (placeholder install ramp) and section 9 (Front Range housing units from Colorado State Demography Office Vintage 2024).
2. Think Ahead, `business-plan/whole-home-solar-payback.md`, sections 6–7 and 15 (output, use, costs, 2×-retail spread, AHIC / 1.16¢ note, Rule 3664).
3. Prison Data Center & Power project book, v1.1, November 18, 2026, and October 2026 refine notes under `/workspace/stored-history/projects/prison-data-center-power/` (no site list, no loads).
4. Colorado Department of Corrections, [Facilities](https://cdoc.colorado.gov/facilities), 21 facilities (19 state-run, two private).
5. Colorado Office of the State Auditor / legislative evaluation of CDOC budgeting practices, May 30, 2025, inmate count as of March 31, 2025.
6. Colorado Department of Education, [State Education Snapshot](https://www.cde.state.co.us/schoolview/explore/statesnapshot/), updated January 2026, 2025–26 counts.
7. U.S. EIA, CBECS 2018, [Table C22](https://www.eia.gov/consumption/commercial/data/2018/ce/pdf/c22.pdf) (K–12 electricity intensity and typical building size).
8. PNNL-32747, *Distributed Wind Development Potential at United States Correctional Facilities* (2012 CBECS-based electricity intensity of 155.58 kWh/m²/year).
9. Alameda County GSA, Santa Rita Jail energy page (1.5–2 MW load at 4,000–4,500 inmates).
10. Cole et al., NREL, *Cost Projections for Utility-Scale Battery Storage: 2025 Update* (2026 4-hour overnight capital costs, 2024$).
11. Cushman & Wakefield, [2026 Data Center Development Cost Guide press release](https://ir.cushmanwakefield.com/news/press-release-details/2026/Cushman--Wakefield-Releases-2026-Data-Center-Development-Cost-Guide-Citing-21-Rise-in-Per-MW-Construction-Costs/default.aspx), September 3, 2026 ($17.6 million/MW average, excluding chips and GPUs).
12. Uptime Institute, Global Data Center Survey 2025 (weighted average PUE 1.54).
13. EPRI work on 24/7 carbon-free energy procurement (346 MW solar / 100 MW load hourly-match example).
14. U.N. 24/7 Carbon-Free Energy Compact / Google 24/7 CFE materials (hourly, local matching; annual RECs are not sufficient for that claim).
15. C.R.S. § 40-1-103, especially (2)(c) (on-site renewable supply exemption from public-utility regulation).
16. U.S. Census Bureau, ACS 2020–2024, Denver-Aurora-Centennial MSA housing units, 1,290,063, as compiled in public MSA profiles.

*End of draft. Prepared November 25, 2026, America/Denver, as a labeled sizing scenario for the Think Ahead project book.*
