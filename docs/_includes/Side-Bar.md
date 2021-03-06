
- Overview
    - [Why ServiceStack?](?id=why-servicestack)
    - [Architecture Overview](?id=architecture-overview)
    - [What is a message-based WebService?](?id=What-is-a-message-based-web-service)
    - [Advantages of message-based WebServices](?id=advantages-of-message-based-web-services)
    - [Why remote services should use DTOs?](http://stackoverflow.com/a/15369736/85785)
    - [Live Demos](https://github.com/ServiceStackApps/LiveDemos)
- Releases
    - [Latest Release Notes](?id=v4-5-2)
    - [2016 Summary](/releases/)
    - [Release Notes History](?id=release-notes-history)
- Getting Started
    - [Create your first WebService](?id=create-your-first-webservice)
    - [Creating a WebService from scratch](?id=create-webservice-from-scratch)
    - [Your first webservice explained](?id=your-first-webservice-explained)
    - [ServiceStack's API Design](?id=api-design)
    - [Designing a REST-ful service with ServiceStack](http://stackoverflow.com/a/15235822/85785)
    - [Complexity, Services and Role of DTOs](http://stackoverflow.com/a/32940275/85785)
- Reference
    - [Order of Operations](?id=order-of-operations)
    - [Metadata page](?id=metadata-page)
    - [The IoC container](?id=ioc)
    - [Configuration & AppSettings](?id=appsettings)
    - [Routing](?id=routing)
    - [REST, SOAP & default endpoints](?id=endpoints)
    - [SOAP support](?id=soap-support)
    - [Service return types](?id=service-return-types)
    - [Customize HTTP Responses](?id=customize-http-responses)
    - [Customize JSON Responses](?id=customize-json-responses)
    - [Validation](?id=validation)
    - [Error Handling](?id=error-handling)
    - [Debugging](?id=debugging)
    - [ss-utils.js JavaScript Client Library](?id=ss-utils-js)
- Clients
    - [Overview](?id=clients-overview)
    - [C#/.NET client](?id=csharp-client)
    - [JavaScript client](?id=javascript-client)
    - [Silverlight client](?id=silverlight-client)
    - [Dart Client](?id=dart-client)
    - [MQ Clients](?id=messaging#mq-client-architecture)
- Add ServiceStack Reference
    - [Overview](?id=add-servicestack-reference)
    - [C# Add Reference](?id=csharp-add-servicestack-reference)
    - [TypeScript Add Reference](?id=typescript-add-servicestack-reference)
    - [Swift Add Reference](?id=swift-add-servicestack-reference)
    - [Java Add Reference](?id=java-add-servicestack-reference)
    - [Kotlin Add Reference](?id=kotlin-add-servicestack-reference)
    - [F# Add Reference](?id=fsharp-add-servicestack-reference)
    - [VB.NET Add Reference](?id=vbnet-add-servicestack-reference)
- Formats
    - [Overview](?id=formats)
    - [JSON, JSV & XML](?id=json-jsv-and-xml)
    - [CSV Format](?id=csv-format)
    - [MessagePack Format](?id=messagepack-format)
    - [ProtoBuf Format](?id=protobuf-format)
    - [HTML5 Report Format](?id=html5reportformat)
- View Engines
    - [Razor & Markdown Razor](http://razor.servicestack.net/)
    - [Razor Notes](?id=razor-notes)
    - [View and Template Selection](?id=view-and-template-selection)
    - [Compiled Razor Views](?id=compiled-razor-views)
    - [Razor Views vs Content Pages](http://stackoverflow.com/questions/13206038/servicestack-razor-default-page/13206221#13206221)
    - [Self-Hosted Razor Views](http://www.ienablemuch.com/2012/12/self-hosting-servicestack-serving.html) 
    - [Markdown Razor](?id=markdown-razor)
- Hosts
    - [IIS](?id=iis)
    - [Self-hosting](?id=self-hosting)
- MQ Messaging
    - [Overview](?id=messaging)
    - [Rabbit MQ](?id=rabbit-mq)
    - [Redis MQ](?id=messaging-and-redis)
    - [Amazon SQS](https://github.com/ServiceStack/ServiceStack.Aws#sqsmqserver)
- .NET Core
    - [.NET Core Clients](?id=netcore-clients)
    - [.NET Core Redis](?id=netcore-redis)
- Mono
    - [Overview](?id=mono)
    - [Run ServiceStack as a daemon on Linux](?id=servicestack-as-daemon-on-linux)
    - [Run ServiceStack in Fastcgi hosted on nginx](?id=servicestack-in-fastcgi-hosted-on-nginx)
    - [Linux-Hosting-Options](?id=linux-hosting-options)
- Security
    - [Overview](?id=security)
    - [Authentication & Authorization](?id=authentication-and-authorization)
    - [JWT AuthProvider](?id=jwt-authprovider)
    - [API Key AuthProvider](?id=api-key-authprovider)
    - [Open Id 2.0 Support](?id=openid)
    - [Sessions](?id=sessions)
    - [Restricting Services](?id=restricting-services)
- Advanced
    - [Configuration options](?id=configuration-options)
    - [Run ServiceStack side-by-side with another web framework](?id=servicestack-side-by-side-with-another-web-framework)
    - [Access HTTP specific features in services](?id=access-http-specific-features-in-services)
    - [Logging](?id=logging)
    - [Serialization & Deserialization](?id=serialization-deserialization)
    - [Request & Response filters](?id=request-and-response-filters)
    - [Filter attributes](?id=filter-attributes)
    - [Concurrency Model](?id=concurrency-model)
    - [Built-in profiling](?id=built-in-profiling)
    - [Form Hijacking Prevention](?id=form-hijacking-prevention)
    - [Auto-Mapping](?id=auto-mapping)
    - [HTTP Utils](?id=http-utils)
    - [Dump Utils](?id=dump-utils)
    - [Virtual File System](?id=virtual-file-system)
    - [Config API](?id=config-api)
    - [Physical Project Structure](?id=physical-project-structure)
    - [Modularizing Services](?id=modularizing-services)
    - [MVC Integration](?id=mvc-integration)
    - [ServiceStack Integration](?id=servicestack-integration)
    - [Auto Batched Requests](?id=auto-batched-requests)
    - [Versioning](?id=versioning)
    - [Multitenancy](?id=multitenancy)
    - [Embedded Native Desktop Apps](https://github.com/ServiceStack/ServiceStack.Gap)
- Caching
    - [Overview](?id=caching)
    - [HTTP Caching](?id=http-caching)
    - [CacheResponse Attribute](?id=cacheresponse-attribute)
    - [Cache Aware Clients](?id=cache-aware-clients)
- AutoQuery
    - [Overview](?id=autoquery)
    - [Why Not OData](?id=why-not-odata)
    - [AutoQuery RDBMS](?id=autoquery-rdbms)
    - [AutoQuery Data](?id=autoquery-data)
    - [AutoQuery Data Memory](?id=autoquery-memory)
    - [AutoQuery Data Service](?id=autoquery-service)
    - [AutoQuery Data DynamoDB](?id=autoquery-dynamodb)
    - [AutoQuery UI](https://github.com/ServiceStack/Admin)
- Server Events
    - [Overview](?id=server-events)
    - [JavaScript Client](?id=javascript-server-events-client)
    - [C# Server Events Client](?id=csharp-server-events-client)
    - [Redis Server Events](?id=redis-server-events)
- Service Gateway
    - [Overview](?id=service-gateway)
    - [Service Discovery](?id=service-discovery)
- Encrypted Messaging
    - [Overview](?id=encrypted-messaging)
    - [Encrypted Service Client](?id=encrypted-messaging#encrypted-service-client)
- Plugins
    - [Overview](?id=plugins)
    - [Swagger API](?id=swagger-api)
    - [Postman](?id=postman)
    - [CORS Feature](?id=corsfeature)
    - [Request logger](?id=request-logger)
    - [Sitemaps](?id=sitemaps)
    - [Cancellable Requests](?id=cancellable-requests)
- Tests
    - [Testing](?id=testing) 
    - [HowTo write unit & integration tests](?id=howto-write-unit-integration-tests)
- ServiceStackVS
    - [Install ServiceStackVS](?id=install-servicestackvs)
    - [TypeScript React Template](https://github.com/ServiceStackApps/typescript-react-template/)
    - [React, Redux Chat App](https://github.com/ServiceStackApps/ReactChat)
    - [AngularJS App Template](https://github.com/ServiceStack/ServiceStackVS/blob/master/docs/angular-spa.md)
    - [React Desktop Apps](https://github.com/ServiceStackApps/ReactDesktopApps)
- Single Page Apps
    - [Overview](?id=single-page-apps) 
    - [HTML, CSS and JS Minifiers](?id=html-css-and-javascript-minification)
    - [Bundling and Minification](?id=bundling-and-minification)
- Java
    - [Java ServiceStack Resources](?id=java)
    - [Android Studio & IntelliJ](?id=java-add-servicestack-reference#servicestack-idea-android-studio-plugin)
    - [Eclipse Integration](https://github.com/ServiceStack/ServiceStack.Java/tree/master/src/ServiceStackEclipse#eclipse-integration-with-servicestack)
- Other Languages
    - [Swift](?id=swift)
    - [F#](?id=fsharp)
    - [VB.NET](?id=vbnet)
- Amazon Web Services
    - [ServiceStack.Aws](https://github.com/ServiceStack/ServiceStack.Aws)
    - [PocoDynamo](https://github.com/ServiceStack/PocoDynamo)
    - [AWS Live Demos](http://awsapps.servicestack.net)
    - [Getting Started with AWS](https://github.com/ServiceStackApps/AwsGettingStarted)
- Deployment
    - [Deploy Multiple Sites to single AWS Instance](?id=deploy-multiple-sites-to-aws)
    - [Simple Deployments to AWS with WebDeploy](?id=simple-deployments-to-aws)
    - [Advanced Deployments with OctopusDeploy](?id=advanced-deployment-octopus-deploy)
- Install 3rd Party Products
    - [Redis on Windows](https://github.com/ServiceStack/redis-windows)
    - [RabbitMQ on Windows](https://github.com/ServiceStack/rabbitmq-windows)
    - [Redis SSL on Azure](?id=ssl-redis-azure)
- Use Cases
    - [Azure](?id=azure)
    - [NHibernate](?id=nhibernate) 
- Performance
    - [Real world performance](?id=real-world-performance) 
- Other Products
    - [ServiceStack.Redis](https://github.com/ServiceStack/ServiceStack.Redis)
    - [ServiceStack.OrmLite](https://github.com/ServiceStack/ServiceStack.OrmLite)
    - [ServiceStack.Text](https://github.com/ServiceStack/ServiceStack.Text)
    - [ServiceStack.Aws](https://github.com/ServiceStack/ServiceStack.Aws)
    - [Stripe](https://github.com/ServiceStack/Stripe)
- Future
    - [Roadmap](?id=roadmap)