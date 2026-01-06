# Relatório de Análise do Banco de Dados BikeStores

## Introdução

Este relatório descreve o banco de dados contido no arquivo [`BikeStores.xlsx`](https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/BikeStores.xlsx), que registra vendas de bicicletas em lojas localizadas nos estados da Califórnia (CA), Nova York (NY) e Texas (TX). O dataset inclui informações sobre pedidos, clientes, produtos, categorias, marcas, lojas e representantes de vendas, abrangendo o período de 2016 a 2018.

## Dados
* [Dados históricos](https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/BikeStores.xlsx) de vendas de bicicletas de 2016 a 2018 em formato **.xlsx**;
* **Intervalo dos Dados**: Janeiro de 2016 a Dezembro de 2018, ocupando 246KB;
* O Cojunto possui informações como a categoria, marca, loja, cidade e estado em que foi vendida.

## Perguntas de Negócio Abordadas

Os dashboards foram projetados para responder às seguintes perguntas de negócio chave:
       . Qual é a evolução anual da receita e o crescimento ano a ano?
       . Quais são os padrões mensais de receita, incluindo sazonalidades e picos?
       . Qual loja gera mais receita e qual é a contribuição relativa de cada uma?
       . Como a receita se distribui por estado?
       . Quais são os top 10 clientes por receita gerada?
       . Quais marcas contribuem mais para a receita total?
       . Qual é o desempenho por categoria de produto?
       . Quais representantes de vendas têm o melhor desempenho?
  

## Processamento e limpeza
* Os dados foram baixados para o HD local para manipulação e análise usando o **Excel** e **Power BI**;
* [**Dashboard**](https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Power%20BI/BikeStore.pbix);
* Antes da limpeza, todo o dataset possuia  linhas 4.723 linas;
* **Processo de limpeza:** Alteração do Formato de Número da coluna Revenue (Renda).



O repositório no GitHub pode incluir este relatório, o arquivo Excel original, versão [Excel](https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Excel/An%C3%A1lise_BikeStores.xlsx) alterado para análise e a versão em [Power BI](https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Power%20BI/BikeStore.pbix).

## Dashboard: Receita Anual

Este dashboard mostra a receita total gerada por ano, permitindo identificar tendências de crescimento ou declínio nas vendas.


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
- Receita total acumulada: $ 8,578,988.88.
- Possíveis razões para a queda em 2018: Dados incompletos ou sazonalidade (observam-se lacunas mensais).

## Dashboard: Receita Mensal

Este dashboard exibe a receita por mês, útil para análise de sazonalidade e padrões mensais.
</head>
<body>
       <table>
              <tr>
                     <td><img src= "https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Excel/Imagens/Receita%20Mensal.png"></td>            
              </tr>
       </table>
</body>
</html>    


**Insights**:
- Pico em setembro de 2016 ($ 303.282,61), junho de 2017 ($ 419.892,07).
- Em 2018, abril destaca-se com 909,179.47 USD, mas há meses com receitas baixas ou ausentes (ex.: maio ausente).
- Tendência: Maiores vendas no meio do ano em 2016-2017.

## Dashboard: Receita por Loja

Análise da contribuição de cada loja para a receita total.
</head>
<body>
       <table>
              <tr>
                     <td><img src= "https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Excel/Imagens/Receita%20por%20Loja.png"></td>            
              </tr>
       </table>
</body>
</html>   

**Insights**:
- Baldwin Bikes domina com 68% da receita total.
- Santa Cruz Bikes e Rowlett Bikes representam 21% e 11%, respectivamente.

## Dashboard: Receita por Estado

Distribuição de receita por estado, alinhada com a localização das lojas.
</head>
<body>
       <table>
              <tr>
                     <td><img src= "https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Excel/Imagens/Receita%20por%20Estado.png"></td>            
              </tr>
       </table>
</body>
</html>   

**Insights**:
- Nova York (NY) é o principal mercado, correspondendo à loja Baldwin Bikes.
- Califórnia (CA) e Texas (TX) seguem, refletindo as outras lojas.

## Dashboard: Top 10 Receitas por Cliente

Lista dos 10 clientes com maior receita gerada, útil para identificar clientes VIP.
</head>
<body>
       <table>
              <tr>
                     <td><img src= "https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Excel/Imagens/Maiores%20Clientes.png"></td>            
              </tr>
       </table>
</body>
</html>   

**Insights**:
- Os top 10 clientes geram receitas individuais entre 27k e 37k USD.
- Foco em retenção desses clientes pode impulsionar vendas.

## Dashboard: Receita por Marca

Receita gerada por cada marca de bicicleta.

</head>
<body>
       <table>
              <tr>
                     <td><img src= "https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Excel/Imagens/Receita%20por%20Marcas.png"></td>            
              </tr>
       </table>
</body>
</html>   

**Insights**:
- Trek domina com 60% da receita.
- Marcas como Electra e Surly são fortes em segmentos específicos.

## Dashboard: Receita por Categoria

Distribuição de receita por categoria de produto.

</head>
<body>
       <table>
              <tr>
                     <td><img src= "https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Excel/Imagens/Receita%20por%20Categoria.png"></td>            
              </tr>
       </table>
</body>
</html>   

**Insights**:
- Mountain Bikes e Road Bikes representam cerca de 57% da receita total.
- Crescimento potencial em Electric Bikes, uma categoria emergente.

## Dashboard: Receita por Representante de Vendas

Desempenho dos representantes de vendas medido pela receita gerada.

</head>
<body>
       <table>
              <tr>
                     <td><img src= "https://github.com/lannacassio/Vendas-de-Bicicleta/blob/main/Arquivo%20Excel/Imagens/Receita%20por%20Representante.png"></td>            
              </tr>
       </table>
</body>
</html>   

**Insights**:
- Marcelene Boyer e Venita Daniel são os top performers, responsáveis por mais de 68% da receita.
- Oportunidades de treinamento para representantes com desempenho inferior.

## Conclusão

Este banco de dados fornece insights valiosos sobre o desempenho de vendas da BikeStores. Os dashboards destacam tendências anuais e mensais, contribuições por loja e estado, clientes chave, marcas e categorias populares, e o impacto dos representantes de vendas. Recomendações incluem expansão em mercados de alto desempenho (como NY) e foco em categorias crescentes (como Electric Bikes).

Contribuições e atualizações são bem-vindas!
