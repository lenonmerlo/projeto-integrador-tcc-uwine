# Projeto UWine — TCC Ciência de Dados

Este repositório reúne o Trabalho de Conclusão de Curso (TCC) desenvolvido no contexto do projeto integrador da graduação em **Ciência de Dados**.

O projeto foi construído a partir da base fictícia da **UWine**, com o objetivo de aplicar técnicas estatísticas, analíticas e modelos de **Machine Learning** em Python, seguindo o ciclo de vida de um projeto de Data Science.

---

## Visão Geral do Projeto

O TCC foi desenvolvido em duas partes principais:

- **Parte 1:** análise estatística, definição do tamanho ideal da amostra e validação metodológica;
- **Parte 2:** aplicação de modelos de Machine Learning para Regressão, Clusterização e Classificação.

A Parte 1 fundamenta estatisticamente a construção dos conjuntos utilizados na Parte 2.

---

## Parte 1 — Estatística e Amostragem

A primeira etapa buscou responder à seguinte questão central:

**Qual é o tamanho ideal da amostra para representar adequadamente a população de clientes da UWine?**

Para responder a essa pergunta, foram desenvolvidas análises relacionadas a:

- estratificação amostral da população;
- identificação e interpretação de outliers;
- testes de hipóteses;
- estatística descritiva;
- análise da pesquisa de satisfação;
- validação estatística por bootstrap.

### Principais Resultados da Parte 1

A análise mostrou que não havia um único tamanho ideal global para toda a população. Como os grupos apresentaram comportamentos estatísticos distintos, a definição metodologicamente adequada foi estratificada por `TIPO DA CONTA`:

- **ESSENTIAL:** 50.400 observações;
- **PRIME:** 51.700 observações;
- **VIP:** 51.700 observações.

Essa conclusão orientou a construção dos datasets da Parte 2.

---

## Parte 2 — Machine Learning

Na segunda etapa, foram criados três conjuntos de dados independentes:

- `TRAIN`;
- `VALIDATION`;
- `TEST`.

Cada conjunto foi construído com o tamanho ideal completo por grupo, totalizando **153.800 registros por dataset**:

- ESSENTIAL: 50.400 registros;
- PRIME: 51.700 registros;
- VIP: 51.700 registros.

Essa decisão preservou a representatividade estratificada da população em todas as etapas de modelagem.

### Modelos Desenvolvidos

Foram aplicadas três abordagens principais de Machine Learning:

1. **Regressão**
   - Objetivo: estimar a variável `TOTAL (R$)`;
   - Melhor modelo: `Random Forest Regressor`;
   - Resultado no TEST: R² = 0,7017.

2. **Clusterização**
   - Objetivo: identificar agrupamentos naturais nos dados;
   - Modelo utilizado: `KMeans`;
   - A variável `TIPO DA CONTA` foi removida do treinamento e utilizada apenas posteriormente para interpretação supervisionada dos clusters;
   - A rediscretização mostrou casamento parcial entre clusters e tipos reais, com taxa estável em torno de 60,3%.

3. **Classificação**
   - Objetivo: prever `TIPO DA CONTA`;
   - Melhor modelo: `Random Forest Classifier`;
   - Resultado no TEST: Accuracy = 92,18%.

---

## Estrutura do Repositório

- `LENON_MERLO_PARTE_1_TCC.ipynb` — notebook principal da Parte 1;
- `LENON_MERLO_PARTE_1_TCC.pdf` — versão em PDF da Parte 1;
- `PARTE 2/LENONMERLO_TCC_PARTE_2_V2.ipynb` — notebook principal da Parte 2;
- `PARTE 2/LENONMERLO_TCC_PARTE_2.pdf` — versão em PDF da Parte 2;
- `Apresentacao/` — materiais de apresentação do projeto;
- `README.md` — documentação geral do projeto.

---

## Base de Dados

A base `table25.csv` não foi incluída neste repositório devido ao tamanho do arquivo.

Como se trata da base fornecida para a disciplina, ela deve ser utilizada localmente no mesmo diretório do notebook para que as análises possam ser reproduzidas corretamente.

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- SciPy
- Scikit-learn
- Seaborn
- Matplotlib
- Statsmodels
- Jupyter Notebook
- Google Colab

---

## Acesso ao Projeto

- **Google Colab — Parte 1:** [Abrir notebook no Colab](https://colab.research.google.com/drive/1yymRRKpQ1s9WvYUgcVSQVaIuRFaAlOYK?usp=sharing)
- **YouTube — Parte 1:** [Assistir apresentação no YouTube](https://www.youtube.com/watch?v=PF_c_SYjKp4)

---

## Observação

Este projeto foi elaborado para fins acadêmicos, como parte das atividades da disciplina de **Projeto Integrador / TCC**, utilizando uma empresa e um cenário fictícios.

---

## Autor

**Lenon Otmar Tonoli Merlo**
