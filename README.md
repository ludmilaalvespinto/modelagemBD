# Estudos de modelagem de Banco de Dados

  <p>
    Com o objetivo de treinar a modelagem do banco de dados, deixarei os meus estudos nesse repositório.
  </p>
  <br>

 <h1>
   Desafio DIO E-commerce     
 </h1>
 <p>
   O escopo principal corresponde a venda de produtos.
</p>
<br>
<p>
  Narrativa: Os produtos são vendidos por uma única plataforma online, cada produto possui um fornecedor, um ou mais produtos podem compor um pedido. 
</p>
<p>
  Um cliente pode se cadastrar no site com seu CPF ou CNPJ, o endereço do cliente irá determinar o valor do frete. Um cliente pode comprar mais de um pedido, este tem um período de carência para devolução do produto.
</p>
<p>
 Os pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega. O pedido pode ser cancelado. 
</p>
<p> 
O desafio foi modelado no programa MySQL Workbech.
</p>

<div align="center">
  <img src="https://github.com/ludmilaalvespinto/modelagemBD/assets/102269120/46b9db77-5c0f-48d1-bf76-521b2cff6e3b">
</div>

<br>
<h1>
  Desafio DIO 02 - Oficina
</h1>
<p>
  Modelar um sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica. Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões periódicas.
</p>
<p>
  Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
</p>
<p>
  A partir da OS, alcula-se o valor do serviço, consultando-se uma tabela de referencia de mão-de-obra. O valor de cada peça também irá compor a OS, o cliente autoriza a execução dos serviços, a mesma equipe avalia e executa os serciços.
</p>
<p>
  Os mecânicos possuem código, nome, endereço e especialidade. Cada OS possui numero, data de emissão, um valor, staus, e uma data para conclusão dos trabalhos.
</p>
<p>
  Uma OS pode ser composta por vários serviços e um mesmo serviço pode estar contido em mais de uma OS.Uma OS pode ter vários tipos de peça e uma peça pode estar presente em mais de uma OS.
</p>
