# Config Service

[Spring Cloud Config](https://cloud.spring.io/spring-cloud-config/spring-cloud-config.html) is horizontally scalable centralized configuration service for distributed systems. It uses a pluggable repository layer that currently supports local storage, Git, and Subversion. 

The default implementation of the server storage backend uses git. But in this project, I use `native profile`, which simply loads config files from the local classpath. You can see `shared` directory in Config service resource. This approach is great for getting started quickly and for testing.

**With Spring Cloud Config, You Can Change App Configuration Dynamically.**