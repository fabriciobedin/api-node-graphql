# api-node-graphql
first time using graphql to create a simple api

> open http://localhost:4000

```
query {
  users {
    id
    name
    email
  }
}
```

```
mutations {
  createUser (name: "Fabricio Bedin", email: "fabricioobedin@gmail.com") {
    id
    name
    email    
  }
}
```

```
query {
  user (id : 1) {
    name
    email
  }
}
```
