# Atividade_7

## Projeto de Classificação de Pessoas
Este projeto utiliza uma rede neural convolucional (CNN) para classificar imagens de pessoas em diferentes categorias. Ele foi desenvolvido com a biblioteca Keras e usa camadas convolucionais para extrair características das imagens, seguidas por camadas densas para realizar a classificação final.

## Descrição do modelo
O modelo é uma rede neural sequencial composta por várias camadas convolucionais e de normalização, seguidas por camadas densas e dropout para evitar overfitting. A camada de saída utiliza a função de ativação softmax para classificar as imagens em até 20 classes diferentes.

## Principais componentes do modelo:

Camadas Conv2D e MaxPooling2D para proteção de características.
Camadas de BatchNormalization para melhorar o desempenho e estabilizar o treinamento.
Camadas Dense com Dropout para a fase de classificação final.
Otimizador Adam e função de perda categorical_crossentropy.

## Instruções de instalação:

Os arquivos utilizados na atividade estão acima.



## Créditos
Este projeto foi desenvolvido por Alonso Sales, Layane Bentes, João Victor e Jaime Silva como parte de um projeto acadêmico em Sistemas de Informação. As bibliotecas utilizadas incluem Keras/TensorFlow para modelagem de redes neurais e Sklearn para avaliação de métricas.


