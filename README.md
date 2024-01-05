# Blackjack Game in JavaScript
Este é um simples jogo de Blackjack implementado em HTML, CSS e JavaScript. No Blackjack, o objetivo é chegar o mais perto possível de 21 pontos sem ultrapassar esse valor. Este jogo permite que você jogue contra o computador (dealer).

## Funcionalidades:
* **Inicialização do Jogo:** O jogo é iniciado quando a página é carregada.

* **Baralho e Embaralhamento:** Um baralho padrão é construído e embaralhado.

* **Distribuição de Cartas:** O dealer e o jogador recebem cartas iniciais.

* **Ações do Jogador:** O jogador pode "pedir" (receber uma carta) ou "manter" (encerrar sua vez).

* **Lógica do Dealer:** O dealer segue uma lógica simples para pedir cartas até atingir uma pontuação de 17 ou mais.

* **Verificação de Vitória/derrota:** O jogo verifica automaticamente o resultado (vitória, derrota ou empate) quando o jogador decide "manter".

* **Tratamento de Áses:** A lógica do jogo considera a possibilidade de reduzir o valor de Áses para evitar ultrapassar 21.

# Como Jogar:
Acesse a página do jogo (Insira um link para a sua versão de demonstração ao vivo ou hospedada). 

1. Clique em "Reload Game" para iniciar um novo jogo.

2. Clique em "HIT" para receber uma nova carta.

3. Clique em "STAND" para encerrar sua vez e verificar o resultado.

# Estrutura do Código:

* **Variáveis Globais:** Armazenam pontuações e contadores de Áses para o dealer e o jogador.

* **Funções para Construção do Baralho:** buildDeck() e shuffleDeck() constroem e embaralham o baralho.

* **Função de Inicialização do Jogo:** startGame() distribui as cartas iniciais e define eventos de clique.

* **Funções de Ações do Jogador:** hit() e stand() para pedir cartas ou encerrar a vez.

* **Funções Auxiliares:** getValue(), checkAce(), e reduceAce() ajudam na manipulação de cartas e pontuações.

* **Função de Recarregar o Jogo:** retry() para reiniciar o jogo.
