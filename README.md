<sub> 📂 Projeto EDA - Análise Exploratória de Dados - Felipe V. Sousa

# 🪻 Espécies de Flores Iris

Este repositório tem como objetivo o estudo e a utilização de ferramentas para obter insights e informações valiosas de diversos conjuntos de dados.

[Visualização do Projeto](https://github.com/benzerinsio/EDA_iris_species/blob/main/EDA_Iris.ipynb)


## 🎯 **Objetivo da análise**

Vamos observar um conjunto de dados que representa várias características de diferentes espécies de flores iris, como o tamanho e largura de sépalas e pétalas.

Examinando e analisando os dados conseguimos chegar a uma conclusão interessante antes mesmo de verificar o nome das espécies. É possível fazer uma estimativa da quantidade de espécies diferentes apenas com a análise de dados. 

Aproveite!


## 📊 **Fonte de Dados**

Os dados utilizados nessa análise foram baixados da internet e correspondem à um csv possuindo as características das flores iris - um conjunto de dados sem o nome das espécies e depois verificando a análise com o conjunto de dados que contém o nome das espécies.

## 💬 Conclusão

Neste projeto, realizamos uma Análise Exploratória de Dados (EDA) no conjunto de dados Iris, inicialmente desconsiderando o nome das espécies. 

O foco foi explorar e tratar os dados numéricos, aplicando técnicas de clustering para identificar padrões. 

Utilizando o método K-Means, calculamos o WCSS (Within-Cluster Sum of Squares) e aplicamos o método do cotovelo, que sugeriu a existência de 3 clusters distintos. 

Ao validar os resultados com a coluna de espécies, confirmamos que os clusters correspondiam às 3 espécies de Iris presentes no conjunto de dados. 

Este exercício demonstrou a eficácia do clustering não supervisionado em identificar estruturas naturais nos dados, alinhando-se com a classificação real das espécies.