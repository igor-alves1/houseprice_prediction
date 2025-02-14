# Previsão de preços de casas

O projeto contido neste repositório é um modelo de Regressão Linear, que utiliza a técnica de mínimos quadrados, cujo objetivo é prever o preço
de casas, dadas algumas _features_, como tamanho, avaliação da vista, avaliação das condições da casa, número de quartos, entre outros. Este projeto
foi realizado utilizando este [_dataset_](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction), o qual possui informações sobre vendas
de casas no Condado de King, EUA.

Este projeto foi realizado com o objetivo tanto de praticar e aprender mais sobre treinamento e avaliação de modelos de _Machine Learning_, 
como de praticar a criação de gráficos e utilizar ferramentas de visualização de dados, permitindo o estududo das previsões de maneira estatística.

### Execução

Para executar o projeto, basta instalar as bibliotecas necessárias, presentes no arquivo ```requirements.txt```, e rodar o arquivo 
Jupyter Notebooks ```main.ipynb```.

### Resultados

É possível observar que os resultados foram positivos e seguem uma tendência linear. Outro resultado interessante é que o 
modelo treinado com apenas as _features_ contendo as variáveis _dummies_ do _zipcode_, _sqft_living_, _lat_ e _view_, performou de maneira semelhante ao modelo com todas as _features_,
mostrando que, em razão de multicolinearidade, as _features_ excluídas não agregavam tanto ao modelo. 
