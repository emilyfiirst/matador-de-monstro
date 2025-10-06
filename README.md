# 🧟‍♂️ Matador de Monstro

Um pequeno jogo interativo feito com **HTML**, **CSS** e **Vue.js**, onde o jogador enfrenta um monstro em uma batalha de ataques, curas e estratégias até que um dos dois fique sem vida.

---

## 🕹️ Funcionalidades

- 🎮 **Iniciar Jogo:** começa uma nova partida, restaurando as vidas para 100%.
- ⚔️ **Ataque:** o jogador causa dano ao monstro, que revida em seguida.
- 💥 **Ataque Especial:** causa mais dano que o ataque comum, mas também provoca um contra-ataque.
- 💚 **Curar:** o jogador recupera parte da vida e o monstro ataca logo depois.
- 🚪 **Desistir:** encerra a partida atual.
- 🧾 **Log de ações:** exibe uma lista detalhada das ações realizadas por jogador e monstro.

---

## 🧩 Estrutura do Projeto

```
📁 matador-de-monstro
│
├── index.html      # Estrutura principal da aplicação
├── style.css       # Estilos visuais do jogo
└── app.js          # Lógica do jogo (Vue.js)
```

---

## 💻 Tecnologias Utilizadas

- **HTML5**
- **CSS3**
- **JavaScript (Vue.js 2)**

---

## ⚙️ Como Executar

1. Baixe ou clone este repositório:
   ```bash
   git clone https://github.com/emilyfiirst/matador-de-monstro.git
   ```

2. Abra o arquivo `index.html` em qualquer navegador moderno.

3. Clique em **Iniciar Jogo** e divirta-se! 🕹️

---

## 📱 Interface do Jogo

- **Barra de Vida:** mostra a porcentagem de vida do jogador e do monstro.
- **Botões de ação:** controlam os ataques, curas e desistências.
- **Painel de Log:** exibe as ações realizadas em tempo real.

---

## 🧠 Lógica do Jogo (Resumo)

- O jogador e o monstro começam com 100 de vida.
- Cada ataque causa um dano aleatório dentro de um intervalo.
- O ataque especial adiciona dano extra.
- A cura aumenta a vida do jogador até o máximo de 100.
- Quando um dos dois chega a 0 de vida, o jogo termina automaticamente.

---

## 🏆 Objetivo

Derrote o monstro antes que ele acabe com sua vida!  
Gerencie seus ataques e curas para vencer essa batalha.

---

## 👨‍💻 Autor

Desenvolvido como exercício prático de **Vue.js** para aprendizado de reatividade e manipulação de estado no front-end.
