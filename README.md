# Projeto de Detecção de Emails de Spam

## Visão Geral

Este projeto tem como objetivo desenvolver um modelo robusto de aprendizado de máquina para a detecção de emails de spam, garantindo alta precisão na identificação de mensagens indesejadas, ao mesmo tempo em que minimiza falsos positivos. O foco principal é criar um sistema que classifique com precisão os emails como spam ou não-spam (ham), mantendo o número de falsos positivos o mais baixo possível.

## Destaques do Projeto

- Implementou várias técnicas e algoritmos de aprendizado de máquina para construir e avaliar modelos de detecção de spam.
- Escolheu o modelo de Regressão Logística devido ao seu ótimo desempenho em termos de falsos positivos.
- Alcançou um resultado notável com apenas 8 casos de falsos positivos no modelo final.
- Demonstrou a importância de reduzir os falsos positivos para melhorar a experiência do usuário e a credibilidade do sistema.

## Conjunto de Dados

O projeto utilizou um conjunto de dados bem selecionado de mensagens de email, categorizadas como spam e ham, para treinar e avaliar os modelos de aprendizado de máquina. O conjunto de dados foi pré-processado para extrair características relevantes dos emails e convertê-las para formato numérico adequado para o treinamento do modelo.

## Seleção do Modelo

Após experimentação rigorosa com vários algoritmos de aprendizado de máquina, como Naive Bayes, SVC, Random Forest, XGBoost e Regressão Logística, o modelo de Regressão Logística se destacou como o melhor desempenho. Ele demonstrou uma capacidade notável de minimizar falsos positivos, mantendo ao mesmo tempo alta precisão na detecção de spam.

## Resultados

O modelo de Regressão Logística escolhido apresentou os seguintes resultados:
- Total de casos de falsos positivos: 8
- Alta precisão em distinguir entre emails de spam e ham.
- Redução de interrupções para os usuários, evitando eficazmente que emails legítimos sejam marcados como spam.

## Conclusão

Este projeto aborda com sucesso o desafio de minimizar falsos positivos na detecção de emails de spam. O modelo de Regressão Logística escolhido demonstra sua capacidade de discernir efetivamente emails de spam, reduzindo significativamente a ocorrência de falsos positivos. Ao equilibrar precisão e recall, o modelo fornece uma solução confiável para filtragem de emails, contribuindo para uma experiência mais eficiente e amigável ao usuário.
