---
title: Release management
layout: home
nav_order: 5
---

# Release management

## LDES Server

### Versions:

* Latest Official version: [![Docker Image Version](https://img.shields.io/docker/v/openldes/ldes-server/latest)](https://hub.docker.com/r/openldes/ldes-server/tags)
* Latest Alpha version: [![Docker Image Version](https://img.shields.io/docker/v/openldes/ldes-server)](https://hub.docker.com/r/openldes/ldes-server/tags)

Go to the [LDES Server Github Releases](https://github.com/OpenLDES/LDESServer/releases/) for all the releases.

## Linked Data Interactions

The Linked Data Interactions Repo (LDI) is a bundle of basic SDKs used to receive, generate, transform and output Linked Data. This project is set up in the context of the OpenLDES Project to ease adopting LDES on data consumer and producer side.

Go to the [LDI Github Releases](https://github.com/OpenLDES/Linked-Data-Interactions/releases/) for all the releases.

### Linked Data Interactions Orchestrator (LDIO)

The Linked Data Interactions Orchestrator is built to be a lightweight Linked Data pipeline framework.

For more detail on how to use the LDIO, please visit the [LDIO Documentation](https://openldes.github.io/Linked-Data-Interactions/latest/).

#### Versions:

* Latest Official version: [![Docker Image Version](https://img.shields.io/docker/v/openldes/ldi-orchestrator/latest)](https://hub.docker.com/r/openldes/ldi-orchestrator/tags)
* Latest Alpha version: [![Docker Image Version](https://img.shields.io/docker/v/openldes/ldi-orchestrator)](https://hub.docker.com/r/openldes/ldi-orchestrator/tags)

### Linked Data Interactions for Apache NiFi

To also support existing users of Apache NiFi, all LDI components have been made available as NiFi component.
For that, a specially bundled NiFi Docker image is available.

Documentation on how to use the individual Processors can be found in the in-app documentation and on [the LDI NiFi docs](https://openldes.github.io/Linked-Data-Interactions/latest/ldi-nifi).

#### Versions:

* Latest Official version: [![Docker Image Version](https://img.shields.io/docker/v/openldes/ldi-workbench-nifi/latest)](https://hub.docker.com/r/openldes/ldi-workbench-nifi/tags)
* Latest Alpha version: [![Docker Image Version](https://img.shields.io/docker/v/openldes/ldi-workbench-nifi)](https://hub.docker.com/r/openldes/ldi-workbench-nifi/tags)


## Which version should I use?

* As a general recommendation, the **official release** is the goto version to use. This is the ideal version to use on Production.
* The **alpha/snapshot versions** available on dockerhub provide a certain stability, but have not been internally validated on specification compliance. These versions can be used for non-production environments (test/acceptance/...)
* The images found on **GitHub** itself should not be used for anything other than testing, they are prone to changes and do not come with any support.

## Notification of new releases

To get informed when a new version of a building block is released, go to 'watch'.
On the [notifications](https://github.com/notifications) page, you can see your personal notification subscribtions
