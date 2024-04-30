# Snake_game

Esse código implementa o jogo clássico da cobrinha usando a biblioteca Turtle no Python. Aqui está um resumo do que foi implementado:

1. **Inicialização do ambiente de jogo:** A tela é configurada com uma largura e altura de 600 pixels, com um fundo preto e o título "My Snake Game". O rastreamento da tela é desligado para evitar atualizações automáticas.

2. **Criação dos objetos Snake, Food e Scoreboard:** A cobra, a comida e o placar são inicializados.

3. **Configuração dos controles de teclado:** O programa está configurado para responder às teclas de seta para cima, baixo, esquerda e direita, movendo a cobra na direção correspondente.

4. **Loop principal do jogo:** O jogo é executado em um loop enquanto a variável `game_is_on` for verdadeira.

5. **Atualização da tela:** A tela é atualizada a cada iteração do loop.

6. **Movimento da cobra:** A cada iteração do loop, a cobra se move de acordo com a direção definida pelo jogador.

7. **Detecção de colisão com comida:** Se a cabeça da cobra estiver próxima o suficiente da comida, a comida é reposicionada aleatoriamente, a cobra cresce e a pontuação aumenta.

8. **Detecção de colisão com parede:** Se a cabeça da cobra atingir as bordas da tela, o jogo termina e é exibida a mensagem de "game over" no placar.

9. **Detecção de colisão com o próprio corpo:** Se a cabeça da cobra colidir com qualquer parte do seu próprio corpo, o jogo termina e é exibida a mensagem de "game over" no placar.

No geral, esse código cria uma implementação funcional e básica do jogo da cobrinha em Python usando a biblioteca Turtle.
