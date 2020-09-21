---
description: "Docker is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers"
title: Docker
weight: 1
---

Learning road map for Docker

## Basics
### Instances
- `docker run` command
- Managing volumes
- Creating docker network
- Creating, tagging, publishing own image from `Dockerfile`

## Intermediate

### Images
- Interpretation of `docker inspect`

### Instances
- Create docker swarm
- Create stack of services
- Manage number of replicas

### Tools
- Managing multiple services with docker-compose
  - All services can communicate, but only one is entry point from outside

### Networking
- Know different network drivers

## Expert
- Manage own docker repository

### Instances
- Apply and make use of labels

#### Security
- Produce signed images
- Default docker engine security
- Swarm security
- Use namespaces and cgroups

### Logging
- Configure different logging drivers