# Rede Neural Penguins
 Uso de rede neural para fazer a classificacao de especies de penguins

 Trabalho realizado para a manteria de INTELIGENCIA COMPUTACIONAL durante a 6 semestre de Engenharia de Computação

### Bibliotecas usadas 
 - scikit-learn
 - Matplotlib
 - Numpy
 - Pandas
 - Tensorflow whit keras

### Link do banco de dados utilizado 
[Penguins.csv](https://raw.githubusercontent.com/NathanSFon/Perceptron/main/penguins.csv)

## Objetivo 

No banco de dados utilizado temos como base 3 especies de pinguin, sendo elas: Adelia, Chinstrap e Gentoo. Cada linha representa um individuo da especia e suas caracteristicas, dividitos em 7 colunas. 

Para os dados de treinamento separamos apenas as colunas referentes as caracteristicas especificas de cada pinguin, associando a especie do pinguim

![Grafico de comparção entre a massa corpora e as caracteristicas de cada especie](https://github.com/NathanSFon/Rede_neural_Penguins/blob/main/Graficos/comparacao_massaXcorpo.png)

A partir desses dados, temos por meta realizar o treinamento de uma rede neural para poder, pelas caracteristicas de um penguin, classificar qual e a especie de pinguim.

## Codigo 
Para realizar a todo o processamento e treino da rede neural utilezei a plataforma do Google Colaboratory ![colaboratory](https://blog.netdata.cloud/assets/images/colab-a699aa465989ccdc63feb80cdd107224.png). Devido ao bom desempenho de processamento e a facilidade que o Colab traz para podermos utilizar as principais bibliotecas que precisaremos para o treinamento da rede neural

Segue o link do notebook do colab [Rede Neural](https://colab.research.google.com/drive/1-Du_dW43OsaU605Na01wbHvA4qB6NHXK?usp=sharing)
Voce pode acessar e realizar os teste. 
No final do notebook temos uma breve analise do desempenho da rede neural
