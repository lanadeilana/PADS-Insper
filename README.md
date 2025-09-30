# Projeto Integrador | PADS - Insper (1º Tri)

Entrega final do Projeto Integrador do 1º trimestre do **Programa Avançado em Ciência de Dados e Decisão (PADS)** do Insper.

---

## Objetivo

Prever a falência de empresas com até dois anos de antecedência, usando dados contábeis e cadastrais históricos de empresas suecas.

---

## Etapas realizadas

### Python (EDA + pré-processamento):
- Tratamento de `missing values`
- Remoção de colunas irrelevantes ou com baixa variabilidade
- Criação da variável-alvo `churn_in_2y`
- Estatísticas descritivas e histogramas
- Geração de colunas transformadas (log)

### R (modelagem preditiva):
- Padronização de variáveis
- Modelos testados:
  - Regressão Logística
  - Árvore de Decisão (rpart)
  - Random Forest (ranger)
  - LASSO (glmnet)
- Avaliação com: AUC, sensibilidade, acurácia, matriz de confusão
- Interpretação dos coeficientes e importância de variáveis

---

## Estrutura dos arquivos

| Arquivo | Descrição |
|--------|-----------|
| `VF_projeto_integrador_1tri_grupo5.ipynb` | Notebook Python com EDA e engenharia de dados |
| `projeto_integrador_ilana_izabelle_julia_livia.html` | Relatório final em HTML com tudo (Python + R) |
| `modelagem_em_R.Rmd` (se aplicável) | Script RMarkdown com os modelos (pode subir ainda) |

---

##  Visualizar projeto completo (HTML)

 Acesse o projeto final com visualização web:

 [Clique aqui para abrir o HTML no navegador](https://htmlpreview.github.io/?https://raw.githubusercontent.com/lanadeilana/PADS-Insper/main/projeto_integrador_ilana_izabelle_julia_livia.html)

---

##  Feito por:

- Ilana García (@lanadeilana)
- Izabelle Silva
- Lívia Bertoni
- Júlia Navarro

---

## Programa Avançado em Data Science e Decisão | Insper

> 1º Trimestre — Módulos: Computação para Ciência de Dados (Python) e Aprendizado Estatístico de Máquina I (R)
