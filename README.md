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

Tarefa 03 -  # 🐼 Módulo 04 - Introdução ao Pandas e Carregamento de Dados

Repositório dedicado aos estudos e exercícios práticos do **Módulo 04** do curso **Profissão: Cientista de Dados (EBAC)**, abrangendo desde a criação de estruturas básicas até o consumo de APIs governamentais e análise de bases de dados públicas com **Pandas**, **NumPy** e **Requests**.

## 💡 Como elaborei este projeto

Estruturei o desenvolvimento em Jupyter Notebooks (Google Colab), evoluindo gradualmente da manipulação de estruturas em memória para a extração, tratamento e exportação de dados reais:

### 1. Estruturas de Dados e Operações Vetorizadas (`Tarefa 01`)
* **Séries Temporais (`pd.Series`):** Utilizei dados históricos de anomalia térmica global da NASA/GISS (1900–2020) para praticar a criação e indexação de séries a partir de listas e dicionários.
* **DataFrames e Transformações (`pd.DataFrame`):** Simulei matrizes com distribuição normal via NumPy (`np.random.normal`), customizei índices e colunas e apliquei cálculos vetorizados por linha (`mean(axis=1)`) e transformações logarítmicas (`np.log`).

### 2. Filtros Condicionais e Análise de Dados Reais (`Tarefa 02`)
* **Simulação de Vestibular (Operações entre DataFrames):** Calculei percentuais de acerto por disciplina, notas totais e apliquei filtros booleanos compostos (`|`, `>`, `==`) para segmentar candidatos aprovados acima da nota de corte e eliminados por critério de nota zero.
* **Dados de Vacinação COVID-19 no Acre (DATASUS):** Carreguei uma base real com mais de 96 mil registros (`pd.read_csv`), utilizando métodos como `.nunique()`, `.unique()`, `.value_counts()`, `.loc[]`, `.copy()` e `.drop_duplicates()` para levantar métricas de pacientes únicos, doses aplicadas, atendimento a menores de 18 anos e mapear os estabelecimentos de saúde atuantes.

### 3. Consumo de APIs Públicas e Manipulação de Strings (`Tarefa 03`)
* **Extração via API (`requests` + JSON):** Conectei diretamente à API de Pedidos de Verificação de Limites (PVL) do Tesouro Nacional (`apidatalake.tesouro.gov.br`), convertendo a resposta JSON em DataFrame estruturado.
* **Tratamento de Datas e Regex:** Analisei os status mais frequentes das solicitações e utilizei expressões regulares (`.str.extract('(\d{4})')`) sobre campos textuais (`data_status`) para extrair o ano e analisar sua distribuição histórica.
* **Modularização e Exportação:** Desenvolvi funções personalizadas em Python (`consulta_dados(uf, tipo_interessado)`) para automatizar consultas filtradas por estado e esfera administrativa, finalizando com a exportação dos resultados para formato `.csv`.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas** (leitura/escrita de CSV, filtros booleanos, agregações, manipulação de strings e limpeza de dados)
* **NumPy** (geração de dados aleatórios e operações matemáticas vetorizadas)
* **Requests** (requisições HTTP e consumo de APIs REST em JSON)
* **Jupyter Notebook / Google Colab**
