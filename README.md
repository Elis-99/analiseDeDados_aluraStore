# Análise de Desempenho das Lojas e Recomendação de Venda

## Visão Geral

Este projeto teve como objetivo analisar o desempenho de quatro lojas, com o objetivo de identificar qual delas seria a mais indicada para ser vendida. Para isso, foram utilizados dados de faturamento, frete médio, avaliações de clientes, produtos mais vendidos e categorias mais vendidas.

## Metodologia

1.  **Coleta e Importação de Dados:** Os dados de cada loja foram coletados a partir de arquivos CSV e importados para o Google Colab utilizando a biblioteca `pandas`.

2.  **Análise Exploratória de Dados (EDA):** Realizou-se uma análise exploratória para entender as características de cada loja, incluindo:

    *   Faturamento total.
    *   Frete médio.
    *   Avaliação média dos clientes.
    *   Identificação dos produtos mais vendidos.
    *   Identificação das categorias de produtos mais vendidas.
3.  **Visualização de Dados:** Foram criados gráficos para representar visualmente os resultados da análise, facilitando a identificação de padrões e tendências. Utilizou-se a biblioteca `matplotlib.pyplot` para criar gráficos de barras, histogramas e gráficos de linhas.

4.  **Relatório de Recomendação:** Com base nos dados analisados, foi elaborado um relatório para recomendar qual loja deveria ser vendida, justificando a decisão com base nos resultados obtidos.

## Tecnologias Utilizadas

*   **Python:** Linguagem de programação utilizada para a análise de dados e criação dos gráficos.
*   **Pandas:** Biblioteca utilizada para manipulação e análise de dados tabulares.
*   **Matplotlib:** Biblioteca utilizada para a criação de gráficos e visualizações.
*   **Google Colab:** Plataforma utilizada para execução do código e criação do relatório.

## Resultados

A análise revelou os seguintes dados para cada loja:

#### Loja 1

*   **Faturamento:** R$ 1.534.509,12
*   **Frete Médio:** R$ 34,69
*   **Avaliação Média:** 3.97
*   **Produto Mais Vendido:** Micro-ondas
*   **Categoria Mais Vendida:** Móveis

#### Loja 2

*   **Faturamento:** R$ 1.488.459,06
*   **Frete Médio:** R$ 33,62
*   **Avaliação Média:** 4.03
*   **Produto Mais Vendido:** Livro: Iniciando em Programação
*   **Categoria Mais Vendida:** Móveis

#### Loja 3

*   **Faturamento:** R$ 1.464.025,03
*   **Frete Médio:** R$ 33,07
*   **Avaliação Média:** 4.04
*   **Produto Mais Vendido:** Kit banquetas
*   **Categoria Mais Vendida:** Móveis

#### Loja 4

*   **Faturamento:** R$ 1.384.497,58
*   **Frete Médio:** R$ 31,28
*   **Avaliação Média:** 3.99
*   **Produto Mais Vendido:** Cama box
*   **Categoria Mais Vendida:** Móveis

Com base nesses dados, foi recomendado que a **Loja 4** fosse vendida, devido ao seu menor faturamento e a um frete médio mais baixo, o que pode indicar uma estratégia de preços menos eficiente ou um mix de produtos menos lucrativo.

## Conclusão

Este projeto demonstrou a aplicação de técnicas de análise de dados para auxiliar na tomada de decisões estratégicas em um contexto de negócios. A utilização de Python e suas bibliotecas permitiu a coleta, análise e visualização dos dados de forma eficiente, culminando na elaboração de um relatório com uma recomendação embasada em evidências.
