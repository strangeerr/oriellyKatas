# REST

## Context
We need a way to communicate between API server and the client. We could use REST, GraphQL or gRPC

## Decision
REST should be used for API server because of the following reasons:
- It is suitable for web applications due to good browser support
- Ideal for our scenario since we mostly perform CRUD operations

## Pros and Cons

### Pros
- Easier to onboard new developers as REST is the oldest and most popular architectural design

### Cons
- Might be less efficient and can be blocker while improving efficiency for scalability
