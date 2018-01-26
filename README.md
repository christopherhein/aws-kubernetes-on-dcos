# Kubernetes on DC/OS on AWS

This repository features a sample application, and a couple shell scripts to
help you deploy Kubernetes on DC/OS on top of AWS making use of the
`--cloud-provider` flag which enables Kubernetes to provision AWS resources from
within the DC/OS cluster. Most commonly this means being able to expose services
to the outside world using `type: LoadBalancer` or auto provisioning of Elastic
Block Store volumes.


