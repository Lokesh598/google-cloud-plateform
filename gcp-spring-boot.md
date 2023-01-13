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

#### spring cloud gcp work flow

Spring Cloud GCP is a set of libraries that allow developers to easily build and run Spring-based applications on Google Cloud Platform (GCP). It provides a set of connectors for various GCP services, such as Cloud Storage, Cloud SQL, and Cloud Pub/Sub, as well as support for authentication and authorization with Cloud Identity and Access Management (IAM).

A typical workflow for building and deploying a Spring Cloud GCP application would involve the following steps:

1. Setting up a GCP project: Before you can start using Spring Cloud GCP, you will need to create a new GCP project and enable the necessary APIs.

2. Configuring your application: Once your GCP project is set up, you'll need to configure your Spring application to use Spring Cloud GCP. This includes adding the necessary dependencies to your project and configuring the GCP credentials.

3. Building and deploying your application: After your application is configured, you can build and deploy it to a GCP environment, such as App Engine or Kubernetes Engine.

4. Using GCP services: Once your application is running, you can use the Spring Cloud GCP connectors to easily integrate with various GCP services, such as Cloud Storage, Cloud SQL, and Cloud Pub/Sub.
5. Monitoring and troubleshooting: Finally, you can use GCP tools, such as Stackdriver, to monitor and troubleshoot your application as it runs on GCP.

6. Scaling: when the traffic increases and your application needs more resources you can use the GCP services to scale up your application to handle the increased traffic.

Overall, Spring Cloud GCP provides a simple and convenient way to build and run Spring-based applications on GCP, and allows developers to take advantage of the full range of GCP services and tools while working within the familiar Spring framework.
