Análise de Churn de Clientes - Telecom X parte 2

Para a parte final do desafio foi realizada a moodelagem dos dados com os conceitos de Machine Learning para o projeto "Churn de Clientes" da empresa fictícia Telecom X. Esteb reposiotório faz parte da formação em Data Science da Alura.

O trabalho foi conduzido em Python e foram as bibliotecas pandas, seaborn, matplotlib, numpy, statsmodels, sklearn e imblearn. 

Objetivos do Desafio

    Preparar os dados para a modelagem (tratamento, encoding, normalização).
    Realizar análise de correlação e seleção de variáveis.
    Treinar dois ou mais modelos de classificação.
    Avaliar o desempenho dos modelos com métricas.
    Interpretar os resultados, incluindo a importância das variáveis.
    Criar uma conclusão estratégica apontando os principais fatores que influenciam a evasão.

Para concluir o desafio foram utilizados conceitos:
    Pré-processamento de dados para Machine Learning
    Construção e avaliação de modelos preditivos
    Interpretação dos resultados e entrega de insights
    Comunicação técnica com foco estratégico

Processos execultados:

Foi realizado a análise de multicolienaridade e foram desconsideradas 3 variáveis para dar seguimento ao estudo.
Os dados foram separados entre 30% teste, 70% treino e foi utilizado o método SMOTE para balanceamento.

Modelagem dos dados:
Para fins de comparação foi feita a modelagem através dos dados balanceados e desbalanceados.

    Regressão logística: teve um melhor ajuste com os dados balanceados.
    KNN (K-Nearest Neighbors): trouxe melhores resultados com os dados desbalanceados.
    Random Forest: maior acurácia geral, mas menos eficaz para detectar os cancelamentos.
    SVM (Support Vector Machine):maior acurácia com os dados desbalanceados, porém previu apenas metade dos cancelamentos.

Com base nos resultados obtidos após implementar os 4 modelos preditivos foi observado que o que possui um melhor ajuste é o de Regressão Logística com os dados balanceados que apresentou um maior acerto para a variável alvo.

Fatores que mais influenciam no cancelamento: 

    Tempo de contrato: clientes recentes têm maior risco de cancelar.
    Frequência de uso: baixa utilização aumenta risco.
    Satisfação/Feedback: baixa satisfação gera alto risco de cancelamento.
    Tipo de plano: planos básicos ou menos completos geram maior evasão.
    Problemas financeiros: clientes com problemas de pagamento são mais propensos a cancelar.
    Engajamento: pouca interação aumenta risco de churn.

    

