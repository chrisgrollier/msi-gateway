# Basic application gateway [![Build Status](https://travis-ci.org/chrisgrollier/msi-gateway.svg?branch=master)](https://travis-ci.org/chrisgrollier/msi-gateway)

Provides a default and basic pre-configured application gateway.

## Pre-configuration

Pre-configured items are:

- auto register with eureka client to a registry server
- route to registered applications auto discovery through the registry server
- route naming in lowercase
- config server auto discovery through the registry server

For more information about spring cloud config gateway, please check its reference documentation page at https://cloud.spring.io/spring-cloud-gateway/reference/html/
