# memorygame DIO

### Jogo da memória como projeto de treino em HTML5/CSS3 e JS

### HTML5: 

O html carrega a estrutura de cartas do jogo: cada div card possui um propriedade data-card responsável por identificar os pares de cartas e duas imagens: uma da frente neutra (brackets) e a parte traseira com a imagem real, que deve formar o par.
A frente e a traseira possuem as classes card-front e card-back, respectivamente.

### CSS3
Na folha de estilos estão as posições e animações das cartas.
A classes .card-front e .card.flip determinam as rotações das cartas em 180 graus de acordo com o comportamento JS determinado.
São definidos os tratamentos das cartas em relação às animações atribuídas, tempo de transformação e transição.

### JS
O script JavaScript trata os comportamentos:

Virar carta quando clickada (flipCard);
Verificar se a segunda carta é igual a primeira virada (checkForMatch);
Desvirar as Cartas se não forem iguais (unflipCards);
Desabilitar Cartas se forem iguais (disableCards);
Resetar os valores das variaveis para proseguir com o jogo (resetBoard);
Embaralhar as cartas no início do jogo (suffle);

O código também tem algumas variáveis de controle:
hasFlipedCard (boolean): Se a carta foi virada ou não
firstCard, secondCard: Após o click, recebe o card clicado para verificar a propriedade data-card
lockBoard (boolean): Trava o teclado enquando o evento de animação (flip) é realizado.

Desenvolvido na aula prática com a professora Gabriela Pinheiro.
