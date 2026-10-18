# Data Modeling & Evaluation Methods

[← Profile](../README.md)

Two coauthored studies of how educational resources and research output are distributed, using statistical modeling, subgroup analysis, and robustness checks.

## Higher education resource distribution

**人均规模趋同与质量分化：省际高等教育资源集聚分布的双重效应研究**  
田浩然、王国郦、郭峻仙 · 《教育发展研究》, 2026 · CSSCI

The study examines the distribution of higher education resources across 31 Chinese provinces from 2005 to 2022, distinguishing enrollment scale from resource measures such as assets and faculty.

- **Modeling:** province and year fixed effects, growth-rate outcomes, and economic and demographic controls.
- **Evaluation:** geographic and economic subgroup comparisons; lagged explanatory variables, Driscoll–Kraay standard errors, and alternative measures as robustness checks.
- **Finding:** convergence in per-capita enrollment scale can coexist with divergence in selected resource measures, with differences across regions.

These are observational estimates. Robustness checks examine sensitivity to assumptions; they do not by themselves establish causality.

## Doctoral research performance

**Inequality of Doctoral Research Performance—Evidence from the Field of Education in China**  
Guoli Wang, Haoran Tian · Research poster selected for Tsinghua University's Higher Education Forum

The poster studies publication inequality using CNKI records covering 6,189 doctoral students in education, 2015–2024.

- **Data:** Python-based collection and construction of publication measures.
- **Measurement:** Gini coefficients and coefficients of variation.
- **Modeling:** negative binomial regression for publication counts and OLS for journal impact-factor measures.
- **Comparison:** institutional background, funding, and collaboration structure.

Journal impact factors are a proxy used in this study, not a complete measure of an individual's research quality.

This page is a methodological summary. It does not redistribute the publication PDFs or underlying research data.
