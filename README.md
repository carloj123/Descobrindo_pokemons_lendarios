# Descobrindo_pokemons_lendarios
O aprendizado de máquina pode ser definido como uma série de regras e reajustes matemáticos/estatísticos necessários para que se encontre, ao final de uma etapa de "treino" sobre a experiência da máquina, um modelo preditivo que melhor se adeque aos dados disponíveis.
Este relatório tem como objetivo demonstar os passos e decisões tomados para a contrução de um modelo preditivo capaz de argumentar sobre a probabilidade de um pokémon 1 ser lendário. Dessa forma, pode-se dizer que a máquina irá aprender sobre alguns dados de diversos pokémons e terá a capacidade de avaliá-los de acordo com o rótulo já definid

# O dataset
Para que seja possível prever sobre a "raridade" de um pokémon, é necessário entender quais características (ou features) o classificam como tal. Em outras palavras, são necessários dados. Para este ecperimento, foi utilizado um conjunto de dados (comumente chamado de dataset) disponível pela comunidade Kaggle, onde se encontram algumas informações interessantes sobre 721 dessas criaturas, tais como as verificadas abaixo.

# Tecnologias
## Python 3.7.1
* pandas==0.24.2
* numpy==1.15.4
* scikit-learn==0.20.3
