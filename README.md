## **Weight-Loss Misinformation Dashboard (2019–2025)**

This repository contains a **standalone, reproducible dashboard** analyzing fact-checked misinformation related to weight-loss interventions from **2019 to 2025**, with a focus on:

- **GLP-1 therapies** (e.g., Ozempic, semaglutide, Wegovy)
- **Unregulated weight-loss supplements and products**

The analysis uses **ClaimReview data retrieved via the Google Fact Check Tools API** and applies a narrative taxonomy to identify **fraud-oriented misinformation patterns** across regulatory contexts.

**Why This Project Matters**

Public discourse often treats weight-loss misinformation as a problem of scientific misunderstanding.

Our findings suggest a different mechanism:

> **As products move away from regulatory oversight, misinformation becomes more overt, commercial, and fraud-oriented.**

Rather than confusion about approved medications, misinformation clusters around:
- Counterfeit or compounded products
- Fake regulatory approvals
- Fabricated experts and endorsements
- Miracle supplement and “natural alternative” claims

This dashboard reframes weight-loss misinformation as a **commercial fraud surveillance problem**, not only a belief-correction challenge.

**What This Dashboard Shows**

- **Normalized fact-check ratings** (true, false, misleading, other)
- **Top fraud narratives** among false claims
- **Side-by-side comparison** of:
  - Regulated GLP-1 therapies
  - Unregulated supplement ecosystems
- **Searchable table** of fact-checked claims with source links

All outputs are derived from **fact-checked content**, not raw social media posts.

**Data Source**

- **Google Fact Check Tools API** (ClaimReview schema)
- Fact-checking organizations include:
  - Snopes
  - FactCheck.org
  - Full Fact
  - Lead Stories
  - AAP FactCheck
  - USA Today (Verify)
  - Local Verify partners

**Timeframe:** January 1, 2019 – December 31, 2025

**Methodological Notes**

- Each row represents a **ClaimReview entry**, not exposure or prevalence.
- Claims are filtered by date using `claimDate` when available, otherwise `reviewDate`.
- Narrative tags are assigned using a **rule-based taxonomy** applied to:
  - Claim text
  - Review titles
  - Fact-check ratings
- This project does **not** estimate misinformation reach or audience size.

## Citation: Data source: Google Fact Check Tools API, ClaimReview
Analysis & visualization: Akshaya Bhagavathula, 2026

