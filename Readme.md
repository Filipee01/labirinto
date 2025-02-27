# 🌀 Labirinto com Backtracking

## 📘 Descrição

Esta atividade envolve a criação de um labirinto em Python, usando a biblioteca Pygame para visualização e a biblioteca Numpy para manipulação das matrizes que representam o labirinto. O objetivo é permitir que o jogador encontre o prêmio no labirinto utilizando o algoritmo de backtracking.

---

## 🧩 Lógica do Backtracking

**A função de backtracking consiste nos seguintes passos:**

- Criar uma nova pilha.
- Localizar a posição inicial do jogador.
- Inserir essa posição na pilha.
- Enquanto a pilha não estiver vazia, executar o loop while.
- Retirar a localização do topo da pilha.
- Se a posição contiver o prêmio, encerrar o loop.
- Caso contrário, mover o jogador para essa posição e examinar as posições vizinhas.
- Se uma posição vizinha for válida, adicioná-la ao topo da pilha.
- Repetir o processo enquanto a pilha não estiver vazia.

---

## 📂 Estrutura de Arquivos

- `__pycache__`: Contém o arquivo executável.
-`Readme.md`: contém as istruções sobre toda implementação
- `labirinto1.txt`: Arquivo que contém os dígitos binários base para a construção do labirinto.
- `main_maze.py`: Arquivo principal que cria e executa o labirinto.
- `maze.py`: Arquivo de implementação do labirinto.

---

## 🚀 Execução do Código

Para executar o código, utilize o seguinte comando no terminal:

```sh
python main_maze.py

```

## Luiz Filipe Santos de Souza
## 20230102493
