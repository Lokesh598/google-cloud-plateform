# Spring Cloud GCP
https://googlecloudplatform.github.io/spring-cloud-gcp/reference/html/index.html#introduction

#### Monolith Application:

A monolithic application is self contained and independent from other computing application.
A monolithic app has all or most of its functionality within a single process or container and it's componentized in internal layers or libraries.

##### Disadvantages:
Slower development speed – A large, monolithic application makes development more complex and slower.

Scalability – You can’t scale individual components.

Reliability – If there’s an error in any module, it could affect the entire application’s availability.

Barrier to technology adoption – Any changes in the framework or language affects the entire application, making changes often expensive and time-consuming.

Lack of flexibility – A monolith is constrained by the technologies already used in the monolith.

Deployment – A small change to a monolithic application requires the redeployment of the entire monolith.

#### Micoservice application:
A microservices architecture, also simply known as microservices, is an architectural method that relies on a series of independently deployable services. These services have their own business logic and database with a specific goal. Updating, testing, deployment, and scaling occur within each service. Microservices decouple major business, domain-specific concerns into separate, independent code bases. Microservices don’t reduce complexity, but they make any complexity visible and more manageable by separating tasks into smaller processes that function independently of each other and contribute to the overall whole. 

##### Advantage:
Agility – Promote agile ways of working with small teams that deploy frequently.

Flexible scaling – If a microservice reaches its load capacity, new instances of that service can rapidly be deployed to the accompanying cluster to help relieve pressure. We are now multi-tenanant and stateless with customers spread across multiple instances. Now we can support much larger instance sizes. 

Continuous deployment – We now have frequent and faster release cycles. Before we would push out updates once a week and now we can do so about two to three times a day. 

Highly maintainable and testable – Teams can experiment with new features and roll back if something doesn’t work. This makes it easier to update code and accelerates time-to-market for new features. Plus, it is easy to isolate and fix faults and bugs in individual services.

Independently deployable – Since microservices are individual units they allow for fast and easy independent deployment of individual features. 

Technology flexibility – Microservice architectures allow teams the freedom to select the tools they desire. 

High reliability – You can deploy changes for a specific service, without the threat of bringing down the entire application.

Happier teams – The Atlassian teams who work with microservices are a lot happier, since they are more autonomous and can build and deploy themselves without waiting weeks for a pull request to be approved.
