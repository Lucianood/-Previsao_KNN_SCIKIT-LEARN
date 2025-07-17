# 🔍 Previsão com KNN usando Scikit-Learn

Este projeto tem como objetivo aplicar o algoritmo **KNN (K-Nearest Neighbors)** em um conjunto de dados fictício, demonstrando uma aplicação prática de Machine Learning supervisionado com a biblioteca Scikit-Learn, desde a preparação dos dados até a avaliação de resultados.

---

## 🧠 Objetivo

Utilizar o algoritmo de classificação KNN para prever uma categoria (rótulo) com base em dados de entrada, analisando a acurácia do modelo em diferentes valores de `k`.

---

## 📊 Tecnologias Utilizadas

- Python 3.x
- Scikit-Learn
- Pandas
- Matplotlib (opcional para visualizações)

---

## 📁 Estrutura do Projeto

📦 Previsao_KNN_SCIKIT-LEARN
┣ 📜 knn_modelo.py # Código principal com o treinamento do modelo
┣ 📄 dados.csv # Base de dados fictícia utilizada no projeto
┣ 📄 README.md # Este arquivo


---

## ⚙️ Funcionalidades

- Leitura e tratamento de dados com Pandas
- Separação entre dados de treino e teste
- Treinamento de modelo KNN com Scikit-Learn
- Avaliação da acurácia do modelo
- Testes com diferentes valores de `k`
- Exibição de previsões e comparação com os dados reais

---

## 🧪 Como Executar

1. Clone este repositório:
https://github.com/Lucianood/-Previsao_KNN_SCIKIT-LEARN.git

Instale as dependências (caso ainda não tenha):
pip install scikit-learn pandas

Execute o arquivo Python:
python knn_modelo.py

📈 Exemplo de Saída

Treinando modelo com K = 3
Acurácia do modelo: 0.80
Previsões: [1 0 1 1 0]
Reais:     [1 0 1 0 0]
