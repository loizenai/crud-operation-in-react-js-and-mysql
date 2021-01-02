# Crud Operation In React.js and Mysql

Tutorial : https://loizenai.com/react-node-js-crud-mysql/

[Crud Operation In React.js and Mysql](https://loizenai.com/react-node-js-crud-mysql/)

Tutorial: React Node.js MySQL CRUD Example – Step By Step React, Nodejs and Mysql simple full-stack Application

In the tutorial, I introduce how to build an “React.js Nodejs CRUD MySQL Example” project with the help of Ajax to POST/GET/PUT/DELETE requests with step by step coding examples:

– Nodejs project produces CRUD RestAPIs with MySQL database using the supporting of Sequelize ORM.
– React.js project will consume the Nodejs CRUD RestAPIs by Ajax then show up on Reactjs component’s views.

– I draw a fullstack overview Diagram Architecture from React.js Frontend to MySQL database through Nodejs RestAPI backend.
– Develop Nodejs CRUD RestAPIs with the supporting of Sequelize ORM.
– Implement Reactjs CRUD application with Ajax fetching APIs to do CRUD request (Post/Get/Put/Delete) to Nodejs Backend APIs.
– I create a testsuite with a number of integrative testcases with CRUD RestAPI requests from Reactjs to do CRUD requests to Nodejs RestAPIs Server and save/retrieve data to MySQL database.

React Node.js Mysql CRUD Example – Step By Step React, Nodejs and Mysql simple full-stack Application

## Overall Architecture System: Reactjs + Nodejs + MySQL – React Node.js MySQL CRUD Example - Crud Operation In React.js and Mysql

![React.js Nodejs MySQL Diagram Architecture](https://loizenai.com/wp-content/uploads/2020/11/React.js-Nodejs-MySQL-Diagram-Architecture.png)

- We build a backend: Nodejs CRUD Application with MySQL that provides RestAPIs for POST/GET/PUT/DELETE data entities and store them in MySQL database.
- We implement React.js CRUD Application that use Ajax to interact (call/receive requests) with Nodejs CRUD application and display corresponding data in Reactjs Component.

## Nodejs MySQL CRUD Design Application – React Node.js MySQL CRUD Example

![Nodejs-Build-CRUD-MySQL-Architecture-Overview](https://loizenai.com/wp-content/uploads/2020/11/Nodejs-Build-CRUD-MySQL-Architecture-Overview.png)

We have 4 main blocks for the application:

- For building RestAPIs in Nodejs application, we use Express framework.
- For interacting with database MySQL, we use Sequelize ORM.
- We define APIs URL in router.js file
- We implement how to process each API URL in controller.js file
- We use Bootstrap and JQuery Ajax to implement frontend client.

## Reactjs CRUD Application Design – React Node.js MySQL CRUD Example - Crud Operation In React.js and Mysql

![Reactjs CRUD RestAPI Application Frontend Architecture Diagram](https://loizenai.com/wp-content/uploads/2020/11/Reactjs-CRUD-RestAPI-Application-Frontend-Architecture-Diagram.png)

– Reactjs CRUD Application is designed with 2 main layers:

React.js components let you split the UI into independent, reusable pieces, and think about each piece in isolation.
Ajax is used by Reactjs component to fetch (post/put/get/delete) data from remote restapi by http request
Reactjs CRUD Application defines 5 components:

- Home.js is used serve as the landing page for your app.
- AppNavbar.js is used to establish a common UI feature between components.
- CustomerList.js is used to show all customers in the web-page
- CustomerEdit.js is used to modify the existed customer
- App.js uses React Router to navigate between components.

## Integrative Project Goal – React Node.js MySQL CRUD Example

Reactjs Home page:

![Reactjs Home page](https://loizenai.com/wp-content/uploads/2020/11/Project-Goal-Home-Page.png)

Reactjs List all data:

![Project Goal Customer List](https://loizenai.com/wp-content/uploads/2020/11/Project-Goal-Customer-List.png)

Reactjs add data:

![Reactjs add data](https://loizenai.com/wp-content/uploads/2020/11/Project-Goal-Reactjs-Add-a-Customer-through-Nodejs-RestAPI.png)

Reactjs update data:

![Reactjs update data](https://loizenai.com/wp-content/uploads/2020/11/Project-Goal-Reactjs-Update-Customer-through-Nodejs-RestAPI-to-MySQL-database.png)

Reactjs delete a customer with id=2, check the Customer List after deleting:

![Project Goal – Reactjs show List Customer after Delete successfully](https://loizenai.com/wp-content/uploads/2020/11/Project-Goal-Reactjs-show-List-Customer-after-Delete-successfully.png)

Check MySQL Database after do CRUD operations:

![Check MySQL records after do CRUD operation](https://loizenai.com/wp-content/uploads/2020/11/Check-MySQL-records-after-do-CRUD-operation.png)

## Tutorial Link - Crud Operation In React.js and Mysql

https://loizenai.com/react-node-js-crud-mysql/

## Youtube Video - Crud Operation In React.js and Mysql

https://www.youtube.com/watch?v=MjLjHEP74vE&t=28s

## Related post - Crud Operation In React.js and Mysql

- [Angular 10 Nodejs PostgreSQL CRUD Example](https://loizenai.com/angular-10-nodejs-postgresql-crud-example-using-express-restapis-sequelize-tutorial/)
- [SpringBoot + Angular 10 + PostgreSQL CRUD Example](https://loizenai.com/springboot-angular-10-postgresql-crud-restapi-example/)
- [Integrate Reactjs SpringBoot](https://loizenai.com/integrate-reactjs-springboot/)
- [SpringBoot React MySQL CRUD Example](https://loizenai.com/springboot-react-mysql-crud-example/)
- [Reactjs Nodejs PostgreSQL Example](https://loizenai.com/reactjs-nodejs-postgresql-example/)
- [SpringBoot Reactjs MongoDB CRUD](https://loizenai.com/reactjs-nodejs-postgresql-example/)
