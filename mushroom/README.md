# Mushroom Dataset

## Objetivo
Analisar o Mushroom Dataset e construir um modelo de classificação
capaz de prever se um cogumelo é comestível ou venenoso com base
em suas características físicas.

## Dataset
Mushroom Dataset disponibilizado pelo UCI Machine Learning Repository.

## Etapas
- Análise exploratória dos dados
- Tratamento de variáveis categóricas
- Treinamento de modelo de classificação binária

### EDA Insights
- Algumas features apresentam separação quase perfeita entre classes
- A feature `odor` é extremamente informativa para classificação
- Existem colunas com apenas um valor e que não contribuem para o modelo

## Análise Exploratória
- Dataset composto exclusivamente por variáveis categóricas
- Algumas features apresentam forte relação com o target
- Identificação de colunas irrelevantes e valores desconhecidos

### Model Interpretation
The model achieved very high accuracy due to the presence of highly informative
categorical features such as `odor`, which almost perfectly separates edible
and poisonous mushrooms. This behavior is well known for this dataset.

## Modelo
- Classificação binária com Logistic Regression
- Variáveis categóricas tratadas com One-Hot Encoding
- Alta acurácia devido à forte relação entre algumas features e o target
