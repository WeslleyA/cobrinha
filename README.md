# 🐍 Jogo da Cobrinha (Snake Game)

Uma recriação moderna e responsiva do clássico *Snake Game* (Jogo da Cobrinha) desenvolvida em HTML5 Canvas e JavaScript puro (Vanilla JS), com sistema de pontuação e persistência de recorde local.


---

## 📌 Sobre o Projeto

Este projeto implementa o tradicional jogo da cobrinha em uma grade (grid) $20 \times 20$ utilizando a API do Canvas em conjunto com funções de tempo (`setInterval`) para controlar a taxa de atualização dos movimentos.

### 🚀 Funcionalidades

- **Grade Dinâmica Baseada em Matrix/Tile:** Movimentação fluida calculada através de coordenadas de grade ($20 \times 20$ blocos).
- **Persistência de Recorde (`localStorage`):** O recorde do jogador fica salvo no navegador, mantendo o histórico de alta pontuação mesmo após fechar ou recarregar a página.
- **Detecção de Colisão Inteligente:** 
  - Colisão com os limites (paredes) do Canvas.
  - Colisão com o próprio corpo da cobra.
- **Geração Segura de Comida:** A maçã nasce aleatoriamente na tela sem o risco de aparecer em cima de algum segmento do corpo da cobra.
- **Prevenção de Inversão Instantânea:** Impede que a cobra dê "meia-volta" diretamente contra a sua direção atual de movimento (evitando suicídio acidental).
- **Tela de Game Over com Reinício Rápido:** Exibe a pontuação final, o recorde histórico e permite reiniciar a partida instantaneamente pelo teclado.

---

## 🎮 Controles

| Ação | Teclas |
| :--- | :--- |
| **Mover para Cima** | `Seta para Cima` ou `W` |
| **Mover para Baixo** | `Seta para Baixo` ou `S` |
| **Mover para Esquerda** | `Seta para Esquerda` ou `A` |
| **Mover para Direita** | `Seta para Direita` ou `D` |
| **Reiniciar Partida (Game Over)** | `Espaço` ou `R` |

---

## 🛠️ Tecnologias Utilizadas

- **[HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML):** Estruturação e elemento `<canvas>` para renderização visual do jogo.
- **[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS):** Estilização da página com layout centralizado (`Flexbox`) e tema escuro.
- **[JavaScript (ES6+)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript):** Lógica do jogo, manipulação do Canvas 2D, escuta de eventos de teclado e manipulação de armazenamento local (`localStorage`).

---

## 💻 Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/WeslleyA/cobrinha.git](https://github.com/WeslleyA/cobrinha.git)
