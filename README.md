# restaurant-system-saas

Project developed for freelance work, with the aim of creating a management system for restaurant managers.

## 🚀 Project Features

### Administrators

- Can manage managers
- You can create a pre-registration for a manager, thus generating only managers who have paid for the system

### Managers
They have the entire management system for your restaurant, among the features are:

- Country management of the restaurants you own
- Management of restaurant culinary types
- Management of restaurant sub-managers
- Skills management of restaurant sub-managers
- Management of one or more restaurants as desired
- Management of restaurant product categories
- Restaurant product management
- Restaurant menu management
- Creating a link to the restaurant menu

Observation:
  Thinking about the possibility of a manager (restaurant owner) having one or more restaurants, the system was designed so that each restaurant has its own menu, as well as its product categories and their respective products linked to these categories.
  Movement? The reason is that depending on the environment in which our manager's restaurant is located, several external influences can influence the value of the product, be it a more expensive rent because it is in a more expensive neighborhood, or for reasons that prices are inflated, among others.
  Therefore, if you have two restaurants, for example, you have to define a price for a Coca Cola, for example, 2x in the system, one for each restaurant.
  
## 💌 Features to be implemented (ideas)

- Each sub-manager will be able to manage the restaurant that is linked to their respective ID, meaning that the manager only has an overview of the system.
- Each restaurant may have an ordering system linked to the menu, so when the customer is viewing the restaurant's menu, they can request an order to be delivered to table X according to what was requested
- Management of restaurant managers is done via subscription. (In case of non-payment, the system blocks actions or limits the manager's possibilities)
- With the order system developed, create statistical data to be displayed to managers and sub-managers

## 📋 Technologies

This project was developed with the following technologies:

- [NodeJS](https://nodejs.org/en/)
- [TypeScript](https://www.typescriptlang.org/)
- [Prisma](https://www.prisma.io/)
- [NestJS](https://docs.nestjs.com/)
- [Domain Driven Design](https://en.wikipedia.org/wiki/Domain-driven_design)
- [Clean Architecture](https://fullcycle.com.br/o-que-e-clean-architecture/)

If you want to see what the folder structure was like, visit the repository: https://github.com/Kemuel-Batista/ignite-nodejs-05-nest-ddd-clean

## 👨🏽‍💻 Project demonstration codes

#### Restaurants Code

##### create-restaurant.controller.ts - https://gist.github.com/Kemuel-Batista/408cd92f32c771cce30e034fe9b00690
##### create-restaurant-use-case.ts - https://gist.github.com/Kemuel-Batista/342a4e3078e2743f76df5040f096cab4
##### restaurants-repository.ts - https://gist.github.com/Kemuel-Batista/ae1802f0013d61a1814940a5abf255b4
##### prisma-restaurants-repository.ts - https://gist.github.com/Kemuel-Batista/3ec726b194070f1030391a2bde69cae7
##### prisma-restaurant-mapper.ts - https://gist.github.com/Kemuel-Batista/e49ae56efa7654f6d683a275da6e1e09
##### restaurant-entity.ts - https://gist.github.com/Kemuel-Batista/74e693d4dff8ec5ac4dce3d12ea46760
##### aggregate-root.ts - https://gist.github.com/Kemuel-Batista/cb4110bf3d6c750051760f69b5c71025
