# Análise de Funil de Vendas e Conversão

Este projeto foi desenvolvido com foco na aplicação de Análise de Dados utilizando **SQL** e **PostgreSQL** para construção da base analítica, e **Excel** para desenvolvimento do dashboard final, com o objetivo de analisar o desempenho do funil de vendas e os principais indicadores comerciais.

A proposta foi transformar dados brutos em uma visão analítica estruturada, permitindo acompanhar métricas como **receita, leads, vendas, taxa de conversão e ticket médio**, além de análises complementares sobre comportamento de usuários, desempenho por região, lojas e produtos.

O projeto simula um cenário real de análise comercial, estruturando um fluxo completo desde a manipulação dos dados até a construção de um painel analítico.

---
## Contexto Analítico

Em operações comerciais, a análise do funil de vendas é essencial para entender a eficiência da conversão e identificar gargalos ao longo da jornada do cliente.

Este projeto foi desenvolvido para analisar:

- Evolução da receita ao longo do tempo
- Volume de leads e vendas
- Taxa de conversão do funil
- Ticket médio
- Estados com maior volume de vendas
- Marcas mais vendidas
- Lojas com melhor desempenho
- Comportamento das visitas por dia da semana

O foco foi estruturar uma base analítica confiável e aplicar consultas SQL que sustentem uma leitura clara e consistente dos indicadores.

---

## Objetivos

- Construir uma base de dados analítica utilizando SQL
- Realizar tratamento e padronização dos dados
- Consolidar métricas de negócio com PostgreSQL
- Desenvolver um dashboard analítico no Excel
- Analisar o funil de vendas e conversão
- Identificar padrões de comportamento e desempenho
- Simular um cenário real de análise comercial

---

## Estrutura do Projeto

```bash
📁 analysis
┣ regras_de_negocio.md
┣ decisoes_analiticas.md

📁 dashboard
┣ dashboard_funil_vendas.xlsx

📁 assets
┣ video_demo.mp4
```

### Descrição das pastas

- **analysis** → Regras e decisões analíticas  
- **dashboard** → arquivo final do Excel  
- **assets** → vídeo demonstrando o dashboard  

---

## Tratamento e Modelagem dos Dados

A construção da base analítica foi realizada utilizando SQL no PostgreSQL, com foco na consistência e organização dos dados.

### Principais técnicas aplicadas:

- Junções entre tabelas (`JOIN`)
- Agregações (`SUM`, `AVG`, `COUNT`)
- Agrupamentos (`GROUP BY`)
- Tratamento de dados inconsistentes
- Padronização de campos
- Criação de métricas derivadas

A estrutura foi pensada para conectar dados de:

- Vendas  
- Produtos  
- Lojas  
- Clientes  
- Comportamento de navegação  

---

## Métricas e Indicadores

Principais KPIs desenvolvidos:

- Receita total  
- Quantidade de leads  
- Quantidade de vendas  
- Taxa de conversão (%)  
- Ticket médio  
- Vendas por estado  
- Vendas por marca  
- Vendas por loja  
- Volume de visitas por dia da semana  

Toda a lógica de cálculo está baseada em consultas SQL estruturadas.

---


[Adicione aqui o link do vídeo do projeto.](https://youtu.be/rzrr9z4iBL4?si=_SO6-J1kBcFl7qEr)

Exemplo:

```md
[▶️ Assistir demonstração do dashboard](./assets/video1.mp4)
```

Ou:

```md
[▶️ Assistir demonstração do dashboard](https://github.com/Analise-Funil-Vendas-e-Conversao/assets/video1.mp4)
```

---

## Considerações Finais

Este projeto demonstra a construção de uma solução completa de análise de dados aplicada ao contexto comercial, utilizando **SQL** e **PostgreSQL** para estruturação da base e **Excel** para visualização dos dados.

O foco foi garantir consistência na base analítica, qualidade nas métricas e clareza na visualização, reforçando a importância de um bom tratamento de dados antes da construção de dashboards.

---

## Insights Possíveis

- Identificação de gargalos no funil de conversão  
- Análise de eficiência por região  
- Relação entre visitas e conversão  
- Oportunidades de aumento de ticket médio  
