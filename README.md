# Desafio 5 DevSuperior - API de Ecommerce (DSCommerce)
Quinto desafio do curso Java Spring Professional do Professor Nélio Alves - Dev Superior.

## Descrição do desafio:
O projeto DSCommerce é um sistema de comércio com as seguintes funcionalidades:
- **Consulta de catálogo**: Esta funcionalidade permitirá listar produtos, inclusive filtrando
os mesmos. Esta funcionalidade servirá para o usuário encontrar produtos para colocar
em seu carrinho de compras.
- **Login**: por meio da qual o usuário informa suas credenciais e obtem um token de acesso
às funcionalidades protegidas do sistema, conforme seus perfis de acesso.
- **Manter produtos**: as quatro operações básicas de criar, recuperar, atualizar
e deletar produtos, também conhecida como CRUD (Create, Retrieve, Update, Delete).
Esta funcionalidade servirá para a área administrativa do sistema.
- **Registrar pedido**: Esta funcionalidade é responsável por registrar um pedido do cliente
no sistema, a partir das informações do carrinho de compras.

Você deverá entregar o projeto DSCommerce estruturado e com todas funcionalidades implementadas.

O projeto deve ser implementado com Java e Spring Boot, usando banco de dados H2, conforme as aulas.

## Critérios de avaliação:
- [x] Mínimo 12 commits no projeto no usuário do aluno;
- [x] Endpoints públicos GET /produts e GET /products/{id} funcionam sem necessidade de login;
- [x] Endpoint de login funcionando e retornando o token de acesso;
- [x] Endpoints privados de produto (POST/PUT/DELETE) funcionam somente para usuário ADMIN;
- [x] Endpoint GET /users/me retorna usuário logado;
- [x] Endpoints GET /orders/{id} e POST /orders funcionando;
- [x] Usuário que não é ADMIN não consegue acessar pedido que não é dele em GET /orders/{id};
- [x] Endpoint GET /categories deve ser público e retornar todas categorias.

## Competências avaliadas:
- Estruturação de projeto Spring Boot de API Rest;
- Implementação de Authorization Server com password grant em projeto Spring Boot;
- Implementação de Resource Server em projeto Spring Boot;
- Controle de acesso por perfil de usuário em nível de rota;
- Controle de acesso em nível de regra de negócio;
- Realização de casos de uso.

## Desafios anteriores:
1. https://github.com/paulorc-silva/Desafio-DevSuperior-Componentes-DI
2. https://github.com/paulorc-silva/Desafio-DevSuperior-Dominio-ORM
3. https://github.com/paulorc-silva/Desafio-DevSuperior-CRUD
4. https://github.com/paulorc-silva/Desafio-DevSuperior-JPA-SQL-JPQL