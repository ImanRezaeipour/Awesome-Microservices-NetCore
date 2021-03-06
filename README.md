# Awesome Microservices .NET Core Resources [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

    The Best Resources for Microservices in .NET Core

## Give a Star! ⭐️

If you liked this repo or if it helped you, please give a star ⭐️ for this repository. That will not only help strengthen our .NET community but also improve skills about the Microservices for .NET developers around the world. Thank you very much 👍

## Contents
- [Training Series](#training-series)
  - [Building Microservices On .NET Core](#building-microservices-on-net-core)
  - [Building microservices through Event Driven Architecture](#building-microservices-through-event-driven-architecture)
  - [Building API Gateway Using Ocelot In ASP.NET Core](#building-api-gateway-using-ocelot-in-aspnet-core)
  - [Distributed .NET Core (DShop)](#distributed-net-core-dshop)
  - [Microservices .NET](#microservices-net)
  - [.NET Conf: Focus on Microservices](#net-conf-focus-on-microservices)
  - [Microservices with .NET Core and Docker](#microservices-with-net-core-and-docker)
  - [.NET Microservices Architecture Guidance (Microsoft)](#net-microservices-architecture-guidance-microsoft)
- [Other Tutorials](#other-tutorials)
- [Other Repositories](#other-repositories)
- [Contribution](#contribution)
- [Licence](#license)

## Training Series

### Building Microservices On .NET Core

1. [Building Microservices On .NET Core – Part 1 The Plan](https://altkomsoftware.pl/en/blog/building-microservices-net-core-part-1-plan/)

2. [Building Microservices On .NET Core – Part 2 Shaping microservice internal architecture with CQRS and MediatR](https://altkomsoftware.pl/en/blog/microservices-net-core-cqrs-mediatr/)

3. [Building Microservices On .NET Core – Part 3 Service Discovery with Eureka](https://altkomsoftware.pl/en/blog/service-discovery-eureka/)

4. [Building Microservices On .NET Core – Part 4 Building API Gateways With Ocelot](https://altkomsoftware.pl/en/blog/building-api-gateways-with-ocelot/)

5. [Building Microservices On .NET Core – Part 5 Marten An Ideal Repository For Your Domain Aggregates](https://altkomsoftware.pl/en/blog/building-microservices-domain-aggregates/)

6. [Building Microservices On .NET Core – Part 6 Real time server client communication with SignalR and RabbitMQ](https://altkomsoftware.pl/en/blog/building-microservices-6/)

7. [Building Microservices On .NET Core – Part 7 Transactional Outbox with RabbitMQ](https://altkomsoftware.pl/en/blog/microservices-outbox-rabbitmq/)

**Repository :** https://github.com/asc-lab/dotnetcore-microservices-poc

### Building microservices through Event Driven Architecture

1. [Building microservices through Event Driven Architecture part1 : application specific business rules](https://logcorner.com/building-microservices-through-event-driven-architecture-part1-application-specific-business-rules/)

2. [Building microservices through Event Driven Architecture part2 : domain objects and business rules](https://logcorner.com/building-microservices-through-event-driven-architecture-part2-domain-objects-and-business-rules/)

3. [Building microservices through Event Driven Architecture part3: Presenters, Views, and Controllers](https://logcorner.com/building-microservices-through-event-driven-architecture-part3-presenters-views-and-controllers/)

4. [Building microservices through Event Driven Architecture part4: repositories](https://logcorner.com/building-microservices-through-event-driven-architecture-part4-repositories/)

5. [Building microservices through Event Driven Architecture part5: dockerization (Web Api Core and SQL Server Linux)](https://logcorner.com/building-microservices-through-event-driven-architecture-part5-dockerization-web-api-core-and-sql-server-linux/)

6. [Building microservices through Event Driven Architecture part7: Implementing EventSourcing on Domain Model](https://logcorner.com/building-microservices-through-event-driven-architecture-part7-event-sourcing-core-domain/)

7. [Building microservices through Event Driven Architecture part8: Implementing EventSourcing on Repositories](https://logcorner.com/building-microservices-through-event-driven-architecture-part7-implementing-eventsourcing-on-repositories/)

8. [Building microservices through Event Driven Architecture part9: Implementing EventSourcing on Application](https://logcorner.com/building-microservices-through-event-driven-architecture-part8-implementing-eventsourcing-on-application/)

9. [Building microservices through Event Driven Architecture part10: Handling updates](https://logcorner.com/building-microservices-through-event-driven-architecture-part10-handling-updates-and-deletes/)

10. [Building microservices through Event Driven Architecture part11: Run Unit tests inside a docker container](https://logcorner.com/building-microservices-through-event-driven-architecture-part11-run-unit-tests-inside-a-docker-container/)

11. [Building microservices through Event Driven Architecture part12: Continuous Integration](https://logcorner.com/building-microservices-through-event-driven-architecture-part12-continuous-integration/)

**Repository :** https://github.com/logcorner/LogCorner.EduSync.Speech.Command/

### Building API Gateway Using Ocelot In ASP.NET Core 

1. [Building API Gateway Using Ocelot In ASP.NET Core](https://www.c-sharpcorner.com/article/building-api-gateway-using-ocelot-in-asp-net-core/)

2. [Part Two - Building API Gateway Using Ocelot In ASP.NET Core - Authentication](https://www.c-sharpcorner.com/article/building-api-gateway-using-ocelot-in-asp-net-core-part-two/)

3. [Part Three -Building API Gateway Using Ocelot In ASP.NET Core - Logging](https://www.c-sharpcorner.com/article/building-api-gateway-using-ocelot-in-asp-net-core-part-three-logging2/)

4. [Part Four - Building API Gateway Using Ocelot In ASP.NET Core - Rate Limiting](https://www.c-sharpcorner.com/article/building-api-gateway-using-ocelot-in-asp-net-core-rate-limiting-part-four/)

5. [Building API Gateway Using Ocelot In ASP.NET Core - QoS (Quality of Service)](https://www.c-sharpcorner.com/article/building-api-gateway-using-ocelot-in-asp-net-core-qos/)

6. [Building API Gateway Using Ocelot In ASP.NET Core - Load Balancing](https://www.c-sharpcorner.com/article/building-api-gateway-using-ocelot-in-asp-net-core-load-balancing/)

7. [Building API Gateway Using Ocelot In ASP.NET Core - Service Discovery (Eureka)](https://www.c-sharpcorner.com/article/building-api-gateway-using-ocelot-in-asp-net-core-service-discoveryeureka/)

8. [Building API Gateway Using Ocelot In ASP.NET Core - Service Discovery (Consul)](https://www.c-sharpcorner.com/article/building-api-gateway-using-ocelot-in-asp-net-core-service-discovery-consul/)

9. [Building API Gateway Using Ocelot In ASP.NET Core - Configuration (Consul)](https://www.c-sharpcorner.com/article/building-api-gateway-using-ocelot-in-asp-net-core-configuration-consul/)

**Repository :** https://github.com/catcherwong-archive/APIGatewayDemo

### Distributed .NET Core (DShop)

1. [Distributed .NET Core (DShop) - Teaser](https://www.youtube.com/watch?v=6YYB8vv3pZg&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

2. [Distributed .NET Core (DShop) - Episode 1 [Intro, HTTP requests flow, Infrastructure with Docker]](https://www.youtube.com/watch?v=s4fd3PRlOcw&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

3. [Distributed .NET Core (DShop) - Episode 2 [CQRS - Write side, Discounts service, MongoDB repository]](https://www.youtube.com/watch?v=yqh0dN4oDTs&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

4. [Distributed .NET Core (DShop) - Episode 3 [Subscribing RabbitMQ messages, API gateway]](https://www.youtube.com/watch?v=L9UUUPedidg&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

5. [Distributed .NET Core (DShop) - Episode 4 [Asynchronous microservices integration via events]](https://www.youtube.com/watch?v=KiIetmswEos&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

6. [Distributed .NET Core (DShop) - Episode 5 [CQRS - Read side, Internal HTTP communication]](https://www.youtube.com/watch?v=o0fMHARUwq0&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

7. [Distributed .NET Core (DShop) - Episode 6 [Service discovery & Load balancing with Consul + Fabio]](https://www.youtube.com/watch?v=UWfn8Iml2Kc&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

8. [Distributed .NET Core (DShop) - Episode 7 [Handling asynchronous requests, SignalR, Polly]](https://www.youtube.com/watch?v=rKmL2Onh4hg&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

9. [Distributed .NET Core (DShop) - Episode 8 [Distributed transactions, 2PC, Event Choreography, Saga]](https://www.youtube.com/watch?v=KI223ULIFoA&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

10. [Distributed .NET Core (DShop) - Episode 9 [Vault secrets, Seq logging, Jaeger distributed tracing]](https://www.youtube.com/watch?v=8bDHf7yiNKM&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

11. [Distributed .NET Core (DShop) - Episode 10 [Metrics with AppMetrics, InfluxDB, Prometheus, Grafana]](https://www.youtube.com/watch?v=2OiE-h9sNM4&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

12. [Distributed .NET Core (DShop) - Episode 11 [Travis CI pipelines, custom MyGet feeds]](https://www.youtube.com/watch?v=sS9yB7m_OsQ&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

13. [Distributed .NET Core (DShop) - Episode 12 [Docker basics, Docker Hub, docker-compose]](https://www.youtube.com/watch?v=drD0vgKecAc&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

14. [Distributed .NET Core (DShop) - Episode 13 [Integration tests with xUnit, Web API, Mongo, RabbitMQ]](https://www.youtube.com/watch?v=fDe_Neayo9I&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

15. [Distributed .NET Core (DShop) - Episode 14 [Consumer-driven contract testing with Pact]](https://www.youtube.com/watch?v=qRCY5BTYQk0&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

16. [Distributed .NET Core (DShop) - Episode 15 [Orchestration with Portainer, Kubernetes and Rancher]](https://www.youtube.com/watch?v=YxvB6-6FSZE&list=PLqqD43D6Mqz38LoZEuo_hJAp2NxXskcut)

**Repository :** https://github.com/devmentors/DNC-DShop

### Microservices .NET

1. [Meet Pacco & Microservices .NET!](https://www.youtube.com/watch?v=5SLyrETnJoE&list=PLqqD43D6Mqz1LNS7bqFhAJNfmVfQ077hz)

2. [CQRS - reserving a resource](https://www.youtube.com/watch?v=Ne5XueXktfM&list=PLqqD43D6Mqz1LNS7bqFhAJNfmVfQ077hz)

3. [Inbox & Outbox pattern - transactional message processing](https://www.youtube.com/watch?v=ebyR5RPKciw&list=PLqqD43D6Mqz1LNS7bqFhAJNfmVfQ077hz)

4. [API Gateway with Ocelot and RabbitMQ](https://www.youtube.com/watch?v=TM3DpaWdLRM&list=PLqqD43D6Mqz1LNS7bqFhAJNfmVfQ077hz)

5. [Contract testing with Pact.io](https://www.youtube.com/watch?v=vhlH5NyNbjA&list=PLqqD43D6Mqz1LNS7bqFhAJNfmVfQ077hz)

6. [Distributed Tracing with Jaeger](https://www.youtube.com/watch?v=toXFRBtv4fg&list=PLqqD43D6Mqz1LNS7bqFhAJNfmVfQ077hz)

7. [Dynamic Credentials with Vault](https://www.youtube.com/watch?v=L3mDWAA-rzg&list=PLqqD43D6Mqz1LNS7bqFhAJNfmVfQ077hz)

8. [DevMentors Live #0 - "Microservices .NET" Q&A, future plans etc...](https://www.youtube.com/watch?v=tQu96sqWkz8&list=PLqqD43D6Mqz1LNS7bqFhAJNfmVfQ077hz)

9. [Sidecar pattern + custom reverse proxy + k8s](https://www.youtube.com/watch?v=1v8SXWXxGvM&list=PLqqD43D6Mqz1LNS7bqFhAJNfmVfQ077hz)

**Repository :** https://github.com/devmentors/Pacco

### .NET Conf: Focus on Microservices

1. [Welcome to .NET Conf: Focus on Microservices](https://www.youtube.com/watch?v=ZEvoxXnsbbU&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

2. [Why You Should Care About Microservices](https://www.youtube.com/watch?v=7hY6fggwHqU&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

3. [Stay Sharp](https://www.youtube.com/watch?v=x_IGNq4snx8&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

4. [A Journey into .NET Microservices with Steeltoe](https://www.youtube.com/watch?v=3meYereHHtM&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

5. [Orleans at Microsoft](https://www.youtube.com/watch?v=KhgYlvGLv9c&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

6. [Adding a Little DAPR to Your .NET Microservices](https://www.youtube.com/watch?v=g-gOlkD9lKs&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

7. [Developing and Deploying Microservices with 'Tye'](https://www.youtube.com/watch?v=MMIUpYOQq5Y&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

8. [Beyond REST and RPC: Asynchronous Eventing and Messaging Patterns](https://www.youtube.com/watch?v=6zs-PhgfLU4&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

9. [The Intersection of Microservices, Domain-Driven Design and Entity Framework Core](https://www.youtube.com/watch?v=DG8Qe7TJiIE&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

10. [Build High-performance Microservices with gRPC and .NET](https://www.youtube.com/watch?v=HVq4TstHCEs&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

11. [DevOps, Waffles, and Superheroes - Oh My!](https://www.youtube.com/watch?v=5BkKjTxIokU&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

12. [API Communication in Microservices with Azure API Management and Azure Functions](https://www.youtube.com/watch?v=YLMsAMvY4KA&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

13. [Evolving .NET Framework Monoliths with .NET 5 and Kubernetes](https://www.youtube.com/watch?v=Wbjh4T-cdv8&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

14. [Migrating .NET Framework Web Apps to Azure](https://www.youtube.com/watch?v=UT_Fd-Pkiuw&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

15. [Building & Debugging Microservices faster using Kubernetes and Visual Studio](https://www.youtube.com/watch?v=98nIvg7ne7Q&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

16. [Workshop Module 1: Introducing Microservices](https://www.youtube.com/watch?v=jMDufMYAsmw&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

17. [Workshop Module 2: Modeling and Architecting Microservices](https://www.youtube.com/watch?v=u7MM21aIsqk&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

18. [Workshop Module 3: Microservice Communication](https://www.youtube.com/watch?v=iL3Kxd4Auys&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

19. [Workshop Module 4: Deploying Microservices to Kubernetes](https://www.youtube.com/watch?v=3G7NB4waGbk&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

20. [Workshop Module 5: Deploying Service Mesh to Kubernetes](https://www.youtube.com/watch?v=qwEfynnevEU&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

21. [Workshop Module 6: Distributed Data](https://www.youtube.com/watch?v=7kVmb747vfM&list=PLdo4fOcmZ0oUc2ShrReCS7KoBbPEONE0p)

**Repository :** https://github.com/dotnet-presentations/dotNETConf/tree/master/2020/FocusOnMicroservices

### Microservices with .NET Core and Docker

1. [Microservices with .NET Core and Docker Episode 1](https://www.youtube.com/watch?v=P5alkeFH8aU&list=PLuFW0YeVZv-kJyjRycyu-5R0COCbTXtIu)

2. [Microservices with .NET Core and Docker Episode 02](https://www.youtube.com/watch?v=Uwsgd7cIJxk&list=PLuFW0YeVZv-kJyjRycyu-5R0COCbTXtIu)

3. [Microservices with .NET Core and Docker Episode 03 - Serilog and Seq](https://www.youtube.com/watch?v=orPeI28AmaM&list=PLuFW0YeVZv-kJyjRycyu-5R0COCbTXtIu)

4. [Microservices with .NET Core and Docker Episode 04 - Bandwidth Tester with Serilog and Seq](https://www.youtube.com/watch?v=xwbzNI5ymAs&list=PLuFW0YeVZv-kJyjRycyu-5R0COCbTXtIu)

5. [Microservices with .NET Core and Docker Episode 05 - PostgreSQL Setup](https://www.youtube.com/watch?v=8QvVoFiYxIc&list=PLuFW0YeVZv-kJyjRycyu-5R0COCbTXtIu)

6. [Microservices with .Net Core and Docker Episode 06 - Corona Virus Dashboard Part 01](https://www.youtube.com/watch?v=yd8FycqRRAk&list=PLuFW0YeVZv-kJyjRycyu-5R0COCbTXtIu)

7. [Microservices with .Net Core and Docker Episode 07 - Corona Virus Dashboard Part 02](https://www.youtube.com/watch?v=nGmPHTnB8pk&list=PLuFW0YeVZv-kJyjRycyu-5R0COCbTXtIu)

8. [DockerMonitoring with Grafana and .NET Core](https://www.youtube.com/watch?v=udGjA6Pxtuo&list=PLuFW0YeVZv-kJyjRycyu-5R0COCbTXtIu)

**Repository :** https://github.com/DotNetMax/DockerMonitoringService

### .NET Microservices Architecture Guidance (Microsoft)

- [.NET Microservices: Architecture for Containerized .NET Applications](https://docs.microsoft.com/en-us/dotnet/architecture/microservices/)

- [Download eBook (PDF)](https://aka.ms/microservicesebook)

- [Microservice Architecture with ASP.NET Core (Video)](https://channel9.msdn.com/Shows/On-NET/Microservice-Architecture-with-ASPNET-Core)

- [Implement Microservices Patterns with .NET Core and Docker Containers (Video)](https://channel9.msdn.com/events/Ignite/Microsoft-Ignite-Orlando-2017/BRK3317)

**Repository :** https://github.com/dotnet-architecture/eShopOnContainers

## Other Tutorials

1. [Microservices with ASP.NET Core 3.1](https://procodeguide.com/programming/microservices-asp-net-core/)

2. [Microservices using ASP.NET Core, Ocelot, MongoDB and JWT](https://www.codeproject.com/Articles/5271708/Microservices-using-ASP-NET-Core-Ocelot-MongoDB-an)



## Other Repositories

## Contribution

Let's complete this awesome together and create the most complete resource for microservices in .NET ✌️

Feel free to open an issue or create a pull request with your additions.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Mohammad Javad Ebrahimi](https://github.com/mjebrahimi/) has waived all copyright and related or neighboring rights to this work.
