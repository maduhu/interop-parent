# interop-parent

The repo contains a project that contains a POM file that contains all the dependencies required for all the interop related projects.

Contents:

- [Deployment](#deployment)
- [Configuration](#configuration)
- [API](#api)
- [Logging](#logging)
- [Tests](#tests)

## Deployment

Project is built using Maven and uses Circle for Continous Integration. 

This is a single pom file that contains the dependencies used/needed by interop-domain, interop-common and other base level interop projects such as interop-spsp-clientproxy

## Configuration

[pom.xml](./pom.xml) and [circle.yml](./circle.yml) can be found in the repo

## API

This repo does not contain an API.

## Logging

The projects does not generate any logs.

## Tests

There are no tests for project as it is a configuration project.