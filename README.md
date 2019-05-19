# Authentication and Security in gRPC Microservices Examples

A collection of simple examples to accompany the "Authentication and Security in gRPC Microservices Examples"
talk.

https://kccnceu19.sched.com/event/MPbC

Talk Slides: TBD

Full talk video: TBD


## Prework

This examples have been setup on Google Kubernetes Engines, but they should work on any other kubernetes cluster (public or private).

1. Create a demo GKE cluster https://cloud.google.com/kubernetes-engine/docs/how-to/creating-a-container-cluster
   and set up the `gcloud` to make it the default cluster.
2. Make sure you can use the `kubectl` command line tool by following: https://cloud.google.com/kubernetes-engine/docs/quickstart

## Build the docker images

Build the docker images and push them to container registry so that we can later deploy them in
our kubernetes cluster.

```
$ kubernetes/docker_build_and_push.sh
```


## Example 1: Connect securely using TLS

TODO: add commands to run


## Example 2: Authenticate request with a JWT token

TODO: add commands to run


## Example 3: Mutual TLS with manually provided certificates

TODO: add commands to run


## Example 4: Mutual TLS with istio and automated key rotation 

gRPC client and server are using insecure channels and trust the proxy to perform mutual authentication on their behalf.

TODO: add commands to run


## Contents

- `kubernetes`: configuration for running examples on Kubernetes
