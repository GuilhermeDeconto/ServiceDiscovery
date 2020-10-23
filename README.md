# ServiceDiscovery

In order to use Eureka service discovery with zuul and eureka client, run the following applications:
* [Eureka Service Discovery](https://github.com/GuilhermeDeconto/ServiceDiscovery)
* [Zuul Gateway](https://github.com/GuilhermeDeconto/Gateway)
* [Eureka Client](https://github.com/GuilhermeDeconto/DataseedService)

In addition you'll need the following commands to see everything working:
* [Check eureka registration](http://localhost:8761/)
* [Check if zuul has client serive route](http://localhost:8762/actuator/routes)
* [Call service through zuul](http://localhost:8762/spring-cloud-eureka-client/api/test)
