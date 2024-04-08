Este repositório possui um notebook Python que implementa um agente de aprendizado por reforço usando o algoritmo Q-learning para resolver o ambiente de simulação "LunarLander-v2" disponível no Gymnasium. O objetivo do agente é aprender a pousar uma nave espacial na Lua, evitando colisões e mantendo um pouso suave.

O agente utiliza uma rede neural para estimar os valores Q para cada ação em um determinado estado. Durante a fase de treinamento, o agente interage com o ambiente, atualiza sua política com base nas recompensas recebidas e ajusta os valores Q de acordo com o algoritmo Q-learning.

## Funcionalidades Implementadas

- Implementação do algoritmo Q-learning.
- Utilização de uma rede neural para estimar os valores Q.
- Visualização dos resultados através de um gráfico da recompensa acumulada por episódio.

## Como Executar

Para executar este notebook:

1. Certifique-se de ter as bibliotecas necessárias instaladas, incluindo o Gymnasium com suporte para o ambiente Box2D.
2. Execute cada célula do notebook sequencialmente.

## Resultados

O gráfico gerado ao final do notebook mostra a recompensa acumulada em cada episódio. O objetivo é que a recompensa aumente ao longo dos episódios, indicando que o agente está aprendendo a tarefa com sucesso.
