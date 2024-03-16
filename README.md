# Deep-Learning-Project
Este trabalho foi desenvolvido no âmbito da disciplina de Deep Learning da Pós Graduação Data Science e Business Inteligence. 

# Visão Geral
O objetivo deste programa é desenvolver um modelo de Machine Learning utilizando uma variante de redes neurais (TensorFlow/Keras) para classificar a emoção associada a expressões do Twitter. Especificamente, o objetivo é criar um modelo capaz de analisar o texto das expressões e atribuir uma das seis emoções pré-definidas a cada uma delas.

# Requisitos

Bibliotecas utilizadas: 
• Numpy (pip install numpy) 
• Tensorflow
• Pandas 
• matplotlib: para fazer plot da representação gráfica

# Implementação 

Pré-processamento dos Dados:

1. Importação da base de dados

   ![image](https://github.com/Monpintc/Deep-Learning-Project/assets/154018252/3bd3b903-628c-44a5-9b15-8bf56c9ae74d)

2. Limpeza dos dados: remoção de pontuações, conversão do texto para minusculas, remoção dos espaços brancos, tratamento de siglas e de emojis e stemming para reduzir as palavras à sua forma raíz.
3. Definição do dicionário: o código define um dicionário que contém abreviações comumente usadas em conversas do twitter com os significados correspondentes escritos por extenso.  

4. Tokenization: Etapa crucial no processamento de dados que envolve a conversão de dados textuais em dados numéricos. 

Modelagem

Construção e treino do modelo de Machine Learning para classificar as emoções das expressões do Twitter.

Avaliação

Avaliar o desempenho do modelo treinado, usando métricas como acurácia, precisão, recall e F1-score.

Resultados

![image](https://github.com/Monpintc/Deep-Learning-Project/assets/154018252/98807465-64b3-4471-b1b7-eaa5fe2e567f)



# Autores

João Santos & Mónica Coelho
