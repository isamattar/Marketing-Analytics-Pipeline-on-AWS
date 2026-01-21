Plataforma de Análise de Performance de Campanhas Publicitárias na AWS



Visão Geral

Este projeto tem como objetivo desenvolver uma plataforma de análise de dados de campanhas publicitárias, utilizando serviços da AWS e técnicas de Data Science, simulando um cenário real do mercado de Publicidade e Propaganda.



O projeto foi desenvolvido com foco acadêmico e profissional, demonstrando um pipeline completo de dados, desde a ingestão até a análise e visualização de KPIs estratégicos de campanhas.



Aviso Importante: Este projeto utiliza dados fictícios, criados apenas para fins educacionais. 



Problema de Negócio

Empresas de publicidade lidam com grandes volumes de dados de campanhas vindos de diferentes mídias e formatos. A ausência de um ambiente centralizado dificulta:



&nbsp;	• A análise de performance das campanhas

&nbsp;	• A comparação entre tipos de mídia

&nbsp;	• A mensuração de ROI

&nbsp;	• A tomada de decisões baseadas em dados



Este projeto busca resolver esse problema por meio de um Data Lake na AWS, permitindo análises escaláveis e organizadas.



Objetivos do Projeto

&nbsp;	• Construir um pipeline de dados na AWS

&nbsp;	• Centralizar dados de campanhas publicitárias

&nbsp;	• Realizar tratamento e padronização dos dados (ETL)

&nbsp;	• Analisar KPIs de marketing e mídia

&nbsp;	• Criar visualizações para suporte à tomada de decisão



Arquitetura da Solução



Fluxo de Dados:

&nbsp;	1. Dados de campanhas (CSV)

&nbsp;	2. Upload para Amazon S3 (Data Lake)

&nbsp;	3. Processamento e limpeza com AWS Glue

&nbsp;	4. Consultas analíticas com Amazon Athena (SQL)

&nbsp;	5. Análise exploratória com Python (Pandas)

&nbsp;	6. Visualização via Power BI / Amazon QuickSight



&nbsp;Serviços AWS Utilizados

&nbsp;	• Amazon S3 – Armazenamento dos dados brutos e processados

&nbsp;	• AWS IAM – Gerenciamento de permissões

&nbsp;	• AWS Glue – ETL e catalogação de dados

&nbsp;	• Amazon Athena – Consultas SQL

&nbsp;	• Amazon CloudWatch – Monitoramento e logs

&nbsp;	• Amazon QuickSight – Dashboard



Estrutura dos Dados

Os dados simulam campanhas publicitárias e estão organizados em arquivos CSV:

&nbsp;campaigns.csv

&nbsp;	• campaign\_id

&nbsp;	• client

&nbsp;	• media\_type (OOH, Digital, Retail Media)

&nbsp;	• start\_date

&nbsp;	• end\_date

&nbsp;	• budget

impressions.csv

&nbsp;	• campaign\_id

&nbsp;	• date

&nbsp;	• impressions

&nbsp;	• clicks

&nbsp;	• cost

&nbsp;sales\_impact.csv

&nbsp;	• campaign\_id

&nbsp;	• date

&nbsp;	• conversions

&nbsp;	• revenue



&nbsp;KPIs Analisados

&nbsp;	• Impressões totais

&nbsp;	• CTR (Click Through Rate)

&nbsp;	• CPC (Custo por Clique)

&nbsp;	• CPA (Custo por Aquisição)

&nbsp;	• ROI por campanha

&nbsp;	• Performance por tipo de mídia

&nbsp;	• Receita gerada vs investimento



&nbsp;Tecnologias Utilizadas

&nbsp;	• Python

&nbsp;	• Pandas

&nbsp;	• SQL

&nbsp;	• AWS SDK (Boto3)

&nbsp;	• Amazon Athena

&nbsp;	• AWS Glue

&nbsp;	• Streamlit / QuickSight

&nbsp;	• Git \& GitHub

&nbsp;

Como Executar o Projeto (Resumo)

&nbsp;	1. Criar um bucket no Amazon S3

&nbsp;	2. Fazer upload dos arquivos CSV

&nbsp;	3. Configurar Glue Crawler e Glue Job

&nbsp;	4. Executar consultas no Athena

&nbsp;	5. Realizar análises em Python

&nbsp;	6. Visualizar os resultados no dashboard



&nbsp;Diferenciais do Projeto

&nbsp;	• Pipeline completo de dados na AWS

&nbsp;	• Projeto alinhado ao mercado de publicidade

&nbsp;	• Aplicação prática de Data Science

&nbsp;	• Boa organização e documentação

&nbsp;	• Ideal para estágio e posições júnior



Próximos Passos

&nbsp;	• Automatizar ingestão com AWS Lambda

&nbsp;	• Integração com APIs de mídia digital

&nbsp;	• Aplicar modelos de Machine Learning para previsão de performance

&nbsp;	• Deploy do dashboard em ambiente cloud



&nbsp;Contexto Acadêmico

Projeto desenvolvido como parte do aprendizado em Data Science (1/2º semestre), com foco em Cloud Computing e análise de dados aplicados ao negócio.



Contato

Desenvolvido por Isabella Mattar



Estudante de Data Science | AWS | Python | Analytics

