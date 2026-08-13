# Java Jenkins Demo — Spring PetClinic

A Jenkins CI/CD demo using the [Spring Framework PetClinic](https://github.com/spring-petclinic/spring-framework-petclinic) sample application.

## Running locally

```bash
./mvnw jetty:run-war
```

Then open http://localhost:8080/

## Building

```bash
./mvnw clean package
```

## Jenkins Pipeline

A `Jenkinsfile` is included at the root of the repository with stages for Checkout, Build, Test, and Package.
