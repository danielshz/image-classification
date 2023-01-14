## 💻 Sobre o projeto

O projeto tem a finalidade de introduzir o conceito de Aprendizado de Máquina (Machine Learning) sob a ótica da estatística, descrevendo os tipos de modelagem — de dados e **algorítmica** —, de áreas de aprendizado de máquina — **supervisionado** e não-supervisionado — e de problemas existentes — regressão e **classificação**, por exemplo. Diante disso, o projeto trabalha com a base de dados MNIST ("*Modified National Institute of Standards and Technology*"). Essa base consiste de 70.000 imagens de tamanho 28 x 28, em tons de cinza, contendo dígitos manuscritos, e o principal objetivo com ela é identificar qual é o dígito em questão.

Atualmente, há algoritmos extremamente sofisticados (e pesadíssimos!) que chegam a atingir uma taxa de erro de 0,17%, porém nesse projeto é abordado um algoritmo bem mais simples, o classificador de Bayes ingênuo Gaussiano, introduzido no arquivo do Jupyter Notebook. Para tal, será utilizado o pacote `scikit-learn` (https://scikit-learn.org/stable/), que implementa diversos algoritmos de aprendizado de máquina de forma muito eficiente e de fácil uso. A partir disso, no projeto, são realizadas diversas análises do problema em questão — classificação das imagens dos dígitos —, bem como avaliações do classificador escolhido e como foi seu desempenho nesse cenário.
