# 🚀 Automacao De Indicadores

Este repositório contém o projeto "Automacao De Indicadores" desenvolvido no Jupyter Notebook, com o objetivo de automatizar o envio diário de e-mails com dados para gerentes e diretoria. O programa visa facilitar o processo de coletar dados de vendas de uma base de dados e realizar análises, separando os dados por lojas e enviando relatórios personalizados para cada gerente.

## 📋 Descrição do projeto

O programa lê o arquivo de vendas principal, denominado Vendas.xlsx, e realiza as seguintes etapas:

1. Separação de dados por lojas: Com base no arquivo Lojas.csv, o programa cria uma pasta separada para cada loja dentro da pasta "Backup Arquivos Lojas". Em seguida, salva as vendas correspondentes a cada loja em uma planilha individual.

2. Análise de metas: O programa realiza uma análise dos dados de vendas por loja e gera relatórios contendo informações sobre o desempenho em relação às metas estabelecidas. Esses relatórios são enviados por e-mail para os respectivos gerentes.

3. Relatório para diretoria: Além dos relatórios para os gerentes, o programa envia um e-mail para a diretoria com informações sobre a melhor e pior loja do dia, bem como a melhor loja do ano até o momento e a pior.

## 📦 Arquivos complementares

O projeto utiliza os seguintes arquivos complementares:

- Emails.xlsx: Planilha que contém os endereços de e-mail dos gerentes e da diretoria.
- Lojas.csv: Arquivo que lista as lojas e suas informações correspondentes.
- Vendas.xlsx: Arquivo principal contendo os dados de vendas.

A pasta "Backup Arquivos Lojas" é criada para armazenar as vendas separadas por loja em planilhas individuais.

Nota: Este projeto é uma demonstração de automação de processo básica e pode ser personalizado e aprimorado conforme suas necessidades específicas.
