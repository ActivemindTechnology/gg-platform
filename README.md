# GameGolf Platform v2
The project will be used to develop the new platform infrastructure and application architectures.

## GG Applications and Services


## Architecture
![GG Platform Application Services](/docs/images/readme/GameGolfApplicationArchitecture.png?raw=true)
### Directory Structure
- Apps dir contains Helm releases with a custom configuration per cluster.
- Infrastructure dir contains common infra tools such as NGINX ingress controller and Helm repository definitions.
- Clusters dir contains the Flux configuration per cluster.
- Docs for more in depth design and development documentation.

├── apps  
│   ├── base  
│   ├── production  
│   └── staging  
├── docs  
|   ├── design  
|   ├── developer  
|   ├── development 
|   ├── images 
├── infrastructure  
│   ├── base  
│   ├── production  
│   └── staging  
└── clusters  
    ├── development  
    ├── production  
    ├── staging  
    └── test  


### Project Status

### GG System Services - Application & Others


### Tools and utilities
https://fluxcd.io/docs/  
https://kind.sigs.k8s.io/docs/user/quick-start/  


### 3rd party libraries


