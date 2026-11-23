# Think Ahead — Whole-Home Solar Payback at 30% and 33% Module Efficiency

**Date:** November 23, 2026 (America/Denver)  
**Document type:** Business-plan section (research draft)  
**Companion to:** `business-plan/solar-shade-system.md` (rates, net-metering rules, and the insurance path are reused from that draft so the two sections stay consistent). This file does not replace the shade-system pricing section.  
**Market:** Denver / Front Range, Colorado.

**How to read this draft.** Every dollar figure and every kilowatt-hour is either taken from a cited source or labeled as an **estimate**. A whole-home package that covers the roof, facade screens, a garage roll-out, a gazebo, and a carport with 30–33% cells is not a catalog product in November 2026, so installed cost, packing factor, snow-melt draw, and life are planning estimates until there is an engineered bill of materials. This is not a customer quote, an interconnection study, or a licensed engineering opinion. Main payback counts **electricity savings only**. Insurance is a separate line at the end.

---

## 1. Pricing and payback summary

Planning case: a typical Think Ahead home with a **2,000 sq ft, 45° A-frame roof** plus the four add-on arrays described in section 2. Nameplate uses the requested formula \(kW = area_{m^2} \times 1\,kW/m^2 \times efficiency\), which assumes the entire area is active cell area (see section 3). Production uses Denver PVWatts-style specific yields adjusted for tilt and orientation (section 4). Snow-melt pulses are subtracted from roof output only (section 5). There is **no federal residential tax credit** for a 2026 install (IRC section 25D ended after December 31, 2025).

| Item | 30% efficiency | 33% efficiency |
|---|---:|---:|
| Total active area | 3,600 sq ft (334.45 m²) | same |
| Nameplate | **100.34 kW** | **110.37 kW** |
| Annual AC output, net of snow-melt pulses, estimate | **117,830 kWh** | **129,640 kWh** |
| Delivered cost, base (estimate) | **$725,500** | **$797,500** |
| Delivered cost, low–high (estimate) | $470,500 – $1,146,300 | $517,100 – $1,258,900 |
| Annual energy savings, all kWh at $0.15/kWh | $17,675 | $19,446 |
| Annual energy savings, all kWh at 13.71¢/kWh | $16,155 | $17,774 |
| Simple payback, base cost, all kWh at $0.15 | **41.0 years** | **41.0 years** |
| Simple payback, base cost, all kWh at 13.71¢ | **44.9 years** | **44.9 years** |
| Annual energy savings, use capped at 9,000 kWh, leftover at 1.16¢ AHIC, $0.15 / 13.71¢ | $2,612 / $2,496 | $2,749 / $2,633 |
| Simple payback, base cost, 9,000 kWh cap, $0.15 / 13.71¢ | **278 / 291 years** | **290 / 303 years** |
| Break-even year if the $5,511 insurance path is layered on, all kWh at $0.15 / 13.71¢ | **35 / 38 years** | **36 / 38 years** |
| Break-even year if that insurance path is layered on, 9,000 kWh cap, $0.15 / 13.71¢ | **120 / 122 years** | **128 / 131 years** |

Headline takeaways:

- **Electricity alone does not pay this package back inside a 25- or 30-year solar life**, even in the generous case that every kilowatt-hour is valued at retail. At the base cost, simple payback is about **41 years** at the $0.15/kWh baseline and about **45 years** at the 13.71¢ all-in off-peak figure used in the shade-system section. Raising cell efficiency from 30% to 33% barely changes payback in years, because cost in these tables is also scaled with nameplate at the same dollars-per-watt.
- **The all-retail case is not how Xcel Colorado net metering works for a system this large.** A typical Denver / Xcel household uses about 7,000 kWh/year (584 kWh/month, EIA 2025, as compiled for Xcel Colorado). The brief’s 8,000–10,000 kWh band is a slightly higher planning range. This package produces about **12 to 18 times** that much energy. Under 4 CCR 723-3-3664, a net-metered system must be sized to supply **no more than 120% of average annual consumption** and must not exceed **service entrance capacity**. Year-end leftovers, if any, cash out at AHIC (about **1.16¢/kWh** in a 2025 secondary figure, not a verified 2026 tariff number). When only household use is credited at retail and the rest is paid at 1.16¢, annual cash savings fall to about **$2,400–$2,900**, and simple payback stretches to **roughly 260–320 years** at the base cost. In practice the utility may not interconnect the full nameplate under Schedule NM at all.
- **A standard 200 A, 240 V service is about 48 kW of entrance capacity.** The 100–110 kW package exceeds that limit in 4 CCR 723-3-3664(a)(II) unless the service is upgraded. Even a 400 A service would be tight.
- **30–33% modules are mostly not for sale as certified residential products in November 2026.** The closest commercial tandems are in the mid-to-high 20s, with 2027 shipment targets and roadmaps to 29–30% later in the decade (section 3). Cost ranges below are therefore analogs from today’s silicon and building-integrated products, applied to the higher nameplate, and should be read as estimates.
- **Insurance is not in the main payback.** If the program’s 10%/year premium path from the cited $5,511 Colorado average is added on top, all-retail break-even moves into the mid-to-late 30s. With consumption capped, break-even stays well beyond 100 years. Jason’s path to about $1,100 (which, from a 10% schedule, implies a $3,155 starting premium, not $5,511) is smaller: about $13,055 of 10-year savings and about $43,900 over 25 years, versus $22,805 and $76,647 on the $5,511 path.

The only component that approaches a conventional solar payback on energy alone, and only if its output can actually be used at retail, is the **front carport** (about 15–17 years at the base $3.62/W). The gazebo is next (about 22–24 years). The roof, screens, and garage roll-out do not pay back on electricity inside 25 years at the base costs used here.

---

## 2. Typical home and area assumptions

Areas are planning assumptions for a single detached Front Range house, stated so they can be replaced with a measured takeoff. They are chosen to stay consistent with the 2,000 sq ft A-frame used in the shade-system section and with ordinary residential sizes for a two-car garage, a backyard gazebo, and a two-car carport.

| Component | Assumed area | Reasoning |
|---|---|---|
| 1. Total solar roof with snow-melt pulses | **2,000 sq ft** (185.81 m²), two 1,000 sq ft planes | Same midpoint of the 1,500–2,500 sq ft range used in `solar-shade-system.md`. Treated here as a **building-integrated solar roof**, not as the retractable shade fabric in that section. Planning pitch is **12/12 (45°)**, a common A-frame / steep gable. Ridge assumed **east–west**, so one plane faces south and one faces north. Plan/footprint is about 2,000 × cos(45°) ≈ **1,414 sq ft**. |
| 2. Solar shade screens to grade | **800 sq ft** (74.32 m²): 400 sq ft south + 400 sq ft west | Near-vertical facade screens, not a second copy of the roof. For a house with an east–west ridge and roughly 40 ft eaves, a 10 ft drop from eave to grade is **400 sq ft per long wall**. The planning case puts collecting fabric on the **south and west** (sunny) facades and does **not** electrify a north wall, which would add cost for very little yield. A different eave height or a three-side wrap would change the area. |
| 3. Garage-ceiling roll-out above the door | **256 sq ft** (23.78 m²): 16 ft × 16 ft | A standard two-car garage door is **16 ft wide**. A 16 ft projection covers about one stall length of apron in front of the door, which is what a ceiling-mounted roll-out above the door can reasonably shade. Assumed to deploy to a shallow drain slope of about **10°**, facing **south** in the planning case (see orientation risk below). |
| 4. Backyard gazebo | **144 sq ft** (13.38 m²): 12 ft × 12 ft | 12 × 12 is a common residential gazebo. Low-pitch roof, about **10°**, planned as unshaded and able to face reasonably south. A 10 × 10 (100 sq ft) or 14 × 14 (196 sq ft) would scale nameplate almost linearly. |
| 5. Front carport | **400 sq ft** (37.16 m²): 20 ft × 20 ft | A two-car canopy “out front.” 18–24 ft wide by 18–22 ft deep is the usual residential band; 20 × 20 is the midpoint. Planned as a purpose-built solar carport at **15° south**, not a flat patio cover. |

**Total collecting area:** **3,600 sq ft** (334.45 m²).

**Orientation risk.** If the street elevation is a gable end, the garage and front carport face east or west, not south, and their specific yield falls toward the east/west figures in section 4 (roughly 15–25% lower than a south plane at the same tilt). The tables use the favorable south-facing planning case and would need to be rerun for a specific lot.

These five pieces are **additive**. They are not the same 12 kW retractable shade system priced in the companion section. A house that already has that shade system on the roof should not also count a full 2,000 sq ft of fixed solar roof on the same planes without an explicit design decision.

---

## 3. Nameplate at 30% and 33%, and whether those cells can be bought

Formula used, as requested: \(kW = area_{m^2} \times 1\,kW/m^2 \times efficiency\). One sun (1,000 W/m²) times efficiency times area is the STC nameplate if every square meter is active cell. Real modules have frames, gaps, and sometimes inactive field tiles, so packing is often about 80–95%. The figures below are therefore an **upper bound on watts for a given area**. A 90% packing factor would cut every kW and kWh number in this draft by about 10%; cost would fall with them only if the job is priced per watt, not per square foot of roof or structure.

| Component | Area (m²) | kW at 30% | kW at 33% |
|---|---:|---:|---:|
| Solar roof | 185.81 | 55.74 | 61.32 |
| Shade screens | 74.32 | 22.30 | 24.53 |
| Garage roll-out | 23.78 | 7.13 | 7.85 |
| Gazebo | 13.38 | 4.01 | 4.41 |
| Carport | 37.16 | 11.15 | 12.26 |
| **Total** | **334.45** | **100.34** | **110.37** |

**Commercial availability in November 2026 (not a 30–33% residential catalog product):**

- Sirius PV’s HybridTandem residential module, using Caelux perovskite glass, is rated **525 W** in the same footprint as the company’s existing **450 W** silicon module — about **16.7% more power**, or roughly the mid-20% efficiency range if the 450 W board is a typical ~22% residential module. As of November 19, 2026, Sirius was still in remaining testing and certification and was pointing to customer availability in the near term, with EPIC-compatible frames in limited quantity in the first half of 2027 ([pv magazine](https://www.pv-magazine.com/2026/11/19/sirius-pv-unveils-525-w-perovskite-tandem-residential-modules-debuts-ironridge-partnership/), November 19, 2026).
- Heliene and Caelux announced commercial-scale tandem production in Minnesota, with modules at **27% or greater**, a **29% target by 2028**, and **commercial shipment in 2027**. Caelux has said greater-than-30% tandem configurations are a **2028–2029** roadmap item, not a 2026 residential SKU ([pv magazine](https://www.pv-magazine.com/2026/11/13/heliene-announces-commercial-production-of-perovskite-tandem-modules-using-caelux-glass/), November 13, 2026).
- Tandem PV reported a **30.4%** perovskite/silicon **demonstration module** (100 cm² class) in June 2026; that is a lab/demo result, not a widely sold residential panel ([pv magazine](https://www.pv-magazine.com/2026/06/01/tandem-pv-announces-30-4-efficient-perovskite-silicon-demonstration-module/), June 1, 2026).
- Oxford PV has discussed tandem commercialization and lifetime targets; it does not publish a public residential list price in the sources reviewed for this draft.

**Cost implication.** There is no verified public dollars-per-watt asking price for a certified 30–33% residential module in November 2026. An assumed **$0.08/W** tandem premium has appeared in at least one consulting write-up; that is a model assumption, not a vendor quote, and is **not** used as a line item here. The installed-cost ranges in section 7 are taken from today’s silicon rooftop, solar-roof, awning, pergola, and carport analogs and then applied to the 30% and 33% nameplates. That is conservative in one direction (more watts at the same $/W raise the total) and optimistic in another (it assumes those efficiencies can be bought and warranted at those analog prices). A later factory quote should replace this.

---

## 4. Denver specific yield (PVWatts-style), by tilt and orientation

NREL PVWatts v8 is the calculator behind the companion section’s **1,635 kWh/kW-year** figure for Denver at latitude tilt, south, 14% system losses. The same default losses and a fixed open-rack array are used here.

**South-facing, by tilt** — NREL PVWatts v8, 1 kW, azimuth 180°, 14% losses, typical-year weather, as compiled November 3, 2026 ([kratopower](https://kratopower.com/blogs/news/best-angle-for-solar-panels)):

| Tilt | Annual kWh per kW (Denver, south) | Used for |
|---:|---:|---|
| 0° (flat) | 1,377 | Reference |
| 15° | 1,562 | Front carport (designed solar tilt) |
| 25° | 1,626 | Matches Open Sun’s downtown Denver PVWatts run, November 5, 2026 |
| 35° (near best in that run) | 1,643 | Reference |
| 40° | 1,634 | Close to the companion section’s 1,635 at latitude tilt |
| **45°** | **1,615** | South roof plane |
| 90° (vertical) | **1,105** | South facade screens |

**Other orientations.** Open Sun ran PVWatts v8 for downtown Denver on November 5, 2026, at a 25° tilt, and published a pitch-adjustment table from PVGIS (same date). Those 25° PVWatts results were: south 1,626, east 1,346, west 1,286, north 930 kWh/kW-year. At 12/12 (45°), the PVGIS factors relative to the same direction at 25° are south 102%, east 95%, west 91%, north 65% ([Open Sun Denver report](https://opensun.io/guides/denver-roof-solar-report), November 2026).

Applied in this draft:

| Surface | Specific yield used (kWh/kW-year) | Basis |
|---|---:|---|
| Roof, south 45° | **1,615** | Direct PVWatts v8 (kratopower) |
| Roof, north 45° | **605** | **Estimate:** Open Sun PVWatts 25° north (930) × PVGIS 45°/25° factor (65%) ≈ 605. Not a direct PVWatts 45° north run. |
| Roof, blended (50/50) | **1,110** | Mean of 1,615 and 605, equal plane areas |
| Screens, south vertical | **1,105** | Direct PVWatts v8 (kratopower) |
| Screens, west vertical | **874** | **Estimate:** 1,105 × Open Sun’s 25° west/south ratio (1,286 / 1,626). A direct PVWatts 90° west run was not obtained. |
| Screens, blended (50/50) | **990** | Mean of 1,105 and 874 |
| Garage roll-out, 10° south | **1,500** | **Estimate:** interpolation between PVWatts south 0° (1,377) and 15° (1,562) |
| Gazebo, ~10° south | **1,500** | Same interpolation. A true 15° south gazebo would use 1,562 (~4% more). |
| Carport, 15° south | **1,562** | Direct PVWatts v8 (kratopower) |

No extra shade, soiling beyond PVWatts’ 14% default, snow-cover loss (except the pulse credit in section 5), or availability haircut is applied. Retractable screens and the garage roll-out will produce nothing while stowed for hail or wind; that downtime is **not** in these kWh figures and would lower them. The companion shade-system draft used a 5–25% availability haircut for a moving roof; a similar factor could be applied later once a duty cycle exists.

---

## 5. Snow-melt pulses as a parasitic load

The roof is specified with **snow-melt pulses**, not a continuously heated roof. Two very different energy budgets apply. Only the pulse case is subtracted in the main tables.

**Base case — interfacial pulses (used in the kWh tables).** Lab work on pulsed Joule heating for PV glass shows that melting a thin interfacial layer, then letting gravity and wind shed the rest, can clear snow at under **10 J/cm²** per pulse, versus more than 30 J/cm² and much longer run times for bulk heating (University of Illinois Urbana-Champaign / CAS collaborators, *Advanced Functional Materials*, 2022; [pv magazine](https://www.pv-magazine.com/2022/05/17/pulsed-joule-heating-tech-to-remove-snow-frost-ice-from-solar-modules/), May 17, 2022; [CAS summary](https://english.cas.cn/newsroom/news--archives/2022/research-news/202207/t20220704_1125412.shtml), July 4, 2022). Ten J/cm² is **0.0278 kWh/m²**. On 185.81 m² of roof that is **5.16 kWh per full-roof pulse**.

Denver’s 1991–2020 climate normal (Stapleton) is **49.0 inches** of snow per year, **31.4 days** with at least 0.1 inch, and **15.9 days** with at least 1 inch ([Current Results](https://www.currentresults.com/Weather/Colorado/Places/denver-snowfall-totals-snow-accumulation-averages.php), from NOAA monthly/annual summaries). Combining those counts is an **estimate**, not a measured pulse log:

| Pulse schedule, estimate | Pulses / year | Parasitic use |
|---|---:|---:|
| One pulse on each ≥0.1 inch day | 31.4 | 162 kWh |
| Two pulses on each ≥1 inch day, plus one on the lighter days | 47.3 | 244 kWh |
| Two pulses on every snow day | 62.8 | 324 kWh |

**The main tables subtract 250 kWh/year** from roof output (the middle of that band, rounded). That is about 0.4% of roof production and is negligible for payback. This technology is **lab-scale** in the cited papers; it is not a priced residential roof product, and a real controller could use more or less energy.

**Sensitivity — melting the entire snow mass in place (not used in the main tables).** Melting 49 inches of snow, if the snow-to-water ratio is about 10:1 (a typical dry Front Range rule of thumb, **not** a NOAA annual SWE normal — that official equivalent was not found for this draft), is about 4.9 inches of water, or 25.5 lb/sq ft. Latent heat of fusion is 144 BTU/lb; raising snow about 12°F at 0.51 BTU/lb-°F adds a little more (physics as summarized by [Tesmar](https://www.tesmar.com/html/snowmelt_design.html)). That is about **2,240 kWh/year** on 2,000 sq ft before environmental losses. With a 1.5–2.0× loss factor (heat to air and to the roof deck, **estimate**), use would be about **3,400–4,500 kWh/year**, or roughly 6–7% of roof output at 30%. A steep A-frame will often shed snow once the bond is broken, so full-mass melting is the pessimistic end, not the design intent of “pulses.”

Electric snow-melt mats sized like a driveway (about 50 W/sq ft in a [WarmlyYours Denver](https://www.warmlyyours.com/en-US/posts/Outdoor-Heating-System-Keeps-Ice-and-Snow-from-Denver-Driveway-2915) example, page updated February 25, 2026) would be a much larger parasitic load if run for hours per storm, and are not assumed here.

---

## 6. Annual kilowatt-hours

Gross AC energy = nameplate × specific yield from section 4. Net roof energy subtracts the 250 kWh pulse load. Other components have no snow-melt deduction in this draft (the gazebo and carport could be given a small winter-shedding credit or load later).

| Component | Yield (kWh/kW-year) | kWh at 30%, net | kWh at 33%, net |
|---|---:|---:|---:|
| Solar roof | 1,110 | 61,620 | 67,810 |
| Shade screens | 990 | 22,070 | 24,280 |
| Garage roll-out | 1,500 | 10,700 | 11,770 |
| Gazebo | 1,500 | 6,020 | 6,620 |
| Carport | 1,562 | 17,410 | 19,160 |
| **Total, net** | — | **117,830** | **129,640** |

Rounded to the nearest 10 kWh. Unrounded totals are 117,833 and 129,642 kWh.

For context, that is about **12–18 times** a typical Denver / Xcel household’s annual use (section 8).

---

## 7. Installed cost estimates

No federal ITC is applied. Colorado conventional rooftop solar averaged **$2.64/W** installed as of November 13, 2026, or $30,076 for an 11.4 kW system ([EnergySage](https://www.energysage.com/local-data/solar-panel-cost/co/)). A total solar roof, retractable screens, and site-built canopies cost more per watt than that rooftop average. Figures below are **planning ranges from comparable products**, then applied to the 30% and 33% nameplates at the same dollars-per-watt. Totals are rounded to the nearest $100 in the summary; component tables use whole dollars.

**Roof (building-integrated solar roof + pulse hardware).** Tesla stopped taking new Solar Roof orders in August 2026 (Electrek, as reported in later 2026 recaps). Recent observed installed costs, while the product was still being interconnected, are the best BIPV analog found: New York-area projects about **$5.70/W** in 2025 (NY-Sun compilation cited in a Dobbs Ferry, NY application letter); California owner-built Solar Roofs, no battery, median **$8.51/W** over 2024–2026 and **$11.12/W** in 2025 (CPUC DG Stats through August 31, 2026, analyzed by [Cali Energy](https://cali-energy.com/blog/tesla-solar-roof-vs-solar-panels-california)). Those $/W figures were for systems of roughly 10–12 kW on a full roof, so they already embed a lot of inactive or roofing-only area. Spreading a similar roofing job over 55–61 kW of active 30–33% area should lower dollars-per-watt; using $5.70–$11.12/W on the full nameplate is therefore a **high** way to read those comps, and is kept as a conservative envelope. **Base: $8.00/W** (estimate, inside that observed band). Pulse-system hardware has no commercial price; **$6,000** is a placeholder ($3/sq ft) in the base case, with **$4,000** low and **$20,000** high (the high end is in the neighborhood of whole-roof electric snow-melt at about $10/sq ft, the per-square-foot figure WarmlyYours quoted for a Denver driveway system).

**Shade screens and garage roll-out.** Retractable solar awning analogs in the companion section run about **$3.35–$14.48/W** of fabric (Solar Markise and similar finished cassettes, 2026 retail, before a whole-roof install). Base for the facade screens: **$7.00/W** (estimate, above the cheapest patio cassette and below the companion draft’s $9.34/W delivered cost for a tilting dual-plane roof). Base for the smaller garage cassette: **$8.00/W** (estimate, a small-system premium). Low and high use $3.35 and $14.48.

**Gazebo.** Turnkey solar patio covers / pergolas have been quoted at about **$3.75–$4.75/W** ([WattBuild](https://www.wattbuild.com/learn/about/94/solar-panel-patio-cover), updated February 26, 2026) and, in a higher Southern California planning range, **$4.00–$7.50+/W** ([Team All Star](https://www.teamallstarconstruction.com/solar-patio-covers/solar-pergola-cost/)). **Base: $5.00/W.** Low $3.75, high $7.50.

**Carport.** EnergySage Marketplace, first half of 2026, published July 9, 2026: residential solar carports about **$3.62/W**, or about $18,100 for a 5 kW one-car example and $34,998 for the 9.7 kW average ([EnergySage](https://www.energysage.com/solar/alternatives-to-rooftop-solar/what-is-a-solar-panel-carport/)). A broader 2026 compilation of published figures is about **$3.15–$4.50/W** (for example [HyreSolar](https://hyresolar.com/cost/solar-carport/), retrieved October 2026). **Base: $3.62/W.** Low $3.15, high $4.50.

| Component | $/W low–base–high | Cost at 30%, low / base / high | Cost at 33%, low / base / high |
|---|---|---:|---:|
| Solar roof (incl. pulse hardware) | $5.70 / $8.00 / $11.12, plus $4k / $6k / $20k | $321,700 / **$451,900** / $639,800 | $353,500 / **$496,500** / $701,800 |
| Shade screens | $3.35 / $7.00 / $14.48 | $74,700 / **$156,100** / $322,900 | $82,200 / **$171,700** / $355,100 |
| Garage roll-out | $3.35 / $8.00 / $14.48 | $23,900 / **$57,100** / $103,300 | $26,300 / **$62,800** / $113,600 |
| Gazebo | $3.75 / $5.00 / $7.50 | $15,100 / **$20,100** / $30,100 | $16,600 / **$22,100** / $33,100 |
| Carport | $3.15 / $3.62 / $4.50 | $35,100 / **$40,400** / $50,200 | $38,600 / **$44,400** / $55,200 |
| **Total, estimate** | — | **$470,500 / $725,500 / $1,146,300** | **$517,100 / $797,500 / $1,258,900** |

These are not factory bills of materials. Electrical service upgrades, trenching, structural engineering, a PE stamp (Denver Policy DRC R329 at 10 kW and above), and interconnection studies for a 100 kW-class system are only partly inside the analog $/W figures and could add more on a real lot.

---

## 8. What a kilowatt-hour is worth, and the consumption cap

Rates are reused from `solar-shade-system.md` so the two drafts stay consistent.

- **Jason’s baseline:** **$0.15/kWh.** Close to Xcel Colorado’s 2025 EIA average all-in residential price of **15.90¢/kWh** ([WattCosts](https://wattcosts.com/electricity-rates/colorado/denver/), from EIA Form 861, verified October 23, 2026 in that compilation).
- **Companion-section all-in off-peak figure:** **13.71¢/kWh.** Season-weighted Xcel Colorado off-peak all-in (8/12 × 12.72¢ winter off-peak + 4/12 × 14.50¢ summer off-peak = 13.31¢) × 1.03 Denver franchise fee. Solar without a battery produces almost entirely in off-peak (daylight) hours, and Schedule NM credits off-peak exports only against off-peak use. The $7.10 monthly service and facility charge is not offset.
- **Year-end avoided-cost rate:** about **1.16¢/kWh** AHIC, a 2025 secondary figure also used in the companion draft and **not independently verified** from Xcel’s official 2025 or 2026 tariff. Xcel’s Solar Bank Election Form (17-9178, rev. 02-24) last published official AHIC values through 2023, when the rate was 1.529¢ (2022 was 2.672¢). Treat year-end cash as **far below retail**.

**Household use.** Xcel Energy Colorado’s average residential consumption in the 2025 EIA data is **584 kWh/month**, or **7,008 kWh/year** (same WattCosts compilation). Statewide Colorado use is somewhat higher in other 2024–2025 summaries (on the order of 8,000 kWh/year). The brief asks for a cap at a typical Denver home of **8,000–10,000 kWh/year**; this draft uses **9,000 kWh** as the midpoint of that band and also shows 7,008, 8,000, and 10,000.

**Net-metering limits (this is the binding constraint).** 4 CCR 723-3-3664(a) requires that retail renewable distributed generation be sized to supply **no more than 120% of the customer’s average annual electricity consumption** at the site, and that rated capacity **not exceed service entrance capacity**. On Schedule NM, excess kWh bank month to month and credit 1:1 against retail use **in the same TOU period**; within 60 days after year-end, leftovers cash out at AHIC unless the customer has elected rollover (Xcel Schedule NM; Colorado PUC Rule 3664). For a 7,008–10,000 kWh household, 120% is only **8,410–12,000 kWh/year** of eligible production — an order of magnitude below the 118,000–130,000 kWh this package would make. A 100 kW nameplate also exceeds a typical 200 A service entrance.

Two bookkeeping views are shown below, as requested:

1. **All kWh at retail** — every produced kilowatt-hour valued at $0.15 or 13.71¢. This is a ceiling, not a tariff outcome for this system size.
2. **Consumption-capped** — kilowatt-hours up to annual household use valued at retail; the remainder valued at 1.16¢ AHIC. This still assumes the full array is allowed to interconnect and that leftover energy is purchased at AHIC. If the system is instead limited to 120% of use, the retail-only savings would be even lower (see the notes under the tables).

No degradation and no rate inflation are in the base tables, consistent with the companion section (a 0.5%/year degradation and 2–3% rate inflation would be a normal later sensitivity).

---

## 9. Annual dollar savings and simple payback (electricity only)

Simple payback = delivered cost ÷ first-year energy savings. At 0% APR this is also the year the 0% loan would be repaid if 100% of those savings were applied to principal. Life of today’s silicon modules is commonly 25–30 years; high-efficiency tandems do not yet have a comparable field-proven residential warranty at 30–33%.

### 9.1 All kilowatt-hours valued at retail

| | 30% efficiency | 33% efficiency |
|---|---:|---:|
| Net annual kWh | 117,830 | 129,640 |
| Savings at $0.15/kWh | **$17,675** | **$19,446** |
| Savings at 13.71¢/kWh | **$16,155** | **$17,774** |
| Payback at base cost, $0.15 | **41.0 years** | **41.0 years** |
| Payback at base cost, 13.71¢ | **44.9 years** | **44.9 years** |
| Payback at low cost, $0.15 / 13.71¢ | 26.6 / 29.1 years | 26.6 / 29.1 years |
| Payback at high cost, $0.15 / 13.71¢ | 64.9 / 71.0 years | 64.7 / 70.8 years |

### 9.2 Consumption capped, leftover at 1.16¢/kWh

| Use cap | Rate on the capped kWh | 30%: annual savings | 30%: payback at base cost | 33%: annual savings | 33%: payback at base cost |
|---|---|---:|---:|---:|---:|
| 7,008 kWh (Xcel CO average) | $0.15 | $2,337 | 310 years | $2,474 | 322 years |
| 7,008 kWh | 13.71¢ | $2,246 | 323 years | $2,383 | 335 years |
| 8,000 kWh | $0.15 | $2,474 | 293 years | $2,611 | 305 years |
| 8,000 kWh | 13.71¢ | $2,371 | 306 years | $2,508 | 318 years |
| **9,000 kWh (mid of 8–10k)** | **$0.15** | **$2,612** | **278 years** | **$2,749** | **290 years** |
| **9,000 kWh** | **13.71¢** | **$2,496** | **291 years** | **$2,633** | **303 years** |
| 10,000 kWh | $0.15 | $2,751 | 264 years | $2,888 | 276 years |
| 10,000 kWh | 13.71¢ | $2,622 | 277 years | $2,759 | 289 years |

If the array were not allowed to export anything above the 120% cap, and leftover production were worth $0 rather than AHIC, first-year retail savings at $0.15 would be only $1,261–$1,800 depending on the use figure (120% of 7,008–10,000 kWh), and payback at the base cost would be about **400–630 years**. That is the stricter reading of Rule 3664.

**Why 33% does not shorten payback here.** Cost is scaled with watts at a constant $/W, and energy also scales with watts, except for the small fixed snow-melt load and the fixed $6,000 pulse-hardware placeholder. Payback in years is therefore almost the same at 30% and at 33%. A real 33% module would only beat 30% on payback if it cost less than 10% more (the ratio of the two efficiencies), or if the job were priced mostly by area (roofing, posts, motors) rather than by watt.

---

## 10. Per-component table (base cost, electricity only)

Figures at the **base** delivered cost. Component paybacks value that component’s own kWh at retail; they do not allocate the household’s limited retail cap among devices. In a capped-bill world the first kilowatt-hours are worth 13.71–15¢ and the rest are worth about 1.16¢, so adding a fifth array to a house that is already export-capped is worth very little on the electric bill.

### 30% efficiency

| Component | Area | kW | Net kWh/year | Base cost (est.) | $ / year at $0.15 | $ / year at 13.71¢ | Payback at $0.15 | Payback at 13.71¢ |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Solar roof | 2,000 sq ft | 55.74 | 61,620 | $451,900 | $9,244 | $8,449 | 48.9 years | 53.5 years |
| Shade screens | 800 sq ft | 22.30 | 22,070 | $156,100 | $3,311 | $3,026 | 47.1 years | 51.6 years |
| Garage roll-out | 256 sq ft | 7.13 | 10,700 | $57,100 | $1,605 | $1,467 | 35.6 years | 38.9 years |
| Gazebo | 144 sq ft | 4.01 | 6,020 | $20,100 | $903 | $825 | 22.2 years | 24.3 years |
| Carport | 400 sq ft | 11.15 | 17,410 | $40,400 | $2,612 | $2,387 | 15.5 years | 16.9 years |
| **Total** | **3,600 sq ft** | **100.34** | **117,830** | **$725,500** | **$17,675** | **$16,155** | **41.0 years** | **44.9 years** |

### 33% efficiency

| Component | Area | kW | Net kWh/year | Base cost (est.) | $ / year at $0.15 | $ / year at 13.71¢ | Payback at $0.15 | Payback at 13.71¢ |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| Solar roof | 2,000 sq ft | 61.32 | 67,810 | $496,500 | $10,172 | $9,297 | 48.8 years | 53.4 years |
| Shade screens | 800 sq ft | 24.53 | 24,280 | $171,700 | $3,642 | $3,329 | 47.1 years | 51.6 years |
| Garage roll-out | 256 sq ft | 7.85 | 11,770 | $62,800 | $1,766 | $1,614 | 35.6 years | 38.9 years |
| Gazebo | 144 sq ft | 4.41 | 6,620 | $22,100 | $993 | $908 | 22.2 years | 24.3 years |
| Carport | 400 sq ft | 12.26 | 19,160 | $44,400 | $2,873 | $2,626 | 15.5 years | 16.9 years |
| **Total** | **3,600 sq ft** | **110.37** | **129,640** | **$797,500** | **$19,446** | **$17,774** | **41.0 years** | **44.9 years** |

The carport is the only piece whose energy-only payback at the cited EnergySage 2026 $/W lands inside a typical 25-year module life, and only in the all-retail bookkeeping. Once the roof and screens have already more than filled the 8,000–10,000 kWh household cap, additional carport or gazebo kilowatt-hours are worth about 1.16¢, and those component paybacks stretch to well over 100 years if they are last in line.

---

## 11. Separate line: break-even if the premium reduction is layered on

This section is **not** part of the electricity-only payback. It adds avoided homeowners-insurance premium, using the same paths as the companion section, and asks in which year cumulative energy savings plus cumulative premium savings first exceed the base delivered cost. The 10%/year schedule is a **program target**, not a current filed Colorado credit. Think Ahead cannot require the customer to buy its policy as a condition of the loan (C.R.S. sections 10-3-1105 and 10-2-602).

**Path A — arithmetic from the cited 2026 average.** Start at **$5,511** (Insurance.com, September 17, 2026, Quadrant Information Services). Premium falls 10% per year for 10 years, then holds at about **$1,922**. Savings are measured against a constant $5,511 baseline:

| Year | Program premium | Annual savings vs $5,511 | Cumulative savings |
|---:|---:|---:|---:|
| 1 | $4,960 | $551 | $551 |
| 2 | $4,464 | $1,047 | $1,598 |
| 3 | $4,018 | $1,493 | $3,092 |
| 4 | $3,616 | $1,895 | $4,987 |
| 5 | $3,254 | $2,257 | $7,244 |
| 6 | $2,929 | $2,582 | $9,826 |
| 7 | $2,636 | $2,875 | $12,701 |
| 8 | $2,372 | $3,139 | $15,840 |
| 9 | $2,135 | $3,376 | $19,216 |
| 10 | **$1,922** | $3,589 | **$22,805** |
| 11–25, each year | $1,922 | $3,589 | **25-year total $76,647** |

**Path B — Jason’s “down to about $1,100” target.** A 10%/year schedule reaches $1,100 in year 10 only if the starting premium is about **$3,155** ($1,100 / 0.9¹⁰). Cumulative savings versus a constant $3,155 baseline are about **$13,055 over 10 years** and about **$43,900 over 25 years** (year-10 and later annual savings about $2,055). Starting at $5,511 and landing at $1,100 would require a steeper-than-10% path, which is not modeled as a third official case here.

Break-even year at the **base delivered cost** (first year that cumulative energy + insurance savings exceed cost):

| Energy bookkeeping | Insurance path | 30% efficiency | 33% efficiency |
|---|---|---:|---:|
| All kWh at $0.15 | A ($5,511 → $1,922) | **Year 35** | **Year 36** |
| All kWh at 13.71¢ | A | **Year 38** | **Year 38** |
| All kWh at $0.15 | B ($3,155 → $1,100) | **Year 38** | **Year 38** |
| All kWh at 13.71¢ | B | **Year 41** | **Year 41** |
| 9,000 kWh cap, leftover at 1.16¢, $0.15 | A | **Year 120** | **Year 128** |
| 9,000 kWh cap, leftover at 1.16¢, 13.71¢ | A | **Year 122** | **Year 131** |
| 9,000 kWh cap, leftover at 1.16¢, $0.15 | B | **Year 158** | **Year 168** |
| 9,000 kWh cap, leftover at 1.16¢, 13.71¢ | B | **Year 162** | **Year 172** |

Over a 25-year horizon, Path A’s $76,647 of premium savings is real money, but it does not close the gap on a $725,500–$797,500 system if most of the kilowatt-hours are only worth AHIC. At the 9,000 kWh cap and $0.15, 25-year energy plus Path A insurance is only about **$142,000** at 30% efficiency, a shortfall of about **$584,000** against the base cost.

---

## 12. Planning implications

- **Size to the bill, not to every surface.** A system sized at 120% of 7,000–10,000 kWh, on a south 45° plane at 1,615 kWh/kW-year, is only about **5.2–7.4 kW**. At Colorado’s November 2026 rooftop average of $2.64/W, that is about $13,700–$19,600, with an energy-only simple payback of roughly **13–14 years** at 13.71¢ on the consumed kilowatt-hours plus 1.16¢ on the 20% surplus. That is a conventional rooftop outcome, not this five-piece package.
- **The extra area is a hail-and-architecture product, not an electricity product.** Once household use is covered, more roof, screens, a gazebo, and a carport still have insurance, comfort, and design value, but they should not be underwritten as if Xcel will pay 13.71–15¢ for the surplus.
- **If the program wants electricity-only payback under 20 years on a whole-home package,** either delivered cost has to fall dramatically (into a range where structure and motors are paid for by something other than the kWh), or most of the area must be hail-only fabric / canopy without full 30–33% nameplate priced in, or a different offtake than Schedule NM has to exist (a battery to shift into on-peak, a non-NM export contract, or neighborhood aggregation). None of those is assumed here.
- **Service entrance and interconnection have to be designed early.** Rule 3664 and a 200 A panel are hard stops for a 100 kW nameplate, independent of the payback math.

---

## 13. Sources

1. NREL, [PVWatts Calculator](https://pvwatts.nrel.gov/), version 8. Denver south-facing tilt table: [kratopower, November 3, 2026](https://kratopower.com/blogs/news/best-angle-for-solar-panels). Latitude-tilt Denver figure of 1,635 kWh/kW-year and 5.74 kWh/m²/day, as compiled from PVWatts: [SolarSizer](https://solar-sizer.com/peak-sun-hours-by-city.html), October 10, 2026. Orientation at 25° and pitch factors: [Open Sun Denver report](https://opensun.io/guides/denver-roof-solar-report), November 2026 (PVWatts v8 and PVGIS runs, November 5, 2026).
2. IRS and Public Law 119-21: Residential Clean Energy Credit (section 25D) is not available for expenditures made after December 31, 2025; an expenditure is made when original installation is completed (IRS FAQ FS-2025-05, August 21, 2025).
3. EnergySage, [Colorado solar panel cost](https://www.energysage.com/local-data/solar-panel-cost/co/), updated November 13, 2026: $2.64/W, $30,076 for 11.4 kW. EnergySage, [solar carports](https://www.energysage.com/solar/alternatives-to-rooftop-solar/what-is-a-solar-panel-carport/), updated July 9, 2026: $3.62/W (Marketplace, first half of 2026).
4. Cali Energy, [Tesla Solar Roof vs solar panels in California](https://cali-energy.com/blog/tesla-solar-roof-vs-solar-panels-california), using CPUC DG Stats through August 31, 2026: median $8.51/W (2024–2026, no battery), $11.12/W in 2025; Tesla stopped Solar Roof orders in August 2026 (Electrek). NY-Sun area Solar Roof average about $5.70/W in 2025, as cited in a Dobbs Ferry, NY historic-board letter compiling that program’s data.
5. WattBuild, [solar panel patio cover](https://www.wattbuild.com/learn/about/94/solar-panel-patio-cover), updated February 26, 2026: $3.75–$4.75/W turnkey. Team All Star, [solar pergola cost](https://www.teamallstarconstruction.com/solar-patio-covers/solar-pergola-cost/): $4.00–$7.50+/W planning range (Southern California). HyreSolar, [solar carport cost](https://hyresolar.com/cost/solar-carport/): $3.15–$4.50/W compiled range, retrieved October 2026.
6. Retractable solar awning retail comps of about $3.35–$14.48/W: `business-plan/solar-shade-system.md`, section 3, from 2026 listings including the Solar Markise family ([pv magazine](https://www.pv-magazine.com/2026/07/14/german-startup-offers-solar-awnings/), July 14, 2026).
7. Tandem availability: [pv magazine, November 19, 2026](https://www.pv-magazine.com/2026/11/19/sirius-pv-unveils-525-w-perovskite-tandem-residential-modules-debuts-ironridge-partnership/) (Sirius / Caelux 525 W HybridTandem); [pv magazine, November 13, 2026](https://www.pv-magazine.com/2026/11/13/heliene-announces-commercial-production-of-perovskite-tandem-modules-using-caelux-glass/) (Heliene 27%+, shipment 2027, 29% by 2028, >30% roadmap 2028–29); [pv magazine, June 1, 2026](https://www.pv-magazine.com/2026/06/01/tandem-pv-announces-30-4-efficient-perovskite-silicon-demonstration-module/) (Tandem PV 30.4% demonstration module).
8. Pulsed snow removal: Khodakarami et al., *Advanced Functional Materials* (2022), as reported by [pv magazine, May 17, 2022](https://www.pv-magazine.com/2022/05/17/pulsed-joule-heating-tech-to-remove-snow-frost-ice-from-solar-modules/) and [Chinese Academy of Sciences, July 4, 2022](https://english.cas.cn/newsroom/news--archives/2022/research-news/202207/t20220704_1125412.shtml) (<10 J/cm² per pulse). Bulk-melt physics: [Tesmar snow-melt design notes](https://www.tesmar.com/html/snowmelt_design.html). Denver snowfall normals: [Current Results](https://www.currentresults.com/Weather/Colorado/Places/denver-snowfall-totals-snow-accumulation-averages.php), 1991–2020, 49.0 inches, 31.4 days ≥0.1 inch, 15.9 days ≥1 inch (NOAA / NCEI underlying). Driveway snow-melt analog: [WarmlyYours, Denver, updated February 25, 2026](https://www.warmlyyours.com/en-US/posts/Outdoor-Heating-System-Keeps-Ice-and-Snow-from-Denver-Driveway-2915).
9. Xcel Colorado rates and Schedule NM: companion draft section 5, from the PUC No. 8 tariff as compiled by GreenCalculus (reviewed November 2026, tariff served November 15, 2026) and [US Net Metering, Xcel Energy](https://usnetmetering.com/utilities/xcel-energy/) (rules checked November 16, 2026). AHIC secondary 2025 figure of about 1.16¢; official series through 2023 on Xcel form 17-9178, as quoted by [Colorado Solar Quotes, October 3, 2026](https://coloradosolarquotes.com/2026/10/03/xcel-excess-solar-credits-colorado/).
10. 4 CCR 723-3-3664, [Net Metering](https://www.law.cornell.edu/regulations/colorado/4-CCR-723-3-3664): 120% of average annual consumption and service-entrance-capacity limits.
11. Xcel Colorado average use and EIA average price: [WattCosts Denver](https://wattcosts.com/electricity-rates/colorado/denver/), 584 kWh/month and 15.90¢/kWh from EIA Form 861, 2025 annual data.
12. Insurance.com, [Best and cheapest homeowners insurance in Colorado for 2026](https://www.insurance.com/home-and-renters-insurance/homeowners-insurance-in-colorado/), updated September 17, 2026: statewide average **$5,511**. Premium path arithmetic is identical to `solar-shade-system.md`, section 9.3.

---

## 14. Open items

1. A site-specific PVWatts or SAM run for the north 45° plane and for a west-facing vertical facade, to replace the hybrid estimates in section 4.
2. Official Xcel **2025 and 2026 AHIC** from the tariff or a company posting.
3. An interconnection pre-application: whether Public Service Company of Colorado would allow any part of a 100 kW-class residential package under Schedule NM, and what service-entrance upgrade would be required.
4. A factory or installer bid for 30–33% (or the nearest available tandem) modules, packing factor, warranties, and a snow-pulse BOM. Until then, every total in section 7 is an analog estimate.
5. A measured stow / hail-duty cycle for the screens and garage roll-out, so production can be haircut for time not deployed.
6. Lot-specific orientation for the front garage and carport, which may not face south.

---

*End of draft. Prepared November 23, 2026, America/Denver, for the Think Ahead project book. Electricity-only payback is the main result; insurance is a separate overlay in section 11.*
