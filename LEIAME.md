# restaurant-system-saas

Projeto desenvolvido para um trabalho freelancer, com o objetivo de criar um sistema de gerenciamento para gestores de restaurantes.

## 🚀 Funcionalidades do Projeto

### Administradores

- Podem gerenciar os gestores
- Podem criar um pré-cadastro de um gestor, gerando assim apenas gestores que pagaram pelo sistema

### Gestores
Possuem todo o sistema de gerenciamento do seu restaurante, dentre as funcionalidades estão:

- Gerenciamento de países dos restaurantes que possui
- Gerenciamento de tipos culinários do restaurante
- Gerenciamento de sub-gerentes dos restaurantes
- Gerenciamento de competências dos sub-gerentes dos restaurantes
- Gerenciamento de um ou mais restaurantes que assim o desejar
- Gerenciamento de categorias de produtos do restaurante
- Gerenciamento de produtos do restaurante
- Gerenciamento de cardápios do restaurante
- Criação de link para o menu do restaurante

Observação: 
  Pensando na possibilidade de um gestor (dono do restaurante) ter um ou mais restaurantes, o sistema foi projetado para que cada restaurante tenha seu próprio cárdapio, bem como suas categorias de produtos e seus respectivos produtos atrelados a essas categorias. 
  Movivação? O motivo está em que dependendo do ambiente que está localizado o restaurante do nosso gestor, várias influências externas podem influenciar o valor do produto, seja um aluguel mais caro por está em um bairro mais caro, seja por motivos que os preços estão inflacionados, dentre outros.
  Logo se faz necessário que você que tem dois restaurantes por exemplo, tenha que definir um preço de uma Coca Cola, por exemplo, 2x no sistema, um para cada restaurante.
  
## 💌 Funcionalidades a serem implementadas (ideias)

- Cada sub-gerente poderá gerenciar o restaurante que está atrelado ao seu respectivo ID, fazendo com que o gestor apenas tenha uma visão geral do sistema.
- Cada restaurante poderá ter um sistema de pedidos atrelados ao cardápio, logo quando o cliente estiver vendo o cárdapio do restaurante, ele poderá solicitar um pedido para ser entregue a mesa X de acordo com o que foi solicitado
- O gerenciamento de gestores do restaurante ser feito via assinatura. (Em caso de não pagamento, sistema bloquear ações ou limitar as possibilidades do gestor)
- Com o sistema de pedidos desenvolvido, criar dados estatísticos para serem exibidos para os gestores e sub-gerentes

## 📋 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [NodeJS](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)
- [NestJS](https://docs.nestjs.com/)
- [Domain Driven Design](https://en.wikipedia.org/wiki/Domain-driven_design)
- [Clean Architecture](https://fullcycle.com.br/o-que-e-clean-architecture/)

Caso você queira ver como foi a estrutura de pastas, visite o repositório: https://github.com/Kemuel-Batista/ignite-nodejs-05-nest-ddd-clean

## 👨🏽‍💻 Códigos demonstrativos do projeto

#### Restaurants Code

##### create-restaurant.controller.ts - https://gist.github.com/Kemuel-Batista/408cd92f32c771cce30e034fe9b00690
##### create-restaurant-use-case.ts - https://gist.github.com/Kemuel-Batista/342a4e3078e2743f76df5040f096cab4
##### restaurants-repository.ts - https://gist.github.com/Kemuel-Batista/ae1802f0013d61a1814940a5abf255b4
##### prisma-restaurants-repository.ts - https://gist.github.com/Kemuel-Batista/3ec726b194070f1030391a2bde69cae7
##### prisma-restaurant-mapper.ts - https://gist.github.com/Kemuel-Batista/e49ae56efa7654f6d683a275da6e1e09
