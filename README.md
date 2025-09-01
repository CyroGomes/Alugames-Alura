# AluGames 🎲

Um sistema interativo de aluguel de **boardgames**, desenvolvido com **HTML**, **CSS** e **JavaScript**, que permite gerenciar o status de cada jogo, alternando entre **Alugar** e **Devolver** de forma visual.

O projeto foca na **experiência do usuário**, mostrando claramente quais jogos estão alugados e quais estão disponíveis.

---

## 💡 Funcionalidades

* Lista de boardgames com imagens e nomes.
* Botão que alterna entre **Alugar** e **Devolver** dependendo do status do jogo.
* Alteração visual do jogo alugado com efeito de sobreposição (`overlay`) para indicar indisponibilidade.
* Layout responsivo, adaptando-se a telas grandes e pequenas.

---

## 🎨 Como funciona visualmente

* Jogos **disponíveis** mostram botão **Alugar** e imagem normal.
* Jogos **alugados** mostram botão **Devolver** e a imagem com overlay escurecida.

Exemplo de fluxo:

1. Ao clicar em **Alugar**:

   * O jogo recebe a classe `.dashboard__item__img--rented`.
   * O botão muda para **Devolver** e recebe a classe `.dashboard__item__button--return`.
2. Ao clicar em **Devolver**:

   * O overlay é removido.
   * O botão volta para **Alugar**.

---

## 🖥️ Tecnologias Utilizadas

* **HTML5**: Estrutura da página e elementos semânticos.
* **CSS3**: Layout, responsividade e efeitos visuais.
* **JavaScript (Vanilla)**: Alternância de status dos jogos, manipulação de classes e eventos de clique.

---

## 🔧 Observações

* Sistema **frontend**: não há banco de dados; ao atualizar a página, todos os jogos voltam ao status inicial.
* Layout responsivo e moderno, com destaque visual para jogos alugados.
* Código JavaScript modular, usando função `alterarStatus(id)` para alternar o estado de qualquer jogo.

---

# Alugames-Alura
# Alugames-Alura
