![Andrés Olguín — Data Engineer. Databricks, PySpark, SQL, Python and Delta Lake.](assets/data-engineer-banner.png)

# Andrés Olguín · Data Engineer

**English** · [Español](README.es.md)

[LinkedIn](https://www.linkedin.com/in/andyolguin/) · [Resume EN](cv/Andres_Olguin_CV_EN.pdf) · [CV ES](cv/Andres_Olguin_CV_ES.pdf) · [CV PT](cv/Andres_Olguin_CV_PT.pdf) · [Email](mailto:andyolguint720@gmail.com)

I build and validate **ETL/ELT pipelines** with **Databricks, PySpark, Python and SQL**, focusing on data quality, dimensional modeling and reliable reprocessing.

My professional background combines cloud data workflows, data operations and technical coordination. I have worked with Azure Data Factory, ADLS Gen2, Azure Databricks, Azure DevOps and PostgreSQL on AWS RDS, alongside Python/SQL validation and operational documentation.

**Open to remote Data Engineer opportunities · English, Spanish and Portuguese**

## Core stack

![Core stack: Databricks, PySpark, Python, SQL, Delta Lake, dbt and PostgreSQL.](assets/core-stack.svg)

**Data engineering:** ETL/ELT · Medallion architecture · Data quality · Star schemas · Idempotency · CI/CD

## Selected engineering projects

These repositories document my implementations, design decisions and reproducible examples.

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/andresolguin/databricks-medallion-lakehouse-pipeline"><img src="assets/project-lakehouse.svg" alt="Databricks Medallion Lakehouse — sales analytics, Bronze, Silver and Gold." width="100%"></a>
<h3><a href="https://github.com/andresolguin/databricks-medallion-lakehouse-pipeline">Databricks Medallion Lakehouse</a></h3>
<p>Turn delivered sales CSV files into a validated analytical star schema, with duplicate handling, corrections, late backfills and source lineage.</p>
<p><strong>Stack:</strong> PySpark · Spark SQL · Delta Lake · Unity Catalog</p>
<p><strong>Demonstrates:</strong> Medallion layers, explicit quality decisions, retry-safe processing and fact reconciliation.</p>
<p><a href="https://github.com/andresolguin/databricks-medallion-lakehouse-pipeline/blob/main/docs/architecture.md">Architecture</a> · <a href="https://github.com/andresolguin/databricks-medallion-lakehouse-pipeline/blob/main/docs/runbook.md">Runbook</a> · <a href="https://github.com/andresolguin/databricks-medallion-lakehouse-pipeline/blob/main/docs/validation.md">Validation</a></p>
<p><a href="https://github.com/andresolguin/databricks-medallion-lakehouse-pipeline/actions/workflows/ci.yml"><img src="https://github.com/andresolguin/databricks-medallion-lakehouse-pipeline/actions/workflows/ci.yml/badge.svg" alt="Lakehouse pipeline checks in GitHub Actions"></a></p>
<p><sub>Local Spark/Delta and CI verification. Databricks workspace validation is pending.</sub></p>
</td>
<td width="50%" valign="top">
<a href="https://github.com/andresolguin/agridax-data-platform"><img src="assets/project-agridax.svg" alt="AgriDax Data Platform — agricultural analytics, Python, PostgreSQL and dbt." width="100%"></a>
<h3><a href="https://github.com/andresolguin/agridax-data-platform">AgriDax Data Platform</a></h3>
<p>Organize agricultural operations, field events and weather into analytical marts, with temporal modeling, quality gates and controlled publication.</p>
<p><strong>Stack:</strong> Python · PostgreSQL 16 · dbt Core · Docker Compose</p>
<p><strong>Demonstrates:</strong> Revision handling, business history, quarantine, recovery and transactional publication.</p>
<p><a href="https://github.com/andresolguin/agridax-data-platform/blob/main/README.md">Overview &amp; setup</a> · <a href="https://github.com/andresolguin/agridax-data-platform/tree/main/docs/adr">Design decisions</a> · <a href="https://github.com/andresolguin/agridax-data-platform/blob/main/docs/recovery.md">Recovery</a></p>
<p><sub>Python/PostgreSQL/dbt local implementation. GCP/BigQuery is the target architecture.</sub></p>
</td>
</tr>
</table>

## Engineering approach

- **Make the data contract explicit:** define grain, keys, types and rejection rules.
- **Plan for change:** handle duplicates, revisions, late arrivals and reprocessing.
- **Verify results:** reconcile keys and values, retain lineage and make failures visible.
- **Make the work reproducible:** include setup instructions, tests and architecture decisions.

## Background & collaboration

Beyond data engineering, my background includes technical team coordination, LLM training and evaluation, university research with Python, and teaching programming fundamentals at UTN-FRGP.

For roles, technical conversations or collaboration: **[LinkedIn](https://www.linkedin.com/in/andyolguin/)** · **[Email](mailto:andyolguint720@gmail.com)**
