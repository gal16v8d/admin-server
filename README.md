# admin-server

# Getting Started

Check this as reference: https://www.tutorialspoint.com/spring_boot/spring_boot_admin_server.htm

### Pre-requisites

* Maven 3
* Java 17

### Docker Image

- In the project dir, build using the command:

```bash
docker build -t gsdd-eureka-server .
```

- Run the docker image as:

```bash
docker run -d -p 8761:8761 gsdd-admin-server
```