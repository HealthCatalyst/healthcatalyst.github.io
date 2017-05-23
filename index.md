## Welcome

Fabric is a set of micro-services for healthcare.  You can pick and choose only the services you want and install them via docker.

### What do you need?

#### I need to add authentication
[Fabric.Identity](https://github.com/HealthCatalyst/Fabric.Identity)


``curl -sSL https://healthcatalyst.github.io/InstallScripts/installidentityandauthorization.txt | sh``

#### I need to manage permissions for my app
[Fabric.Authorization](https://github.com/HealthCatalyst/Fabric.Authorization)

``curl -sSL https://healthcatalyst.github.io/InstallScripts/installidentityandauthorization.txt | sh``

#### I need to run Machine Learning Models easily
[Fabric.MachineLearning](https://github.com/HealthCatalyst/Fabric.MachineLearning)

``curl -sSL https://healthcatalyst.github.io/InstallScripts/installmachinelearning.txt | sh -s <username> <domain>``

#### I need to render HTML inside an EHR workspace
[Fabric.EHR](https://github.com/HealthCatalyst/Fabric.EHR)


[Fabric.TestEHR](https://github.com/HealthCatalyst/Fabric.TestEHR)

#### I need a data service that speaks FHIR
[Fabric.FHIR](https://github.com/HealthCatalyst/Fabric.FHIR)

#### I need a tool to automatically move data from my Sql Server to ElasticSearch
[Fabric.Databus](https://github.com/HealthCatalyst/Fabric.Databus)


``curl -sSL https://healthcatalyst.github.io/InstallScripts/installfabricdatabus.txt | sh``

#### I need a base docker image that has all the tools included to authenticate with Microsoft ActiveDirectory
[Fabric.BaseOS](https://github.com/HealthCatalyst/Fabric.BaseOS)

[On Docker Hub](https://hub.docker.com/r/healthcatalyst/fabric.baseos)

#### I need a simple way to run an ElasticSearch & Kibana cluster
[Fabric.ElasticSearch](https://github.com/HealthCatalyst/Fabric.ElasticSearch)

``curl -sSL https://healthcatalyst.github.io/InstallScripts/installelasticsearch.txt | sh -s <ip1> <ip2> <ip3>``

(More coming soon)
