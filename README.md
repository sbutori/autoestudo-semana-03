
# Relatório de Autoestudo - Semana 03

## Configurações iniciais e importação do dataset

Nessa seção fizemos a importação das bibliotecas necessárias e do dataset a partir do Google Drive.

## Pré-processamento

Realizamos o encoding das labels ("Intenção") e a tokenização e conversão em sequência das features ("Pergunta"). Também separamos um conjunto de treino e de validação.

## Construir e treinar o modelo

Treinamos um modelo no Tensorflow com base em uma Embedding Layer. No dataset de treino, a acurácia foi de cerca de 83% no conjunto de treino e 60% no conjunto de validação.

## Avaliar o modelo

Avaliamos e geramos um report do modelo, obtendo um f1-score médio de 56% no conjunto de validação.

## Tensorboard

Uma visualização gráfica da evolução do treino foi providenciada pelo Tensorboard do Tensorflow.

## Implementação alternativa com word2vec

Fizemos uma implementação alternativa com word2vec e o um classificador RandomForest. Nesse cenário, obtivemos um f1-score médio de 45%, considerávelmente inferior ao obtido com o Tensorflow (56%).

## Visualização do word2vec no Embedding Projector

O Embedding Projector do Tensorflow permite visualizar os embeddings (representação vetorial das palavras) gerados pelo word2vec em alta dimensão. Palavras semelhantes ficam próximas às outras nessa representação 3D.
