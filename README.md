# Otimização de Sinais de Compra e Venda em Bitcoin com Machine Learning

## Índice
- [Resumo](#resumo)
- [Introdução](#introdução)
- [Revisão de Literatura](#revisão-de-literatura)
- [Metodologia](#metodologia)
  - [Criação dos Sinais de Compra e Venda](#criação-dos-sinais-de-compra-e-venda)
  - [Feature Engineering](#feature-engineering)
    - [Média Móvel Exponencial (EMA)](#média-móvel-exponencial-ema)
    - [Taxa de Variação (Rate of Change - ROC)](#taxa-de-variação-rate-of-change---roc)
    - [Momentum (MOM)](#momentum-mom)
    - [Relative Strength Index (RSI)](#relative-strength-index-rsi)
    - [Oscilador Estocástico (%K e %D)](#oscilador-estocástico-k-e-d)
    - [Média Móvel Simples (MA)](#média-móvel-simples-ma)
  - [Modelos de Machine Learning](#modelos-de-machine-learning)
    - [Random Forest](#random-forest)
    - [Otimização de Hiperparâmetros com Grid Search](#otimização-de-hiperparâmetros-com-grid-search)
- [Conclusão](#conclusão)
- [Referências](#referências)

---

## Resumo
Este projeto visa otimizar sinais de compra e venda para Bitcoin utilizando técnicas de Machine Learning (ML). Com a análise de dados históricos, o modelo identifica padrões de mercado e ajusta estratégias de forma automatizada, fornecendo uma abordagem dinâmica para o trading de Bitcoin.

## Introdução
Com a evolução do Bitcoin de um sistema de pagamento para um ativo de reserva de valor volátil, o uso de ML para prever movimentos de mercado tornou-se relevante. Este projeto aplica algoritmos de ML, como Random Forest, para analisar tendências e prever preços de Bitcoin.

## Revisão de Literatura
A revisão de literatura aborda:
1. **Análise Técnica**: Estudo de padrões de preço e volume.
2. **Análise Fundamentalista**: Avaliação de fatores econômicos para determinar o valor intrínseco do ativo.
3. **ML no Trading**: Aplicações de algoritmos de ML, como redes neurais profundas e Random Forest, que mostraram eficácia em prever retornos de mercado.

## Metodologia

### Criação dos Sinais de Compra e Venda
Implementação de sinais de compra e venda com médias móveis de curto e longo prazo. A estratégia considera a posição relativa entre as médias móveis para indicar compra, venda ou inatividade.

### Feature Engineering
O projeto inclui diversas métricas para enriquecer os dados usados nos modelos de ML:

#### Média Móvel Exponencial (EMA)
A EMA dá maior peso aos preços mais recentes e ajuda a capturar tendências em diferentes períodos.

#### Taxa de Variação (Rate of Change - ROC)
Calcula a variação percentual do preço em relação a um período anterior, capturando mudanças de curto e médio prazo.

#### Momentum (MOM)
Indica a força de uma tendência ao calcular a diferença entre o preço atual e o preço de períodos passados.

#### Relative Strength Index (RSI)
Um indicador que mede a velocidade e magnitude dos movimentos de preços, identificando condições de sobrecompra ou sobrevenda.

#### Oscilador Estocástico (%K e %D)
Acompanha a posição do preço em relação aos máximos e mínimos em um período específico, ajudando a identificar condições de mercado.

#### Média Móvel Simples (MA)
Calcula a média dos preços de fechamento em um intervalo determinado, fornecendo uma visão geral da tendência de mercado.

### Modelos de Machine Learning
Os dados foram analisados com diferentes algoritmos de classificação, medindo desempenho com validação cruzada de 10 folds. Algoritmos testados incluem Random Forest, KNN e LDA, entre outros.

#### Random Forest
Um ensemble de múltiplas árvores de decisão, que aumenta a precisão e ajuda a evitar overfitting. Inclui otimização de hiperparâmetros com Grid Search.

#### Otimização de Hiperparâmetros com Grid Search
Ajuste dos hiperparâmetros por meio do Grid Search, com dados de treinamento padronizados usando o StandardScaler para garantir média zero e desvio padrão unitário.

## Conclusão
O projeto demonstrou que técnicas de Machine Learning aplicadas a sinais de compra e venda para Bitcoin oferecem uma abordagem inovadora para traders, otimizando decisões de mercado com análise dinâmica e automatizada.

## Referências
- [Referências detalhadas sobre revisão de literatura e algoritmos utilizados]

