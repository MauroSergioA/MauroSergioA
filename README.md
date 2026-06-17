# Olá, eu sou Mauro Sergio 👋
### Data Engineer & Analytics Specialist

> Construo plataformas de dados e automatizo processos que transformam operações complexas em inteligência acionável.

Com atuação focada na modernização de arquiteturas de dados, sou responsável por projetar e evoluir ecossistemas analíticos escaláveis. Minha especialidade é integrar múltiplas fontes — de ERPs robustos como Consinco/Oracle a APIs e planilhas —, garantindo desde a ingestão eficiente até a modelagem dimensional para o consumo final em Business Intelligence.

---

## 🛠️ Stack Principal e Ferramentas

**Engenharia e Banco de Dados**  
![Apache Hop](https://img.shields.io/badge/Apache%20Hop-E25A1C?style=flat&logo=apache&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat&logo=oracle&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoftsqlserver&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)

**Analytics e BI**  
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black) ![Metabase](https://img.shields.io/badge/Metabase-509EE3?style=flat&logo=metabase&logoColor=white)

**Orquestração e DevOps**  
![Apache Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white) ![Airbyte](https://img.shields.io/badge/Airbyte-615EFF?style=flat) ![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Explorando Atualmente:** `Apache Iceberg` | `DuckDB` | `Kubernetes` | `MinIO` | `Data Lakehouse`

---

## 🎯 Minhas Especialidades

*   **Arquitetura de Dados:** Data Warehouse, Modelagem Dimensional (Star Schema), Data Lakehouse.
*   **Engenharia e ETL/ELT:** Pipelines escaláveis, CDC, Processamento Incremental, Qualidade de Dados.
*   **Integração e Automação:** Extração de dados complexos do Oracle ERP (Consinco), APIs REST, automação inteligente com Python.
*   **Business Intelligence:** Retail Analytics, Self-Service Analytics, Criação de Dashboards executivos de alto impacto.
*   **Performance:** SQL Tuning avançado, indexação e particionamento em grandes volumes de dados.

---

## 🏗️ O que estou construindo: Enterprise Retail Data Warehouse

Desenvolvimento de uma arquitetura multicamada (*Medallion Architecture*: Bronze / Silver / Gold) voltada para o setor de varejo alimentar de alta volumetria no Ceará.

*   **Fontes de Dados:** Oracle ERP Consinco, SQL Server, APIs REST, Google Sheets e planilhas operacionais.
*   **Ingestão e Orquestração:** Pipelines orquestrados via Apache Hop com processamento incremental, rotinas de *Change Data Capture* (CDC) e cargas parametrizadas.
*   **Armazenamento (Data Lake/DW):** Banco de dados PostgreSQL (v18) gerenciando **+90 milhões de registros** com particionamento de tabelas e índices otimizados para alta performance.
*   **Transformação e Modelagem:** Tratamento de dados utilizando **dbt** para criação das camadas Silver e construção de Data Marts na camada Gold (Star Schema).
*   **Visualização e Consumo:** Disponibilização de dados tratados para consumo no Power BI e Metabase, habilitando Self-Service Analytics e gestão assertiva de indicadores estratégicos.

### Fluxo da Arquitetura

```text
╭────────────────────────────────────────╮
│      🏢 ERP Oracle Consinco / APIs     │
╰───────────────────┬────────────────────╯
                    ▼
╭────────────────────────────────────────╮
│             🚀 Apache Hop              │
╰───────────────────┬────────────────────╯
                    ▼
╭────────────────────────────────────────╮
│       🥉 Camada Bronze (Raw Data)      │
╰───────────────────┬────────────────────╯
                    ▼
╭────────────────────────────────────────╮
│     🛠️ dbt (Transformação e Testes)    │
╰───────────────────┬────────────────────╯
                    │
        ┌───────────┴───────────┐
        ▼                       ▼
╭───────────────╮       ╭───────────────╮
│ 🥈 Camada     │       │ 🥇 Camada     │
│    Silver     │       │    Gold       │
╰───────┬───────╯       ╰───────┬───────╯
        │                       │
        └───────────┬───────────┘
                    ▼
╭────────────────────────────────────────╮
│    📊 Power BI / Metabase (Consumo)    │
╰────────────────────────────────────────╯
```

## 📫 Contato
Fique à vontade para se conectar comigo para trocarmos ideias sobre Arquitetura de Dados, Business Intelligence, ou para conversarmos sobre novos projetos e parcerias!
<p align="left">
  <a href="https://www.linkedin.com/in/maurosergiodata" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:maurosergio.comercial@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>
