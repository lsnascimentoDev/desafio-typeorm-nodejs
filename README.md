<!DOCTYPE html>
<html lang="en">

<head>

</head>

<body>


  <h2>#Execute o projeto</h2>


  <h3>1. Clone este repositório</h3>
  <p>git clone: https://github.com/lsnascimentoDev/desafio-typeorm-nodejs.git</p>

  <h3>2. Acesse a pasta do projeto no seu terminal/cmd</h3>
  <p>cd /desafio-typeorm-nodejs/desafio-typerm-nodejs</p>

  <h3>3. Instale as dependências</h3>
  <p>yarn install</p>

  <h3>4. Execute a aplicação</h3>
  <p>yarn dev:server</p>
  
  </br> 
  
  
  <h2>#Desafio</h2>

<p>Aplicação que permite a criação de clientes, produtos e pedidos, onde o cliente pode gerar novos pedidos de
  compra de certos produtos, como um pequeno e-commerce.</p>
  
 </br> 
  
  <h2>#Tecnologias</h2>

<p>Express junto ao Node.js e TypeScript, incluindo o uso de banco de dados com o TypeORM.</p>

</br> 

<h2>#Funcionalidades</h2>

<p>1. Permite que um cliente seja criado, e retorne um json com o registro.</p>
<p> 2. No cadastro do cliente, validação e retorno de erro, caso o e-mail já esteja cadastrado no banco de dados.
<p>  3. Permite que um produto seja criado, e retorne um json com o registro.</p>
<p>  4. No cadastro de produto, validação e retorno de erro, caso o nome do produto já esteja cadastrado no banco de dados.
<p>  5. Permite que um pedido seja criado, e retorne um json com todos os dados do pedido.</p>
<p> 6. Validação na criação de um novo pedido com um cliente que não existe no banco de dados, retornando um erro.</p>
<p>  7. Validação na criação de um novo pedido com produtos que não existem no banco de dados, retornando um erro caso um
  ou mais dos produtos enviados não exista no banco de dados.</p>
<p>  8. Validação na criação de um novo pedido com produtos que não possuem quantidade disponível, retornando um erro caso
  um ou mais dos produtos enviados não possua a quantidade necessária.</p>
<p>  9. Quando um novo pedido for criado, é alterada a quantidade total dos produtos baseado na quantidade pedida.</p>
<p> 10. Ao cadastrar um novo pedido, o pedido é retornado via json, contendo todas as informações do pedido com os
  relacionamentos.</p>





</body>

</html>

