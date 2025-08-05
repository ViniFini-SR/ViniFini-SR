# Vinicios Santos

Guardarei meus projetos, estudos e experimentos sobre Data Lake, OLAP, streaming de dados e as tecnologias para Engenharia e Analytics de Dados.

---

## 🚀 Sobre mim

Sou entusiasta de arquitetura de dados, processamento distribuído e soluções escaláveis para Big Data.

No meu dia a dia trabalho e estudo tecnologias como:

- **Apache Kafka**: ingestão de dados em tempo real via streams.
- **Apache Pinot**: OLAP eficiente para consultas analíticas rápidas.
- **Apache Iceberg**: gerenciamento de tabelas transacionais no Data Lake.
- **MinIO**: armazenamento de objetos compatível com S3 para Data Lake.
- **Apache Hive**: catálogo central para integração entre ferramentas.
- **Trino**: engine SQL distribuída para consultas federadas sobre Data Lake.
- **Apache Spark + Python**: processamento e manipulação de dados em larga escala.
- **Jupyter Notebooks**: ambiente interativo para testes e análises.
- **SQL**: Domínio avançado em SQL para consultas complexas, otimização e modelagem de dados.
- **PL/SQL e PL/pgSQL**: Programação de stored procedures, funções e triggers em Oracle e PostgreSQL.
- **Bancos de Dados Relacionais**: Experiência com Oracle, PostgreSQL, SQLite e MS SQL Server.
- **Apache Airflow**: orquestração e agendamento de pipelines de dados.

---

## 🛠️ Stack de Ferramentas

| Ferramenta                | Finalidade                                    |
|---------------------------|-----------------------------------------------|
| ![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white) | Ingestão e streaming de dados |
| ![Pinot](https://img.shields.io/badge/Pinot-4E9AD1?logo=apache&logoColor=white) | OLAP em tempo real, consultas analíticas |
| ![Iceberg](https://img.shields.io/badge/Iceberg-1B9E77?logo=apache&logoColor=white) | Data Lakehouse, tabelas transacionais |
| ![MinIO](https://img.shields.io/badge/MinIO-CB1B45?logo=minio&logoColor=white) | Storage de objetos para Data Lake |
| ![Hive](https://img.shields.io/badge/Hive-FCBA03?logo=apachehive&logoColor=white) | Catálogo de metadados |
| ![Trino](https://img.shields.io/badge/Trino-3D6BA0?logo=trino&logoColor=white) | Query engine distribuído |
| ![Spark](https://img.shields.io/badge/Spark-F88909?logo=apachespark&logoColor=white) + ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) | Processamento distribuído e manipulação |
| ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white) | Ambiente interativo para testes e análises |
| ![SQL](https://img.shields.io/badge/SQL-4479A1?logo=postgresql&logoColor=white) | Consultas e manipulação de dados |
| ![Oracle](https://img.shields.io/badge/Oracle-F80000?logo=oracle&logoColor=white) | Banco de dados Oracle |
| ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) | Banco de dados PostgreSQL |
| ![Airflow](https://img.shields.io/badge/Airflow-017CEE?logo=apacheairflow&logoColor=white) | Orquestração de pipelines de dados |

---

## 💡 Como uso cada uma

Para garantir uma arquitetura robusta e eficiente, sigo estas práticas:

- **Ingestão de dados:** Utilizo Kafka para ingestão contínua, com tópicos organizados e produtores/consumidores desacoplados.
- **Armazenamento:** Persisto dados brutos e processados no MinIO, sempre em formato Iceberg para versionamento e atomicidade.
- **Catálogo:** O Hive atua como catálogo central, facilitando integração entre Spark, Trino e demais ferramentas.
- **OLAP:** Os dados analíticos são indexados no Pinot, permitindo consultas rápidas e em tempo real.
- **Processamento:** Spark com Python é utilizado para manipulação de dados, integrando o catálogo Hive e acessando diretamente as tabelas Iceberg/MinIO.
- **Query Engine:** Trino é utilizado para consultas SQL distribuídas e federadas sobre o Data Lake e outras fontes, aproveitando o catálogo do Hive e o formato Iceberg.
- **Experimentação:** Jupyter Notebooks é o ambiente de escolha para testes, prototipação e validação de pipelines antes de produção.
- **Bancos Relacionais:** Utilizo Oracle, PostgreSQL, SQLite e MS SQL Server para armazenamento transacional, relatórios e integração com sistemas legados, aplicando otimizações e programação em PL/SQL e PL/pgSQL quando necessário.
- **Orquestração:** Apache Airflow para agendamento, monitoramento e gestão de workflows de dados complexos, garantindo execução confiável e tratamento de falhas.

---

## 📫 Entre em contato

- [LinkedIn](https://www.linkedin.com/in/vinicios-santos-rosa-sql/)
- [Email](mailto:viniciossr12@gmail.com)
