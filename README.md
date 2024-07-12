# foundation

The goal with this project, was to roll my own basic API gateway layer between frontend and backend services.  Ultimately, I like having an API Gateway layer because this can also have built into it, the responsibility of checking which containers are available in the cluster, and connect them (This is not how it's currently configured, but that is the long term goal as a POC)

K8S Cluster

Container Services:
- Web Frontend
- API Gateway
- Platform Backend Service

*Network Setup*

Client -> API Gateway <-> Platform

**Technologies**

Client & API Gateway:

- Docker
- Kubernetes
- Node.js
- Hapi.js Framework
- SQLITE (using MikroORM)
- Redux
- React - Frontend UI
- Typescript
- MikroORM

Backend: 

- LAMP (Ubuntu, Apache2, MariaDB, PHP 7.1)
- Laravel 5.6 MVC Framework
- Vue/x - Frontend UI
