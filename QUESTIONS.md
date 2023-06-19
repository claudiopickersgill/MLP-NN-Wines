1) Escolha uma base de dados. Essa base deve ser multivariada e possuir uma variável objetivo, que pode ser usada na fase de treino (modelos supervisionados) e/ou na validação do modelo (modelos supervisionados e não-supervisionados) <br/>
OBS: Caso você não possua uma base, utilize a base de dados de vinho brancos. Considere bons vinhos aqueles que obtiveram notas >= 6. Como motivo da escolha (questão 2.a) apenas indique utilizou a base proposta pelo professor. <br/>
2) A partir da base escolhida, você irá aplicar as etapas do modelo CRISP de desenvolvimento de projetos em Ciência de Dados: <br/>
    a. Explique a origem dos dados e o motivo para a escolha. Descreva, também, como os dados foram obtidos. Essa é a fase de COMPREENSÃO DO NEGÓCIO.<br/>
    b. Descreva as variáveis do problema e o tipo de cada uma (categórica ou numérica). Mostre a distribuição (usando um histograma) para cada uma delas. Comente sobre a faixa dinâmica de cada uma delas. Essa é a fase de COMPREENSÃO DOS DADOS.<br/>
    c. Descreva o objetivo do modelo que será criado neste projeto.<br/>
    d. Agora faça o tratamento de dados necessários para o treinamento: escalonamento, normalização, transformação de variável (ex: aplicar a função log em uma variável com distribuição exponencial), separação entre treino e teste… Você deve optar pelas tarefas necessárias, descrevendo cada uma delas e justificando o motivo. Essa é a fase PREPARAÇÃO DOS DADOS.<br/>
    e. Agora defina o modelo de redes neural do tipo MLP que você irá utilizar. Essa é a fase de MODELAGEM:<br/>
        I. Quantas camadas?<br/>
        II. Quantos neurônios na camada de entrada?<br/>
        III.Quantos neurônios na camada de saída? Justifique.<br/>
        IV.Quantos números de neurônios na camada intermediária? Como esse número foi escolhido?<br/>
        V. Qual será o algoritmo utilizado no treinamento?<br/>
        VI. Qual a função de ativação será utilizada em cada camada? Justifique.<br/>
        VII. Qual a função de otimização será utilizada neste treinamento?<br/>
        VIII. Quais serão as figuras de mérito que serão usadas na avaliação do modelo. Justifique.<br/>
    f. Apresente os seguintes resultados:<br/>
        I. A matriz de confusão do problema<br/>
        II. O(s) histograma(s) da(s) saída(s) da rede neural<br/>
        III. Os valores das figuras de métrica utilizadas.<br/>
        IV. Caso tenha utilizado validação cruzada no treino, apresente as incertezas para cada um dos resultados anteriores.<br/>
    g. Avalie os resultados, dando sua interpretação de acordo com a compreensão da natureza do problema proposto. Essa é a fase de AVALIAÇÃO DO MODELO.<br/>