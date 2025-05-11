# Atividade Data Science - Indicadores Socioeconômicos INSE 2021

Este repositório contém a análise exploratória e o pré-processamento do conjunto de dados **INSE 2021** (Índice Socioeconômico Escolar), disponibilizado pelo INEP.

---

## 📄 Descrição dos Dados

| Coluna            | Descrição                                                               |
| ----------------- | ----------------------------------------------------------------------- |
| `NU_ANO_SAEB`     | Ano de levantamento (2021)                                              |
| `TP_TIPO_REDE`    | Tipo de rede de ensino (**1**=Federal, **2**=Estadual, **3**=Municipal) |
| `TP_LOCALIZACAO`  | Localização da escola (**1**=Urbana, **2**=Rural)                       |
| `QTD_ALUNOS_INSE` | Número de alunos considerados no cálculo                                |
| `MEDIA_INSE`      | Média do índice socioeconômico escolar                                  |
| `PC_NIVEL_1`–`8`  | Percentual de alunos em cada nível socioeconômico (1 a 8)               |

---

## 📁 Estrutura do Projeto

```
DataScienceATT/
├── INSE_2021__brasil.xlsx        # Arquivo original do INEP
├── analysis_notebook.ipynb       # Notebook com leitura, wrangling e visualizações
├── ine_inse_2021_tratado.csv     # Dados tratados para Power BI
└── README.md                     # Documento em Markdown
```

---

## 🚀 Como Utilizar

1. **Abrir o Notebook**

   * Carregue `analysis_notebook.ipynb` no Jupyter Lab/Notebook.
2. **Executar Células**

   * Leia e inspecione o arquivo Excel.
   * Realize o data wrangling e gere estatísticas descritivas.
   * Crie visualizações (bar plots, histogramas, scatter).
   * Exporte o CSV tratado para `inep_inse_2021_tratado.csv`.
3. **Construir Dashboard**

   * No Power BI (Desktop ou Web), importe `inep_inse_2021_tratado.csv`.
   * Monte visuais: gráficos de barras para médias, slicers, cartões e tabelas.

---

> **Observação:**
> Este projeto tem foco em demonstrar o uso de **pandas**, **numpy** e **matplotlib**, além de preparar dados para **Power BI**. A análise não aprofunda interpretações estatísticas.
