
# Healthcare: Hospital Data Warehouse Modernization

Layers:
- Databricks: Bronze/Silver/Gold Delta tables, jobs, SQL
- dbt: Modeling (staging → intermediate → marts), tests, docs
- Metabase: Dashboards (wired to gold schema)

## Quick start
- infra: `infrastructure/terraform/databricks`
- databricks code: `databricks/…`
- dbt project: `dbt/…`
