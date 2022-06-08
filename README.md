## Árvores Genealógicas com Prolog
O trabalho consiste na criação de um banco de regras que estruturam a árvore genealógica dos principais deuses e criaturas da **mitologia grega**. É possível fazer consultas de relações de paternidade, irmandade e ancestralidade, além de consultas sobre suas funções e posições como divindades.


### Exemplos de Aplicação
1. `parent(caos, X).`: Resulta nos filhos de caos. O que aconteceria se no lugar de caos fosse X e no lugar de X algum outro deus? 
2. `god(X, noite).`: Resulta no nome do deus da noite.
3. `nameis(caronte, X).`: Resulta na classificação de não divindades na história.  
  
Teste as outras regras e descubra suas funcionalidades!

### Exercício Proposto
Observe o código [Árvore Genealógica Deuses Gregos](https://github.com/elc117/t2-2022a-eduardo_gilson/blob/main/%C3%81rvore%20Geneal%C3%B3gica%20Deuses%20Gregos.pl). Utilize as regras criadas e os exemplos dados anteriormente para responder as seguintes perguntas: 

1. Atena é a deusa do que? 
2. Atena é filha de quem? 
3. Atena é descendente de quem? 
4. Quem são os irmãos de Atena?
5. Irene é uma deusa do olimpo?
6. Zeus é um deus do olimpo? 
7. Quais são os deuses primordiais?

#### Vamos complicar mais um pouco. Responda:
1. Quem são os irmãos do deus que é filho de uma deusa olimpiana com um deus que é ancestral dos pais de Atena? (dica: voce pode partir o problema em partes). 
2. Caso tenha conseguido resolver o problema o dividindo em partes, agora tente resolvê-lo com apenas um comando.

### Referências
[Greek Mythology Family Tree](https://www.youtube.com/watch?v=O7F16sC860s&t=160s)  
[How to learn Prolog by watching Game of Thrones](https://medium.com/free-code-camp/how-to-learn-prolog-by-watching-game-of-thrones-4852ea960017)

