# 10 — Alumni Status Tracker: Where Every YFYİ Startup Is Now

**Verification date:** 19 August 2026
**Method:** live-domain probing with parked/for-sale detection, LinkedIn company-page
resolution, and targeted search across startup databases (Tracxn, Crunchbase, PitchBook,
CB Insights), Turkish tech press and company sites. Full method notes at the bottom.

> ⚠️ **Superseded in part.** The program's own roster (261 startups, 2005–2024, with
> official Active / Exit / Out of Business labels) is analysed in
> [`12-official-roster-analysis.md`](12-official-roster-analysis.md). Where that file and
> this one disagree, **the official file wins**. 56 of the flags below agree with it,
> **14 conflict** (listed in §8 of the roster analysis), and 150 official startups are
> absent here. Known corrections: Gauss and Enhencer are one company; Buyan and Burkut are
> one company (Tulpar Arge); İndisera, Seyisco and Lonca should be dropped from CHANGED;
> Inofab Health is an **exit**, not merely active. The method notes at the bottom of this
> file remain valid and explain most of the 14 conflicts.

---

## Flag definitions

| Flag | Meaning |
|---|---|
| 🟢 **ACTIVE** | Positive evidence of current operation — live product site, recent funding, current corporate presence, or recent press. |
| 🟡 **CHANGED** | Still exists but is materially different: acquired, rebranded, pivoted, or relocated. The original YFYİ entity is no longer what it was. |
| 🔴 **PASSIVE** | Positive evidence of dormancy — domain parked, for sale, empty, "coming soon", or abandoned with no trace of activity since the program year. |
| ⚪ **UNVERIFIED** | No public signal either way. Concentrated in the 2005–2014 cohorts (predating startup databases) and the 2024–25 cohorts (too new to have a footprint). Not a judgement — an absence of evidence. |

**Coverage:** 173 startups listed after the gap-search addendum. **97 (56%) carry a
determinate flag** (ACTIVE / CHANGED / PASSIVE); **76 (44%) are UNVERIFIED**. The newly
surfaced 2006, 2013 and 2024 names were added conservatively as UNVERIFIED unless prior
status evidence already existed.

---

## Summary

| Flag | Count | Share |
|---|---:|---:|
| 🟢 ACTIVE | 45 | 26% |
| 🟡 CHANGED | 11 | 6% |
| 🔴 PASSIVE | 41 | 24% |
| ⚪ UNVERIFIED | 76 | 44% |
| **Total** | **173** | |

Of the 97 startups where a determination was possible, **58% are still going in some form**
(ACTIVE or CHANGED) and **42% are dormant**. That survival rate is respectable for
early-stage cohorts — but note the survivorship bias: startups that die also stop leaving
traces, so some of the UNVERIFIED bucket is almost certainly dead.

The authoritative per-startup table is [`data/startup-status.csv`](data/startup-status.csv)
(173 rows, one per startup, with the evidence and evidence type for each call). The
narrative below groups the same data for reading. Note that Nanovatif and Invidyo appear in
the ACTIVE narrative below but are counted once each in the CSV under their CHANGED parent
entries (Isıteks and Mobilus respectively).

---

## 🟡 CHANGED — the eleven that became something else

These are the most interesting outcomes in the dataset.

### 1. Alictus → **SciPlay Games Turkey** *(cohort 2013)*
**Acquired.** `alictus.com` now redirects to `sciplaygamesturkey.com`, which states
outright: *"ALICTUS IS NOW SCIPLAY GAMES TURKEY."* LinkedIn (15,839 followers) reads
*"Formerly Alictus, we are now SciPlay, the leading developer and publisher of
free-to-play mobile games."* This is the clearest exit in YFYİ's history — a 2013 idea-stage
team acquired into a NASDAQ-listed games group (SciPlay / Light & Wonder).

### 2. Ddosify → **Anteon** *(cohort 2021, Elginkan Grand Prize co-winner)*
**Rebranded and pivoted.** Now "Anteon (formerly Ddosify)" — an open-source, eBPF-based
Kubernetes monitoring *and* performance-testing platform, having started as pure load
testing. Incorporated in Delaware, Seed VC stage, 7K+ GitHub stars on the open-source
engine, Red Hat certified container. Co-founder & CTO Fatih Baltacı. The Ddosify name
survives as the "Load Engine" component inside Anteon.

### 3. Akıllıfon → **Magnus** *(cohort 2019, KoçSistem award)*
**Rebranded.** Raised 600,000 TL from Lima Ventures in December 2020, then rebranded to
Magnus for international operations and new products, raising ~$420,000. `akillifon.com`
now shows "Yenileniyoruz" (we're renewing).

### 4. Isıteks → **Nanovatif Malzeme Teknolojileri** *(cohort 2016, Elginkan Grand Prize)*
**Isıteks turned out to be a product, not a company.** It is the wearable-heater product
line of **Nanovatif Materials Technologies**, founded 2017 at ODTÜ Teknokent by
Prof. Dr. Emrah Ünalan, Dr. Şahin Coşkun and Doğa Doğanay — three materials scientists with
200+ publications, among the world's leading teams in silver-nanowire production. Nanovatif
is active and has won a Spinoff Prize. *(This corrects `05-alumni-graduates.md`, which
treated Isıteks as the company. `isiteks.com` belongs to an unrelated dehumidification
business.)*

### 5. Seyisco → **Seyis** *(cohort 2017, KoçSistem + Elginkan International awards)*
**Pivoted.** Went from smart pothole/road-damage detection for municipalities to
**"Akıllı Sarf Malzeme Yönetimi"** (smart consumables management) at `seyis.co`. Same brand,
entirely different product. LinkedIn page still carries the original smart-city positioning
(351 followers).

### 6. Blok-Z *(cohort 2018, Growth Circuit investment + Draper University)*
**Relocated and repositioned.** Now a **Germany-based** energy-software provider offering
24/7 Carbon-Free Energy solutions via its **GreenLink** platform, matching hourly
consumption to renewable sources. Listed on EU-Startups, Tracxn and PitchBook. The
`blok-z.com` domain now resolves to an unrelated "Voltfox" page — the company operates
under its corporate identity rather than that domain.

### 7. Notrino Research *(cohort 2019, Ostim Teknopark award)*
**Broadened.** Entered YFYİ with **CurAlive**, a portable 6-channel ECG with PPG sensors.
`notrino.com` is now "Notrino Research — AI-Powered Digital Technologies", an R&D house
doing AI and sensor work across healthcare, energy, automotive, telecoms and banking. Went
from single medical device to multi-sector engineering services.

### 8. Lonca *(cohort 2019)*
**Pivoted.** Entered as in-store AR shopping campaigns; `lonca.co` is now a **B2B wholesale
clothing marketplace** — "Wholesale clothing directly from Turkey at better prices."

### 9. Sweephy *(cohort 2020, KoçSistem + ODTÜ TEKNOKENT Internationalisation awards)*
**Relocated.** Now headquartered in **Tallinn, Estonia**, founded 2021 by Abdullah Alka
Kandilli, Erce Can Bekture and Ertuğ Dilek. Raised **$180K** across a 2022 seed round from
**Startup Wise Guys** and Alesta. Notable: Startup Wise Guys was YFYİ's own 2020 delivery
partner — the program's international partner became its graduate's investor and new home.

### 10. Mobilus / RotaMobil → **Invidyo** *(cohort 2005)*
**Team moved products.** Entered YFYİ 2005 as RotaMobil under Mobilus; the team later built
**Invidyo** (AI care-monitoring cameras) through the Teknojumpp accelerator. `invidyo.com`
is live. Retail in Turkey (E-Bebek, Babymall), 60 Toys "R" Us locations in Canada, Amazon.

### 11. İndisera *(cohort 2016, TEB Grand Prize)*
**Repositioned.** `indisera.com` is live as "AI-Powered Digital Solutions & SaaS
Development" — a different proposition from the 2016 award-winning entry. Flagged CHANGED
on the strength of the repositioning; the underlying corporate continuity is not fully
documented. **[?]**

---

## 🟢 ACTIVE — verified operating

### With documented funding, revenue or scale

| Startup | Cohort | Evidence |
|---|---|---|
| **V-Count** | 2005 | LinkedIn 43,331 followers; AI visitor analytics; offices Miami, Dubai, London, Hong Kong, Brussels; exports to 100+ countries. Now a YFYİ sponsor. |
| **ISSD** | 2010 | `issd.com.tr` live: "since 2009 at ODTÜ Teknokent; active in 20+ countries, 80+ cities, 5,000+ points." Now a YFYİ sponsor. |
| **Enhencer** | 2017 orbit | `enhencer.com` live. Raised $1M (2024, Diffusion Capital Partners + Boğaziçi Ventures + Mert Kaçmaz), total ₺57.8M (~$1.7M). 1,000 e-commerce clients across 45 countries. |
| **FineDine** | 2017 orbit | $3M revenue (Oct 2024), 5M customers, $1.25M raised (Savour Ventures, twozero, TechOne) + **$1M seed from Arya Women's Investment, Jan 2025**. M&A with Foodback. |
| **Sensgreen** | 2018 | `sensgreen.com` live. **$2.62M raised**, ~$1.1M ARR (2025), $4.1–4.25M valuation (Apr 2025), 12+ countries, latest round Oct 2025. |
| **Deplike** | 2016 | LinkedIn 3,815 followers. **216 Capital investment (Nov 2025)**; product Chordie AI; preparing Series A for international expansion. |
| **Otsimo** | 2016 | `otsimo.com` live; LinkedIn 9,705 followers; special-education and speech-therapy apps for autism. |
| **İnofab Health** (Spirohome) | 2014–15 | `inofab.health` live — "world's first personal ultrasonic spirometer." €220K (2017) + €1.1M (2018). |
| **Oculera** | 2020 | **Received investment from ÜNLÜ Ventures, November 2025.** VR eye-health testing; CE and FDA approved. |
| **Mikro Biyosistemler** | 2017 | `mikrobiyo.com.tr` live; ODTÜ spin-off (2015); investors include the **European Union / EIC Fund** and Diffusion Capital Partners. |
| **Some Carbon** | 2023 | In the **Türk Telekom Ventures** portfolio. CO₂-to-methanol and carbon management for iron-steel and cement. |
| **Nefes IoT** | 2023 | `nefesiot.com` live. Early forest-fire detection over NB-IoT and LoRaWAN. **TÜBİTAK BiGG 1512 grant.** |
| **Bionome** | 2022 | `bionome.com.tr` live. Founded 2022 at ODTÜ Teknokent; CBD and pharma/cosmetic raw materials via engineered micro-organisms. **2nd place, EIT-backed EWA Women in Food & Agriculture programme.** Chair: Nerve Cansu İşeri. |
| **Nanovatif** (Isıteks) | 2016 | ODTÜ Teknokent; Spinoff Prize winner; silver-nanowire wearable heaters. |
| **Triwi** | 2018 | `triwi.info` live + iOS app. Raised **2.3M TL via crowdfunding** (~$70K round, 2022); Infinia technology partnership. Founders Alara & Zeynep Akçasız. |

### Live and operating, smaller or quieter footprint

| Startup | Cohort | Evidence |
|---|---|---|
| **Btech Innovation** | 2015 | `btech.com.tr` — medical and industrial advanced engineering; awards and success-story pages. Became a YFYİ sponsor. |
| **Enwair Enerji** | 2015 | `enwair.com` — silicon-based anodes for high-capacity Li-ion batteries. Exactly the 2015 pitch. |
| **B-PREG** | 2018 | `bpreg.com` — unidirectional/woven prepregs, slit tapes, dry fabrics. |
| **Inovarium** | 2018 | `inovarium.com` live (redirects to product portal). |
| **3D3 Teknoloji** | 2017 | `3d3teknoloji.com` — 3D printing, scanning, filament, Ankara. |
| **Pyronome** | 2017 | `pyronome.com` — "Create Scalable and Maintainable Software in Minutes." |
| **Comind** | 2017 | `comind.com.tr` live. |
| **Webgazer** | 2017 | Ankara, founded 2015; Tracxn records 3 employees as of April 2026. Small but alive. |
| **Kuantek Elektronik** | 2017 | Corporate profile active (AI, FPGA, image/signal processing). No recent press. |
| **Eyesoft** | 2017 | `eyesoft.com.tr` live. |
| **Mavilab** | 2017 | `mavilab.com.tr` — Mavi Laboratuvarlar Grubu. |
| **Burkut** | 2017 | `burkut.com.tr` / `burkut.tech` — water technology + web automation platform. |
| **Algodocs** | 2019 | `algodocs.com` — intelligent document data extraction. |
| **EarFit** | 2019 | `earfit.com.tr` — "Acoustic Excellence Engineered by Innovation." |
| **Bakiyem.com** | 2019 | `bakiyem.com` — virtual POS and payment products. |
| **Trendoline** | 2017/2019 | `trendoline.com` live (video challenge app). |
| **Bionova** | 2020 | LinkedIn `bionovabiotech`; new METU Teknopark project extracting pectin from apple pomace. |
| **Case Future** | 2020 | `casefuture.com` — "Discover, watch and learn." |
| **iyiMakina** | 2020 | `iyimakina.com` — iyiMakina A.Ş., used heavy-machinery marketplace. |
| **Magfi** | 2020 | `magfi.co` — live production app. |
| **solarVis** | 2020 | `solarvis.co` — "the Command Center for Solar Sales." |
| **Biopols** | 2021 | `biopols.co` — "Keep Smart Keep Fresh." |
| **Distant** | 2021 | `getdistant.com` live. |
| **Rens** | 2023 | `rens.co` — "Sürdürülebilirlikte Dijital Dönüşüm." |
| **Momentum Teknoloji** | 2016 | `momentum.com.tr` — "Fikirden ürüne, üründen pazara." |
| **AdmetGPT** | 2025 | `admetgpt.com` — Bio-Generative Intelligence Platform, ADMET prediction. |
| **ARGOS-EO** | 2025 | `argos-eo.com` — Argos Elektro-Optik, advanced defence solutions. |
| **TiPS Cell Technologies** | 2025 | `tipscelltech.com` — induced pluripotent stem cells and neurons. |
| **Vision Labs** | 2025 | `visionlabs.com.tr` — AI-powered mobile apps, computer-vision studio. |
| **Snipr** | 2025 | `snipr.io` live. |
| **sciRobot** | 2015 | LinkedIn active (157 followers) — care-home activity platform. |
| **Vivosens** | 2015 | LinkedIn active (1,167 followers) — health tracking. |
| **Hidrotürbin Teknoloji Enerji** | 2015 | LinkedIn active (292 followers), registered Ltd. Şti. |
| **Invidyo** | 2005 lineage | `invidyo.com` live — see CHANGED #10. |

---

## 🔴 PASSIVE — positive evidence of dormancy

### Domain for sale or parked

| Startup | Cohort | Evidence |
|---|---|---|
| Planote | 2016 | `planote.com` listed for sale; LinkedIn stalled at 16 followers |
| Temperfect | 2016 | `temperfect.com` for sale |
| Qwerty | 2018 | `qwertyhealth.com` for sale |
| Davet.com | 2018 | `davet.com` for sale |
| Hera | 2018 | `heratalent.com` for sale |
| Breathall | 2020 | `breathall.com` for sale |
| WeeKiddo | 2020 | `weekiddo.com` for sale |
| Gauss İstatistik Ar-Ge | 2017 | `gaussdata.com` for sale |
| AeroES | 2019 | `aeroes.com` for sale |
| iCaked | 2017 | `icaked.com` parked (lander redirect) |
| Oculera *(domain only)* | 2020 | `oculera.com` parked — **but the company is ACTIVE**, see above; listed here only to note the dead domain |
| OPTIO | 2020 | `optio.tech` parked |
| Castera | 2020 | `castera.co` parked |
| Vivente | 2020 | `vivente.health` parked; no live site despite being the 2020 Elginkan Grand Prize winner |
| Ajanda | 2025 | `ajanda.ai` parked |
| MACHINA | 2015 | `machinarobotics.com` parked |
| HyperCrops | 2024 | `hypercrops.com` parked |
| BugScribe | 2025 | `bugscribe.com` parked *(won the 2025 ODTÜ TEKNOKENT Incubation Award — likely simply pre-launch; treat as provisional)* |
| GEEN | 2015 | `geenbio.com` taken over by an unrelated gambling site |

### "Coming soon" / holding pages

| Startup | Cohort | Evidence |
|---|---|---|
| Şeften | 2022 | `seften.com` — "Coming Soon… under construction" |
| EN/IO | 2019 | `enio.com.tr` — unmodified Next.js default page |
| SAKAI | 2025 | `sakai.com.tr` — "Domain Default page" |

### No web presence and no trace since the program year

| Startup | Cohort |
|---|---|
| Buyan *(2017 Elginkan Grand Prize)* | 2017 |
| Powder Tech *(2019 Elginkan co-winner)* | 2019 |
| Restearn *(2017 public-vote winner)* | 2017 — `restearn.com` returns an empty response |
| Peerket | 2017 |
| Biyoçip *(2015 Elginkan Grand Prize)* | 2015 |
| Talassa *(2016 Arçelik Grand Prize)* | 2016 |
| Wmedya Interactive / Ondestek *(2016 Microsoft Grand Prize)* | 2016 |
| GBlock | 2016 — LinkedIn stalled at 6 followers |
| Matmas | 2016 |
| Ruwell | 2018 |
| Areytech | 2018 — server returns 403 only, no site |
| Warden Legal | 2018 |
| Viliks | 2018 |
| Safetech | 2018 |
| Microsolar | 2018 |
| Dora | 2018 |
| Ankabeta | 2018 |
| Porion | 2020 |
| Favor | 2020 |
| Coffenext *(2022 Elginkan co-winner)* | 2022 |

> **Notable:** four Elginkan Grand Prize winners — Biyoçip (2015), Buyan (2017),
> Powder Tech (2019) and Coffenext (2022) — plus Vivente (2020) have no traceable current
> operation. Winning the flagship prize was not predictive of survival.

---

## ⚪ UNVERIFIED — no public signal either way

**2005–2014 cohorts** (predate startup databases; only the flagship winners were ever named
in press): Kade Vision · Prz Biyoteknoloji · 2C · JeoTim · Biyonesil · Garajsoft · KURUP ·
Kaleidoscope · Isırgan/Dentofast · TIM · Javatar · Algı · PragmaCraft · OE · Heavy Science ·
Nanosis · Powermems · Ultravision

**2015 cohort:** Capres · Engelsiz İnovasyon Takımı · The Light · SmartGel · Kovan ·
Footballpreneurs · Rocketscience · Gelecek Robotik · Arbatros Bilişim · Sotek · Pa_ó ·
GDS (MORRS) · Ekosist

**2017 cohort:** AllEars / Drive Buddy · DijiFi / Dijifin · İMERA · Niceveri Ar-Ge ·
Bzzify Yazılım · MASA · Lingo · Smarteng · Bambulabs

**2019 cohort:** Fado · Geodo · Hetra · Neopoliklinik · Renty · Inspecthink · Persona ·
Safellence · Tiroit / Alp Imaging · Tuvis · Tvoystol.ru · Volte · Wobeya ·
SRT – Solar Roof Track · TradeMate · UlakFin

**2020 cohort:** HED · Hetes · HiFace · Noticy · Yolla

**2022 cohort:** Driven · Appvest · The Clico · SynthData · Phoyer

**2024–25 cohorts** (too new for a footprint): Step4 · Agada · AliceCo AI · SunSight Labs

> Several of these have same-name collisions that produced false positives during probing
> and were deliberately **not** counted as evidence: `fado.com.tr` (greenhouse systems),
> `persona.com.tr` (attendance software), `renty.com.tr` (car rental),
> `drivebuddy.co` (car frames), `hetra.com.tr` (web design), `tuvis.com` (Israeli comms
> security), `kovan.io` (SaaS studio), `lingo.com` (US telecoms), `thelight.com` (a church),
> `masa.com`, `dora.co`, `hera.com`, `bionova.com`. Name collisions are the single biggest
> hazard in this dataset.

---

## Patterns worth noting

1. **Exits.** Alictus → SciPlay was the only acquisition traceable from public sources.
   The official roster records **six** exits in total (Onedio, Inofab Health, Udentify,
   Alictus, Tuvis, Drive Buddy) — see `12-official-roster-analysis.md` §4.
2. **The prize does not predict survival.** Five Elginkan Grand Prize winners are dormant;
   meanwhile several non-winners (Enhencer, FineDine, Sensgreen, Deplike) became the
   best-funded alumni.
3. **Deep tech survives better than consumer.** Materials, medtech and industrial alumni
   (Nanovatif, Enwair, B-PREG, Mikro Biyosistemler, Btech, İnofab) are overwhelmingly still
   operating. Consumer marketplaces and social apps (iCaked, Peerket, Restearn, Trendoline,
   Planote, Magfi's cohort peers) are the densest part of the PASSIVE list.
4. **Pivots go up-market.** Every documented pivot moved from a narrow consumer or
   single-device product toward B2B/infrastructure — Ddosify→Anteon, Seyisco→Seyis,
   Notrino→multi-sector R&D, Lonca→B2B wholesale.
5. **The 2018–2020 cohorts hold the strongest survivors.** Sensgreen, Triwi, B-PREG,
   Inovarium, Oculera, solarVis, Sweephy, iyiMakina, Bionova all trace to those three years.
6. **The Startup Wise Guys loop.** YFYİ's 2020 delivery partner later invested in and
   hosted a YFYİ graduate (Sweephy) in Tallinn.

---

## Method and limitations

**What was done.** Every startup name was probed across up to seven TLDs
(`.com`, `.co`, `.com.tr`, `.io`, `.ai`, `.tech`, `.net`) with full redirect following.
Responses were screened for domain-parking patterns (`/lander` redirects), "for sale"
listings, "coming soon" holding pages and sub-400-byte shells — an early pass that treated
HTTP 200 as "alive" produced roughly a dozen false positives, all corrected. Homepage text
was then keyword-matched against each startup's original YFYİ description to filter
same-name collisions. LinkedIn company pages were resolved across slug variants. Finally,
targeted searches ran against Tracxn, Crunchbase, PitchBook, CB Insights, EU-Startups and
Turkish tech press for the highest-signal names.

**Limitations.**
- **A dead domain is not a dead company**, and a live domain is not a live company. Oculera
  raised from ÜNLÜ Ventures in November 2025 while `oculera.com` sits parked. Some PASSIVE
  entries may be operating under a name or domain not discoverable from the YFYİ record.
- **UNVERIFIED is not PASSIVE.** 55 startups produced no signal in either direction. Turkish
  early-stage companies frequently operate without a discoverable web presence, particularly
  B2B and defence suppliers.
- **The 2005–2014 cohorts are largely untraceable** because ODTÜ TEKNOKENT never published
  cohort lists for those years — only the grand-prize winners were ever named.
- **The 2024–25 cohorts are too recent to classify fairly.** A parked domain eight months
  after Demo Day usually means pre-launch, not failure.
- **No financial or employment verification** was possible for most entries. Revenue and
  headcount figures come from third-party databases (Tracxn, GetLatka, CB Insights) whose
  estimates are frequently stale or modelled.
- **The authoritative source is ODTÜ TEKNOKENT itself** (info@odtuteknokent.com.tr), which
  holds the complete alumni registry that has never been published.
