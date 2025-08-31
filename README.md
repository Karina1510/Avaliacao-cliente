# Avaliação de Pizza Interativa 🍕
Este repositório contém um sistema de avaliação de 5 estrelas desenvolvido para uma pizzaria. O objetivo foi criar uma forma simples e visualmente atraente para que os clientes possam dar feedback, com uma experiência de usuário intuitiva e dinâmica.

## 💻 Tecnologias Utilizadas
O projeto foi construído com as seguintes tecnologias:

*HTML*: Utilizado para a estrutura fundamental da página, organizando os elementos de avaliação, emojis e textos.

*CSS*: Responsável por toda a estilização e animação, incluindo o efeito de hover nas estrelas e o layout responsivo do campo de avaliação.

*JavaScript*: Para a lógica de interatividade, permitindo que o texto e os emojis mudem dinamicamente de acordo com a nota selecionada.

## 🚀 Funcionalidades do Projeto
Sistema de Avaliação por Estrelas: Campo interativo de 5 estrelas onde o usuário pode clicar para registrar uma nota.

Feedback Dinâmico: A mensagem de texto e o emoji de feedback são atualizados instantaneamente para refletir a nota escolhida, de "Odiei a pizza" (1 estrela) a "Eu amei a pizza!" (5 estrelas).

Design Responsivo: A interface se adapta perfeitamente a diferentes dispositivos, de smartphones a desktops.

## 💡 Estrutura do Código
A estrutura do projeto foi pensada para ser organizada e eficiente.

A classe `.wrapper` centraliza todo o conteúdo do sistema de avaliação na página.

A classe .stars contém os botões de rádio `(<input>)` e os ícones de estrela `(<label>)`, que são os elementos-chave para a interação.

O JavaScript utiliza document.querySelectorAll() para selecionar os inputs das estrelas, e variáveis const para armazenar as listas de mensagens e caminhos de imagens de forma organizada.

Um event listener monitora os cliques nas estrelas, e o script, através do id da estrela, atualiza dinamicamente o textContent do feedback e o src do emoji correspondente.

🛠️ Como Usar
Clone este repositório para o seu ambiente local.
git clone https://github.com/Karina1510/Avaliacao-cliente.git

Abra o git hub pages  para visualizar o projeto.

# 🧑‍💻 Autor
Nome: Karina Silva
