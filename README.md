
# Super Trunfo - Cidades do Mundo

## Sobre o Jogo
Este programa implementa uma versão do jogo "Super Trunfo" baseada em cidades do mundo, o jogo foi desenvolvido como atividade prática para a matéria de Introdução à Programação de Computadores (ADS - Estacio). O jogo permite ao usuário cadastrar cartas personalizadas ou utilizar um conjunto padrão de cartas, embaralhá-las e jogar contra o computador escolhendo atributos das cartas para competir rodada a rodada.

## Funcionalidades
- Cadastro de cartas personalizadas.
- Utilização de cartas padrão.
- Embaralhamento de cartas.
- Seleção de atributos para disputa.
- Comparação de atributos entre cartas do jogador e do computador.
- Exibição do resultado final da partida.

## Estrutura do Código
O código utiliza uma estrutura `Carta` para armazenar informações sobre cada cidade, incluindo:
- Nome do continente
- Nome do país
- Nome do estado
- Nome da cidade
- Código da carta
- População
- Pontos turísticos
- Área
- PIB
- Densidade populacional
- PIB per capita
- Super poder

### Funções Principais
1. **`main()`**: Interface do menu principal do jogo.
2. **`cadastrarCartas()`**: Permite ao jogador cadastrar novas cartas.
3. **`CartasPadrao()`**: Carrega um conjunto de cartas pré-definidas.
4. **`embaralhar()`**: Mistura as cartas aleatoriamente.
5. **`jogar()`**: Inicia a partida entre o jogador e o computador.
6. **`exibirCarta()`**: Mostra os atributos de uma carta específica.
7. **`escolher_atributo()`**: Permite ao jogador selecionar o atributo para disputa.

## Como Jogar
1. Execute o programa.
2. Escolha uma das opções do menu:
   - **1:** Cadastrar novas cartas.
   - **2:** Usar cartas padrão.
   - **3:** Jogar.
   - **4:** Sair.
2.1. Escolher a entrada das cartas.
2.2. Escolher iniciar ou sair.
3. No modo de jogo, escolha um atributo para disputar.
4. O computador também possui cartas, e o vencedor de cada rodada é determinado pelo maior valor do atributo escolhido.
5. Após todas as rodadas, o programa exibe o placar final.

## Pré-requisitos
- Compilador C (GCC recomendado)
- Sistema operacional compatível com C (Windows, Linux, macOS)

## Como Compilar e Executar
1. Abra um terminal e compile o código:
   ```sh
   gcc super_trunfo.c -o super_trunfo
   ```
2. Execute o programa:
   ```sh
   ./super_trunfo
   ```

## Melhorias Futuras
- Implementação de um sistema de pontuação mais complexo.
- Adição de mais atributos nas cartas.
- Interface gráfica para melhorar a experiência do usuário.

