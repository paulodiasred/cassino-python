# Máquina Caça-Níquel em Python

## Descrição

Este projeto é uma simulação de uma máquina caça-níquel, desenvolvida em Python. O jogo permite que os jogadores apostem um valor em cada rodada e tenham a chance de ganhar de volta três vezes o valor apostado, dependendo do resultado do sorteio de símbolos.

## Funcionalidades

- **Simulação do Jogo**: Os jogadores podem realizar apostas e ver os resultados em um formato gráfico com emojis.
- **Múltiplos Jogadores**: Suporta a simulação de várias apostas de diferentes jogadores em um determinado período.
- **Sistema de Regras**: Implementa regras simples de vitória, onde o jogador ganha se os três símbolos sorteados forem iguais.

## Estrutura do Código

O código é dividido em várias classes:

- **BaseMachine**: Classe abstrata que define a interface para a máquina caça-níquel, com métodos para geração de resultados, exibição e verificação de vitórias.
  
- **Player**: Classe que representa um jogador, com um atributo de saldo que armazena o dinheiro disponível para apostas.

- **CassaNiquel**: Implementação da máquina caça-níquel que gera permutações de símbolos, calcula o resultado do jogo e atualiza o saldo dos jogadores.

## Como Usar

1. **Clone o repositório**:

   ```bash
   git clone https://github.com/seu_usuario/sua_maquina_caca_niquel.git
   cd sua_maquina_caca_niquel
   
2. **Execute o código**:
Execute o script Python:
    ```bash
    python cassa_niquel.py
O jogo será simulado com 100 jogadores, cada um realizando até 5 apostas em um período de 10 dias. O saldo dos jogadores e o resultado de cada rodada serão exibidos no console.

## Tecnologias Utilizadas
- **Python**:
- **Biblioteca padrão (sem dependências externas)**:

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.
