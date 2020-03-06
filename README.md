## **GraphQL with Laravel**

#### **What is GraphQL**

GraphQL is open source data query language for APIs and a runtime for fulfilling those queries with your existing data.
GraphQL was developed internally by Facebook in 2012. GraphQL provides a complete and understandable description of the data in your API,
gives clients the power to ask for exactly what they need and nothing more, makes it easier to evolve APIs over time, and enables powerful developer tools.


#### **Why should we use GraphQL**

Apps using GraphQL are fast and stable because they control the data they get, not the server. 

Send a GraphQL query to your API and get exactly what you need, nothing more and nothing less.

GraphQL queries always return predictable results.

GraphQL queries access not just the properties of one resource but also smoothly follow references between them.

While typical REST APIs require loading from multiple URLs, GraphQL APIs get all the data your app needs in a single request.

Apps using GraphQL can be quick even on slow mobile network connections.

Access the full capabilities of your data from a single endpoint.

GraphQL uses types to ensure Apps only ask for what’s possible and provide clear and helpful errors.

Apps can use types to avoid writing manual parsing code.

GraphQL APIs give apps continuous access to new features and encourage cleaner, more maintainable server code.

Write GraphQL APIs that leverage your existing data and code with GrapWe are going to implement GraphQL to our laravel App. let's follow the below steps.hQL engines available in many languages.

You provide functions for each field in the type system, and GraphQL calls them with optimal concurrency.

#### **How to implement GraphQL**

Follow the steps for implement GraphQL in Laravel

**create one laravel project.**

    composer create-project --prefer-dist laravel/laravel graphql-with-laravel

To support GraphQL in the application, we need to install a library `rebing/graphql-laravel` that allows us to define schemas and queries in a simple way.

**Testing the API with GraphQL**

For the testing in graphql, we need to download graphql and install it to our system. you can download it from here https://www.electronjs.org/apps/graphiql
and run below command to terminal.

    php artisan serve
    
Lets run it on browser.

    http://127.0.0.1:8000/graphiql
    
And then you can see the below screen.

![picture](img/graphql.png) 

Let's write a queries.

Get User

![picture](img/user.png)


That's it. Happy Coding :)








