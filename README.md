# Ludo Bomb Bonanza 🎲💣

O **Ludo Bomb Bonanza** é uma adaptação digital inspirada no clássico jogo de tabuleiro Ludo, integrada com dinâmicas modernas de *crash games* e sistemas de risco e recompensa. Este repositório armazena o código-fonte, a interface e a lógica computacional do jogo.

---

## 🎮 O que é o Jogo e Como Funciona

Diferente do Ludo tradicional focado apenas em estratégia pura entre quatro jogadores, o **Ludo Bomb Bonanza** adiciona uma camada de adrenalina através de multiplicadores e eventos aleatórios de colisão:

1. **Aposta e Preparação:** O jogador define os parâmetros iniciais da rodada antes de lançar os dados.
2. **Movimentação no Tabuleiro:** Ao rolar os dados, as peças avançam pelas casas do tabuleiro. Cada casa percorrida adiciona pontos ou multiplicadores ao painel.
3. **O Fator "Bomb" (Risco):** Espalhadas pelo tabuleiro existem casas de perigo ocultas (Bombas). Se a sua peça parar em uma dessas casas, a rodada explode, resetando os ganhos acumulados.
4. **Mecânica de Cash Out:** O grande desafio do jogador é estratégico — decidir o momento exato de encerrar a rodada (fazer o *Cash Out*) e garantir a pontuação antes de atingir uma bomba.

---

## 🚀 Como Jogar (Instruções)

1. Abra o arquivo `index.html` diretamente no seu navegador de preferência.
2. No painel lateral, defina o valor ou pontos que deseja colocar em risco na rodada.
3. Clique no botão **"Lançar Dados"** para iniciar o movimento das suas peças.
4. Acompanhe o crescimento do multiplicador conforme avança no tabuleiro.
5. Clique em **"Cash Out"** a qualquer momento para garantir sua vitória antes que uma bomba encerre sua jogada!

---

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído utilizando as tecnologias fundamentais do desenvolvimento web:

* **HTML:** Utilizado para estruturar o tabuleiro, as casas do jogo, os peões e o painel de controle do usuário.
* **CSS** Responsável por todo o design visual, estilização das cores do tabuleiro, posicionamento dos elementos e pelas animações das explosões e movimentação.
* **JavaScript** O coração do jogo. Controla o loop principal, a movimentação dos peões, o cálculo dos multiplicadores, a lógica de *Cash Out* e o motor de RNG (Gerador de Números Aleatórios) para os dados e bombas.

---

## 📂 Estrutura Técnica do Repositório

O projeto está organizado de maneira limpa e modular para facilitar a manutenção e leitura do código:

