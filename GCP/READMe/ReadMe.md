# GCP Assignment

GCP assignment_Tingyue He

# Visit locally

Deployed on [http://localhost:8080](http://localhost:8080).

Also deployed on [https://crucial-study-401302.de.r.appspot.com](https://crucial-study-401302.de.r.appspot.com). Please wait for 1.5 minutes for the server to start for the first time deploying.

# Framework and Tools Used

| Components |         Technology         |
| :--------- | :------------------------: |
| Frontend   |             no             |
| Backend    | Spring Boot 2.7.5, Java 11 |

# Option 1: Build and Run

## Option 1.1: Build jar

### Prerequisite Installation

- springboot 3.1.4
- Java 11

#### Build jar and Run

Navigate to the project root directory and execute the following e.g. 8080.

```
mvn clean install
./mvnw spring-boot:run
```

### Local Result:

localhost:8080/username
-> the79
localhost:8080/localtime
-> localtime(show up)

### Deploy

Navigate to the project root directory and execute the following:
mvn clean install -> to compile the setup environment
gcloud app browse -> open the correct browse that we try to deploy

```

```
