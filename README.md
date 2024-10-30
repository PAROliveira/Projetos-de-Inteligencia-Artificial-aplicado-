Projeto de Otimização de Sinais de Compra e Venda em Bitcoin com Machine Learning
Índice
Resumo
Introdução
Revisão de Literatura
Metodologia
Criação dos Sinais de Compra e Venda
Feature Engineering
Média Móvel Exponencial (EMA)
Taxa de Variação (Rate of Change - ROC)
Momentum (MOM)
Relative Strength Index (RSI)
Oscilador Estocástico (%K e %D)
Média Móvel Simples (MA)
Modelos de Machine Learning
Random Forest
Otimização de Hiperparâmetros com Grid Search
Resumo
Inicialmente idealizado como um sistema de pagamento descentralizado e peer-to-peer, o Bitcoin evoluiu para se tornar uma reserva de valor e um ativo altamente volátil. A aplicação de técnicas de Machine Learning (ML) oferece uma abordagem inovadora para a otimização de sinais de compra e venda de Bitcoin, analisando grandes volumes de dados históricos, identificando padrões e ajustando estratégias de forma automatizada e dinâmica.

Introdução
A previsão de retornos de ativos financeiros é essencial para decisões de investimento. Técnicas de Machine Learning (ML) automatizam a construção de modelos analíticos e permitem identificar padrões complexos em dados financeiros. No contexto do trading de Bitcoin, a aplicação de algoritmos como o Random Forest se mostrou eficiente na previsão de preços e tendências de mercado.

Revisão de Literatura
Estratégias tradicionais: A análise técnica estuda padrões de preço e volume, enquanto a análise fundamentalista avalia fatores econômicos para determinar o valor intrínseco.
Machine Learning no trading: Algoritmos de ML como redes neurais profundas e Random Forest têm mostrado eficácia na previsão de retornos e tendências de mercado.
Metodologia
Criação dos Sinais de Compra e Venda
Implementação de sinais baseados em médias móveis de curto e longo prazo. Se a média de curto prazo estiver acima da média de longo prazo, indica-se compra; caso contrário, venda ou inatividade.

Feature Engineering
Média Móvel Exponencial (EMA)
Uma média ponderada que dá maior peso aos preços mais recentes, usada para diferentes tendências (curto, médio e longo prazo).

Taxa de Variação (Rate of Change - ROC)
Mede a variação percentual do preço em relação a um período anterior, captando mudanças de curto e médio prazo.

Momentum (MOM)
Calcula a diferença entre o preço atual e o preço de períodos anteriores, medindo a força da tendência.

Relative Strength Index (RSI)
Um oscilador que mede a velocidade e a mudança dos movimentos de preços, indicando condições de sobrecompra ou sobrevenda.

Oscilador Estocástico (%K e %D)
Avalia a posição do preço de fechamento em relação aos máximos e mínimos de um período, identificando sobrecompra ou sobrevenda.

Média Móvel Simples (MA)
Calcula a média dos preços de fechamento sobre um intervalo específico.

Modelos de Machine Learning
Testamos diferentes algoritmos de Machine Learning para classificação, medindo o desempenho com validação cruzada de 10 folds. Incluímos algoritmos como Random Forest, KNN, LDA, entre outros.

Random Forest
Utiliza um modelo de ensemble para combinar múltiplas árvores de decisão, aumentando a precisão e evitando overfitting. Inclui otimização de hiperparâmetros com Grid Search e validação cruzada.

Otimização de Hiperparâmetros com Grid Search
Os dados de treinamento foram padronizados usando StandardScaler para garantir média zero e desvio padrão unitário. Utilizamos Grid Search para ajuste dos hiperparâmetros.
