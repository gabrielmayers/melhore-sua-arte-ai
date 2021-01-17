# Melhore sua arte:
Projeto de IA para melhora de imagens - Hackathon CCR 2021

## O que é?

A ideia aqui e apresentar uma prova de conceito da nossa plataforma que utiliza IA para melhorar a qualidade de imagens.

## Como funciona?

Utilizamos um modelo de [Autoencoder](https://towardsdatascience.com/auto-encoder-what-is-it-and-what-is-it-used-for-part-1-3e5c6f017726) com camadas [convolucionais](https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53) para criar uma rede neural artificial. Depois, treinamos a rede utilizando a dataset aberto ["Fashion MNIST"](https://www.kaggle.com/zalando-research/fashionmnist) que contém imagens de peças de roupas.

Para treinar o modelo, criamos um novo dataset com imagens em má definição a partir do dataset original, dessa forma, nossa rede neural conseguiu aprender a diferença entre as imagens originais e as imagens com má definição.

## Resultados:

Após o treinamento do modelo, utilizamos a rede neural para corrigir imagens com má definição que criamos anteriormente. Os resultados podem ser visualizados abaixo:

![resultados: ](https://github.com/gabrielmayers/melhore-sua-arte-ai/blob/main/resultados.png)
