# RAG Document Summariser Demo

### Provisioning ARO

01. Provision an 'Azure with ARO Open Environment (Subscription Based)' ([ARO](https://demo.redhat.com/catalog?search=aro&item=babylon-catalog-prod%2Fazure-gpte.open-environment-aro4-sub.prod)) on 'demo.redhat.com'

### Deploying HTML Frontend

faruq to add

### Deploying Services

02. Deploy services on ARO by deploying the following images:
    * ChromaDB server: docker.io/faruqzafir/test1:v1
    * HTML frontend: docker.io/rach228/flowise-webserver:v3
        * Ensure container is exposed at port 8080
    * Flowise chatflow: docker.io/rach228/flowise-chatflow:1.2

### Building Chatflow on Flowise

![](chatflow_sample.jpg)
