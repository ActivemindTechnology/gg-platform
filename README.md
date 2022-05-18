# GameGolf Platform v2
The project will be used to develop the new platform infrastructure and application architectures.

## GG Applications and Services
- [Smart Caddie](/docs/development/SMARTCADDIE.md) - 
- [Club Performance](/docs/development/CLUBPERFORMANCE.md)
- [Geofencing Tool](/docs/development/GEOFENCINGTOOL.md)
- [Notifications Worker](/docs/development/NOTIFICATIONWORKER.md)
- [Web API](/docs/development/WEBAPI.md)
- [Game Processing Engine](/docs/development/GAMEPROCESSINGENGINE.md)

## Architecture
![GG Platform Application Services](/docs/images/readme/GameGolfApplicationArchitecture.png?raw=true)
### Directory Structure
- Apps dir contains Helm releases with a custom configuration per cluster.
- Infrastructure dir contains common infra tools such as NGINX ingress controller and Helm repository definitions.
- Clusters dir contains the Flux configuration per cluster.
- Docs for more in depth design and development documentation.

```
├── apps  
│   ├── base  
│   │   ├── club-performance  
│   │   ├── game-processing  
│   │   ├── geofencing-tool  
│   │   ├── notification-workers  
│   │   └── smart-caddie  
│   │ 
│   └── clusters  
│       ├── dev-test  
│       └── stage-prod  
├── docs  
│   ├── deployment  
│   ├── design  
│   ├── developer  
│   ├── development 
│   └── images 
│
├── infrastructure  
│   ├── nginx  
│   ├── postgres  
│   ├── rabbitmq  
│   ├── starboard  
│   └── dapr
│    
└── clusters  
    ├── base  
    └── environments  
        ├── dev-test  
        └── stage-prod  
```

### Project Status
# Project Status

![devops-ci Actions Status](https://github.com/mcknight-joe/gg-platform/actions/workflows/devops-ci.yaml/badge.svg)

[![GG Platform Stats](https://github-readme-stats.vercel.app/api?username=mcknight-joe&theme=dark)](https://github.com/ActivemindTechnology/gg-platform)


### GG System Services - Application & Others


### Tools and utilities
https://fluxcd.io/docs/  
https://kind.sigs.k8s.io/docs/user/quick-start/  


### 3rd party libraries


