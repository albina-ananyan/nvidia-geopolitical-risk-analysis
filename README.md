# NVIDIA Geopolitical Risk Analysis

## Overview

This project evaluates NVIDIA Corporation's exposure to geopolitical and supply-chain risk arising from its dependence on Taiwan-based semiconductor manufacturing.

Using OECD Inter-Country Input-Output (ICIO) data, World Semiconductor Trade Statistics (WSTS) industry data, SEC filings, earnings call transcripts, SQL databases, and natural language processing (NLP) techniques, the analysis assesses whether NVIDIA's public disclosures accurately reflect the magnitude of its operational and geopolitical exposure.

The project combines macroeconomic supply-chain analysis with firm-level disclosure analysis to examine how geopolitical concentration translates into business risk.

---

## Research Question

**How does NVIDIA's reliance on Taiwan translate into financial and operational risk under potential geopolitical disruption scenarios?**

Specifically, the analysis evaluates:

* Taiwan's role in global semiconductor production
* Industry-wide concentration trends in semiconductor manufacturing
* NVIDIA's dependence on Taiwan-based suppliers such as TSMC
* Whether NVIDIA communicates these risks consistently across regulatory filings and investor-facing communications

---

## Key Findings

### 1. Taiwan Plays a Critical Role in Global Semiconductor Production

Analysis of OECD ICIO data shows that Taiwan accounted for approximately **7.23% of global semiconductor value-added in 2022**, despite representing a relatively small share of global GDP.

Taiwan's share has increased steadily over time, indicating growing geographic concentration within a strategically important industry.

### 2. Semiconductor Activity Is Becoming Increasingly Concentrated in Asia-Pacific

Analysis of WSTS semiconductor billings data shows that Asia-Pacific has experienced substantially faster growth than the Americas, Europe, and Japan.

This trend suggests that semiconductor production is becoming increasingly concentrated in a region exposed to geopolitical tensions and supply-chain disruption.

### 3. NVIDIA Formally Acknowledges Geopolitical Risk

Keyword analysis of NVIDIA's FY2026 Form 10-K identified extensive discussion of:

* Geopolitical risk
* China-related exposure
* Supply-chain dependencies
* Manufacturing concentration

The company's regulatory disclosures explicitly recognize these risks.

### 4. Investor Communication Places Less Emphasis on Risk

Comparison of NVIDIA's earnings call transcripts and SEC filings reveals a significant divergence in risk communication.

Risk-related terms appear frequently in formal filings but are largely absent from investor-facing earnings call discussions.

### 5. Earnings Calls Maintain a More Optimistic Tone

Sentiment analysis indicates that earnings call communications are substantially more positive than regulatory filings.

This suggests that NVIDIA communicates geopolitical risk differently depending on audience and communication context.

---

## Methodology

### Supply Chain Analysis

* OECD Inter-Country Input-Output (ICIO) Tables
* Taiwan Domestic Input-Output Tables
* Semiconductor industry classification analysis
* Global value-added concentration measurement

### Industry Trend Analysis

* World Semiconductor Trade Statistics (WSTS)
* Regional semiconductor billings analysis
* Long-run geographic concentration trends

### Natural Language Processing (NLP)

* PDF text extraction
* Text preprocessing and normalization
* Keyword frequency analysis
* Normalized keyword comparison
* Sentiment analysis

### Database Infrastructure

* SQL database integration
* Structured storage of economic and text datasets
* Reproducible querying and aggregation workflows

---

## Repository Structure

```text
nvidia-geopolitical-risk-analysis/

├── data/
│   ├── nvidia/
│   │   ├── nvidia_fy2026_10k.pdf
│   │   └── nvidia_q3_fy2026_earnings_call_transcript.pdf
│   │
│   ├── oecd/
│   │   ├── oecd_icio_2025.xlsx
│   │   ├── oecd_icio_database.db
│   │   └── semiconductor_value_added_components.csv
│   │
│   ├── taiwan/
│   │   └── taiwan_input_output_table_2022.csv
│   │
│   └── wsts/
│       └── wsts_historical_semiconductor_billings_2025.xlsx
│
├── figures/
│   ├── taiwan_share_global_semiconductor_value_added.png
│   ├── regional_semiconductor_billings.png
│   ├── raw_keyword_frequency.png
│   ├── normalized_keyword_frequency.png
│   ├── sentiment_comparison.png
│   └── pearson_residuals_analysis.png
│
├── notebooks/
│   └── nvidia_geopolitical_risk_analysis.ipynb
│
├── presentation/
│   └── nvidia_geopolitical_risk_presentation.pptx
│
├── report/
│   └── nvidia_geopolitical_risk_report.pdf
│
└── README.md
```

---

## Technologies

* Python
* Pandas
* SQL
* Natural Language Processing (NLP)
* Sentiment Analysis
* Data Visualization
* PDF Processing

---

## Skills Demonstrated

* Geopolitical Risk Analysis
* Supply Chain Economics
* Semiconductor Industry Research
* SEC Filing Analysis
* Earnings Call Analysis
* Natural Language Processing
* SQL Database Management
* Data Cleaning & Feature Engineering
* Statistical Analysis
* Data Visualization
* Research Communication

---

## Data Sources

### Company Disclosures

* NVIDIA FY2026 Form 10-K
* NVIDIA Q3 FY2026 Earnings Call Transcript

### Economic & Industry Data

* OECD Inter-Country Input-Output (ICIO) Tables
* Taiwan Domestic Input-Output Table (2022)
* World Semiconductor Trade Statistics (WSTS)

### Research Sources

* OECD Semiconductor Value Chain Research
* Center for Strategic and International Studies (CSIS)
* Industry and geopolitical risk literature

---

## Conclusion

The findings indicate that NVIDIA faces material geopolitical exposure due to its dependence on a highly concentrated semiconductor supply chain centered in Taiwan.

While the company acknowledges these risks in formal regulatory disclosures, analysis of earnings call communications suggests that geopolitical and supply-chain vulnerabilities receive substantially less emphasis in investor-facing discussions.

As semiconductor production becomes increasingly concentrated within the Asia-Pacific region, NVIDIA's dependence on Taiwan remains a persistent structural risk with potential implications for supply continuity, market access, and long-term competitive positioning.

---

## Disclaimer

This project was completed for academic and research purposes and does not constitute investment advice.
