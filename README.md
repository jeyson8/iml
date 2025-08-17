# Análise Churn Case Analytics
Este projeto fazz uma análise preditiva de churn com base em dados fictícios de uma base de clientes de telecomunicações, integrando informações contratuais, demográficas e de NPS (as quais não foram utilizadas).

## Projeto
- 'customer_original.csv': Dados contratuais e serviços
- 'customer_social.csv': Dados demográficos
- 'customer_nps.csv': Pontuação NPS por clientes
- 'case_analytics_churn.ipynb': notebook com o pipeline e visualizações
- 'requirements': lista de dependências para rodar o projeto

## Estapas do código no notebook
**Instalação das dependências**
**Importação das bibliotecas**
**Carregamento das bases via upload**
**Tratamento dos dados da coluna CPF para normalização das bases***
**Avaliação da qualidade dos metadados**
**Análise exploratória**
**Comparação dos 3 modelos**
**Escolha do melhhor modelo**
**Levantamento das principais variáveis para o modelo escolhido**
**Conclusão**

## Dependências (bibliotecas utilizadas)
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- nbformat

## Como utilizar
1. Clone o repositório ou faça o download dos arquivos
2. Instale as dependências por meio do comando 'pip install -r requiriments.txt'
3. Abra o notebook 'case_analytics_churn.ipynb' no Jupyter Notebook ou via Google Colab
4. Execute cada bloco do código, um na sequência do outro para poder replicar e acompanhar a análise construída

## Autor
Projeto desenvolvido por Jeyson Ferreira Alves
