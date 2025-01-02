# README: Data Preparation for Churn Classification

## Context

Este notebook foi criado para preparar um conjunto de dados que será utilizado na tarefa de classificação de Churn. Ele utiliza um dataset fictício de uma empresa de telefonia, criado e disponibilizado pela IBM com fins didáticos. O dataset original e o dicionário de features podem ser encontrados [neste link no Kaggle](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset).

## Objetivo

O objetivo principal deste notebook é:

- Realizar a análise exploratória do dataset.
- Executar a limpeza, transformação e engenharia de dados.
- Preparar o conjunto de dados para ser utilizado em modelos de aprendizado de máquina.

## Requisitos

### Bibliotecas Necessárias

O notebook utiliza as seguintes bibliotecas:

- `numpy`
- `pandas`
- `pandas-profiling`
- `seaborn`
- `matplotlib`
- `scikit-learn`

Instalação de dependências adicionais:

```bash
!pip install pandas-profiling==3.3.0
```

### Ambiente

Certifique-se de estar utilizando um ambiente Python 3.7 ou superior, com Jupyter Notebook ou JupyterLab instalado.

## Estrutura do Notebook

### 1. Configurações Iniciais

As bibliotecas são importadas e as dependências instaladas. Aqui também é definida a configuração inicial para visualização de dados e análise exploratória.

### 2. Carregamento e Análise do Dataset

- O dataset é carregado em um DataFrame do pandas.
- Uma análise exploratória é realizada utilizando a biblioteca `pandas-profiling` para identificar valores ausentes, distribuições de variáveis e possíveis problemas nos dados.

### 3. Limpeza e Transformação

- Tratamento de valores ausentes.
- Codificação de variáveis categóricas (One-Hot Encoding e Ordinal Encoding).
- Padronização de variáveis numéricas.

### 4. Engenharia de Features

- Criação de novas features que podem aumentar a performance do modelo de classificação.
- Seleção de variáveis relevantes para o problema.

### 5. Exportação dos Dados Preparados

Os dados processados são exportados para serem utilizados em etapas subsequentes, como treinamento de modelos de aprendizado de máquina.

## Como Utilizar

1. **Clone ou baixe este repositório.**
2. **Instale as dependências listadas.**
3. **Abra o notebook em seu ambiente Jupyter.**
4. **Execute as células sequencialmente.**

## Referências

- [Telco Customer Churn Dataset - Kaggle](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset)
- Documentação oficial das bibliotecas utilizadas.

## Contribuição

Sugestões e melhorias são bem-vindas. Envie suas ideias através de pull requests ou entre em contato.

---

Este README foi projetado para facilitar a compreensão e execução do notebook. Certifique-se de seguir as instruções para garantir que o processo de preparação do dataset seja realizado com sucesso.

