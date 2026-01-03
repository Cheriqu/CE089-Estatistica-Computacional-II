# Teoria dos Valores Extremos (TVE) - UFPR

Este repositório contém as aplicações práticas desenvolvidas para a disciplina de Teoria dos Valores Extremos. O foco é a modelagem de caudas de distribuição e a predição de eventos que ocorrem com baixa frequência, mas possuem severidade extrema.



## 🛠️ Conteúdo Técnico

Os trabalhos exploram as principais abordagens para dados extremos:

### 1. Método dos Máximos de Blocos (Block Maxima)
* **Distribuição GEV:** Ajuste da *Generalized Extreme Value Distribution*, unificando as famílias Gumbel, Fréchet e Weibull para modelar os máximos anuais ou mensais.
* **Estacionariedade:** Verificação de tendências temporais nos dados (ex: aumento da temperatura máxima ao longo dos anos).

### 2. Inferência e Predição de Risco
* **Níveis de Retorno (Return Levels):** Cálculo da magnitude esperada de um evento para períodos de retorno específicos (ex: "qual o nível da enchente esperada para daqui a 100 anos?").
* **Diagnóstico de Ajuste:** Avaliação da qualidade do modelo através de gráficos de probabilidade (PP-plot) e quantil (QQ-plot).
* **Incerteza:** Estimação de intervalos de confiança para os parâmetros de forma ($\xi$), escala ($\sigma$) e localização ($\mu$).

---

## 🚀 Tecnologias e Implementação

* **Linguagem:** R.
* **Pacotes Específicos:** `extRemes`, `ismev` ou `evd` (bibliotecas padrão para TVE no R).
* **Relatórios:** Análises reprodutíveis em R Markdown, documentando desde a análise exploratória até a interpretação dos riscos.

---

## 📂 Estrutura de Arquivos

* `Extremos.Rmd` / `.pdf`: Análise fundamental focada no ajuste da distribuição GEV e interpretação dos parâmetros.
* `Trabalho2.rmd` / `.pdf`: Aplicação prática avançada, possivelmente envolvendo comparação de modelos ou dados ambientais específicos.

---
**Autor:** Luiz Henrique Barretta Francisco  
*Graduado em Estatística / Mestrando em Métodos Numéricos em Engenharia - UFPR*
