# Dashboard de Fluxo de Caixa  — Power BI

Dashboard desenvolvido no **Microsoft Power BI** para análise e acompanhamento de movimentações financeiras, permitindo visualizar receitas, despesas, saldo, margem e evolução financeira ao longo do período analisado.

Link do Projeto: https://gustagtdev.github.io/Dashboard-Fluxo-de-Caixa/
---

## 🎯 Objetivo

O objetivo deste projeto é transformar dados financeiros brutos em informações visuais que facilitem a análise e a tomada de decisões.

O dashboard permite responder perguntas como:

- Quanto foi recebido no período?
- Quanto foi gasto?
- Qual foi o saldo financeiro?
- Quais categorias geraram mais entradas?
- Quais categorias representaram maiores saídas?
- Como o saldo evoluiu ao longo dos meses?
- Qual foi a margem financeira?
- Quais foram os meses de melhor e pior desempenho?

---

## 🛠️ Ferramentas utilizadas

- **Microsoft Power BI**
- **Power Query** — tratamento e transformação dos dados
- **DAX** — criação de medidas e indicadores
- **Microsoft Excel** — fonte dos dados
- **Modelagem de dados** — organização e relacionamento das informações

---

## 📌 Principais indicadores

O dashboard apresenta os seguintes indicadores:

| Indicador | Descrição |
|---|---|
| 💰 Total de Entradas | Soma de todos os valores recebidos |
| 💸 Total de Saídas | Soma de todos os valores gastos |
| 📊 Saldo | Diferença entre entradas e saídas |
| 📈 Margem | Relação entre o saldo e o total de entradas |
| 📅 Saldo Acumulado | Evolução do saldo ao longo do período |

---

## 📑 Estrutura do Dashboard

### 1. Visão Geral

Apresenta um resumo da situação financeira do período, incluindo:

- Total de entradas
- Total de saídas
- Saldo
- Evolução mensal das entradas
- Evolução mensal das saídas
- Saldo acumulado

Essa página funciona como uma visão executiva do desempenho financeiro.

---

### 2. Análise de Receita

Permite analisar a composição das entradas financeiras.

São apresentados:

- Total de receitas
- Receitas por categoria
- Distribuição das entradas
- Detalhamento das movimentações

As categorias permitem identificar quais fontes possuem maior participação na geração de receita.

---

### 3. Análise de Despesa

Apresenta a distribuição das saídas financeiras por categoria.

A análise permite identificar:

- Principais categorias de gastos
- Participação de cada categoria nas despesas
- Valores gastos
- Detalhamento das movimentações

Essa visão facilita a identificação das categorias que possuem maior impacto sobre o orçamento.

---

### 4. Análise Temporal

Analisa a evolução financeira ao longo dos meses.

São apresentados:

- Saldo acumulado
- Margem financeira
- Entrada mensal
- Saída mensal
- Saldo mensal
- Evolução do saldo acumulado

A análise temporal permite identificar períodos de maior ou menor desempenho financeiro.

---

## 📊 Principais análises

Entre os principais insights possíveis estão:

### Receitas

A análise por categoria permite identificar as principais fontes de entrada e compreender quais atividades possuem maior participação no resultado financeiro.

### Despesas

A análise das despesas permite identificar as categorias que mais consomem recursos, possibilitando uma avaliação mais detalhada dos gastos.

### Saldo

O saldo é calculado pela diferença entre o total de entradas e o total de saídas:

**Saldo = Entradas − Saídas**

### Margem

A margem representa a relação entre o saldo obtido e o total de entradas:

**Margem = (Entradas − Saídas) / Entradas**

### Evolução temporal

O saldo acumulado permite acompanhar como o resultado financeiro evoluiu durante o período analisado.

---

## 🎨 Visualizações utilizadas

O projeto utiliza diferentes tipos de visualizações de acordo com o objetivo da análise:

- **Cards** → indicadores financeiros
- **Gráficos de linha** → evolução temporal
- **Gráficos de barras** → comparação entre categorias
- **Tabelas** → detalhamento das movimentações
- **Filtros/segmentações** → exploração dos dados

A escolha dos visuais foi feita considerando o tipo de informação e a necessidade de comparação entre os dados.

---

## 📅 Período analisado

**Período dos dados:** Janeiro a Novembro de 2025

**Data de atualização:** 30/11/2025

> Dezembro de 2025 permanece disponível na estrutura de calendário, porém não é apresentado nos visuais que representam o período efetivamente analisado, pois não existem movimentações registradas para esse mês.

---

## 🧮 Medidas DAX

Algumas das principais medidas utilizadas no projeto incluem indicadores relacionados a:

- Total de Entradas
- Total de Saídas
- Saldo
- Margem
- Saldo Acumulado
- Análises mensais

Exemplo da lógica utilizada para o saldo:

```DAX
Saldo = [Total Entrada] - [Total Saída]
