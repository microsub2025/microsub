# Structure and Use case-based Approach to Migrating Monolithic Applications into Microservices

## Subject web apps
|Web app|Description|Technologies|
|---|---|---|
|[JPetStore2](https://github.com/KimJongSung/jPetStore)|Online pet store|Spring, MyBatis|
|[JPetStore6](https://github.com/mybatis/jpetstore-6)|Online pet store|Spring, Stripes, MyBatis|
|[PetClinic](https://github.com/spring-projects/spring-petclinic)|Pet and veterinarian management system|SpringBoot, Thymeleaf, Spring Data JPA|
|[ShoppingApp](https://github.com/manhduydl/Shopping-web-Jsp-Servlet)|Online clothing store|JSP Model 2, JDBC|
|[DayTrader](https://github.com/WASdev/sample.daytrader7)|Online stock trading system|JSP Model 2, JavaServer Faces, JDBC, EJB|

# Ground truths & Baselines
To evaluate the proposed method, ground truths are required. In this study, we utilized the ground truths provided by the study [[1](#reference)]. These ground truths can be found at the following link.
(https://github.com/microdvi/MicroDVI/tree/main/Ground%20truths)

The proposed method is compared with
the five baselines: 
1) **MEM** 
    + [Frontend](https://github.com/gmazlami/microserviceExtraction-frontend)
    + [Backend](https://github.com/gmazlami/microserviceExtraction-backend)
2) [Bunch](https://github.com/ArchitectingSoftware/Bunch)
3) [Mono2Micro](https://github.com/rahlk/ASE21-Tutorial)
4) UseCaseExec
    + S.-H Kim, D. Jung, N. Mohd Ali, A. B. Md Sultan, and J. Oh, "Microservice identification by partitioning monolithic web applications based on use-cases," J. Inf. Commun. Converg. Eng., vol. 21, no. 4, pp.268-280, 2023
5) Study [[1](#reference)]

MEM, Bunch, and Mono2Micro are the same as those used in the study [[1](#Reference)]. The results of these baselines are available at the following link. (https://github.com/microdvi/MicroDVI/tree/main/Baselines)

# Project structure

## Web app graphs
This folder contains the web app graphs used by the proposed approach.

## Use case descriptions
This folder includes the use case descriptions derived from the experimental web apps.

## Results
Experimental results used in the Evaluation section are provided in Results folder.

# Reference
[1] S. H. Kim and J. Oh, "Migrating Monolithic Web Applications to Microservice
Architectures Considering Dependencies on Databases and Views," ***In proceedings of the 40th ACM/SIGAPP Symposium On Applied Computing***, 2025.