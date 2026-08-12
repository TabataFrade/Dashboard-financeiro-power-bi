# 📊 Dashboard Financeiro - Vendas | Power BI

Projeto de **Business Intelligence** desenvolvido em **Power BI** para análise e acompanhamento do desempenho financeiro, com foco em **receitas, custos, despesas e lucro**.

O dashboard organiza os principais indicadores financeiros em uma experiência visual e interativa, permitindo acompanhar resultados, identificar variações ao longo do tempo e analisar informações de forma mais detalhada.

---

## 🖥️ Visualização do Dashboard

### 🏠 Capa

Página inicial do projeto, com navegação para as áreas de **Visão Geral** e **Detalhamento**.

![Capa do Dashboard Financeiro](images/capa.jpeg)

### 📈 Visão Geral

A página de Visão Geral apresenta os principais indicadores financeiros e permite acompanhar o desempenho do negócio de forma consolidada.

Entre as análises disponíveis estão:

* receita total;
* custos;
* despesas;
* lucro;
* evolução mensal da receita;
* comparação entre receita e despesas;
* custos e despesas ao longo do tempo;
* distribuição das saídas;
* receita por cliente;
* filtro por ano.

![Visão Geral do Dashboard Financeiro](images/visao-geral.jpeg)

### 🔎 Detalhamento

A página de Detalhamento permite analisar o resultado financeiro com maior profundidade, destacando a evolução do lucro ao longo dos meses e os valores mensais de receita, custos e despesas.

![Detalhamento do Dashboard Financeiro](images/detalhamento.jpeg)

---

## 🎯 Objetivo do projeto

O objetivo deste projeto é centralizar informações financeiras em um único painel e transformar dados em indicadores de fácil interpretação.

Com o dashboard, é possível:

* acompanhar receitas, custos, despesas e lucro;
* analisar a evolução dos resultados ao longo dos meses;
* identificar períodos de maior ou menor desempenho;
* comparar entradas e saídas financeiras;
* analisar a participação dos clientes na receita;
* apoiar análises e tomadas de decisão com informações visuais.

---

## 📌 Principais indicadores

O dashboard acompanha os seguintes KPIs:

* **Receita**
* **Custos**
* **Despesas**
* **Lucro**

---

## 🧠 Modelagem de dados

O modelo semântico foi estruturado com tabelas de movimentações financeiras, plano de contas, calendário e medidas.

| Tabela          | Finalidade                                            |
| --------------- | ----------------------------------------------------- |
| `Recebimentos1` | Informações relacionadas aos recebimentos             |
| `Saidas`        | Movimentações financeiras de saída                    |
| `Contas`        | Plano de contas e classificação das movimentações     |
| `Data`          | Tabela calendário para análises temporais             |
| `Medidas`       | Centralização dos indicadores utilizados no dashboard |

---

## 🛠️ Tecnologias e recursos utilizados

* **Power BI Desktop**
* **Power Query**
* **DAX**
* **Modelagem de dados**
* **Power BI Project (`.pbip`)**
* **TMDL**
* **Git**
* **GitHub**

---

## 📂 Estrutura do repositório

```text
.
├── Dash Financeiro - Vendas.pbip
├── Dash Financeiro - Vendas.Report/
├── Dash Financeiro - Vendas.SemanticModel/
├── images/
│   ├── capa.jpeg
│   ├── visao-geral.jpeg
│   └── detalhamento.jpeg
├── .gitignore
└── README.md
```

---

## 📊 Fontes de dados

O projeto utiliza arquivos Excel como fontes de dados, incluindo:

* `Recebimentos.xlsx`
* `Pagamentos.xlsx`
* `CadastroPlanoContas.xlsx`

> **Observação:** os arquivos de dados de origem não estão incluídos neste repositório.

Para atualizar os dados em outro computador, será necessário configurar novamente as fontes no **Power Query**.

---

## 💡 Competências demonstradas

* desenvolvimento de dashboards em Power BI;
* tratamento e transformação de dados com Power Query;
* criação de indicadores com DAX;
* modelagem e relacionamento de dados;
* análise de indicadores financeiros;
* construção de análises temporais;
* organização de projetos Power BI no formato PBIP;
* versionamento com Git e GitHub.

---

## 👩‍💻 Autora

**Tabata Frade**

Projeto desenvolvido para fins de **estudo, portfólio e demonstração de habilidades em Business Intelligence e análise de dados**.
::: 
