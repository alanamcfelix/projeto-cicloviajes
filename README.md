# projeto-cicloviajes
O projeto visa realizar uma análise exploratória de dados do programa de compartilhamento de bicicletas Citi Bike em Nova York, utilizando o conjunto de dados disponível no Google BigQuery. O objetivo é entender o padrão de uso das bicicletas, identificar tendências, e fornecer informações detalhadas sobre o comportamento dos usuários.
# Análise do Programa de Compartilhamento de Bicicletas Citi Bike

## Descrição do Projeto

Este projeto realiza uma análise exploratória dos dados do programa Citi Bike em Nova York. Utilizamos o conjunto de dados disponível no Google BigQuery para entender o padrão de uso das bicicletas, identificar tendências e fornecer insights sobre o comportamento dos usuários.

## Objetivo

O objetivo principal é transformar dados brutos em insights acionáveis. Buscamos entender o uso das bicicletas, identificar padrões e fornecer recomendações para a melhoria do serviço com base em métricas como número total de viagens, duração média das viagens e distribuição por faixa etária e tipo de usuário.

## Equipe

- Alana Felix.


## Tecnologias e Ferramentas Utilizadas

- **Google BigQuery:** Para consulta e processamento dos dados.
- **Looker Studio (Google Data Studio):** Para a criação de visualizações interativas e relatórios.
- **SQL:** Linguagem usada para transformação e preparação dos dados.

## Processamento e Análises

1. **Transformação dos Dados:**
   - Criação de novas variáveis:
     - `start_time`: Hora de início da viagem, calculada a partir do `stoptime` e `tripduration`.
     - `year`: ano da viagem extraído da `stopdate`.
   - Categorização de idades em faixas etárias:
     - Menos de 20
     - 20-29
     - 30-39
     - 40-49
     - 50-59
     - 60 ou mais

2. **Métricas de Uso:**
   - Total de viagens realizadas.
   - Duração média das viagens.
   - Distribuição de viagens por faixa etária, tipo de usuário e gênero.

3. **Visualizações Criadas:**
   - **Número total de viagens:** Cartão de Informação (Scorecard).
   - **Tempo médio, mínimo e máximo das viagens:** Cartão de Informação (Scorecard).
   - **Número de viagens por ano por tipo de assinatura:** Gráfico de Linha.
   - **Distribuição de viagens por faixa etária:** Gráfico de Barras.
   - **Distribuição de viagens por tipo de usuário:** Gráfico de Pizza.
   - **Distribuição de viagens por gênero:** Gráfico de Pizza.


## Resultados e Conclusões

- **Visão Geral:** resumo das métricas principais, como número total de viagens e média diária de viagens.
- **Tendências:** análise das tendências ao longo do tempo e padrões de uso entre diferentes variáveis demográficas.
- **Recomendações:** sugestões para a melhoria do serviço baseadas nos padrões identificados, como ajustes na infraestrutura e estratégias de marketing.

## Limitações e Próximos Passos

- **Limitações:**
  - Possíveis erros ou omissões nos dados.
  - Dependência da precisão e completude dos dados fornecidos.
  
- **Próximos Passos:**
  - Integração de dados adicionais, como feedback dos usuários e condições climáticas.
  - Monitoramento contínuo das tendências e ajustes nas estratégias conforme necessário.





## Arquivo no Looker Studio: 
https://lookerstudio.google.com/reporting/5b66a1fd-63cc-4572-b7a8-d58c950f9809



