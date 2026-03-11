# ETL Pipeline de Vendas com Python

Este projeto demonstra a construção de um pipeline ETL simples utilizando Python e Pandas no Jupyter Notebook.

O objetivo é extrair, transformar e carregar dados de vendas simulados.

## Tecnologias utilizadas

- Python
- Pandas
- Jupyter Notebook

## Estrutura do projeto

data/
   raw/
      vendas.csv

   processed/
      vendas_tratadas.csv

ETL_pipeline_vendas.ipynb

## Etapas do Pipeline

### Extract
Leitura de um dataset CSV contendo informações de vendas.

### Explore
Análise inicial dos dados utilizando:
- info()
- describe()
- verificação de valores nulos

### Transform
Transformações aplicadas:

- Conversão da coluna de data
- Criação da coluna `revenue`
- Extração de ano, mês e dia

### Load
Salvamento dos dados processados na pasta:

data/processed/vendas_tratadas.csv

## Resultado

O pipeline gera um dataset tratado pronto para análise de dados ou modelagem.

## Autor

Projeto desenvolvido para prática de Engenharia de Dados / Ciência de Dados.
