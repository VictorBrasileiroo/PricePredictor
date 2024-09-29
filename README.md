# PricePredict: São Paulo Property Pricing

<img src="img title.svg"></img>

## Bibliotecas Utilizadas

- **pandas**: Utilizada para manipulação e análise de dados em formato tabular.
- **numpy**: Usada para realizar cálculos numéricos e manipulação de arrays.
- **plotly.express**: Permite a criação de gráficos interativos e visualizações de dados.
- **matplotlib**: Usada para criar gráficos estáticos e visualizações.
- **plotly.graph_objects**: Utilizada para criar gráficos mais complexos e personalizados.
- **seaborn**: Uma biblioteca de visualização de dados baseada em matplotlib, que fornece uma interface de alto nível para desenhar gráficos estatísticos.
- **sklearn**: Conjunto de ferramentas para machine learning, utilizado para pré-processamento de dados, treinamento de modelos e avaliação de desempenho.

## Análise de Dados

1. **Leitura do Dataset**  
   O projeto começa com a leitura do conjunto de dados, que contém informações sobre propriedades imobiliárias.

2. **Tratamento dos Dados**  
   - **Identificação de Variáveis Constantes**: Variáveis que não variam entre as entradas são identificadas e removidas para evitar viés nos modelos.

3. **Análise de Correlação**  
   Realiza-se uma análise de correlação entre as variáveis numéricas para entender como elas se relacionam com o preço da propriedade. Um dataframe numérico é criado para este propósito e as correlações são classificadas.

## Treinamento de Machine Learning

1. **Limpeza de Colunas Não Importantes**  
   Colunas que não têm impacto significativo nas previsões são removidas.

2. **Tratamento de Variáveis Categóricas**  
   As variáveis categóricas são convertidas em variáveis numéricas usando one-hot encoding para que possam ser utilizadas nos modelos de machine learning.

3. **Segmentação dos Dados**  
   Os dados são divididos em conjuntos de treino e teste, utilizando 70% dos dados para treino e 30% para teste.

4. **Avaliação dos Modelos**  
   Os modelos são instanciados e treinados. A análise do RMSE (Root Mean Square Error) é realizada para avaliar o desempenho dos modelos.

5. **Cross Validation**  
   Utiliza-se Cross Validation para obter uma avaliação mais robusta do modelo.

## Avaliação e Otimização do Modelo

1. **Seleção do Modelo**  
   O modelo a ser utilizado é selecionado com base em seu desempenho durante a validação.

2. **Busca de Hiperparâmetros com GridSearchCV**  
   Realiza-se uma busca de hiperparâmetros para otimizar o desempenho do modelo.

3. **Validação nos Dados de Teste**  
   O modelo otimizado é avaliado com o conjunto de dados de teste.

4. **Visualização dos Resultados**  
   Os resultados são plotados para comparação entre os valores reais e as previsões.

<img src="img footer.svg"></img>

## Contribuições

Sinta-se à vontade para contribuir com melhorias, sugestões ou correções para este projeto. Pull requests são bem-vindos!


