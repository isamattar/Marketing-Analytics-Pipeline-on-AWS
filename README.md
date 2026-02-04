# Plataforma de Análise de Performance de Campanhas Publicitárias na AWS

## Visão Geral
Este projeto tem como objetivo desenvolver uma plataforma de análise de dados de campanhas publicitárias, utilizando serviços da AWS e técnicas de Data Science, simulando um cenário real do mercado de Publicidade e Propaganda.

O projeto foi desenvolvido com foco acadêmico e profissional, demonstrando um pipeline completo de dados, desde a ingestão até a análise e visualização de KPIs estratégicos de campanhas.

> **Aviso Importante:** Este projeto utiliza dados fictícios, criados apenas para fins educacionais.

## Problema de Negócio
Empresas de publicidade lidam com grandes volumes de dados de campanhas vindos de diferentes mídias e formatos. A ausência de um ambiente centralizado dificulta:

- A análise de performance das campanhas
- A comparação entre tipos de mídia
- A mensuração de ROI
- A tomada de decisões baseadas em dados

Este projeto busca resolver esse problema por meio de um Data Lake na AWS, permitindo análises escaláveis e organizadas.

## Objetivos do Projeto
- Construir um pipeline de dados na AWS
- Centralizar dados de campanhas publicitárias
- Realizar tratamento e padronização dos dados (ETL)
- Analisar KPIs de marketing e mídia
- Criar visualizações para suporte à tomada de decisão

## Arquitetura da Solução

### Fluxo de Dados:
1. Dados de campanhas (CSV)
2. Upload para Amazon S3 (Data Lake)
3. Processamento e limpeza com AWS Glue
4. Consultas analíticas com Amazon Athena (SQL)
5. Análise exploratória com Python (Pandas)
6. Visualização via Power BI / Amazon QuickSight

### Serviços AWS Utilizados
- **Amazon S3:** Armazenamento dos dados brutos e processados
- **AWS IAM:** Gerenciamento de permissões
- **AWS Glue:** ETL e catalogação de dados
- **Amazon Athena:** Consultas SQL
- **Amazon CloudWatch:** Monitoramento e logs
- **Amazon QuickSight:** Dashboard

## Estrutura dos Dados
Os dados simulam campanhas publicitárias e estão organizados em arquivos CSV:

**`campaigns.csv`**
- `campaign_id`
- `client`
- `media_type` (OOH, Digital, Retail Media)
- `start_date`
- `end_date`
- `budget`

**`impressions.csv`**
- `campaign_id`
- `date`
- `impressions`
- `clicks`
- `cost`

**`sales_impact.csv`**
- `campaign_id`
- `date`
- `conversions`
- `revenue`

## KPIs Analisados
- Impressões totais
- CTR (Click Through Rate)
- CPC
