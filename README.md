# Visão Geral
Este repositório contém a solução desenvolvida por nossa equipe para coletar dados da Internet por meio de técnicas de Web Scraping.

## Coleta de Dados
Realizamos a coleta de dados utilizando técnicas de web scraping em uma plataforma de venda de imóveis do município de Fortaleza. Durante esse processo, dedicamos atenção especial à identificação de dados faltantes, adotando estratégias apropriadas para lidar com essas lacunas e garantir a integridade do conjunto de dados.

## Pré-processamento de Dados
Após a coleta, avançamos para o pré-processamento dos dados. Implementamos as seguintes transformações:

- Dados Faltantes: Optamos por imputar os dados faltantes utilizando uma abordagem específica para preservar a qualidade dos dados.
- Transformação de Dados Categóricos: Realizamos a conversão de dados categóricos para um formato aceito pelos algoritmos da biblioteca scikit-learn.
- Escala de Features: Mudamos a escala das features coletadas para garantir comparações significativas entre as variáveis independentes.

## Análise Estatística
Conduzimos uma análise estatística abrangente dos dados, exibindo estatísticas simples, como média, mediana e desvio padrão. Utilizamos gráficos, incluindo boxplots, para comparar diferentes features e extrair conclusões valiosas sobre o conjunto de dados.

## Seleção de Características
Empregamos técnicas avançadas de seleção de características para gerar múltiplas versões do conjunto de dados. Isso incluiu métodos como análise de importância de características e eliminação de características redundantes, otimizando assim a representação dos dados para os algoritmos subsequentes.
