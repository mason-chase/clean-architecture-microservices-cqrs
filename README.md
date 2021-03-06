# Clean Architecture with CQRS
Example of best practices Clean Architecture with CQRS, Micros Service implementing an eCommerce:

## Tech Stack
- [ ] Front-end UI (Blazor)
- [ ] Back-end services (.NET 6)
- [ ] gRPC Code-First ([protobuf-net.Grpc](https://protobuf-net.github.io/protobuf-net.Grpc/))
- [ ] MiroService Orechestration (Kuberenetes' [Helm Chart](https://helm.sh/))
- [ ] [Infrastructure-as-Code](https://en.wikipedia.org/wiki/Infrastructure_as_code): [Terraform CDK](https://github.com/hashicorp/terraform-cdk/blob/main/docs/getting-started/csharp.md)
- [ ] Message Distribution Service ([Apache Kafka](https://kafka.apache.org/), [Producter](https://github.com/confluentinc/confluent-kafka-dotnet/) [Consumer](https://github.com/criteo/kafka-sharp))
- [ ] Authentication Service (Keycloak)
- [ ] [MariaDB Galera Cluster](https://mariadb.com/kb/en/what-is-mariadb-galera-cluster/)
- [ ] [Apache Cassandra](https://cassandra.apache.org/_/index.html)

## Technical Features
- [ ] Multi-Region Application Architecture
- [ ] Load balancing and High Availibity 
- [ ] Private premise deployment
- [ ] [Geocasting](https://en.wikipedia.org/wiki/Geocast)
- [ ] Azure's AKS
- [ ] AWS's Kuberenetes

## Data Replication and Consistency
- [ ] [CRDT (Conflict-free replication data type)](https://en.wikipedia.org/wiki/Conflict-free_replicated_data_type)
- [ ] [Semi-Synchronous Replication](https://dev.mysql.com/doc/refman/5.7/en/replication-semisync.html)

## Best practices
- [ ] [TDD](https://en.wikipedia.org/wiki/Test-driven_development), [BDD](https://en.wikipedia.org/wiki/Behavior-driven_development), [DDD](https://en.wikipedia.org/wiki/Domain-driven_design)
- [ ] [SOLID](https://en.wikipedia.org/wiki/SOLID) Principles: [S](https://en.wikipedia.org/wiki/Single-responsibility_principle) [O](https://en.wikipedia.org/wiki/Open%E2%80%93closed_principle) [L](https://en.wikipedia.org/wiki/Liskov_substitution_principle) [I](https://en.wikipedia.org/wiki/Interface_segregation_principle) [D](https://en.wikipedia.org/wiki/Dependency_inversion_principle)
- [ ] Dependency Injection (DI) [Autofac](https://autofac.org/)
- [ ] Clean Code Tools ([Sonar Analyzer](https://www.nuget.org/packages/SonarAnalyzer.CSharp/))
- [ ] Code Snippets ([C# code snippets](https://docs.microsoft.com/en-us/visualstudio/ide/visual-csharp-code-snippets?view=vs-2022))
- [ ] Localizaitons ([Unicode CLDR Project](https://cldr.unicode.org/))
- [ ] Authentication token with refresh token (JWT)
- [ ] Error Handling (Business Logic, Application Failure, Third Party Failure, Security and Unhandled)
- [ ] [API-first-code-first](https://swagger.io/resources/articles/adopting-an-api-first-approach/#:~:text=An%20API%2Dfirst%20approach%20means,be%20consumed%20by%20client%20applications.)
- [ ] Monitoring and [Health Checks](https://docs.microsoft.com/en-us/aspnet/core/host-and-deploy/health-checks?view=aspnetcore-6.0)
- [ ] [GitOps](https://www.gitops.tech/)
- [ ] Document-As-Code and [Self Documenting](https://en.wikipedia.org/wiki/Self-documenting_code) ([DocFx](https://dotnet.github.io/docfx/) [Graphwiz](http://www.graphviz.org/))
- [ ] API Documentation ([Slate](https://github.com/slatedocs/slate))
- [ ] Multi Threading (await/async)

## Documentation
- [ ] Developer onboarding
- [ ] Domain expert knowledge exchange
- [ ] Customer
- [ ] Customer Service Staff
- [ ] Product owner

## Front-end Services
- [ ] Customer Onboarding, Login
- [ ] Product directory
- [ ] Shopping cart and order processing
- [ ] Customer Relationship Service (Chat, Ticket)
- [ ] Fullfilment Center
- [ ] Product administration

## Front specific features
- [ ] [Deep linking](https://en.wikipedia.org/wiki/Mobile_deep_linking)

## Back-end Services
- [ ] Customer
- [ ] Product
- [ ] Order
- [ ] Payment
- [ ] Customer Relationship Service

## Data Access Frameworks (ORM)
- [ ] [Entity Framework Core](https://docs.microsoft.com/en-us/ef/core/what-is-new/ef-core-6.0/plan)
- [ ] Dapper
- [ ] [Lazy Migration](https://github.com/kennethklee/mongoose-rolling-migration)

## Caching and searching
- [ ] Redis
- [ ] Elastic Search

## Pipelines
- [ ] GitLab, GitHub, Azure, [Argo](https://argoproj.github.io/)
- [ ] Unit testings
- [ ] Integration testings
- [ ] End To End Testing ([Selenium](https://www.selenium.dev/), [XPath](https://en.wikipedia.org/wiki/XPath))

## Agile concepts
- [ ] Jira, Azure DevOps
- [ ] Epic, Feature, User Story, Boards
- [ ] Values: Business, Infrastructure

## Integration System
- [ ] Multiple Payment Integrations
- [ ] SMS Delivery System
- [ ] Email Delivery System

## C-sharp / .NET Tools
- [ ] Xunit
- [ ] [Bunit](https://github.com/bUnit-dev/bUnit)
- [ ] [Specflow](https://github.com/SpecFlowOSS/SpecFlow)
- [ ] [Bogus](https://github.com/bchavez/Bogus)
- [ ] [FluentValidation](https://fluentvalidation.net/)
- [ ] [BenchmarkDotNet](https://github.com/dotnet/BenchmarkDotNet)

## C-sharp specific enhancement
- [ ] [LanguageExt](https://github.com/louthy/language-ext)
- [ ] [SmartEnum](https://github.com/ardalis/SmartEnum)
