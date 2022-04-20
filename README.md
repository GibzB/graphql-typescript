# Graphql-Typescript
First attempt in coding using Typescript &amp; GraphQL

## GraphQL
GraphQL is another method for managing APIs. It's an alternative to Rest APIs that allows you to request "only the data you need". This helps reduce the amount of data that needs to be sent to the client from the server.
## TypeScript
TypeScript is a superset of JavaScript that compiles to JavaScript for production. It's like JavaScript, but with powers – type powers.
TypeScript helps you build typed applications that help you avoid static type errors in those apps and make predictable code.
TypeScript helps us build more predictable JavaScript code during development through type-checking

### TypeGraphQL
The goal of TypeGraphQL is to make it seamless to enjoy static typing in your resolvers and create your schemas from one place.
#### Resolver decorator
 Decorates the class as an object with many query and mutation resolve methods. The beauty here is we're defining the queries and mutations and the resolve methods in the same class.

#### Query decorator
Tells GraphQL that this is a query and the respective resolve method

#### Mutation decorator
Tells GraphQL that this is a mutation and the respective resolve method

#### Arg decorator
Tells GraphQL that this argument is a GraphQL argument for the resolver.

## Test App
Here i run the GraphiQL playgroud on my local env on http://localhost:8000/graphql with the query 

[{
  getUsers{
    id
    name
    email
  }
}]

Output is as below:

