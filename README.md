# Laboratory Procedure for the Production and Quantification of PHB in *Cupriavidus necator*

**Biotechnology Research Internship — Week 2: Laboratory Methodologies and Data Collection Simulation**
**Rabi Narayan Patra** | 10 October 2026

A complete, SOP-style laboratory procedure for a mock experiment: producing polyhydroxybutyrate (PHB) in
*Cupriavidus necator* on a volatile fatty acid feed, and quantifying it to an absolute titre. It continues
directly from the Week 1 experimental design.

## The five procedure parts

| Part | What it covers | Output |
|---|---|---|
| **A** | Cryostock revival and two-stage preculture | A reproducible, physiologically uniform inoculum |
| **B** | Shake-flask cultivation and timed sampling | A growth and accumulation profile over 48 h |
| **C** | Harvest, lyophilisation and gravimetric cell dry weight | The mass denominator for every titre |
| **D** | Acidic methanolysis and GC-FID quantification | Absolute PHB mass per sample |
| **E** | Nile red flow cytometry | An independent, chloroform-free cross-check |

Every step is stated with its reagent quantities, equipment settings and timing, and **each part ends in a gate**
that must pass before the next begins.

## Three design decisions that carry the weight

**A two-stage preculture.** A single preculture forces cells to adapt to liquid culture and to a mineral medium
at the same time, giving lag phases of 12–15 h instead of 3–4 h. Separating the two adaptations is what makes
the growth curve reproducible enough to schedule in advance.

**Orthogonal verification.** Parts D and E measure the same pellets by methods that share *no* chemical or
instrumental steps — different chemistry, different instrument, different failure modes. When two such methods
agree within 15%, the chance that both are wrong in the same direction is small. Where they disagree, the
discrepancy is treated as a finding to be explained, not a choice to be made.

**Pre-specified acceptance criteria.** The conditions for accepting a batch were fixed *before* the data
existed, so a result cannot be accommodated by adjusting the criteria afterwards.

## Safety

Every hazardous substance is classified by its **GHS hazard statements** — chloroform alone carries seven,
including H351 (suspected carcinogen) and H372 (organ damage on prolonged exposure) — and the standard
**hierarchy of controls** is applied in order: elimination, engineering, administrative, PPE.

The strongest control on the most hazardous step (100 °C acid methanolysis in chloroform and methanol) is not
a glove or a fume hood but the fact that a **chloroform-free method runs in parallel**, so the hazardous route
is never the only route to an answer.

## Data collection and quality control

- **10 quantities** recorded, each paired with its instrument and its form (Figure 4)
- **7 controls** run with every batch: reagent blank, matrix blank, internal standard, duplicate, spike
  recovery, sterility control, instrument checks
- **A worked calculation chain** from raw peak areas to a reported titre, showing that every figure depends on
  three independently gated quantities
- **A carbon-balance check** that is independent of both analytical methods — the strongest single check
  available, because it tests whether the process is understood rather than merely whether the instruments work
- **11 troubleshooting entries**, each pairing a symptom with the specific cause it most likely indicates

## Repository contents

```
├── README.md
├── Laboratory_Procedure_and_Data_Collection_Biotech.docx   # the document (21 pages, ~6,120 words)
├── Laboratory_Procedure_and_Data_Collection_Biotech.pdf
├── references.md                                           # the 14 sources
└── figures/                                                # all five figures
```

**In the v1.0 release bundle:** the document in both formats, all five figures, and the figure-generation script.

## A note on the file format

The task specifies a PDF; the portal's upload box accepts **Word only**. Both are provided — upload the `.docx`
to the portal; the `.pdf` is identical in content.

## Author

**Rabi Narayan Patra** — Biotechnology Research Intern, 2026.
GitHub: [@rabinarayanpatra350-biotech](https://github.com/rabinarayanpatra350-biotech)
