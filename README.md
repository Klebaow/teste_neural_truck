# teste_neural_truck

'''Documentação do Script de Simulação de Caminhão

Este script Python simula o comportamento de um caminhão em várias condições de estrada e clima, e treina uma rede neural para prever a condição de condução com base em várias características do caminhão.

Variáveis Iniciais:

ang_direct: Ângulo atual da direção em graus.
cond_estrada: Condições da estrada (0: ruim, 1: média, 2: boa).
carga_truck: Peso da carga do caminhão em kg.
consu_combus: Consumo de combustível em litros por 100km.
cond_clima: Condições climáticas (0: ruim, 1: média, 2: boa).
cond_condu: Condição de condução (0: insegura, 1: segura).
Simulação de Dados: O script gera um conjunto de dados simulados com 10.000 observações. Cada observação inclui a velocidade atual, aceleração, posição do acelerador e do freio, rotação do motor, ângulo de direção, condições da estrada, peso da carga, consumo de combustível, condições climáticas e condição de condução.

Rede Neural: O script define uma classe NeuralNetwork que implementa uma rede neural simples com duas camadas ocultas e uma camada de saída. A rede é treinada usando o conjunto de dados simulados.

Treinamento e Avaliação: O conjunto de dados é dividido em conjuntos de treinamento, validação e teste. A rede neural é treinada no conjunto de treinamento e as previsões são feitas no conjunto de teste.

Uso: Para usar este script, você pode ajustar as variáveis iniciais e os parâmetros de treinamento conforme necessário. Depois de treinar a rede neural, você pode usá-la para fazer previsões sobre a condição de condução com base nas características do caminhão. As previsões são probabilidades que indicam a probabilidade da condição de condução ser segura.

'''

'''
Observando os resultados, parece que a rede neural está prevendo a mesma probabilidade para todas
 as amostras de teste. Isso indicar que a rede neural não está aprendendo
corretamente com os dados de treinamento.

'''
