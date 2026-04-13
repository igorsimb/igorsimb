<h1 align="center">Igor Simbirtsev</h1>

<p align="center">
Senior Backend Engineer (Python)
</p>

---

## About

I am a backend engineer focused on internal systems and data platforms. Over the past few years, I have been working on data ingestion, processing pipelines, data quality, reporting, and tools for analysts.

Most of my work involves production systems that:
- process tens of millions of rows daily,
- operate on terabyte-scale ClickHouse datasets,
- are used by analytics teams and business stakeholders.

My primary focus is backend and data.  
I approach frontend pragmatically — as a way to make complex systems accessible and usable.

---

## What I Work On

- designing and maintaining backend systems for analytics;
- building data ingestion and processing pipelines;
- working with ClickHouse, PostgreSQL, and background job systems;
- developing internal admin tools and interfaces;
- improving system reliability, maintainability, and clarity.

---

## Tech Stack

**Backend**
- Python 3.9–3.14
- Django, Django REST Framework
- FastAPI, Flask
- asyncio

**Data Storage**
- PostgreSQL
- ClickHouse (TB-scale)
- Redis
- ScyllaDB

**Background Processing & Scheduling**
- Celery, Celery Beat
- Airflow (~15 active DAGs)

**Infrastructure**
- Docker, Docker Compose
- GitHub Actions (CI)

**Quality & Observability**
- pytest
- loguru
- structured logging and documentation

---

## Selected Projects (production, private)

### Internal Analytics Platform & Admin Interface

I designed and maintain an internal platform used by the analytics team, covering the full lifecycle from ingestion to reporting.

The system includes:
- supplier data ingestion (email / FTP),
- validation and consolidation of incoming files,
- nightly data processing pipelines,
- analytical reporting on top of ClickHouse,
- integrations with external services.

Technically, this is a Django-based system with Celery and Airflow, running on top of ClickHouse (~2.4 TB) and PostgreSQL.

---

### Pricelens — Data Ingestion Observability

A subsystem for monitoring supplier data ingestion.

It tracks events across the pipeline, stores failure reasons, and provides an interface for investigating issues.

This improved visibility into the ingestion process and made it easier to identify unstable data sources and bottlenecks.

---

### Emex Upload

A Django module for uploading and validating large datasets.

Key aspects:
- files up to ~1M rows,
- complex validation rules,
- near real-time user feedback,
- detailed error reporting and processing status.

---

## Approach

I focus on building systems that are maintainable, well-structured, and observable.  
Clear architecture, testing, and documentation are important parts of the process.

I also work closely with non-engineering stakeholders and aim to communicate technical concepts in a clear and practical way.

---

## Contacts

- LinkedIn: https://www.linkedin.com/in/igor-simbirtsev/
- Telegram: https://t.me/igor_dev
