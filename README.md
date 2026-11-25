 # 🐼 Módulo 04 - Introdução ao Pandas e Carregamento de Dados

Repositório dedicado aos estudos e exercícios práticos do **Módulo 04** do curso **Profissão: Cientista de Dados (EBAC)**, focado na criação, estruturação e manipulação de dados utilizando **Pandas** e **NumPy**.

## 💡 Como elaborei este projeto

Desenvolvi este projeto de forma prática em Jupyter Notebook, aplicando passo a passo os fundamentos das estruturas de dados do Pandas na resolução de problemas reais e simulados:

1. **Manipulação de Séries Temporais (`pd.Series`):** Utilizei dados históricos de anomalia térmica global da NASA/GISS (de 1900 a 2020) para praticar diferentes formas de criação e indexação de séries — tanto a partir de listas com índices customizados quanto diretamente via dicionários Python.
2. **Geração de Dados e Criação de DataFrames (`pd.DataFrame`):** Simulei uma matriz de dados utilizando distribuição normal com NumPy (`np.random.normal`) e a converti em um DataFrame estruturado, customizando os nomes das colunas (`x1`, `x2`, `x3`) e ajustando a indexação das linhas de 1 a 20 (`np.arange`).
3. **Engenharia de Atributos e Operações Vetorizadas:** Criei novas colunas calculadas diretamente sobre o DataFrame, aplicando operações por linha (`mean(axis=1)`) e transformações matemáticas vetorizadas com NumPy (`np.log`) para gerar indicadores derivados.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas** (criação e manipulação de `Series` e `DataFrames`)
* **NumPy** (geração de arrays aleatórios e cálculos matemáticos vetorizados)
* **Jupyter Notebook** (Anaconda / Google Colab)
