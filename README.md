# Dashboard Financeiro - Vendas | Power BI

Projeto de Business Intelligence desenvolvido em **Power BI** para análise financeira, com foco em receitas, despesas, custos e resultado.

## Objetivo

Centralizar indicadores financeiros em um dashboard interativo, facilitando o acompanhamento da evolução dos resultados e o detalhamento das movimentações.

## Páginas do relatório

- **Capa** — página inicial e navegação do dashboard.
- **Visão Geral** — visão consolidada dos principais indicadores.
- **Detalhamento** — análise detalhada das movimentações e categorias.

## Principais indicadores

- Receita
- Despesas
- Custos
- Saídas
- Lucro

## Tecnologias e recursos

- Power BI Desktop
- Power Query
- DAX
- Modelagem de dados
- Power BI Project (`.pbip`)
- TMDL (Tabular Model Definition Language)
- Git / GitHub

## Estrutura do projeto

```text
.
├── Dash Financeiro - Vendas.pbip
├── Dash Financeiro - Vendas.Report/
├── Dash Financeiro - Vendas.SemanticModel/
├── .gitignore
└── README.md
```

O projeto está salvo no formato **PBIP**, permitindo versionar separadamente as definições do relatório e do modelo semântico.

## Fontes de dados

As planilhas de origem **não estão incluídas neste repositório**. Os caminhos locais foram neutralizados para publicação e apontam para a estrutura genérica abaixo:

```text
C:\Dados\DashboardFinanceiro\BaseDados
C:\Dados\DashboardFinanceiro\Planilhas Financeiro
```

Para atualizar os dados no Power BI, ajuste as origens no **Power Query** para o local onde as bases estiverem armazenadas no seu computador.

Arquivos de origem referenciados pelo projeto incluem:

- `Pagamentos.xlsx`
- `Recebimentos.xlsx`
- `CadastroPlanoContas.xlsx`

## Como abrir

1. Clone ou baixe este repositório.
2. Abra `Dash Financeiro - Vendas.pbip` no Power BI Desktop.
3. Ajuste as fontes de dados no Power Query, caso deseje atualizar o modelo.
4. Atualize os dados e salve o projeto.

## Controle de versão

Arquivos locais e de cache do Power BI, como `localSettings.json` e `cache.abf`, não são versionados.

---

Projeto desenvolvido para fins de estudo, portfólio e demonstração de habilidades em Business Intelligence.
