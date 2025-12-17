# ✂️ M1 - Pedra, Papel e Tesoura (Rock, Paper, Scissors)

## 🔗 Deploy do Projeto

Confira a aplicação em execução através do link abaixo:
👉 [Jogar Pedra, Papel e Tesoura](https://victormartinsd.github.io/m1-pedra-papel-tesoura-VictorMartinsD/)

## 📸 Preview

<p align="center">
  <img src="https://github.com/user-attachments/assets/412659d7-6d4e-42e4-b6d8-8c1fd1875789" alt="Screenshot da tela de testes do projeto Pedra Papel Tesoura" width="600">
</p>

## ✨ Sobre o Projeto

Este projeto consiste na implementação da **lógica central** do clássico jogo Pedra, Papel e Tesoura (Rock, Paper, Scissors), utilizando JavaScript puro. O objetivo é desenvolver a única função necessária que encapsula as regras de vitória, derrota e empate.

A implementação é testada contra uma bateria de nove combinações possíveis (`Pedra x Pedra`, `Pedra x Tesoura`, `Pedra x Papel`, etc.) para garantir que a lógica esteja 100% funcional.

## 🛠️ Funcionalidade Principal

O núcleo do jogo foi construído através da função em `script.js`:

### `playRockPaperScissor(player1, player2)`

* **Propósito:** Determinar o resultado do jogo (vitória do Jogador 1, vitória do Jogador 2 ou Empate) com base nas jogadas fornecidas.
* **Entrada:** Duas strings representando as jogadas: `player1` e `player2` (ex: `"Pedra"`, `"Papel"`, `"Tesoura"`).
* **Saída:** Uma string contendo o resultado final (ex: `"Jogador 1 venceu!"`, `"Jogador 2 venceu!"`, `"Empate!"`).
* **Foco Técnico:** Uso de operadores lógicos complexos (`||` e `&&`) para implementar a lógica de vitória de forma concisa.

## 📁 Estrutura de Arquivos

* `index.html`: Interface visual que carrega os testes e exibe os resultados.
* `testes/testes.js`: Contém as 9 combinações de jogo e a função de execução dos testes.
* `script.js`: **Arquivo principal** onde a função `playRockPaperScissor` foi desenvolvida.

## ⚙️ Como Executar os Testes

1.  **Clone o Repositório:**
    ```bash
    git clone [https://github.com/VictorMartinsD/m1-pedra-papel-tesoura-VictorMartinsD.git](https://github.com/VictorMartinsD/m1-pedra-papel-tesoura-VictorMartinsD.git)
    ```
2.  **Acesse a Pasta:**
    ```bash
    cd m1-pedra-papel-tesoura-VictorMartinsD
    ```
3.  **Abra o `index.html`:** Simplesmente abra o arquivo `index.html` no seu navegador.
4.  **Execute os Testes:** Clique no botão **"Executar Bateria de Testes"** para verificar se a sua implementação está correta.

---
---

# 🇺🇸 M1 - Rock, Paper, Scissors

## 🔗 Project Deploy

You can check out the application in action at the link below:
👉 [Play Rock, Paper, Scissors](https://victormartinsd.github.io/m1-pedra-papel-tesoura-VictorMartinsD/)

## ✨ About the Project

This project consists of implementing the **core logic** of the classic Rock, Paper, Scissors game using pure JavaScript. The goal is to develop the single necessary function that encapsulates the rules for winning, losing, and drawing.

The implementation is tested against a battery of nine possible combinations (`Rock vs Rock`, `Rock vs Scissors`, `Rock vs Paper`, etc.) to ensure the logic is 100% functional.

## 🛠️ Main Functionality

The game's core logic is built around the following function in `script.js`:

### `playRockPaperScissor(player1, player2)`

* **Purpose:** To determine the game's result (Player 1 win, Player 2 win, or Draw) based on the moves provided.
* **Input:** Two strings representing the moves: `player1` and `player2` (e.g., `"Pedra"`, `"Papel"`, `"Tesoura"` or `"Rock"`, `"Paper"`, `"Scissors"` if adapted). *Note: The test file uses Portuguese moves.*
* **Output:** A string containing the final result (e.g., `"Jogador 1 venceu!"`, `"Jogador 2 venceu!"`, `"Empate!"`).
* **Technical Focus:** Use of complex logical operators (`||` and `&&`) to implement the winning logic concisely.

## 📁 File Structure

* `index.html`: Visual interface that loads the tests and displays the results.
* `testes/testes.js`: Contains the 9 game combinations and the test execution function.
* `script.js`: **Main file** where the `playRockPaperScissor` function was developed.

## ⚙️ How to Run Locally

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/VictorMartinsD/m1-pedra-papel-tesoura-VictorMartinsD.git](https://github.com/VictorMartinsD/m1-pedra-papel-tesoura-VictorMartinsD.git)
    ```
2.  **Access the Folder:**
    ```bash
    cd m1-pedra-papel-tesoura-VictorMartinsD
    ```
3.  **Open `index.html`:** Simply open the `index.html` file in your browser.
4.  **Run the Tests:** Click the **"Executar Bateria de Testes"** button to verify your implementation.
