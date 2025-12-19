  Repository Overview:

The folder “How ESG Creates Firm Value (Raw Data)” provides the complete data foundation and analytical materials for the study “How ESG Creates Firm Value: Disaggregating Environmental, Social, and Governance Capabilities through a Meta-Analytic Structural Lens.”
The repository is constructed to mirror the empirical design and methodological steps described in Section 3 (Methodology) of the paper, ensuring transparency, traceability, and full replicability of the meta-analytic structural equation modeling (MASEM) process.
Its internal structure follows the sequential logic of the study, from systematic literature identification and coding, to meta-analytic synthesis, structural estimation, and robustness validation.

  Folder Structure and Description:

1.Meta-Analysis Literature List:
This subfolder contains the study-level master literature database that underpins the entire meta-analytic procedure reported in Sections 3.1–3.4 of the paper.
Rather than serving as a simple bibliography, this file represents the empirical screening and coding backbone of the analysis.
Each row corresponds to a unique empirical study included in the meta-analysis and is assigned a Research ID, which enables consistent tracking across literature screening, effect-size extraction, correlation matrix construction, and robustness diagnostics. The database records essential descriptive information, including authorship, publication outlet, and year of publication.
Following the multi-stage inclusion and exclusion process described in Section 3.2, this literature list documents the final sample of 251 quantitative empirical studies, each reporting dimension-level ESG indicators and firm-level performance outcomes. These studies form the basis for the extraction of effect sizes used in subsequent meta-analytic synthesis.

2.Main MASEM Analysis:
This subfolder contains the analytical files required to estimate the meta-analytic structural equation model described in Section 3.5.2.
Specifically, it includes:
The integrated meta-analytic correlation matrix,
Executable scripts (e.g., Mplus code) implementing the TSSEM procedure,
Output files reporting standardized path coefficients, model fit indices, and explained variance.
The structural model estimates the differentiated effects of environmental, social, and governance dimensions on financial performance, market value, and innovation output, while controlling for firm size, firm age, and leverage. All results reported in Figure 1 and Tables 2–3 of the paper can be reproduced directly using the files in this folder.

3.Robustness Checks:
This subfolder documents the robustness analyses reported in Section 4.3 of the paper.
It includes materials for:
Sensitivity analysis, conducted using the Sample-Adjusted Meta-Analytic Deviancy (SAMD) statistic to identify influential effect sizes and re-estimate the model after their removal;
Publication bias assessment, including Egger’s regression test, Rosenthal’s fail-safe N, and Trim-and-Fill procedures.
Across all robustness specifications, the core findings remain stable: environmental capabilities dominate internal performance and innovation outcomes, governance mechanisms drive market valuation, and social practices exhibit asymmetric internal benefits and external discounting.

  Replicability Statement:
  
All data files are organized at the study level and are linked consistently through unique identifiers. This structure allows independent researchers to replicate the full empirical workflow described in the paper—from systematic literature screening and effect-size synthesis to meta-analytic structural equation modeling and robustness testing—using the provided data and executable scripts..
