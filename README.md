## **Análise de Dados em Rede de Lojas de Venda de Açaí**

Neste projeto, exploraremos uma base de dados com 70.000 registros de uma rede de lojas de açaí. Vamos investigar padrões, tendências e insights relevantes para o negócio. 
<br>
<br>

## **Objetivo**
A métrica KPI (Indicador-Chave de Desempenho) será usada para avaliar o desempenho das lojas. Vamos considerar as seguintes métricas:
<br>

- Indicador 1 - Quantidade de Vendas por Loja
- Indicador 2 - Quantidade de Vendas por Cidade
- Indicador 3 - Faturamento por Cidade
- Indicador 4 - Faturamento de Cidade por Forma de Pagamento
- Indicador 5 - Faturamento por Estado
- Indicador 6 - Faturamento de Estado por Forma de Pagamento
- Indicador 7 - Faturamento de Vendas por Local de Consumo
- Indicador 8 - Faturamento - Evolução das lojas ao longo do tempo

<br>

## **Descrição do Projeto:**

- Utilizar a biblioteca Pandas
- Carregar os dados de um arquivo Excel
- Fazer análise exploratória nos dados
- Gerar Estatísticas das colunas quantitativas
- Gerar gráficos interativos
<br>
<br>

Sobre o Projeto: Este Projeto foi Desenvolvido Sob Mentoria da [EmpowerData.](https://www.empowerdata.com.br/)

---

## **Análise de Indicadores de Desempenho - KPI's**

####  **Indicador 1 - Quantidade de Vendas Por Loja.**
  
Nesta análise, examinamos a quantidade de vendas em várias lojas, com o objetivo de entender qual loja teve a maior e a menor quantidade de vendas.
<br>

![Grafico-1_Quantidade_vendas_loja](https://github.com/FernandaPavan/Business-Analytics-Vendas-Varejo/assets/110939025/4d8c2281-c6a9-418e-9cfe-7a82730e3280)
No gráfico-1, Principais Resultados: 

* A Loja 4 - lidera em vendas, com 13.483.
* A Loja 6 - vem logo atrás, com 13.075.
* As Lojas 1 e 5 - também registram bons resultados, com vendas próximos a 12.000.
* A Loja 2 - apresenta a menor quantidade de vendas entre as lojas analisadas, com 8.318.
  
 <br>
 <br>

####  **Indicador 2- Quantidade de Vendas Por cidade.**
  
  A quantidade de vendas se concentra no volume de unidades vendidas. Essa métrica foca exclusivamente na contagem de transações, sem considerar o valor monetário envolvido.

 ![Grafico-2_Quantidade_vendas_cidade](https://github.com/FernandaPavan/Business-Analytics-Vendas-Varejo/assets/110939025/e20550cf-7b8b-4641-93e2-c57f8916dd37)
No gráfico-2, Principais Resultados:

- A cidade de Santos lidera em quantidade de vendas, totalizando 13.483. 
- Logo em seguida, Florianópolis, Fortaleza e São Paulo também se destacam, registrando vendas acima de 12.000.
- Por fim, o Rio de Janeiro registra um total de 10.603 vendas, enquanto Niterói apresenta um volume menor, com um total de 8.318 vendas.

<br>
<br>

####  **Indicador 3 - Faturamento por Cidade**
  
  O faturamento de vendas considera o valor monetário total das vendas.
  
![Grafico-3_Faturamento_cidade](https://github.com/FernandaPavan/Business-Analytics-Vendas-Varejo/assets/110939025/f112ba38-f244-4b62-9352-fd9856a5277b)
No gráfico-3, Principais Resultados:

- O que podemos analisar é que as cidades de Santos, Florianópolis, Fortaleza e São Paulo obtiveram um faturamento acima de 100 mil.
- Rio de Janeiro registrou 88 mil, enquanto Niterói teve o menor faturamento, com 69 mil.

<br>
<br>

####  **Indicador 4 - Faturamento de Cidade por Forma de Pagamento**
  
![Grafico-4_Faturamento_cidade_forma_pagamento](https://github.com/FernandaPavan/Business-Analytics-Vendas-Varejo/assets/110939025/3b35c2b0-493c-4bfb-b646-0419adae6b1b)
No gráfico-4, Principais Resultados:

Observamos que as cidades de Santos, Florianópolis, Fortaleza, São Paulo e Rio de Janeiro vendem mais no crédito e débito - Vendas em dinheiro são o dobro das realizadas via Pix. A loja de Niterói vende menos no pix. 

Sugestões:

- Seria interessante obter dados como: Se há campanhas para parcelamento no cartão.
- Se há divulgação do pagamento via Pix - ou se o publico alvo tem acesso a este recurso ou não.
- Por exemplo, a idade é um fator interessante pois há pessoas que não sabem utilizar tecnologias. 

<br>
<br>

####  **Indicador 5 - Faturamento por Estado**
  
![Grafico-5_Faturamento_estado](https://github.com/FernandaPavan/Business-Analytics-Vendas-Varejo/assets/110939025/e763edf4-841c-4cef-a6ce-948a1df43340)
No gráfico-5, Principais Resultados:

- O estado de São Paulo possui duas lojas físicas e obteve um bom faturamento, atingindo 214.568 mil. 
- O estado do Ceará e Santa Catarina possui apenas uma loja fisica cada e ambas tiveram um bom desempenho no faturamento atingindo acima de 100mil. 
- O estado do Rio de Janeiro possui duas lojas físicas e não obteve um bom desempenho em uma delas, Niterói, impactando no faturamento em 157.949 mil - resultando em uma diferença de 56.619 para São Paulo.

<br>
<br>

#### **Indicador 6 - Faturamento de Estado por Forma de Pagamento**
![Grafico-6_Faturamento_estado_forma_pagamento](https://github.com/FernandaPavan/Business-Analytics-Vendas-Varejo/assets/110939025/234ad7b8-d98f-45d5-8112-23612e52915a)
No gráfico-6, Principais Resultados:

- O estado do Ceará e Santa Catarina seguem bem distribuidos na forma de pagamento. 
- São Paulo, liderando em crédito e débito.
- Rio de Janeiro, apresenta uma queda significativa em crédito, débito e dinheiro.

<br>
<br>

 ####  **Indicador 7 - Faturamento de Vendas por Local de Consumo**
![Grafico-7_Faturamento_vendas_local_consumo](https://github.com/FernandaPavan/Business-Analytics-Vendas-Varejo/assets/110939025/9c84d771-55d3-41b0-bf52-c605631a86cc)
  No gráfico-7, Principais Resultados:

- Há uma distribuição equilibrada em ambas as categorias. Tanto consumo no local quanto delivery seguem bem distribuídos quanto à forma de pagamento.

<br>
<br>


#### **Gráfico 8 - Faturamento Evolução das lojas ao longo do tempo**
![Grafico-8_Interativo_longo_tempo](https://github.com/FernandaPavan/Business-Analytics-Vendas-Varejo/assets/110939025/01aa47f0-29bb-4fdd-a1a6-05f6ad302c9d)
No gráfico-8, Principais Resultados:

- As lojas 1, 4, 5 e 6 atingiram o Faturamento acima de 100mil.
- Em seguida, a loja 3 com Faturamento acima de 80 mil.
- A loja 1, com 69mil.
