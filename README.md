# Jogo do Número Secreto

Este é um projeto simples de um jogo de adivinhação desenvolvido com HTML, CSS e JavaScript. O objetivo do jogador é adivinhar um número secreto gerado aleatoriamente dentro de um intervalo definido.

![Tela inicial do Jogo do Número Secreto](./img/tela-inicial.png)

## 🚀 Funcionalidades

- **Geração de Número Aleatório:** Um número secreto é gerado aleatoriamente no início de cada jogo.
- **Validação de Tentativas:** O jogo informa ao usuário se o chute foi maior ou menor que o número secreto.
- **Contagem de Tentativas:** Exibe o número de tentativas que o jogador levou para acertar.
- **Reiniciar Jogo:** Um botão "Novo Jogo" é habilitado ao final de uma partida para reiniciar o jogo com um novo número secreto.
- **Sem Repetição:** O jogo evita sortear números que já foram utilizados na sessão atual, até que todos os números possíveis tenham sido sorteados.
- **Acessibilidade com Voz:** Utiliza a `Web Speech API` para falar os textos exibidos na tela (títulos e dicas), tornando a experiência mais interativa.

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando as seguintes tecnologias:

- **HTML5:** Para a estrutura da página.
- **CSS3:** Para a estilização (não incluído no arquivo `app.js`, mas parte do projeto completo).
- **JavaScript:** Para toda a lógica do jogo e manipulação do DOM.
- **Web Speech API:** Para a funcionalidade de síntese de voz.

## 🎲 Como Jogar

1.  Clone ou baixe este repositório.
2.  Abra o arquivo `index.html` em seu navegador de preferência (Google Chrome, Firefox, etc.).
3.  Digite um número entre 1 e 10 no campo de entrada.
4.  Clique no botão "Chutar".
5.  Siga as dicas na tela até adivinhar o número secreto.
6.  Após acertar, clique em "Novo Jogo" para jogar novamente!

---

Projeto desenvolvido durante o curso "JavaScript: manipulando o DOM" da Alura.