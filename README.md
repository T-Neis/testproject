# My Microservices Project

## Description

This project demonstrates a microservices architecture using Spring Boot. It consists of three services: an Authorization Server (UAA), an API Key Auth Provider, and a Resource Server.

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/T-Neis/testproject.git
   cd testproject
   ```

2. Ensure you have JDK 17 and Gradle installed.

## Build and Run Instructions

1. Build the project:

   ```bash
   ./gradlew build
   ```

2. Start the UAA server:

   ```bash
   ./gradlew :uaa-server:bootRun
   ```

3. Start the API key auth provider:

   ```bash
   ./gradlew :apikey-auth-provider:bootRun
   ```

4. Start the resource server:

   ```bash
   ./gradlew :resource-server:bootRun
   ```

## Endpoints

### Resource Server

- `GET /test`: Returns "Access granted!" if authenticated.

## Technologies Used

- Spring Boot
- Spring Security
- Spring Authorization Server
- OAuth2
- JWT
- Gradle
