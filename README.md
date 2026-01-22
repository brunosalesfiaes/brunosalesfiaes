# 🚀 Cálculo da Menor Distância em Espaço Tridimensional (Star Wars)

## 📌 Descrição do Projeto

Este projeto foi desenvolvido como parte de uma **avaliação/prova**, com o objetivo de aplicar conceitos de **geometria analítica no espaço tridimensional (ℝ³)** utilizando a linguagem **Java**.

O problema é contextualizado no universo de **Star Wars**, onde:

* O usuário controla uma nave espacial equipada com **6 canhões**;
* Uma nave inimiga é avistada no espaço;
* Para garantir o disparo mais eficiente, é necessário calcular o **menor caminho (menor distância)** entre as duas naves em um ambiente tridimensional.

---

## 🎯 Objetivo

Calcular a **menor distância possível entre duas naves espaciais**, considerando suas posições no espaço 3D, de forma que o disparo percorra o menor trajeto possível.

---

## 🧠 Modelagem do Problema

* Cada nave é representada por **4 vértices no espaço tridimensional**, simulando sua estrutura espacial;
* Cada vértice possui coordenadas **(X, Y, Z)**;
* A menor distância entre as duas naves é obtida calculando-se a distância entre **todos os pares possíveis de vértices**, escolhendo o menor valor encontrado.

---

## 📐 Fundamentação Matemática

A distância entre dois pontos no espaço tridimensional é calculada pela fórmula da **distância euclidiana em ℝ³**:

[
d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2 + (z_2 - z_1)^2}
]

Essa fórmula é aplicada repetidamente para todos os vértices das duas naves.

---

## ⚙️ Funcionamento do Programa

1. O usuário informa as coordenadas **X, Y e Z** dos 4 vértices da **nave do jogador**;
2. Em seguida, informa as coordenadas dos 4 vértices da **nave inimiga**;
3. O programa:

   * Calcula a distância entre cada vértice da nave 1 com cada vértice da nave 2;
   * Armazena a menor distância encontrada;
4. Ao final, exibe no terminal a **menor distância entre as duas naves**, representando o menor caminho para o disparo.

---

## 🖥️ Tecnologias Utilizadas

* **Linguagem:** Java
* **Entrada de dados:** `Scanner`
* **Conceitos aplicados:**

  * Vetores e matrizes
  * Laços de repetição
  * Funções/métodos
  * Geometria analítica em 3D

---

## 📂 Estrutura do Código

* `prova.java`

  * Método `main`: responsável pela entrada de dados e pelo cálculo da menor distância;
  * Método `distancia`: calcula a distância euclidiana entre dois pontos no espaço tridimensional.

---

## ▶️ Como Executar

1. Compile o código:

```bash
javac prova.java
```

2. Execute o programa:

```bash
java prova
```

3. Insira as coordenadas conforme solicitado no terminal.

---

## ✅ Exemplo de Saída

```
A menor distancia entre as duas naves é: 12.45
```

---

## 📚 Aplicações Acadêmicas

Este código demonstra a aplicação prática de:

* Geometria Analítica
* Espaço Tridimensional
* Programação Estruturada
* Resolução de problemas matemáticos com programação

---

## 👨‍🎓 Autor

**Bruno Sales**
Graduando em Ciência da Computação
Projeto desenvolvido para fins avaliativos (prova)
