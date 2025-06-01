# Pipeline Development: Spotify API

[![Leia em Português](https://img.shields.io/badge/Leia%20em-Português-green)](README.md)

## 💼 About the Project  

This project includes steps for defining the data source—Spotify’s open data API—creating a PoC (Proof of Concept), and developing the solution based on data security rules for credential management.

Additionally, I implemented robust code for data ingestion and processing, with a direct connection to PostgreSQL to support a **medallion architecture** in an RDBMS context. Considering a three-layer data model, Apache Airflow was chosen as the orchestrator for the pipeline. Finally, a **Data Catalog** was developed with relevant metadata and technical documentation, all available in markdown files (`.md`) within this repository.

## 🎯 Objectives  

Beyond the technical execution of scripts and system integration, the main goals are:

- Provide data from open data sources to support the Data Community in personal projects and analytical development;
- Learn about secure credential management on a local machine;
- Ensure project efficiency even without cloud-based infrastructure;
- Develop reusable code templates for data ingestion and cleansing;
- Deepen knowledge in data architecture and PoC development;
- Strengthen data governance concepts using open-source tools, ensuring knowledge sharing and easy access.

## 🛠️ Tools Used  

A variety of tools were used throughout the project, including:

- Spotify API as the data source;
- Python libraries: `cryptography.fernet`, `requests`, `json`, `pandas`, `psycopg2`, `sqlalchemy`;
- PostgreSQL;
- Apache Airflow;
- DataHub;
- Excalidraw;
- GitHub.

## 🔎 Where to Find It?

You can find all files and documentation in this repository. Look for the folders:
- `/scripts` – Python scripts for ingestion and transformation;
- `/docs` – Technical documentation in Markdown;
- `/visuals` – Excalidraw diagrams and data visualizations.

## 👩🏻‍💻 Proof of Concept (PoC)

Since a PoC is a critical step in project development, I conducted this phase to ensure the best technical solution for the scenario and to meet the defined objectives.

This involved testing the technical feasibility of the proposed architecture. Any technical bottlenecks encountered will be documented to support knowledge sharing and to help others understand how to implement a project of this scale.

Using **Excalidraw**, I designed the expected flow of the technical solution. The goal here is to document this initial step and, in case of any changes, those will also be communicated.

The flow includes the following steps:
- Defining the data source;
- Connecting to the API;
- Securing credentials;
- Ingesting data;
- Processing and cleansing data;
- Connecting to PostgreSQL;
- Designing a **Medallion Architecture** with 3 data layers using SQL refinements;
- Orchestrating processes using **Apache Airflow**;
- Generating a **Data Catalog** and technical documentation for governance and a realistic data culture simulation.

Lastly, but certainly not less important, a **Data Visualization report** will be developed using Python. This is to show how to generate meaningful visualizations even in the absence of more advanced (often paid) BI tools.

![image](https://github.com/user-attachments/assets/6ae0a99c-e748-4771-9262-c6f661b276e2)
