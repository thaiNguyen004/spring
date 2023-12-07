# Contents of 
(Spring - Spring boot more than 300 pages)
## Chaper 01- Getting started with Spring
### 1.1 What is Spring?	
### 1.2 Initializing a Spring application
#### 1.2.1 Initializing a Spring project with Spring Tool Suite
#### 1.2.2 Examining the Spring project structure
#### 1.3 Writing a Spring application	
#### 1.3.1 Handling web requests	
#### 1.3.2 Defining the view	
#### 1.3.3 Testing the controller
#### 1.3.4 Building and running the application	
#### 1.3.5 Getting to know Spring Boot DevTools	
#### 1.3.6 Let’s review	
### 1.4 Surveying the Spring landscape	
#### 1.4.1 The core Spring Framework	
#### 1.4.2 Spring Boot	
#### 1.4.3 Spring Data	
#### 1.4.4 Spring Security	
#### 1.4.5 Spring Integration and Spring Batch
#### 1.4.6 Spring Cloud	
#### 1.4.7 Spring Native	
## Chapter 02 - Developing web Applications
### 2.1 Displaying information	
#### 2.1.1 Establishing the domain	
#### 2.1.2 Creating a controller class	
#### 2.1.3 Designing the view	
### 2.2 Processing form submission	
### 2.3 Validating form input	
#### 2.3.1 Declaring validation rules	
#### 2.3.2 Performing validation at form binding	
#### 2.3.3 Displaying validation errors	
### 2.4 Working with view controllers	
### 2.5 Choosing a view template library	
#### 2.5.1 Caching templates	
## Chapter 03 -Working with data	
### 3.3 Persisting data with Spring Data JPA	
#### 3.3.1 Adding Spring Data JPA to the project	
#### 3.3.2 Annotating the domain as entities	
#### 3.3.3 Declaring JPA repositories	
#### 3.3.4 Customizing repositories	
## Chapter 04 - Working with nonrelational data	
### 4.1 Working with Cassandra repositories	
#### 4.1.1 Enabling Spring Data Cassandra	
#### 4.1.2 Understanding Cassandra data modeling	
#### 4.1.3 Mapping domain types for Cassandra persistence	
#### 4.1.4 Writing Cassandra repositories	
## Chapter05 - Securing Spring	
### 5.1 Enabling Spring Security	
### 5.2 Configuring authentication	
#### 5.2.1 In-memory user details service	
#### 5.2.2 Customizing user authentication	
### 5.3 Securing web requests	
#### 5.3.1 Securing requests	
#### 5.3.2 Creating a custom login page	
#### 5.3.3 Enabling third-party authentication	
#### 5.3.4 Preventing cross-site request forgery	
### 5.4 Applying method-level security	
### 5.5 Knowing your user	
## Chapter 06 - Working with configuration properties	
### 6.1 Fine-tuning autoconfiguration	
#### 6.1.1 Understanding Spring’s environment abstraction	
#### 6.1.2 Configuring a data source	
#### 6.1.3 Configuring the embedded server	
#### 6.1.4 Configuring logging	
### 6.2 Creating your own configuration properties	
#### 6.2.1 Defining configuration property holders	
#### 6.2.2 Declaring configuration property metadata	
### 6.3 Configuring with profiles	
#### 6.3.1 Defining profile-specific properties	
#### 6.3.2 Activating profiles	
#### 6.3.3 Conditionally creating beans with profiles	
## Chapter 07-Creating REST services	
### 7.1 Writing RESTful controllers	
#### 7.1.1 Retrieving data from the server	
#### 7.1.2 Sending data to the server	
#### 7.1.3 Updating data on the server	
#### 7.1.4 Deleting data from the server	
### 7.2 Enabling data-backed services	
#### 7.2.1 Adjusting resource paths and relation names	
### 7.3 Consuming REST services	
#### 7.3.1 GETting resources	
#### 7.3.2 PUTting resources	
#### 7.3.3 DELETEing resources	
#### 7.3.4 POSTing resource data	
## Chapter 8 -Securing REST	
### 8.1 Introducing OAuth 2	
### 8.2 Creating an authorization server	
### 8.4 Developing the client	139
## Chapter 09 - Sending messages	
### 9.1 Sending messages with JMS	
#### 9.1.1 Setting up JMS	
#### 9.1.2 Sending messages with JmsTemplate	
#### 9.1.3 Receiving JMS messages	
### 9.3 Messaging with Kafka	
#### 9.3.1 Setting up Spring for Kafka messaging	
#### 9.3.2 Sending messages with KafkaTemplate	
#### 9.3.3 Writing Kafka listeners
## Chapter 10 -Integrating Spring	
### 10.1 Declaring a simple integration flow
#### 10.1.1 Defining integration flows with XML	
#### 10.1.2 Configuring integration flows in Java	
#### 10.1.3 Using Spring Integration’s DSL configuration	
### 10.2 Surveying the Spring Integration landscape	
#### 10.2.1 Message channels	
#### 10.2.2 Filters	
#### 10.2.3 Transformers	
#### 10.2.4 Routers	
#### 10.2.5 Splitters	
#### 10.2.6 Service activators	
#### 10.2.7 Gateways	
#### 10.2.8 Channel adapters	
### 10.3 Creating an email integration flow	
## Chapter 11- Introducing Reactor	
### 11.1 Understanding reactive programming	
### 11.2 Getting started with Reactor	
#### 11.2.1 Diagramming reactive flows	
#### 11.2.2 Adding Reactor dependencies	
### 11.3 Applying common reactive operations	
#### 11.3.1 Creating reactive types	
#### 11.3.2 Combining reactive types	
#### 11.3.3 Transforming and filtering reactive streams	
#### 11.3.4 Performing logic operations on reactive types	
## Chapter 12 - Developing reactive APIs
### 12.1 Working with Spring WebFlux 
#### 12.1.1 Introducing Spring WebFlux	
#### 12.1.2 Writing reactive controllers	
### 12.2 Defining functional request handlers	
### 12.3 Testing reactive controllers	
#### 12.3.1 Testing GET requests	
#### 12.3.2 Testing POST requests	
#### 12.3.3 Testing with a live server	
### 12.4 Consuming REST APIs reactively	
#### 12.4.1 GETting resources	
#### 12.4.2 Sending resources	
#### 12.4.4 Handling errors	
### 12.5 Securing reactive web APIs	
#### 12.5.1 Configuring reactive web security
#### 12.5.2 Configuring a reactive user details service	
## Chapter 13- Persisting data reactively	
### 13.1 Working with R2DBC	
#### 13.1.1 Defining domain entities for R2DBC	
#### 13.1.2 Defining reactive repositories	
#### 13.1.3 Testing R2DBC repositories	
#### 13.1.4 Defining an OrderRepository aggregate root service	
#### 13.3.1 Defining domain classes for Cassandra persistence	
#### 13.3.2 Creating reactive Cassandra repositories	
#### 13.3.3 Testing reactive Cassandra repositories	
## Chapter 14 - Working with Rsocket	
### 14.1 Introducing RSocket	
### 14.2 Creating a simple RSocket server and client	
#### 14.2.1 Working with request-response	
#### 14.2.2 Handling request-stream messaging	
#### 14.2.3 Sending fire-and-forget messages	
#### 14.2.4 Sending messages bidirectionally	
### 14.3 Transporting RSocket over WebSocket	

