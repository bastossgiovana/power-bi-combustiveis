# Dashboard de Preços de Combustíveis

Este projeto foi desenvolvido como parte prática do curso **"Analisando dados de forma inteligente"**, da **Alura**. A proposta é utilizar um dataset real de preços de combustíveis no Brasil para construir um painel que permita entender rapidamente onde a gasolina está mais cara, quais bandeiras praticam os menores preços e como os valores vêm se movendo ao longo do tempo.

## Sobre o projeto

O dashboard foi construído a partir de um dataset público de preços de combustíveis, com amostras coletadas em revendas espalhadas por todo o Brasil. A análise cobre os principais tipos de combustível (Diesel, Diesel S10, Etanol, Gasolina, Gasolina Aditivada e GNV) e permite cruzar essas informações por estado, bandeira e revenda.

O painel foi dividido em duas visões, pensadas para responder perguntas diferentes:

- **Último mês** — foco no cenário mais recente, útil para acompanhar o comportamento atual dos preços.
- **Geral** — visão histórica completa, útil para identificar tendências e comparar a variação de preços ao longo do tempo.

## Principais análises disponíveis

- Comparação dos estados com os combustíveis mais caros e mais baratos do país.
- Ranking das bandeiras (distribuidoras) com os menores preços médios.
- Diferença entre o preço mínimo e o máximo dentro de cada estado 
- Evolução da média geral dos combustíveis dia a dia, com linha de tendência para facilitar a leitura do movimento.
- Número de revendas que praticam preços acima da média nacional.

## Prévia do dashboard

| Visão "Último mês" | Visão "Geral" |
|---|---|
| Preços mais recentes por estado, ranking de bandeiras e série temporal do período mais atual | Preços consolidados de todo o histórico, ranking geral de bandeiras e variação percentual completa |

## Como o painel está organizado

- **Filtros laterais** — por tipo de produto, bandeira e revenda, permitindo ir além da visão geral e investigar casos específicos.
- **Cartões de indicadores (KPIs)** — total de amostras analisadas e número de revendas acima da média, indicando o tamanho da base e possíveis preços fora da curva.
- **Gráfico de barras** — preço médio da gasolina por estado (UF), ordenado do mais caro para o mais barato.
- **Ranking de bandeiras** — tabela com as distribuidoras de menor preço médio.
- **Tabela por estado** — preço máximo, mínimo e diferença percentual, mostrando o quanto o preço pode variar dentro de uma mesma UF.
- **Série temporal** — evolução da média geral de combustíveis por dia, com linha de tendência.

## Tecnologias e ferramentas

- Power BI — construção do dashboard e das visualizações interativas.
- Power Query — extração, limpeza e tratamento dos dados antes da modelagem.
- DAX (Data Analysis Expressions) — criação de medidas, colunas calculadas e indicadores (KPIs) utilizados no painel.

## Principais aprendizados

Este projeto reforçou alguns pontos importantes em análise e visualização de dados:

- Escolher o tipo certo de gráfico para cada pergunta faz diferença na clareza da informação.
- KPIs eficazes comunicam uma ideia central de forma rápida, sem necessidade de explicação adicional.
- Filtros interativos dão autonomia ao usuário para explorar os dados sob diferentes ângulos.
- Comparar "último mês" com "visão geral" ajuda a evitar conclusões precipitadas baseadas apenas no dado mais recente.

