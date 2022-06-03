# Microservice Architecture

## Context
Architecture to follow while developing the software and orchestration tool to deploy backend server


## Decision
Microservices architecture should be followed while developing the solution.

For the following reasons, microservices architecture was chosen over monolithic architecture:

- Microservice architecture makes software more modular unlike monolithic architecture style
- We have multiple services running and requires each one to talk to others. Managing them becomes easy with kubernetes that follows microservice architecture.
- Leveraging write-once-run-anywhere benefit is possible using kubernetes that uses containerization
- Kubernetes is an accepted industry standard

## Pros and Cons

### Pros
- Decouples services
- Easy maintenance of software

### Cons
- Requires maintenance of additional configuration files to manage services
- As services grow, it becomes difficult to manage service definitions
