# Análise das Mudanças Globais no Nível do Mar

Este projeto tem como objetivo analisar as mudanças globais no nível médio do mar ao longo do tempo. Utilizando dados fornecidos pela Agência de Proteção Ambiental dos Estados Unidos (US EPA), pelo CSIRO e pela NOAA, e também as medições realizadas pela NASA por meio do satélite Jason-3, vamos explorar as tendências e a incerteza associadas a essas mudanças.

## Conjunto de Dados

O conjunto de dados utilizado contém informações sobre as mudanças absolutas médias globais no nível do mar a partir de 1880 até 2014. Esses dados combinam medições de longo prazo de marégrafos com medições recentes de satélites. Eles representam as mudanças cumulativas no nível do mar para os oceanos do mundo, considerando a altura da superfície do oceano, independentemente de se a terra próxima está se elevando ou afundando.

A medição do nível do mar realizada pela NASA por meio do satélite Jason-3 utiliza ondas de rádio e outros instrumentos para obter a altura da superfície do oceano. Essas medições são realizadas a cada 10 dias para todo o planeta, permitindo o estudo da evolução do nível médio global do mar ao longo do tempo.

## Análise de Dados

O projeto consiste em uma análise exploratória dos dados e na apresentação de insights relevantes sobre as mudanças no nível do mar. Alguns dos principais aspectos abordados são:

- Visualização da variação do nível médio global do mar ao longo do tempo, utilizando gráficos que destacam as tendências e flutuações sazonais.
- Exploração da incerteza associada às medições do nível do mar, fornecendo insights sobre a confiabilidade dos dados.
- Estatísticas descritivas para compreender as características dos dados, incluindo média, desvio padrão e quartis.
- Análise de correlação entre as medições do nível do mar e a incerteza associada, fornecendo insights sobre possíveis relações entre essas variáveis.

## Pré-requisitos e Instalação

Antes de executar o projeto, é necessário ter instalado o Python e as seguintes bibliotecas:

- Pandas
- Matplotlib
- Seaborn
- Scipy

## Execução do Projeto

Para executar o projeto, siga os passos abaixo:

1. Clone este repositório em sua máquina local.
2. Certifique-se de ter todas as dependências necessárias instaladas.
3. Execute o arquivo `main.py`.
4. Os gráficos e informações serão exibidos no console.

## Resultados e Insights

Com base na análise dos dados, alguns insights importantes podem ser destacados:

- O nível médio global do mar apresenta uma tendência de aumento ao longo do tempo, indicando a ocorrência de mudanças significativas.
- A incerteza associada às medições do nível do mar é relativamente estável ao longo do tempo, sugerindo uma consistência razoável nos dados coletados.
- As estatísticas descritivas revelam uma média negativa para o nível do mar, indicando uma redução média ao longo do período analisado.
- A correlação entre as medições do nível do mar e a incerteza associada é negativa, sugerindo que à medida que o nível do mar aumenta, a incerteza diminui.

Esses insights fornecem informações valiosas para compreender as mudanças no nível do mar e seus possíveis impactos no futuro. É importante destacar que essas conclusões são baseadas nos dados disponíveis e nas análises realizadas até o momento.

### Gráficos

####Variação do Nível Médio Global do Mar
![Gráfico 1](https://github.com/giovanipalo/global-sea-level-change-analysis/blob/main/Global%20Mean%20Sea%20Level%20Variation.png)
Descrição: Este gráfico exibe a variação do nível médio global do mar ao longo do tempo, destacando as flutuações sazonais e as tendências de aumento ao longo dos anos.

####Tendência da Variação do Nível Médio Global do Mar
![Gráfico 2](https://github.com/giovanipalo/global-sea-level-change-analysis/blob/main/Trend%20of%20Global%20Mean%20Sea%20Level%20Variation.png)
Descrição: Neste gráfico, é possível visualizar a tendência de aumento do nível médio global do mar ao longo do tempo, mostrando a direção e a magnitude dessa mudança.

####Incerteza das Medições do Nível Médio Global do Mar
![Gráfico 3](https://github.com/giovanipalo/global-sea-level-change-analysis/blob/main/Uncertainty%20of%20Global%20Mean%20Sea%20Level%20Measurements.png)
Descrição: Esse gráfico ilustra a incerteza associada às medições do nível médio global do mar, fornecendo informações sobre a confiabilidade dos dados coletados.


## Contribuições e Melhorias Futuras

Este projeto é uma análise inicial das mudanças globais no nível do mar e pode ser expandido e aprimorado de várias maneiras. Algumas sugestões de contribuições e melhorias futuras incluem:

- Incorporação de mais conjuntos de dados e fontes confiáveis para ampliar a análise.
- Utilização de técnicas de modelagem para previsão do nível do mar no futuro.
- Análise de tendências regionais e comparação com eventos climáticos específicos.
- Desenvolvimento de uma interface gráfica interativa para facilitar a visualização e exploração dos dados.

Se você deseja contribuir com o projeto, sinta-se à vontade para fazer um fork deste repositório, implementar melhorias e enviar um pull request. Sua colaboração é muito bem-vinda!

## Referências

- US Environmental Protection Agency: [Global Average Absolute Sea Level Change, 1880-2014](https://www.epa.gov/climate-indicators/climate-change-indicators-sea-level)
- CSIRO: [Climate Change: Science and Solutions for Australia](https://www.csiro.au/en/Research/OandA/Areas/Assessing-our-climate/State-of-the-Climate-2016/Oceans/Sea-level)
- NOAA: [Sea Level Trends](https://tidesandcurrents.noaa.gov/sltrends/)
- NASA: [Jason-3](https://www.jpl.nasa.gov/missions/jason-3/)

Os gráficos são os seguintes:

Variação do Nível Médio Global do Mar: Imagem do Gráfico 1
Descrição: Este gráfico exibe a variação do nível médio global do mar ao longo do tempo, destacando as flutuações sazonais e as tendências de aumento ao longo dos anos.

Tendência da Variação do Nível Médio Global do Mar: Imagem do Gráfico 2
Descrição: Neste gráfico, é possível visualizar a tendência de aumento do nível médio global do mar ao longo do tempo, mostrando a direção e a magnitude dessa mudança.

Incerteza das Medições do Nível Médio Global do Mar: Imagem do Gráfico 3
Descrição: Esse gráfico ilustra a incerteza associada às medições do nível médio global do mar, fornecendo informações sobre a confiabilidade dos dados coletados.
