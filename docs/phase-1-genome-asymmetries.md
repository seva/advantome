# Phase 1: Genome-Derived Asymmetries — Catalog and Selection

Date: 2026-06-26

Goal: catalog genome-derived actionable signal classes, filter against Phase 0 unfair advantage criteria, and select one to pursue.

---

## Signal Catalog

### 1. Pharmacogenomics (PGx)

| Property | Assessment |
|---|---|
| **Mechanism** | Gene variants affecting drug metabolism, transport, and target receptors. Well-characterized in CYP450 family (CYP2C19, CYP2D6, CYP3A5), TPMT, NUDT15, SLCO1B1, VKORC1, etc. |
| **Evidence quality** | Strong. CPIC guidelines for 19 genes affecting 47+ drugs. FDA label includes PGx info for ~400 drugs. Multiple consortia (CPIC, DPWG) publish actionability tiers. |
| **Population data** | ~99% of individuals carry at least one actionable PGx variant. 42% carry more than 2. But most data from European populations; effect sizes and allele frequencies differ substantially in other ancestries. |
| **DTC availability** | Yes — 23andMe offers PGx reports (CYP2C19, CYP2D6, etc.). Growing segment of DTC market. Increasingly available through clinical labs. |
| **Key limitation** | Discordant recommendations between agencies. Clinical implementation lags evidence. Need for population-specific data. |

### 2. Polygenic Risk Scores (PRS)

| Property | Assessment |
|---|---|
| **Mechanism** | Aggregate effect of thousands of common variants (SNPs) on complex trait risk. |
| **Evidence quality** | Moderate and growing. AUC ~0.61 alone, ~0.70 with clinical factors. Strongest for cardiovascular disease, breast cancer, type 2 diabetes. 2025-2026 reviews show incremental clinical value emerging. |
| **Population data** | 91% of GWAS data from European ancestry. PRS overestimates risk in non-European populations. Multi-ancestry PRS improving but still limited. |
| **DTC availability** | Yes — 23andMe, MyHeritage, and others offer disease risk reports based on PRS. Growing. |
| **Key limitation** | Low discriminative power at individual level in general population. Poor portability across ancestries. Most useful as adjunct to clinical risk factors. |

### 3. Mendelian / Rare Disease Variants

| Property | Assessment |
|---|---|
| **Mechanism** | Single-gene variants causing monogenic disorders. ACMG recommends reporting 73+ secondary findings genes (v3.2). |
| **Evidence quality** | Very strong for known pathogenic variants. Diagnostic yield ~25% in rare disease cohorts via WGS. |
| **Population data** | ~2% of individuals carry an actionable ACMG secondary finding. Carrier rate for recessive conditions ~52% cumulative. |
| **DTC availability** | Limited. Clinical-grade sequencing required. Some DTC companies offer carrier screening panels. |
| **Key limitation** | Low prevalence for any single condition. Requires clinical-grade sequencing. Incidental findings create counseling burden. |

### 4. Expanded Carrier Screening (ECS)

| Property | Assessment |
|---|---|
| **Mechanism** | Screening for recessive and X-linked conditions for reproductive planning. |
| **Evidence quality** | Strong. ACOG-recognized. 76% of at-risk couples take action (IVF with PGT-M, prenatal diagnosis). Tay-Sachs screening reduced incidence by 90%. |
| **Population data** | Cumulative carrier rate ~52% across 176 conditions. At-risk couple rate ~1.1%. |
| **DTC availability** | Yes — many labs offer ECS panels. Growing. |
| **Key limitation** | Narrow actionability window (reproductive). Limited value outside family planning context. |

### 5. Ancestry / Genetic Genealogy

| Property | Assessment |
|---|---|
| **Mechanism** | Autosomal DNA, Y-chromosome, mtDNA analysis for population origin, relatedness, migration. |
| **Evidence quality** | Strong for population genetics. Well-validated reference panels. |
| **Population data** | Massive databases: Ancestry ~25M+ profiles, 23andMe ~15M+. Strong network effects. |
| **DTC availability** | Largest DTC segment. $1.04B market (2025), growing 8.5% CAGR. |
| **Key limitation** | Low clinical actionability. Entertainment/identity value. No compounding health utility. |

### 6. Epigenetic Age / Biological Age

| Property | Assessment |
|---|---|
| **Mechanism** | DNA methylation patterns at specific CpG sites → epigenetic clocks (Horvath, Hannum, PhenoAge, GrimAge). |
| **Evidence quality** | Emerging. Strong correlation with chronological age and some health outcomes. Reproducibility and clinical utility still debated. |
| **DTC availability** | Growing — TruDiagnostic, Infinite Epigenetics offering consumer tests. Epigenetics market $2.5B (2025), 11% CAGR. |
| **Key limitation** | Actionability unclear. Science still developing. Interpretation standards lacking. |

### 7. Nutrigenetics / Wellness Traits

| Property | Assessment |
|---|---|
| **Mechanism** | Gene variants affecting nutrient metabolism (MTHFR, FTO, APOE, etc.), food sensitivities, exercise response. |
| **Evidence quality** | Weak to moderate. Most single-gene nutrition claims poorly supported. Some validated associations (lactose intolerance, caffeine metabolism). |
| **DTC availability** | Broadly available. Many DTC companies include wellness reports. |
| **Key limitation** | Low actionability. Most claims lack clinical evidence. Weak differentiation from generic advice. |

---

## Filter Against Phase 0 Unfair Advantage Criteria

(Criteria: Valuable, Rare/underused, Hard to copy, Exploitable, Compounding, Context-fit, Legible)

| Signal class | Valuable | Rare | Hard copy | Exploitable | Compounding | Context-fit | Legible | Score |
|---|---|---|---|---|---|---|---|---|
| PGx | ++ | ++ | ++ | ++ | ++ | ++ | ++ | **14/14** |
| PRS | + | ++ | + | + | + | ++ | + | **9/14** |
| Mendelian/rare | ++ | ++ | + | + | + | + | ++ | **10/14** |
| Carrier screening | ++ | + | + | ++ | - | + | ++ | **9/14** |
| Ancestry | + | + | + | ++ | - | + | ++ | **8/14** |
| Epigenetic age | + | ++ | + | + | + | + | + | **8/14** |
| Nutrigenetics | + | + | - | + | - | + | + | **5/14** |

**Scoring:**
- `++` = strong fit (2 pts)
- `+` = moderate fit (1 pt)
- `-` = weak or no fit (0 pts)

---

## Selection: Pharmacogenomics (PGx)

PGx scores highest across all criteria. Rationale:

| Criterion | Why PGx fits |
|---|---|
| **Valuable** | Direct impact on drug efficacy and adverse event prevention. Adverse drug reactions are a leading cause of morbidity. |
| **Rare/underused** | Clinical PGx implementation remains <10% of prescribing decisions despite decades of evidence. Most patients are never genotyped. |
| **Hard to copy** | Requires: (a) knowledge of variant interpretation and CPIC guidelines, (b) ability to translate genotype into actionable prescribing guidance, (c) infrastructure to deliver insights at the point of care. Each layer is nontrivial. |
| **Exploitable** | Immediately actionable — the next time a relevant drug is prescribed, the PGx profile applies. No behavior change or lifestyle intervention required. |
| **Compounding** | As a person accumulates more prescriptions over a lifetime, the value of having their PGx profile grows. Each new drug-gene pair discovered adds to the existing knowledge base. |
| **Context-fit** | Precision medicine is accelerating. DTC genetic testing is a $2.3B and growing market. Consumers increasingly expect personalized health insights. |
| **Legible** | CPIC guidelines provide clear actionability tiers (strong, moderate, optional). Genotype → phenotype → recommendation is a well-defined pipeline. |

### Specific Asymmetry Target

Not "all PGx" — the initial target should be **drug-metabolizer phenotypes for the most clinically impactful gene-drug pairs**, specifically:

- **CYP2C19** — clopidogrel, PPIs, SSRIs, voriconazole
- **CYP2D6** — SSRIs, tricyclic antidepressants, tamoxifen, opioids
- **CYP3A5** — tacrolimus
- **TPMT / NUDT15** — thiopurines (azathioprine, 6-MP)
- **SLCO1B1** — statins (simvastatin)
- **VKORC1 / CYP2C9** — warfarin
- **ABCG2 / CYP2C9** — statin-related adverse events

These seven gene-drug groups cover the highest-evidence, most-actionable CPIC Level A/B pairs.

### Why Not the Others

| Rejected class | Reason |
|---|---|
| **PRS** | Individual-level discriminative power still too low for an unfair advantage. Useful as population screening tool but not as personal actionable intelligence. |
| **Mendelian/rare** | Low prevalence per variant. Requires clinical-grade WGS/WES. High-false-positive counseling burden. Better suited as a clinical service than a personal asymmetry platform. |
| **Carrier screening** | Narrow window of relevance (reproductive). Market is already served by established clinical labs. |
| **Ancestry** | Entertainment value, not health asymmetry. Low compounding. Already dominated by well-capitalized incumbents. |
| **Epigenetic age** | Science too immature. Actionability unproven. Risk of misleading consumers. |
| **Nutrigenetics** | Weak evidence base. Poor differentiation. Most claims cannot survive scrutiny. |

---

## Phase 2 Implications

- Need a PGx interpretation engine: translate raw genotype data (VCF/23andMe format) into metabolizer phenotypes and CPIC-guided recommendations
- Target input: raw genotype data from DTC providers (23andMe, AncestryDNA export) or clinical WGS/WES
- Output: actionable report with drug-specific guidance per CPIC levels
- Focus on interpretable, evidence-grounded output — no overclaiming

## Sources

- CPIC guidelines: https://cpicpgx.org/guidelines/
- PharmGKB: https://www.pharmgkb.org/
- Clinical implementation of polygenic risk scores (Kullo 2025): https://www.nature.com/articles/s41576-025-00900-8
- Opportunistic genomic screening clinical utility: https://www.gimjournal.org/article/S1098-3600(24)00257-0/fulltext
- Expanded carrier screening outcomes: https://www.gimjournal.org/article/S1098-3600(21)01493-3/fulltext
- DTC genetic testing market: https://www.polarismarketresearch.com/industry-analysis/direct-to-consumer-testing-market
- PGx in Chinese cohort: https://www.nature.com/articles/s41467-025-61644-x
- PGx variants in Indian clinical practice: https://pmc.ncbi.nlm.nih.gov/articles/PMC12286129/
- Consumer epigenomics ELSI: https://link.springer.com/article/10.1186/s43682-026-00044-8
