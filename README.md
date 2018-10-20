# app-config
Default placeholder repository for https://github.com/johnboyes/gs-spring-cloud-config-server

https://github.com/johnboyes/gs-spring-cloud-config-server is setup to have one github config repository for each application, using a pattern of {application}-config.

The default application name is `app`, so I need this `app-config` repository to ensure that https://gs-spring-cloud-config-server.herokuapp.com/actuator/health shows that the application is healthy (see https://github.com/johnboyes/gs-spring-cloud-config-server/issues/4)
