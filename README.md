# Compustat-Global-Financial

# Análise de Impacto de Fatores Financeiros no Faturamento (RECEITA TOTAL)

## **Descrição do Projeto**
Este projeto tem como objetivo analisar o impacto de variáveis independentes, como **pesquisa**, **EBITDA** e **setor**, no **faturamento (RECEITA TOTAL)** das empresas. O foco é identificar como essas variáveis influenciam a receita e determinar os percentuais de contribuição de cada fator para o crescimento ou redução no faturamento.

A análise será baseada em dados financeiros fornecidos e utilizará técnicas de modelagem estatística para responder à seguinte pergunta:

- Para cada dólar investido, como **pesquisa**, **EBITDA** e **setor** afetam o faturamento das empresas?

---

## **Objetivo**
1. Identificar os principais fatores que aumentam ou diminuem a **RECEITA TOTAL**.
2. Quantificar a contribuição percentual de cada variável independente no faturamento.
3. Fornecer insights baseados em setores específicos.

---

## **Estrutura do Projeto**
O projeto será estruturado da seguinte forma:

### **1. Preparação dos Dados**
- **Entrada**: Conjunto de dados contendo as variáveis:
  - `RECEITA_TOTAL` (variável dependente)
  - `PESQUISA` (variável independente)
  - `EBITDA` (variável independente)
  - `SETOR` (variável categórica)
- **Tratamento dos Dados**:
  - Verificação de valores ausentes e outliers.
  - Transformação e normalização, se necessário.
  - Codificação da variável categórica `SETOR`.

### **2. Metodologia**
- **Modelagem Estatística**:
  - Será utilizada uma **Regressão Linear Múltipla** para estimar a relação entre a **RECEITA TOTAL** e as variáveis independentes.
  - O modelo considerará a variável `SETOR` como uma variável dummy para analisar diferenças entre setores.
- **Validação**:
  - Avaliação do modelo com métricas como R² ajustado, erro médio absoluto (MAE) e significância estatística dos coeficientes.
  - Aplicação de testes de multicolinearidade (VIF) para garantir robustez do modelo.

### **3. Resultados Esperados**
- Quantificação da contribuição percentual de:
  - **Pesquisa** no aumento/diminuição da receita.
  - **EBITDA** como proxy de lucratividade operacional.
  - Diferenças entre setores na influência sobre o faturamento.
- Visualizações claras para facilitar a interpretação:
  - Gráficos de dispersão.
  - Gráficos de barras para análise por setor.

### **4. Ferramentas Utilizadas**
- **Linguagem de Programação**:
  - Python (bibliotecas principais: `pandas`, `statsmodels`, `matplotlib`, `seaborn`).
- **Software Estatístico**:
  - Possível uso do R para validação cruzada.
- **Documentação e Apresentação**:
  - Relatórios em PDF e gráficos interativos.

---

## **Requisitos**
### **Dependências do Projeto**
- Python 3.10+
- Bibliotecas Python:
  - `pandas`
  - `numpy`
  - `statsmodels`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`
- Arquivo de dados em formato CSV.


