# Iris Dataset — Classification Project

## Objetivo
Explorar o dataset Iris e desenvolver um modelo de **classificação multiclasse**
capaz de identificar a espécie da flor com base em suas medidas físicas.

---

## Dataset
O Iris Dataset é um conjunto de dados clássico da área de Machine Learning,
disponibilizado originalmente por Ronald Fisher.

- Fonte: UCI Machine Learning Repository
- Total de amostras: 150
- Classes:
  - Iris-setosa
  - Iris-versicolor
  - Iris-virginica

Cada classe possui 50 amostras balanceadas.

---

## Features
- Sepal length
- Sepal width
- Petal length
- Petal width

## Target
- Species (espécie da flor)

---

## Análise Exploratória (EDA)
- Verificação de tipos de dados e valores ausentes
- Análise estatística descritiva
- Visualizações para entender a separação entre as espécies

### Principais insights:
- As medidas das **pétalas** separam melhor as espécies do que as sépalas
- Iris-setosa é claramente separável das demais
- Iris-versicolor e Iris-virginica apresentam alguma sobreposição

---

## Visualizações
- Scatter plots entre petal length e petal width
- Scatter plots entre sepal length e sepal width
- Uso de cores para diferenciar as espécies

---

## Modelo
- Algoritmo: Logistic Regression (classificação multiclasse)
- Pré-processamento:
  - Padronização das features com `StandardScaler`
  - Codificação do target com `LabelEncoder`
- Divisão treino/teste com classes estratificadas

---

## Avaliação
- Métrica principal: Accuracy
- Resultado: **100% de acurácia no conjunto de teste**

> Este resultado é esperado para o Iris Dataset, devido à forte separação
entre as classes, especialmente quando utilizadas as medidas das pétalas.

---

## Tecnologias Utilizadas
- Python
- Pandas
- Matplotlib & Seaborn
- Scikit-learn

---

## Conclusão
O projeto demonstra um pipeline completo de Machine Learning,
incluindo exploração de dados, visualização, pré-processamento,
treinamento e avaliação de um modelo de classificação.

Apesar de simples, o Iris Dataset é ideal para demonstrar
boas práticas e fundamentos de ciência de dados.
