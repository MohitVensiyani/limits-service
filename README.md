# Limits Service

The Limits Service is a Spring Boot microservice that provides configuration limits for applications. It retrieves configuration properties from a centralized configuration server and exposes them via a RESTful API.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Usage](#usage)
- [Building and Running](#building-and-running)
- [Further Enhancements](#further-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Overview

This service is part of a microservices architecture and is designed to demonstrate the use of Spring Boot with Spring Cloud Config Server for centralized configuration management.

## Features

- Retrieves configuration properties from a Spring Cloud Config Server.
- Exposes a REST endpoint to provide configuration limits.
- Supports different profiles for environment-specific configurations.

## Getting Started

### Prerequisites

- Java 17 or later
- Maven 3.6+
- Spring Boot 3.x
- A running instance of Spring Cloud Config Server

### Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/limits-service.git
cd limits-service
