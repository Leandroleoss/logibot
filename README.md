# LogiBot 🤖

Jogo didático interativo no navegador para ensinar lógica de programação para iniciantes absolutos, sem exigir conhecimento prévio de sintaxe. O jogador controla um robô de logística em um galpão automatizado usando blocos visuais, acompanhando a execução passo a passo e a tradução em código em tempo real.

> **Jogar online:** `https://leandroleoss.github.io/logibot/`

---

## 🎯 Objetivo do Projeto

Introduzir conceitos fundamentais de programação de forma visual, prática e sem frustração com erros de digitação ou sintaxe:

1. **Fase 1 — Sequência:** Coletar uma caixa e entregá-la na zona marcada entendendo a ordem exata das instruções.
2. **Fase 2 — Repetição (`Repetir`):** Automatizar deslocamentos longos respeitando um limite de blocos na tela.
3. **Fase 3 — Condicionais (`Se... Então`):** Atravessar uma ponte com buracos gerados em posições aleatórias usando decisão baseada em sensor.
4. **Fase 4 — Variáveis:** Usar um contador (`caixas`) para controlar o estado do robô e destrancar o portão de saída.
5. **Fase 5 — Funções:** Criar e reutilizar uma rotina personalizada (`Minha_Rotina()`) para resolver trechos repetitivos com menos blocos.

---

## ✨ Funcionalidades

* **Execução Visual e Passo a Passo:** Modos **Executar**, **Passo a Passo (`⏭ Passo`)**, controle de velocidade (`1x` / `2x`) e **Reiniciar**.
* **Sensor Visual no Tabuleiro:** Destaca a casa inspecionada à frente do robô quando uma condição é avaliada.
* **Edição Ágil de Blocos:** Reordenação (`↑` / `↓`), remoção e limite de blocos por fase quando aplicável.
* **Tradução ao Vivo para Código:** Exibe a estrutura equivalente em estilo Python sincronizada com o bloco em execução.
* **Avaliação por Estrelas:** Concede de **1 a 3 estrelas** com base na eficiência da solução, sem bloquear o avanço do jogador.
* **Diagnóstico Educativo:** Explica o motivo exato quando uma ação falha (colisão, queda, ação fora de posição ou limite excedido).

---

## 🛠️ Tecnologias Utilizadas

* **HTML5**
* **CSS3**
* **JavaScript (Vanilla JS)**

---

## 🚀 Como Executar Localmente

1. Clone ou baixe este repositório:
   ```bash
   git clone [https://github.com/Leandroleoss/logibot.git](https://github.com/Leandroleoss/logibot.git)
