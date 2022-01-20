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
- [MariaDB Galera Cluster](https://mariadb.com/kb/en/what-is-mariadb-galera-cluster/)
- [Apache Cassandra](https://cassandra.apache.org/_/index.html)

## Technical Features
- Multi-Region Application Architecture
- Load balancing and High Availibity 
- Private premise deployment
- [Geocasting](https://en.wikipedia.org/wiki/Geocast)
- Azure's AKS
- AWS's Kuberenetes

## Best practices
- TDD, BDD, DDD
- SOLID Principles
- Clean Code Tools ([Sonar Analyzer](https://www.nuget.org/packages/SonarAnalyzer.CSharp/)
- Code Snippets ([C# code snippets](https://docs.microsoft.com/en-us/visualstudio/ide/visual-csharp-code-snippets?view=vs-2022))
- Localizaitons
- Authentication Token
- Error Handling
- [API-first-code-first](https://swagger.io/resources/articles/adopting-an-api-first-approach/#:~:text=An%20API%2Dfirst%20approach%20means,be%20consumed%20by%20client%20applications.)
- Monitoring and [Health Checks](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/health-checks?view=aspnetcore-6.0)
- (GitOps)[https://www.gitops.tech/]
- Document-As-Code and [Self Documenting](https://en.wikipedia.org/wiki/Self-documenting_code) ([DocFx](https://dotnet.github.io/docfx/) [Graphwiz](http://www.graphviz.org/))
- API Documentation ([Slate](https://github.com/slatedocs/slate))

## Documentation
- Developer onboarding
- Domain expert knowledge exchange
- Customer
- Customer Service Staff
- Product owner

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

## Pipelines
- GitLab, GitHub, Azure
- Unit testings
- Integration testings
- End To End Testing

## Agile coneps
- Jira, Azure DevOps
- Epic, Feature, User Story, Boards
- Values: Business, Infrastructure

## Integration System
- Multiple Payment Integrations
- SMS Delivery System
- Email Delivery System

## C-sharp / .NET Tools
- Xunit
- [Bunit](https://github.com/bUnit-dev/bUnit)
- [Specflow](https://github.com/SpecFlowOSS/SpecFlow)
- [Bogus](https://github.com/bchavez/Bogus)
- [FluentValidation](https://fluentvalidation.net/)

## C-sharp specific enhancement
- [LanguageExt](https://github.com/louthy/language-ext)
- [SmartEnum](https://github.com/ardalis/SmartEnum)
