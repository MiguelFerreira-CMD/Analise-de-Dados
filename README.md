# Análise de Cancelamento de Clientes

Projeto de estudo de **Análise de Dados com Python**, utilizando uma base com mais de 50 mil clientes.

## O que fiz

- Importei a base de dados com Pandas;
- Visualizei e explorei os dados;
- Removi a coluna `CustomerID`;
- Identifiquei valores vazios;
- Removi os registros com dados vazios;
- Analisei quantos clientes cancelaram o serviço;
- Calculei a proporção e a porcentagem de cancelamentos;
- Criei gráficos para analisar as colunas da base;
- Analisei possíveis relações entre:
  - Duração do contrato;
  - Ligações para o call center;
  - Dias de atraso;
  - Frequência de uso;
  - Outras características dos clientes;
- Fiz uma filtragem da base para observar a taxa de cancelamento em um grupo específico de clientes.

## Tecnologias

- Python
- Pandas
- Plotly
- Jupyter Notebook

## Resultado inicial

Na base analisada, aproximadamente **57% dos clientes haviam cancelado o serviço**.

Após a filtragem realizada no exercício, a taxa observada de cancelamento foi de aproximadamente **18%**.

## Estrutura do projeto 📁
```text
  Analise_de_Dados/
│
├── inicial.ipynb       # notebook com toda a análise.
├── cancelamentos.csv     # base de dados utilizada no exercício.
