# 🧭 Graph Routing Optimization Lab

Este repositório é meu **laboratório pessoal de grafos, rotas e caminhos mais curtos**.

Aqui eu brinco, experimento, testo ideias e tento responder perguntas simples que todo mundo já se fez alguma vez:

> “Qual é o caminho mais curto da minha casa até o hospital?”  
> “E até a padaria?”  
> “E se eu mudar o critério?”  

A diferença é que, neste repositório, essas perguntas viram **grafos, matrizes, algoritmos e código em Python**.

---

## 🧠 O que significa *Graph Routing Optimization*?

O nome do repositório resume exatamente o que está sendo explorado aqui:

### **Graph**
Tudo começa com **grafos**:  
- nós → ruas, esquinas, pontos da cidade, locais
- arestas → conexões entre esses pontos
- pesos → distância, custo ou esforço entre dois pontos

A cidade vira um grafo.

---

### **Routing**
Routing é o problema de **escolher caminhos**:
- de um ponto A até um ponto B
- passando por ruas intermediárias
- respeitando custos (distância, metros, etc.)

---

### **Optimization**
Não basta qualquer caminho — queremos o **melhor**:
- o mais curto
- o menos custoso
- o mais eficiente

Ou seja: **otimização**.

---

## 🎯 Objetivo do repositório

Este repositório **não é um framework**  
**não é um projeto comercial**  
**não é um tutorial definitivo**

Ele é um **ambiente de aprendizado contínuo**, onde eu:

- estudo **teoria dos grafos na prática**
- implemento **algoritmos clássicos**
- modelo **cenários reais**
- testo **bibliotecas diferentes**
- visualizo resultados para entender melhor

Tudo com foco em **curiosidade técnica** e **aprendizado real**.

---

## 🗺️ Modelagem do mundo real (o CSV)

Uma parte central do laboratório é um **arquivo CSV** que representa um **mapa real**.

Nesse arquivo:
- cada **linha/coluna** representa um ponto da cidade  
- cada **valor** representa a distância entre dois pontos  
- `0` significa que não existe ligação direta  

O mapa inclui:
- minha casa
- esquinas
- ruas
- conexões reais entre pontos

Ou seja: **uma cidade real transformada em uma matriz de adjacência**.

Esse CSV é a base para todos os experimentos.

---

## 🧮 Algoritmo estudado: Dijkstra

O principal algoritmo utilizado até agora é o **algoritmo de Dijkstra**, que resolve o problema de:

> Encontrar o **caminho mais curto** entre dois nós em um grafo ponderado.

Ele é usado para responder perguntas como:
- caminho mais curto até o hospital
- caminho mais curto até a padaria
- caminho mais curto até a farmácia
- caminho mais curto até o mercado
- caminho mais curto até a academia

Cada experimento muda apenas o **destino**, mas o grafo é o mesmo.

---

## 🧩 O papel do NetworkX

A principal biblioteca usada neste laboratório é o **NetworkX**.

### O que é o NetworkX?
NetworkX é uma biblioteca Python para:
- criar grafos
- manipular grafos
- executar algoritmos clássicos de grafos
- explorar propriedades estruturais
- visualizar grafos

Neste repositório, o NetworkX é usado para:
- transformar a matriz CSV em um grafo
- aplicar o algoritmo de Dijkstra
- extrair subgrafos com o caminho mais curto
- visualizar o grafo completo e o caminho destacado

Ele funciona como um **canivete suíço da teoria dos grafos**.

---

## 📊 Outras bibliotecas utilizadas

### Pandas
Usado para:
- leitura do CSV
- manipulação da matriz de adjacência
- preparação dos dados para o grafo

### Matplotlib
Usado para:
- desenhar o grafo
- destacar visualmente o caminho mais curto
- facilitar a análise e a intuição do resultado

---

## 🔬 Experimentos realizados

Até o momento, os experimentos incluem:
- cálculo do caminho mais curto entre diferentes pontos
- visualização do caminho em vermelho sobre o grafo
- comparação visual entre rotas possíveis
- validação do modelo do mapa

Cada experimento é uma **pergunta diferente feita ao mesmo grafo**.

---

## 🚀 Próximo passo: OR-Tools

Como evolução natural do laboratório, este repositório também será usado para testar:

- **OR-Tools**
- problemas de roteamento mais complexos
- cenários com múltiplos destinos
- otimização além de apenas um par origem-destino

A ideia é comparar:
- algoritmos clássicos de grafos (NetworkX)
- ferramentas de otimização (OR-Tools)

Tudo usando **os mesmos dados reais**.

---

## 🧪 Filosofia do laboratório

Este repositório existe para:
- errar
- refatorar
- testar ideias
- aprender fazendo

Nada aqui é definitivo.  
Tudo aqui pode mudar.

Esse laboratório cresce junto com o meu entendimento sobre grafos, rotas e otimização.

---
