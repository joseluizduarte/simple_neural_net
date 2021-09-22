# simple_neural_net

Modelo simples de rede neural para identificação dos números 0 e 5 em imagens do MNIST dataset.

Configuração do ambiente fornecida pelo repositório: https://github.com/fastai/fastbook





### O modelo

Foi utilizada uma rede neural simples com três camadas:

* a primeira camada linear com diversas features

* uma camada não-linear

* última camada linear com 1 feature



### Parâmetros de treinamento

* Utilizou-se learning rate igual a 0.1 pois esse valor foi suficiente para que o treinamento não apresentasse divergência.
* A partir de diferentes valores testados, o batch size de 128 foi o que apresentou uma maior velocidade de aumenta da acurácia durante o treinamento.
* Das três opções de features (20, 30, 50) testadas, todas apresentaram resultados satisfatórios.



### Resultados

Todas 3 opções de treinamento apresentadas forneceram acurácia maior que 98.5% e chegaram a ultrapassar 99% em algumas situações de treinamento. Uma vez que os pesos são inicializados de forma aleatória, pode haver pequenas diferenças entre as acurácias alcançadas em diferentes treinamentos usando os mesmos parâmetros.
