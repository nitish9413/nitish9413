# Nitish Katkade — Data Engineer
[![Databricks Certified Data Engineer](https://img.shields.io/badge/Databricks_Certified-Data_Engineer_Associate-FF3621?style=flat&logo=databricks&logoColor=white)](https://credentials.databricks.com/YOUR_CREDENTIAL_ID)

[![Databricks Certified Data Engineer](https://api.accredible.com/v1/frontend/credential_website_embed_image/badge/175835796)](https://credentials.databricks.com/175835796)

Software Engineer building production-grade **data pipelines, ETL systems, and Lakehouse infrastructure**.  
Currently engineering an **HVAC Fault Detection & Diagnostics (FDD) Engine** designing the data layer for real time rule evaluation and analytics at scale.

<p align="left"> <img src="https://komarev.com/ghpvc/?username=nitish9413&label=Profile%20views&color=0e75b6&style=flat" alt="nitish9413" /> </p>

---

## What I build

- **ETL & Incremental Pipelines** — batch and streaming ingestion with exactly once semantics, schema governance, and audit trails
- **Lakehouse Stack** — Delta Lake tables, PySpark transformations, Databricks workflows; recently migrated large scale workflows from Pandas → Polars for significant performance gains
- **Production Python Packages** — modular, testable, cloud agnostic libraries (see `open_auto_loader` below)

---

## Flagship project

### [open_auto_loader](https://github.com/nitish9413/open_auto_loader)
A high-performance incremental data ingestion library built on **Polars + Delta Lake**.  
Supports Local, AWS S3, Azure Blob, and GCP out of the box. SQLite-backed checkpointing ensures files are processed exactly once.

```python
loader = OpenAutoLoader(
    source="s3://raw-bucket/incoming/",
    target="s3://silver-bucket/tables/users",
    format_type="csv"
)
loader.run(batch_id="daily_batch_001")
```

---

## Tech stack

**Core:** Python · PySpark · Polars · SQL  
**Lakehouse:** Delta Lake · Databricks · Azure Data Lake  
**Infra:** Docker · FastAPI · PostgreSQL · MySQL · Azure  
**Cloud Storage:** AWS S3 · Azure Blob · GCP GCS

---

## Currently learning

Advanced Cloud Data Engineering — Azure Data Factory · Synapse Analytics · medallion architecture patterns

---

## Let's connect

Open to collaborating on **Data Engineering, MLOps, and AI pipeline** projects.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/nitishkatkade)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:nitishkatkade94@gmail.com)

---

## GitHub stats

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nitish9413&theme=dark&hide_border=true&include_all_commits=true&count_private=false&layout=compact)
