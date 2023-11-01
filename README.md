# Projeto de Detecção de Emails de Spam

## Conjunto de Dados

O projeto utilizou um conjunto de dados bem selecionado de mensagens de email, categorizadas como spam e ham, para treinar e avaliar os modelos de aprendizado de máquina. O conjunto de dados foi pré-processado para extrair características relevantes dos emails e convertê-las para formato numérico adequado para o treinamento do modelo.

## Seleção do Modelo

Após experimentação com vários algoritmos de aprendizado de máquina, como Naive Bayes, SVC, Random Forest, XGBoost e Regressão Logística, o modelo de Regressão Logística se destacou como o melhor desempenho.

## Resultados

O modelo de Regressão Logística escolhido apresentou os seguintes resultados:
- Total de casos de falsos positivos: 8
- Alta precisão em distinguir entre emails de spam e ham.
- Redução de interrupções para os usuários, evitando eficazmente que emails legítimos sejam marcados como spam.
