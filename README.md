# configserver-devvault
Config-Server For `DevVault-Microservice` Project.

Configuration for:
- Eureka Client

```yaml
#eureka-client configuration
eureka:
  client:
    fetch-registry: true
    register-with-eureka: true
    service-url:
      defaultZone: ${EUREKA_SERVER_ADDRESS:http://localhost:8761/eureka}
  instance:
    prefer-ip-address: true
```
