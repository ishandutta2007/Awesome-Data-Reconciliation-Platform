# Awesome-Data-Reconciliation-Platform

## Top Data Reconciliation Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Transaction Matching, Account Reconciliation, ETL/Data Diff Validation, Exception Workflows & Financial Close Controls*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Reconciliation**. These systems match, compare, and certify data across ledgers, systems, and pipelines—spanning classic financial reconciliation and modern data-pipeline / ETL validation.



**Examples** include Duco, AutoRek, SmartStream TLM, BlackLine Transaction Matching, ReconArt, Fiserv Frontier Reconciliation, Oracle Account Reconciliation, Xceptor, OpenReconcile, Trintech, Datafold, QuerySurge, Datagaps ETL Validator, Acceldata, Bigeye, Metaplane, Soda, Anomalo, Great Expectations Cloud, and QualiDI (the category leaders).



**Open-source emphasis**: Enterprise financial transaction matching and close-oriented reconciliation are almost entirely commercial. Strong open tools exist for **data quality, validation, and diff-style reconciliation** (Great Expectations, Soda Core, custom SQL/dbt patterns). This section expands those while remaining realistic about the commercial gap for regulated finance recon.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Duco](https://du.co/)**  

  Intelligent reconciliation platform for financial services—automating matching, exception management, and control across complex data sets.



- **[AutoRek](https://www.autorek.com/)**  

  Automated reconciliation and financial control platform for high-volume matching and exception workflows.



- **[SmartStream TLM](https://www.smartstream-stp.com/)**  

  Transaction Lifecycle Management suite including robust reconciliation and exception management for capital markets and banking.



- **[BlackLine Transaction Matching](https://www.blackline.com/)**  

  Enterprise transaction matching and account reconciliation within BlackLine’s financial close platform.



- **[ReconArt](https://www.reconart.com/)**  

  Flexible reconciliation software for transaction matching, period-end close, and exception management.



- **[Fiserv Frontier Reconciliation](https://www.fiserv.com/)**  

  Reconciliation capabilities within Fiserv’s financial technology stack for institutions.



- **[Oracle Account Reconciliation](https://www.oracle.com/)**  

  Oracle Cloud EPM Account Reconciliation for automated matching, variance analysis, and close certification.



- **[Xceptor](https://www.xceptor.com/)**  

  Data automation and reconciliation platform used in financial services for complex data processing and matching.



- **[OpenReconcile](https://www.openreconcile.com/)**  

  Reconciliation-focused platform for automated matching and exception handling.



- **[Trintech](https://www.trintech.com/)**  

  Financial close and reconciliation solutions (including Cadency) for enterprise accounting controls.



- **[Datafold](https://www.datafold.com/)**  

  Data diff and quality platform used for regression testing, column-level comparison, and pipeline change validation.



- **[QuerySurge](https://www.querysurge.com/)**  

  Automated data testing and ETL validation platform for comparing source and target data.



- **[Datagaps ETL Validator](https://www.datagaps.com/)**  

  ETL testing and data validation tool for reconciling data across pipeline stages.



- **[Acceldata](https://www.acceldata.io/)**  

  Data observability platform that includes pipeline reliability and quality checks relevant to reconciliation.



- **[Bigeye](https://www.bigeye.com/)**  

  Data observability with metrics and SLAs that support ongoing data reconciliation monitoring.



- **[Metaplane](https://www.metaplane.dev/)**  

  Warehouse-native observability for detecting anomalies that affect reconciliation integrity.



- **[Soda](https://www.soda.io/)**  

  Data quality platform with checks that can underpin pipeline-level reconciliation and contracts.



- **[Anomalo](https://www.anomalo.com/)**  

  AI-driven data quality platform for unsupervised detection of data issues that break reconciliations.



- **[Great Expectations Cloud](https://greatexpectations.io/)**  

  Commercial collaboration layer around the open-source Great Expectations validation framework.



- **[QualiDI](https://www.qualidi.com/)**  

  Data integration testing and validation platform for ETL/ELT reconciliation scenarios.



## Open-Source GitHub Projects

- **[Great Expectations (GX Core)](https://github.com/great-expectations/great_expectations)**  

  Open-source data validation framework for defining expectations and comparing datasets—widely used for pipeline and ETL-style reconciliation checks.



- **[Soda Core](https://github.com/sodadata/soda-core)**  

  Open-source data quality scanning with SodaCL—useful for freshness, completeness, and cross-check style reconciliation rules.



- **[dbt tests and custom recon models](https://github.com/dbt-labs/dbt-core)**  

  Using dbt tests and SQL models to implement source-to-target and period-over-period reconciliation logic.



- **[Data diff open libraries](https://github.com/)**  

  Community tools and scripts for row-level and aggregate comparison of tables across systems.



- **[SQL-based reconciliation patterns](https://github.com/)**  

  Shared SQL templates for matching keys, hashing rows, and surfacing breaks between ledgers or pipelines.



- **[Pandas / Spark reconciliation notebooks](https://github.com/)**  

  Open examples of large-scale comparison using dataframes for non-financial or mid-scale recon.



- **[Elementary](https://github.com/elementary-data/elementary)**  

  Open-source dbt-native observability that surfaces anomalies and test failures relevant to data recon.



- **[Documentation and GX / Soda recon playbooks](https://greatexpectations.io/)**  

  Guides for building validation suites that act as continuous reconciliation gates.



- **[Self-hosted validation stacks](https://github.com/)**  

  Combining Great Expectations or Soda Core with orchestrators for scheduled reconciliation jobs.



- **[Open reporting for breaks](https://github.com/)**  

  Templates for exception reports and break aging that finance and data teams can adapt.



### Additional Strong Open-Source Options

- Implementing pipeline and ETL reconciliation with **Great Expectations** or **Soda Core**.

- Encoding matching logic in **dbt** or pure SQL for owned, versioned checks.

- Accepting that high-volume financial transaction matching, regulated close workflows, certification, and audit-ready exception management still require commercial platforms (Duco, AutoRek, BlackLine, SmartStream, ReconArt, Oracle, Trintech, etc.).

- Focusing open-source efforts on data-pipeline integrity and preventing silent mismatches before they reach finance.



**Frameworks for building custom systems**: Validate sources with GX/Soda → compare with SQL or dataframe diffs → orchestrate with Airflow/Prefect → report breaks to tickets. Suitable for data engineering recon. Treasury, banking, and close teams typically run dedicated commercial reconciliation platforms.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Financial reconciliation supports audit and regulatory processes. Open-source tools are not substitutes for controlled commercial systems in regulated environments. This list is not accounting or compliance advice.



---

**Made for finance ops, data engineers, and control teams.**

Let's keep numbers matching, exceptions visible, and as open as practical.
