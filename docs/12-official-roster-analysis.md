# 12 — The Official Roster: 261 Startups, Analysed and Reconciled

**Source:** `YFYI_Startups_Performance_Analysis(Startups).csv`, supplied 19 August 2026.
**Cleaned machine-readable copy:** [`data/official-roster-2026.csv`](data/official-roster-2026.csv)
(261 rows, UTF-8, comma-delimited, with a derived `first_batch_year` column).

This file supersedes the reconstructed alumni list in `05-alumni-graduates.md` and the
status flags in `10-startup-status.md` wherever the two disagree. It is the first
**complete, status-labelled roster** of the program in this dossier.

---

## 1. What the file contains

| Column | Notes |
|---|---|
| `startup_name` | Often encodes renames as `Old - New` (e.g. `Ddosify - Anteon`) |
| `yfyi_batch` | Cohort year(s); two startups appear in two batches |
| `status` | **Active / Out of Business / Exit** — the program's own labelling |
| `funding_usd` | Disclosed funding; populated for 41 of 261 |
| `verticals` | Multi-value sector tags |
| `description` · `website` · `corporated` · `headquarter` · `founder_team` | |
| `award` | YFYİ award(s) won; populated for 123 of 261 |
| `grant_amount_try` | Cash grant in TL; populated for 71 of 261 |

**Coverage:** batches **2005 through 2024**. The 2025 cohort is absent, so the ten YFYİ25
teams documented in `03-editions.md` are not in this file.

---

## 2. Headline numbers

| Metric | Value |
|---|---|
| Startups on the roster | **261** |
| 🟢 Active | **112 (43%)** |
| 🔵 Exit | **6 (2%)** |
| 🔴 Out of Business | **143 (55%)** |
| Still alive (Active + Exit) | **118 (45%)** |
| Disclosed funding raised | **$45,084,080** across 41 startups |
| Cash grants paid by the program | **5,140,500 TL** across 71 startups |
| Startups with a recorded award | 123 (47%) |
| Incorporated ("Corporated" = TRUE) | 20 |

**The 261 figure exceeds the "230+ startups" claim on yfyi.com** — the marketing number is
conservative, not inflated. That is worth noting given how many other program statistics
do not reconcile (see `09-data-gaps.md` §2).

---

## 3. Survival by cohort

| Batch | N | Active | Exit | Out of Business | Alive % |
|---|---:|---:|---:|---:|---:|
| 2005 | 2 | 2 | 0 | 0 | 100% |
| 2006 | 5 | 1 | 0 | 4 | 20% |
| 2007 | 3 | 0 | 0 | 3 | **0%** |
| 2008 | 4 | 0 | 0 | 4 | **0%** |
| 2009 | 7 | 0 | 0 | 7 | **0%** |
| 2010 | 7 | 1 | 0 | 6 | 14% |
| 2011 | 8 | 2 | 0 | 6 | 25% |
| 2012 | 9 | 1 | 0 | 8 | 11% |
| 2013 | 14 | 3 | 2 | 9 | 36% |
| 2014 | 9 | 1 | 0 | 8 | 11% |
| 2015 | 10 | 1 | 1 | 8 | 20% |
| 2016 | 15 | 4 | 1 | 10 | 33% |
| 2017 | 24 | 13 | 1 | 10 | **58%** |
| 2018 | 23 | 7 | 0 | 16 | 30% |
| 2019 | 30 | 15 | 1 | 14 | **53%** |
| 2020 | 20 | 8 | 0 | 12 | 40% |
| 2021 | 9 | 7 | 0 | 2 | **78%** |
| 2022 | 20 | 10 | 0 | 10 | 50% |
| 2023 | 18 | 13 | 0 | 5 | **72%** |
| 2024 | 24 | 23 | 0 | 1 | **96%** |
| **Total** | **261** | **112** | **6** | **143** | **45%** |

**Read this curve carefully.** The apparent improvement after 2017 is mostly **age, not
quality** — a 2024 startup has had eight months to fail, a 2009 startup has had seventeen
years. The genuinely informative comparison is between cohorts of similar vintage:
**2013 (36%) and 2016 (33%) and 2017 (58%) versus 2011 (25%), 2012 (11%) and 2014 (11%)**.
On that basis 2017 stands out as the strongest mature cohort — which is exactly the year
of the UC Berkeley pre-accelerator plus Draper University plus Growth Circuit investment
pipeline described in `02-history-and-model.md`. That is the single best available
evidence that the 2017 program design worked.

The 2007–2009 cohorts have a **0% survival rate across 14 startups**. Those were the pure
"student business-idea competition" years, when the prize was a staged cash payment and
little else.

---

## 4. The six exits

The dossier previously reported one exit. There are six.

| Startup | Batch | Funding raised | Sector | Notes |
|---|---|---|---|---|
| **Onedio** | 2013 | **$4,550,000** | Content, News | HQ ODTÜ TEKNOKENT. Founders Kaan Kayabalı, Türkü Oktay, Demirhan Büyüközcü. |
| **Inofab Health** | 2015 | **$3,421,280** | Deeptech, Healthtech | HQ ODTÜ TEKNOKENT. Founders Merthan Öztürk, Kerem Yaşar. `inofab.health` |
| **Udentify** | 2016 | $236,000 | Retailtech, image processing, deeptech, AI | Founder Can Dörtkardeşler. Now `remvisionlab.com` |
| **Alictus** | 2013 | — | Gaming | Founders Emre Taş, Ecem Baran, Onur Dilek. Acquired into SciPlay. |
| **Tuvis** | 2019 | — | Smart manufacturing, Industry 4.0, AI | Founders Bahadır Gölcük, Batuhan Şahin, Eyüp Görkem Bayram. `tuvisai.com` |
| **Drive Buddy** | 2017 | — | Autotech | Founders Emre Yiğit Alparslan, Eşref Öztürk. `drivebuddyapp.com` |

### The Onedio finding

**Onedio is a YFYİ alumnus.** It went through the 2013 batch, was headquartered at ODTÜ
TEKNOKENT, raised $4.55M — and then became one of the program's most consistent sponsors,
funding the *Onedio Reklam Desteği Özel Ödülü* (advertising-support special award, up to
50,000 TL in value) from 2016 through at least 2022. That is the clearest single instance
of the program's flywheel: participant → exit → recurring funder of the next cohorts.

It joins **V-Count** (2005), **ISSD** (2010), **Btech** (2015) and **VLMedia** (2006) as
alumni that came back as sponsors.

### Every exit is award-free

All six exits are in the **"no award recorded"** group. Not one of them won a YFYİ prize.

---

## 5. Awards did not predict survival — now quantified

| Group | N | Active | Exit | Out of Business | Alive % |
|---|---:|---:|---:|---:|---:|
| **Won a YFYİ award** | 123 | 49 | 0 | 74 | **40%** |
| **Won no award** | 138 | 63 | 6 | 69 | **50%** |

Startups that won a YFYİ award were **less** likely to still be operating than those that
did not, and **none** of the six exits came from the award-winning group. The earlier
qualitative observation in `REPORT.md` — that five Elginkan Grand Prize winners are dormant
while the best-funded alumni were not prize-winners — now has a population-level number
behind it.

Two caveats before drawing conclusions. First, awards concentrate in the earlier cohorts,
which are older and therefore more likely to have died — some of this gap is vintage, not
selection. Second, 123 vs 138 on a 10-point difference is suggestive, not conclusive. But
the direction is clear and it is the opposite of what a prize-driven program would predict.

---

## 6. Money

### Funding raised by alumni — $45.08M disclosed across 41 startups

| Rank | Startup | Batch | Raised | Status |
|---:|---|---|---:|---|
| 1 | **Büyütech** | 2012 | $7,149,295 | Active |
| 2 | **V-Count** | 2005 | $4,596,987 | Active |
| 3 | **Onedio** | 2013 | $4,550,000 | Exit |
| 4 | **Evreka** | 2017 | $4,545,126 | Active |
| 5 | **Mikro Biyosistemler → Cellsway** | 2017 | $4,110,000 | Active |
| 6 | **Inofab Health** | 2015 | $3,421,280 | Exit |
| 7 | **Mobilus → Invidyo** | 2005 | $2,930,000 | Active |
| 8 | **Gauss İstatistik Ar-Ge → Enhencer** | 2017 | $1,890,000 | Active |
| 9 | **Kuartis → KuartisMed** | 2011 | $1,800,000 | Active |
| 10 | **Ddosify → Anteon** | 2021 | $1,480,000 | Active |
| 11 | **Magfi** | 2020 | $1,150,000 | Active |
| 12 | **Düğün Buketi** | 2023 | $1,142,795 | Active |
| 13 | Deplike | 2016 | $835,662 | Active |
| 14 | Mavilab (Cybellelaser) | 2017 | $800,000 | Active |
| 15 | Blok-Z | 2018 | $725,000 | Active |
| 16 | Otsimo | 2016 | $641,180 | Active |
| 17 | Akıllı Fon → Magnus | 2019 | $502,000 | Active |
| 18 | B-PREG | 2018 | $300,000 | Active |
| 19 | Udentify | 2016 | $236,000 | Exit |
| 20 | Melo App | 2023 | $229,689 | Active |

Concentration is extreme: **the top 6 startups account for $28.4M — 63% of all disclosed
funding.** Only 41 of 261 alumni (16%) have any disclosed funding at all.

### Grants paid out by the program — 5,140,500 TL across 71 startups

| Batch | Grants (TL) | | Batch | Grants (TL) |
|---|---:|---|---|---:|
| 2006 | 60,000 | | 2016 | 173,000 |
| 2007 | 60,000 | | 2017 | 100,000 |
| 2008 | 125,000 | | 2018 | 352,500 |
| 2009 | 155,000 | | 2019 | 95,000 |
| 2010 | 210,000 | | 2020 | 100,000 |
| 2011 | 185,000 | | 2021 | 175,000 |
| 2012 | 370,000 | | 2022 | 100,000 |
| 2013 | 125,000 | | 2023 | 600,000 |
| 2014 | 550,000 | | 2024 | **1,505,000** |
| 2015 | 100,000 | | | |

**2024 alone accounts for 29% of all grant money ever paid.** After a decade of roughly
flat nominal grants (100,000–350,000 TL a year, 2015–2022), the program stepped up sharply
in 2023–2024. In real terms this is at least partly catch-up for Turkish inflation — the
flagship prize had been nominally frozen at 100,000 TL since 2012 (`09-data-gaps.md` §11) —
but the 2024 total is a genuine increase even after deflating.

Note the ratio: the program has paid out **~5.1M TL in grants** and its alumni have raised
**$45M**. On a rough historical average that is a leverage of well over 10×.

---

## 7. Sectors

| Vertical | Count | | Vertical | Count |
|---|---:|---|---|---:|
| Healthtech | 35 | | Biotech | 12 |
| Artificial intelligence (+ "AI") | 34 | | Military | 10 |
| Deeptech | 20 | | Edtech | 9 |
| Sustainability | 19 | | Industry 4.0 | 8 |
| Climatetech | 19 | | AR / VR | 8 |
| SaaS | 17 | | Digital transformation | 7 |
| Energy | 12 | | Smart city | 7 |
| Internet of Things | 12 | | Image processing | 7 |

**Healthtech is the single largest vertical across 21 years**, confirming the qualitative
read in `05-alumni-graduates.md`. The climate/sustainability pair (38 combined) is heavily
concentrated in 2021–2024 — a clear recent shift in what the program attracts.

### Headquarters

144 of 261 rows have no HQ recorded. Of those that do: **ODTÜ TEKNOKENT 42**, Ankara 22,
İstanbul 11, OSTİM Teknopark 3, Teknopark İzmir (İYTE) 3, Hacettepe Teknokent 3, Ege
Teknopark 3, Teknopark Ankara 3, Ankara Teknokent 2, Bilkent Cyberpark 2. The program is
Ankara-anchored but does place graduates into other technoparks.

---

## 8. Reconciliation with `10-startup-status.md`

I matched my 173-row status file against the official roster by normalised name.

| Outcome | Count |
|---|---:|
| Matched to an official record | 115 of 173 |
| **My flag agrees with official status** | **56** |
| **My flag conflicts with official status** | **14** |
| My UNVERIFIED entries now resolved | **45** |
| No official match (mostly 2025 cohort, absent from the file) | 58 |
| **On the official roster but absent from my list** | **150** |

### The 14 conflicts — and what they teach

**I called it dead, the program says it is alive** (6 cases):
GEEN · Buyan · Areytech · EN/IO · Porion · HyperCrops

Every one of these I flagged PASSIVE on domain evidence — parked, for sale, or no site.
This is precisely the failure mode I warned about in `10-startup-status.md`: **a dead
domain is not a dead company.** Turkish deep-tech and B2B suppliers frequently operate
with no web presence at all. Six false negatives out of 41 PASSIVE calls is a ~15% error
rate on that flag.

**I called it alive, the program says it is out of business** (5 cases):
SciRobot · Hidrotürbin · Trendoline · Bionova · Distant

These I flagged ACTIVE on a live domain or an existing LinkedIn page. **A page that still
resolves is not a company that still trades.** Abandoned sites and dormant LinkedIn pages
persist for years.

**I called it a pivot, the program says it is out of business** (3 cases):
İndisera · Seyisco · Lonca

I read the current content at `indisera.com`, `seyis.co` and `lonca.co` as pivots by the
original teams. The official status says otherwise, which most likely means those domains
were re-registered by unrelated businesses. **These three should be removed from the
CHANGED list.** That reduces my verified pivot/rename count from 11 to 8 — and the official
file independently confirms the remaining ones (see below).

### What the official file confirms

The roster encodes renames directly in the `startup_name` field, and it corroborates
findings I reached independently:

- `Ddosify - Anteon` ✅
- `Akıllı Fon - Robo Advisor - Magnus` ✅
- `Mobilus - Invidyo` ✅
- `Gauss İstatistik Ar-Ge - ENHENCER` — **and this resolves something I had wrong.**
  I treated Gauss (2017 cohort, flagged PASSIVE because `gaussdata.com` is for sale) and
  Enhencer ("2017 orbit", flagged ACTIVE, $1.7M raised) as two separate companies. They are
  one company. Enhencer *is* the YFYİ 2017 Gauss team.
- `Tulpar Arge - Buyan - Burkut` — **Buyan and Burkut are the same entity**, Tulpar Arge,
  status Active. I had them as two separate startups, one PASSIVE and one ACTIVE.
- `Mikro Biyosistemler - Cellsway` — a rename I had missed.
- `Triwi - Rokka` — a rename I had missed.
- `SFM Software - Inovarium`, `DijiFi - Para Mandalı`, `Powder Tech - Ultimate Powders`,
  `Deeblab - Turtela`, `Grid Intelligence - Reengen - Faradai`, `Ankabeta - Parxlab.co`,
  `Microtherm - Microsolar`, `Kuartis - KuartisMed`, `Wmedya - Ondestek`,
  `Sleepi - Talassa` — all previously undocumented here.

### Gap #8 in `09-data-gaps.md` is now closed

That gap questioned whether **VLMedia** was genuinely a YFYİ graduate or merely an ODTÜ
TEKNOKENT ecosystem company listed under the "YFYİ Mezunu İş Ortakları" heading. The
roster settles it: **VLMedia, batch 2006, status Active.** It is a real alumnus — and one
of only two survivors from the entire 2005–2009 era.

---

## 9. The 150 startups this dossier never had

Reconstructing cohorts from press coverage recovered roughly 40% of the real roster. The
missing 150 break down as **63 Active, 4 Exit, 83 Out of Business**. The most significant
omissions, all Active or Exit:

**Pre-2015:** VLMedia (2006) · Kuartis → KuartisMed (2011) · Esetron (2011) ·
Büyütech (2012) · Onedio (2013, Exit) · Grid Intelligence → Reengen → **Faradai** (2013) ·
BeeVision (2013) · Inofab Health (2015, Exit)

**2016–2017:** Udentify (2016, Exit) · Limatek Sistem · Cubicl · **Evreka** ·
Drive Buddy (Exit) · Mavilab (Cybellelaser) · Kuantek · Eyesoft · Akıllı BES ·
DijiFi → Para Mandalı · Meetinghand

**2018–2020:** InfraDynamics · CY Enerji · **Qubitro** · Test Robotic · Alp Imaging ·
Prosoft VR · Pinterrail · Bakiyem

**2021–2022:** Digigammon · ChemCode · CERVOS · **AlgBio** · Integva · Packard ·
SoilBiom · Nilbio Engineering · BixByte · Kybele's Garden · İyileştir

**2023:** Düğün Buketi · Melo App · CareMed · M-Based · Spacelis · Hyperactive Games ·
Nutshell Education Technologies · FRESHDATA Technologies · Fitcheck · Clair

**2024:** Agentscope AI · ADIM · APPITECH · Black Paw · EGN Power · EntoCeres ·
Kurtuluş Deprem Simülasyonu · Sinapps · Proses Design · Raw Banana · RemotechLabs ·
Umigame · Unibio · Virtue24

Several are notable Turkish companies in their own right — **Faradai** (energy AI),
**Evreka** (waste-management SaaS), **Büyütech** (imaging/autotech, the single
best-funded alumnus), **Qubitro** (IoT infrastructure) and **AlgBio** (algae biotech).

---

## 10. What changes elsewhere in this dossier

| Document | Correction required |
|---|---|
| `REPORT.md` | "The only clean exit in 21 years" → **six exits**. Alumni total 150 → **261**. Add the 45% survival rate and the $45.08M funding figure. |
| `05-alumni-graduates.md` | Add Onedio, Büyütech, Evreka, Faradai, Kuartis, Udentify and the other 144 missing names. Reclassify Inofab Health as an **exit**. |
| `10-startup-status.md` | Apply the 14 conflict corrections; merge Gauss/Enhencer and Buyan/Burkut into single entities; drop İndisera, Seyisco and Lonca from CHANGED. |
| `09-data-gaps.md` §8 | **Closed** — VLMedia confirmed as a 2006 alumnus. |
| `09-data-gaps.md` §9 | **Largely closed** — a complete 2005–2024 roster now exists. Only the 2025 cohort remains outside it. |
| `09-data-gaps.md` §10 | **Closed** — outcome data now exists for all 261 startups. |
| `06-partners-sponsors-prizes.md` | Note that Onedio and VLMedia, listed as sponsors, are themselves alumni. |

---

## 11. Limitations of this file

1. **No 2025 cohort.** The ten YFYİ25 teams are absent. Anything about the current batch
   still rests on the sources in `03-editions.md`.
2. **Character encoding damage in the source.** The supplied CSV had already lost the
   Turkish characters `ı ş ğ İ` (they arrive as `?`) before it reached me — `ü ö ç Ü Ö Ç`
   survived. I repaired 55 fields where the correct string was unambiguous (place names,
   organisation names, and company names verified elsewhere in this dossier) and left the
   rest verbatim rather than guess. **208 fields still contain `?` characters.** A clean
   re-export from the original source would fix this.
3. **`status` is a point-in-time label with no date.** There is no "as of" field, so it is
   unclear whether a startup marked Out of Business closed last year or a decade ago.
4. **`funding_usd` is disclosed funding only**, populated for 41 of 261. Absence of a
   figure does not mean a startup raised nothing.
5. **No methodology is stated** for how Active/Out of Business was determined. Where it
   conflicts with my domain-and-press evidence, I have deferred to this file as the
   program's own record — but for the 14 conflicts in §8, both readings are documented so
   you can judge.
6. **`headquarter` is 55% blank** and `corporated` is TRUE for only 20 rows, which looks
   under-populated rather than genuinely meaning 241 unincorporated startups.
