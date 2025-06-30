# 📊 Exercícios de Estatística com Python (Jupyter Notebooks)

Este repositório contém as resoluções detalhadas de uma lista abrangente de exercícios de estatística, implementados e apresentados no formato de Jupyter Notebooks (`.ipynb`). O objetivo é demonstrar a aplicação prática de conceitos estatísticos fundamentais utilizando a biblioteca `scipy.stats` para cálculos de distribuições, valores críticos e testes de hipóteses, além de `matplotlib` para visualizações.

## 📁 Estrutura do Repositório

O repositório está organizado em três arquivos Jupyter Notebooks, cada um contendo a resolução de 18 exercícios da lista.

* `ex01-18.ipynb`: Contém as resoluções dos Exercícios 1 ao 18.
* `ex19-36.ipynb`: Contém as resoluções dos Exercícios 19 ao 36.
* `ex37-54.ipynb`: Contém as resoluções dos Exercícios 37 ao 54.

**Dentro de cada notebook:**
* Cada célula individual corresponde a um exercício específico.
* **Células Markdown:** Utilizadas para questões teóricas, que não exigem código.
* **Células de Código Python:** Utilizadas para implementar os cálculos estatísticos, gerar estatísticas de teste, encontrar valores críticos e criar gráficos visuais das distribuições.

## ✨ Conceitos Estatísticos Abordados

Os exercícios cobrem uma vasta gama de tópicos em estatística inferencial e descritiva, incluindo:

### `ex01-18.ipynb.ipynb` (Exercícios 1 - 18)
* **Distribuições Normais:** Comparação de médias e desvios padrão, determinação de áreas sob a curva (probabilidades) usando escores-Z.
* **Teorema do Limite Central (TLC):**
    * Cálculo da média e erro padrão da distribuição amostral das médias.
    * Probabilidades para médias amostrais.
    * Comparação da dispersão da população e da distribuição amostral.
* **Estimativas Pontuais:** Cálculo da média amostral como estimativa da média populacional.
* **Introdução a Intervalos de Confiança (Média - σ Conhecido):**
    * Cálculo da margem de erro.
    * Construção e interpretação de intervalos de confiança para a média populacional.

### `ex19-36.ipynb.ipynb` (Exercícios 19 - 36)
* **Aproximação Normal da Distribuição Binomial:**
    * Verificação das condições para a aproximação.
    * Cálculo de média e desvio padrão para a aproximação.
    * Aplicação da correção de continuidade para probabilidades binomiais.
* **Determinação de Tamanho de Amostra:**
    * Para estimar médias populacionais.
    * Para estimar proporções populacionais (com e sem estimativa preliminar).
* **Valores Críticos de Distribuições:**
    * Valores críticos para a distribuição Z (Normal Padrão).
    * Valores críticos para a distribuição t de Student.
    * Valores críticos para a distribuição Qui-Quadrado.
* **Introdução a Testes de Hipóteses:**
    * Formulação de hipóteses nulas e alternativas.
    * Identificação de testes unilaterais (esquerda/direita) e bilaterais.
    * Definição e interpretação de Erros Tipo I e Tipo II.

### `ex37-54.ipynb.ipynb` (Exercícios 37 - 54)
* **Intervalos de Confiança para Variância e Desvio Padrão Populacional:**
    * Utilização da distribuição Qui-Quadrado ($\chi^2$).
    * Cálculo de limites de confiança para $\sigma^2$ e $\sigma$.
* **Testes de Hipóteses para Médias Populacionais (σ Conhecido - Teste Z):**
    * Cálculo da estatística de teste Z.
    * Uso da abordagem do valor-p e da abordagem do valor crítico para decisão.
    * Interpretação dos resultados da decisão no contexto do problema.
* **Testes de Hipóteses para Médias Populacionais (σ Desconhecido - Teste t):**
    * Cálculo da estatística de teste t.
    * Uso da abordagem do valor crítico para decisão.
    * Interpretação da decisão no contexto do problema.

## 🛠️ Tecnologias Utilizadas

* **Python 3.x**
* **Jupyter Notebook:** Para ambiente interativo de desenvolvimento.
* **NumPy:** Para operações numéricas e matemáticas.
* **SciPy:** Especificamente `scipy.stats` para funções de distribuição de probabilidade e estatística inferencial.
* **Matplotlib:** Para a criação de gráficos e visualização de distribuições e regiões de rejeição.
