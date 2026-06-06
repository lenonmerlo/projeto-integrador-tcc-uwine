# Projeto UWine — TCC Ciência de Dados

## Projeto UVWine — Partes 1 e 2

Este repositório reúne as **Partes 1 e 2 do Trabalho de Conclusão de Curso (TCC)**, desenvolvido no contexto do projeto integrador da graduação em **Ciência de Dados**.

O projeto foi construído a partir da base fictícia da **UVWine**, com o objetivo de aplicar técnicas estatísticas, analíticas e de aprendizado de máquina em Python ao longo do ciclo de vida de um projeto de Data Science.

---

## Objetivo da Parte 1

Esta etapa busca responder à seguinte questão central:

**Qual é o tamanho ideal da amostra para representar adequadamente a população de clientes da UVWine?**

Para responder a essa pergunta, foram desenvolvidas análises relacionadas a:

- estratificação amostral da população;
- identificação e interpretação de outliers;
- testes de hipóteses;
- estatística descritiva;
- análise da pesquisa de satisfação;
- validação estatística por bootstrap.

---

## Objetivo da Parte 2

Na Parte 2, o foco passa para a etapa de **Machine Learning**, com os seguintes objetivos:

- preparar e validar os conjuntos `train`, `validation` e `test` gerados na Parte 1;
- construir fluxo de modelagem para tarefas de:
  - regressão;
  - clusterização;
  - classificação;
- comparar modelos e métricas para apoiar a seleção de abordagens mais adequadas ao problema da UVWine.

---

## Estrutura do repositório

- `LENON_MERLO_PARTE_1_TCC.ipynb` — notebook principal com todas as análises da Parte 1;
- `LENON_MERLO_PARTE_1_TCC.pdf` — versão em PDF do notebook;
- `PARTE 2/LENONMERLO_TCC_PARTE_2_V2.ipynb` — versão atualizada da Parte 2;
- `README.md` — documentação geral do projeto.

---

## Base de dados

A base `table25.csv` não foi incluída neste repositório devido ao tamanho do arquivo.

Como se trata da base fornecida para a disciplina, ela deve ser utilizada localmente no mesmo diretório do notebook para que as análises possam ser reproduzidas corretamente.

Na Parte 2, foram utilizados os três datasets derivados da Parte 1 (`df_train.csv`, `df_validation.csv` e `df_test.csv`), cada um com **153.800 linhas** e **23 colunas**.

---

## Principais resultados

Os principais resultados obtidos nesta etapa indicaram que:

- o tamanho ideal da amostra foi estimado em **51.400 observações**;
- a base apresenta **assimetria** e **valores extremos** em variáveis financeiras;
- a variável de satisfação numérica apresentou **forte concentração em valores específicos**, o que exigiu cuidado metodológico na interpretação;
- a satisfação geral estimada foi de **64,79%**;
- a técnica de **bootstrap** confirmou estabilidade e precisão das estimativas.

Na Parte 2, os resultados principais incluíram:

- organização do pipeline de Machine Learning com separação explícita entre treino, validação e teste;
- verificação de consistência dimensional entre os três conjuntos;
- confirmação da estratificação entre grupos de clientes (ESSENTIAL, PRIME e VIP) nos três conjuntos;
- preparação da base para avaliação comparativa de modelos de regressão, clusterização e classificação.

---

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- SciPy
- Scikit-learn
- Seaborn
- Matplotlib
- Statsmodels
- Jupyter Notebook

---

## Acesso ao projeto

- **Google Colab:** [Abrir notebook no Colab](https://colab.research.google.com/drive/1yymRRKpQ1s9WvYUgcVSQVaIuRFaAlOYK?usp=sharing)
- **Google Colab (Parte 2):** [Abrir notebook da Parte 2](https://colab.research.google.com/drive/1qLnw-mwpDW8kejwcaBKaF1SItBmSAOYm?usp=sharing)
- **YouTube:** [Assistir apresentação no YouTube](https://www.youtube.com/watch?v=PF_c_SYjKp4)

---

## Observação

Este projeto foi elaborado para fins acadêmicos, como parte das atividades da disciplina de **Projeto Integrador / TCC**, utilizando uma empresa e um cenário fictícios.

---

## Autor

**Lenon Otmar Tonoli Merlo**
