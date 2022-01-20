# Clean Architecture with CQRS
Example of best practices Clean Architecture with CQRS, Micros Service implementing an eCommerce:

## Tech Stack
- Front-end UI (Blazor)
- Back-end services (.NET 6)
- gRPC Code-First ([protobuf-net.Grpc](https://protobuf-net.github.io/protobuf-net.Grpc/))
- MiroService Orechestration (Kuberenetes' [Helm Chart](https://helm.sh/))
- [Infrastructure-as-Code](https://en.wikipedia.org/wiki/Infrastructure_as_code): [Terraform CDK](https://github.com/hashicorp/terraform-cdk/blob/main/docs/getting-started/csharp.md)
- Message Distribution Service (Apache Kafka)
- Authentication Service (Keycloak)

## Best practices
- Authentications
- Error Handling
- TDD
- BDD
- DDD
- Documentations

## Front-end Services
- Customer Onboarding, Login
- Product directory
- Shopping cart and order processing
- Customer Relationship Service (Chat, Ticket)
- Fullfilment Center
- Product administration

## Back-end Services
- Customer
- Product
- Order
- Payment
- Customer Relationship Service


