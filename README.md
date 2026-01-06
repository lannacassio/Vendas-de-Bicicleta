# Relatório de Análise do Banco de Dados BikeStores

## Introdução

Este relatório descreve o banco de dados contido no arquivo `BikeStores.xlsx`, que registra vendas de bicicletas em lojas localizadas nos estados da Califórnia (CA), Nova York (NY) e Texas (TX). O dataset inclui informações sobre pedidos, clientes, produtos, categorias, marcas, lojas e representantes de vendas, abrangendo o período de 2016 a 2018.

## Dados
* [Dados históricos](https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/BikeStores.xlsx) de vendas de bicicletas de 2016 a 2018 em formato **.xlsx**;
* **Intervalo dos Dados**: Janeiro de 2016 a Dezembro de 2018, ocupando 246KB;
* O Cojunto possui informações como a categoria, marca, loja, cidade e estado em que foi vendida.

## Perguntas de Negócio Abordadas

Os dashboards foram projetados para responder às seguintes perguntas de negócio chave:
  1. **Qual é a evolução anual da receita e o crescimento ano a ano?** 
  2. **Quais são os padrões mensais de receita, incluindo sazonalidades e picos?** 
  3. **Qual loja gera mais receita e qual é a contribuição relativa de cada uma?** 
  4. **Como a receita se distribui por estado?** 
  5. **Quais são os top 10 clientes por receita gerada?** 
  6. **Quais marcas contribuem mais para a receita total?** 
  7. **Qual é o desempenho por categoria de produto?** 
  8. **Quais representantes de vendas têm o melhor desempenho?** 

## Processamento e limpeza
* Os dados foram baixados para o HD local para manipulação e análise usando o **Excel** e **Power BI**;
* [**Dashboard**];
* Antes da limpeza, todo o dataset possuia  linhas 4.723 linas;
* **Processo de limpeza:** Alteração do Formato de Número da coluna Revenue (Renda).



O repositório no GitHub pode incluir este relatório, o arquivo Excel original, versão Excel alterado para análise e a versão em Power BI.

## Dashboard: Receita Anual

Este dashboard mostra a receita total gerada por ano, permitindo identificar tendências de crescimento ou declínio nas vendas.

### Receita Anual

</head>
<body>
       <table>
              <tr>
                     <td><img src= "https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Excel/Imagens/Receita%20Anual.png"></td>            
              </tr>
       </table>
</body>
</html>                                                             

**Insights**:
- A receita cresceu de 2016 para 2017 (aumento de aproximadamente 42%), mas diminuiu em 2018 (queda de cerca de 47% em relação a 2017).
- Receita total acumulada: 8,578,988.88 USD.
- Possíveis razões para a queda em 2018: Dados incompletos ou sazonalidade (observam-se lacunas mensais).

## Dashboard: Receita Mensal

Este dashboard exibe a receita por mês, útil para análise de sazonalidade e padrões mensais.

| Mês      | Receita ($) |
|----------|---------------|
| 2016-01 | 241,184.15   |
| 2016-02 | 175,768.10   |
| 2016-03 | 202,157.14   |
| 2016-04 | 187,223.55   |
| 2016-05 | 228,701.13   |
| 2016-06 | 231,120.29   |
| 2016-07 | 222,854.21   |
| 2016-08 | 253,130.83   |
| 2016-09 | 303,282.61   |
| 2016-10 | 235,051.79   |
| 2016-11 | 205,315.47   |
| 2016-12 | 223,695.20   |
| 2017-01 | 316,954.77   |
| 2017-02 | 348,740.47   |
| 2017-03 | 348,177.13   |
| 2017-04 | 254,105.57   |
| 2017-05 | 297,754.66   |
| 2017-06 | 419,892.07   |
| 2017-07 | 255,727.63   |
| 2017-08 | 322,553.32   |
| 2017-09 | 329,388.68   |
| 2017-10 | 345,316.18   |
| 2017-11 | 315,881.67   |
| 2017-12 | 291,022.87   |
| 2018-01 | 426,301.72   |
| 2018-02 | 223,941.44   |
| 2018-03 | 406,701.20   |
| 2018-04 | 909,179.47   |
| 2018-06 | 209.99       |
| 2018-07 | 12,949.89    |
| 2018-08 | 10,256.91    |
| 2018-09 | 9,949.96     |
| 2018-10 | 4,219.92     |
| 2018-11 | 12,278.93    |
| 2018-12 | 7,999.96     |

**Insights**:
- Pico em setembro de 2016 (303,282.61 USD) e junho de 2017 (419,892.07 USD).
- Em 2018, abril destaca-se com 909,179.47 USD, mas há meses com receitas baixas ou ausentes (ex.: maio ausente).
- Tendência: Maiores vendas no meio do ano em 2016-2017.

## Dashboard: Receita por Loja

Análise da contribuição de cada loja para a receita total.

| Loja             | Receita (USD) |
|------------------|---------------|
| Baldwin Bikes   | 5,826,242.21 |
| Santa Cruz Bikes | 1,790,145.91 |
| Rowlett Bikes    | 962,600.76   |

**Insights**:
- Baldwin Bikes domina com 68% da receita total.
- Santa Cruz Bikes e Rowlett Bikes representam 21% e 11%, respectivamente.

## Dashboard: Receita por Estado

Distribuição de receita por estado, alinhada com a localização das lojas.

| Estado | Receita (USD) |
|--------|---------------|
| NY     | 5,826,242.21 |
| CA     | 1,790,145.91 |
| TX     | 962,600.76   |

**Insights**:
- Nova York (NY) é o principal mercado, correspondendo à loja Baldwin Bikes.
- Califórnia (CA) e Texas (TX) seguem, refletindo as outras lojas.

## Dashboard: Top 10 Receitas por Cliente

Lista dos 10 clientes com maior receita gerada, útil para identificar clientes VIP.

| Cliente          | Receita (USD) |
|------------------|---------------|
| Pamelia Newman  | 37,801.84    |
| Abby Gamble     | 37,500.89    |
| Sharyn Hopkins  | 37,138.86    |
| Lyndsey Bean    | 35,857.86    |
| Emmitt Sanchez  | 34,503.82    |
| Melanie Hayes   | 34,390.88    |
| Debra Burks     | 30,645.87    |
| Elinore Aguilar | 29,661.83    |
| Corrina Sawyer  | 29,214.89    |
| Shena Carter    | 27,618.95    |

**Insights**:
- Os top 10 clientes geram receitas individuais entre 27k e 37k USD.
- Foco em retenção desses clientes pode impulsionar vendas.

## Dashboard: Receita por Marca

Receita gerada por cada marca de bicicleta.

| Marca       | Receita (USD) |
|-------------|---------------|
| Trek       | 5,129,381.61 |
| Electra    | 1,344,143.79 |
| Surly      | 1,063,135.82 |
| Sun Bicycles | 381,919.69  |
| Haro       | 207,096.69   |
| Heller     | 193,798.71   |
| Pure Cycles | 166,164.00  |
| Ritchey    | 88,498.82    |
| Strider    | 4,849.75     |

**Insights**:
- Trek domina com 60% da receita.
- Marcas como Electra e Surly são fortes em segmentos específicos.

## Dashboard: Receita por Categoria

Distribuição de receita por categoria de produto.

| Categoria            | Receita (USD) |
|----------------------|---------------|
| Mountain Bikes      | 3,030,775.71 |
| Road Bikes          | 1,852,555.60 |
| Cruisers Bicycles   | 1,109,151.04 |
| Electric Bikes      | 1,020,236.85 |
| Cyclocross Bicycles | 799,874.60   |
| Comfort Bicycles    | 438,506.87   |
| Children Bicycles   | 327,888.21   |

**Insights**:
- Mountain Bikes e Road Bikes representam cerca de 57% da receita total.
- Crescimento potencial em Electric Bikes, uma categoria emergente.

## Dashboard: Receita por Representante de Vendas

Desempenho dos representantes de vendas medido pela receita gerada.

| Representante     | Receita (USD) |
|-------------------|---------------|
| Marcelene Boyer  | 2,938,888.73 |
| Venita Daniel    | 2,887,353.48 |
| Genna Serrano    | 952,722.26   |
| Mireya Copeland  | 837,423.65   |
| Kali Vargas      | 516,695.17   |
| Layla Terrell    | 445,905.59   |

**Insights**:
- Marcelene Boyer e Venita Daniel são os top performers, responsáveis por mais de 68% da receita.
- Oportunidades de treinamento para representantes com desempenho inferior.

## Conclusão

Este banco de dados fornece insights valiosos sobre o desempenho de vendas da BikeStores. Os dashboards destacam tendências anuais e mensais, contribuições por loja e estado, clientes chave, marcas e categorias populares, e o impacto dos representantes de vendas. Recomendações incluem expansão em mercados de alto desempenho (como NY) e foco em categorias crescentes (como Electric Bikes).

Para mais detalhes, consulte o código Python usado para gerar essas análises no repositório GitHub. Contribuições e atualizações são bem-vindas!
