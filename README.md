# E-Commerce platform for electronic products
E-Commerce platform to buy and manage electronic products

## Features
- Functioning login/register service
- Functioning customer shop with local shopping cart persistence
- Functioning product management over RMI 

## Features still missing
- Order table and order logic still missing
- Employee management functions (add employee/remove employee) still missing
- GUI tests missing

# Client information
There is only one employee account (username: "admin", password: "1234"), since registration for employees over a customer client should not be possible, logically.  
Registration is only possible for customers.

## System prerequisites
- System with at least 4GB RAM (for modern operating system requirements)

## Software prerequisites
- At least Java SDK 19 or higher
- A PostgresSQL Server [instructions on the server repository](https://github.com/CyruzSa/electronic-shop-server)
- [Gradle build system](https://gradle.org/)

## Installing / Getting started

Before you start cloning the client repository, you should follow the [server repository instructions](https://github.com/CyruzSa/electronic-shop-server) first.  
Once you finished the server setup, clone the client repository to your desired location.

```shell
git clone git@github.com:CyruzSa/electronic-shop-client.git
```  
Afterwards build the project with Gradle

```shell
./gradlew build
```  
Let the Gradle build system download all the necessary libraries.  
Once the building and indexing is complete, you can run the client.  
```shell
./gradlew run
```
