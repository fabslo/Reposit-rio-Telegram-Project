# Projeto de Automação de Dados com Telegram e AWS

Bem-vindo ao repositório do projeto de automação de dados utilizando o Telegram em conjunto com os serviços da AWS. Este repositório tem como objetivo apresentar os códigos e detalhes do pipeline implementado para automatizar a coleta e processamento de dados do Telegram, integrando diversos serviços da AWS.

## Motivação

O objetivo principal deste projeto é fornecer uma solução eficiente para a automação de dados provenientes do Telegram. A combinação de bots do Telegram e serviços da AWS, como Athena, S3, EventBridge e Lambda, permite criar um pipeline robusto que facilita a extração, transformação e carga (ETL) de dados de maneira escalável e eficaz.

## Arquitetura do Projeto

A seguir, apresentamos a arquitetura do projeto, destacando a integração entre os componentes principais.

![Arquitetura do Projeto](![Projeto-Telegram_page](https://github.com/fabslo/Reposit-rio-Telegram-Project/assets/152207178/2e37d7a9-7e87-407a-9cb8-59d8b964c957)
)

- **Bot do Telegram:** Responsável por coletar dados e enviá-los para o pipeline.
- **Lambda Functions:** Funções serverless que executam as etapas de processamento e integração dos dados.
- **Amazon S3:** Armazena os dados brutos e processados de maneira eficiente.
- **Amazon Athena:** Permite consultas SQL diretamente nos dados armazenados no S3.
- **Amazon EventBridge:** Orquestra e automatiza as ações do pipeline.

## Contexto do Projeto

Este projeto visa facilitar a automação de tarefas relacionadas a dados provenientes do Telegram, proporcionando uma integração perfeita com os serviços da AWS. A seguir, destacamos os principais aspectos do contexto do projeto:

- **Coleta de Dados:** Utiliza bots do Telegram para coletar dados relevantes.
- **Processamento Assíncrono:** O EventBridge dispara eventos que acionam as Lambda Functions para o processamento assíncrono dos dados.
- **Armazenamento Eficiente:** Os dados são armazenados de forma eficiente no Amazon S3, possibilitando fácil escalabilidade.
- **Consulta SQL Dinâmica:** A integração com o Athena permite consultas SQL dinâmicas nos dados armazenados no S3.

Fique à vontade para explorar os códigos e documentação fornecidos neste repositório. Contribuições e feedback são sempre bem-vindos!
