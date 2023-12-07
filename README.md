# Contents
## Chaper 01- Getting started with Spring
### 1.1 What is Spring?	
### 1.2 Initializing a Spring application	9
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
1.4.1 The core Spring Framework	
1.4.2 Spring Boot	20
1.4.3 Spring Data	21
1.4.4 Spring Security	21
1.4.5 Spring Integration and Spring Batch	21
1.4.6 Spring Cloud	21
1.4.7 Spring Native	21
Summary	22
Chapter 02 - Developing web	22
Applications	22
### 2.1 Displaying information	22
2.1.1 Establishing the domain	24
2.1.2 Creating a controller class	26
2.1.3 Designing the view	29
### 2.2 Processing form submission	32
### 2.3 Validating form input	37
2.3.1 Declaring validation rules	38
2.3.2 Performing validation at form binding	39
2.3.3 Displaying validation errors	40
### 2.4 Working with view controllers	40
### 2.5 Choosing a view template library	42
2.5.1 Caching templates	43
Summary	44
Chapter 03 -Working with data	44
### 3.3 Persisting data with Spring Data JPA	45
3.3.1 Adding Spring Data JPA to the project	45
3.3.2 Annotating the domain as entities	45
3.3.3 Declaring JPA repositories	48
3.3.4 Customizing repositories	48
Chapter 04 - Working with	50
nonrelational data	50
### 4.1 Working with Cassandra repositories	51
4.1.1 Enabling Spring Data Cassandra	51
4.1.2 Understanding Cassandra data modeling	54
4.1.3 Mapping domain types for Cassandra persistence	55
4.1.4 Writing Cassandra repositories	60
Chapter05 - Securing Spring	60
### 5.1 Enabling Spring Security	61
### 5.2 Configuring authentication	62
5.2.1 In-memory user details service	64
5.2.2 Customizing user authentication	65
### 5.3 Securing web requests	70
5.3.1 Securing requests	70
5.3.2 Creating a custom login page	73
5.3.3 Enabling third-party authentication	75
5.3.4 Preventing cross-site request forgery	77
### 5.4 Applying method-level security	78
### 5.5 Knowing your user	80
Chapter 06 - Working with	83
configuration properties	83
### 6.1 Fine-tuning autoconfiguration	83
6.1.1 Understanding Spring’s environment abstraction	84
6.1.2 Configuring a data source	86
6.1.3 Configuring the embedded server	88
6.1.4 Configuring logging	89
### 6.2 Creating your own configuration properties	91
6.2.1 Defining configuration property holders	94
6.2.2 Declaring configuration property metadata	95
### 6.3 Configuring with profiles	97
6.3.1 Defining profile-specific properties	98
6.3.2 Activating profiles	99
6.3.3 Conditionally creating beans with profiles	101
Chapter 07-Creating REST services	103
### 7.1 Writing RESTful controllers	104
7.1.1 Retrieving data from the server	104
7.1.2 Sending data to the server	108
7.1.3 Updating data on the server	109
7.1.4 Deleting data from the server	111
### 7.2 Enabling data-backed services	112
7.2.1 Adjusting resource paths and relation names	115
### 7.3 Consuming REST services	118
7.3.1 GETting resources	120
7.3.2 PUTting resources	122
7.3.3 DELETEing resources	122
7.3.4 POSTing resource data	122
Chapter 8 -Securing REST	123
### 8.1 Introducing OAuth 2	124
### 8.2 Creating an authorization server	128
### 8.4 Developing the client	139
Chapter 09 - Sending messages	144
### 9.1 Sending messages with JMS	145
9.1.1 Setting up JMS	145
9.1.2 Sending messages with JmsTemplate	146
9.1.3 Receiving JMS messages	153
### 9.3 Messaging with Kafka	156
9.3.1 Setting up Spring for Kafka messaging	157
9.3.2 Sending messages with KafkaTemplate	158
9.3.3 Writing Kafka listeners	160
Chapter 10 -Integrating Spring	161
### 10.1 Declaring a simple integration flow	162
10.1.1 Defining integration flows with XML	163
10.1.2 Configuring integration flows in Java	165
10.1.3 Using Spring Integration’s DSL configuration	166
### 10.2 Surveying the Spring Integration landscape	167
10.2.1 Message channels	168
10.2.2 Filters	170
10.2.3 Transformers	171
10.2.4 Routers	173
10.2.5 Splitters	174
10.2.6 Service activators	178
10.2.7 Gateways	180
10.2.8 Channel adapters	181
### 10.3 Creating an email integration flow	184
Chapter 11- Introducing Reactor	190
### 11.1 Understanding reactive programming	191
### 11.2 Getting started with Reactor	194
11.2.1 Diagramming reactive flows	195
11.2.2 Adding Reactor dependencies	196
### 11.3 Applying common reactive operations	197
11.3.1 Creating reactive types	198
11.3.2 Combining reactive types	201
11.3.3 Transforming and filtering reactive streams	204
11.3.4 Performing logic operations on reactive types	211
#### 12.1.1 Introducing Spring WebFlux	214
12.1.2 Writing reactive controllers	215
### 12.2 Defining functional request handlers	219
12.3 Testing reactive controllers	222
12.3.1 Testing GET requests	222
12.3.2 Testing POST requests	225
12.3.3 Testing with a live server	226
### 12.4 Consuming REST APIs reactively	226
12.4.1 GETting resources	227
12.4.2 Sending resources	229
12.4.4 Handling errors	231
### 12.5 Securing reactive web APIs	234
12.5.1 Configuring reactive web security	235
12.5.2 Configuring a reactive user details service	236
Chapter 13- Persisting data reactively	238
### 13.1 Working with R2DBC	238
13.1.1 Defining domain entities for R2DBC	239
13.1.2 Defining reactive repositories	243
13.1.3 Testing R2DBC repositories	244
13.1.4 Defining an OrderRepository aggregate root service	246
13.3.1 Defining domain classes for Cassandra persistence	251
13.3.2 Creating reactive Cassandra repositories	253
13.3.3 Testing reactive Cassandra repositories	254
Chapter 14 - Working with Rsocket	255
### 14.1 Introducing RSocket	256
### 14.2 Creating a simple RSocket server and client	258
14.2.1 Working with request-response	258
14.2.2 Handling request-stream messaging	260
14.2.3 Sending fire-and-forget messages	262
14.2.4 Sending messages bidirectionally	263
### 14.3 Transporting RSocket over WebSocket	266

