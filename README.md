# Digital Wallet Project Readme

Este repositorio contiene el código fuente para el proyecto de Digital Wallet. El proyecto está compuesto por varios microservicios, cada uno ubicado en su propia carpeta dentro de este repositorio. Cada microservicio incluye un archivo `application-documentation.yml` que describe el contrato del servicio, diseñado siguiendo las especificaciones de Swagger con OpenAPI. Además, el proyecto hace uso de varias tecnologías y herramientas de Spring Cloud y Spring Boot, como se detalla a continuación.

## Microservicios

- **wallet-service**: Descripción breve del microservicio de billetera.
- **movement-reactive-service**: Descripción breve del microservicio reactivos de movimientos.
- **transfer-service**: Descripción breve del microservicio de transferencia.
- **authentication-service**: Descripción breve del microservicio de autenticación (login con JWT Bearer Token).
- **deposit-service**: Descripción breve del microservicio de depósito.
- **customer-service**: Descripción breve del microservicio de cliente.

## Contrato del Servicio

Cada microservicio incluye un archivo `application-documentation.yml` que describe el contrato del servicio, detallando los endpoints, parámetros, y respuestas esperadas. Este contrato sigue las especificaciones de Swagger con OpenAPI y se utiliza para documentar y definir la interfaz de cada microservicio.

## Tecnologías y Herramientas Utilizadas

- **Spring Cloud Config Server con Github**: Se utiliza para la gestión centralizada de la configuración de los microservicios, almacenando la configuración en un repositorio en Github.
- **Eureka Server**: Se emplea para el registro y descubrimiento de servicios en la arquitectura de microservicios.
- **API Gateway**: Actúa como punto de entrada único para las solicitudes de clientes y enruta las peticiones a los microservicios correspondientes.
- **Spring Webflux**: Se utiliza para construir aplicaciones web reactivas utilizando el paradigma de programación reactiva.
- **Apache Kafka**: Se emplea como sistema de mensajería distribuida para la comunicación entre microservicios.
- **Kadek**: Herramienta utilizada en conjunto con Apache Kafka para simplificar y mejorar la administración de los mensajes.
- **Descubrimiento de Aplicaciones a través de la DNS de Eureka Server**: Se utiliza Eureka Server para descubrir dinámicamente las ubicaciones de los microservicios en la red.
- **Programación Funcional con Java 17**: Se aprovechan las características de programación funcional introducidas en Java 17.
- **Spring Boot 3**: Framework utilizado para crear microservicios de manera eficiente y escalable.

