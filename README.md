# Projeto Limpeza de Dados
Este projeto tem como objetivo a resolução de um problema de logística baseado na distribuição de material escolar em escolas do município do Rio de Janeiro.  Nele, deveríamos fazer o tratamento dos dados fornecidos de acordo com padrões solicitados e encontrar uma rota que otimizasse a distribuição dos materiais em todas as escolas de acordo com suas respectivas localizações.

![vist Card](https://portal.loft.com.br/wp-content/uploads/2022/10/mapa-zonas-bairros-rio-de-janeiro.jpg)


## Índice

- [1. Proposta de Negócios](#1-proposta-de-negócios)

- [2. Compreensão dos Dados](#2-compreensão-dos-dados)

- [3. Plano de Ação](#3-plano-de-ação)

- [4. Insights Extraídos](#4-insights-extraídos)

- [5. Resultados de Negócios](#5-resultados-de-negócios)

- [6. Trabalho Futuro](#6-trabalho-futuro)


## 1. Proposta de Negócios
Fomos contratados para realizar a distribuição de materiais didáticos nas escolas da cidade do Rio de Janeiro. Nossa missão é realizar tratamentos nos dados de acordo com as normas de padrão definidas pelo cliente e encontrar qual a melhor rota que um caminhão deve realizar para entregar os materiais didáticos de forma a otimizar o seu percurso.



## 2. Compreensão dos Dados
Para alcançar esse objetivo, de otimização na entrega de materiais, recebemos três arquivos fundamentais: escolas.csv, subprefeituras.csv e material_didatico.csv. Cada um desses arquivos contém informações cruciais sobre as escolas, os bairros pertencentes a cada subprefeitura e a quantidade de material didático a ser entregue em cada escola, respectivamente.

## 3. Plano de ação
Para executar o projeto de consultoria em dados, foi necessário abordarmos o problema por etapas, tendo como foco inicial o tratamento dos dados recebidos. Após o devido tratamento, os dados foram processados em uma função otimizadora e as escolas finalmente organizadas na melhor ordem esperada para a entrega do material.


### 3.1. Produto final
O produto final consiste em:
- um arquivo csv onde as linhas já estarão ordenadas de acordo com a rota a ser seguida. Além disso, os dados devem estar no padrão especificado abaixo e contendo as seguintes colunas: id da escola, nome da escola, tipo da escola (EM, CIEP ou colégio), logradouro da entrega, número, bairro, subprefeitura, latitude, longitude e quantidade de material didático que deve ser entregue. O logradouro da escola deve estar em uma coluna diferente do número;
- um arquivo csv com a quantidade total de material escolar por subprefeitura para que sejam contabilizados os custos por subprefeitura.
  
Os dados devem estar no seguinte padrão:

- nome das colunas em snake_case
- strings não devem conter acentos
- todas as strings devem estar em maiúsculo
- padronização do nome dos logradouros sem abreviação (Ex: R. deve estar como Rua)
- latitude e longitude devem conter apenas 5 casas decimais
- os ids da escola devem todos ser strings com 3 caracteres (Ex: '024')

### 3.2. Ferramentas e Frameworks
- Python 3.10.0
- Jupyter Notebook
- Git & GitHub
- Bibliotecas: Pandas, Numpy, Matplotlib, Seabord, Plotly




## 4. Insights Extraídos

## 5. Resultados de Negócios

### Objetivo

## 6. Trabalho Futuro
