# Spotter
#### Concept
Spotter is a distributed hosting platform that allows developers to scale their applications horizontally and cut down on infrastructure costs. The platform is designed to orchestrate the deployment and management of "apps" or microservices across a combination of dedicated and spot instances.

#### Inspired by Potluck, Built at YC Hacks 2014.
Potluck is a distributed hosting platform which is intended to allow applications to scale at the low fixed monthly cost of a micro VPS instance. In order to deploy developers would run a docker image of the Potluck server on a VPS provider such as Amazon EC2 or Google Compute Engine. Developers specify 2 parameters at this time: the git repository the application is hosted in (currently Node only but Ruby support is in the pipes) and an IP of a node in a Potluck cluster. The initial node should be deployed with its own IP. [(Read more...)](README.md)
