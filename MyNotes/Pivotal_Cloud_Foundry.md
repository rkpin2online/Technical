## Cloud services features
* Elasticity
* Metered
* Quick provisioning
* Mulitcloud PAAS
* Insdustry standard
* Opens ource
* Built by VMware

### 3 kinds of services 
* IAAS
* PAAS
* SAAS

### PAAS
* Cloud computing model
* Third party delivers hardware/software required for application development
* You manage - Application, Data
* They manage - Runtime, middleware, OS, virtualization, Servers, Storage, Networking
* Application deployment available over internet

### Need for cloudd foundry
* Capable of deploying application on any infrastructure
* Rest API to simplify operations of applications - 
                * Deployment
                * Scale up
                * Scale downn
* Supports multiple programming languages - java, ruby, python
* Reliable platform for delivering micrpservices
* Follow devops principle
                * CI
                * CD
                * Faster availability
### Cloud foundry Features 
 * Integration with cloud providers
 * protability
 * autoscaling
 * centralized administration        
 * dynamic routing
 * Health monitoring system

### Cloud foundry components
* Router - maintains table to keep track of the apps deployed
* User account authentication (UAA)- OAuth2 server
* Cloud controller - brain of the system, managing the entire task and lifecycle of app
* nsync
* cell reps
* BBS
* Consul
* Service brokers
* Log aggregator
* Metric collector
* Diego cell - communicates with cloud controler
* Blobstore

### ORG and SPACES of Cloud foundry
* Organization
                * First step towards using CF
                * Dev account
                *represents org account
                * groups together
                * Resources, application, user, environments
* Spaces
                * ORG divided into spaces
                * represens silo app development
                * spaces have their own quota
* ORG ans Spaces manages the scope of functional domain

### Commands
* Creating users -- cf create-user user1 pass1
* Creating admin users -- 
                * install the cli
                * uaac user add user1 -p pass1 -- empails abc@fds.com
* cf orgs  -- 
* cf org-users org_name
* cf set-org-role user org-name role
* cf unset-org-role user org-name role
* cf spaces -- 
* cf space-users space_name
* cf set-space-role user space-name role
* cf unset-space-role user space-name role
## Note

* Cloud foundry only accepts binary on other hand openshift allows to deploy using git url also
* Four build packs are standard- java, ruby, node.js, Go. For others get from git url
* 

## Q  &  A
* push command if there are multiple org and spaces 
  * Gives option to select among multiple/org/spaces

* How to create the job in PCF which is under Tasks section in PCF dashboard
