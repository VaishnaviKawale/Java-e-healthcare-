# E-Medical-System-Web-Project-Using-Spring-Boot-Security-JPA-Rest-Thymeleaf-HQL (HMS)
Project on Bio-Medical &amp; Hospital sector which is covering various field of this 3 sector.This project is using Spring Framework, Hibernate, JPA, Rest, JSP also with (Post-Dev Data-Science, Big-data, ML etc. ) [ for Hackathon, CSI &amp; SIH]

# Docker Integration

# Youtube Link : https://youtu.be/bGM6xkhz0cU

[![Build Status](https://travis-ci.org/codecentric/springboot-sample-app.svg?branch=master)](https://travis-ci.org/codecentric/springboot-sample-app)
[![Coverage Status](https://coveralls.io/repos/github/codecentric/springboot-sample-app/badge.svg?branch=master)](https://coveralls.io/github/codecentric/springboot-sample-app?branch=master)
[![License](http://img.shields.io/:license-apache-blue.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)


# Docker deployment 
## Requirements

For building and running the application you need:

- [JDK 1.8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
- [Maven 3](https://maven.apache.org)

## Running the application locally

There are several ways to run a Spring Boot application on your local machine. One way is to execute the `main` method in the `com.medical.SpringMVC` class from your IDE.

Alternatively you can use the [Spring Boot Maven plugin](https://docs.spring.io/spring-boot/docs/current/reference/html/build-tool-plugins-maven-plugin.html) like so:

```shell
mvn spring-boot:run
```

## Deploying the application to OpenShift

The easiest way to deploy the sample application to OpenShift is to use the [OpenShift CLI](https://docs.openshift.org/latest/cli_reference/index.html):

```shell
oc new-app soumyadip007/E-Medical-System-Web-Project-Using-Spring-Boot-Security-MVC-Hibernate-JPA-Rest-Thymeleaf-HQL
```

This will create:

* An ImageStream called "springboot-maven3-centos"
* An ImageStream called "springboot-sample-app"
* A BuildConfig called "springboot-sample-app"
* DeploymentConfig called "springboot-sample-app"
* Service called "springboot-sample-app"

If you want to access the app from outside your OpenShift installation, you have to expose the springboot-sample-app service:

```shell
oc expose springboot-sample-app --hostname=www.example.com
```

![Screenshot 2023-07-19 215413](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/ba6549a9-f751-4915-8166-b409ddfabd5b)


# User Panel :
![Screenshot 2023-07-19 215428](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/2941f062-e892-497a-9228-f398ffca4af6)
![Screenshot 2023-07-19 215444](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/e2011d4e-0997-4dab-844b-bf2703833ab8)
![Screenshot 2023-07-19 215455](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/b1b05e3d-cdc7-46fe-b9eb-53b6c28acce6)
![Screenshot 2023-07-19 215505](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/8ba828c3-c1e9-4b7b-b487-3ef61c9c9e19)
![Screenshot 2023-07-19 215515](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/588cc6dc-a84a-416a-b5d4-ebfbdb45e2e9)
![Screenshot 2023-07-19 215523](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/d8fb05d9-901a-4dc4-a2a3-24f709a90479)
![Screenshot 2023-07-19 215531](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/641e3195-e2bd-44c4-ad53-516a128bc0b6)
![Screenshot 2023-07-19 215539](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/20c63ab9-dfca-482d-a124-48515747442a)
![Screenshot 2023-07-19 215547](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/c361df0c-b321-4f98-8995-069f46cee4ae)
![Screenshot 2023-07-19 215554](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/b7a6865e-e9b1-4346-8904-b5fc05ed558d)
![Screenshot 2023-07-19 215602](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/51cb7d02-30e8-402e-857d-34a3db51ee9d)




# Doctor Panel (Dashboard Access):
![Screenshot 2023-07-19 220301](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/48ee2e80-75e1-467f-9fac-966ee501447e)

![Screenshot 2023-07-19 220312](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/5e5ef265-cc58-4fa2-b847-de1acf5c2065)



# Master Admin Panel (Dashboard Access):
![Screenshot 2023-07-19 220418](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/3c59ab23-1a4a-405d-9000-5a2f8142aa16)
![Screenshot 2023-07-19 220427](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/2c8f1951-85e4-4fe0-a4db-5819b98dc8f9)
![Screenshot 2023-07-19 220435](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/ca9c2049-1e23-4524-a8d8-60c4eeb32220)
![Screenshot 2023-07-19 220442](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/eb434cd1-b893-4bd7-b015-5b562d593601)

![Screenshot 2023-07-19 220450](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/82231efd-30f3-403d-acdd-092549a7a818)
![Screenshot 2023-07-19 220457](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/4e8a1250-465e-48af-8f99-9cc902f999d1)
![Screenshot 2023-07-19 220503](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/3720bfe3-840e-4ed8-adcf-3b1a5384c213)
![Screenshot 2023-07-19 220510](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/c0d3faae-5ac0-4efc-b58c-49afa6cf6daf)
![Screenshot 2023-07-19 220520](https://github.com/VaishnaviKawale/Java-e-healthcare-/assets/116081386/3dd0106c-943a-42cf-9aac-07491ef34a8c)


