# Projeto: Uma Jornada pelos Dados da [Olist](https://olist.com/)

<img src="https://d3hw41hpah8tvx.cloudfront.net/images/ilustra_ecossitema_olist_desktop_ff64362482.svg" />

## A Análise

A compreensão do cenário do comércio eletrônico brasileiro é essencial para identificar tendências e oportunidades no mercado. Este projeto se concentra na análise do conjunto de dados da Olist, uma plataforma de comércio eletrônico que desempenha um papel crucial ao conectar pequenas empresas a canais de vendas online, facilitando a comercialização de produtos em diversos marketplaces no Brasil. Além disso, a Olist oferece serviços de logística e gerenciamento de pedidos para seus clientes.

## Objeto de Estudo

O foco da análise recai sobre um conjunto de dados abrangente, composto por informações de 100 mil pedidos realizados na loja Olist no período de 2016 a 2018. Esses pedidos foram efetuados em vários marketplaces brasileiros, proporcionando uma visão detalhada das transações comerciais. A análise contempla diversas dimensões, incluindo: Características das Vendas e Receitas, Horários das Vendas, Avaliações dos Clientes, Logística e Entrega.

Essa abordagem multifacetada visa não apenas avaliar o desempenho da plataforma, mas também fornecer insights profundos sobre o funcionamento da Olist. A análise dos dados reais e anonimizados contribui para a compreensão das dinâmicas do mercado, facilitando a identificação de oportunidades de aprimoramento e tomada de decisões estratégicas no setor.

## Os Dados

Os dados apresentados nesta análise foram retirados diretamente do Kaggle E podem ser obtidos diretamente [neste link](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce).

## Obs: Este projeto faz uso extensivo do Plotly! Embora o GitHub consiga renderizar notebooks Jupyter, é importante notar que os gráficos interativos do Plotly podem não ser totalmente funcionais na visualização direta desta plataforma. Para uma experiência de visualização aprimorada, recomendo replicar o notebook localmente ou explorar o projeto por meio do arquivo HTML disponibilizado, garantindo assim uma visualização mais completa e interativa clique [aqui](https://nbviewer.org/github/GSanner/Projeto_Olist/blob/master/Uma%20Jornada%20pelos%20Dados%20da%20Olist%20-%20interetivo.html).

## Tópicos
- Impotando Bibliotecas
- Importando os dados
- "Cheirando" os Dados
- Renomeando Colunas
- Juntando os DataFrames
- Identificando valores nulos
- Estatística Descritiva
- Distribuídas as avaliações (notas)
- Análise de Pareto
- Clientes que mais gastam
- Principais cidades por número de pedidos por estado
- Cidades com maior geração de receita
- Pareto das Cidades
- Variação ao longo do tempo
- Avaliação dos Produtos
- O método de pagamento afeta o status do pedido?
- Há alguma relação entre o tempo de entrega e as pontuações das avaliações?
- Quais são as cidades dos vendedores com menor/maior tempo de entrega
- Estados com maior/menor tempo de entrega
- Como o tempo médio de entrega varia ao longo do tempo?
- Como a pontuação média das avaliações varia ao longo do tempo
- Categorias de produtos mais vendidas
- Mapa coroplético com o tempo de entrega em dias por cada unidade federativa
- Considerações sobre a Análise
- Referências

-----------------

### Conclusões

A análise abrangente dos dados da Olist proporcionou insights valiosos. Destacam-se a importância de cultivar relacionamentos com os principais clientes, a concentração de atividade econômica em algumas cidades estratégicas e a necessidade de gerenciar eficazmente as expectativas do cliente, especialmente em categorias de produtos complexas. Além do cuidado em diversificar as fontes de receita, evitando uma concentração.

A análise logística revelou uma relação direta entre o tempo de entrega e a satisfação do cliente, indicando a necessidade de melhorias na infraestrutura logística e adaptação às demandas regionais. A visualização geoespacial ofereceu uma perspectiva valiosa para ajustar estratégias com base nas condições específicas de cada região.

A evolução positiva ao longo do tempo no tempo de entrega e nas pontuações médias de avaliação reflete a eficácia das iniciativas implementadas. Em resumo, a análise fornece orientações cruciais para estratégias futuras, visando otimização, aprimoramento da experiência do cliente e crescimento sustentável no mercado de comércio eletrônico.

------------------

## Requisitos e Replicações:

Neste projeto, foi utilizada a versão 3.9.13 do Python

A versão do pip utilizada é a 22.2.2

A versão do git utilizada é a 2.41.0

Demais requisitos se encontram no arquivo requirements.txt

<details>
  <summary>Para utilizar este projeto, siga as instruções abaixo:</summary>

  <details>
    <summary>Passo 1: Clonar o repositório</summary>

    git clone https://github.com/GSanner/Desafio_Indicium_Lighthouse.git

  </details>

  <details>
    <summary>Passo 2: Instalar os pacotes nas versões utilizadas</summary>

    pip install -r requirements.txt
    
  </details>

</details>
