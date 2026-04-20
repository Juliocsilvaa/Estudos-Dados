# 🌐 Requests — Consumo de APIs com Python

Esta pasta documenta o estudo da biblioteca **Requests**, utilizada para realizar requisições HTTP em Python, permitindo a comunicação com APIs e serviços externos.

O foco deste estudo está na compreensão dos fundamentos de consumo de APIs e na aplicação prática desses conceitos em cenários reais de coleta de dados.


## 📚 Sobre a Biblioteca

A biblioteca **Requests** é uma das principais ferramentas para realizar requisições HTTP em Python, sendo amplamente utilizada para:

- Consumo de APIs REST;
- Coleta de dados de serviços externos;
- Integração entre sistemas;
- Automação de fluxos baseados em requisições web.

Ela abstrai a complexidade das requisições HTTP, permitindo trabalhar de forma simples com métodos como:

- `GET`
- `POST`
- `PUT`
- `DELETE`

## 🧠 Aplicação

Os conceitos estudados com a biblioteca Requests foram aplicados em dois contextos com foco em ingestão e integração de dados.

O primeiro ocorreu em um projeto desenvolvido na disciplina de **Introdução à Ciência de Dados**, disponível neste repositório ([Ver Projeto](https://github.com/Juliocsilvaa/Projetos-Pessoais/tree/main/Disciplina%20Introdu%C3%A7%C3%A3o%20a%20Ciencia%20de%20Dados/Projeto%202)), no qual a biblioteca foi utilizada para ingestão de dados hidrológicos via API, estruturando a coleta de dados externos para posterior tratamento e análise.

O segundo contexto envolveu a utilização da biblioteca para consulta e extração de dados a partir do ambiente do Databricks, atuando como mecanismo de integração entre sistemas e permitindo a incorporação de dados ao fluxo analítico. Este repositório, em específico, tem como objetivo demonstrar a implementação desse processo, com foco na integração via API e consumo de dados no Databricks.

## ⚙️ Principais Conceitos Explorados

Durante o estudo, foram abordados:

### 🔹 Requisições HTTP
- `requests.get()` para obtenção de dados;
- Envio de parâmetros via URL (`params`);
- Uso de headers quando necessário.

### 🔹 Tratamento de Respostas
- Acesso ao conteúdo da resposta (`response.text`);
- Conversão para JSON (`response.json()`);
- Verificação de status (`response.status_code`).

### 🔹 Estrutura de APIs
- Endpoints;
- Parâmetros de consulta;
- Formato de resposta (JSON);
- Paginação (quando aplicável).


## 🛠️ Tecnologias Utilizadas

- Python
- Requests
- Pandas (para tratamento posterior dos dados)
- Dotenv
- Jupyter Notebook

