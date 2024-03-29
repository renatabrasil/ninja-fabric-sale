# Ninja Fabric Sale
[![Maintainability](https://api.codeclimate.com/v1/badges/f79ef09861bda7234c54/maintainability)](https://codeclimate.com/github/renatabrasil/ninja-fabric-sale/maintainability)

[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=renatabrasil_ninja-fabric-sale&metric=alert_status)](https://sonarcloud.io/dashboard?id=renatabrasil_ninja-fabric-sale) [![Code Smells](https://sonarcloud.io/api/project_badges/measure?project=renatabrasil_ninja-fabric-sale&metric=code_smells)](https://sonarcloud.io/dashboard?id=renatabrasil_ninja-fabric-sale) [![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=renatabrasil_ninja-fabric-sale&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=renatabrasil_ninja-fabric-sale) [![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=renatabrasil_ninja-fabric-sale&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=renatabrasil_ninja-fabric-sale) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=renatabrasil_ninja-fabric-sale&metric=coverage)](https://sonarcloud.io/dashboard?id=renatabrasil_ninja-fabric-sale)


**Conceptual map**

![](docs/conceptual_map.svg)

**Organizacao das classes**

![](./docs/diagrama_de_classes_alto_nivel/Diagrama de classes.svg)

-----

### Observability

- [docker-compose.yaml <- Grafana + Loki](https://raw.githubusercontent.com/grafana/loki/main/examples/getting-started/docker-compose.yaml)
- [Grafana + Loki](https://grafana.com/docs/loki/latest/getting-started/) 

The links below describe how to configure a Spring Boot Application with prometheus and grafana

- https://medium.com/@contactkumaramit9139/monitoring-spring-boot-applications-with-prometheus-and-grafana-21445260dad4
- https://medium.com/@luanrubensf/monitoring-spring-applications-with-prometheus-and-grafana-ae50bbdd1920 
- https://betterprogramming.pub/how-to-monitor-a-spring-boot-app-with-prometheus-and-grafana-22e2338f97fc
- https://refactorfirst.com/spring-boot-prometheus-grafana

Additional content:

- [Dashboards ready to use!](https://grafana.com/grafana/dashboards/)
  - Id: 13041, Website monitoring
  - Id: 12464, Spring Boot Statistics
  - Id: 16770, HTTP Server Overview
  - Id: 17053, Spring Boot & Endpoint Metrics 2.0
  - Id: 17175, Spring Boot Observability
  - Id: 11378, Spring Boot 2.1 System Monitor 

The links below shows how to configure Spring Application to pull logs in Grafana Loki locally:

- https://www.springcloud.io/post/2022-02/springboot-loki-1/#gsc.tab=0
- https://gist.github.com/ruanbekker/c6fa9bc6882e6f324b4319c5e3622460

### Performance tests


 

### Problemas no build

- O gradle só funcionou com a solução dada aqui: https://stackoverflow.com/questions/58282791/why-when-i-use-github-actions-ci-for-a-gradle-project-i-face-gradlew-permiss
