  Repository Overview

The folder provides the principal replication materials for the study “Do Environmental, Social, and Governance Domains Relate Differently to Firm Performance? Evidence from a Meta-Analytic Structural Equation Model.” The repository is organized to reflect the empirical design and methodological steps described in Section 3 (Methods) of the paper and to support transparency, traceability, and reproducibility of the reported meta-analytic structural equation modeling (MASEM) analyses. Its internal structure follows the analytical sequence of the study, from the identification of the included literature to meta-analytic synthesis, structural estimation, and sensitivity assessment.

Folder Structure and Description

1. Meta-Analysis Literature List

This subfolder contains the study-level master literature database underlying the meta-analysis reported in Sections 3.1–3.4 of the paper. Rather than serving as a simple bibliography, the file documents the final evidence base resulting from the systematic screening process. Each included study is assigned a Research ID to facilitate consistent tracking across the analytical materials.

The database records core descriptive information, including authorship, publication outlet, and year of publication. Following the multi-stage inclusion and exclusion procedure described in Section 3.2, the final sample comprises 283 quantitative empirical studies that contributed at least one eligible correlation to the 36-cell meta-analytic correlation matrix. These study-level records provide the literature foundation for the subsequent quantitative synthesis.

2. Main MASEM Analysis

This subfolder contains the analytical files used for the meta-analytic structural equation model described in Section 3.5. Specifically, it includes:

the pooled meta-analytic correlation matrix;
executable Mplus input files implementing the correlation-based MASEM specification; and
output files reporting standardized path coefficients, model fit indices, and explained variance.

The structural model jointly estimates the conditional associations of the environmental, social, and governance domains with financial performance, market value, and innovation output, while accounting for firm size, firm age, leverage, and the correlations among the ESG domains. The structural-model results reported in Fig. 3 and Tables 2–3 can be reproduced using the files provided in this folder.

3. Robustness Checks

This subfolder contains analytical materials supporting the sensitivity and publication-bias assessments reported in Section 4.4 of the paper. The available files include materials used for: sensitivity analysis based on the Sample-Adjusted Meta-Analytic Deviancy (SAMD) statistic and re-estimation after influential effect sizes are removed; and publication-bias diagnostics, including Egger’s regression test, Rosenthal’s fail-safe N, and Trim-and-Fill procedures.

These analyses are used to assess whether influential estimates or potential small-study effects materially alter the principal comparative domain-to-outcome pattern. They should be interpreted as sensitivity diagnostics and do not independently validate the underlying data or analytical decisions of the primary studies.

Replicability and Data Availability

The public repository provides the included-study literature database, pooled correlation matrices, Mplus input and output files, and the matrices used for the influence and publication-bias checks. These materials allow readers to inspect the evidence base and reproduce the principal structural and sensitivity analyses reported in the paper.

The repository does not redistribute copyrighted full texts or the underlying firm-level data used by the primary studies. The full effect-size extraction file and coding protocol are retained by the authors and are available from the corresponding author on reasonable request, as stated in the manuscript’s Data Availability Statement.

  Replicability Statement:
  
All data files are organized at the study level and are linked consistently through unique identifiers. This structure allows independent researchers to replicate the full empirical workflow described in the paper—from systematic literature screening and effect-size synthesis to meta-analytic structural equation modeling and robustness testing—using the provided data and executable scripts.
