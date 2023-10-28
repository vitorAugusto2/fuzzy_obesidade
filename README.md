# LÓGICA FUZZY - OBESIDADE

## Descrição
O código foi desenvolvido com o propósito de criar um sistema de controle fuzzy para avaliar a obesidade com base em 
fatores como a quantidade de calorias ingeridas, o peso e o tempo de atividade física. O sistema de controle fuzzy 
utiliza a biblioteca skfuzzy para definir variáveis de entrada, variáveis de saída, funções de pertinência e regras de 
controle fuzzy.
* Variáveis de entrada: "comer," "peso" e "tempo_atividade_fisica."
* Variável de saída: "obesidade."
* Funções de pertinência: triangulares, trapezoidais e gaussianas.

## Resultado
### Exemplo
Pessoa:
* Calorias: 3000 Kcal
* Peso: 65 Kg
* Tempo de atividade: 90 minutos

### 1. Triangular
#### 1.1 Gráficos
![plot_comer_triangular.png](img%2Ftriangular%2Fplot_comer_triangular.png)
![plot_peso_triangular.png](img%2Ftriangular%2Fplot_peso_triangular.png)
![plot_tempo_atividade_fisica_triangular.png](img%2Ftriangular%2Fplot_tempo_atividade_fisica_triangular.png)
![plot_obesidade.png](img%2Ftriangular%2Fplot_obesidade.png)
#### 1.2 Output 
![result_triangular.png](img%2Ftriangular%2Fresult_triangular.png)

### 2. Trapezoidal
#### 2.1. Gráficos
![plot_comer_trapezoidal.png](img%2Ftrapezoidal%2Fplot_comer_trapezoidal.png)
![plot_peso_trapezoidal.png](img%2Ftrapezoidal%2Fplot_peso_trapezoidal.png)
![plot_tempo_atividade_fisica_trapezoidal.png](img%2Ftrapezoidal%2Fplot_tempo_atividade_fisica_trapezoidal.png)
![plot_obesidade.png](img%2Ftrapezoidal%2Fplot_obesidade.png)
#### 2.2. Output 
![result_trapezoidal.png](img%2Ftrapezoidal%2Fresult_trapezoidal.png)

### 3. Gaussiana
#### 3.1. Gráficos
![plot_comer_gaussiana.png](img%2Fgaussiana%2Fplot_comer_gaussiana.png)
![plot_peso_gaussiana.png](img%2Fgaussiana%2Fplot_peso_gaussiana.png)
![plot_tempo_atividade_fisica_gaussiana.png](img%2Fgaussiana%2Fplot_tempo_atividade_fisica_gaussiana.png)
![plot_obesidade_gaussiana.png](img%2Fgaussiana%2Fplot_obesidade_gaussiana.png)
#### 3.2. Output 
![result_gaussiana.png](img%2Fgaussiana%2Fresult_gaussiana.png)


## Outro exemplo de aplicação
### Simulador de um estacionamento de veículo
Aqui, o simulador será desenvolvido em dois passos:
1. Corresponde à implementação do controlador fuzzy, que vai processar as entradas e as saídas em cada passo, além de 
calcular a trajetória do veículo.
2. É o simulador gráfico, ou seja, que vai testar e validar o comportamento do controlador fuzzy, permitindo ao usuário
visualizar a trajetória percorrida e efetuar ajustes, caso necessários.

Assim, seu objetivo é estabelecer um algoritmo inteligente capaz de guiar um veículo, localizado em uma determinada 
posição do pátio, em direção a uma vaga de estacionamento previamente demarcada anteriormente.


## Conclusão
Os modelos de lógica fuzzy testados demonstraram resultados razoáveis, sendo a função gaussiana a mais precisa na 
classificação de obesidade, com um valor de 5. No entanto, os modelos triangulares e trapezoidais também 
apresentaram resultados aceitáveis, com valores próximos a 4,84 e 4,5, respectivamente.
