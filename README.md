# Projeto Tech Challenge Fase 2 - Entrega Final

Este repositório contém a entrega final do **Projeto Tech Challenge Fase 2**, desenvolvido pelo grupo composto por:
- **Renato Moreno Ferreira** - rm358385
- **Jose Everton Saraiva Santos** - rm359724

## Descrição do Projeto

O objetivo deste projeto foi desenvolver um pipeline de dados com scripts com Scrap de dados para buscar informações da B3 e do BTC, envolvendo toda uma infraestrutura dos serviços da aws para inserir dados em uma estrutura de Data-Lake, criar processos de ETL com aws glue e visualizações com o athena.

### Funcionalidades:
- Captação e tratamento de dados do site da B3 e captação de precos do Bitcoin pela api da coinGecko.
      Benefício: Automatiza a coleta de dados diretamente da fonte, garantindo que as informações estejam atualizadas diariamente.
- Armazenamento dos arquivos processados no Data-Lake AWS S3, com classificação de dados brutos e refinados.
- Leitura dos dados atraves dos serviços do aws athena.
- Ele é útil para analistas financeiros, desenvolvedores de sistemas de mercado, ou qualquer pessoa que precise trabalhar com dados de pregões de forma eficiente

## Estrutura Técnica

A seguir, detalhamos os 4 repositórios que compõem a estrutura do projeto.

### 1. Repositório de Infraestrutura e Deploy

Este repositório contém as configurações de deploy e a infraestrutura do projeto, criada com AWS CDK. Ele inclui pipelines para gerenciar o deploy da aplicação na AWS.

- [Repositório de Infraestrutura e Deploy no GitHub](https://github.com/Renatmf5/aws-infra-tc2)

### 2. Repositórios dos scripts de Scrap de dados da B3 e Bitcoin e scripts do GLUE.

- [Repositório da scrap-b3 no GitHub](https://github.com/Renatmf5/scrap-b3)

- [Repositório da scrap-btc no GitHub](https://github.com/Renatmf5/scrap-btc)

- [Repositório da Glue-Script no GitHub](https://github.com/Renatmf5/glue-b3-script)
