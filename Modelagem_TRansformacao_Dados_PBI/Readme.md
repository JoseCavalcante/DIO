
<p>Para desenvolver este desafio, algumas etapas foram criadas:</p>

<ul>
  <li>Criação de um Star Schema a partir de uma tabela importada de uma planilha Excel.</li>
  A partir das colunas desta planilha foram obtidos dados para gerar as tabelas <b>Dimensão</b> e a tabela <b>Fato</b> que irão compor o projeto.<br>
  <ul>
    <li>D_Produtos (ID_produto, Produto, Média de Unidades Vendidas, Médias do valor de vendas, Mediana do valor de vendas, Valor máximo de Venda, Valor mínimo de Venda)</li>
    <li>D_Produtos_Detalhes(ID_produtos, Discount Band, Sale Price, Units Sold, Manufactoring Price</li>
    <li>D_Descontos (ID_produto, Discount, Discount Band)</li>
    <li>D_Calendário – Criada por DAX pela função Calendar()</li>
    <li>F_Vendas (SK_ID , ID_Produto, Produto, Units Sold, Sales Price, Discount Band, Segment, Country, Salers, Profit, Date (campos))</li>
    <li>D_Detalhes (Com informações que não foram contempladas nas demais tabelas dimensão)</li>
  </ul>
</ul>




