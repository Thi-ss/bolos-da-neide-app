Este repositório é dedicado ao desenvolvimento do sistema de gestão administrativa da cliente Dona Neide, projetado para organizar e estruturar os processos internos do seu negócio.

O objetivo do sistema é centralizar o fluxo operacional e financeiro, automatizando o controle de contas a pagar e receber, o cálculo de impostos e margens de lucro, além de oferecer módulos para geração de relatórios consolidados e gerenciamento de permissões de acesso por nível de usuário.


Para cada cliente, releia as anotações da sua entrevista (Atividade 02) e identifique:

Entidades: Quais são as "coisas" que precisam ser salvas? (Ex: Cliente, Produto, Consulta).
-> O cliente, o produto e os pedidos devem ser salvos.

Atributos: Quais dados cada entidade tem? (Ex: Nome, CPF, Preço, Cor).
Cliente -> id, nome, cpf, email e telefone
Pedidos -> id_pedido, id_cliente e id_produto
Produto -> id, nome e preco

Relacionamentos: Como elas se conectam? (Ex: 1 Paciente agenda N Consultas).
-> 1 Cliente faz N Pedido e Pedido contém 1 Produto.

![Diagrama DER](./der-neide/der%20-%20neide.drawio.png)