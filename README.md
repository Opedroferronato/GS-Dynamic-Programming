# Projeto: Comparação de Algoritmos de Programação Dinâmica

Este projeto implementa quatro versões de solução para o mesmo problema usando diferentes abordagens:
**Gulosa (Greedy)**, **Recursiva**, **Programação Dinâmica Top‑Down**, e **Programação Dinâmica Bottom‑Up**.

O objetivo é comparar desempenho, complexidade e qualidade das respostas.

---

## 📌 Estrutura do Projeto

* **solution.py** – Contém as quatro soluções do problema:

  * `solve_greedy()` – Algoritmo Guloso
  * `solve_recursive()` – Solução Recursiva
  * `solve_dp_top_down()` – Programação Dinâmica com Memoização
  * `solve_dp_bottom_up()` – Programação Dinâmica Iterativa

---

## 🧠 Problema

Este projeto resolve o problema **Clássico da Mochila (Knapsack Problem)**:

> Dado um conjunto de itens com valores e pesos, determinar o maior valor possível que pode ser colocado na mochila sem ultrapassar sua capacidade.

Este problema é ideal para comparar diferentes abordagens de solução.

---

## 📊 Abordagens Utilizadas

### 1️⃣ Greedy

* Ordena itens pela razão **valor/peso**.
* Escolhe sempre o item “mais vantajoso”.
* **Rápido**, mas **não garante o resultado ótimo**.

### 2️⃣ Recursiva

* Explora todas as combinações possíveis.
* **Custo exponencial**.
* Garante o ótimo, mas é inviável para entradas grandes.

### 3️⃣ Programação Dinâmica Top‑Down (Memoization)

* Parecida com a recursiva, mas **salva resultados intermediários**.
* Reduz drasticamente o tempo de execução.

### 4️⃣ Programação Dinâmica Bottom‑Up

* Constrói uma tabela de resultados iterativamente.
* Geralmente é a abordagem **mais eficiente e estável**.

---

## ▶️ Como Executar

Basta rodar o arquivo principal:

```
python solution.py
```

A saída mostrará o resultado de cada abordagem.

---

## 📈 Comparação Esperada

| Abordagem    | Resultado          | Tempo        | Observações    |
| ------------ | ------------------ | ------------ | -------------- |
| Greedy       | Pode errar o ótimo | Muito rápido | Aproximação    |
| Recursiva    | Sempre ótima       | Muito lento  | Exponencial    |
| DP Top-Down  | Ótimo              | Rápido       | Usa memoização |
| DP Bottom-Up | Ótimo              | Mais rápido  | Iterativo      |

---

## 👥 Integrantes

* **Pedro Henrique Ferronato** – RM 554757
* **Gabriel Martins Vanucci** - RM 556883


---
