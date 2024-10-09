# Projetos-de-Inteligencia-Artificial-aplicado-
# Projeto de Classificação e Agrupamento de Empresas

Este projeto utiliza algoritmos de aprendizado de máquina para classificar empresas em boas e ruins, e em seguida aplicar técnicas de agrupamento para identificar padrões ocultos nos dados financeiros.

## Organização do Repositório

- **README.md**: Este arquivo, com informações sobre o projeto.
- **main.ipynb**: Notebook principal contendo a explicação detalhada da estratégia, execução do código, e geração de relatórios.


## Descrição do Projeto

O projeto é dividido em duas partes principais:

1. **Classificação de Empresas**:
   - Nesta etapa, utilizamos algoritmos supervisionados, como **Árvores de Decisão** e **Redes Neurais**, para classificar as empresas em boas ou ruins. Foram utilizados vários indicadores financeiros, ponderados de acordo com sua importância, para treinar os modelos e prever a classificação das empresas.
   - O processo incluiu a transformação logarítmica dos dados e ajustes de pesos para variáveis que influenciam positivamente ou negativamente o resultado.

2. **Agrupamento de Empresas**:
   - Após a classificação, aplicamos algoritmos de agrupamento **não supervisionados**, como o **K-Means**, para identificar padrões ocultos nos dados. Isso nos permitiu agrupar empresas com características semelhantes, independente de sua classificação como boa ou ruim.
   - Além disso, utilizamos o **PCA (Análise de Componentes Principais)** para reduzir a dimensionalidade dos dados, facilitando a visualização dos clusters em gráficos bidimensionais.
   - No final, os resultados foram apresentados em gráficos de dispersão, mostrando a separação dos clusters e as médias de atributos financeiros para cada grupo.

## Primeiros Passos


1. Execute o notebook principal `main.ipynb` para visualizar a estratégia de classificação e agrupamento de empresas, além dos resultados gerados.
2. Utilize os gráficos e relatórios para interpretar os padrões e insights obtidos com o agrupamento.

> Observação: Toda a lógica de classificação e agrupamento é implementada em arquivos dentro do documento main.ipynb, e é chamada no notebook para fins de visualização e geração de relatórios.
