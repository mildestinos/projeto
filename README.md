# Simulação de Poker Texas Hold'em

Este projeto é uma simulação simplificada do jogo de Poker Texas Hold'em, desenvolvido em HTML, CSS e JavaScript. A aplicação simula a distribuição de cartas comunitárias e do jogador, além de verificar a melhor combinação de mãos ao final de cada rodada.

## Descrição

A interface simula uma mesa de poker onde o usuário pode interagir com as cartas comunitárias e sua própria mão. A aplicação também verifica automaticamente as melhores combinações possíveis ao final do jogo, como par, trinca, sequência, etc., destacando essas informações para o usuário.

### Funcionalidades

1. **Distribuição de Cartas**:
   - O jogador inicia com duas cartas privadas.
   - Cartas comunitárias são reveladas em três etapas:
     - Flop: três cartas.
     - Turn: uma carta.
     - River: uma carta.
   - Cada etapa pode ser ativada por botões interativos, simulando o jogo em um ambiente real de poker.

2. **Verificação de Combinações**:
   - A aplicação verifica automaticamente a combinação de cartas do jogador (par, trinca, etc.) e exibe o resultado ao final da rodada.

3. **Reiniciar o Jogo**:
   - O botão "Reiniciar Jogo" permite recomeçar a rodada, embaralhando o baralho e distribuindo novas cartas para o jogador.

4. **Interface Responsiva**:
   - Layout ajustável em telas menores, com o uso de `media queries`.

### Arquivos e Estrutura

- `index.html`: Estrutura principal da aplicação, incluindo a interface do usuário e elementos interativos.
- `style`: Definições de estilo com o uso de flexbox para disposição dos elementos e efeitos de transição nos botões e cartas.
- `script`: Funções JavaScript para controle do fluxo do jogo, verificação de combinações, e reinício.

## Tecnologias Utilizadas

- **HTML**: Estrutura do projeto e organização dos elementos.
- **CSS**: Estilização e responsividade da interface.
- **JavaScript**: Lógica de distribuição de cartas, verificação de mãos e interação do usuário com a interface.

## Como Usar

1. **Distribua as Cartas**:
   - Clique em "Distribuir Flop" para exibir as três primeiras cartas comunitárias.
   - Clique em "Distribuir Turn" para revelar a quarta carta.
   - Clique em "Distribuir River" para revelar a quinta carta e verifique a melhor combinação de mãos.
2. **Reiniciar o Jogo**:
   - Use o botão "Reiniciar Jogo" para começar uma nova rodada com cartas embaralhadas.

## Futuras Melhorias

- **Identificação Completa de Combinações**: Expansão das verificações para cobrir flush, sequência, full house, entre outras.
- **Sugestões para Melhoria de Mão**: Uma lógica mais detalhada para sugerir quais cartas poderiam melhorar a mão do jogador.
- **Modo Multijogador**: Possibilidade de incluir mais jogadores para simular partidas mais realistas.

## Contribuições

Contribuições para melhorias no código ou novos recursos são bem-vindas. Sinta-se à vontade para abrir um pull request com sugestões ou correções.

