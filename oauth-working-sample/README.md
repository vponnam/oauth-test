## Working sample has the below spring/sso specific dependencies, which can also be found from pom.xml

- spring-boot-starter-web - 2.1.8
- spring-boot-starter-oauth2-client - 2.1.8
- spring-boot-starter-thymeleaf - 2.1.8
- spring-boot-starter-webflux - 2.1.8
- spring-security-oauth2-jose - 5.1.6
- spring-security-config - 5.1.6
- java-cfenv-boot-pivotal-sso - 1.1.1

Things to consider:
- Not sure if this mechanism uses the new Spring Security 5.1.x `issuer-uri` feature[1] or still leverages the legacy config endpoints.

References:  
[1] https://spring.io/blog/2018/07/30/spring-security-5-1-0-m2-released#ability-to-create-clientregistration-from-oidc-discovery
