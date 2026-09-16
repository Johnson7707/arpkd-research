# ARPKD Research Session Handoff — September 15, 2026 (ET)

## LIVE DOCUMENTS — CURRENT STATE

| File | Version | Notes |
|---|---|---|
| index.html | **v7.5 · September 15, 2026** | All Sep 15 additions complete |
| October2026.html | **Sep 15 findings added** | 4 new finding cards |
| arpkd-researcher-network-SKILL-v7.md | **v7.5** | Chandler, Malik, Walker added; Li/Long expanded |
| SESSION_HANDOFF_Sep15_2026.md | This file | |

**Research website:** https://johnson7707.github.io/arpkd-research (needs GitHub push — v7.5 not yet live)
**GitHub:** johnson7707/arpkd-research
**Nathan:** nathaniel_johnson@yahoo.com · Flora CC: fmapremier10@hotmail.com

---

## PATIENT — GIANNA JOHNSON

PKHD1 variants: c.9370C>T (p.His3124Tyr, Zone 3, **ABE substrate**) + c.10926G>A (p.Met3642Ile, Zone 3, VUS, **ABE substrate**). ⚠️ **CORRECTED Sep 16 — see correction note below.**
GFR 103. Portal hypertension: platelets 102, spleen 18cm, no prior bleed. CCHMC. Age 12.
⚠️ AAV contraindicated for cholangiopathy (Krappitz Sep 11, 2026). LNP is correct direction.
⚠️ **BOTH variants are ABE substrates.** Krappitz's existing ABE approach covers both — no CBE program is required.

### 🔴 CORRECTION — September 16, 2026: the "His3124Tyr = CBE substrate" claim was WRONG
Found during the file redundancy audit. Three files disagreed; the handoff was the outlier and was incorrect.
**Biochemistry:** ABE converts A•T → G•C. CBE converts C•G → T•A.
- **c.9370C>T:** reference C•G, patient T•A. Restoring T•A → C•G requires editing the template-strand A to G. **That is ABE, not CBE.**
- **c.10926G>A:** reference G•C, patient A•T. Direct A→G. **ABE.**
Both variants are transition mutations correctable by adenine base editing — which is exactly what Polat et al. (IntechOpen, Sep 5 2026, DOI 10.5772/intechopen.1017730) states, and what the researcher network skill and session-start skill both already said correctly.
**Consequence of the error:** the planned Sep 25 Krappitz question ("is he also designing a CBE approach, or only ABE?") was built on a false premise and would have wasted our one question. **That question is withdrawn.** The CBE-VLP4 (Zhu/ShanghaiTech) entry in the delivery hierarchy is also not needed for Gianna's variants, though it remains a valid general-interest platform.

---

## SESSION — SEPTEMBER 15, 2026

### Papers Reviewed

| Paper | Key Finding | Status |
|---|---|---|
| Li/Harris ABE9 (Nat Commun Dec 2025, DOI: 10.1038/s41467-025-65997-1) | First in vivo kidney base editing — ABE9 (not ABE8e); Ksp organ-specific promoter; liver 40% gDNA/57% cDNA | Added to index v7.5 |
| Caplan/Onuchic PC1 fragment (Nat Commun 2023, DOI: 10.1038/s41467-023-37449-1) | 200aa C-terminal PC1 fragment suppresses ADPKD — explicit ICD15 parallel drawn | Added to index v7.5 |
| Yang/Guay-Woodford cyli (J Mol Med 2023, PMID: 37584738) | Parity dramatically worsens ARPKD liver disease — sex + pregnancy effects confirmed in PKHD1 mouse | Added to index v7.4 (earlier today) |
| Long KRUK article (June 15, 2026) | News article says £200K — OFFICIAL award = £208K, Oct 2025 round, title "Inhibiting AMPK"; Chandler = Long's trainee; Sep 25 question UPDATED: AMPK direction discrepancy (inhibit vs activate) | Updated in index v7.6 |
| Walker KRUK article (June 2024) | Second KRUK project: £240K FPC/PC2 ciliary signaling | Added to index v7.5 |
| Chandler KRUK article (Aug 10, 2026) | AAV FPC fragment restoration; PKDisospheroids; Long's trainee; URL was mislogged as Long's; CORRECTED grant = £99K (not £98K); official title "Evaluating gene therapy for childhood polycystic kidney disease in a 3D human cellular model" | Updated in index v7.6 |
| Malik/Chandler/Long Sci Transl Med 18:862 (Aug 13, 2026) DOI: 10.1126/scitranslmed.adv1289 | The Aug 13 KRUK article ("group photo") is a PUBLISHED PAPER: angiopoietin-1 RNA therapy via lipid nanocomplexes + ultrasound-guided renal artery injection for WT1 glomerular disease — NOT ARPKD but proves lipid nano delivery to kidney cells in vivo | Added to index v7.6; Malik entry expanded in network |
| KRUK Oct 2024 article (Oct 8, 2024) | Chandler J Pathology paper: adrenomedullin/WT1 glomerular signaling; PhD student Emily Moore; NOT an ARPKD/PKD grant — was result of her 2022 fellowship | Corrects prior framing; added to index v7.6 |
| KRUK Latest Awards page (fetched Sep 15, 2026) | Long AMPK grant = £208K (not £200K); title = "INHIBITING AMP-activated protein kinase"; Oct 2025 round (not Jun 2026); Chandler PKD grant = £99K (not £98K); Long new PhD studentship £125K diet/PKD (March 2026); Bebi training fellowship £243K; Jafree research project £248K (AI lymphatics, transplantation) | All corrections applied to files v7.6 |
| Zhu CBE-VLP (Nat Biotechnol Jul 2026, PMID: 42432197) | 46-64% liver CBE editing via tBE-VLP4, zero off-target | Previously noted |
| Giblin/Chung PKD2 LNP (bioRxiv Jun 2026) | CD-targeted LNPs reverse cystic disease in Pkd2 AND Pkd1-deficient models | Previously in network |
| PKD Foundation pipeline | Images only — could not read | Used pkdcuretracker.com |
| PKD Cure Tracker pipeline (19 drugs) | Farabursen Phase 3 imminent (Novartis $1.7B); VX-407 (Vertex PKD1 modulator Phase 2); PYC-003 (peptide-PMO Phase 1); BEAT-PKD Sept 2026 | Assessed; not yet added to docs |
| NIH bone marrow chip | Not relevant to ARPKD-CHF | Correctly filtered |
| Basel HCC organoids | Not relevant to ARPKD-CHF | Correctly filtered |

### Gene Therapy Research Conducted

Key findings from systematic search:
- **Cholangiocyte targeting via α2,3-sialic acid** — already in framework (Cebotaru). MAL-lectin LNP principle not yet pursued.
- **ABE9 > ABE8e for kidney editing** — Li/Harris paper. Relevant for Gianna's renal component.
- **Ksp → HNF1β promoter swap** = path to biliary-specific base editing. Nobody has done this.
- **LNP lipid chemistry determines non-hepatocyte tropism** (Eisai, Sept 2025) — cholangiocyte-targeting lipid screen not yet done.
- **Chung lab dual tracks**: mRNA replacement (Giblin preprint) + CRISPR editing (PKD Foundation grant). Both for PKD kidney.
- **Zhongwei Li (USC)**: ARPKD organoid platforms in vitro + in vivo. Approach via Chung.

### Documents Updated This Session

- **index.html v7.5**: Li/Harris ABE9, Caplan/Onuchic PC1 parallel + ICD15 comparison table, Long AMPK confirmed, Walker 2024 second project, Chandler profile + URL correction, Guay-Woodford cyli (parity)
- **network v7.5**: Chandler (new, warm via Long), Malik (noted, UCL GOS ICH), Walker (added to table with both projects), Li Xiaogang (expanded), Long (confirmed AMPK details)
- **October2026.html**: 4 new finding cards (Li/Harris ABE9, Caplan/Onuchic, Long-Chandler-Walker, cyli)

---

## ⭐⭐ SYNTHESIS SESSION — September 15, 2026 (v7.7)

New section added to index.html: **🎯 Convergence & Path Forward** (anchor `#pathforward`, first item in Framework nav). This is the first section in the framework that assembles findings into a proposed strategy rather than cataloguing them.

### Three Named Principles (NEW)
1. **Organ Divergence Principle** — Kidney and liver in ARPKD may need OPPOSITE interventions. Evidence: AMPK (Walker=activate protective / Long KRUK=inhibit) and STAT3 (Long lab CT-1 2024=protective in kidney / Ziegler-Hassan=pathogenic in liver). ⚠️ Safety implication: a systemic drug helping her kidneys could worsen her liver. Makes organ-targeted delivery a REQUIREMENT, not an optimization.
2. **Vascular Hypothesis of ARPKD-CHF** — Our cascade is entirely epithelial+immune; vasculature appears nowhere. Chandler J Pathol 2024 template: epithelial cells stop supporting adjacent endothelium → endothelial death → scarring. Jafree DMM 2025: microvascular aberrations are EARLY in Pkd1 mice + human polycystic kidneys. Untested transfer: do FPC-deficient cholangiocytes fail to support the peribiliary vascular plexus?
3. **Amplify Failing Compensation** — Nearly all our candidates are inhibitors. But adrenomedullin (Chandler) and GDF15 (framework) are both failing protective responses. Malik/Chandler/Long amplified a protective signal (ANGPT1) rather than blocking a pathogenic one. Restoration class already in framework but never named: FPC fragment, FPCct, ICD15, AAV1-CFTR.

### ⭐⭐ THE ASSEMBLY (most actionable item in framework)
**αvβ6-targeted nanocomplexes + hepatic artery delivery + FPC mRNA or base editor cargo.** All 5 components published; assembly exists nowhere.
| Component | Holder |
|---|---|
| Targeted nanocomplex platform (αvβ3) | **Hart (UCL GOS ICH Genetics)** |
| Image-guided arterial delivery | **Kalber (UCL CABI)** |
| Biliary address (αvβ6, 70%, r=0.94) | **Strazzabosco (Yale)** |
| Restoration cargo | Chandler / Ziegler / Walker-Qian |
| Correction cargo | Krappitz |

**Anatomical basis:** Intrahepatic bile ducts are supplied almost exclusively by the HEPATIC ARTERY (hepatocytes = mostly portal vein). This is why hepatic artery thrombosis post-transplant causes ischemic cholangiopathy. Hepatic artery catheterization is already routine IR (TACE). **Hepatic artery = biliary equivalent of Kalber's renal artery approach.**
**The reframe:** αvβ6 has only ever been studied as a drug target to BLOCK (bexotegrast). Read as a DELIVERY ADDRESS it is a high-density disease-specific surface receptor with the best ARPKD-specific expression data in the literature.

### Two-Track Model (NEW)
- **Track A — Correction:** base editing, permanent, variant-specific (Gianna needs BOTH CBE and ABE), higher regulatory bar, long-term goal
- **Track B — Restoration:** FPC mRNA, transient, mutation-agnostic, LOWER regulatory bar, **could start sooner as a bridge**

### Tie2 Observation
ANGPT1 signals through Tie2. Jafree Cell Reports 2026: most kidney lymphatics arise from **Tie2+** progenitors. Two papers, one lab, one year, same receptor — connection undrawn. ANGPT/Tie2 is a lymphangiogenesis pathway. **Portal hypertension is fundamentally a lymphatic overload problem.** The ANGPT1 therapy may have an unmeasured lymphatic mechanism relevant to the liver.

### 📬 CONTACT POLICY — corrected September 16, 2026
**Email researchers directly. Routing restrictions removed from the network skill.** They were not evidence-based: this network reached 75 people by direct outreach with a strong reply rate, while the single warm referral (Gissen → Long, July 2026) is the one contact that has never replied — now ~11 weeks silent. Long is deprioritized, not a gate.
**Only standing exception:** Fedeles is already CC'd on the active Krappitz thread — reply there rather than opening a second one.
**Verified Sep 16:** Hart `s.hart@ucl.ac.uk` · Janowski `miroslaw.janowski@som.umaryland.edu` (410-706-7904)
**Verify before sending:** Torres (Mayo directory) · Marshall (QMUL site)
**Hart note:** his group is the UCL GOS ICH **Cilia Disorders Section** and his main disease is primary ciliary dyskinesia — a ciliopathy, same family as ARPKD. Platform = cationic targeting peptides for receptor-mediated uptake, which is exactly the αvβ6/A20FMDV2 mechanism. Founder of Nanogenic Solutions Ltd.

### Tier 1 Actions (answerable now, single blood draws / existing tissue)
- Serum **adrenomedullin** in ARPKD-CHF — Chandler's cross-disease injury signature + known elevation in portal hypertension; **these two literatures have never met**; never measured in ARPKD-CHF (Liebau, Miethke)
- Serum **MMP7** in ARPKD-CHF (Miethke, Liebau)
- **αvβ6 in human ARPKD-CHF liver tissue** — confirmed in mouse only; human confirmation validates the delivery-address hypothesis (Strazzabosco, Gupte)
- **AMPK isoform profiling: cholangiocyte vs collecting duct** — directly tests Organ Divergence (Long, Walker)

### New Open Questions
- Is **nephron number reduced in ARPKD**? Jafree: disrupting Osr1+ lymphatics reduces glomerular number. If endowment is reduced, Gianna's GFR 103 masks smaller renal reserve.
- Is **NRP1** the shared node between Chandler's glomerular findings and our open SEMA4D→LSEC question to Gracia-Sancho? Semaphorins signal through neuropilins. Ruhrberg (leading NRP1 authority) confirmed collaborating with Long group.
- Does the Hart platform **tolerate ligand substitution** without losing transfection efficiency? The entire αvβ6 assembly depends on this one technical question.
- Are **peribiliary lymphatics** abnormal in ARPKD-CHF?

---

## 🔬 LOAD-BEARING SOURCE VERIFICATION LEDGER — started Sep 16, 2026

**Method:** verify the most-cited DOIs first; errors in load-bearing sources cascade. 20 sources carry ~400 of the framework's citations.

| # | Citations | DOI as cited | Verdict | Correct citation |
|---|---|---|---|---|
| 1 | **54** | `10.1038/s41598-026-43852-7` (Sci Rep 2026) | 🔴 **WRONG — belongs to a Sargassum/seaweed organoid paper (Heo/Yu, Seoul Nat'l Univ)** | ✅ FIXED → Khare S, Jiang L, Paine-Cabrera D, Apte U, **Pritchard MT**. *Livers* 3(3):331-346, 2023. **DOI: 10.3390/livers3030025**. SRA PRJNA799864 |
| 2 | **29** | `10.1007/s00247-026-06372-9` (Pediatr Radiol 2026) | 🔴 **WRONG — DOI does not resolve; digits transposed** | ✅ FIXED → **MacAskill CJ**, Smothers JB, Kretzler ME, … Dell KM, Hartung EA, Serai SD, **Flask CA**. "Advanced MRI methods for children and young adults with ARPKD to support future multi-center clinical trials." *Pediatr Radiol* 2026. **DOI: 10.1007/s00247-026-06737-5**. ⚠️ Also corrected first author — framework listed Flask first; actual first author is **MacAskill CJ** |
| 3 | 29 | `10.1038/s42003-026-10476-6` | ✅ **VERIFIED CORRECT** | Jiao M, Sun Y, Liu R, Yin X, Hou X, Yuan H, Dai Z, Chen Q, **Zhu C** (corresponding). "P-STAT3-dependent SPP1 transcription in cholangiocytes drives hepatic stellate cell activation in congenital hepatic fibrosis." *Commun Biol*, 2026 Jun 9. PMID: 42265280. Nanjing Medical University. Content matches: PKHD1 deficiency → progressive SPP1 upregulation in cholangiocytes; co-culture showed PKHD1-deficient cholangiocytes secrete OPN activating PI3K/Akt in HSCs |
| 4 | 28 | `10.1002/hep.32298` | ✅ **VERIFIED CORRECT** | Masyuk AI, Masyuk TV, Trussoni CE, Pirius NE, **LaRusso NF** (corresponding). "Autophagy promotes hepatic cystogenesis in polycystic liver disease by depletion of cholangiocyte ciliogenic proteins." *Hepatology* 75(5):1110-1122, 2022. PMID: 34942041. PMC9035076. Content matches: autophagy-mediated depletion of ARL3/ARL13B |
| 5 | 26 | `10.1152/ajpgi.00255.2022` | ✅ **VERIFIED CORRECT** | Yanda MK, Zeidan A, **Cebotaru L**. "Ameliorating liver disease in an autosomal recessive polycystic kidney disease mouse model." *Am J Physiol Gastrointest Liver Physiol* 324(5):G404-G414, 2023. PMID: 36880660. Johns Hopkins. Content matches: VX-809 inhibits cholangiocyte proliferation and limits bile duct malformation in Pkhd1del3-4/del3-4 mice |
| 6 | 22 | `10.1016/j.jhep.2022.01.017` | 🔴 **WRONG JOURNAL + DOI** | ✅ FIXED → **Fabris L**, Milani C, Fiorotto R, Mariotti V, Kaffe E, Seller B, Sonzogni A, **Strazzabosco M**, Cadamuro M. "Dysregulation of the Scribble/YAP/β-catenin axis sustains the fibroinflammatory response in a PKHD1-/- mouse model of congenital hepatic fibrosis." ***FASEB J* 36(6):e22364, 2022. DOI: 10.1096/fj.202101924R. PMID: 35593740.** NOT *J Hepatol* 76(5):1386-1403. ⚠️ **The correct DOI was ALREADY in the document (10 citations) — the same paper was cited two different ways, one right and one wrong.** |
| 7 | 22 | `10.1152/ajpgi.00109.2025` (Ciobanu/Outeda/Cebotaru) | ⬜ NOT YET CHECKED | |
| 8 | 22 | `10.1002/hep.26296` | 🔴🔴 **RETRACTED PAPER + WRONG DOI — WORST FINDING OF THE AUDIT** | **(a)** The DOI cited belongs to an unrelated hepatitis C paper (Shrivastava S … Ray RB, "Up-regulation of circulating miR-20a … hepatitis C virus-mediated liver disease progression," *Hepatology* 58(3):863-871, 2013). **(b)** The paper actually intended — Spirli C, Strazzabosco M et al. "Protein kinase A-dependent pSer675-β-catenin, a novel signaling defect in a mouse model of congenital hepatic fibrosis," *Hepatology* 58(5):1713-1723, 2013, DOI 10.1002/hep.26554, PMID 23744610 — **WAS RETRACTED: *Hepatology* 78(3):E63, 1 Sep 2023, DOI 10.1097/HEP.0000000000000486.** ✅ All 22 re-pointed to **Kaffe E, Fiorotto R, Pellegrino F, Mariotti V, Amenduni M, Cadamuro M, Fabris L, Strazzabosco M, Spirli C. *Hepatology* 67(5):1903-1919, 2018. DOI: 10.1002/hep.29652. PMID: 29140564**, which independently reports the PKA-mediated pSer675 β-catenin phosphorylation. Biology survives; the retracted source does not. |
| 9 | 21 | `10.1152/ajpcell.00057.2025` | ⬜ NOT YET CHECKED | |
| 10 | 18 | `10.1038/s42255-026-01521-z` (Djouder Nat Metab) | ⬜ NOT YET CHECKED | |
| 11 | 18 | `10.1016/j.jhep.2025.09.021` (Galanakis) | ⬜ NOT YET CHECKED | |
| 12 | 16 | `10.1242/dmm.052835` (Waddell/Boulter) | ⬜ NOT YET CHECKED | |
| 13 | 15 | `10.1038/s41467-023-38688-0` (Walker/Qian ICD15) | ⬜ NOT YET CHECKED | |
| 14 | 15 | `10.1007/s00467-025-07129-x` (Guay-Woodford FPC review) | ⬜ NOT YET CHECKED | |
| 15 | 14 | `10.1073/pnas.0602064103` (Masyuk 2006) | ⬜ NOT YET CHECKED | |
| 16 | 14 | `10.1016/j.jhep.2025.09.016` (Hirschfield INTEGRIS-PSC) | ⬜ NOT YET CHECKED | |
| 17 | 14 | `10.1002/hep.26290` (Masyuk) | ⬜ NOT YET CHECKED | |
| 18 | 12 | `10.1172/JCI200318499` (Masyuk 2003) | ⬜ NOT YET CHECKED | |
| 19 | 12 | `10.1016/j.jcmgh.2021.07.012` (Yanda/Cebotaru) | ⬜ NOT YET CHECKED | |
| 20 | 11 | `10.1016/j.cell.2026.02.001` (Zhang) | ⬜ NOT YET CHECKED | |

**Running score: 7 checked · 4 wrong · 3 correct · 127 citations corrected.**

### 🔴🔴 NEW STANDING RULE — CHECK RETRACTION STATUS, NOT JUST EXISTENCE
The Spirli 2013 finding is the most serious of the audit: **the framework relied on a RETRACTED paper for a root-cascade node (FPC → cAMP/PKA → β-catenin pSer675) for an unknown length of time.** A DOI that resolves is not the same as a paper that stands. **Every pre-2020 single-source claim must be re-checked for retraction.** Add retraction checking to arpkd_audit.py and to the pre-send protocol.

### Failure modes found so far
1. **Cross-contamination** — DOI belongs to a completely different paper (Sargassum; hepatitis C miR-20a) — 2 instances
2. **Transcription** — digits transposed, DOI resolves nowhere (Pediatr Radiol) — 1 instance
3. **Wrong journal** — right paper, wrong journal/volume/DOI (Fabris: FASEB J cited as J Hepatol) — 1 instance
4. **Retraction** — source withdrawn from the literature — 1 instance
5. **Internal inconsistency** — the same paper cited two different ways in one document, one correct (Fabris) — 1 instance

**In every case the SCIENCE was described correctly. Only the identifier was wrong.** This failure mode is invisible to a reader and only surfaces on resolution.

**Pattern observed so far:** both errors were in **recently-added 2026 citations**; the three verified-correct sources are long-standing entries (2022, 2023, and one 2026). Tentative hypothesis — errors concentrate in *recently added* material rather than being uniformly distributed. Worth testing as the audit continues: if it holds, newly added citations warrant verification at entry.

**Both failures also shared a signature:** a plausible-looking but non-resolving DOI attached to correctly-described science. The science was right in every case; the identifier was wrong. **This is the failure mode to watch for — it is invisible to a reader and only exposed by resolving the DOI.**

**Next up (session 2):** #6 `10.1016/j.jhep.2022.01.017` (Fabris, 22×) · #7 `10.1152/ajpgi.00109.2025` (Ciobanu/Outeda/Cebotaru, 22×) · #8 `10.1002/hep.26296` (Spirli 2013, 22×) · #9 `10.1152/ajpcell.00057.2025` (21×) · #10 `10.1038/s42255-026-01521-z` (Djouder, 18×).

---

## 🔴🔴 AUDIT ROUND 3 — MAJOR CITATION ERROR FOUND (Sep 16, 2026)

**54 citations — the most-cited source in index.html — were attached to the WRONG PAPER.**

**WRONG:** `Sci Rep 16, 2026. DOI: 10.1038/s41598-026-43852-7`
→ That DOI belongs to **Heo J, Chae DH, Park HS et al. (Yu KR corresponding), "Disease-derived liver organoids … identify *Sargassum japonica* as an anti-fibrotic candidate," Sci Rep 16:13783, 2026, Seoul National University** — a **seaweed** anti-fibrotic organoid paper, nothing to do with PCK rats.

**CORRECT:** **Khare S, Jiang L, Paine-Cabrera D, Apte U, Pritchard MT (corresponding). "Transcriptomics of Congenital Hepatic Fibrosis in ARPKD Using PCK Rats." *Livers* 3(3):331-346, 2023. DOI: 10.3390/livers3030025.** KUMC · NCBI SRA PRJNA799864 · preprint bioRxiv 10.1101/2023.01.19.524760 (PMC9882327) · 1,298 DEGs across PND 15/20/30/90.

**Affected claims (science correct, identifier wrong):** PDGFR-β, CD44, SMAD7, HNF4α, LZTFL1, CXCR6, CELSR1/Wnt-PCP, STAT1/3/4/5B, PND20-30 therapeutic window, "pathogenic triumvirate".

**ALL 54 CORRECTED in index.html + prominent correction notice added at the top of the Path Forward section.** Newsletter skill also corrected (it had a third variant: "*Genes* 3(3):25, 2023" — wrong journal and pages).

**⚠️ PRITCHARD AND APTE ARE IN OUR NETWORK (mpritchard@kumc.edu, Sep 19-20 follow-up due).** Pritchard is corresponding author. Any newsletter or email citing this work must use the Livers 2023 reference. Worth confirming with her directly — it is also a natural, honest opening for the follow-up.

**METHOD THAT FOUND IT:** verify the MOST-CITED DOIs first — errors in load-bearing sources cascade. **This was the first source checked.** Implication: other high-citation-count sources must be verified the same way.

---

## 🔍 AUDIT ROUND 2 — September 16, 2026

### 1. ⚠️ SOURCE ATTRIBUTION — ~10 newsletter-skill entries list "Google AI Mode synthesis" as Source
**Verdict: the workflow was sound; the LOG is wrong.** Checked against index.html: PIEZO1 (entry 69) carries Konstantinou *Nat Commun* 2024 DOI 10.1038/s41467-024-49985-9, Konstantinou *AJP Cell Physiol* 328:C1783-C1792 2025, Fan *Kidney360* 5:715-727 2024 DOI 10.34067/KID.0000000000000453. ICG-001/PRI-724 and Scribble entries also carry primary DOIs. **AI was used as a discovery tool, then grounded before publication.** The skill log records the discovery method instead of the evidence, which would mislead a future session.
**RULE ADDED to newsletter skill:** never record AI synthesis as Source; record the primary citations it led to; safety/contraindication claims require primary citations without exception; back-fill entries 62-73 and 81.

### 2. 🔴 THE CALCIUM CONTRADICTION WAS ALREADY RESOLVED IN OUR OWN DOCUMENT
On Sep 16 I flagged the reduced-vs-increased calcium contradiction and offered "compartmentalisation" as a *possible new hypothesis*. **It was already established in the framework on August 21, 2026**, in the PIEZO1 entry: **"Yoda1 = global cytoplasmic Ca²⁺ (not ciliary microdomain restoration)."**
Ciliary microdomain Ca²⁺ and bulk cytosolic Ca²⁺ are different quantities and can move in opposite directions. Classical FPC model = reduced **ciliary influx**; Morizane/Kuraoka = increased **bulk intracellular**. Not necessarily contradictory. **This distinction is exactly why PIEZO1 was removed from therapeutic candidates.**
**→ The decisive question for BNP: WHICH COMPARTMENT WAS MEASURED?** Add to the Ikeda email.
**Still genuinely unresolved:** cell type (distal tubule vs cholangiocyte) and disease stage.

### 3. Three orphan `</strong>` tags fixed (all on Sep 14 entries, including SLC8A1+TRPV4). index.html and October2026.html now fully tag-balanced, no duplicate IDs, no broken anchors.

### 4. Pattern worth noting
Three of today's "discoveries" were re-derivations of things already in the framework: the calcium node (Sep 14 SLC8A1+TRPV4 entry), the compartmentalisation resolution (Aug 21 PIEZO1 entry), and TRPV4's significance (Sep 14, not a footnote). **The framework has outgrown the ability to hold it in working memory. Search the existing document before declaring anything new.**

---

## ✅ OPEN QUESTIONS ANSWERED — Sep 16, 2026 (2 moved)

**1. "Can ERCP retrograde biliary delivery achieve sufficient transfection of intrahepatic bile ducts?"** → **ANSWERED.** ~1% of hepatocytes (Fabre JW, KCL, PMC1774706). Combined with (a) bile ducts supplied almost exclusively by hepatic artery, (b) hypertrophied peribiliary arterial plexus + reduced portal branches in DPM, (c) Salemdawod/Janowski fractionated intra-arterial case → **hepatic arterial delivery now supersedes ERCP in this framework.** Also: ERCP carries cholangitis risk in an abnormal biliary tree, and cholangitis is a documented fibrosis amplifier here.

**2. "Does tolvaptan (V2R antagonist) have any secondary effect on ARPKD biliary disease?"** → **SUBSTANTIALLY ANSWERED.** (a) Mancinelli R et al. Lab Invest 96(11):1147-1155, 2016 — vasopressin regulates growth of the biliary epithelium in polycystic liver disease; the axis is NOT kidney-restricted. (b) BNP is vasopressin-suppressive and AAV9-BNP reduced hepatic remodeling and cystic indices in the PCK rat.
**⚠️ Distinction preserved:** this answers the BIOLOGY (axis matters in liver) not the DRUG question. Tolvaptan has hepatotoxicity risk — material in a child with cholangiopathy and elevated transaminases. **BNP reaches the same axis endogenously with no hypotension at 40× supraphysiological levels.** Reframed question: which agent suppresses this axis safely in a child with portal hypertension?

**Both now in the Answered Questions section of index.html with full citations. Originals struck through in Open Questions with pointers.**

---

## ⭐⭐⭐ THE CALCIUM CONVERGENCE — Sep 16, 2026 (biggest synthesis of the session)

**Four independent interventions, four labs, four modalities, one node. All four were ALREADY in our framework, in four different sections, never grouped.**

| Intervention | Calcium result (authors' words) | Source |
|---|---|---|
| **BNP (AAV9)** | **increased intracellular calcium** in cystic epithelial cells | Holditch/Ikeda, Kidney Int 92(3):657-668, 2017 |
| **SPTAN1 CRISPR activation** | alleviated cysts, **normalized calcium**, reduced RAC1/c-FOS | Saito/Morizane, Adv Sci 13(25):e24001, 2026 |
| **Cilia ablation** | **restored calcium**/autophagy → rescued cystogenesis | Xia Y, Cell Stem Cell 31:106-122, 2024 |
| **FPCct re-expression** | suppresses cysts, rescues pSRC+pSTAT3 | Hassan/Dafinger/Liebau/Ziegler, AJP Cell Physiol 2026 |

**Root cascade (Masyuk 2003/2006):** FPC+PC2 ciliary flow sensing → Ca²⁺ → FPC loss → impaired Ca²⁺ → AC5/AC6 disinhibited → cAMP → PKA → SRC/STAT3/SPP1 **AND** β-catenin. **Everything downstream of the cAMP bifurcation is a branch. Calcium is the trunk.**

**⭐ WHY THIS MATTERS MORE THAN ANY SINGLE CANDIDATE:** our Therapeutic Candidates table is mostly inhibitors acting DOWNSTREAM of the bifurcation (SRC, STAT3, SPP1, CXCR3, CDK1, αvβ6, YAP) — each blocks ONE branch. **Calcium restoration acts ABOVE the bifurcation.**

**⭐ MUTATION-AGNOSTIC:** BNP supplementation and SPTAN1 epigenome activation **do not require correcting PKHD1**. Bypasses the VUS question entirely; no permanent genomic change; no variant-specific guide design. Materially different risk profile from base editing.

**⚠️⚠️ AUDIT CORRECTION Sep 16 — READ THIS BEFORE USING THE CALCIUM SECTION:**
**(a) DIRECTION OF THE CALCIUM DEFECT IS UNRESOLVED.** Classical (Masyuk 2003/2006): FPC loss → **REDUCED** Ca²⁺ influx → AC5/AC6 disinhibited → cAMP. Sep 14 entry (Kuraoka/Morizane): SPTAN1 loss → RAC1 → **INCREASED** intracellular calcium → cysts; CRISPRa **normalises** it. **BNP RAISED calcium and helped.** "Raised" ≠ "normalised" ≠ "restored". **If calcium is already elevated in cyst cells, raising it further should WORSEN disease.** Possible resolutions: compartmentalisation (ciliary vs bulk cytosolic — different measurements); cell type (distal tubule vs cholangiocyte); disease stage. **Treat as hypothesis requiring direction-specific validation, NOT established convergence.**
**(b) FALSE CLAIM CORRECTED:** first draft said TRPV4 was "only a footnote to the PIEZO1 entry." **Wrong.** TRPV4 is substantive in the **Sep 14 entry "SLC8A1 + TRPV4 = Unified Calcium Dysregulation Mechanism"** — SLC8A1 exports calcium, TRPV4 imports it, both dysregulated from opposite directions; an unstated Morizane/LaRusso convergence. That Sep 14 entry anticipated much of this section.
**NEW QUESTION FOR IKEDA:** what exactly was measured in the BNP in vitro work — bulk cytosolic Ca²⁺, ciliary Ca²⁺, or store release?

---

## ⭐⭐ THE αvβ6 CLOSURE — delivery address = orphaned receptor

**Two of our own hypotheses, written months apart in different sections, complete each other.**
- **A (Aug 20, 2026):** FPC carries an **RGD domain** (OMIM). αvβ6 on cholangiocytes is the candidate receptor. Shed PECD containing RGD may normally **compete with latent TGF-β for αvβ6 binding**. FPC loss → αvβ6 unoccupied → TGF-β hyperactivation.
- **B (Sep 15-16, 2026):** αvβ6 is the ideal **delivery address** — 70% of biliary structures, r=0.94 with portal fibrosis (Locatelli/Strazzabosco 2016); targetable with A20FMDV2.

**⭐ SYNTHESIS: αvβ6 may be so abundant in ARPKD-CHF precisely BECAUSE its natural ligand — FPC's RGD domain — is missing. The disease creates the delivery address by leaving the receptor vacant.** This also explains the r=0.94 strength: unoccupied αvβ6 is free to activate latent TGF-β, so receptor availability and fibrosis severity rise together.

**Testable prediction:** A20FMDV2 carriers should bind diseased cholangiocytes MORE avidly than healthy ones, scaling with severity. **A therapy restoring FPC would progressively REDUCE its own delivery address** — a real repeat-dosing consideration.
**Routing:** Strazzabosco, Marshall (A20FMDV2), Bannell/Cockburn (Leeds, FPC structure), Hart.

---

## ⭐ ORGAN DIVERGENCE PRINCIPLE — REFINED Sep 16

**Divergent nodes — all INTRACELLULAR SIGNALLING:** AMPK · STAT3 · cardiotrophin-1
**Convergent nodes — UPSTREAM SECOND MESSENGERS + VASCULAR:** intracellular calcium (4 interventions, both organs) · RAC1 (cystogenic in kidney per Morizane; PAK1→pSer675-β-catenin in liver — SAME direction) · cAMP (pathogenic both) · natriuretic peptide/vascular signalling (BNP helped both)

**⭐ SCREENING RULE:** interventions acting on **second messengers and vasculature** → candidates for **systemic delivery**. Interventions acting on **intracellular signalling kinases** → require **organ-targeted delivery**.

**Note:** RAC1 dual-organ relevance was flagged in our files as "NEVER COMMUNICATED TO MORIZANE" — still outstanding; R-naproxen and NSC23766 could have dual benefit.

---

## ⭐⭐⭐ BNP / NATRIURETIC PEPTIDE AXIS — FULL PAPER READ Sep 16, 2026

**Holditch et al. Kidney Int 92(3):657-668, 2017. PMC5557687 (free). Corresponding author: Yasuhiro Ikeda, ikeda.yasuhiro@mayo.edu ✅ VERIFIED (507-538-1252).**
**The paper's OWN keywords: ADPKD; ARPKD; adeno-associated virus; congenital hepatic fibrosis; gene therapy.** The authors framed it for ARPKD-CHF explicitly.

### ⭐ BNP HITS NINE NODES ALREADY IN OUR CASCADE
Read as a kidney paper for 9 years. Against our own framework:
| Node | BNP effect |
|---|---|
| **FPC-PC2-Ca²⁺ — THE ROOT** | **increased intracellular calcium in cystic epithelial cells** |
| cAMP | cGMP is the opposing cyclic nucleotide |
| Vasopressin/tolvaptan axis | BNP is vasopressin-suppressive (endogenous route) |
| **Galectin-3 (TREM2 ligand)** | reduced galectin-3 expression |
| IL-8/CTGF | IL-8 top affected pathway |
| PDGF/PDGFRB (Peltz target) | PDGF top affected pathway |
| Wnt (→ zonation section) | Wnt signalling affected |
| Calcineurin/NFAT | negative regulators identified |
| Collagen genes | Col3a1, Col5a2, Col6a3, Col6a1, Col8a2 suppressed |

The **calcium** result is the striking one — it acts at the TOP of our cascade, not midstream.

### ⚠️ CELL-TYPE CAVEAT = THE BEST QUESTION FOR IKEDA
They measured **desmin+ hepatic stellate cells**. Our Yale atlas work (Sep 10) established ARPKD-CHF fibrosis is **NGFR+ portal fibroblast-driven, NOT stellate-cell driven**, and warned NAFLD-targeted antifibrotics may miss. **Ask Ikeda: were NGFR+ portal fibroblasts assessed, or only desmin+ stellate cells?**

### Hydroxyproline null is NOT a failure
Collagen content unchanged — but Waddell/Boulter established CHF's primary ECM defect is **BM LOSS, not collagen excess**. Cystic index, remodeling, stellate activation and galectin-3 all fell anyway.

### Safety
40× supraphysiological BNP → **NO hypotension**, no blood chemistry changes. Removes the obvious objection for a portal hypertension patient.

### Model match
**Neonatal female PCK rats.** Framework notes female PCK rats progress worse than males; cyli paper: parity worsens liver disease. Gianna is female. Neonatal dosing = early-intervention principle.

---

## ⭐⭐ TWO-ARM CONVERGENCE — GC-A for cysts, GC-B for portal hypertension
| Arm | Receptor | Evidence |
|---|---|---|
| BNP/ANP | **GC-A** | suppressed renal AND hepatic cystogenesis in PCK rat (Holditch 2017) |
| CNP | **GC-B** | "offsets the pathogenesis of steatohepatitis, hepatic fibrosis, and **PORTAL HYPERTENSION**" (PMC11734523) |

**⭐ CENDERITIDE (CD-NP) activates BOTH** — first and only dual GC-A/GC-B agonist in clinical trials (Burnett, Mayo; CNP fused to green mamba DNP C-terminus for degradation resistance). **One molecule, both arms. Never tested in ARPKD.**

**"Natriuretic peptide resistance"** (PMID 42645729, Sep 2026 review) = our **Amplify Failing Compensation** principle under another name. Designer peptides: Cenderitide, MANP, ANX042, CRRL269.

**MANP** = Mayo pGC-A activator, reached **first-in-human trials** for resistant hypertension. From a familial NPPA frameshift mutation producing a degradation-resistant peptide.

**🔴 CARDIOTROPHIN-1 = THIRD directional contradiction.** Cenderitide inhibits fibroblast proliferation induced by CT-1 (**pro-fibrotic**). Long lab (Perretta-Tejedor, Physiol Rep 2024): CT-1 **reduces** murine glomerular disease (**protective**). Arrived independently of the AMPK and STAT3 contradictions → **strengthens Organ Divergence Principle**.

### 🔴 GALECTIN-3 — two routes, one with human portal hypertension data
- **BNP reduces galectin-3** (Holditch 2017)
- **Belapectin blocks galectin-3** — NAVIGATE Ph2b (Hepatology May 11, 2026; NCT04365868): significant variceal reduction (per-protocol), >50% Pro-C3 reduction, ELF improvement, portal hypertension risk improved (Baveno VII); best at ELF >11.3
**Both were already in our files, filed separately, never connected.** Gianna has portal hypertension with variceal risk.

### sGC — the second cGMP route
Runcaciguat (sGC activator) shows renoprotection in preclinical CKD. Agonist antibody to NPR1 published Nature 633:654-661 (2024). Portal hypertension features reduced intrahepatic NO → connects to our open **SEMA4D/LSEC eNOS** question to Gracia-Sancho.

### NEW CONTACTS
- **Ikeda, Yasuhiro** — ikeda.yasuhiro@mayo.edu ✅ VERIFIED — corresponding author
- **Cataliotti, Alessandro** — Mayo Cardiorenal — **THE BRIDGE**: co-author on BOTH the ARPKD BNP paper AND MANP clinical program
- **Burnett, John C. Jr.** — Mayo Cardiorenal — world leader, designer natriuretic peptides; cenderitide/MANP

---

## 📧 HARRIS THREAD — REVIEWED Sep 16, 2026 (full email string read)

**⚠️ PERMISSION DATE CORRECTED:** granted **Sep 2**, not Sep 3. The Sep 3 *"Yes, thank you!"* was acknowledgment of the in-trans update, not the permission.

**⚠️ PERMISSION IS CONDITIONAL — exact wording (Sep 2, 2026):**
> *"You could mention this but please say it is research evaluation. Using the clinical guidelines, it would likely be scored as a variant of uncertain significance (VUS)."*

**Binding requirement:** every published reference to Mayo's Met3642Ile view must say (a) **research evaluation** and (b) **remains a VUS under clinical ACMG guidelines**. Both halves. Index.html already complies; **session-start skill was non-compliant and has been corrected Sep 16.**

**His Aug 28 wording, verbatim:** *"we have seen this variant as the likely second pathogenic change in one family we have analyzed and there is also support in the literature of its pathogenicity, so we do consider it a likely pathogenic change."*

**Reply pattern learned from the thread:**
- Replies are very short — "Yes, thank you!" / "Sounds great!" The ONE substantive reply came to the longest, most specific email. **Specificity earns answers; brevity in our email does not.**
- He states his limits plainly: declined SPTAN1 (*"I am not an expert in SPTAN1 and the pathways it is associated with"*) while fully answering the variant question. **Ask him PKD genetics/variants; expect redirection outside that.**
- He volunteers people unprompted (offered Christian Hanna).
- **The thread is closed** — his Sep 3 reply was terminal. A new email needs its own reason, which the BNP paper supplies.

---

## 🔬 GAP-CLOSING RESEARCH SESSION — September 16, 2026 (v7.8)

Every gap named on Sep 15 was researched directly. Six findings. One inverts a hypothesis. One is already proven in the PCK rat.

### ⭐⭐⭐ 1. "Amplify Failing Compensation" IS ALREADY PROVEN IN THE PCK RAT
**Holditch SJ, Schreiber CA, HARRIS PC, LARUSSO NF, Ramirez-Alvarado M, Cataliotti A, TORRES VE, Ikeda Y. Kidney Int 92(3):657-668, 2017. DOI: 10.1016/j.kint.2017.02.017. PMID: 28416225. Free PMC5557687.**
AAV9-BNP (B-type natriuretic peptide, guanylyl cyclase A agonist → cGMP; anti-fibrotic, anti-hypertensive, vasopressin-suppressive) in the **PCK rat**: reduced kidney weight, renal cystic index, fibrosis, **AND suppressed hepatic cystogenesis**. In vitro: ↓cystic epithelial proliferation, ↓fibrotic gene expression, ↑intracellular Ca²⁺. No toxicity; luciferase-AAV9 control showed no benefit.
- **Validates Principle 3 directly in the correct model** — supplementing a vasodilatory peptide, not blocking anything
- **One of very few interventions with SIMULTANEOUS renal + hepatic benefit in a PKHD1 model**
- **Harris and LaRusso are BOTH already in our network with active correspondence**
- **Torres (Mayo PKD Center director, TEMPO/tolvaptan PI) is a co-author — NEW contact via Harris**
- In the literature since 2017; absent from our framework
- **Boundary on Organ Divergence:** BNP helped both organs → divergence appears at intracellular signaling nodes (AMPK, STAT3), convergence at vascular/hemodynamic ones
- **New questions:** Has BNP been measured in ARPKD-CHF? Is **sacubitril/valsartan** (raises endogenous BNP via neprilysin inhibition, already used in pediatric heart failure) a repurposing candidate?

### ⚠️ 2. PRINCIPLE 2 INVERTED — peribiliary plexus is HYPERTROPHIED, not lost
- **de Lédinghen V et al. J Gastroenterol Hepatol 13:720-724, 1998.** CHF/DPM explant: **paucity of portal vein branches + HYPERTROPHY of the peribiliary vascular plexus.** Described as an indirect diagnostic argument for CHF.
- **Vet Pathol 2015, DOI 10.1177/0300985815610567 (comparative DPM):** compensatory hepatic ARTERIAL response → arterial twigs, vascular coiling, thickened mural smooth muscle → **"prolific stout arterioles interdigitating with juvenile ductal elements in DPM portal tracts."** Presinusoidal PHT initiates **adaptive perfusion through the arterial peribiliary plexus.**
- **CORRECTED PRINCIPLE 2:** ARPKD-CHF = portal venous paucity + compensatory hepatic arterial hypertrophy. NOT peribiliary vascular loss.
- **⭐ THIS STRENGTHENS THE ASSEMBLY:** hepatic arterial supply to ARPKD bile ducts is **ENLARGED**; portal supply **REDUCED**. Arterial delivery doubly advantaged. Arteries are physically woven through the malformed ducts.
- Retained: VEGF-A/NRP1/adrenomedullin question in cholangiocytes still open, but predicted direction is now **arterial remodeling/angiogenesis**, not endothelial dropout.

### ⭐⭐ 3. HEPATIC ARTERY ARGUMENT PUBLISHED INDEPENDENTLY — prompted by a death
**Salemdawod A, Walczak P, Janowski M. Mol Ther Nucleic Acids, Dec 2025. DOI: 10.1016/j.omtn.2025.102782. PMID: 41431698. Univ. Maryland School of Medicine.**
- **Intellia MAGNITUDE Phase 3 participant DIED** after IV LNP-CRISPR (nex-z, TTR amyloidosis) — grade 4 liver enzymes, ↑bilirubin. **FDA clinical hold on MAGNITUDE + MAGNITUDE-2 IND, October 29, 2025.** >650 patients enrolled.
- Toxicity mechanism: **ionizable lipids accumulate in LIVER SINUSOIDAL ENDOTHELIAL CELLS** → neutrophil cytokines → neutrophilic inflammation. Biodegradable LNPs blunt but do not abolish.
- Argument: IV = whole organ bathed simultaneously, no hepatic reserve. Hepatic artery infusion = regional, iterative, fractionated, adaptive dosing, decades of IR experience (HAIC, TACE, HA infusion pumps).
- **⚠️⚠️ SAFETY FOR GIANNA: our framework already documents LSEC capillarization in ARPKD-CHF. She has abnormal LSECs, elevated transaminases, portal HTN and thrombocytopenia BEFORE any therapy. The patient who died had none of those. Systemic IV LNP-CRISPR may carry materially higher risk in ARPKD-CHF. Hepatic arterial fractionated delivery may be a prerequisite, not a refinement.**
- Precedent: PBAE nanoparticles intra-arterial > IV for hepatic transfection in orthotopic rat model (PMID 37197026, Johns Hopkins); LDL nanoparticles via implanted HA port-catheter in rats (PMC9730405).
- **NEW CONTACTS: Janowski + Walczak, Univ. Maryland — SAME INSTITUTION AS QIAN AND OUTEDA (both permission granted). Possible warm intra-institutional route.**

### ⭐⭐ 4. αvβ6-TARGETED NANOPARTICLES TO BILIARY EPITHELIUM ALREADY EXIST
**Our Sep 15 claim that this "does not exist anywhere" was WRONG. Better news than being right.**
- **Ligand = A20FMDV2**, 20-mer from FMDV VP1 coat protein. Kd ~50 nM, selective for αvβ6 vs other integrins. Used in **human PET imaging**; preclinical safety demonstrated; used for αvβ6-specific drug delivery and αvβ6 CAR-T. Limitation: poor serum stability — cyclized/PEGylated variants engineered (PMC8138772, PMC8849274).
- **⭐ KEY PAPER (PMC12268842):** A20FMDV2-modified liposomes **targeted integrin αvβ6 on BILIARY EPITHELIAL CELLS** in a rat intrahepatic cholestasis of pregnancy model; improved stillbirth rates and liver function vs free drug; acted via mitochondrial function and bile metabolism.
- Conjugation chemistry published (DSPE-PEG2000-maleimide); no change to liposome size/PDI/zeta potential (PMC5488751).
- **STILL MISSING:** αvβ6 nanoparticles carrying **gene therapy cargo**, via **hepatic artery**, in an **ARPKD/PKHD1 model**. Assembly is narrower AND closer than we thought.
- **NEW CONTACT: John F. Marshall, Barts Cancer Institute QMUL — developed A20FMDV2. Cold contact appropriate.**

### ✅ 5. ADRENOMEDULLIN CONFIRMED ELEVATED IN NON-CIRRHOTIC PORTAL HYPERTENSION
**Tahan V et al. World J Gastroenterol 9(10):2325-2327, 2003. PMID: 14562402.**
NCPH **236 ± 61.4 pg/mL** vs healthy **84.1 ± 31.5** (p<0.0001) — ~3× elevated. Higher than compensated cirrhosis (108.4). Correlates with NO (r=0.827, p<0.0001).
**ARPKD-CHF is presinusoidal NON-cirrhotic portal hypertension = the NCPH group exactly.** Chandler's finding and the hepatology literature describe the same biology in two organs. **Still never measured in ARPKD-CHF.** Tier 1 action, now testable rather than exploratory.

### 6. RETROGRADE BILIARY DELIVERY IS WEAK — HEPATIC ARTERY SUPERSEDES ERCP
Retrograde bile duct infusion reaches the hepatic lobule and shows remarkable canalicular tight junction permeability, but transfects only **~1% of hepatocytes** (Fabre JW, KCL; PMC1774706). Combined with Findings 2+3, **hepatic artery now supersedes ERCP as the preferred biliary delivery route in this framework.** ERCP also carries cholangitis risk in an abnormal biliary tree.
Also: J Transl Genet Genom 2026 (DOI 10.20517/jtgg.2026.36) names **cholangiocytes as an unsolved LNP targeting population** — which is exactly what A20FMDV2 addresses.

### 📋 REVISED ASSEMBLY SCORECARD
| Component | Sep 15 | Sep 16 |
|---|---|---|
| Nanocomplex platform | Hart αvβ3 published | Unchanged + A20FMDV2 conjugation published |
| αvβ6 biliary targeting | Hypothetical | ✅ **DONE in vivo (ICP rat)** |
| Hepatic artery delivery | Our inference | ✅ **Published Dec 2025 after a patient death** |
| Arterial access in ARPKD | Assumed normal | ⭐ **BETTER than normal — hypertrophied** |
| Restoration cargo | Concept only | ⭐ **BNP PROVEN in PCK rat (Harris/LaRusso/Torres)** |
| Correction cargo | Krappitz ABE/CBE | Unchanged — IV LNP now has a death + FDA hold |

### 🔴 REVISED TIER 1 ACTIONS
1. **⭐ FIRST EMAIL — Harris, about the BNP paper.** ⚠️ **FRAME AS "is this axis still viable?" NOT "why was it abandoned."** Harris is a MIDDLE author on Holditch et al. 2017; senior author is **Yasuhiro Ikeda** (AAV gene therapy, Mayo) and **Cataliotti** is the natriuretic peptide expert. Harris likely contributed PKD/PCK rat expertise, not the therapeutic program — asking why it stopped risks an SPTAN1-style decline (*"I am not an expert in..."*). Ask what he CAN answer and let him redirect; he volunteers people readily (offered Hanna unprompted). CC Hanna. Draft:
   > A question about a paper you co-authored — Holditch et al., Kidney International 2017, where AAV9-BNP reduced renal cystic burden and suppressed hepatic cystogenesis in the PCK rat. It is one of very few interventions we have found with benefit in both the kidney and the liver in a PKHD1 model, which matters to us because our daughter's dominant disease is hepatic. Is the guanylyl cyclase A / cGMP axis still something you would consider a viable direction in ARPKD?
2. **LaRusso** — same question, hepatology side. Send 1–2 days later so it doesn't read as a blast.
3. **Ikeda (Mayo)** — the actual senior author. If Harris redirects, this is where. Was AAV9-BNP ever tested in a liver-predominant PKHD1 context?
4. **Torres (Mayo)** — third co-author, PKD Center director. Verify address on Mayo directory.
5. **Cataliotti (Mayo)** — natriuretic peptide expert. Does sacubitril/valsartan raise BNP enough to matter?
2. **Serum adrenomedullin AND serum BNP in ARPKD-CHF.** Both standard assays; BNP is routine cardiology. Neither ever measured.
3. **Ask Strazzabosco:** αvβ6 confirmed in HUMAN ARPKD-CHF liver? Aware A20FMDV2 liposomes reach biliary epithelium in vivo?
4. **Ask Krappitz:** does the Intellia death + FDA hold (Oct 29, 2025) change his view of IV LNP for a patient with pre-existing cholangiopathy and abnormal LSECs?

---

## PENDING ACTIONS

### 🔴 IMMEDIATE (not yet done)
- [ ] Push v7.5 files to GitHub (johnson7707.github.io/arpkd-research)
- [ ] Send Liebau thank-you (drafted Sep 14)
- [ ] Send Krappitz reply-all: correction + registry template + permission request (drafted Sep 14)
- [ ] Send Freedman follow-up (drafted Sep 14)

### SEP 25 EMAIL CLUSTER
| Researcher | One Question | Notes |
|---|---|---|
| **Long** | Your KRUK award describes "inhibiting AMPK" to modulate ARPKD — Walker 2023 shows ICD15 drives AMPK activation as the disease-suppressive signal. Could you help us understand how inhibition fits that framework? (Has AMPK modulation also been tested in biliary/hepatic ARPKD cells?) | Reference his £208K KRUK AMPK award title directly — "Inhibiting AMP-activated protein kinase" — do NOT say "activating"; the contradiction IS the question |
| **LaRusso** | Returned Sep 15. Reference: (1) Cai/Tacke cholangiokines review Table 1 he reviewed; (2) his NF-Y/TGFβ1 AJP-GI 2025 paper. Is NF-Y activated in PKHD1-deficient cholangiocytes? | One question only |
| **Morizane** | Does SPTAN1/RAC1 pathway operate in biliary epithelial cells (not just renal CNT cells)? | Follow-up from Kuraoka/Adv Sci 2026 |
| **Krappitz** | ⚠️ **QUESTION REPLACED Sep 16** (old CBE question was based on an error — both variants are ABE substrates). New question: does the Intellia MAGNITUDE death and FDA clinical hold (Oct 29, 2025) change his view of IV LNP delivery for a patient with pre-existing cholangiopathy and abnormal LSECs? | The LNP toxicity mechanism is LSEC accumulation; ARPKD-CHF children have abnormal LSECs at baseline |
| **Chaudhuri** | EFHD2 in cholangiocytes follow-up (permission granted Sep 14) | |
| **Gonzalez** (gonzalef@mail.nih.gov) | Linafexor = CS0159; NCT07282353 | |
| **Strazzabosco** | Dual macrophage blockade: CX3CL1/CX3CR1 + CXCL10/CXCR3 combined — untested in ARPKD | |
| **Gores** | Approach through LaRusso — not cold | |

### NEXT CCHMC VISIT (ask Miethke)
- Serum MMP7 (is the TGF-β1/MMP7 loop already running?)
- Is Gianna on UDCA?
- Losartan — appropriate given PHT + loop-breaking rationale?

### NOV 27, 2026
- Saroglitazar PDUFA — if FDA approves, discuss off-label at CCHMC

### TAKA DEADLINE
- **October 19, 2026** (Kidney Research UK) — SEPARATE from Long's confirmed £208K AMPK grant (Oct 2025 KRUK Paediatric & Rare round) and his separate £125K diet/PKD PhD studentship (March 2026 PKD round)

---

## NEW CONTACTS ADDED THIS SESSION

| Researcher | Institution | Email | Status | Why |
|---|---|---|---|---|
| Chandler, Jennifer | UCL GOS ICH | UCL GOS ICH directory | NEW · warm via Long (supervisor) · do NOT cold-contact before Long Sep 25 | AAV FPC fragment restoration; PKDisospheroids (Jasmine Kaur); Long's former trainee; KRUK fellowship £206,219 (glomerular/WT1, Jan 2022); KRUK PKD grant £99K (corrected from £98K — official awards page) "Evaluating gene therapy for childhood polycystic kidney disease in a 3D human cellular model" (March 2026 round); Oct 2024 J Pathology adrenomedullin/WT1 paper; PhD student Emily Moore (adrenomedullin arm) |
| Malik, Saif | UCL GOS ICH | UCL GOS ICH directory | NEW · noted · Long group · CO-AUTHOR Sci Transl Med Aug 2026 | Co-first author Malik/Chandler/Long Sci Transl Med 18:862 (2026) DOI: 10.1126/scitranslmed.adv1289 — angiopoietin-1 RNA therapy via lipid nanocomplexes + ultrasound-guided renal artery delivery for WT1 glomerular disease; confirmed lipid-based kidney delivery feasibility |
| Li, Xiaogang PhD | Mayo Clinic, Dept Biochemistry & Molecular Biology | li.xiaogang@mayo.edu | NEW · approach via Harris ONLY | ABE9 first kidney base editing; Ksp organ-specific promoter; LNP = next step (stated in paper) |

| **Hart, Stephen L.** ⭐ | UCL GOS ICH — Genetics & Genomic Medicine | UCL directory | **🆕 HIGHEST-VALUE NEW CONTACT · route via GISSEN, not Long** | Built the αvβ3-targeted nanocomplex platform (Sci Transl Med 2026). Key Q: can ligand be swapped αvβ3→αvβ6 for biliary targeting? |
| **Kalber, Tammy L.** | UCL Centre for Advanced Biomedical Imaging | UCL CABI directory | 🆕 NEW · via Hart/Gissen | Ultrasound-guided renal artery injection. Q: applied to hepatic artery? |
| **Ruhrberg, Christiana** | UCL Institute of Ophthalmology | UCL directory | 🆕 NEW · noted | World NRP1 authority; co-author Jafree Cell Reports 2026; links Chandler's NRP1 finding to our SEMA4D question |
| **Russell, Lauren G.** | UCL GOS ICH (Long group) | UCL directory | 🆕 NEW · noted | Co-first author Cell Reports 2026; on 3 of 4 major Long papers; operational linchpin |

**Network total: v7.8 (75 researchers — Sep 15: Hart, Kalber, Ruhrberg, Russell added, Jafree upgraded to cold-contact-appropriate. Sep 16: Torres, Marshall, Janowski, Walczak added.)**

---

## CRITICAL STANDING RULES

- **FIRST-NAME RULE**: Never use first names in researcher emails
- **ONE QUESTION PER EMAIL**
- **30-DAY RULE** between contacts
- **PERMISSION RULE**: Nothing from Krappitz Sep 11 email in documents until explicit permission
- **AAV CONTRAINDICATED** for Gianna (cholangiopathy — Krappitz Sep 11)
- **BOTH variants are ABE substrates** (c.9370C→T and c.10926G→A) — corrected Sep 16, 2026; the prior "His3124Tyr = CBE" rule was wrong
- **LNP delivery = correct direction** for Gianna (not AAV)
- HRFD: Jasmine Jaber jaberj2@chop.edu · 267-425-5325 · ON HOLD
- Krappitz gate: Liu DR (Harvard) — do NOT cold-email
- Approach Chandler ONLY through Long
- Approach Li (Xiaogang) ONLY through Harris

---

## KEY PIPELINE ITEMS TO ADD TO INDEX (next session)

Three items from PKD Cure Tracker not yet added to documents:

1. **Farabursen (CYX082)** — Novartis anti-miR-17, Phase 3 registrational imminent. Phase 1b: htTKV halted (0.05% vs 2.58% placebo). Novartis acquired Regulus $1.7B Jun 2025. Open question: does miR-17 suppress PKHD1/FPC?

2. **VX-407** — Vertex Pharmaceuticals. Phase 2 active, AGLOW trial, 26 participants. Oral PKD1 modulator/corrector for specific variants. Same precision approach as CFTR modulators. Primary completion July 2027. NCT07161037.

3. **PYC-003** — PYC Therapeutics (Australia). Phase 1 recruiting. Peptide-PMO antisense targeting PKD1 mutations. 166 participants. NCT06714006. Direct analogue to Liebau's ASO for PKHD1.

4. **BEAT-PKD start date corrected**: September 2026 (pushed from July). NCT07282821.

---

## ICD15 → AMPK → CDK1 RESEARCH TRIANGLE (confirmed Sep 15) — ⚠️ DIRECTION DISCREPANCY ADDED

**Walker (Sheffield)** → characterized ICD15 mechanism (FPC C-terminal → mitochondria → AMPK ACTIVATION suppresses cysts, Nat Commun 2023) + ciliary FPC/PC2 co-operation (KRUK 2024, £240K)
**Long (UCL GOS ICH)** → **CORRECTED: £208K** (not £200K) Oct 2025 KRUK Paediatric & Rare round. Official title: **"Inhibiting AMP-activated protein kinase to modulate Autosomal Recessive Polycystic Kidney Disease"** — June 2026 KRUK news article described it as cyst energy metabolism; OFFICIAL AWARD SAYS INHIBITING AMPK.
**Chandler (UCL GOS ICH, Long trainee)** → testing AAV FPC fragment delivery in human ARPKD kidney cells (KRUK March 2026 PKD round, **£99K** corrected from £98K). Official title: "Evaluating gene therapy for childhood polycystic kidney disease in a 3D human cellular model"
**Missing experiment**: AAV-ICD15 disease suppression test in Pkhd1 mice (analogous to Caplan/Onuchic PC1 fragment)
**Missing experiment**: Long's AMPK work in biliary/hepatic ARPKD cells (not just renal)

### 🚨 CRITICAL MECHANISTIC DISCREPANCY — MUST RAISE WITH LONG SEP 25
Walker 2023: FPC → ICD15 → mitochondria → AMPK **ACTIVATION** → suppresses cysts.
Long 2026 KRUK award: **INHIBITING** AMPK modulates ARPKD.
These are contradictory unless AMPK has a biphasic role (different isoforms, different cell types, or different disease stages). Possible explanations: (1) Walker shows activation is protective in FPC-replete cells; (2) Long may be testing whether chronic AMPK hyperactivation in FPC-deficient cells becomes maladaptive; (3) different AMPK subunit composition in collecting duct vs. biliary epithelium. This discrepancy is the single most important scientific question to raise in the Long Sep 25 email — MORE IMPORTANT than the biliary extension question previously planned.

---

## DELIVERY HIERARCHY (current)

| Approach | Status | ARPKD-CHF utility |
|---|---|---|
| LNP-ABE (Liu ZSD precedent) | 27%→53% liver; selective advantage | Hepatocyte-predominant; liver → biliary indirect benefit |
| LNP + HNF1β promoter-ABE9 | THEORETICAL — never done | Biliary-specific editing; zero published precedent |
| MAL-lectin LNP (α2,3-sialic acid targeting) | THEORETICAL | Disease-specific cholangiocyte tropism via Cebotaru's mechanism |
| CBE-VLP4 (Zhu/ShanghaiTech) | 46-64% liver, zero off-target | ⚠️ NOT needed for Gianna — both her variants are ABE substrates (corrected Sep 16). Retained as a general platform of interest only |
| AAV1-CFTR transcomplementation (Cebotaru) | Proven in Pkhd1 mice | Biliary cyst reduction; AAV generally contraindicated for Gianna |
| HITI + LNP (Ginn + Abe/Kimura) | Mutation-agnostic | Needs cholangiocyte targeting |
| Chandler AAV-FPC fragment (UCL) | Phase: human ARPKD kidney cells; £99K KRUK March 2026; PKDisospheroids model | Kidney; biliary extension not started |
| Malik/Chandler/Long lipid nanocomplexes + renal artery (UCL) | Sci Transl Med 2026 — proven in WT1 glomerular disease preclinical models | Glomerular disease; angiopoietin-1 RNA; ultrasound-guided renal artery — first UK lipid nano delivery to kidney confirmed |
