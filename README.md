# microservices-new
Microservices Spring Boot App.


<div align="center">

![Architecture](architecture.png)

</div>

## Endpoints (plus means it exists, minus it does not)
|endpoint-name|GET|POST|DELETE|
|-|-|-|-|
|/api/order|-|+|-|
|/api/product|+|+|-|
|/api/inventory?skuCode={item}|+|-|-|
