## micronaut vs spring boot comparison project
This repo contains simple projects with equivalent functionality in Java using [Micronaut](http://micronaut.io) and [Spring Boot](http://start.spring.io).

Projects:
* [customer-svc](customer-svc/README.md)  Micronaut version
* [customer-svc-sb](customer-svc-sb/README.md)  Spring Boot version


### Stats
| Stat          | customer-svc  | customer-svc-sb  | diff % |
| ------------- |:-------------:| -----:| ----- :|
| uber jar size | 12826333 | 19484021 | 52% |
| native image size| 59175120   |   N/A | |
| startup time  | 866ms      |   1176 | 36% |
