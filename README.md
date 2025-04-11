# Prevendo Vendas de Sorvete com Machine Learning (Gelato Mágico) 🍦📊

## Desafio DIO - Prevendo Vendas de Sorvete com Machine Learning

Este é um projeto para aplicar conceitos de Machine Learning na previsão de vendas de sorvete com base na temperatura do dia. O objetivo é construir um modelo preditivo que auxilie donos de sorveterias, como a Gelato Mágico, a otimizar sua produção, reduzir desperdícios e maximizar lucros.

## Cenário

Imagine ser o proprietário da sorveteria Gelato Mágico em uma cidade litorânea. A quantidade de sorvetes vendidos diariamente parece ter uma forte correlação com a temperatura ambiente. Utilizaremos Machine Learning para prever as vendas e planejar a produção de forma eficiente.

## Objetivo

O objetivo deste projeto é desenvolver um modelo de regressão preditiva que permita:

✅ Treinar um modelo de Machine Learning para prever as vendas de sorvete com base na temperatura do dia.
✅ Registrar e gerenciar o modelo usando o MLflow.
✅ Implementar o modelo para previsões em tempo real em um ambiente de cloud computing.
✅ Criar um pipeline estruturado para treinar e testar o modelo, garantindo reprodutibilidade.

## Prints

![]

## Descrição do Processo

Neste projeto, pretendo seguir os seguintes passos:

1.  **Entendimento do Problema:** Compreender a relação entre temperatura e vendas de sorvete.
2.  **Coleta de Dados:** Simular dados de temperatura e vendas de sorvete (inicialmente).
3.  **Escolha do Modelo:** Utilizar um modelo de regressão linear para prever as vendas.
4.  **Implementação:** Escrever o código em Python usando scikit-learn para treinar o modelo.
5.  **Registro com MLflow (Planejado):** Integrar o MLflow para rastrear experimentos e registrar o modelo.
6.  **Implantação (Ideia):** Considerar a implantação em um serviço de nuvem como Azure ML ou localmente com Flask.
7.  **Pipeline (Planejado):** Estruturar o código em um pipeline para reprodutibilidade.
8.  **Avaliação:** Avaliar o desempenho do modelo usando métricas de regressão.

## Insights

Até o momento, percebi a forte intuição por trás da correlação entre temperatura e vendas de sorvete. A utilização de Machine Learning pode trazer um planejamento muito mais preciso para negócios sazonais como sorveterias.

## Possibilidades (Após a IA analisar minhas sentenças)

Com base nas sentenças no arquivo `inputs/sentencas.txt`:

> O sol estava forte hoje.
> Muitas pessoas foram à praia.
> A temperatura subiu bastante durante a tarde.
> As crianças adoram sorvete no verão.
> A previsão do tempo indicava calor.

Uma IA poderia analisar essas sentenças e fornecer os seguintes insights e possibilidades para o projeto de previsão de vendas de sorvete:

* **Confirmação da Correlação:** As sentenças reforçam a ideia de que dias quentes e ensolarados, especialmente no verão e com pessoas indo à praia, tendem a aumentar a demanda por sorvete.
* **Sugestão de Dados Adicionais:** A IA poderia sugerir a inclusão de dados como:
    * Dias da semana (fins de semana podem ter mais vendas).
    * Feriados (podem impulsionar as vendas).
    * Eventos locais (shows, festivais na praia).
    * Previsão do tempo detalhada (além da temperatura, considerar umidade, probabilidade de chuva).
    * Localização da sorveteria (proximidade da praia, centros urbanos).
* **Estratégias de Marketing:** A IA poderia sugerir insights para estratégias de marketing, como promoções em dias de alta temperatura ou em locais com grande concentração de pessoas (praias, parques).
* **Otimização de Estoque:** A previsão precisa pode ajudar não apenas na produção, mas também na gestão de estoque de diferentes sabores, antecipando os mais procurados em dias de calor.
* **Análise Sazonal:** A IA poderia destacar a importância de analisar a sazonalidade das vendas ao longo do ano, com picos no verão e quedas em estações mais frias.

