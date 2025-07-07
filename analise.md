# ANÁLISE DOS MODELOS PARA CLASSIFICAÇÃO

## ANN
ANNs foram uma *boa* escolha para a classificação do estágio, mas *más* para a classificação binária da progressão. Porém, além dessa tendência, seu desempenho variou bastante de exeucção à execução, e com hiperparâmetros e arquiteturas diferentes.
É provavel que um desempenho significantemente melhor em ambas tarefas seja possível com uma arquitetura mais avançada, técnicas e hiperparâmetros de regularização diferentes, mais dados de trainamento, ou uma combinação de todos.

## DECISION TREES
Árvores de decisão foram uma *boa* escolha para classificação do estágio, mas *péssimas* para a classificação binária da progressão.

## SVMs
SVMs foram uma escolha *aceitável* para a classificação da progressão e *boa* para classificação do estágio (multi-class: usando one-versus-all)
