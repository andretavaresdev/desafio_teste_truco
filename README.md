# Truco Paulista

## Especificação do desafio

Partida de truco paulista para quatro jogadores divididos em duas duplas. Utiliza baralho de 40 cartas, três cartas por jogador, vira e manilhas. O programa trata a disputa de rodadas e mãos, pontuação, pedidos de truco, seis, nove e doze, mão de onze e mão de ferro.

## Funcionamento dos casos de teste

Os testes são escritos em JavaScript e executados com Jest. Cada teste verifica o resultado esperado de uma operação. Os casos também cobrem erros de entrada e situações nos limites das regras.

| Arquivo | Verificação |
|---|---|
| `tests/carta.test.js` | Criação e validação das cartas. |
| `tests/baralho.test.js` | Baralho, embaralhamento e distribuição. |
| `tests/ranking.test.js` | Ordem de força e manilhas. |
| `tests/aposta.test.js` | Valores de aposta e aumentos. |
| `tests/rodada.test.js` | Resultado de cada rodada. |
| `tests/mao.test.js` | Resultado da mão e empates. |
| `tests/partida.test.js` | Controle da partida, pontos e vencedores. |
| `tests/aumento.test.js` | Pedidos, respostas e sequência de aumentos. |
| `tests/maoDeOnze.test.js` | Mão de onze e mão de ferro. |
| `tests/erros.test.js` | Entradas e ações inválidas. |
| `tests/personalizacao.test.js` | Verificações adicionais de limites e consistência. |

## Como executar

```bash
npm ci
npm test
```

## Colaborador

- André Tavares (RA: 24066498-2)
