

# 🌳 Bagging and Ensemble Learning

Estudo prático e progressivo sobre **Ensemble Learning**, com foco em **Bagging**, **Bootstrap Sampling**, combinação de múltiplas Decision Trees e **Out-of-Bag Error (OOB Error)**.

Este laboratório faz parte de uma formação prática em Machine Learning com foco não apenas na utilização de algoritmos, mas na compreensão de **como eles funcionam, por que são utilizados, quais problemas resolvem e como suas decisões podem ser justificadas tecnicamente**.

---

# 📚 Sobre este Laboratório

Uma Decision Tree individual possui uma grande vantagem: é relativamente simples de interpretar.

Porém, árvores também apresentam uma limitação importante:

> Uma única árvore pode apresentar alta variância e ser muito sensível aos dados utilizados durante o treinamento.

Pequenas alterações no conjunto de treinamento podem produzir árvores completamente diferentes.

O objetivo deste laboratório é entender como o **Ensemble Learning** pode utilizar vários modelos para produzir uma previsão mais estável e robusta.

O principal conceito estudado será:

> **Bagging — Bootstrap Aggregating**

A ideia fundamental é treinar diversos modelos utilizando diferentes amostras dos dados e posteriormente combinar suas previsões.

---

# 🎯 Objetivos

Ao finalizar este laboratório, o objetivo é ser capaz de:

- explicar o conceito de Ensemble Learning;
- entender por que combinar modelos pode melhorar a generalização;
- explicar o conceito de Bootstrap Sampling;
- entender amostragem com reposição;
- construir diferentes conjuntos de treinamento através de Bootstrap;
- treinar múltiplas Decision Trees;
- entender por que as árvores produzidas são diferentes;
- combinar previsões de diferentes modelos;
- compreender Aggregation;
- comparar uma Decision Tree individual com Bagging;
- analisar redução de variância;
- compreender Out-of-Bag Samples;
- calcular e interpretar Out-of-Bag Error;
- compreender as vantagens e limitações do OOB Error;
- relacionar OOB Error com Cross-Validation;
- avaliar estabilidade dos modelos;
- interpretar os resultados de um Ensemble;
- justificar tecnicamente quando Bagging é uma escolha adequada.

---

# 🧠 Pré-requisitos

Este laboratório assume conhecimento prévio dos conceitos estudados nos laboratórios anteriores:

- Decision Trees;
- Classification Trees;
- Regression Trees;
- Gini Index;
- Entropy;
- Information Gain;
- Splitting Criteria;
- Stopping Conditions;
- Overfitting;
- Underfitting;
- Bias;
- Variance;
- Pre-pruning;
- Post-pruning;
- `max_depth`;
- `min_samples_leaf`;
- avaliação de modelos;
- RMSE;
- train/test split.

O objetivo agora não é abandonar esses conceitos.

É entender como podemos utilizá-los dentro de uma arquitetura composta por **múltiplos modelos**.

---

# 🗺️ Estrutura do Laboratório

O laboratório será dividido em etapas progressivas:

```text
LABORATÓRIO 3
│
├── Fase 1 — Baseline e Limitações da Decision Tree
│
├── Fase 2 — Ensemble Learning
│
├── Fase 3 — Bootstrap Sampling
│
├── Fase 4 — Bagging
│
├── Fase 5 — Aggregation
│
├── Fase 6 — Decision Tree vs Bagging
│
├── Fase 7 — Out-of-Bag Error
│
├── Fase 8 — Análise de Variância e Estabilidade
│
├── Fase 9 — Avaliação e Interpretação
│
└── Desafio de Mercado
