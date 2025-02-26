# 🪷 Espécies de Flores Iris  
*Projeto de Análise Exploratória de Dados (EDA) - Felipe V. Sousa*

Bem-vindo(a)! Este repositório apresenta uma **Análise Exploratória de Dados (EDA)** no conjunto de dados das flores Iris, explorando padrões e aplicando clustering para estimar o número de espécies.

🔗 [Visualizar o Notebook](https://github.com/benzerinsio/FloralSpecies-EDA/blob/main/EDA_iris.ipynb)

## 🎯 Objetivo da Análise

Analisar um conjunto de dados com características das flores Iris (comprimento e largura de sépalas e pétalas) para identificar padrões e estimar o número de espécies distintas, usando técnicas exploratórias e clustering, sem depender inicialmente dos rótulos das espécies.

## 📊 Fonte de Dados

Os dados provêm de um arquivo CSV disponível publicamente, contendo características das flores Iris. A análise utiliza duas versões: uma sem os nomes das espécies e outra com os rótulos para validação.

## 🛠️ Bibliotecas Utilizadas

- **Pandas**: Manipulação e análise de dados.  
- **NumPy**: Cálculos numéricos e operações matemáticas.  
- **Seaborn**: Visualizações estatísticas aprimoradas.  
- **Matplotlib**: Geração de gráficos e plots.  
- **Scikit-learn**: Implementação do algoritmo K-Means e cálculo do WCSS.

## 💬 Conclusão

Este projeto realizou uma **Análise Exploratória de Dados (EDA)** no dataset Iris, inicialmente sem os rótulos das espécies. Usando o algoritmo K-Means e o método do cotovelo (baseado no WCSS), identificamos 3 clusters distintos, que, ao serem validados com os rótulos, corresponderam às 3 espécies reais. O estudo destacou a eficácia do clustering não supervisionado para revelar padrões naturais nos dados.