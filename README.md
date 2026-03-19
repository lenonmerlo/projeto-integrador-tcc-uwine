# TCC UVVine - Parte 1

Este repositório apresenta a **Parte 1** do Trabalho de Conclusão de Curso (TCC), desenvolvida no contexto do projeto integrador da graduação em **Ciência de Dados**.

O projeto utiliza a base fictícia da empresa **UVVine** com o objetivo de aplicar técnicas estatísticas e analíticas em Python, contemplando as etapas iniciais do ciclo de vida de um projeto de Data Science.

## Objetivo da Parte 1

Esta etapa tem como foco responder à seguinte questão principal:

**Qual é o tamanho ideal da amostra para representar adequadamente a população de clientes da UVVine?**

Para isso, foram desenvolvidas análises relacionadas a:

- estratificação amostral da população;
- identificação de outliers;
- testes de hipóteses;
- estatística descritiva;
- análise da pesquisa de satisfação;
- validação por bootstrap.

## Estrutura do repositório

- `LENON_MERLO_PARTE_1_TCC.ipynb`: notebook principal com todas as análises da Parte 1.
- `LENON_MERLO_PARTE_1_TCC.pdf`: versão em PDF do notebook.
- `README.md`: descrição geral do projeto.

## Base de dados

A base `table25.csv` não foi incluída neste repositório devido ao tamanho do arquivo. Como se trata da base fornecida para a disciplina, ela deve ser utilizada localmente no mesmo diretório do notebook para reprodução das análises.

## Principais resultados

Os resultados obtidos indicaram que:

- o tamanho ideal da amostra é de **51.400 observações**;
- a base apresenta assimetria e valores extremos em variáveis financeiras;
- a variável de satisfação apresenta forte concentração em valores específicos;
- a satisfação geral estimada foi de **64,79%**;
- a técnica bootstrap confirmou estabilidade e precisão das estimativas.

## Tecnologias utilizadas

- Python
- Pandas
- NumPy
- SciPy
- Seaborn
- Matplotlib
- Statsmodels
- Jupyter Notebook

## Observação

Este projeto foi elaborado para fins acadêmicos, como parte das atividades da disciplina de **Projeto Integrador / TCC**, utilizando cenário e empresa fictícios.

## Autor

**Lenon Otmar Tonoli Merlo**
