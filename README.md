# Projeto Limpezad de Dados
O projeto atual tem como objetivo a otimização da distribuição de materiais didáticos nas escolas da cidade do Rio de Janeiro. Nossa consultoria foi contratada para realizar tratamentos nos dados fornecidos de acordo com padrões específicos e encontrar a melhor rota para a entrega eficiente dos materiais.

![vist Card](https://cdn.discordapp.com/attachments/1205131422378098728/1205131482625212447/TOUT.webp?ex=65d74127&is=65c4cc27&hm=758e087a03e2a21fb286f31f66dff790ebfcc970e1f4f2cb29dc8ba24b7f2d40&)


## Índice

- [1. Proposta de Negócios](#1-proposta-de-negócios)

- [2. Compreensão dos Dados](#2-compreensão-dos-dados)

- [3. Plano de Ação](#3-plano-de-ação)

- [4. Insights Extraídos](#4-insights-extraídos)

- [5. Resultados de Negócios](#5-resultados-de-negócios)

- [6. Trabalho Futuro](#6-trabalho-futuro)


## 1. Proposta de Negócios
Para alcançar esse objetivo, de otimização na entrega de materiais, recebemos três arquivos fundamentais: escolas.csv, subprefeituras.csv e material_didatico.csv. Cada um desses arquivos contém informações cruciais sobre as escolas, os bairros pertencentes a cada subprefeitura e a quantidade de material didático a ser entregue em cada escola, respectivamente.



## 2. Compreensão dos Dados

## 3. Plano de ação
Para alcançar esse objetivo, de otimização na entrega de materiais, recebemos três arquivos fundamentais: escolas.csv, subprefeituras.csv e material_didatico.csv. Cada um desses arquivos contém informações cruciais sobre as escolas, os bairros pertencentes a cada subprefeitura e a quantidade de material didático a ser entregue em cada escola, respectivamente.


### 3.1. Meta final
O produto final a ser entregue consiste em dois arquivos CSV. O primeiro arquivo terá as linhas ordenadas de acordo com a rota otimizada de entrega. As colunas seguirão um padrão específico, com informações como id da escola, nome da escola, tipo da escola (EM, CIEP ou colégio), logradouro e número da entrega, bairro, subprefeitura, latitude, longitude e quantidade de material didático. Vale ressaltar que o logradouro da escola será separado em uma coluna distinta para o número.

### 3.2. Ferramentas e Frameworks

Escopo das ferramentas usadas no projeto:

- Python 3.10.0
- Jupyter Notebook
- Git & GitHub
- Pandas
- Numpy

### 3.3. Instalação do Projeto

1. **Clonar o Repositório (se necessário):**

   Se o projeto estiver hospedado em um repositório git, você pode cloná-lo para o seu ambiente local. Use o seguinte comando no terminal:

   ```bash
   git clone git@github.com:user_github/projeto-limpeza-de-dados
   ```

2. **Navegar até o Diretório do Projeto:**

   Mude para o diretório do projeto usando o comando `cd`:

   ```bash
   cd projeto-limpeza-de-dados
   ```

3. **Criar um Ambiente Virtual (opcional, mas recomendado):**

   Crie um ambiente virtual para isolar as dependências do projeto. Isso é especialmente útil para evitar conflitos entre diferentes projetos. Use o seguinte comando:

   ```bash
   python -m venv nome-do-ambiente
   ```

   Ative o ambiente virtual:

   - No Windows:

     ```bash
     nome-do-ambiente\Scripts\activate
     ```

4. **Instalar as Dependências:**
   Agora, você pode instalar as dependências do projeto usando o arquivo `requirements.txt`. Execute o seguinte comando:

   ```bash
   pip install -r requirements.txt
   ```

   Isso instalará todas as bibliotecas e versões específicas listadas no arquivo `requirements.txt`.

5. **Verificar a Instalação:**
   Após a instalação, você pode verificar se todas as dependências foram instaladas corretamente:

   ```bash
   pip freeze
   ```

### 3.4. Processo CRISP-DM
A metodologia [CRIPS-DM](https://www.ibm.com/docs/en/spss-modeler/saas?topic=dm-crisp-help-overview) foi aplicada para traçar meu plano de ação. Este é o processo, passo a passo:

<p align="center">
 <img src="https://cdn.discordapp.com/attachments/1181695164633329824/1181695982753304697/CRISP-DM_Flowchart_ElderResearch_Circular-1.png?ex=6581ff25&is=656f8a25&hm=978e079ffa29bbb54af68d891c7318a2bb1f9a30f3ac0c144434b96df3e2a367&"  style="zoom:65%"/>
</p>


**Passo 1. Entendimento do Negócio:**

**Passo 2. Compreensão dos Dados:**

**Passo 3. EDA:**

**Passo 4. Preparação dos Dados:**

**Passo 5. Seleção de Features:**
    
**Passo 6. Modelagem de Machine Learning:**

**Passo 7. Avaliação:**


## 4. Insights Extraídos

## 5. Resultados de Negócios

### Objetivo

## 6. Trabalho Futuro
