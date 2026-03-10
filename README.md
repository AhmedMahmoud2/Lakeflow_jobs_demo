# Databricks Lakeflow Jobs — YouTube Series Notebooks

> **DataMindAI | Ahmed | Head of Data Engineering**

## Contents

| Notebook | Topic | Cells |
|----------|-------|-------|
| `01_Lakeflow_Jobs_Presentation_Guide.ipynb` | All 11 features — job anatomy, compute, triggers, dependencies, task values, If/Else, For-Each, SQL, partial repairs, alerts, DABs | 40 |
| `02_Dynamic_Value_References.ipynb` | `{{ }}` dynamic references — job metadata, task values, SQL output rows, For-Each `{{input.X}}` | 14 |
| `03_Task_Values.ipynb` | `dbutils.jobs.taskValues` — publishing, consuming, lists, For-Each, `.get()` with debugValue | 18 |

## How to use in Databricks

### Option 1 — Git Clone directly in Databricks
1. Go to **Workspace → Repos → Add Repo**
2. Paste your GitHub repo URL
3. Click **Clone**
4. Open any `.ipynb` file — Databricks renders it as a notebook automatically

### Option 2 — Manual import
1. Download any `.ipynb` file
2. Databricks Workspace → Import → select the file

## Pre-requisites
- Databricks workspace (Free Edition or above — **not** Community Edition)
- Unity Catalog enabled
- Run the **Setup cell** at the top of each notebook once (creates `demo_catalog.bronze/silver/gold`)

## Student dummy data
All three notebooks use the same 10 students:

| ID | Name | Course | Score | Attendance |
|----|------|--------|-------|------------|
| S001 | Aisha Rahman | Data Science | 82 | 95 |
| S002 | James Bradley | Data Science | 41 | 60 |
| S003 | Priya Patel | Engineering | 76 | 88 |
| S004 | Carlos Mendez | Engineering | 55 | 72 |
| S005 | Sophie Williams | Mathematics | 91 | 98 |
| S006 | Kwame Asante | Mathematics | 38 | 55 |
| S007 | Liu Wei | Data Science | 67 | 80 |
| S008 | Emma Johnson | Engineering | 74 | 85 |
| S009 | Tariq Ahmed | Data Science | 29 | 40 |
| S010 | Fatima Al-Sayed | Mathematics | 88 | 94 |

## Sales dummy data (Notebook 01)
8 orders across North/South/East/West regions — Laptops (£1,200), Monitors (£450), Keyboards (£85), Mouse (£35), Headsets (£150).

---
*Series: Databricks Lakeflow Jobs — Complete Guide | DataMindAI*
