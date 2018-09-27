# Why Containers?

Containerization is an approach to software development in which an application or service, its dependencies, and its configuration (abstracted as deployment manifest files) are packaged together as a container image. 
The containerized application can be tested as a unit and deployed as a container image instance to the host operating system (OS).

Just as shipping containers allow goods to be transported by ship, train, or truck regardless of the cargo inside, software containers act as a standard unit of software deployment that can contain different code and dependencies. Containerizing software this way enables developers and IT professionals to deploy them across environments with little or no modification.

Containers also isolate applications from each other on a shared OS. Containerized applications run on top of a container host that in turn runs on the OS (Linux or Windows). Containers therefore have a significantly smaller footprint than virtual machine (VM) images.

Another benefit of containerization is scalability. You can scale out quickly by creating new containers for short-term tasks. From an application point of view, instantiating an image (creating a container) is similar to instantiating a process like a service or web app. For reliability, however, when you run multiple instances of the same image across multiple host servers, you typically want each container (image instance) to run in a different host server or VM in different fault domains.

In short, containers offer the benefits of isolation, portability, agility, scalability, and control across the whole application lifecycle workflow. The most important benefit is the environment's isolation provided between Dev and Ops

# Containers Four Ways in Azure
In this lab, we will showcase how to deploy containers in Azure four ways:
1. [App Service](https://azure.microsoft.com/en-us/services/app-service/) 
2. [Service Fabric](https://azure.microsoft.com/en-us/services/service-fabric/)
3. [Azure Kubernetes Service](https://azure.microsoft.com/en-us/free/kubernetes-service/search/?&OCID=AID719825_SEM_LPmbT3sq&lnkd=Google_Azure_Brand&gclid=Cj0KCQjw_7HdBRDPARIsAN_ltcJApFDF6gPnEVs6pjFjKlaAnfwU-qeWywytCzkIbYRe9qUo0p5WiZYaAtJ9EALw_wcB&dclid=CJOeraOT3N0CFVg9TwodhDUJQA)
4. [Azure Container Instances](https://azure.microsoft.com/en-us/services/container-instances/)

# Authors

