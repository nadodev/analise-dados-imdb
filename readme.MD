# Projeto de Análise Exploratória de Dados do IMDb

Este projeto envolve a realização de uma Análise Exploratória de Dados (EDA) em um dataset de filmes do IMDb. O objetivo é descobrir insights e padrões nos dados por meio de visualizações e análise estatística.

## Sumário

1. [Introdução](#introdução)
2. [Dataset](#dataset)
3. [Instalação](#instalação)
4. [Uso](#uso)
5. [Análise Exploratória de Dados](#análise-exploratória-de-dados)
6. [Resultados](#resultados)

## Introdução

O Projeto de EDA do IMDb tem como objetivo explorar um dataset de filmes do IMDb, focando em diversos aspectos como avaliações, gêneros, diretores, entre outros. Ao analisar esses dados, podemos obter insights sobre tendências na indústria cinematográfica, gêneros populares e a relação entre diferentes atributos dos filmes.

## Dataset

O dataset usado neste projeto contém as seguintes colunas:

- **Title**: Título do filme.
- **Director**: Diretor do filme.
- **Star Cast**: Elenco principal do filme.
- **Year**: Ano de lançamento do filme.
- **IMDb Rating**: Avaliação do IMDb para o filme.
- **MetaScore**: Avaliação MetaScore para o filme.
- **Genre**: Gênero principal do filme.
- **Second_Genre**: Segundo gênero do filme.
- **Third_Genre**: Terceiro gênero do filme.
- **Duration (minutes)**: Duração do filme em minutos.

## Instalação

Para executar este projeto, é necessário ter Python instalado. Além disso, você precisa instalar as seguintes bibliotecas:

- pandas
- matplotlib
- seaborn
- scikit-learn

Você pode instalar as bibliotecas necessárias usando o seguinte comando:

```bash
pip install pandas matplotlib seaborn scikit-learn
```


## Uso

1. Clone este repositório:

```bash
git clone https://github.com/nadodev/analise-dados-imdb.git
cd analise-dados-imdb
```

## Análise Exploratória de Dados

O processo de EDA neste projeto inclui os seguintes passos:

1. **Carregamento e Limpeza dos Dados**:
    - Carregamento do dataset.
    - Tratamento de valores ausentes.
    - Exploração básica dos dados (head, describe).

2. **Análise Visual**:
    - Visualizações para explorar distribuições, correlações e padrões nos dados.
    - Gráficos de barras, histogramas, scatter plots, entre outros.

3. **Análise Estatística**:
    - Cálculo de estatísticas descritivas como média, mediana, desvio padrão, etc.
    - Correlação entre variáveis para entender relações entre os atributos dos filmes.

## Resultados

Os resultados da EDA fornecem insights sobre características dos filmes, preferências de gênero, distribuições de avaliações, entre outros aspectos relevantes para o dataset do IMDb.

---