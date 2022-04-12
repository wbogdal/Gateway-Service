# Exchange-Service
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Examples](#setup)
* [Author](#author)


## General info
This project is simple gateway service which proxy request into exchange service which is available on link below:
https://github.com/wbogdal/Exchange-Service
	
## Technologies
Project is created with:
* Spring Boot
* Java 11
* Netflix Zuul
	
## Setup
To build this project execute:

* git clone https://github.com/wbogdal/Gateway-Service.git
* cd gatewayservice
* mvn install

then to run execute:

* cd target
* java -jar gateway-service-0.0.1-SNAPSHOT.jar

Please remember to run as well the exchange service.

## Examples
* Example link to get exchanged currency
http://localhost:8088/currencies/exchange/123/EUR/PLN

* Example json with response
{
    "amount": 573.566097,
    "currency": "PLN"
}

Please note that provided free api key can only handle 300 request per month. You can get your free api key here - https://currencyapi.com/

## Author
* Wojciech Bogdał
