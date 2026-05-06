# 🧩 8-Puzzle Solver

Sistema desenvolvido em linguagem C para resolver o clássico problema do **8-Puzzle** utilizando algoritmos de busca e manipulação de estados.

---

## 📌 Sobre o projeto

O projeto implementa o jogo 8-Puzzle, permitindo a resolução automática do tabuleiro por meio de algoritmos de busca, com diferentes níveis de dificuldade.

O objetivo principal é aplicar conceitos de:

* Estruturas de Dados
* Busca em Espaço de Estados
* Manipulação de Estados
* Algoritmos de Busca
* Lógica Computacional
* Inteligência Artificial clássica

---

## 🎮 O que é o 8-Puzzle?

O 8-Puzzle é um jogo composto por um tabuleiro 3x3 contendo 8 peças numeradas e um espaço vazio.

O objetivo é reorganizar as peças até alcançar o estado final desejado, movimentando apenas peças adjacentes ao espaço vazio.

Exemplo:

Estado inicial:

```txt
1 2 3
4 X 6
7 5 8
```

Estado objetivo:

```txt
1 2 3
4 5 6
7 8 X
```

---

## ⚙️ Funcionalidades

✅ Geração de tabuleiros com diferentes níveis de dificuldade
✅ Representação do tabuleiro em matriz
✅ Movimentação das peças
✅ Verificação de estados
✅ Resolução automática do puzzle
✅ Exibição do caminho solução

---

## 🛠️ Tecnologias utilizadas

* Linguagem C
* Estruturas de Dados
* Algoritmos de Busca
* Manipulação de Matrizes

---

## 🧠 Algoritmos utilizados

O sistema utiliza algoritmos de busca para explorar os estados possíveis do tabuleiro.

### 🔍 BFS (Breadth-First Search)

Busca em largura utilizada para encontrar a solução com menor número de movimentos.

### 🌲 IDDFS (Iterative Deepening Depth-First Search)

Busca em profundidade iterativa, combinando baixo uso de memória com exploração em profundidade.

---

## 📂 Estrutura do projeto

```txt
📁 8-PUZZLE
 ┣ 📄 main.c
 ┣ 📄 fila.h
 ┣ 📄 pilha.h
 ┣ 📄 puzzle.h
 ┣ 📄 busca.c
 ┗ 📄 README.md
```

---

## ▶️ Como executar

Compile o projeto:

```bash
gcc *.c -o puzzle
```

Execute:

```bash
./puzzle
```

---

## 📚 Conceitos aplicados

Este projeto foi desenvolvido com foco acadêmico para praticar:

* Estruturas de dados dinâmicas
* Filas e pilhas
* Algoritmos de busca
* Representação de estados
* Raciocínio lógico
* Programação em C

---

## 🚀 Autor

Desenvolvido por **Isabel Baungartner** e **Julia de Souza Leandro**

🎓 Ciência de Dados e Inteligência Artificial — PUC Campinas
