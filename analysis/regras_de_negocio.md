# Regras de Negócio e Transformações de Dados

Este documento descreve as principais regras aplicadas na preparação dos dados e construção da base analítica utilizando SQL e PostgreSQL.

O objetivo foi garantir consistência nos cálculos e permitir análises corretas.

---

## Consolidação da Base de Dados

Os dados foram extraídos de múltiplas tabelas e consolidados utilizando SQL.

Foram aplicadas junções (JOIN) para integrar informações de:

- Vendas  
- Leads  
- Produtos  
- Lojas  
- Clientes  
- Visitas  

A consolidação garantiu uma visão única e estruturada para análise.

---

## Tratamento de Dados

Durante a preparação da base, foram aplicadas transformações para garantir qualidade dos dados:

- Remoção de valores nulos  
- Padronização de campos  
- Ajuste de formatos numéricos  
- Tratamento de inconsistências  

Essas etapas foram essenciais para evitar erros nas análises.

---

## Definição das Métricas

As métricas foram construídas diretamente em SQL, garantindo consistência nos cálculos.

Regras aplicadas:

- Receita = soma dos valores de vendas  
- Leads = contagem de registros de entrada no funil  
- Vendas = contagem de conversões  
- Taxa de conversão = vendas / leads  
- Ticket médio = receita / número de vendas  

---

## Agrupamentos e Segmentações

As análises foram organizadas utilizando agrupamentos por:

- Data (dia, mês, período)  
- Estado  
- Loja  
- Marca  
- Produto  

Isso permitiu análises em diferentes níveis de granularidade.

---

## Organização Temporal

Os dados foram estruturados para permitir análises ao longo do tempo.

Foram consideradas:

- Evolução diária  
- Comparação entre períodos  
- Análise de tendência  

---

## Estrutura Analítica

A base foi organizada para suportar:

- Análise de funil de vendas  
- Análise de desempenho comercial  
- Análise de comportamento de usuários  

A estrutura permite cruzar dados de diferentes áreas do negócio.

---

## Objetivo das Transformações

As transformações realizadas tiveram como objetivo:

- Garantir consistência nos dados  
- Melhorar a confiabilidade das métricas  
- Evitar erros de cálculo  
- Permitir análises corretas  
- Simular um cenário real de análise de dados  