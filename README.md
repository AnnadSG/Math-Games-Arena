# Arena de Jogos Matemáticos

Protótipo de plataforma modular de jogos matemáticos (CNJM) com agentes de procura adversa.

- Jogos: Dominório, Cães e Gatos, Rastos
- Agente: negamax com cortes alfa-beta e aprofundamento iterativo, limitado por tempo
- Modos: humano vs agente, humano vs humano, agente vs agente

## Como correr
Abre `index.html` num browser. Não precisa de servidor nem de instalação.

## Estrutura
Cada jogo implementa a mesma interface (`init`, `moves`, `apply`, `result`, `ev`, `label`, `pick`, `cell`);
o motor `search()` funciona com qualquer jogo que a implemente.
