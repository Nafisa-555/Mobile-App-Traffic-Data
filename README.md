# Mobile App Traffic Data – Data Analytics Project

### By-
**Nafisa Ansari**

### Objective
Analyze traffic data of 6 apps to understand patterns behind IVT (Invalid Traffic) detection.

### Steps Performed
- Cleaned and preprocessed raw Excel data
- Converted text-based columns to numeric
- Compared IVT vs Non-IVT apps
- Computed correlation and key ratios
- Exported analysis results to Excel
### Key Findings
- The analysis suggests clear behavioral differences between legitimate and IVT-affected traffic:
- Higher Request Rates: IVT-affected apps generally have a higher requests_per_idfa and idfa_ua_ratio, which suggests automated or spoofed requests from non-human sources.
- Fewer Impressions: impressions_per_idfa are lower for IVT apps. This indicates that the high volume of requests does not translate into real ads being shown to users.
- Stable Baseline: Non-IVT apps (where IVT == 0) show stable and consistent ratios close to 1, which aligns with normal, expected user behavior.

### Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
