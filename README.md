# Análise de Dados de SRAG

Este repositório contém um projeto de análise de dados sobre os casos de Síndrome Respiratória Aguda Grave (SRAG), focado na identificação de fatores de risco, padrões temporais e geográficos, e a aplicação de modelos de machine learning para previsão de evolução dos casos.

## Objetivo

O objetivo principal deste projeto foi analisar os dados históricos de notificações de SRAG para identificar padrões relevantes, como fatores de risco associados a óbitos, distribuição geográfica dos casos, e tendência ao longo do tempo. Além disso, foram explorados modelos preditivos para prever a evolução dos casos e otimizar a gestão de recursos e intervenções de saúde.

## Análises Realizadas

1. **Análises Temporais:**
   - Identificação de períodos críticos, como o aumento de casos entre abril e junho.
   - Análise da tendência semanal, com pico de casos nas segundas-feiras.
   - Sugestão de modelos de séries temporais (como SARIMAX) para previsões mais assertivas.

2. **Análises Geográficas:**
   - A região Sudeste apresentou o maior número de casos, com destaque para os estados de SP, MG e RJ.
   - A análise mostrou uma distribuição geográfica intensa nas regiões mais densamente povoadas.

3. **Análise de Fatores de Risco:**
   - Identificação dos principais fatores de risco associados aos óbitos, como cardiopatia, diabetes e pneumonia.
   - Verificação de que 77% dos óbitos ocorreram em pacientes com fatores de risco identificados.

4. **Análise de Sintomas:**
   - Identificação dos sintomas mais comuns entre pacientes com SRAG, com destaque para dor de garganta, saturação de oxigênio no sangue, febre e dispneia.

## Modelos de Machine Learning

Foram utilizados dois modelos de machine learning:

1. **Random Forest Classifier:** Para prever a evolução do SRAG com base nos fatores de risco.
2. **Gradient Boosting:** Para uma segunda análise com foco em otimização e maior precisão nos resultados.

Ambos os modelos mostraram bons resultados, mas há espaço para melhorias, especialmente na otimização de hiperparâmetros.

## Conclusão

As análises realizadas mostram que, com base em dados históricos e predições por meio de modelos de machine learning, é possível tomar decisões mais eficazes para o controle da SRAG. Estratégias de prevenção e intervenção podem ser aprimoradas com o uso de dados, resultando em respostas mais rápidas e assertivas. Além disso, a análise dos fatores de risco pode ajudar a identificar grupos mais vulneráveis e, assim, reduzir a mortalidade.
