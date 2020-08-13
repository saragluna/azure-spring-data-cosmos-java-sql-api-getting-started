# Project Name

Azure Spring Data Cosmos getting started tutorial.

## Features

This tutorial provides getting started features for `azure-spring-data-2-2-cosmos` and `azure-spring-data-2-3-cosmos` modules

## Getting Started

### Prerequisites

- Java Development Kit 8
- An active Azure account. If you don't have one, you can sign up for a [free account](https://azure.microsoft.com/free/). Alternatively, you can use the [Azure Cosmos DB Emulator](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator) for development and testing. As emulator https certificate is self signed, you need to import its certificate to java trusted cert store, [explained here](https://docs.microsoft.com/en-us/azure/cosmos-db/local-emulator-export-ssl-certificates)
- (Optional) SLF4J is a logging facade.
- (Optional) [SLF4J binding](http://www.slf4j.org/manual.html) is used to associate a specific logging framework with SLF4J.
- (Optional) Maven

SLF4J is only needed if you plan to use logging, please also download an SLF4J binding which will link the SLF4J API with the logging implementation of your choice. See the [SLF4J user manual](http://www.slf4j.org/manual.html) for more information.

### Installation

mvn clean install

### Quickstart

1. git clone https://github.com/Azure-Samples/azure-spring-data-cosmos-java-getting-started.git
2. cd azure-spring-data-cosmos-java-getting-started
3. cd azure-spring-data-2-2-cosmos-java-getting-started (for `azure-spring-data-2-2-cosmos`) or azure-spring-data-2-3-cosmos-java-getting-started (for `azure-spring-data-2-3-cosmos`)
4. mvn spring-boot:run

## Resources

Please refer the [source code](https://github.com/Azure/azure-sdk-for-java/tree/master/sdk/cosmos) for more information.
