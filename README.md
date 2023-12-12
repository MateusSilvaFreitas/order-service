# Order Service

Welcome to the Order Service of our E-Commerce System. This Java-based microservice manages the entire lifecycle of orders, including tracking order progress from separation to delivery.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Overview

The Order Service is a Java-based microservice that handles order-related functionalities within our e-commerce system. It communicates with other microservices to ensure a seamless shopping experience.

## Prerequisites

Ensure you have the following installed:

- OpenJDK 17
- Apache Maven
- Kafka (for event-driven communication)
- MySQL 8

## Installation

1. Clone the repository.
2. Navigate to the order-service directory.
   ```bash
   cd order-service
   ```
3. Build the project using Maven.
   ```bash
   mvn clean install
   ```

## Usage

1. Set up environment variables for configuration.
   - Check the `.env.example` file for guidance.
   - Create a `.env` file and add the necessary configuration.

2. Start the Order Service.
   ```bash
   java -jar target/order-service.jar
   ```

3. Ensure the Kafka server is running to enable event-driven communication.
