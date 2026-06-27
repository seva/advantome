# Phase 0: What Is Unfair Advantage?

Date: 2026-06-26

Goal: define the target concept before applying it to genome research.

---

## Working Definition

An unfair advantage is an asymmetry that lets one actor get better results than comparable actors with less effort, lower cost, faster feedback, lower risk, or higher compounding.

It is not merely "something useful." It has to be asymmetric.

---

## General Criteria (for acquired asymmetries)

An advantage is unfair when it has most of these properties:

1. **Valuable**: improves a meaningful outcome.
2. **Rare or underused**: not widely held or not widely exploited by the relevant comparison group.
3. **Hard to copy**: difficult to imitate because of timing, context, tacit knowledge, relationships, physiology, capital, credibility, or accumulated practice.
4. **Exploitable**: the person can actually use it.
5. **Compounding**: produces increasing returns through repeated use.
6. **Context-fit**: matters in the arena being played.
7. **Legible enough to act on**: can be converted into choices, systems, positioning, or experiments.

These criteria were designed for acquired asymmetries (skills, networks, capital, position). They describe edges you *build*. They do not cleanly map to genome-derived asymmetries, which are physiologically *endowed* — present at birth, non-replicable, lifelong.

---

## Genome-Specific Asymmetry Framework

Genome-derived asymmetries are different in kind from acquired ones:

| Property | Acquired asymmetry | Genome-derived asymmetry |
|---|---|---|
| Source | Built over time | Inherited at conception |
| Rarity | Earned (hard to achieve) | Given (allele frequency) |
| Copyability | Copyable with effort | Biologically exclusive |
| Durability | Decays without maintenance | Lifelong, stable |
| Knowledge | Created by the action | Pre-exists, unlocked by discovery |

Because a genome-derived asymmetry *is the trait itself*, three general criteria become undiscriminating constants:

- **Rare** — every variant has a population frequency; all are definitionally rare compared to the global allele pool
- **Hard to copy** — no one can acquire your genome; biological exclusivity is absolute
- **Compounding** — all genome traits are lifelong; none degrade

The real discriminators for genome-derived asymmetries are:

### 1. Signal Integrity
Is the variant-trait association real and replicable? Single-SNP effects vary from well-characterized (CYP2C19 poor metabolizer, effect size: dramatic) to noisy and unreplicated (most GWAS associations, effect size: marginal). Integrity is a function of:
- Replication in independent cohorts
- Functional validation (mechanism known, not just statistical)
- Consistent effect direction across populations

### 2. Actionability Without Gatekeeper
Can the asymmetry be exploited *by you alone*, without requiring a physician, lab, institution, or permission? This is the critical filter. A variant predicting response to a prescription drug requires a doctor — you cannot act unilaterally. A variant affecting nutrient metabolism, exercise response, or sleep physiology can be acted on directly. Gatekeeper dependency is a structural weakness: you don't control the lever.

### 3. Measurement Redundancy
Could the same edge be discovered cheaper, faster, or more accurately by a non-genetic measurement? If a blood test, questionnaire, or wearable gives you the same information, the genome-derived asymmetry is redundant. Examples:
- **Direct**: Cholesterol panel tells you cardiovascular risk more accurately than PRS. Genome adds nothing.
- **Non-redundant**: CYP2C19 metabolizer status cannot be inferred from any blood panel. Genome is the only path.

### 4. Effect Size
How much does this variant actually change the outcome for you? Effect size determines whether the asymmetry is strategic or trivial:
- **Large** (odds ratio > 3, or deterministic): actionable asymmetry — knowing changes the decision
- **Moderate** (OR 1.5–3): marginal edge, may justify action depending on context
- **Small** (OR < 1.5): probabilistic noise that disappears at the individual level

### 5. Net Benefit
Does the value of knowing exceed the total cost? Costs include:
- Privacy risk (data permanence, insurance discrimination, re-identification)
- Anxiety burden (false positives, uncertain results, VUS)
- Action cost (time, money, opportunity cost of acting on a wrong signal)
- False positive risk (acting on a variant that turns out not to matter)

---

## What Is Not A Genome-Derived Unfair Advantage

- A trait with no action path (most common variants)
- An effect that can be measured directly and more cheaply
- A risk estimate with 95% CI crossing 1.0
- A result requiring a third-party gatekeeper you do not control
- A finding whose net cost exceeds its net benefit

---

## Genome Asymmetry Types

| Type | Signal integrity | Gatekeeper | Measurement redundancy | Effect size | Net benefit |
|---|---|---|---|---|---|
| **Pharmacogenomics** | High (CPIC Level A/B) | Yes (prescriber) | Non-redundant | Large (dose changes, ADR avoidance) | Strong for high-evidence pairs |
| **Mendelian / monogenic** | High (ACMG SF v3.2) | Probably (confirmatory testing) | Non-redundant | Very large (near-deterministic) | Depends on condition actionability |
| **Polygenic risk score** | Moderate | Yes (physician) | Partially redundant (overlaps clinical risk factors) | Small to moderate (AUC 0.6–0.7) | Marginal outside high prior probability |
| **Carrier status** | High | No (reproductive decision is personal) | Non-redundant | Near-deterministic for offspring | Strong but window-limited |
| **Trait / wellness** | Low to moderate | No | Redundant for most (observable without genetics) | Small to none | Weak |
| **Ancestry** | High | No | Redundant with family records for recent, genome-exclusive for deep | Not a health outcome | Identity value only |

---

## RAROC 2x2 For Genome Asymmetries

Axes:
- X-axis: actionability (can you exploit it yourself)
- Y-axis: effect size (how much it changes outcomes)

### High Effect / High Actionability

Best targets. The asymmetry is real, large, and you control the lever.

- Carrier status (reproductive decisions)
- Select PGx where self-action is possible (e.g., knowing CYP1A2 caffeine metabolizer status affects your own caffeine consumption without a prescriber)
- Monogenic traits with behavioral action paths (e.g., hereditary hemochromatosis — donate blood)

### High Effect / Low Actionability

Potent but constrained. You need a gatekeeper. Worth pursuing only if the gatekeeper path is reliable.

- Most PGx (CYP2C19-clopidogrel, TPMT-thiopurines, SLCO1B1-statins)
- ACMG secondary findings requiring clinical confirmation
- Pharmacogenomics where prescriber adoption is low

### Low Effect / High Actionability

Tactical edges. You control the action, but the payoff is small.

- Caffeine metabolism (CYP1A2)
- Lactose tolerance (LCT)
- Alcohol flush (ALDH2)
- Most wellness/nutrigenetics

### Low Effect / Low Actionability

Ignore.

- Most polygenic risk scores at the individual level
- Unreplicated GWAS associations
- Traits with no known action path

---

## Selecting a Target

For this project, the target genome asymmetry must pass:

1. **Signal integrity** — is the trait real and replicable?
2. **Non-redundant** — can this edge only be discovered via genome?
3. **Effect large enough** — does knowing change the decision?
4. **Net benefit positive** — does the value exceed the cost?
5. **Honest framing** — no overclaiming, no probabilistic noise sold as certainty

Criteria 1–4 are gates. Criterion 5 is a standing constraint on how the asymmetry is communicated.

---

## Ethical Boundary

"Unfair" can mean either:

- **Strategically asymmetric**: legal, ethical, and based on real genetic variation that others happen not to have or not to know about.
- **Procedurally unfair**: based on deception, privileged non-public access, coercion, or rule-breaking.

Advantome should target the first and reject the second.

---

## Sources

- Competitive advantage overview: https://en.wikipedia.org/wiki/Competitive_advantage
- Resource-based view and VRIN criteria: https://en.wikipedia.org/wiki/Resource-based_view
- VRIO framework: https://en.wikipedia.org/wiki/VRIO
- Core competency: https://en.wikipedia.org/wiki/Core_competency
- CPIC guidelines: https://cpicpgx.org/guidelines/
- ACMG secondary findings v3.2: https://www.acmg.net/
- FDA direct-to-consumer genetic test limitations: https://www.fda.gov/medical-devices/in-vitro-diagnostics/direct-consumer-tests
