# config-server

This is a [Spring Cloud Config](http://cloud.spring.io/spring-cloud-config/)
config server.

This is for the purpose of reproducing Spring Boot
[issue #5491](https://github.com/spring-projects/spring-boot/issues/5491).

See the [test-app](https://github.com/shakuzen/boot-issue-5491)
and the [config-repo](https://github.com/shakuzen/config-repo-5491)
to reproduce the reported issue.

## Instructions

After cloning this repository, start the config server locally to serve the config-repo's configuration files.
Then proceed to the instructions in the [test-app](https://github.com/shakuzen/boot-issue-5491) to finish reproducing the issue.
