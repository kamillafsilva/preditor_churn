# Predição de churn em assinatura de serviços
## Overview
Esse projeto foi desenvolvido durante o curso de [Classificação com Spark da Alura](https://cursos.alura.com.br/course/spark-modelos-classificacao), o objetivo era construir um modelo de classificação binária para estimar a probabilidade de clientes cancelarem um serviço de assinatura. Além das etapas propostas no curso, implementei um processo de otimização dos hiperparâmetros com a biblioteca ``hyperopt``, utilizando a área sob a curva PR como função objetivo. O modelo XGBoost otimizado apresentou o melhor desempenho no conjunto de teste.

## Implementação
O código completo do projeto está disponível neste notebook do Colab: [preditor_churn](https://colab.research.google.com/drive/1u5Z4eGJXAWPZfBBAXtz_rBDyfpF3g1c6?usp=sharing).
