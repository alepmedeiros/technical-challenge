# Solicitação para um nível Pleno

### Alguns passos que podem ser seguidos para criação do desafio nivel pleno

1. O operador deverá informar o cliente(não precisa desenvolver o cadastro), e os produtos(não precisa desenvolver o cadastro).
2. Campos da tabela de clientes(codigo, nome, cidade e uf).
3. Campos da tabela de produtos(codigo descricao, preco de venda).
4. As tabelas de clientes e produtos devem ser criadas no banco de dado e alimentadas com 20 registros ou mais, para teste. As tabelas será avalidas no teste(Pk, Fk, indices, etc).
5. Para informar o produto na tela do pedido de vendas, o operador deve digitar: código do produto, quantidade e valor unitario.
6. A medida que o operador digita os produtos e confirma, eles devem ir entrando em uma grid para visualização. Deve exitir um botão para inserir o produto no grid.
7. O grid deve aprensetar: código do produto, descrição do produto, quantidade, valor unitario e valor total.
8. Deve ser possivel navegar pelo grid com seta para cima e seta para baixo.
9. Estando navegando pelo grid, deve ser possivel acionar ENTER sobre um produto para alterá-lo. Poderá ser alterando quantidade e valor unitario. Utilizando o mesmo botão de inserir para confirmar e atualizar o grid com as alterações feitas pelo operador.
10. Estando navegando pelo grid, deve ser possivel acionar DEL sobre um produto para apaga-lo. Perguntar ao operador se realemten deseja apaga-lo.
11. Permitir produtos repetidos no grid.
12. Exibir no rodapé da tela o valor total do pedido.
14. Incluir botão GRAVAR PEDIDO. Quando acionado, o sistema deve gravar 2 tableas(dados gerais do pedido e produtos do pedido)
15. Campos da tabela de pedidos produtos(autoincremento, numero pedido, codigo produto, quantidade, valor unitario, valor total).
16. Utilizar transação e tratar possivels erros.
17. O pedido deve possuir número sequencial e crescente.
18. A chave primária da tabela de dados gerais do pedido deve ser (numero pedido), não podendo haver duplicidade entre os registros gravados.
19. A chave primária da tabela de produtos deve ser(autoincrem), pois pode existir repetição de produtos.
20. Criar FKs necessárias para ligar tabelas de produtos do pedido.
21. Criar indices necessário nas tabelas de dados gerais do pedido e produtos do pedido.
22. Criar botão na tela de pedidos, que deve ficar visuvel quando o código do cliente estiver em branco, para carregar pedidos já gravados. Solicitar(numero do pedido) e carregar o cliente e os produtos.
23. Criar botão na tela de pedidos, que deve ficar visivel quando o codigo do cliente estiver em branco, para cancelar um pedido. Solicitar(numero do pedido) e apagar as duas tabelas.
