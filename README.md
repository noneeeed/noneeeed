[![Typing SVG](https://readme-typing-svg.demolab.com?font=Mystery+Quest&size=40&pause=1000&color=7B00F7&background=FFFFFF&center=true&vCenter=true&width=435&lines=Hi+there+and+welcome)](https://git.io/typing-svg)

Hi, I'm Bader

Junior data engineer in Kampen, the Netherlands. I build batch data pipelines with Python, SQL, dbt, Airflow, Databricks and Azure. In 2026 I completed the HackYourFuture Core Program and Data Track.

Before tech, I ran two electronics stores in Homs for almost four years and kept the sales, purchase and stock records on paper. I also led a 15-person team collecting data on local NGOs. That is where my interest in reliable data started.

I'm looking for a junior data engineering role in the Netherlands, hybrid or remote.

Projects
JobMatch · live demo

Job search app for the Dutch market, built by a 6-person team as our HackYourFuture final project. I worked on the data layer:

Ingestion from the FreeHire API, up to 5,000 postings per run, with exponential backoff on timeouts, 429 and 5xx errors
7 of the project's 12 dbt models on Databricks, including staging deduplication with a ROW_NUMBER() window and tables with one row per posting and skill, city or requirement for the app's filters
13 dbt tests, a skill popularity mart, and a daily Airflow DAG that publishes five marts to the app's PostgreSQL database

Python · SQL · dbt · Databricks · Airflow · PostgreSQL · Azure Data Lake Storage

Steam News Pipeline

Daily ETL job I built solo during the Data Track. It pulls Dota 2 news from the Steam Web API, validates it with Pydantic, cleans it with pandas and loads it into PostgreSQL idempotently, so re-runs never duplicate rows. The raw JSON is backed up to Azure Blob Storage, and the job runs in Docker on a schedule in Azure Container Apps.

Python · pandas · Pydantic · PostgreSQL · Docker · Azure · GitHub Actions

Data Track assignments
Topic	What I built.	Code
SQL	Audited NYC taxi data for duplicates, nulls and orphaned keys, then modeled it as a star schema of views	Week 9
dbt	A tested mart at one row per borough per day, with staging models and a custom macro	Week 10
Dashboards	A Metabase dashboard and a Streamlit metrics app on the same marts, with documented metrics	Week 11
Orchestration	An Airflow DAG (ingest, dbt run, dbt test) with retries and backfills, deployed to a shared Airflow instance	Week 12
Databricks	PySpark exploration, incremental dbt models on Delta Lake and a Git-backed Databricks Job	Week 13
Infrastructure as code	Azure storage deployed with Bicep from GitHub Actions, with a what-if preview on every pull request	Week 14
Stack
Languages: Python, SQL, JavaScript
Data: dbt, Apache Airflow, Databricks, PySpark, Delta Lake, pandas, Pydantic
Storage: PostgreSQL, Azure Data Lake Storage, Azure Blob Storage, SQLite
Cloud and DevOps: Azure Container Apps, Container Registry, Key Vault, Docker, GitHub Actions, Bicep
Testing: pytest, dbt tests, ruff
Dashboards: Metabase, Streamlit
Outside work

I captained Syria's Dota 2 team for four years. In my spare time I have been learning to run generative AI models such as Stable Diffusion and Ollama locally.

![Top Langs](https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=noneeeed&layout=compact&theme=radical)


![Streak Stats](https://github-readme-streak-stats-eight.vercel.app/?user=noneeeed&theme=radical)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Mystery+Quest&size=40&pause=1000&color=7B00F7&background=FFFFFF&center=true&vCenter=true&width=435&lines=I+Could+Be+Your+F1+Button)](https://git.io/typing-svg)


