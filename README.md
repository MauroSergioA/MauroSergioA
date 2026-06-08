# Mauro Sergio — Data Engineer

Construo pipelines de dados que conectam sistemas legados complexos a decisões de negócio.

Trabalho com engenharia de dados no varejo alimentar desde 2023, liderando a arquitetura de um Data Warehouse completo sobre o ERP Consinco/Oracle.

## Stack

![Apache Hop](https://img.shields.io/badge/Apache%20Hop-E25A1C?style=flat&logo=apache&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)

## O que estou construindo

Data Warehouse multicamada (Bronze / Silver / Gold) para uma rede de varejo alimentar no Ceará:

- **Extração** — Apache Hop integrando Oracle ERP, SQL Server, APIs REST e Google Sheets
- **Armazenamento** — PostgreSQL 18 com 90M+ registros de vendas
- **Transformação** — dbt com modelos incrementais e star schema
- **Visualização** — Power BI com DAX avançado e Metabase

## Arquitetura

```
Fontes          Extração       Bronze    Transformação    Silver / Gold    Consumo
──────────      ────────       ──────    ─────────────    ─────────────    ───────
Oracle ERP  ──►
SQL Server  ──► Apache Hop ──► Bronze ──► dbt ──────────► Silver ───────► Power BI
APIs REST   ──►                                            └──► Gold ────► Metabase
Google Sheets►
```

## Projetos

| Repositório | Descrição | Stack |
|---|---|---|
| [superque-dbt](https://github.com/MauroSergioA/superque-dbt) | Modelos dbt do DW do varejo | dbt · PostgreSQL |
| [Retail-Data-Pipelines](https://github.com/MauroSergioA/retail-data-pipelines) | Pipelines de extração | Apache Hop · Oracle |

## Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maurosergiodata)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:maurosergio.comercial@gmail.com)

---

*Open to Remote — Data Engineer · Analytics Engineer · BI Developer*
