# etl-weather-azure

Pipeline ETL de dados climáticos desenvolvido com Python, realizando extração automatizada via API Open-Meteo, transformação e enriquecimento dos dados com Pandas, seguido da carga em Azure SQL Database para análise e visualização estratégica.

---

## 🚀 Tecnologias Utilizadas

- Python
- Pandas
- SQLAlchemy
- PyODBC
- Azure SQL Database
- Open-Meteo API
- Google Colab

---

## 📊 Arquitetura do Pipeline

Open-Meteo API
        ↓
Extração com Python
        ↓
Transformação com Pandas
        ↓
Carga no Azure SQL
        ↓
Visualização do DashBoard

---

## ⚙️ Funcionalidades

- Extração automatizada de dados climáticos
- Tratamento e padronização dos dados
- Criação de métricas climatológicas
- Integração com Azure SQL Database
- Pipeline ETL completo

---

## 📁 Estrutura do Projeto

```bash
etl-weather-azure/
├── notebook/
│   └── etl_pipeline.ipynb     # Notebook principal
│
├── sql/
│   └── create_table.sql       # Script de criação da tabela
│
├── weather-etl-dashboard/
│   └── index.html             # Dashboard 
│
├── .gitignore
└── README.md                  # Documentação do projeto
