# eureka-server
Eureka Server (Service Discovery)
Uses Spring Cloud netlflix eureka server and this project can be combined with config-server project(check the other repoistory). fail-fast is set to false to make it run independently. Set fail-fast(check application.yml) to true and run config-server. Eureka server connects to config-server to pull up the configuration during the startup.
