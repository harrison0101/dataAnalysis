Este projeto realiza uma análise exploratória e limpeza de dados utilizando um dataset de crimes e segurança pública. O notebook da_01.ipynb conduz todo o fluxo de trabalho típico de um projeto de análise de dados, desde a importação e inspeção inicial até visualizações e preparação do dataset limpo.

O objetivo principal é identificar padrões de criminalidade relacionados a tipo de crime, localização, horário, dia da semana, características das vítimas e outros fatores.

🧰 Tecnologias Utilizadas

Python 3

Pandas — manipulação de dados

NumPy — operações numéricas

Matplotlib — geração de gráficos

Google Colab (ou Jupyter Notebook)

📑 Estrutura do Notebook
1. Importação de Dados

Carregamento do arquivo CSV contendo registros de crimes.

2. Inspeção Inicial

Visualização inicial (head, info, describe)

Verificação de missing values

Verificação de duplicatas

3. Limpeza e Padronização

Inclui:

Remoção de espaços em colunas categóricas

Conversão de colunas para tipos apropriados

Criação da coluna datetime

Extração de year, month, hour, weekday

Correção de valores de gênero

Filtragem de idades inválidas

Criação de faixas etárias (bins)

Remoção de duplicatas por ID

Validações com assert

O arquivo limpo é salvo como
crime_safety_dataset_clean.csv.

4. Análises Exploratórias (EDA)

Gráficos e contagens:

Tipos de crimes mais comuns

Crimes por horário

Crimes por cidade

Crimes por dia da semana

📈 Gráficos Gerados

Top 10 tipos de crimes (barras)

Ocorrências por hora do dia (linha)

Top 10 cidades com mais ocorrências

Ocorrências por dia da semana

📂 Dados de Saída

O notebook gera como resultado final:

crime_safety_dataset_clean.csv


Dataset preparado e validado para análises futuras ou criação de modelos preditivos.

🚀 Como Executar o Projeto
✔️ 1. Clone ou baixe o repositório
git clone https://github.com/seu-repositorio.git

✔️ 2. Instale as dependências
pip install pandas numpy matplotlib

✔️ 3. Abra o notebook
jupyter notebook da_01.ipynb


Ou envie o notebook para o Google Colab.

📝 Possíveis Extensões do Projeto

Modelos de machine learning para prever tipos ou horários de crimes

Análise temporal avançada (Time Series)

Dashboard interativo (Power BI, Streamlit, Dash)

Enriquecimento com dados externos (clima, eventos, localização)
